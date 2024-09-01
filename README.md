# Usecase-8-Project-5

## Streamlit link: https://team-pirates-project-5.streamlit.app/

### The Final presentation will be on Sunday
### Due Date: Sun , 1 Sep, 10:00 am.
## Final Deliverables:
- Notebook file(.ipynb).
- Presentation 8 mins.
- Deployed fastAPI, streamlit app
- README.md file.


## Team Members:
* Ziyad
* Salman
* Musab
* Abdullah

## Introduction:
The objective of this project is to perform Exploratory Data Analysis (EDA) on a dataset related to university rankings. The goal is to uncover meaningful insights and patterns within the data that can help us better understand the factors that contribute to a university's ranking.

## Dataset Synopsis and Origin:
The dataset used for this project was sourced from Coursera, a popular online learning platform that offers courses from universities and companies worldwide. The dataset includes various features such as the course name, provider, ratings, number of reviews, duration, and other relevant attributes. This data was extracted through web scraping techniques from [Coursera](https://www.coursera.org/search?query=data&language=English&sortBy=BEST_MATCH) to compile a comprehensive overview of the available courses, enabling further analysis and insights into the patterns and factors contributing to course popularity and performance on the platform.

## Model Selection:
For clustering, we used two different machine learning models: DBSCAN and K-means. We tested both models to see how well they worked with our specific dataset. After testing, we found that K-means gave us better results than DBSCAN. K-means was very good at managing our data and making clear groups. Which was key to our project's success.

## Feature Engineering:
- **Initialize the LabelEncoder**: A LabelEncoder object was created to convert categorical text data into a model-understandable numerical format.

## Hyperparameter Optimization:

## Performance Metric Visuals:

## Best Model Determination:
We chose the best-performing model based on its ability to effectively cluster data and its quantitative performance metrics. Here’s why we selected K-means as our optimal model:

- **Effective Clustering**: K-means demonstrated superior capability in forming distinct and interpretable clusters compared to DBSCAN. This was evident from the clear segmentation of customers into meaningful groups based on their purchasing behaviors.

- **Silhouette Score**: K-means achieved a high silhouette score, indicating that the clusters were well-separated and cohesive. This metric helped confirm that K-means was not only clustering data but doing so in a way that was statistically significant and relevant for our analysis.

These criteria—effective clustering and a good silhouette score—were key in determining that K-means was the best model for our project needs.

## Feature and Prediction Insights:
