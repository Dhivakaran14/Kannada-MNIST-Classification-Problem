# Kannada-MNIST-Classification-Problem

# Procedure:

 1.Extract the dataset from the npz file from the downloaded dataset with 60000 images for training and 10000 images for test, each image is of the size 28X28.

2. Perform PCA to 10 components. So now we have train and test images in 10 dimension instead of 28X28 dimension.

3. Now apply the the following models:
   • Decision Trees
   • Random forest
   • Naive Bayes Model
   • K-NN Classifier
   • SVM

4. For each of this method produce the following metrics:
   • Precision, Recall, F1 - Score
   • Confusion Matrix
   • RoC - AUC curve
