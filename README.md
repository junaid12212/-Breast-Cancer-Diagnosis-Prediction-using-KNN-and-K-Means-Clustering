# -Breast-Cancer-Diagnosis-Prediction-using-KNN-and-K-Means-Clustering

Problem: 
The goal of this project is to classify breast cancer cases using machine learning techniques.

Data Preprocessing:
The following preprocessing steps were performed to prepare the data for modeling:
1) Encoded the diagnosis column
2) Dropped unnecessary columns
3) Applied Min-Max Normalization to scale all feature values
4) Split the dataset into training data and testing data

Algorithms used:
1) K-Nearest Neighbors (classification)
   A supervised learning algorithm used for classification and predicts the class based on the majority class of the nearest     neighbors
2) K-Means (clustering)
   An unsupervised learning algorithm and groups data into two clusters to analyze natural separation between malignant and      benign cases

Model Evaluation:
The KNN model was evaluated on the testing dataset using the following performance metrics:
-Accuracy: 0.9649
-Precision: 0.9535
-Recall: 0.9535
-F1-Score: 0.9535
The high accuracy and balanced precision and recall values indicate that the KNN classifier performs very well.
K-Means clustering also demonstrated meaningful separation of the two classes, supporting the dataset’s strong inherent structure.




