# 📚 Book Recommendation System

This project is a **Content-Based Book Recommendation System** that suggests books similar to the one provided by the user. It analyzes various features of the input book and finds the most relevant matches using text-based similarity techniques.

## 🚀 Project Goal

To build a content-based filtering system that recommends books similar to a given title using metadata such as the book's title, author, publisher, and more.

## 🧰 Technologies Used

- **Python**
- **Pandas** – for data manipulation  
- **Seaborn & Matplotlib** – for data visualization  
- **scikit-learn** – for cosine similarity, MinMaxScaler, and TfidfVectorizer  
- **NLTK** – for text preprocessing (stopwords, lemmatization)

## 📦 Dataset

The dataset used for this project is from **Kaggle**:  
[Books Dataset](https://www.kaggle.com/datasets/abdallahwagih/books-dataset)

It contains information about:
- Book titles
- Authors
- Categories
- Published year
- Description
- Average Rating
- Number of pages
- Ratings Count
- ISBN

## 🔍 Main Features

- **Search by book title**  
- **Get top similar book recommendations** based on:
  - Author
  - Title
  - Publisher
  - and combined metadata

## 🧠 How It Works

1. **Preprocessing**:
   - Cleaning text data
   - Removing stopwords
   - Lemmatizing key features

2. **Feature Engineering**:
   - Creating a "soup" of relevant book features
   - Vectorizing the soup using `TfidfVectorizer`

3. **Recommendation Logic**:
   - Calculating cosine similarity between books
   - Returning the top N most similar books to the input title

## 📌 Future Improvements

- Deploy the model using **Streamlit** or **Flask**
- Add collaborative filtering or hybrid recommendation
