# Pose estimation for animal motion capture

![](videos/DogRun.mp4)


### Used Tools
-[DeepLabCut](https://github.com/DeepLabCut/DeepLabCut) using Python3

## Steps
1. Downloaded the videos to train and analyze
2. Then installed DeepLabcut in my newly created conda environment [(Instructions)](https://github.com/DeepLabCut/DeepLabCut/blob/master/docs/installation.md)
3. First created a new project using DLC [(docs)](https://deeplabcut.github.io/DeepLabCut/docs/intro.html)
4. extracted the frames from the videos to label them
5. Editing the config file i can add the joints/points and skeleton each points
6. Now we label the extracted frames and after labeling we need to check/evaluate the labels
7. We then have to create training dataset to prepare for training (the main directory in above Git is done till this step)
8. we can train in via the CPU and GPU in the local machine or for better representation head over to the Google Colab and follow the path/instructions
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Maski0/Viga-DLC/blob/main/Viga_demo.ipynb)

## Note: There are Branches for After-Training&Evaluate dir and EndResult-withskeletonmesh project dir
-The video with skeleton is in videos folder in the EndResult-withskeletonmesh branch 

