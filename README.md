# **Mobile Price Classification Project- From Data to Dollars**

## **Objective**
The objective of this project is to develop machine learning models that facilitate data-driven decision-making for classifying mobile prices. Primarily focused on predicting mobile price ranges based on device features, helping stakeholders align pricing with market expectations.Using a dataset of 2000 records and 21 attributes, the goal was to predict the price range of mobile phones based on their features such as battery power, camera quality, screen size, and more.
<img width="1116" height="610" alt="image" src="https://github.com/user-attachments/assets/f0faaf18-1ffa-48a4-bd49-08c3081e105c" />


## **Dataset**
- The dataset contains **2000 records** with **21 attributes**, including features such as:
  - **battery_power**
  - **bluetooth**
  - **clck_spd**
  - **dual_sim**
  - **front_cam**
  - **four_g**
  - **ram_mb**
  - **scrn_ht**
  - **price_range** (target variable) and more.
  
- The target variable, **price_range**, was originally numeric, but it was converted to a categorical variable for classification purposes. The data was cleaned to remove inconsistencies and improve model performance.

## **Models Used**
- **Support Vector Machine (SVM)**  
- **Decision Tree**
- **Logistic Regression**
<img width="1352" height="688" alt="image" src="https://github.com/user-attachments/assets/2014b453-df7c-4c35-811c-cdef82bc2869" />

These models were implemented using **Weka**, a powerful tool for data mining and machine learning.

## **Results**
- Overall, the outputs from the data mining techniques, the SVM model has the highest accuracy of 96.53%, followed by logistics regression at 96.35%, and lastly J48 decision trees achieved 83.24%.*
- In terms of precision SVM and logistic regression measured 0.97 followed by decision tree at 0.84.*
- In terms of sensitivity, the results are also similar to SVM leading at 0.97, logistics regression measuring 0.96, and decision tree with 0.83.*
- **All three of the models seem to agree that ram_mb, batry_pwr, px_res_wdt, and  px_res_ht being the most important features for predicting the price range of mobile phones.**
- This project allows businesses to gain a competitive edge by making strategic decisions based on classification outputs.

## **How to Run the Project**
1. **Install Weka**: Download and install Weka.
2. **Load the Dataset**: Open Weka and load the dataset file.[Link for Dataset](https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification)
3. **Run the Models**:  
   - Select the classification algorithm (SVM or Decision Tree or logistic regression).
   - Choose the appropriate parameters and run the model to train and test it on the dataset.
4. **Evaluate the Models**: Analyze the results and performance metrics such as accuracy, precision, and recall.

