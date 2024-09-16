# SVM-Cancer-Cell-Classification
This Jupyter notebook demonstrates the use of Support Vector Machines (SVM) to classify human cell samples as benign or malignant based on their characteristics. SVM is a powerful tool for classification, capable of handling non-linear data by mapping it into a higher-dimensional feature space. This allows for the separation of data points using a hyperplane as the decision boundary.
# Dataset
The analysis is based on a publicly available dataset from the UCI Machine Learning Repository (Asuncion and Newman, 2007).It consists of several hundred human cell sample records, each with a set of characteristics. Key fields in the dataset include:
ID: Patient identifiers.
Clump to Mit: Cell characteristics, graded from 1 to 10 (with 1 being closest to benign).
Class: Indicates the diagnosis, with a value of 2 for benign and 4 for malignant samples.
# Procedure
1.	Loading the Data: Import the dataset and observe its structure.
2.	Preprocessing:
o	Convert the 'Class' field to a categorical type to reflect its binary nature.
o	Split the dataset into training and testing sets.
3.	Modeling with SVM:
o	Choose an appropriate kernel function for the SVM.
o	Train the SVM model on the dataset.
4.	Evaluation:
o	Assess the model’s accuracy using the test data.
o	Discuss the results and any potential improvements.
5.	Practice: Interactive section for trying different SVM parameters.
 

# Detailed Steps
1. Load the Cancer Data
The dataset includes records for several hundred human cells, with each record detailing cell characteristics and a diagnosis confirmed by medical procedures.
2. Modeling
Utilize the SVM algorithm from Scikit-learn to train the model. SVM’s ability to use different kernel functions allows it to effectively categorize data in a higher-dimensional space.
3. Evaluation
After training, the model's performance is evaluated to determine its accuracy and effectiveness in classifying new data samples.
4. Practice
This section allows for experimentation with different SVM parameters to explore their impact on model performance.

This notebook provides a practical sample approach to understanding and applying SVM for binary classification problems in the field of medical diagnostics. By following the steps outlined, we can not only reproduce the results but also gain insights into SVM’s operational mechanics. My speciall thanks to IBM Developer Skills Network.
