# Sentiment Analysis Engine

## Week 1

**07/08/2024** - Started exploring and dedicating the dataset for the project.

**14/08/2024** - Selected IMDB and Twitter datasets for diverse sentiment sources; began preprocessing, including text cleaning and tokenization.

**21/08/2024** - Finalized preprocessing methods; implemented basic exploratory data analysis (EDA) to identify key trends and patterns in sentiment distribution.

## Week 2

**28/08/2024** - Researched potential model architectures; decided to use a combination of Naive Bayes and Support Vector Machines (SVM) as baselines [[5]

**04/09/2024** - Set up baseline models with hyperparameter tuning; began model evaluation on the validation set.

## Week 3

**11/09/2024** - Transitioned to deep learning models (LSTM and BERT) for comparison against baseline models; started model training.

**18/09/2024** - Trained models completed initial evaluation; results showed LSTM performed best on text length variability and context.

## Week 4

**25/09/2024** - Implemented performance tuning on LSTM model; added additional layers and dropout for enhanced generalization.

**02/10/2024** - Finalized model; began testing on unseen test data to assess model accuracy and robustness.

## Week 5

**09/10/2024** - Integrated model into API for deployment and tested API endpoints for consistency.

## Week 6

**16/10/2024** - Documented findings and prepared final project report, summarizing model performance and sentiment insights.

---
#THE DEPLOYED MODEL
![alt text](https://github.com/swatuu0602/Sentiment-Analysis-Engine/blob/main/Screenshot%20from%202024-11-09%2020-29-01.png)



# Sentiment Analysis Engine Deployment

## Overview

This project involves the deployment of a sentiment analysis engine using a fine-tuned NLP model. The engine is designed to analyze and categorize sentiment from textual input, specifically designed for social media platforms like Twitter. The model was trained using pre-existing datasets and deployed using Flask, with a front-end interface for users to interact with.

## Features

- **Sentiment Prediction**: The engine predicts whether a given text has a positive, negative, or neutral sentiment.
- **Real-Time Analysis**: The engine can analyze live tweets by users based on specific keywords.
- **User Dashboard**: Provides an interactive interface for users to input text and view sentiment analysis results.
- **Model Customization**: The model has been fine-tuned using DistilBERT and RoBERTa base models for improved performance in sentiment analysis tasks.

## Technologies Used

- **Python**: Primary programming language for the model and backend.
- **Flask**: Web framework used for deploying the model.
- **DistilBERT and RoBERTa**: Pre-trained NLP models fine-tuned for sentiment analysis.
- **HTML/CSS/JavaScript**: For the front-end web interface.
- **TensorFlow/PyTorch**: For model development and deployment.

## Setup Instructions

### Prerequisites

Before starting, ensure you have the following installed:

- Python 3.x
- Flask
- TensorFlow or PyTorch (based on your model)
- Dependencies listed in `requirements.txt`

### Steps to Deploy

1. Clone the repository:
   ```bash
   git clone https://github.com/ahmed-gharib89/deploy-sentiment-analysis-model.git
   cd deploy-sentiment-analysis-model
2. Install Dependencies
    pip install -r requiremetnts.txt
3. Run the application
    streamlit run app.py

  ![alt_text](https://github.com/swatuu0602/Sentiment-Analysis-Engine/blob/main/components/Screenshot%20from%202024-11-09%2020-31-09.png)



## 🌐 Sources
1. [github.com - INT426-Coursera-Answers/README.md at main](https://github.com/Bhanupriya-art/INT426-Coursera-Answers/blob/main/README.md)
2. [medium.com - NLP Sentiment Analysis and Deployment](https://medium.com/@kwabenaabrefa/nlp-sentiment-analysis-and-deployment-610dc02254ad)
3. [github.com - ahmed-gharib89/deploy-sentiment-analysis-model](https://github.com/ahmed-gharib89/deploy-sentiment-analysis-model)
4. [geeksforgeeks.org - What is README.md File?](https://www.geeksforgeeks.org/what-is-readme-md-file/)
5. [makeareadme.com - Make a README](https://www.makeareadme.com/)
6. [geeksforgeeks.org - Twitter Sentiment Analysis WebApp Using Flask](https://www.geeksforgeeks.org/twitter-sentiment-analysis-webapp-using-flask/)
