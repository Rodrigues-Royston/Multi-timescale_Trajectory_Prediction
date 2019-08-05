## Abstract
Most existing methods for abnormal activity detection model normal activities present in the training data. Any activity deviating from the learned normal representation is flagged as
anomalous. Typically, these methods are trained at a specific timescale (either a single time-instant or a constant time duration) and are restricted to capture anomalies present only at that
timescale. But abnormal activities can happen at different timescales. For example, jumping is a short term anomaly and loitering is a long term anomaly in a scenario where walking is
considered as a normal activity. Hence, a pre-defined timescale may not be sufficient to capture the wide range of anomalies.

In this thesis we propose a multi-timescale (from small to large) model to capture the temporal
dynamics pertaining to different timescales. Our model is based on 1D-convolutional neural
network and is capable of learning regularity in sequences at multiple time scales. In particular,
the proposed model predicts future and past human pose trajectories for a given input pose
trajectory at different timescales. Prediction errors at all the timescales are considered to
classify an event as anomalous. Our experiments show that the proposed model can capture
anomalies occurring at different timescales. We also show that our method outperforms the
existing methods on challenging public data-sets.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Rodrigues-Royston/Multi-timescale_Trajectory_Prediction/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
