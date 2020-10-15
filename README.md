# SPS-5999-Predict-heart-failure-using-IBM-Auto-AI-Service

 <p align=”center”> [![Click for the demo](https://github.com/DheepaThiyagu/SPS-5999-Predict-heart-failure-using-IBM-auto-ai-service/blob/master/predict.png?raw=true)](https://www.youtube.com/watch?v=YwEWx-rL0tE) </p>
<p> As shown in the video,this application leverages machine learning models to predict heart failure risks, and helps the customer understand how various factors lead to risk of heart failure.

<p>
 In this application, we study the effects of average hearbeat per minute,palpitations per day,cholesterol, BMI, Age, Sex, Family History, Smoking habit for the last 5 years,how excercise minutes per week to determine how much of a difference these factors can make on our risk of heart failure. By using our application, customers see the radical difference in their lifestyle choices they make to avoid the risk of heart failure. By leveraging AI and machine learning, we help customers understand just how much their cholestrol level, smoking habits, excercise and BMI  increases or decreases their risk, by predicting whether they are prone  or not prone to heart failure.
# Description
<p>
 Using IBM AutoAI, we automate all the tasks involved in building predictive models for different requirements. We see how AutoAI generates great models quickly which save time and effort and aid in faster decision-making process. We create a model  from a data set that includes the average hearbeat per minute, palpitations per day, holesterol, BMI, Age, ex, Family History, Smoker for the last 5 years,excercice min per week  to predict the risk of heart failure.

<p> When we have completed this project,we understand how to:

- Setup, quickly, the services on IBM Cloud for building the model.
- Ingest the data and initiate the AutoAI process.
- Build different models using AutoAI and evaluate the performance.
- Choose the best model and complete the deployment.
- Generate predictions using the deployed model.
# Architecture Components

![click for the project flow](https://github.com/DheepaThiyagu/SPS-5999-Predict-heart-failure-using-IBM-auto-ai-service/blob/master/heartfailureautoai.png?raw=true)



# Flow Description
1. We create an IBM Watson Studio Service on IBM Cloud.
2. We create an IBM Cloud Object Storage Service and add that to Watson Studio.
3. We uploads the patient data file into Watson Studio.
4. We create an AutoAI Experiment to predict heart failure on Watson Studio
5. AutoAI uses Watson Machine Learning to create several models, and the user deploys the best performing model.
6. Finally we use the Node-RED service and use the dashboard to connect to the deployed model and predict heart failure.
# Included components
* IBM Watson Studio - IBM Watson® Studio helps data scientists and analysts prepare data and build models at scale across any cloud.
* IBM Watson Machine Learning - IBM Watson® Machine Learning helps data scientists and developers accelerate AI and machine-learning deployment.
* IBM Node-RED - Node-RED is a programming tool that provides a browser-based editor that makes it easy to wire together flows using the wide range of nodes in the palette that                 can be deployed to its runtime in a single-click.
* IBM Cloud Object Storage - IBM Cloud™ Object Storage makes it possible to store practically limitless amounts of data, simply and cost effectively.


