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
![alt text](https://github.com/PeterShin23/dsp1/blob/main/FIGURES/top20_all.png?raw=true) | Many of the top 20 words have an subjectively positive connotation, including “great”, “good”, “bought”, “like”, “love” and “well”. There seems to be little to no words with a subjectively negative connotation. While there are a majority of positive connotation words, we cannot conclude that these words necessarily are used in a context that yields or prompt a higher rating review
![alt text](https://github.com/PeterShin23/dsp1/blob/main/FIGURES/top10_rating5.png?raw=true) | Many of the top 10 words in reviews with a rating of 1 have mostly subjectively neutral descriptive words other than “return” which is subjectively negative
![alt text](https://github.com/PeterShin23/dsp1/blob/main/FIGURES/top10_rating1.png?raw=true) | Compared to the top 10 words of all reviews, reviews with a rating of 5 have more top 10 words that explicitly a positive connotation such as “love”, “great”, “east”, “get”, and “bought”
![alt text](https://github.com/PeterShin23/dsp1/blob/main/FIGURES/rating_distribution.png?raw=true) | The distribution of ratings across all reviews shows very few reviews with a rating of 1 to 3, with most reviews being a 5 star rating. This distribution correlates with our findings of the top 20 words in reviews as most descriptive words we observed are positive
![alt text](https://github.com/PeterShin23/dsp1/blob/main/FIGURES/rating_diff.png?raw=true) | The distribution of predicted - actual ratings found with test data. Distribution shows majority of predictions by model makes an accurate prediction of actual rating. However, our model still makes some very inaccurate predictions as shown by 4 and -4 rating differences.





## REFERENCES
[1]	“Consumer reviews of Amazon Products,” Kaggle, 20-May-2019. [Online]. Available: https://www.kaggle.com/datasets/datafiniti/consumer-reviews-of-amazon-products?Fbclid=IwAR0yIq8hjHkHZTXoqGVG2xiIQunCDA0JI1ChlZ5XhSZulLyZReaQnheRv-4&select=1429_1.csv. [Accessed: 14-Feb-2023]. 

[2]	“Amazon ecommerce trends for 2023,” Insider Intelligence, 06-Jan-2023. [Online]. Available: https://www.insiderintelligence.com/insights/amazon-ecommerce-trends/. [Accessed: 08-Feb-2023]. 
