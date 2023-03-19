# Emotion Image Classification Analysis

## SRC

### Installing/Building Code
All source code exists in the SRC directory. Install all dependencies required by each file that are specified by the imports.
To run the files in this directory, developers used Jupiter Notebook.

### Code Usage
Users can use, copy, modify, merge, publish, distribute, and sublicense this software, granted that the original MIT License is included in new software.

## DATA

### Data Dictionary
Emotion  | Train File Frequency  |  Test File Frequency
------------- | ------------- | -------------
 angry | 3995 | 956
 disgust | 436 | 111
 fear |  4097 | 1024
 happy| 7215 | 1774
 neutral | 4965 | 1233
 sad | 4830 | 1247
 surprise | 3171 | 831

Link to data: https://www.kaggle.com/datasets/msambare/fer2013?resource=download 

### Revelant Notes
- We retrieved our data from KAGGLE [1]. The data set includes two folders – train and test – and seven subfolders in each of the train and test folder with each subfolder having jpg images representing one of seven distinct emotions: angry, disgust, fear, happy, neutral, sad, surprise. 
- The training data set includes a total of 28709 images and the test data set includes a total of 7178 images. 
- The images are already edited to follow the same format of being grayscale and having 48x48 pixel dimensions. The images are also aligned so that the faces are relatively centered and take up around the same space in the overall image space.


## FIGURES
Graph | Summary
------------- | -------------
![alt text](https://github.com/nikhil-R-A/dsp2/blob/main/FIGURES/train_counts.png?raw=true) | Number of images for each emotion in training set
![alt text](https://github.com/nikhil-R-A/dsp2/blob/main/FIGURES/test_counts.png?raw=true) | Number of images for each emotion in test set
![alt text](https://github.com/nikhil-R-A/dsp2/blob/main/FIGURES/average_surprise.png?raw=true) | Average image generation of all surprise images in training set
![alt text](https://github.com/nikhil-R-A/dsp2/blob/main/FIGURES/average_fear.png?raw=true) | Average image generation of all fear images in training set
![alt text](https://github.com/nikhil-R-A/dsp2/blob/main/FIGURES/average_happy.png?raw=true) | Average image generation of all happy images in training set
![alt text](https://github.com/nikhil-R-A/dsp2/blob/main/FIGURES/average_disgust.png?raw=true) | Average image generation of all disgust images in training set
![alt text](https://github.com/nikhil-R-A/dsp2/blob/main/FIGURES/average_neutral.png?raw=true) | Average image generation of all neutral images in training set
![alt text](https://github.com/nikhil-R-A/dsp2/blob/main/FIGURES/average_angry.png?raw=true) | Average image generation of all angry images in training set
![alt text](https://github.com/nikhil-R-A/dsp2/blob/main/FIGURES/average_sad.png?raw=true) | Average image generation of all sad images in training set






## REFERENCES
[1] 	M. Sambare, “Fer-2013,” Kaggle, 19-Jul-2020. [Online]. Available:				https://www.kaggle.com/datasets/msambare/fer2013?resource=download.			[Accessed: 18-Mar-2023]. 

[2]	B. Taha, “What is SVM: Build an image classifier with SVM,” Analytics Vidhya,		27-Aug-2021. [Online]. Available:									https://www.analyticsvidhya.com/blog/2021/06/build-an-image-classifier-	
with-svm/#:~:text=The%20main%20advantage%20of%20SVM,Object%20Detection%20and%20image%20classification. [Accessed: 14-Mar-2023]. 

