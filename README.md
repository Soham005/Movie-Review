# 🎬 Movie Review Sentiment Analysis App

This project is a **Movie Review Sentiment Analysis App** built with **Python, Scikit-learn, and Streamlit**.  
It classifies user-submitted movie reviews as **Positive 😊** or **Negative 😞** in real time.

---

## 🚀 Features
- Takes a user’s movie review as input
- Uses **TF-IDF Vectorization** for feature extraction
- Predicts sentiment using a trained **Machine Learning model**
- Interactive **Streamlit web app** for easy usage

---

## 🛠 Tech Stack
- **Python 3**
- **Scikit-learn** – ML model & TF-IDF
- **Streamlit** – Frontend for deployment
- **Pandas / NumPy** – Data handling
- **Pickle** – Model persistence

---

## 📂 Project Structure

├── app.py # Streamlit app
├── Movie_Reviews.ipynb # Jupyter notebook (training & EDA)
├── IMDB Dataset-2.csv # Dataset (~50,000 reviews)
├── model.pkl # Trained ML model
├── scaler.pkl # TF-IDF vectorizer (saved)

---

## ⚡ How It Works
1. **Dataset**: IMDB movie reviews (~50k entries)
2. **Preprocessing**: Cleaning, tokenization, and TF-IDF feature extraction
3. **Model Training**: ML model trained for binary classification
4. **Deployment**: Integrated into a **Streamlit app** for real-time predictions

---

## To run the file

streamlit run app.py

📊 Example

Input:

This movie was absolutely fantastic! The story and visuals were amazing.

Output:

Positive Review ✅