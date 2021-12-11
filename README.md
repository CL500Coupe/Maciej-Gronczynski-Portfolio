
# [Project 1 - Face detection & gender classification](https://share.streamlit.io/cl500coupe/gender_recognition_app/main/app.py)
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

![](/images/eska%20tv.png)


# [Project 2 - Stroke prediction](https://www.kaggle.com/maciejgronczynski/stroke-prediction-eda-lr-k-nearest-xgboost)
According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths.
This project presents how to use machine learning approach to predict whether a patient is likely to get stroke based on the input parameters like
gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.

![](/images/project2_image1_fixed.png)

Main objective is to classify/predict if a particular person based on their parameters is likely to have a stroke.
This anaylsis might be very helpful and interesting in case of real-world problems as strokes account for as much as 11% of all deaths in the world.
To sum up, I'm going to create my target variable y(stroke 0=no,1=yes) and try to predict output using features(basically rest of the columns) using different classification models.

![](/images/project2_image2_fixed.png)

In this project I use 3 different models (Linear Regression, K-nearest neighbors and XGBoost) and compare them to each other.





# [Project 3 - NBA players height prediction](https://www.kaggle.com/maciejgronczynski/height-prediction-eda-lr-cross-val-ridge-lasso)
