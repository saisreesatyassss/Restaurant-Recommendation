# Restaurant Recommendation Flask App

## Overview

The Restaurant Recommendation Flask App is a web application that utilizes natural language processing and collaborative filtering to suggest restaurants based on user preferences. Whether you're a food enthusiast or simply looking for new dining options, this app provides personalized recommendations by analyzing textual reviews and ratings.

## Features

### 1. Predict Restaurant Recommendations
- Input your favorite restaurant, and the app will suggest similar restaurants with comparable reviews.
- Utilizes cosine similarity and TF-IDF to understand the textual patterns of reviews.

### 2. Data Cleaning and Preprocessing
- Handles missing values and duplicates in the Zomato dataset.
- Renames columns for better readability and consistency.
- Converts rating values to a standardized format.

### 3. Flask Web Application
- Utilizes Flask to create a user-friendly web interface.
- Allows users to input their preferred restaurant and receive personalized recommendations.
![img 1](https://github.com/saisreesatyassss/Restaurant-Recommendation/assets/132558766/8d144dcc-2fca-4051-b26b-962195d75943)
![img 2](https://github.com/saisreesatyassss/Restaurant-Recommendation/assets/132558766/ec20c3cb-1726-4213-803e-b0a5684e470d)

## Under the Hood

### Libraries Used
- **Pandas:** Handles data manipulation and preprocessing.
- **Seaborn and Matplotlib:** Creates visualizations for data exploration.
- **Plotly:** Generates interactive plots for an enhanced user experience.
- **Flask:** Develops the web application.
- **NLTK:** NLP library for text processing.
- **Scikit-learn:** Implements machine learning functionalities.

### Data Processing
- Cleans and preprocesses the Zomato dataset for meaningful insights.
- Utilizes TF-IDF and cosine similarity for restaurant recommendations.
- Implements collaborative filtering to suggest restaurants based on user preferences.

### Web Application
- Utilizes Flask to create a web interface for users.
- Allows users to input their favorite restaurant for personalized recommendations.
- Renders recommendations with relevant details such as cuisines, mean rating, and cost.

## Getting Started

1. Clone the repository:

```bash
git clone  https://github.com/saisreesatyassss/AutoMLwebapp
```  

3.  Run the app:
 ```bash
python app.py
```  
