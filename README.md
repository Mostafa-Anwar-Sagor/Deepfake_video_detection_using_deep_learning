# AI-Powered Deepfake Detection System

## Give a Star⭐ to this repository

**Developed by Mostafa Anwar**

## Latest Update
#### This project includes a dockerised Django Application that allows you to spin up a container within seconds without worrying about dependencies.


## 1. Introduction
This project aims to detect video deepfakes using deep learning techniques like ResNext and LSTM. The system achieves deepfake detection through transfer learning, where a pretrained ResNext CNN extracts feature vectors, which are then processed by an LSTM layer for classification.


## 2. Directory Structure
For ease of understanding the project is structured in below format
```
Deepfake_detection_using_deep_learning
    |
    |--- Django Application
    |--- Model Creation
    |--- Documentaion
```
1. Django Application 
   - This directory consists of the django made application of our work. Where a user can upload the video and submit it to the model for prediction. The trained model performs the prediction and the result is displayed on the screen.
2. Model Creation
   - This directory consists of the step by step process of creating and training a deepfake detection model using our approach.
3. Documentation
   - This directory consists of all the documentation done during the project
   
## 3. System Architecture
The system uses a hybrid deep learning approach combining CNN and LSTM architectures for robust deepfake detection.

## 4. Demo 
The application provides a web interface for uploading and analyzing videos for deepfake detection.

## 5. Our Results

| Model Name | No of videos | No of Frames | Accuracy |
|------------|--------------|--------------|----------|
|model_84_acc_10_frames_final_data.pt |6000 |10 |84.21461|
|model_87_acc_20_frames_final_data.pt | 6000 |20 |87.79160|
|model_89_acc_40_frames_final_data.pt | 6000| 40 |89.34681|
|model_90_acc_60_frames_final_data.pt | 6000| 60 |90.59097 |
|model_91_acc_80_frames_final_data.pt | 6000 | 80 | 91.49818 |
|model_93_acc_100_frames_final_data.pt| 6000 | 100 | 93.58794|

## 6. Author

**Mostafa Anwar**  
This project was developed as part of my internship work, focusing on leveraging deep learning for deepfake detection.

## 7. License

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

## 8. Future Enhancements
### Below are potential improvements for the project:
- [ ] Deploying the application to cloud platforms
- [ ] Creating an open source API for detection
- [ ] Batch processing of entire videos instead of processing first 'x' frames
- [ ] Optimizing the code for faster execution
#### Completed 
- [X] Dockerizing the application
- [X] Enabling the project to work on Non-CUDA computers (normal or AMD GPUs)

## 9. Don't forget to Star⭐ this repository! 
