# PCA-SVM-Work-Together

We investigate how a dimensionality reduction technique can help optimize the number of features needed to feed a classification algorithm. In this case, the data corresponds to images of 40 different people, where we have 10 pictures of each person.

Each picture has a resolution of 64x64 pixels, meaning that if dimensionality reduction is not applied, the classifier inputs 4064 features, used for prediction. With PCA this is reduced significantly to 150 (the first 150 principal components of the training data).

An SVM classifier is trained with the first 150 principal components of the data and an accuracy score is given.
