# Face-Recognition-using-PCA

## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [Goal](#goal)
  * [Technical Aspect](#technical-aspect)
  * [Technologies Used](#technologies-used)
  * [Results](#results)

## Demo
![image](https://github.com/Sagnick0907/Face-Recognition-using-PCA/assets/76872499/7ed65a6e-408d-4da8-9ab8-456a3a767f89)  
Error Value: 2342.026995562169  
Prediction Class: 25  
Actual Class: 25  
Overall Mean Squared Error: 2294.2300397878194  

## Overview  
This question requires you to create a basic facial recognition system using a technique called principal component analysis (PCA) by projecting the face images on the feature space (face space) which best
represents the variations among distinct faces. The face space is defined as the “Eigenfaces", which are the eigenvectors of the set of faces.  

The goal of implementing this system is to recognize a person's face by comparing it to a pre-existing database of faces, and identifying the closest match.  


## Motivation and Goal  
The goal is to implement a facial recognition system that extracts Eigenfaces, projects faces onto them for efficient representation, and accurately identifies individuals in a dataset with diverse conditions.    

## Technical Aspect  
Dataset: AT&T face dataset contains a set of grayscale face images with dimensions 92x112    

1. Load dataset and divide the date into training and test sets.  
2. Implement the PCA algorithm from scratch.  
3. Implement image reconstruction using the eigen projections and visualise differences for different number of components.  
4. Visualise the mean(Eigen face) generated.  
5. Given training set, obtain accuracy by attempting a face regonition module and obtaining the accuracy for different number of principal components.  

## Technologies Used
- Google Colab  
- Concepts used : PCA(from scratch).    
- Libraries: numpy, matplotlib.pyplot, os, time , cv2

## Results

![image](https://github.com/Sagnick0907/Face-Recognition-using-PCA/assets/76872499/9376aa68-b037-497d-b828-8362bb37abfc)    


![image](https://github.com/Sagnick0907/Face-Recognition-using-PCA/assets/76872499/19b2af55-68e5-403f-ada9-13a1679b6831)  


![image](https://github.com/Sagnick0907/Face-Recognition-using-PCA/assets/76872499/bb3be128-ca57-4c41-a052-9d8cef97ad76)  




