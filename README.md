# Overview
This project is a Flask web application for sentiment analysis of text reviews from Flipkart. The app allows users to input text and receive a sentiment analysis result indicating whether the input is positive or negative.

This project aims to perform sentiment analysis on customer reviews of products on Flipkart. The goal is to classify reviews as positive, negative based on their content.

# Methodology

Data Collection: Scraped customer reviews from Flipkart using BeautifulSoup.

Data Preprocessing: Cleaned the text data by removing special characters, stopwords, and performing lemmatization.

Feature Engineering: Used TF-IDF to convert text data into numerical features.

Model Building: Trained a logistic regression,knn,RandomForest,Navie Bayies model on the BOW,TF-IDF,W2V,BERT features to classify reviews.

Evaluation: Evaluated the model using accuracy, precision, recall, and F1-score metrics.

# Observations

Dataset: The dataset consists of X reviews across Y categories.

Preprocessing: Cleaning the text data significantly improved model performance.

Model Performance: Compare all model achieved an accuracy of Z% on the test set.

Insights: Positive reviews often mention product features and benefits, while negative reviews focus on issues and complaints.

# Features

Input Form: Users can enter text for sentiment analysis.

Sentiment Analysis: The app uses a machine learning model to classify the input text as positive or negative.

Theme Toggling: Users can switch between light and dark themes for the app interface.

# Deployment

# AWS Deployment

Launch EC2 Instance: Use the AWS Management Console to launch an EC2 instance.

Install Dependencies: SSH into the EC2 instance and install Python 3 and other necessary packages.

Clone Repository: Clone the project repository onto the EC2 instance.

Run Flask App: Navigate to the project directory and run the Flask app using python3 app.py.

Accessing the App

Once the Flask app is running, access it through your EC2 instance's public IP address or domain name on port 5000 (e.g., http://your-ec2-public-ip:5000).

# Project Structure

app.py: Main Flask application file.

templates/index.html: HTML template for the app interface.

model.pkl: Trained machine learning model for sentiment analysis.

requirements.txt: List of Python packages required for the project.

# Usage

Access the web app through your browser.

Enter text into the input form and submit.

View the sentiment analysis result displayed on the webpage.

# Future Improvements

Implement user authentication for secure access.

Expand sentiment analysis capabilities to handle different languages and sentiment types.


Credits:

This project was developed by Balaga UdayKiran as part of Sentiment Analysis Web App Tool.
email:udayk0596@gmail.com
