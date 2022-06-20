# head-pos-estimation using mediapipe

This work is done with collaboration of my colleague : Ahmed Abdellah --> https://github.com/AhmedAbdellaa

# Output Test Video here

https://youtube.com/shorts/12t8YOLolQk

# Overview

Estimating the head pose of a person is a crucial problem that has a large amount of applications 
such as aiding in gaze estimation, modeling attention, fitting 3D models to video and performing face alignment.

==>Evaluation Metrices

1- R2 Score

2- Mean Squared Error (MSE)

==>MediaPipe Pose

The pipeline is implemented as a MediaPipe graph that uses a pose landmark subgraph from the pose landmark module and renders using a dedicated pose renderer subgraph. 
The pose landmark subgraph internally uses a pose detection subgraph from the pose detection module.

==>Input / Output 

Our method takes as input a single RGB frame from runtime video.
Results : The blue line indicates the direction the subject is facing; the green line for
the downward direction while the red one for the side.

# Model Performance 

==>After all the Attempts on different models
we will know that Support vector Regression (SVR) is the best performer  
==>total r2score for three labels =  82%

