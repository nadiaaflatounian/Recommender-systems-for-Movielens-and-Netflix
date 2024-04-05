# System-Development
Building a recommender system 


**Netflix and MovieLens Recommendation System**

This repository contains the code for building a recommendation system using the Netflix and MovieLens dataset. The recommendation system is implemented using various methods, each represented in different files.

### Files Overview:

1. **Netflix Cleaning.ipynb**: This notebook combines datasets and performs data cleaning, including handling missing values.

2. **Netflix EDA.ipynb**: This notebook focuses on exploratory data analysis (EDA) and feature engineering to gain insights into the dataset. at the finla part prepared dataset for building recommender system is saved.

3. **Netflix_CFuserbased.ipynb**: Implements User-Based Collaborative Filtering using K-Nearest Neighbors (KNN) prediction and classification technique on Netflix dataset.

4. **MovieLens_CFuserbased.ipynb**: Implements User-Based Collaborative Filtering using K-Nearest Neighbors (KNN) prediction and classification technique on MovieLens dataset.

5. **Netflix SVD.ipynb**: This notebook contains SVD and SVD++  methods implemented for recommender system on Netflix dataset.

6. **MovieLens_SVD_FinalVersion.ipynb**: This notebook contains SVD and SVD++  methods implemented for recommender system on MovieLens dataset.

7. **MovieLens_CF(Item_Genre)_FinalVersion.ipynb**: This notebook aims to develop a movie recommendation system by implementing Item-Based Collaborative Filtering using K-Nearest Neighbors (KNN) prediction and classification techniques on the MovieLens dataset. It focuses on analyzing user ratings and movie genres to provide personalized movie recommendations. Key features include data preprocessing, genre analysis, and implementing similarity measures for recommendation.

8. **Netflix_CF(Item)_FinalVersion.ipynb**: This notebook outlines the process of creating a movie recommendation system by implementing Item-Based Collaborative Filtering using K-Nearest Neighbors (KNN) prediction and classification techniques on the Netflix dataset. It emphasizes feature engineering, genre analysis, similarity computations, and model evaluation. The system aims to provide personalized movie recommendations based on user ratings and genre preferences.


### Usage:

To use this repository, follow these steps:

1. Run the notebooks in the following order:
   - Netflix_Cleaning.ipynb
   - Netflix_EDA.ipynb
   - Other notebooks using saved file in Netflix_EDA.ipynb
     
**Note** All cleaning, EDA and implementation for Item based methods are integrated in Files MovieLens_SVD_FinalVersion.ipynb, MovieLens_CF(Item_Genre)_FinalVersion.ipynb and Netflix_CF(Item)_FinalVersion.ipynb are 

2. Ensure all necessary libraries and dependencies are installed.

3. Adjust parameters and experiment with different methods as needed.

### Note:

- Each notebook provides detailed explanations and insights into the implementation and results.
- Feel free to modify the code according to specific requirements or to experiment with different techniques.

### Acknowledgments:

This project was completed as part of my System Development course..

