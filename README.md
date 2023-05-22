# sms-email-spam-detector
Model to detect if a sms/email is spam or not
SMS_Spam_Detection.ipynb is the python file to get the data from "spam.csv" file and do the data wrangling, data cleaning,
EDA,data preprocessing, vectorization, data modelling and data validation.
model.pkl is the pickle file having the trained model
vectorizer.pkl is the pickle file having the vectorizer to create tfidf vector for the test data(sms/email) 
app.py is the application file that will run on http://localhost:8501/ using streamlit.
