# KNN-wine-quality
<p align="justify">
Using the first 800 instances in the file “winequality-white.csv”, we will build a k-Nearest Neighbours classifier in Python to predict wine quality depending on eleven different factors
</p>

## Predicting Wine Quality with k-Nearest Neighbours
The attached jupyter notebook walks through the following steps:
1. Loads the data file;
2. Construct a new binary column “good wine” that indicates whether the wine is good (which we define as having a quality of 6 or higher) or not;
3. Splits the data set into a training data set (first 400 samples), a validation data set (next 200 samples) and a test data set (last 200 samples);
4. Normalises the data according to the Z-score transform;
5. Loads and trains the k-Nearest Neighbours classifiers for k = 1, 2, . . . , 100;
<p align="center">
<img src = "https://user-images.githubusercontent.com/70657426/150609047-44fc5827-d856-4e3e-96a3-a3c89093ca42.png">
</p>
6. Evaluates each classifier using the validation data set and selects the best classifier;
7. Predicts the generalisation error using the test data set.
8. Try a new splitting: split the data set into a training data set (first 200 samples), a validation data set (next 200 samples), and a test data set (last 400 samples). Then redo steps 4 to 7. predicts the new generalisation error.
<p align="center">
  <img src ="https://user-images.githubusercontent.com/70657426/150609074-12ddbb0d-f3b6-4755-8f3f-f2a68fc5676a.png">
</p>
