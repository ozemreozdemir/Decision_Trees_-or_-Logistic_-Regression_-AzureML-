Low-cost Sensor
======================================
Design a simple, low-cost sensor that can distinguish between red wine and white wine.

Your sensor must correctly distinguish between red and white wine for at least 95% of the samples in a set of 6497 test samples of red and white wine.

Your technology is capable of sensing the following wine attributes:

Fixed acidity  -  Free sulphur dioxide
Volatile acidity  -  Total sulphur dioxide
Citric acid  -  Sulphates
Residual sugar  -  pH
Chlorides  - Alcohol
Density
Tasks

Read WineQuality.pdf.
Use the RedWhiteWine.csv/arff file that is provided, and upload to Azure Machine Learning as a dataset
Note: If needed, remove the quality attribute, which you will not need for this assignment.
Build an experiment in Azure Machine Learning using Decision Trees or Logistic Regression.
What is the percentage of correct classification results (using all attributes)?
What is the percentage of correct classification results (using a subset of the attributes)?
What is the AUC of your model?
What is your best AUC that you can achieve?
Which are the the minimum number of attributes? Why?