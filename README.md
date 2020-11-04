# CV-Traffic-light-detection
Detect traffic lights in San Diego


# The Dataset

The dataset comes from Kaggle's [LISA Traffic Light Dataset](https://www.kaggle.com/mbornoe/lisa-traffic-light-dataset). It consists of video of 43,007 frames and 113,888 traffic lights annotated. The resolution of each frame is 1280 x 960. The field of view is 66 degrees.

#### The training set

I use the folder `dayTrain` to train the model. This folder contains 13 subfolders (`dayClip1` to `dayClip13`). 

#### Traffic light annotations

The annoation file stores the following information separated by semicolons

*Filename;Annotation tag;Upper left corner X;Upper left corner Y;Lower right corner X;Lower right corner Y;Origin file;Origin frame number;Origin track;Origin track frame number*


