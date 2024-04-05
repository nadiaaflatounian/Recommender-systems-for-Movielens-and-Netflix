
# MovieLens Recommendation System Overview (SVD & SVD++)

This system is designed to recommend movies to users based on their historical interactions with a dataset, leveraging both explicit and implicit feedback mechanisms. Key functions and steps include:

## SVD
- **Data Cleaning**
- **Data Preparation**: The data is split into three distinct sets: training, validation, and testing. This separation allows us to train the model, fine-tune it, and finally evaluate its performance with unseen data.
- **User-Item Matrix Creation**: We transform the data into a user-item matrix, where rows represent users, columns represent movies, and values are ratings. Missing values are filled with zeros, indicating unrated movies.
- **Matrix Factorization with SVD**: We apply Singular Value Decomposition (SVD) to the training matrix, decomposing it into user and item (movie) matrices. This factorization helps in capturing the latent factors associated with users' preferences and movies' characteristics.
- **Prediction and Evaluation**: The system predicts ratings by reconstructing the user-item matrix from the decomposed matrices. Predictions are then compared against actual ratings to evaluate the model's accuracy, using metrics such as RMSE (Root Mean Square Error) and MAE (Mean Absolute Error).
- **Recommendations**: Finally, the system can recommend movies to a user by selecting movies with the highest predicted ratings that the user has not yet rated.

## SVD++
1. **Data Sampling**: The dataset is sampled to include a manageable subset of data, representing a specific percentage of the original data.
2. **Feedback Identification**: Both explicit ratings and implicit feedback (such as viewing history) are utilized. Ratings above a certain threshold are considered positive implicit feedback.
3. **Data Splitting**: The sampled dataset is split into training, validation, and testing sets to facilitate model training and evaluation.
4. **Matrix Factorization**: Utilizes techniques such as SVD and SVD++ to factorize the user-item interaction matrix into latent factors, capturing underlying patterns in user preferences and item characteristics.
5. **Prediction and Evaluation**: The system predicts ratings for unseen movies based on the factorized matrices and evaluates the accuracy of these predictions using metrics like RMSE (Root Mean Square Error).
6. **Hyperparameter Tuning**: This technique employs grid search to find the optimal set of parameters for the model, improving prediction accuracy.
7. **Recommendations**: Provides personalized movie recommendations to users based on predicted ratings for unseen movies, aiming to enhance user satisfaction and engagement.
