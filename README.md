# ML_Lab_Problem_Statement_6_SVM
The SVM model performs classification by finding the optimal hyperplane to separate different classes, while in regression, it predicts continuous outcomes by minimizing prediction error. Its effectiveness in high-dimensional spaces and robustness against overfitting make it a versatile tool for both tasks.

Support Vector Machine (SVM)

SVM for Classification (Wine Quality Dataset)
In our project, SVM was utilized to classify the quality of wine based on various physicochemical tests. The following steps were taken:

Data Preparation: The wine quality dataset was loaded and explored to understand its structure. It was then split into training and testing sets.
Model Construction: An SVM classifier was constructed and trained on the training set.
Prediction: The classifier predicted the quality scores on the testing set.
Evaluation: We evaluated the model's performance using metrics such as accuracy, precision, recall, and F1-score, allowing us to understand how well the model could classify wine quality.

SVM for Regression (Concrete Compressive Strength Dataset)
For the regression task, we employed SVM to predict the compressive strength of concrete based on its composition. The process included:

Data Preparation: The concrete compressive strength dataset was loaded and explored to comprehend its structure.
Model Construction: An SVM regressor was built and trained on the training set to learn the relationship between the input features and the compressive strength.
Prediction: The regressor predicted the concrete strength values on the testing set.
Evaluation: The model's performance was assessed using Mean Squared Error (MSE) and R-squared metrics, along with visualizations to compare actual versus predicted values.
In both cases, SVM's capability to handle high-dimensional data and maintain robustness against overfitting was critical for achieving reliable results in classification and regression tasks.
