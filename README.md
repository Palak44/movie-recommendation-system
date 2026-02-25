# 🎬 Movie Recommendation System

## 📌 Project Overview

A content-based movie recommendation system that suggests similar movies using cosine similarity on movie metadata. This system analyzes movie features to find and recommend the most similar films based on user input.

## 🛠 Tech Stack

- **Language**: Python
- **Data Processing**: Pandas
- **Machine Learning**: Scikit-learn
- **NLP**: CountVectorizer
- **Algorithm**: Cosine Similarity

## ⚙️ How It Works

The system follows these key steps:

1. **Data Preprocessing** - Clean and prepare the movie dataset
2. **Feature Engineering** - Extract relevant movie attributes
3. **Text Vectorization** - Convert text features to numerical vectors using CountVectorizer
4. **Similarity Matrix Generation** - Compute cosine similarity between all movies
5. **Recommendation Function** - Return top N most similar movies

## 🚀 Quick Start

### Example Usage

```
Input: Avatar
Output: 5 similar recommended movies
```

## 📂 Dataset

- **Source**: TMDB 5000 Movies Dataset (Kaggle)
- **Features**: Movie metadata including genres, keywords, cast, and plot information

## 📈 Future Improvements

- [ ] Add Streamlit Web App for interactive recommendations
- [ ] Deploy online for public access
- [ ] Implement collaborative filtering
- [ ] Add hybrid recommendation approach
- [ ] Include user ratings feedback loop

## 👤 Author

Palak44
