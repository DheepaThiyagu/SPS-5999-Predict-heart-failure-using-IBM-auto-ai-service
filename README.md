# SPS-5999-Predict-heart-failure-using-IBM-Auto-AI-Service
[click for the demo](https://www.youtube.com/watch?v=YwEWx-rL0tE)
<p> As shown in the video,this application leverages machine learning models to predict heart failure risks, and helps the customer understand how various factors affect the heart.

<p>
 In this application, we study the effects of average hearbeat per minute,palpitations per day,cholesterol,BMI,Age,Sex,Family History, Smoker for the last 5 years,excercice min per week to determine how much of a difference these factors can make on your risk of heart failure. By using our application, customers see the radical difference in their lifestyle choices they make to avoid the risk of heart failure. By leveraging AI and machine learning, we help customers understand just how much their cholestrol level, smoking habits, excercise and BMI  increases or decreases their risk ailure, by predicting whether they are prone  or not prone to heart failure.
#Description
<p>
 Using IBM AutoAI, you automate all the tasks involved in building predictive models for different requirements. You see how AutoAI generates great models quickly which save time and effort and aid in faster decision-making process. You create a model that from a data set that includes the average hearbeat per minute,palpitations per day,cholesterol,BMI,Age,Sex,Family History, Smoker for the last 5 years,excercice min per week  to predict the risk of heart failure.

<p>When you have completed this code pattern, you understand how to:

- Setup, quickly, the services on IBM Cloud for building the model.
- Ingest the data and initiate the AutoAI process.
- Build different models using AutoAI and evaluate the performance.
- Choose the best model and complete the deployment.
- Generate predictions using the deployed model by making REST calls.
- Compare the process of using AutoAI and building the model manually.
- Visualize the deployed model using a front-end application.
#Architecture Components


#Flow Description
1. The user creates an IBM Watson Studio Service on IBM Cloud.
2. The user creates an IBM Cloud Object Storage Service and adds that to Watson Studio.
3. The user uploads the insurance premium data file into Watson Studio.
4. The user creates an AutoAI Experiment to predict insurance premium on Watson Studio
5. AutoAI uses Watson Machine Learning to create several models, and the user deploys the best performing model.
5. The user uses the Flask web-application to connect to the deployed model and predict an insurance charge.
#Included components
* IBM Watson Studio - IBM Watson® Studio helps data scientists and analysts prepare data and build models at scale across any cloud.
* IBM Watson Machine Learning - IBM Watson® Machine Learning helps data scientists and developers accelerate AI and machine-learning deployment.
* IBM Node-RED - Node-RED is a programming tool that provides a browser-based editor that makes it easy to wire together flows using the wide range of nodes in the palette that                 can be deployed to its runtime in a single-click.
* IBM Cloud Object Storage - IBM Cloud™ Object Storage makes it possible to store practically limitless amounts of data, simply and cost effectively.
#Featured technologies
* artificial-intelligence - Build and train models, and create apps, with a trusted AI-infused platform.
* Python - Python is an interpreted, high-level, general-purpose programming language.


