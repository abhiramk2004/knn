Dataset: Iris dataset, a classic benchmark for classification problems.

Conducted Exploratory Data Analysis (EDA) and found the dataset was preprocessed and suitable for KNN modeling.

Applied StandardScaler to normalize all feature values, ensuring that each feature contributed equally to the distance metric used by KNN.

Used pairplot to visually analyze relationships between features and assess category separability.

Inference:

Setosa is perfectly separable from the other classes.

Versicolor and Virginica have some overlap, but using all features together improves distinguishability due to the unique contribution of each.

Checked the correlation matrix and confirmed that although some features were correlated, none were highly enough to warrant dropping them.

Experimented with different values of n_neighbors and different distance metrics to identify the most suitable configuration.

Found that all metrics yielded similar results; chose Euclidean distance for simplicity.

Visualized decision boundaries using NumPy and Matplotlib to understand how the model partitions the feature space.

Evaluated model performance using the classification report, which provided metrics including precision, recall, and F1-score for each class, enabling a deeper understanding of where the model performed well and where it needed improvement.
