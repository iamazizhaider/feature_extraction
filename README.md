In this report, we investigate the problem of classifying seven different classes of images. The
classes include Cats, Dogs, and Horses. To address this problem, we explore the use of feature
extraction methods such as Scale-Invariant Feature Transform (SIFT), Speeded Up Robust
Features (SURF), and Histogram of Oriented Gradients (HOG). We train two different
classifiers, namely Artificial Neural Network (ANN) and Random Forest, using the extracted
features.
For the feature extraction step, we implemented a MATLAB code to extract SIFT, SURF, and
HOG features from the image dataset. The dataset was divided into a 70-30 ratio of training and
test data. SIFT, SURF, and HOG features were extracted for each class.
After the feature extraction step, we trained two different classifiers, ANN and Random Forest,
using the extracted features in Python programming language. For both classifiers, we used the
training data to train the model and the test data to evaluate its performance.
In conclusion, the proposed approach demonstrates the effectiveness of using feature extraction
methods such as SIFT, SURF, and HOG, in combination with machine learning classifiers such
as ANN and Random Forest, for classifying different classes of images.
