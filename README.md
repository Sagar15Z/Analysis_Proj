# Restaurant Review Sentiment Analysis(Jupyter N)
This project focuses on analyzing the sentiment expressed in restaurant reviews. By processing customer feedback, the model aims to determine whether a review expresses a positive or negative opinion.

# Overview
The workflow of this project involves several key steps:
1.  Data Acquisition and Preprocessing: Restaurant reviews and their corresponding sentiment labels serve as the primary input. The initial stage involves cleaning this data to prepare it for analysis. This includes tasks such as removing irrelevant characters, handling missing values, and potentially stemming or lemmatizing words.
2.  Sentiment Exploration: Following data cleaning, the project explores the distribution of positive and negative reviews. Visualizations, such as word clouds generated using the wordcloud library, are employed to provide an intuitive understanding of the most frequent terms associated with each sentiment.
3.  Text Vectorization: To enable machine learning algorithms to process the textual data, the reviews are converted into a numerical format using techniques like Count Vectorization. This process transforms the text into a matrix of token counts.
4.  Model Training and Evaluation: The vectorized data is then split into training and testing sets. Several machine learning algorithms are applied to this data to build sentiment classification models. The performance of these models is evaluated on the testing set to identify the most effective one for this task.
5.  User Interface: The best-performing model is integrated into a simple Graphical User Interface (GUI). This allows users to input their own restaurant reviews and receive an immediate sentiment prediction (positive or negative) from the trained
