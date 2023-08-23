## Breast cancer classification

The correct diagnosis of breast cancer and classification of patients into malignant or benign groups can promote timely clinical treatment to patients.
Dataset consists of several Medical Variables(Independent) and one Outcome Variable(Dependent).Here I used several different supervised machine learning classifier algorithms and compared their performance.

## dataset description:

Attribute Information:

1) ID number
   
2) Diagnosis (M = malignant, B = benign)
   
3-32)
Ten real-valued features are computed for each cell nucleus:

a) radius (mean of distances from center to points on the perimeter)
b) texture (standard deviation of gray-scale values)
c) perimeter
d) area
e) smoothness (local variation in radius lengths)
f) compactness (perimeter^2 / area - 1.0)
g) concavity (severity of concave portions of the contour)
h) concave points (number of concave portions of the contour)
i) symmetry
j) fractal dimension ("coastline approximation" - 1)

The mean, standard error and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. For instance, field 3 is Mean Radius, field 13 is Radius SE, field 23 is Worst Radius.All feature values are recoded with four significant digits.

Class distribution: 357 benign, 212 malignant

## Project description:
1) Exploratory data analysis of dataset
   
2) build different classification models 
Support Vector Classifier
Logistic Regression
K – Nearest Neighbor Classifier
Naive Bayes Classifier
Decision Tree Classifier
Random Forest Classifier
Adaboost Classifier
XGBoost Classifier

3) Conclusion



