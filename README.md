# 🎬 Movie-Recommendation-System
This project is a Content-Based Movie Recommendation System built with Machine Learning. It recommends similar movies based on a user’s input by analyzing features like genres, keywords, cast, and crew using cosine similarity.The core idea is to help users discover new movies based on what they already like — just like how Netflix or IMDb shows "Recommended for you" suggestions.
 ## 📌 Project Objective
The goal is to build a system that suggests movies similar to a given movie title using content-based filtering. This project uses:
+ Text feature extraction (TF-IDF or CountVectorizer)
+ Cosine similarity
+ Pandas & Scikit-learn for data handling and modeling
  ## 📂 Dataset
The dataset is from Youtube source,Im attaching the csv file  [movies.csv](https://github.com/user-attachments/files/21005558/movies.csv).This Dataset contains Movie titles,Cast and crew,Genre,Keywords,Overview,Popularity, vote average,vote count etc 
# 🧠 How It Works
+ Data Preprocessing
  -  Combine relevant features (e.g., genres, keywords, cast, director)
  - Clean and format text
+ Feature Extraction
  - Convert text data into numeric form using CountVectorizer or TfidfVectorizer
+ Similarity Calculation
  - Compute cosine similarity between all movie vectors
+ Recommendation
  - Based on the user’s input movie title, fetch top N similar movies
  
