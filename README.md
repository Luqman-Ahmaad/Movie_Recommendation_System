# 🎬 Movie Recommendation System (Content-Based)

This is a **Content-Based Movie Recommendation System** built with **Python**, **scikit-learn**, and **Streamlit**. It recommends movies based on the content (genres, keywords, cast, etc.) using **Cosine Similarity**.

---

## 🔗 Live Demo

🚀 [Click here to try the app]([https://movie-recommendations--system.streamlit.app/.app])
> *(Replace with your actual deployed Streamlit Cloud URL)*

---

## 🧠 How it works

- Extracts features like genres, keywords, overview, cast, and crew
- Combines them into a single text field (called `tags`)
- Transforms tags into vectors using `CountVectorizer`
- Uses **Cosine Similarity** to find movies with similar content
- Recommends top 5 similar movies

---

## 📌 Features

✅ Recommend similar movies based on content  
✅ Clean, simple **Streamlit** web interface  
✅ Lightweight and easy to deploy on **Streamlit Cloud**  
✅ Based on **Cosine Similarity** and **text vectorization**  
✅ Uses **preprocessed movie metadata** for fast performance

---

## 📦 Requirements

- Python
- streamlit
- pandas
- numpy
- scikit-learn
- nltk


  
