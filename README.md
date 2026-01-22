# 🎬 Movie & TV Recommendation System

A content-based movie and TV show recommendation system built using Python, TF-IDF, and cosine similarity on Netflix data.

📌 What This Project Does

This project recommends similar movies or TV shows when a user enters a title.
The recommendations are based on genre and description similarity.

▶️ How to Run

1. Open the Jupyter notebook: `movie_tv_recommendation_system.ipynb`
2. Run all cells
3. Call the function:
```python
recommend("Kota Factory")

🛠️ Technologies Used

* Python
* Pandas & NumPy – Data processing
* Matplotlib – Data visualization
* Scikit-learn – TF-IDF & cosine similarity
* Jupyter Notebook

📂 Dataset

- Netflix Movies and TV Shows Dataset
- Contains information such as:
    *Title
    *Type (Movie / TV Show)
    *Genre
    *Description
    *Release year
    *Rating

⚙️ How the Recommendation System Works

1.Clean and preprocess the dataset
2.Combine genre and description into a single text feature
3.Convert text into numerical vectors using TF-IDF
4.Compute similarity between titles using cosine similarity
5.Recommend top similar movies or TV shows
