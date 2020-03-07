# Pedestrian-detection
Write a program to implement the Histogram of Orientated Gradients (HOG) Algorithm for
pedestrian detection. The dataset used to evaluate the descriptor is “NICTA Pedestrian
Dataset,” where it contains both the training set and the testing set. The training set contains
1000 positives samples (images contain pedestrians) and 2000 negatives samples (images do
not contain pedestrians). The testing set includes 500 positive samples and 500 negative
samples. Resize all images to 64 × 128 and use the following set of parameters:
• Cell size [8 8]
• Block size [ 16 16]
• Gradient operators: Gx= [-1 0 1] and Gy= [-1 0 1]T
• Number of orientation bins = 9
2. Write a program to train and test the linear Support Vector Machine (SVM) classifier for
pedestrian detection using the extracted features from part 1.
a) Train the SVM classifier with HOG features of the training set (use built-in
function/library (e.g. from sklearn.svm import SVC)).
b) Classify the HOG features of the testing images (both positive and negatives samples)
using the trained SVM model (use built-in function/library).
c) Compute the accuracy, false positive rate, and the miss rate.
3. Repeat the experiment in part 2 for training the SVM classifier with different set of kernel
functions (e. g. rbf, polynomial, etc.).
