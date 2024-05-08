# House_Price_Predictor_Streamlit_web_app
<hr>
<h4>Note: This Repository is required for deployment of this project on Streamlit Cloud.</h4>
<hr>
Web App Link: https://gaurav-van-house-price-predictor-streamlit-heroku-app-g56zmy.streamlitapp.com/
<hr>
Project Repo: https://github.com/Gaurav-Van/Data_Science__Machine_Learning-Projects
<hr>
This Model / Project / Web app predicts the price of a Real Estate property / House on the basis of Features like : (area_type, location, 
total_sqft, balcony, bathroom, BHK) 
</br></br>
Model Used - Linear Regression (Multiple Linear Regression)
</br></br>
The Project / Web App is built in Python using the Following Libraries:
</br></br>

 * numpy
 * pandas
 * matplotlib
 * seaborn
 * sklearn
 * pickle
 * flask
 * streamlit
 * json
<hr>

## Concept Used</br></br>
<b>1. Data Collection -</b> From Kaggle: https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data<br><br>
<b>2. Data Pre-Procesing</b><br>
* Removing Not-so-important columns
* Checking and removing or replacement of null values
* Outlier detection using Box plot, Outlier treatment using Flooring and Capping 
* Adding new data on the basis of Domain Knowledge
<br>
<b>3. EDA -</b> Performing Data analysis on the basis of Domain Knowledge [ do check the jupyter file ] 
</br></br>
<b>4. Model Building</b><br><br>

* Encoding 
* As i am dealing with Regression problem, that too linear models so no need of Feature Scalling 
* Dividing the data by Train test split
* Testing Model's Score on divided data [ train_test_split and cross_val_score]
* <b>Model Used</b> - Linear Regression (Multiple Linear Regression)
</br></br>

<b>5. Deployment - </b> Building web app with the help of streamlit and deploying it on heroku cloud
<hr>
