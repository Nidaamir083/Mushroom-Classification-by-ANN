# Mushroom-Classification-by-ANN
The classification of mushrooms as edible or poisonous using machine learning techniques.
Dataset: Comprehensive mushroom data, exploring key features like cap shape, color, and odor.

Techniques: Importing libraries pandas, numpy and IPython for dataloading. Data is cleaned and there are no null values, all the columns are in float and integer form so no preprocessing required. Standard Scaler is used to arrange values in array for further analysis.

ANN model implication: After train, test and split data I used Sequential layers with activation function 'Relu' and 'Sigmoid' as it is a binary classification. 'Adam' is the optimizer that works good on almost every data, loss is 'binry_crossentropy' as it is binary classification.

Insights: Achieved strong accuracy metrics:  accuracy: 0.9801, loss: 0.0542 , val_accuracy: 0.9743,  val_loss: 0.0654.

Data Visualization: Matplotlib is used to show the plot of accuracy and loss which is well defined of perfect data not over or underfit. Confusion matrix from seaborn library is used to show the 'True Label' and 'Predicted Label'.

The model performs exceptionally well, with high precision and recall.

However:

False Positives (105) could result in misclassifying non-poisonous mushrooms as poisonous.

False Negatives (88) are more concerning as they represent poisonous mushrooms being classified as non-poisonous.


