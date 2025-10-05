# Comparative-Study-of-ML-Classifiers-for-Sensorless-Drive-Diagnosis

## Abstract
This study presents a comparative study of seven machine learning classifiers for Sensorless Drive Diagnosis. We tested linear models (Logistic Regression, SGD Classifier), Tree-based methods (Decision Tree), instance-based learning (KNeighbors Classifier), generative models (Gaussian Naive Bayes), and discriminative classifiers (LDA, QDA). We examined the effects of features-reduction techniques such as feature selection (Recursive Feature Elimination, SelectKBest) and dimensionality reduction (PCA). We also leveraged instance-reduction techniques (Nearest Neighbors, Voronoi Neighbors), and conducted a comparative study against the full dataset. Our study shows that KNeighbors with Recursive Feature Elimination outperformed with the highest accuracy of 99.92%, surpassing the model’s performance trained on full dataset.

## Highlights of Research
1) Conduted an in-depth comparison of LR, SGD, DT, KNN, NB, LDA, and QDA on the Sensorless Drive Diagnosis dataset from UCI, containing 58,509 instances and 48 features across 11 motor conditions.
2) Explored the impact of feature selection (RFE, SKB), dimensionality reduction (PCA), and instance reduction (NN, VN) to optimize performance and computational efficiency.
3) Applied hyperparameter tuning using GridSearchCV with 3-fold cross validation to identify the best configuration for each model.
4) The KNeighbors Classifier with Recursive Feature Elimination (RFE) achieved the highest accuracy of 99.92%, outperforming all other combinations and even models trained on the full dataset.
5) Demonstrated that feature reduction can enhance both model interpretability and efficiency without compromising accuracy.
