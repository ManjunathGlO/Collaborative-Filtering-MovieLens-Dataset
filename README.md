

<img width="1536" height="1024" alt="ChatGPT Image Jul 5, 2026, 03_06_00 PM" src="https://github.com/user-attachments/assets/fc300309-2fb4-4421-a1b1-33294c9d1ffe" />

<h3 align="center">
  <a href="./CollaborativeFiltering.ipynb">
    <strong>📓 View Jupyter Notebook »</strong>
  </a>
</h3>


# 🎬 Movie Recommendation System using Collaborative Filtering

## Collaborative-Filtering-MovieLens-Dataset
A machine learning project that implements a **Collaborative Filtering Recommendation System** using the MovieLens dataset. The project analyzes user rating behavior to identify similar users and movies, enabling personalized movie recommendations based on historical preferences


## 📌 Business Problem

Streaming platforms like Netflix, Amazon Prime, and Disney+ host thousands of movies, making it difficult for users to discover content they are likely to enjoy.

The goal of this project is to build a recommendation engine that leverages historical user ratings to:

- Recommend movies based on similar users.
- Identify movies with similar viewing patterns.
- Improve user engagement and retention through personalized recommendations.
- Reduce information overload by suggesting relevant content.

---

## 🎯 Objectives

- Analyze MovieLens user rating data.
- Build a user–movie interaction matrix.
- Measure similarity between users and movies.
- Recommend movies using Collaborative Filtering.
- Explore user preferences and movie relationships.

---

## 🔄 Methodology

### 1. Data Collection
- Loaded MovieLens datasets:
  - movies.csv
  - ratings.csv
  - links.csv
  - tags.csv

### 2. Data Preprocessing
- Merged datasets where required.
- Created User–Movie Pivot Tables.
- Filled missing ratings with zero.

### 3. Similarity Computation
- Calculated User-to-User similarity using **Cosine Distance**.
- Calculated Movie-to-Movie similarity using **Correlation Distance**.

### 4. Recommendation Analysis
- Identified the top similar users.
- Found common movies watched by different users.
- Recommended similar movies based on correlation.

### 5. Result Interpretation
- Evaluated recommendation quality.
- Compared user preferences.
- Generated personalized recommendations.

---

## 📊 Key Features

- User-Based Collaborative Filtering
- Movie-Based Collaborative Filtering
- Cosine Similarity
- Correlation Similarity
- User-Movie Pivot Matrix
- Personalized Movie Recommendations
- Exploratory Data Analysis

---

## 📈 Key Insights

- Built a recommendation engine using the MovieLens dataset.
- Identified the Top-5 users similar to a selected user.
- Found movies commonly watched by multiple users.
- Recommended movies similar to **The Godfather (1972)** using correlation analysis.
- Demonstrated how collaborative filtering powers modern recommendation systems. :contentReference[oaicite:1]{index=1}

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- SciPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Project Structure

```
Movie-Recommendation-System/
│
├── data/
│   ├── movies.csv
│   ├── ratings.csv
│   ├── links.csv
│   └── tags.csv
│
├── notebooks/
│   └── CollaborativeFiltering.ipynb
│
├── images/
│   ├── user_similarity.png
│   ├── movie_similarity.png
│   └── recommendation_workflow.png
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## 💼 Skills Demonstrated

- Recommendation Systems
- Collaborative Filtering
- User Similarity Analysis
- Movie Similarity Analysis
- Machine Learning Fundamentals
- Data Preprocessing
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Data Visualization
- Python Programming

---

## 🚀 Future Improvements

- Item-Based Collaborative Filtering
- Matrix Factorization (SVD)
- Hybrid Recommendation System
- Content-Based Recommendation
- Interactive Web Application using Streamlit
- Model Evaluation with Precision@K and Recall@K

---

## 📌 Conclusion

This project demonstrates how collaborative filtering techniques can generate personalized movie recommendations by learning from user behavior. It showcases practical machine learning, data analysis, and recommendation system concepts widely used by platforms like Netflix, Amazon Prime Video, Spotify, and YouTube.



## 👤 Author

**Manjunath G L**  
> - 💼 Aspiring Data Analyst
> - 📍 Bengaluru, India 
> - 📧 Email: manjunathgl064@gmail.com 

If you want to contact me, you can reach me through below handles.

<a href="https://www.linkedin.com/in/manjunathgl/" target="_blank">
  <img src="https://img.shields.io/badge/ManjunathGL-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin"/>
</a>

<a href="https://github.com/ManjunathGlO" target="_blank">
  <img src="https://img.shields.io/badge/ManjunathGl-20232A?style=for-the-badge&logo=Github&logoColor=white" alt="Twitter"/>
</a>


  ## 📄 License

- This project is licensed under the MIT License — you are free to use, modify, and distribute the code with proper attribution.
- Feel free to adapt it for academic, personal, or commercial use.


## Show your support
Give a ⭐️ if you like this project!
