
**ProjectTest_Recognition Testing: YouTube Sentiment Analysis**

This project focuses on the development of a sentiment analysis tool for YouTube comments. The system aims to analyze the sentiment of comments on a specific YouTube video using a machine learning model. Due to computational limitations, only the first 30 comments can be processed in each analysis.

**Data Source:** https://www.kaggle.com/datasets/kazanova/sentiment140

**Model:** The project utilizes a TensorFlow-based model to predict the sentiment (positive, neutral, or negative) of each comment. The model processes the text comments by encoding them into numerical formats and then uses a pre-trained model for prediction.

**Flask Web Application:** The project includes a Flask server, which allows users to input a YouTube video URL. The system extracts the video ID, retrieves comments from the video using the YouTube Data API, and performs sentiment analysis on them.

YouTube Data API Integration: The application uses the YouTube Data API to fetch comments from a video by its video ID. These comments are then passed to the sentiment analysis model for classification.

**Sentiment Prediction:** Comments are categorized into "Positive," "Negative," or "Neutral" based on the model's predictions.
**Summarized Results:** The tool provides a summary showing the number of positive and negative comments, as well as a rating that represents the percentage of positive comments.
**Limitations:** Due to computational constraints, only 30 comments from each video are processed in the current implementation.

This project can be extended to include more comments or additional features such as graphical representations of the results, integration of more sophisticated models, and scalability improvements.
