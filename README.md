# Titanic Dataset
## Analysis And Prediction of the number of survivors of the famous Titanic Dataset. Includes Visualization using seaborn,plotly , Datapreprocessing and result prediction and Accuracy testing.

The training set is used to build  machine learning models. For the training set, we provide the outcome (also known as the “ground truth”) for each passenger. Model will be based on “features” like passengers’ gender and class. You can also use feature engineering to create new features.
The test set should be used to see how well the model performs on unseen data. For the test set, we do not provide the ground truth for each passenger. 

## Variabales 
- pclass: A proxy for socio-economic status (SES)
  - 1st = Upper
  - 2nd = Middle
  - 3rd = Lower

- age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

- sibsp: The dataset defines family relations in this way...
- Sibling = brother, sister, stepbrother, stepsister
- Spouse = husband, wife (mistresses and fiancés were ignored)

- parch: The dataset defines family relations in this way...
- Parent = mother, father
- Child = daughter, son, stepdaughter, stepson

Some children travelled only with a nanny, therefore parch=0 for them.
