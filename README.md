# Email Spam Detector

A machine learning–based web application that classifies emails as **Spam** or **Not Spam (Ham)** using Natural Language Processing (NLP) techniques and a Logistic Regression model. The trained model is deployed using a Flask web framework for real-time prediction.

---

## 📌 Project Overview

Email spam is a persistent problem that affects productivity and security.  
This project builds a supervised machine learning model to automatically detect spam emails based on their textual content.

The system follows a complete ML pipeline:
- Data preprocessing
- Feature extraction using TF-IDF
- Model training with Logistic Regression
- Model serialization
- Deployment using Flask

---

## 🛠️ Technologies Used

- Python
- Scikit-learn
- Pandas & NumPy
- Natural Language Processing (TF-IDF Vectorizer)
- Flask (Web Framework)
- HTML (Frontend templates)
- Pickle (Model persistence)

---

## 📂 Project Structure


Email_Spam_Detector/
│
├── app.py # Flask application
├── templates/ # HTML templates for UI
├── Email Spam Classification Using Python.ipynb # Model training notebook
├── feature_extraction.pkl # Saved TF-IDF vectorizer
├── logistic_regression.pkl # Trained ML model
├── mail_data.csv # Dataset
├── README.md # Project documentation


---

## ⚙️ How It Works

1. Email text is provided as input through the web interface.
2. The text is transformed using a pre-trained TF-IDF vectorizer.
3. The processed input is passed to a Logistic Regression model.
4. The model predicts whether the email is **Spam** or **Ham**.
5. The result is displayed on the web page.

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Email_Spam_Detector.git

Navigate to the project directory:

cd Email_Spam_Detector

Install required dependencies:

pip install flask scikit-learn pandas numpy

Run the Flask application:

python app.py

Open your browser and go to:

http://127.0.0.1:5000/
📊 Model Details

Algorithm: Logistic Regression

Feature Extraction: TF-IDF Vectorization

Type: Binary Classification (Spam / Ham)

Logistic Regression was chosen for its simplicity, speed, and interpretability, making it suitable for text classification tasks.

✅ Output

Spam → Unwanted or malicious email

Ham → Legitimate email

The prediction is shown instantly through the web interface.

📈 Future Improvements

Improve accuracy using advanced models (Naive Bayes, SVM, or Deep Learning)

Add email subject analysis

Enhance UI design

Deploy the application online (Heroku / Render)

👤 Author

Developed by Jackson Richard 
B.Tech – Information Technology
