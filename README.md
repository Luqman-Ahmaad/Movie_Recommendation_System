# 🎬 Movie Recommendation System (Content-Based)

This is a **Content-Based Movie Recommendation System** built with **Python**, **scikit-learn**, and **Streamlit**. It recommends movies based on the content (genres, keywords, cast, etc.) using **Cosine Similarity**.

---

## 🔗 Live Demo

🚀 [Click here to try the app](https://movie-recommendations--system.streamlit.app)

---

## 🧠 How it Works

- Extracts features like genres, keywords, overview, cast, and crew from the dataset.
- Combines them into a single text field (`tags`) per movie.
- Converts the tags into numeric vectors using `CountVectorizer`.
- Uses **Cosine Similarity** to compute similarity between movies.
- Recommends the **Top 5 most similar movies** based on the selected title.

---

## 📌 Features

✅ Content-based filtering using movie metadata  
✅ Built with **Streamlit** for an interactive web UI  
✅ Fast and responsive recommendations  
✅ Uses **Cosine Similarity** for measuring movie similarity  
✅ Suitable for small to medium-sized datasets  
✅ Easily deployable on **Streamlit Cloud**


