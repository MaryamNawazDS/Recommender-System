# 🎬 Recommender System Using Collaborative Filtering

## 📌 Project Overview

This project demonstrates the development of a **movie recommender system** using **collaborative filtering**. The system is trained on the **MovieLens 100k Dataset**—a widely used benchmark dataset containing user ratings for movies. The primary objective is to predict a user's rating for unseen movies based on the preferences of similar users.

---

## 📂 Dataset: MovieLens 100k

- **Source:** [GroupLens Research](https://grouplens.org/datasets/movielens/100k/)
- **Size:** 100,000 ratings
- **Users:** 943
- **Movies:** 1,682
- **Ratings:** From 1 to 5 stars
- **Format:** User-Movie-Rating triples
- **Purpose:** Frequently used in research for benchmarking collaborative filtering algorithms

---

## 🎯 Objectives

- Load and explore the **MovieLens 100k** dataset.
- Build a **user-based collaborative filtering** model using similarity metrics.
- Predict missing movie ratings for users.
- Recommend movies based on predicted ratings.
- Evaluate performance using standard metrics like **RMSE (Root Mean Squared Error)**.

---

## 🛠️ Techniques Used

- **Collaborative Filtering** (User-User)
- **Similarity Metrics**:
  - Cosine Similarity
  - Pearson Correlation
- **Sparse Matrix Representation**
- **Data Preprocessing** and **Pivot Tables**
- **Model Evaluation**: RMSE

---

## 🧪 How to Use

1. **Prepare the dataset**:
   - Download the [MovieLens 100k dataset](https://grouplens.org/datasets/movielens/100k/)
   - Place the files in the appropriate directory.
   - Ensure paths in the notebook are correctly set.

2. **Run the notebook**:
   - Open `Recommender_System.ipynb` in Jupyter Notebook.
   - Execute each cell sequentially to preprocess data, train the model, and generate recommendations.

---

## 📈 Sample Output

Here’s an example of the system recommending top 5 movies to a user:

Recommended movies for User 10:

Star Wars (1977)

Fargo (1996)

Return of the Jedi (1983)

Toy Story (1995)

Silence of the Lambs, The (1991)



> 📌 **Note:** Recommendations will vary depending on the similarity threshold, number of neighbors, and dataset version.

---

## ✅ Key Takeaways

- Developed a fully functional **movie recommender system** using collaborative filtering.
- Demonstrated the power of **user similarity** to uncover hidden preferences.
- Highlighted the importance of **data sparsity** and **cold start problems** in recommender systems.
- Provided a baseline for further enhancements such as:
  - Item-based filtering
  - Matrix factorization (e.g., SVD)
  - Deep learning-based recommenders

---

## 🚀 Future Enhancements

- Incorporate **item-based collaborative filtering** for comparison.
- Explore **hybrid recommender systems** combining content and collaborative signals.
- Integrate **implicit feedback** such as clicks or views.
- Build a **web interface** to serve real-time recommendations.

---


