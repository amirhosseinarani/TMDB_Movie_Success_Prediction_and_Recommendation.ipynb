## Overview
In this project, we delve into the cinematic world using The Movie Database (TMDB) dataset to predict the financial success of movies and to curate a personalized movie recommendation engine. Employing a suite of machine learning models, we analyze and forecast movie revenue and profitability. We also develop a recommendation system, leveraging content-based filtering to suggest movies that resonate with users' preferences.

## Datasets
The project uses two primary datasets:
- `df_movies`: It contains comprehensive details about movies, including budget, genres, homepage URL, unique identifiers, keywords, original language, title, overview, popularity metrics, production companies, production countries, release dates, revenue figures, runtime, spoken languages, status, taglines, and user engagement data measured by vote count.
- `df_credits`: This dataset enriches the `df_movies` with granular details of cast and crew, providing deeper insights into the movies' production backgrounds.

## Machine Learning Models
Machine learning models were deployed in two different predictive capacities:

### Regression Analysis
For predicting the scaled revenue (`revenue_scaled (M$)`) of movies:
- **Linear Regression**: Showcased a solid performance with an R-squared value indicating the proportion of variance explained by the model.
- **Lasso Regression**: Displayed slight improvements over linear regression in error metrics, suggesting a more robust fit to the data.

### Classification Analysis
To determine the profitability of movies:
- **Logistic Regression**
- **Decision Tree**
- **Random Forest**: Emerged as the best model, exhibiting the highest accuracy and a commendable balance across all performance metrics.
- **XGBoost**

## Recommender System
A sophisticated recommender system was built on the pillars of genres, keywords, production details, and linguistic analysis. By amalgamating these aspects into a singular feature vector per movie and leveraging the nuanced TF-IDF Vectorization, the system quantifies content similarity with high precision. 

## Conclusion
This exploration into the TMDB dataset yielded predictive models that ascertain revenue and profitability with substantial accuracy. The content-based recommendation system stands as a testament to the potential of machine learning in enhancing user experience. Such systems are pivotal to platforms like Netflix and Spotify, whose success hinges on the art of accurate content suggestion.

## How to Use
Interested parties can utilize the prediction models or the recommender system by running the Jupyter notebook `TMBD_Project.ipynb` provided. Make sure all the required libraries are installed and follow the instructions within the notebook to execute the desired sections.

## Author
- Amirhossein Arani


