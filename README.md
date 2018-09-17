# Linear_classifier


# Data Source
In this experiment, we will use Wisconsin Breast Cancer data to classify it as benign or malignant.
https://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/wdbc.data
The data has been modified:
The id field has been removed
The diagnosis field has been moved to the end




# Data Attributes
Number of instances: 569 
Number of attributes: 31 (diagnosis, 30 real-valued input features)
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
The mean, standard error, and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. For instance, field 1 is Mean Radius, field 11 is Radius SE, field 21 is Worst Radius. All feature values are recoded with four significant digits.


The last field is diagnosis: M for Malignant and B for Benign
Class distribution: 357 benign, 212 malignant
