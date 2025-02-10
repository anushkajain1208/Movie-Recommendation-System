# Movie-Recommendation-System

## Overview
This project is a **Movie Recommendation System** that utilizes both **Collaborative Filtering (SVD & KNN-based)** and **Content-Based Filtering (TF-IDF and Cosine Similarity)** to provide personalized movie recommendations. The system is built using **Python, Flask, and Surprise** for recommendation algorithms.

## Features
- **Hybrid Recommendation System** (Combining Collaborative and Content-Based Filtering)
- **SVD (Singular Value Decomposition) Collaborative Filtering**
- **KNN (User-Based) Collaborative Filtering**
- **Content-Based Filtering using TF-IDF**
- **Flask Web Interface** for user interaction
- **Ngrok for Public Access** to the locally hosted application

## Tech Stack
- **Python** (Pandas, NumPy, Scikit-Surprise, Scikit-Learn, Flask)
- **Flask** (For the web interface)
- **Pyngrok** (For public URL access)

## Installation & Setup
### 1. Clone the repository
```bash
git clone https://github.com/anushkajain1208/movie-recommendation-system.git
cd movie-recommendation-system
```

### 2. Install Dependencies
Ensure you have Python installed (preferably Python 3.7+). Then install the required dependencies:
```bash
pip install flask-ngrok pyngrok scikit-surprise flask pandas numpy scikit-learn
```

### 3. Add Dataset Files
Make sure you have the following dataset files in the same directory:
- **ratings.csv** (Contains user ratings for movies)
- **movies.csv** (Contains movie titles and IDs)


### 4. Access the Web Application
The script will print a public URL from Ngrok. Open that link in your browser to access the application.

## Usage
- Enter a **User ID** in the input field.
- Click **Get Recommendations**.
- The system will generate a list of recommended movies based on hybrid filtering.
- Click **Go Back** to input another user ID.



