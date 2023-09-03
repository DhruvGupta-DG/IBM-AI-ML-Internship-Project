# IBM-AI-MLInternship-Project
Sentiment Analysis and Text Data Preprocessing
This Python script is designed for sentiment analysis and text data preprocessing on a dataset of reviews. It utilizes various libraries to clean and analyze text data, generate visualizations, and perform sentiment analysis. Below is an overview of the code's functionality and how to use it:

Usage:
Data Loading and Inspection:

The code begins by importing necessary libraries and loading a dataset from a CSV file. Make sure to specify the correct file path for your dataset using pd.read_csv('Reviews.csv').
Data Cleaning:

Punctuation and numbers are removed from the text data to prepare it for analysis.
Accented characters and special characters are also removed.
The cleaned text data is stored in the 'Text' column of the DataFrame.
Feature Engineering:

The code calculates various text-related features such as length, polarity, subjectivity, character count, word count, word density, and punctuation count.
These features are added as new columns to the DataFrame.
Data Visualization:

Visualizations of polarity, subjectivity, word frequencies, bigrams, trigrams, and word clouds are generated using Matplotlib, Seaborn, and NLTK.
Sentiment Analysis:

The code categorizes the reviews into sentiment categories (e.g., "Positive," "Negative," "Neutral") based on polarity scores.
It calculates and displays the percentage of reviews in each sentiment category using a pie chart.
Dependencies:
Python 3.x
Libraries: pandas, numpy, nltk, textblob, matplotlib, seaborn, wordcloud, and sklearn.
Running the Code:
Ensure you have the necessary libraries installed.
Provide the correct file path for your dataset in the pd.read_csv('Reviews.csv') line.
Run the script in a Python environment.
Note:
This code provides a comprehensive analysis of text data, including sentiment analysis and various text-related metrics.
You can customize and extend the code to fit your specific dataset and analysis requirements.
Feel free to adapt and use this code for your own text analysis projects.

