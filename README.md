# Analyzing_Customer_Feedback_Sentiments_for_Restaurants
Analyzing Customer Feedback Sentiments for Restaurants using Deep Learning

# Customer Feedback Sentiment Analysis for Restaurants - Documentation

## Overview

Welcome to the Customer Feedback Sentiment Analysis web application for Restaurants! This application is designed to analyze customer reviews and provide predictions on whether the reviews are positive or negative. By using the principles of Natural Language Processing (NLP) and Machine Learning, this application aims to help users make informed decisions about restaurants based on the sentiments expressed in the reviews.

## How It Works

1. **User Input**: Users can access the web application through a user-friendly interface. On the application's homepage, there will be a text input box where users can enter their feedback about a particular restaurant they visited.

2. **Text Analysis**: Once the user submits their feedback, the application leverages the NLP method and Machine Learning algorithms to analyze the content of the review text. The review is processed to understand the sentiments expressed within it.

3. **Sentiment Classification**: The application uses a predefined dictionary of words, containing positive and negative keywords commonly found in restaurant reviews. Based on the occurrence and context of these words in the user's feedback, the model classifies the review as either positive or negative.

4. **Prediction Display**: The results of the sentiment analysis are then showcased on the application's UI. Users will be able to see whether their review has been classified as positive or negative. This provides them with valuable insights into the sentiments underlying their feedback.

5. **Visualization**: In addition to the individual predictions, the web application also offers a visualization of the overall sentiment trends. Users can see the total number of positive and negative reviews for a specific restaurant, which can aid in assessing its overall reputation.

![download](https://github.com/yp723/Analyzing_Customer_Feedback_Sentiments_for_Restaurants/assets/81978809/6b406447-59ba-4660-87bc-4d123d0a8beb)

## Intended Users

The Customer Feedback Sentiment Analysis web application is intended for:

- **Restaurant-Goers**: Customers who want to share their experiences and receive instant feedback on whether their reviews are considered positive or negative.

- **Decision-Makers**: Restaurant owners, managers, and staff who wish to monitor and understand customer sentiments to improve their services and address potential issues.

## Advantages

- **Real-time Analysis**: The application provides instant results, enabling users to receive feedback on their reviews immediately.

- **Automated Sentiment Classification**: Users do not need to manually interpret their review sentiments, as the algorithm handles the sentiment analysis.

- **Data Visualization**: The application visually presents the overall sentiment trends, allowing users to gauge the restaurant's reputation at a glance.

## Technologies Used

The Customer Feedback Sentiment Analysis web application utilizes the following technologies:

- **Python**: The core programming language used for implementing the NLP and Machine Learning algorithms.

- **Natural Language Processing (NLP)**: Techniques and methods applied to understand and process human language.

- **Machine Learning (ML)**: The application leverages ML models to classify review sentiments based on the predefined dictionary of words.

- **Web Development (HTML, CSS, JavaScript)**: For creating the user interface and enabling a smooth user experience.

- **Framework (Flask)**: A web framework to host and deploy the application.

## Project Work Flow:

- Data Collection
- Text Pre-processing
- Import the Libraries.
  - importing the dataset
  - Remove Punctuations
  - Convert each word into a lower case.
  - Stemming.
  - Splitting Data into Train and Test.
- Model Building
  - import the model building Libraries
  - Initializing the model
  - Adding Input Layer
  - Adding Hidden Layer
  - Adding Output Layer
  - Configure the Learning Process
- Training and testing the model
  - Optimize the Model
  - Save the Model
- Application Building
  - Build HTML Page
  - Build python Code

## How to Use

1. Access the Customer Feedback Sentiment Analysis web application through the provided URL.

2. On the homepage, you will find a text input box.

3. Enter your feedback about a restaurant in the text input box.

4. Click on the "Submit" button to analyze your feedback.

5. The application will process your feedback and display whether it is classified as a positive or negative review.

## Future Enhancements

We are committed to continuously improving the Customer Feedback Sentiment Analysis web application. Some potential future enhancements include:

- **Multilingual Support**: Expanding the application's capabilities to analyze feedback in multiple languages to cater to a broader user base.

- **Fine-grained Sentiment Analysis**: Instead of a binary positive/negative classification, enhancing the model to provide more nuanced sentiment analysis, such as neutral, very positive, very negative, etc.

- **User Authentication**: Implementing user authentication to enable users to track their previous reviews and sentiments.

## Conclusion

The Customer Feedback Sentiment Analysis web application aims to empower restaurant-goers and decision-makers by providing valuable insights into the sentiments expressed in customer reviews. Through the combination of NLP and Machine Learning techniques, users can receive instant predictions and visualize overall sentiment trends, facilitating informed decisions and continual improvement in the restaurant industry.

## HTML Pages of the project

Home Page:
![Screenshot (21).png](..%2F..%2FOneDrive%2FPictures%2FScreenshots%2FScreenshot%20%2821%29.png)

Prediction Page:
![Screenshot (22).png](..%2F..%2FOneDrive%2FPictures%2FScreenshots%2FScreenshot%20%2822%29.png)

About Page:
![Screenshot (23).png](..%2F..%2FOneDrive%2FPictures%2FScreenshots%2FScreenshot%20%2823%29.png)

Good Review Prediction:
![Screenshot (25).png](..%2F..%2FOneDrive%2FPictures%2FScreenshots%2FScreenshot%20%2825%29.png)

Average Review Prediction:
![Screenshot (27).png](..%2F..%2FOneDrive%2FPictures%2FScreenshots%2FScreenshot%20%2827%29.png)

Bad Review Prediction:
![Screenshot (26).png](..%2F..%2FOneDrive%2FPictures%2FScreenshots%2FScreenshot%20%2826%29.png)