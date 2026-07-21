# Assignment 1: Dataset Exploration & Problem Framing

📌 Dataset : https://www.kaggle.com/datasets/shivamb/netflix-shows

**Netflix Movies & TV Shows Dataset**

This dataset contains information about movies and TV shows available on Netflix, including details such as title, type, director, cast, country, release year, rating, duration, genre, and description.


## 🎯 Business Problem

Netflix needs to make informed decisions about content planning and recommendations. A machine learning model can help predict whether new content should be released as a **Movie** or **TV Show** based on its metadata.

This can improve:
- Content planning
- Recommendation systems
- User engagement
- Catalog analysis


## 🤖 Machine Learning Problem

**Problem Type:** Classification

### Justification

The target variable is **`type`**, which has two categories:
- Movie
- TV Show

Since the output is categorical, this is a **Binary Classification** problem.


## 🎯 Target Variable and Key Features

Target variable is `type` and its key features are 

- release_year
- duration
- rating
- listed_in
- country
- director
- cast


## 📊 Dataset Exploration

The following exploration was performed using **Pandas**:

- Dataset Shape
- Data Types
- Missing Values
- Summary Statistics
- Content Distribution
- Country Distribution
- Rating Distribution


## 🔍 Key Observations

1. Movies make up a larger portion of Netflix's catalog than TV Shows.
2. Several important columns such as **director**, **cast**, and **country** contain missing values and require preprocessing.
3. The dataset contains content from many countries and genres, making it suitable for recommendation systems and predictive analysis.


## 🛠️ Tools Used

- Python
- Pandas
- Matplotlib
- Google Colab
- GitHub