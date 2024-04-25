## Asignment

Predict the class of breast cancer (malignant or ‘bad’ versus benign or ‘good’) from the features of images taken from breast samples. Ten biological attributes of the cancer cell nuclei have been calculated from the images, as described below:

<br />

|Attribute | Domain |
|----------|--------|
|01. Sample code number             | id number
|02. Clump Thickness                | 1 - 10
|03. Uniformity of Cell Size        | 1 - 10
|04. Uniformity of Cell Shape       | 1 - 10
|05. Marginal Adhesion              | 1 - 10
|06. Single Epithelial Cell Size    | 1 - 10
|07. Bare Nuclei                    | 1 - 10
|08. Bland Chromatin                | 1 - 10
|09. Normal Nucleoli                | 1 - 10
|10. Mitoses                        | 1 - 10
|11. Class                          |2 for benign
|                                   |4 for malignant

<br />

At a minimum, you should complete these steps:

- Split the data into training and test sets.
- Get basic descriptive statistics for the training data and check for missing and incorrect values. Replace missing values if this makes sense to do.
- Do the necessary feature preparation and build a logistic regression model.
