# Tripadvsior-Using-AI-algorithms
Comparing Random Forest, Decision Tree, and Liner Regression to develop the best Tripadvisor

## Rome Hotel Rating Prediction: A Machine Learning Study
### Project Overview
This project aims to predict hotel ratings on TripAdvisor for accommodations located in Rome. By analyzing various features such as hotel class, review counts, and amenities, we built a system to understand what specific factors lead to higher guest satisfaction.

### Data Preparation
The dataset was cleaned by removing unnecessary information like hotel URLs and names. We handled missing values and converted the "class" feature into a numeric format to make it readable for our machine learning models. To ensure a fair evaluation, we split the data: 80% was used for training the models, and 20% was reserved for testing their accuracy.

### Models and Evaluation
We compared three different machine learning models to find the most accurate way to predict ratings. To judge which model performed the best, we used a metric called RMSE (Root Mean Squared Error). A lower RMSE means the model's predictions are closer to the actual ratings.

Linear Regression: This model looks for a straight-line relationship between the features and the rating. It achieved an RMSE of 0.7676.

Decision Tree Regressor: This model makes predictions by following a tree-like structure of yes/no questions. It had the highest error with an RMSE of 0.9575.

Random Forest Regressor: This is an "ensemble" model that combines many decision trees to reach a more stable and accurate result. It performed the best with the lowest RMSE of 0.7609.

### Key Findings from the Best Model
By analyzing the Random Forest model, we identified the features that have the biggest impact on a hotel's score:

Engagement: The number of reviews is the strongest predictor of a rating.

Technology: Providing "Free High-Speed Wi-Fi" is extremely important to modern guests.

Comfort: Because of Rome's climate, having "Air Conditioning" is a major factor in guest satisfaction.

Trust and Quality: Official awards like the "Certificate of Excellence" significantly boost a hotel's predicted score.

### Business Strategies
Based on our machine learning results, here are recommendations for hotel managers in Rome:

Prioritize Digital Needs: Since high-speed internet is a top priority for guests, hotels should ensure their Wi-Fi is both fast and reliable.

Focus on Family Amenities: Features like "Children Activities" were found to be very important, so investing in family-friendly services can improve ratings.

Manage Online Reputation: Because review counts matter so much, managers should actively encourage guests to leave feedback and respond to reviews professionally.
