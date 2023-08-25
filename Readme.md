# Internship Project - Data Science with Python Career Program

The Dataset used in this project is the "Amazing Mart" Dataset, which contains the information about different products taken by different customer from different geographical areas for the year 2013 to 2016 with their sales and profits. 
The Data consist of two files Order Data which is a TSV file and Order Breakdown Data which is in JSON format. In this we have to Import the Data properly and merge the data and make a single data frame, save this data frame in a CSV format.
This data has 8047 rows and 19 features.Following are the features of the dataset :

1. Order ID => Unique Order ID for each Customer.
2. Order Date => Order Date of the product.
3. Customer Name => Name of the Customer.
4. City => City of residence of of the Customer.
5. Country => Country of residence of the Customer.
6. Region => Region where the Customer belong.
7. Segment => The segment where the Customer belongs.
8. Ship Date => Shipping Date of the Product.
9. Ship Mode => Shipping Mode specified by the Customer.
10. State => State of residence of the Customer.
11. Days to Ship => Days to Ship of the Product.
12. Product Name => Name of the Product.
13. Discount => Discount provided.
14. Actual Discount => Actual Discount provided.
15. Sales => Sales of the Product.
16. Profit => Profit/Loss incurred.
17. Quantity => Quantity of the Product.
18. Category => Category of the product ordered.
19. Sub-Category => Sub-Category of the product ordered.

# In this Project we have to perform these actions -
1. Explore the Data using Excel . understand the data and prepare a short summary about the dataset in the PPT.
2. Download the Amazing Mart dataset and perform Data cleaning and Data Pre-Processing if Necessary.
3. The Data consist of two files Order Data which is a TSV file and Order Breakdown Data which is in JSON format. Import the Data properly and merge the data and make a single data frame, save this data frame in a CSV format.
4. Use the various methods such as Handling null values, One-Hot Encoding, Imputation and Scaling of Data Pre-Processing where necessary.
5. Find correlations between various columns of the data.
6. Perform Exploratory data analysis (EDA) on the Data and perform Graphical Analysis on the Data. Include the graphs with conclusions from the Graphical Analysis.
7. Prepare the Data for Machine Learning modeling.
8. Identify the required columns and target variable for machine learning modeling.
9. Apply various Machine Learning techniques such as Regression or classification ,Bagging, Ensemble techniques and find out the best model using various Machine Learning model evaluation metrics.
10. Save the best model and Load the model.
11. Take the original data set and make another dataset by randomly picking 20 data points from the Amazing Mart dataset and apply the saved model on the same Dataset and test the model.
12. Create an app.py file and other dependencies files for Streamlit app to be deployed on Streamlit Cloud. Make a simple website and deploy your ML model on Streamlit, Make the website public.
15. Share the Streamlit website and GitHub repository links in the Project PPT.

# Streamlit App

This project aims to provide a user-friendly web application that predicts the Sales of the Mart based on various features. The app is built using Streamlit, a popular Python library for creating interactive web applications.

# Features
1. Predict the Sales of the Mart based on its features.
2. Explore the dataset and visualize the data.
3. Input various features on which sales is based like Product Name, Order date, Quantity, Actual Discount, Segment, Ship mode, Days to ship, Country, State, City, and more, to get an estimated Sales.
4. The app uses a trained machine learning model to make predictions.

So by using this library I made this app and you can access the app link here : https://data-science-internship-project-qwq23z8aznpvyjldddlbxm.streamlit.app/
