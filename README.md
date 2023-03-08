# Hands-on-ML
A few exercises made studying the book Hands-On Machine Learning with Scikit-Learn &amp; TensorFlow, by Aurelien Geron

Here is what you will find in the exercises folder:

**Chapter 3: Classification**
- **E3.1:** A MNIST Classifier based on KNN, using Grid Search to stablish the better parameters for the data
- **E3.4:** A SPAM Classifier. Taking emails text files, the notebook handles the data, removing unnecessary information and transforming the text into vectors, where each instance represents the number of time a word has appeared. For that, the program stablishes a common vocabulary for all e-mails. Once that's done, a Logistic Regressor can be called to make predictions on wheter some e-mail will be SPAM or not.

**Chapter 4: Training Models**
- **E4.12:** An implementation from scratch of Batch Gradient Descent using early stopping for Softmax Regression. Testing on the Iris dataset, the algorithm reached 96.7% of correct predictions.

**Chapter 5: Support Vector Machines**
- **E5.8:** A comparison between LinearSVC, std. SVC and SGD applied to Iris dataset.
- **E5.9:** An application of a Support Vector Classifier model in the MNIST dataset. Using One-vs-All method for classification and a rbf kernel, the test reached an accuracy of 97.2%.
- **E5.10:** An application of a Support Vector Machine regressor applied to the California dataset.

**Chapter 6: Decision Trees**
- **E6.7:** Training of a Decision Tree Classifier on the Moons dataset. Final accuracy of 87%.
- **E6.8:** Spliting the Moons dataset in 1000 subsets, I trained one Decision Tree Classifier in each subset, and then predicted the result of all data with all models and kept the most frequent result only. The final accuracy ended to be 86.8%.

**Chapter 7: Ensemble Learning**
- **E7.8:** An ensemble method using a Voting Classifier with a Random Forest Classifier, an Extra Trees Classifier, and a SVM Classifier.
- **E7.9:** A Stacking Ensemble using the predictions of the previous exercise as data itself.

**Chapter 8: Dimensionality Reduction**
- **E8.9:** A PCA test on the performance of Random Forest Classifier on MNIST dataset.
- **E8.10:** Use of many dimensionality reduction algorithms (TSNE, PCA, LLE, and MDS) to reduce the MNIST dataset images into only 2 dimensions, and then ploting them into a 2d chart to check if there's some clusterization between different digits. The best result was joining TSNE and PCA, using the latter to preserve variability and the former to reduce dimensionality.

**Chapter 9: Unsupervised Learning**
- **E9.10:** Use of K-Means algorithm to cluster faces images using the Olivetti dataset.
- **E9.11:** Again using the Olivetti dataset, but now using a Random Forest Classifier to predict data, and using K-Means algorithm to reduce the dimensionality of the data.
- **E9.12:** First use of PCA algorithm to reduce dimensionality of the Olivetti dataset, then using Gaussian Mixture to generate new faces based on learning.
- **E9.13:** Use of PCA to reduce dimensionality of Olivetti dataset, then reversing the reduction to reconstruct data and then check how much of the information was lost. Since we're dealing with images of faces, this can be observed visually.
