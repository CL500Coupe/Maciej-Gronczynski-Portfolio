Portfolio

# Explore my personal collection of datasets, all created and compiled by me
1.  [Biggest gender/face recognition dataset](https://www.kaggle.com/datasets/maciejgronczynski/biggest-genderface-recognition-dataset)
2. [Copper Mining Company - Stock Price Prediction](https://www.kaggle.com/datasets/maciejgronczynski/cooper-mining-company-stock-price-prediction)
3. [Doomtrooper CCG (All cards)](https://www.kaggle.com/datasets/maciejgronczynski/doomtrooper-ccg-all-cards)
4. [Vehicle Classification - Dataset](https://www.kaggle.com/datasets/maciejgronczynski/vehicle-classification-dataset)
5. [Current NBA Players](https://www.kaggle.com/datasets/maciejgronczynski/current-nba-players)

# Doomtrooper DataSight: AI-Powered Card Recognition and Dataset Compilation
![final_gif](https://github.com/CL500Coupe/Maciej-Gronczynski-Portfolio/assets/63499090/bd1ec431-ef57-457c-a40d-0a7ee5ffd7f6)

In this innovative project, I've meticulously compiled a dataset of over 1000 unique cards from the classic Doomtrooper card game, which is accessible for viewing [here](https://www.kaggle.com/datasets/maciejgronczynski/doomtrooper-ccg-all-cards). Utilizing a custom script, I automated the data collection process by extracting card information through a webcam. The above GIF demonstrates this fascinating procedure, and the script's code is available for review [here](https://github.com/CL500Coupe/Doomtrooper-DataSight-AI-Powered-Card-Recognition-and-Dataset-Compilation).


# [Dissertation Project - Predicting Stock Price 21 days into the future 80% accuracy](https://www.kaggle.com/code/maciejgronczynski/kghm-stock-price-prediction-21-days-in-future-80#5.Building-model-(RANDOM-FOREST-CLASSIFIER))

In this project, I successfully developed a machine learning model to predict stock market trends using a Random Forest Classifier. The model was trained and tested on historical market data, demonstrating a solid performance with an accuracy of almost 80%.

Dataset was collected and pre-processed by me can be accessed [here](https://www.kaggle.com/datasets/maciejgronczynski/cooper-mining-company-stock-price-prediction)

![](/images/predi2.png)


# [Project A - Face detection & gender classification](https://share.streamlit.io/cl500coupe/gender_recognition_app/main/app.py)
Face detection and Gender recognition web application hosted on streamlit.io.
I used 18000 images of faces split into two categories (man,woman). Each image is 180 by 180 pixels.
Keras Sequential model with Conv2D, MaxPooling2D layers was build on dataset that was previously autotuned and normalised.
Validation accuracy fluctuates between 89-92%.

![](/images/photo_1_fix2.png)
![](/images/photo_2_fixed.png)


Training procees is using Convolutional Neural Networks is shared [here](https://www.kaggle.com/maciejgronczynski/cnn-sequential-gender-recognition-model)

Disclaimer: All data used to train and test my Convolutional Neural Networks model was collected
by myself and it's public and free to use on [kaggle](https://www.kaggle.com/maciejgronczynski/biggest-genderface-recognition-dataset)

Dataset and model were collected and trained by myself.

![](/images/streamlit_image.png)





# [Project B - Stroke prediction](https://www.kaggle.com/maciejgronczynski/stroke-prediction-eda-lr-k-nearest-xgboost)
According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths.
This project presents how to use machine learning approach to predict whether a patient is likely to get stroke based on the input parameters like
gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.

![](/images/project2_image1_fixed.png)

Main objective is to classify/predict if a particular person based on their parameters is likely to have a stroke.
This anaylsis might be very helpful and interesting in case of real-world problems as strokes account for as much as 11% of all deaths in the world.
To sum up, I'm going to create my target variable y(stroke 0=no,1=yes) and try to predict output using features(basically rest of the columns) using different classification models.

![](/images/project2_image2_fixed.png)

In this project I use 3 different models (Linear Regression, K-nearest neighbors and XGBoost) and compare them to each other.





# [Project C - NBA players height prediction](https://www.kaggle.com/maciejgronczynski/height-prediction-eda-lr-cross-val-ridge-lasso)
In this analysis I will try to predict player_height using features from dataset. There is strong correlation between player_height and player_weight that's why I decided to drop player_weight column to find usefull correlations in other features.


![](/images/project3_image1_fixed.png)

After analysing dataset and applying linear regression models to try predict player_height target value I came to few conclusions.
First of all at the beginning I thought that there's strong correlation between player_height and features like offensive, defensive rebound.
As a basketball fan I always thought that biggest and tallest players usually grabs most rebounds, but after analysing dataset we can clearly see that there's very low correlation of 0.589033 for offensive rebounds and 0.614650 for defensive rebounds.
Also negative correlaction value between player_height and assists was a big suprise for me.

In this analysis I use 3 different models to predict player_height (Linear Regression, cross-val and Ridge-lasso).
