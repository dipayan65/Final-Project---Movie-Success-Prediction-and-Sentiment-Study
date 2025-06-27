# 🎬 Movie Success Prediction & Sentiment Analysis

This project uses machine learning and natural language processing to predict whether a movie will be a **Hit** or **Flop**, based on its metadata and audience sentiment from IMDB reviews.

---

## 📌 Project Highlights

- ✅ Predict movie success using metadata (budget, votes, runtime, etc.)
- 💬 Perform sentiment analysis using VADER (from NLTK)
- 🌐 Deploy a Streamlit app for interactive predictions
- 📊 Visualize insights with word clouds, confusion matrix, and feature importance

---

## 🛠 Tools & Technologies Used

- Python (Pandas, NumPy, Scikit-learn)
- NLTK (VADER Sentiment)
- Matplotlib & Seaborn
- Streamlit
- Google Colab / Jupyter Notebook

---

## 📂 Project Structure

```
movie-success-prediction/
│
├── data/
│   ├── IMDB Dataset.csv
│   └── tmdb_5000_movies.csv
│
├── model/
│   └── rf_movie_model.pkl
│
├── app.py                  # Streamlit app
├── Movie_Success_Report.pdf
├── Movie_Success_Colab.ipynb
├── movie_success_predictions.csv
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run the Streamlit App

```bash
# Step 1: Install dependencies
pip install -r requirements.txt

# Step 2: Run the app
streamlit run app.py
```

---

## 🧠 Model Info

- Classification using **Random Forest** and **Logistic Regression**
- Features: budget, popularity, vote average, vote count, runtime, avg sentiment
- Sentiment extracted using VADER and joined by movie title

---

## 📈 Visual Outputs

- Word clouds for positive/negative reviews
- Confusion matrix heatmap
- Feature importance bar chart

---

## 📄 Report

A 2-page PDF summary (`Movie_Success_Report.pdf`) includes:
- Introduction, Tools, Steps, Visuals, Conclusion

---

## 🤝 Contributions

Contributions are welcome! Fork this repo, improve it, and make a pull request.

---

## 📧 Contact

Created by **Dipayan Ghosh**  
🔗 [LinkedIn](https://www.linkedin.com/in/dipayan-ghosh-71ba18196)  
🐙 [GitHub](https://github.com/dipayan-ghosh-71ba18196)
