
# SMS/Email Spam Detection System using NLP

## 📋 Description

This project is an SMS/Email Spam Detection System that uses Natural Language Processing (NLP) techniques to classify SMS messages as spam or ham (not spam). By analyzing the text data, the system detects patterns commonly associated with spam messages and provides a fast, reliable classification.




## 🚀 Features

**Spam Detection:** Accurately classifies SMS messages as spam or ham.

**Real-Time Analysis:** Provides instant results for SMS classification.

**User-Friendly Interface:** Simple and intuitive for seamless usage.

**Scalable Model:**  Easily adaptable for larger datasets.

**Efficient Preprocessing:** Removes noise like stop words, punctuation, and performs tokenization.
## 🔧 Tech Stack

**Programming Language:** Python

**Libraries/Frameworks:** NLTK 

**Data Preprocessing:** Pandas, Numpy

**Visualization:** Matplotlib, wordcloud libraries

**Model Used:** Naive Bayes or Logistic Regression

**Deployment:** Flask/Streamlit for creating a user interface
## 🧠 How It Works

**Data Collection:** 

The model uses a labeled dataset of SMS messages with spam/ham labels.

**Data Cleaning:**

• Remove unnecessary columns

• Rename the column names

• Change ham -> 0 & spam -> 1

• Check missing values and duplicate values

**Data Preprocessing:**

• All Characters convert in Lower Case

• **Tokenization -** Convert the text into smaller parts

• Removing special characters

• Removing StopWords and Punctuation

• **Stemming/Lemmatization -** Dance, Dancing, Danced convert in  Dance

**Model Training:**

• A classification algorithm (e.g., Naive Bayes) is trained on the preprocessed data.


**Prediction:**

• User input is preprocessed, and the trained model predicts whether the SMS is spam or ham.

**Output:**

Displays the result to the user (e.g., "Spam" or "Not Spam").
## 🛠️ Installation and Setup

**1.) Clone the repository:**

git clone https://github.com/Kaif2596/SMS-Spam-Detection-System-using-NLP.git
cd SMS Spam Detection System

**2.) Install dependencies:**

pip install -r requirements.txt

**3.) Run the application:**

streamlit run app.py



## 📊 Demo

**•	Spam and Ham Ratio**

![image alt](https://github.com/Kaif2596/SMS-Spam-Detection-System-using-NLP/blob/main/Image%2001.png?raw=true)


**• Clean Dataset:**

![image alt](https://github.com/Kaif2596/SMS-Spam-Detection-System-using-NLP/blob/main/Image%2002.png?raw=true)


**• WordCloud:**

![image alt](https://github.com/Kaif2596/SMS-Spam-Detection-System-using-NLP/blob/main/Image%2003.png?raw=true)



 
## 📈 Results

**• Application Demo:**

![image alt](https://github.com/Kaif2596/SMS-Spam-Detection-System-using-NLP/blob/main/Image%2004.png?raw=true)


**Dataset Example:**

• **Sample spam message:** "Congratulations! You've won a $1,000 gift card. Claim now!"

• **Sample ham message:** "Hey, are we still on for the meeting at 3 PM?"



**Output Example:** 

• **Input:** "Win $1000 now by clicking the link!"

• **Output:** Spam


