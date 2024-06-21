**Used Car Price Prediction**
---------------
**Overview**
---------
This repository hosts a project dedicated to predicting the prices of used cars. It employs various machine learning techniques for data cleaning, outlier removal, preprocessing, and building predictive models. The final model is deployed via Streamlit.

**Table of Contents**
----------

  1. Project Structure
  2. Dataset
  3. Data Cleaning
  4. Exploratory Data Analysis (EDA)
  5. Modeling
  6. Evaluation Metrics
  7. Deployment
------------    

1. **Project Structure**

    Used-Car-Price-Prediction

        ├── Used_Car_Price_pred.ipynb
        
        ├── used_car.pkl
        
        ├── streamlit2.py
        
        ├── README.md

    **Used_Car_Price_pred.ipynb**: Jupyter notebook containing all tasks such as data cleaning, EDA, modeling, and evaluation.
   
    **used_car.pkl**: Pickle file of the chosen model (Decision Tree).
   
    **Streamlit2.py**: Streamlit app for deploying the model.
   
    **README.md**: Project documentation.


2. **Dataset**
   
   The dataset, sourced from Kaggle, includes a list of used car models along with various attributes such as fuel type, transmission, model, manufacturer, and more. The data was gathered from Craigslist listings    in the USA.
    
3. **Data Cleaning**

    The data cleaning process involved:

        •Handling missing values
  
        •Removing outliers
  
        •Data pre-processing using One Hot Encoding

4. **Exploratory Data Analysis (EDA)**

    EDA was performed using:

        •Matplotlib

        •Seaborn

        •Plotly

    Visualizations were created to understand the distribution of data, relationships between features, and to identify any patterns.

5. **Modeling**

    Several machine learning models were built and evaluated:

        • Linear Regression

        • Random Forest

        • Decision Tree (chosen model)

        • Model Stacking

6. **Evaluation Metrics**

    The models were evaluated using the following metrics:

        • Mean Squared Error (MSE)

        • Mean Absolute Error (MAE)

        • R2 Score

7. **Deployment**

    The final model (Decision Tree) was saved as a pickle file and deployed using Streamlit.
