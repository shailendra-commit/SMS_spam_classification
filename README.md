This project is a Streamlit-based web application that detects spam SMS messages using Natural Language Processing (NLP) techniques. The model has been trained using TF-IDF, Count Vectorizer, and Bag of Words to classify messages as spam or ham (not spam). The entire pipeline includes data cleaning, exploratory data analysis (EDA), text preprocessing, model building, evaluation, and deployment.

🛠️ Steps Followed

1️⃣ Data Cleaning

Removed special characters, stopwords, and unnecessary spaces.

Converted text to lowercase.

Handled missing values (if any).

2️⃣ Exploratory Data Analysis (EDA)

Visualized data distributions of spam vs. ham messages.

Analyzed the frequency of words in spam and non-spam messages.

Used word clouds to understand common words in each category.

3️⃣ Text Preprocessing

Tokenization: Split text into individual words.

Lemmatization: Converted words to their root forms.

Vectorization: Converted text into numerical representations using:

TF-IDF (Term Frequency-Inverse Document Frequency)

Count Vectorizer

Bag of Words

4️⃣ Model Building

Trained multiple machine learning models, including:

5️⃣ Model Evaluation
Evaluated model performance using:
Accuracy, Precision, Recall, and F1-score.

6️⃣ Model Improvement
Hyperparameter tuning for improved accuracy.
Feature engineering for better text representations.

7️⃣ Web App Development
Developed a user-friendly Streamlit web application.
The user can enter an SMS message, and the model predicts whether it's Spam or Ham.
