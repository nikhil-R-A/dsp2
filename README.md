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
![alt text](https://github.com/nikhil-R-A/dsp2/blob/main/FIGURES/average_surprise.png?raw=true) | Many of the top 20 words have an subjectively positive connotation, including “great”, “good”, “bought”, “like”, “love” and “well”. There seems to be little to no words with a subjectively negative connotation. While there are a majority of positive connotation words, we cannot conclude that these words necessarily are used in a context that yields or prompt a higher rating review
![alt text](https://github.com/PeterShin23/dsp1/blob/main/FIGURES/top10_rating5.png?raw=true) | Many of the top 10 words in reviews with a rating of 1 have mostly subjectively neutral descriptive words other than “return” which is subjectively negative
![alt text](https://github.com/PeterShin23/dsp1/blob/main/FIGURES/top10_rating1.png?raw=true) | Compared to the top 10 words of all reviews, reviews with a rating of 5 have more top 10 words that explicitly a positive connotation such as “love”, “great”, “east”, “get”, and “bought”
![alt text](https://github.com/PeterShin23/dsp1/blob/main/FIGURES/rating_distribution.png?raw=true) | The distribution of ratings across all reviews shows very few reviews with a rating of 1 to 3, with most reviews being a 5 star rating. This distribution correlates with our findings of the top 20 words in reviews as most descriptive words we observed are positive
![alt text](https://github.com/PeterShin23/dsp1/blob/main/FIGURES/rating_diff.png?raw=true) | The distribution of predicted - actual ratings found with test data. Distribution shows majority of predictions by model makes an accurate prediction of actual rating. However, our model still makes some very inaccurate predictions as shown by 4 and -4 rating differences.





## REFERENCES
[1] 	M. Sambare, “Fer-2013,” Kaggle, 19-Jul-2020. [Online]. Available:				https://www.kaggle.com/datasets/msambare/fer2013?resource=download.			[Accessed: 18-Mar-2023]. 

[2]	B. Taha, “What is SVM: Build an image classifier with SVM,” Analytics Vidhya,		27-Aug-2021. [Online]. Available:									https://www.analyticsvidhya.com/blog/2021/06/build-an-image-classifier-	
with-svm/#:~:text=The%20main%20advantage%20of%20SVM,Object%20Detection%20and%20image%20classification. [Accessed: 14-Mar-2023]. 

