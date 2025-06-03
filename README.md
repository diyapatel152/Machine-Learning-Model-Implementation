# Machine-Learning-Model-Implementation

COMPANY: CODETECH IT SOLUTIONS

NAME: PATEL DIYA 

INTERN ID :CT04DF1541

DOMAIN: PYTHON PROGRAMMING

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

## TASK DESCRIOTON:

This project is part of my internship task where the goal is to build a machine learning model that can identify whether a text message is spam or not spam (ham). For this, I used a dataset called spam.csv which contains thousands of real SMS messages labeled as spam or ham.

The main idea is to train a program that can learn from these messages and make predictions on new, unseen messages. The project was completed using Python in a Jupyter Notebook, along with popular libraries like Pandas, Scikit-learn, and Matplotlib.

Two important columns in the dataset used for this study are "v1", which shows the label indicating whether a message is "spam" or "ham," and v2, which shows the text of the message itself.  The dataset was cleaned and preprocessed prior to the application of any machine learning techniques.  Any extraneous columns had to be eliminated, missing values had to be handled to maintain data consistency, and the categorical labels had to be converted into numerical format, with "1" being assigned to "spam" and "0" to "ham."  To properly prepare the data for machine learning modeling, several procedures were necessary.

To generate an efficient spam detection model, this project followed to a number of crucial procedures. Pandas was used to load the data first, and preliminary checks were made to find and deal with any missing or undesirable numbers.  To maintain data integrity, extraneous columns were eliminated and any rows lacking labels were deleted during the data cleaning stage.  Since raw text cannot be directly interpreted by machine learning models, text preprocessing was then done. In order to solve this, the bag-of-words method was employed to transform the text messages into numerical representations using CountVectorizer. Following cleaning and vectorization, the data was divided into training and testing sets, with 20% set aside for testing and 80% utilized to train the model. Because of its success in text classification challenges, the Multinomial Naive Bayes algorithm was selected for model training.  Ultimately, the trained model demonstrated great performance in accurately recognizing spam messages when evaluated using the confusion matrix and accuracy score during the model evaluation stage.

**Outcomes**
- Built a spam detection model with strong performance metrics.
- Gained practical experience in data preprocessing, vectorization, and classification.
- Learned how to clean real-world text data and handle missing labels.
- Applied model evaluation techniques to validate the performance.
