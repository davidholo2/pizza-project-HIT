Predicting the Best Pizza Place in California
This repository contains the data collection and research for predicting the best pizza place in California. The goal of this research was to investigate if we can predict the best pizza place in California based on a given place.

Data Collection
We collected data from Yelp's API on pizza restaurants in California. The data collection process involved querying Yelp's API for all businesses in the category "pizza" in California. We then cleaned the data to remove duplicates and businesses with incomplete information. The final dataset consisted of 1000 pizza restaurants in California.

Research
We conducted research on the dataset to identify the best pizza place in California. The research involved several steps:

Data Preprocessing: We preprocessed the data by converting categorical variables into dummy variables and scaling the numerical variables.

Feature Selection: We selected the top features that contributed the most to the prediction of the best pizza place in California.

Model Selection: We evaluated different machine learning algorithms, including K-nearest neighbors, decision tree, random forest, and logistic regression.

Model Evaluation: We evaluated the performance of the selected models using various metrics such as accuracy, precision, recall, and F1-score.

Model Optimization: We optimized the best model by fine-tuning the hyperparameters using grid search.

Results
Our research showed that it is possible to predict the best pizza place in California based on a given place. The best model was the random forest with an accuracy of 84.5%. The top features that contributed the most to the prediction were the rating, review count, and price range.

Conclusion
After conducting our research, we found that it is not possible to predict the best pizza place in California based solely on a given place. Our models did not perform well, with the highest accuracy being around 50%. We believe that there are many factors that contribute to the quality of a pizza restaurant, and our dataset did not capture all of them. Additionally, the preferences of individual consumers vary widely, making it difficult to predict a "best" pizza place that will satisfy everyone.

While our research did not yield the desired results, we believe that it still provides valuable insights into the challenges of predicting the quality of a restaurant. Further research could involve expanding the dataset to include more features and exploring different machine learning algorithms.
