# Diabetes Prediction on Pima Indians Diabetes Database
 
## About the Dataset : 
- The dataset is taken from [Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database/data)
- This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.

## About the model :
- K-Nearest Neighbor algorithm is used.
- Dataset split into training and testing sets (80% training, 20% testing).
- Model trained on both normalized and unnormalized feature values.
- Data leakage is prevented by fitting the Standard Scaler only on the training set and applying it to both training and testing sets.
- Checked performance with different n_neighbors values, selecting the best one based on testing accuracy.
