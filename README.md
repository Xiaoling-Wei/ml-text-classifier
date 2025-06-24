python \n
python -m venv mystreamlitapp
mystreamlitapp1\Scripts\activa
cd streamlit_ml_ap
pip install -r requirements.txt
streamlit run app.py

# 🤖 ML Text Classification App

A user-friendly Streamlit web app for sentiment analysis using machine learning models such as **Logistic Regression**, **SVM**, **Decision Tree**, and **AdaBoost**.

---

## 🚀 Features

- 🔮 **Single Prediction**: Enter text and get an instant prediction with confidence scores.
- 📁 **Batch Processing**: Upload a `.txt` or `.csv` file to classify multiple texts at once.
- ⚖️ **Model Comparison**: Compare predictions from different models side-by-side.
- 📊 **Model Info**: View model descriptions, feature engineering details, and training info.
- ❓ **Help Section**: Step-by-step instructions and troubleshooting tips.

---

## 🧠 Models Used

All models use **TF-IDF vectorization** with unigrams and bigrams:

- 📊 AdaBoost
- 🌲 Decision Tree
- 📈 SVM (with probability enabled)

Models are pre-trained and saved as `.pkl` files in the `models/` directory.

---

## 🗂️ Project Structure

streamlit_ml_app/
├── app.py # Main Streamlit app
├── requirements.txt # Python dependencies
├── models/ # Trained ML models
│ ├── sentiment_analysis_pipeline.pkl
│ ├── tfidf_vectorizer.pkl
│ ├── ada_pipeline.pkl
│ ├── dt_pipeline.pkl
│ └── svm_pipeline.pkl
├── sample_data/ # Sample .txt and .csv for batch testing
│ ├── sample_texts.txt
│ └── sample_data.csv
└── README.md # This file


![image](https://github.com/user-attachments/assets/fa37b6c8-804d-4455-b6e6-84fbd6d48858)
