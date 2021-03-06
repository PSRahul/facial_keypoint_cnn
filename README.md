# Facial Keypoint Detector 

This deep learning model based on convolutional neural networks detects left eye, right eye and mouth from a image of a face.

The model has 7 Convolutional layers and 3 Linear layers implemented with Pytorch.

## Metrics and Optimizer
Loss Function -  MSELoss     
Optimiser-   Adagrad 

## Dataset 
Trained Using dataset from Kaggle
https://www.kaggle.com/c/facial-keypoints-detection/data 

Sample images provide model predictions versus  the true values.

![](sample1.png)            | ![](sample4.png)
:-------------------------:|:-------------------------:
![](sample2.png)  | ![](sample3.png)

## Future Possible Work
1. Augment train dataset with manual labelling of keypoints   
2. Using advanced layers such as skip and residual nets.
