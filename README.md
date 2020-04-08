## Multi-timescale Trajectory Prediction for Abnormal Human Activity Detection
This repository will contain the implementation of the approach described in the paper,  
```markdown
@InProceedings{Rodrigues_2020_WACV,
author = {Rodrigues, Royston and Bhargava, Neha and Velmurugan, Rajbabu and Chaudhuri, Subhasis},
title = {Multi-timescale Trajectory Prediction for Abnormal Human Activity Detection},
booktitle = {The IEEE Winter Conference on Applications of Computer Vision (WACV)},
month = {March},
year = {2020}
} 
```


Our newly proposed dataset is now available for download. Kindly, contact me at royston.rodrigues@protonmail.com to request for a download link. Please cite our paper if you find our work or dataset useful for your research.

## Project Updates
- **08/04/2020** : Download information for IITB-Corridor dataset is on this webpage
- **14/12/2019** : IITB-Corridor dataset is now available for download
- **10/12/2019** : This work has been accepted at WACV 2020
- **16/08/2019** : Initial project page online
- **12/08/2019** : Paper now on ArXiv

### Trajectory Predicition for Normal Samples
The proposed model can predict future human pose trajectories successfully for normal pedestrian activities. (Please reload the webpage if the gif files don’t appear in synchronization)  

|![GitHub Logo](/result_gifs/normal_01.gif) |![GitHub Logo](/result_gifs/normal_02.gif) |
|:--:|:--:|
|Video Frames|Input Trajectory, Our Predicition|
|![GitHub Logo](/result_gifs/normal_03.gif) |![GitHub Logo](/result_gifs/normal_04.gif) |
|Input Trajectory, Ground Truth|Input Trajectory, Ground Truth, Our Predicition|

### Trajectory Predicition for Abnormal Samples
The proposed model generates large deviations for the prediction of human pose trajectories corresponding to abnormal activities. (Please reload the webpage if the gif files don’t appear in synchronization)

|![GitHub Logo](/result_gifs/abnormal_01.gif) |![GitHub Logo](/result_gifs/abnormal_02.gif) |
|:--:|:--:|
|Video Frames|Input Trajectory, Our Predicition|
|![GitHub Logo](/result_gifs/abnormal_03.gif) |![GitHub Logo](/result_gifs/abnormal_04.gif) |
|Input Trajectory, Ground Truth|Input Trajectory, Ground Truth, Our Predicition|

### IITB-Corridor Dataset
In order to benchmark existing techniques for the task of abnormal activity detection we introduce a new data-set, which consists of group activities such as protest, chasing, fighting, sudden running as well as single person activities such as hiding face, loitering, unattended baggage, carrying a suspicious object and cycling (in a pedestrian area). We believe such a dataset will motivate investigations for human activity analysis to consider single human or multi-human interaction. We name it the IITB-Corridor dataset. IITB-Corridor is a large scale surveillance dataset with 4,83,566 frames and will be made available for free for research purpose.




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

### Download Information for IITB-Corridor  Dataset 

IITB-Corridor Dataset Download Link :-

1.) Train Set :- https://drive.google.com/file/d/1HZZjINXIgWnq1FYuVTTBsfJiWsXy1uU5/view?usp=sharing

2.) Test Set :- https://drive.google.com/open?id=1F0m6kRcVKAvDIhGLgOY4QJ-oFdTmkzPI

Password for both the files : tb7bdEZE


Please note, this dataset is made available for research purposes only. 

### Results
To compare with existing approaches, we use frame level AUC as the evaluating criteria. Our proposed model outperforms existing methods. The comparison is given in the below table.

|Method|HR-Avenue|HR-ShanghaiTech|ShanghaiTech|IITB-Corridor|
|:--:|:--:|:--:|:--:|:--:|
|Liu et al. (CVPR-18)|86.20|72.70|72.80|64.65|
|Morais et al. (CVPR-19)|86.30|75.40|73.40|64.27|
|**Ours**|**88.33**|**77.04**|**76.03**|**67.12**|

### Contact

Feel free to contact me at royston.rodrigues@protonmail.com for queries regarding this work.
