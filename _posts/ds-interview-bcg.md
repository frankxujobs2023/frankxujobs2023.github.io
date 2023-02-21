# BCG Intreview Q
1. How to build up a recomendation system
2. How to boost sales of a local store
3. How would you build a model to predict the profitability of different stores nationwide
4. What data do you need to build better sales strategie
5. Maximize revenue for fashion retailer client
6. Traditional market sizing questions for the business case
7. What method would you use for feature engineering
## 8. When does recall matter more, when does precision matter more

Recall and precision are both important performance metrics in binary classification problems, but their relative importance depends on the specific problem and the business objectives. Here are a few general guidelines:

Recall matters more when:

False negatives are more costly than false positives: In some applications, missing a positive instance can have more severe consequences than incorrectly identifying a negative instance. For example, in medical diagnosis, failing to detect a disease can be life-threatening, while a false alarm is less critical.

The class distribution is imbalanced: When the positive class is rare compared to the negative class, recall can be more important because it measures the ability of the classifier to identify the positive instances correctly.

The goal is to maximize the coverage: In some scenarios, the primary goal is to capture as many positive instances as possible, even at the cost of including some negative instances. This is often the case in information retrieval, where recall measures the fraction of relevant documents retrieved.

Precision matters more when:

False positives are more costly than false negatives: In some applications, incorrectly flagging a negative instance can be more damaging than missing a positive instance. For example, in fraud detection, incorrectly accusing a customer of fraud can harm their reputation and result in legal consequences.

The class distribution is balanced: When the positive and negative classes are roughly balanced, precision can be more important because it measures the fraction of true positives among all positive predictions.

The goal is to maximize the accuracy: In some scenarios, the primary goal is to make sure that the positive predictions are highly accurate, even at the cost of missing some positive instances. This is often the case in text classification, where precision measures the fraction of relevant documents among all retrieved documents.

## 9. Dimension Reduction
Principal Component Analysis (PCA): PCA is a popular unsupervised linear dimensionality reduction technique that transforms the data into a new coordinate system, where the first few principal components explain the maximum amount of variance in the data. PCA is particularly useful when the data has a linear structure and the goal is to identify the most important features.

t-Distributed Stochastic Neighbor Embedding (t-SNE): t-SNE is a non-linear dimensionality reduction technique that maps the high-dimensional data onto a low-dimensional space while preserving the pairwise distances between the points as much as possible. t-SNE is particularly useful when the data has a complex, non-linear structure and the goal is to visualize the data in a two-dimensional or three-dimensional space.

Linear Discriminant Analysis (LDA): LDA is a supervised linear dimensionality reduction technique that projects the data onto a new space that maximizes the separation between the classes. LDA is particularly useful for classification tasks when the goal is to identify the most discriminative features.

Autoencoders: Autoencoders are a type of neural network that can be used for unsupervised dimensionality reduction. The autoencoder learns to encode the high-dimensional data into a lower-dimensional space and then decode it back into the original space, minimizing the reconstruction error. Autoencoders are particularly useful when the data has a complex, non-linear structure and the goal is to identify the most important features.

Random Projections: Random projections are a simple and efficient technique for reducing the dimensionality of high-dimensional data. The idea is to randomly project the data onto a lower-dimensional space while preserving the pairwise distances between the points as much as possible. Random projections are particularly useful when the data has a large number of features and the goal is to reduce the computational complexity of the subsequent analysis.

## Links
[data_challenge](https://www.youtube.com/watch?v=Q6fEKz6W-SA)
