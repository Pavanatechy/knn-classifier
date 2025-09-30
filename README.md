1.Load & preprocess the Iris dataset
-Drops the Id column.
-Converts feature columns to numeric and scales them with StandardScaler.
-Keeps Species as string labels.
2.Train KNN with different K values
-Tests K = 1 to 15 and records accuracies.
-Selects the best K (highest accuracy).
3.Evaluate best mode
-Fits KNN with the best K.
-Prints accuracy and confusion matrix.
4.Visualize decision boundarie
-Uses only the first two features (Sepal length & Sepal width).
-Creates a mesh grid and predicts class labels for each point.
-Converts string predictions to numeric codes so contourf can plot regions.
-Overlays actual data points with matching colors.
