# Detection-Of-Alzheimers-Disease
Purpose:
This code is designed to perform classification on an Alzheimer's disease dataset using Linear Discriminant Analysis (LDA) and K-Nearest Neighbors (KNN) algorithms. It also includes visualization of the data clusters using LDA and plots showing the performance of KNN with varying numbers of neighbors.

Dependencies:
1.matplotlib: For data visualization.
2.pandas: For data manipulation.
3.scikit-learn: For machine learning algorithms and utilities.
4.imbalanced-learn (imblearn): For data augmentation using SMOTE.



Steps:
1.Import Libraries: Import necessary libraries including matplotlib, pandas, and various modules from scikit-learn.

2.Load Dataset: Load the Alzheimer dataset from a CSV file.
3. Handle Missing Values: Use SimpleImputer to handle missing values in the dataset by replacing them with the mean of their respective columns.
4. Perform LDA: Fit the Linear Discriminant Analysis model to the data and transform it into a lower-dimensional space.

5.Visualize LDA Clusters: Visualize the data clusters in the reduced LDA space using a scatter plot.

6.Data Augmentation: Use Synthetic Minority Over-sampling Technique (SMOTE) to augment the dataset to address class imbalance.

7.Split Data: Split the augmented data into training and testing sets.

8.Scale Features: Standardize the features by scaling them to have a mean of 0 and a standard deviation of 1.

9.Modeling with KNN: Train a K-Nearest Neighbors classifier using cross-validation to find the optimal number of neighbors.

10.Evaluate Model: Evaluate the performance of the KNN classifier on the test set, displaying accuracy, confusion matrix, and classification report.

11.Plot Accuracy vs. Number of Neighbors: Plot the training and testing accuracies of the KNN classifier for different numbers of neighbors to visualize the model's performance.





This code shows 98.6% accuracy on test data.
