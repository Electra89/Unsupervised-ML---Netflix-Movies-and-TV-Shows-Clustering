

#  Netflix Movies and TV Shows Clustering

<p  align="center">
<img  src="https://media.tenor.com/twG41IiAAscAAAAC/no.gif"  alt="Animated gif netflix Image"  height="382px">
</p>

Welcome to the Netflix Movies and TV Shows Clustering project repository. This project aims to explore, analyze, and cluster the Netflix dataset to uncover insights into the content landscape and identify patterns within the movies and TV shows.

## Problem Statement

The Netflix dataset of movies and TV shows up to 2019, sourced from Flixable, a third-party Netflix search engine. The analysis aims to comprehend the content landscape across countries, assess Netflix's focus on TV shows versus movies in recent years, and cluster similar content based on text-based features. The dataset reflects a shift in Netflix's content strategy, revealing a substantial increase in TV shows and a significant decrease in movies since 2010, as reported by Flixable in 2018. The exploration seeks to uncover additional insights from this dataset.

##  Project Summary

### Key Steps

### 1. Data Preprocessing

-   **Handling Null Values:** Implemented strategies to handle missing data ensuring data integrity.
-   **Managing Nested Columns:** Resolved nested columns to enhance data visualization and analysis.

### 2. Rating Categorization

-   **Categorizing Ratings:** Classified ratings into groups (adult, children's, family-friendly, not rated) for better understanding.

### 3. Exploratory Data Analysis (EDA)

-   **Insightful Analysis:** Conducted EDA to gain insights into the dataset, identifying trends, patterns, and outliers.

### 4. Clustering

-   **Feature Selection:** Utilized attributes like director, cast, country, genre, rating, and description.
-   **TF-IDF Vectorization:** Processed text data through TF-IDF vectorization.
-   **Reducing Dimensionality:** Implemented PCA to enhance performance.

### 5. Clustering Algorithms

-   **K-Means and Hierarchical Clustering:** Both K-Means Clustering and Agglomerative Hierarchical Clustering algorithms were utilized to create clusters. 
-   **Optimal Clusters:** The optimal number of clusters was determined (4 for K-Means and 2 for hierarchical clustering) using various evaluation methods.

### 6. Recommender System

-   **Content-Based Recommender:** Developed a content-based recommender system using a cosine similarity matrix.


## Tech-stack Used
- Python
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
  
## Key Findings
- Netflix has a lot more movies than TV shows.
- The United States is a major contributor to Netflix, leading in both movies (1850) and TV shows (705)
- Adult and teen content ratings have the highest counts
-   Bollywood actors dominate movies, while Japanese anime-related content holds sway in TV shows.
- we have found out number cluster would be 4 
  

## Conclusion
This project underscores the application of data analysis, machine learning, and visualization techniques to understand and cluster Netflix movies and TV shows. By sharing our findings and approach, we aim to contribute insights into content analysis and recommendation strategies.
 

## Code and Notebooks
Access the [Colab notebook](https://github.com/Electra89/Unsupervised-ML---Netflix-Movies-and-TV-Shows-Clustering/blob/main/Unsupervised_ML_Netflix_Movies_and_TV_Shows_Clustering.ipynb) to view the detailed project implementation.

## Data Source

The analysis is based on the Airbnb_NYC. You can find more about the dataset [here](https://github.com/Electra89/Unsupervised-ML---Netflix-Movies-and-TV-Shows-Clustering/blob/main/NETFLIX%20MOVIES%20AND%20TV%20SHOWS%20CLUSTERING.csv).


## License

This project is licensed under the [MIT License](LICENSE).

