1. Dataset Exploration: Iris Dataset
Objective:
The goal of this task is to load and explore the Iris dataset. The Iris dataset is widely used for machine learning and statistical analysis. It consists of 150 samples from three species of iris flowers (Setosa, Versicolor, Virginica), with four features measured: sepal length, sepal width, petal length, and petal width (all in centimeters).

Steps Involved:
Loading the Dataset:

The Iris dataset is loaded using load_iris() from sklearn.datasets. This function provides both the features and the target labels (species). We will focus on exploring the features.
Displaying the First Five Rows:

The first five rows of the dataset are displayed to give an overview of the data and to check its structure. This step helps to verify that the data has been loaded correctly.
Dataset Shape:

The shape of the dataset is printed, which shows the number of samples (rows) and the number of features (columns). This gives us a quick understanding of the size of the dataset.
Summary Statistics:

Summary 
statistics are generated for each feature using the describe() function from pandas. These statistics include:
Mean: The average value of each feature.
Standard Deviation (std): The spread of the feature values.
Minimum and Maximum (min/max): The range of values for each feature.
Quartiles (25%, 50%, 75%): These represent different percentiles in the distribution of the feature values.
