![Header](./img/banner.jpg)

## Overview

This repository contains a project that performs sentiment analysis on tweets related to US airlines. The primary goal is to classify the sentiment of each tweet as either positive, neutral, or negative using various data preprocessing techniques, exploratory data analysis (EDA), and machine learning models.

## Project Structure

`notebooks/`: Contains the Jupyter Notebook (airline_sentiment_analysis.ipynb) used for the analysis and model building.
`data/`: (Optional) This directory should include the dataset used for the analysis (us_airlines.csv). Note that the actual dataset may not be included due to size constraints or privacy concerns.
`img/`: Contains the banner for this repository
`README.md`: Provides an overview of the project, instructions for setup, and usage details.

## Getting Started

## Prerequisites
To run the analysis on your local machine, you will need the following Python libraries installed:

`pandas`
`numpy`
`matplotlib`
`seaborn`
`scikit-learn`
`nltk`

You can install the required packages using the following command:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn nltk
```

## Dataset
The analysis uses a dataset containing tweets about US airlines. Each tweet is labeled with a sentiment (positive, neutral, or negative) and includes other relevant information such as the airline mentioned, tweet creation date, etc.

## Installation

To get this project, you can clone it by running the following code:

    https://github.com/ilhamtaufieq17/US-Airlines-Sentiment-Classification.git
    
## Project Workflow
1. Data Exploration and Cleaning:
- Initial exploration of the dataset to understand its structure.
- Cleaning the data by handling missing values and removing irrelevant columns.

2. Exploratory Data Analysis (EDA):
- Visualization of sentiment distribution among the tweets.
- Identification of common reasons behind negative sentiments.

3. Text Processing:
- Tokenization, stopword removal, and lemmatization of tweet text.
- Conversion of text data into numerical features using TF-IDF vectorization.

4. Model Building and Evaluation:
- Training a logistic regression model to classify tweet sentiments.
- Evaluation of the model using a confusion matrix and classification report.

## Results

The sentiment classification model performed well on negative sentiments but struggled with positive sentiments due to limited data. Key insights and recommendations for improving the model and airline customer service are discussed in the project.

## Contribute

If you'd like to contribute, feel free to contact me here:

<a href="https://www.linkedin.com/in/ilham-taufieq-julfianto/" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="52" height="40" alt="linkedin logo"/>
  </a>
  <a href="mailto:taufieq17@gmail.com" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/gmail/default.svg"  width="52" height="40" alt="gmail logo"/>
  </a>

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

The dataset used for this analysis was inspired by public datasets available on Kaggle.
This project was developed as a demonstration of sentiment analysis techniques using Python and machine learning.
