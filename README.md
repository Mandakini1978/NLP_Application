 This project built a streamlit application that uses natural language processing to classify the overall sentiment of  book review as positive review or negative review, and provides with a suggested rating, based on reviewer comments.
 
 Model building walkthrough:
 
 Data Clean up via Databrick & Pandas
Converting the Kindle review text data into token counts using CountVectorizer (ScikitLearns)
Convert numerical rating into Positive & Negative review to be use for training/testing
Use Pycaret to create a classification model and compare for Accuracy using F1 Score
Optimize the model by hyperparameter tuning. 
deployment via Streamlit.

link:
https://share.streamlit.io/jlister19/kindlereviewsdeploy/main/new_app.py
