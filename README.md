# COS801 Final Project: Abnormal Crowd Surveillance Behavior Detection Using 3D CNNs

## Aim
The goal of this project is to implement a deep learning model using 3D convolutional neural networks to process video data to enable the detection and identification of abnormal behaviour in video surveillance scenarios.

## Methodology

### A. Video Preprocessing
Frame extraction, clip formation, training and testing data prepartion and data formatting is done on the crowd video data.

### B. Feature Extraction
Feature extraction is completed using a fine-tuned pre-trained 3CD model sourced from a github repository, a custom 3d CNN trained from scratch using the video data and an enahnced 3d CNN with spatial attention mechanism.

### C. Video Classification
The above mentioned models are also used for classification. There are 2 classes within the dataset, normal crowd behaviour and abnormal crowd behavour.

### D. Evaluation
1. **Accuracy**
2. **Loss**
3. **Confusion Matrix**

## Repository Contents
- **Python Script used for COS801 Porject (code)**
- **Reference Materials used in research (folder)**

## References
1. Dataset: [Link](https://www.crcv.ucf.edu/projects/Abnormal_Crowd/)
2. C3D GitHub Repository: [Link](https://github.com/DavideA/c3d-pytorch)
