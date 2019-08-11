## Multi-timescale Trajectory Prediction for Abnormal Human Activity Detection
This repository will contain the implementation of the approach described in the paper, 
```markdown

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

![Image] https://rodrigues-royston.github.io/Multi-timescale_Trajectory_Prediction/dataset_gifs/protest.gif 
![useful image](/dataset_gifs/protest.gif)
image: Multi-timescale_Trajectory_Prediction/dataset_gifs/protest.gif
```



Our newly proposed dataset will be made available here soon. Please cite our paper if you find our work or dataset useful for your research.

### Trajectory Predicition for Normal Samples
The proposed model is able to predicit future human pose trajectories sucessfuly for normal pedestrain activities. 
(Please reload the webpage if the gif files don't appear in synchronization)

|![GitHub Logo](/result_gifs/normal_01.gif) |![GitHub Logo](/result_gifs/normal_02.gif) |
|:--:|:--:|
|Video Frames|Input Trajectory, Our Predicition|
|![GitHub Logo](/result_gifs/normal_03.gif) |![GitHub Logo](/result_gifs/normal_04.gif) |
|Input Trajectory, Ground Truth|Input Trajectory, Ground Truth, Our Predicition|

### Trajectory Predicition for Abnormal Samples
The proposed model generates large deviations for prediciton of human pose trajectories corresponding to abnormal activities. (Please reload the webpage if the gif files don’t appear in synchronization) 

|![GitHub Logo](/result_gifs/abnormal_01.gif) |![GitHub Logo](/result_gifs/abnormal_02.gif) |
|:--:|:--:|
|Video Frames|Input Trajectory, Our Predicition|
|![GitHub Logo](/result_gifs/abnormal_03.gif) |![GitHub Logo](/result_gifs/abnormal_04.gif) |
|Input Trajectory, Ground Truth|Input Trajectory, Ground Truth, Our Predicition|

### Corridore Dataset
In order to benchmark existing techniques for the task of abnormal activity detection we introduce a new data-set, which consists of group activities such as protest, chasing, fighting, sudden running as well as single person activities such as hiding face, loitering, unattended baggage, carrying a suspicious object and cycling (in a pedestrian area). We believe such a
dataset will motivate investigations for human activity analysis to consider single human or multi-human interaction. We name it the Corridor dataset. The Corridor is a large scale surveillance dataset with 4,83,566 frames and will be made available for free for research purpose.



|![GitHub Logo](/iitb_imgs/small_protest.jpg) |![GitHub Logo](/iitb_imgs/small_running.jpg) |![GitHub Logo](/iitb_imgs/small_fighting.jpg) |
|:--:|:--:|:--:|
|*Protest*|*Sudden Running*|*Fighting*|

|![GitHub Logo](/iitb_imgs/small_unattended.jpg) |![GitHub Logo](/iitb_imgs/small_chasing.jpg) |![GitHub Logo](/iitb_imgs/small_suspicious.jpg) |
|:--:|:--:|:--:|
|*Unattended Baggage*|*Chasing*|*Suspicious Object*|

|![GitHub Logo](/iitb_imgs/small_hiding.jpg) |![GitHub Logo](/iitb_imgs/small_playing.jpg) |![GitHub Logo](/iitb_imgs/small_loitering.jpg) |
|:--:|:--:|:--:|
|*Hiding Face*|*Playing with Ball*|*Loitering*|

|![GitHub Logo](/iitb_imgs/small_cycling.jpg) |![GitHub Logo](/iitb_imgs/small_normal.jpg) |![GitHub Logo](/iitb_imgs/small_normal_2.jpg) |
|:--:|:--:|:--:|
|*Cycling*|*Standing*|*Walking*|

### Results
To compare with existing approaches, we use frame level AUC as the evaluating criteria. Our proposed model outperforms existing methods. 
The comparison is given in the below table. 

|Method|HR-Avenue|HR-ShanghaiTech|ShanghaiTech|Corridore|
|:--:|:--:|:--:|:--:|:--:|
|Liu et al. (CVPR-18)|86.20|72.70|72.80|64.65|
|Morais et al. (CVPR-19)|86.30|75.40|73.40|64.27|
|**Ours**|**88.33**|**77.04**|**76.03**|**67.12**|

### Contact

Feel free to contact me at royston.rodrigues@protonmail.com for quires regarding this work.
