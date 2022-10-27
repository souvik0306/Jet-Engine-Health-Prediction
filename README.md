## Jet-Engine-Health-Prediction

### Random Forest - 
The random forest is a classification algorithm consisting of many decisions trees. It uses bagging and feature randomness when building each individual tree to try to create an uncorrelated forest of trees whose prediction by committee is more accurate than that of any individual tree.

<image src="https://github.com/souvik0306/Jet-Engine-Health-Prediction/blob/main/random_forest.png" width="650" height="450">

### Why use Random Forest?
1. It takes less training time as compared to other algorithms.
2. It predicts output with high accuracy, even for the large dataset it runs efficiently.
3. It can also maintain accuracy when a large proportion of data is missing.

### Scripts - 

1. [jet_regression.ipynb](https://github.com/souvik0306/Jet-Engine-Health-Prediction/blob/main/jet_regression.ipynb) - Utilizes a basic Random Forest Regressor algorithm from sklearn. [RMSE on Test - 49.30]
2. [jet_nn.ipynb](https://github.com/souvik0306/Jet-Engine-Health-Prediction/blob/main/jet_nn.ipynb) - Uses a Keras based Sequential Neural Network [Accuracy - 87.57%]
3. [jet_engine.ipynb](https://github.com/souvik0306/Jet-Engine-Health-Prediction/blob/main/jet_engine.ipynb) - Uses a Random Forrest Classifier [Train Acc. - 99.9% vs Test Acc. - 89.2%] (Prone to Overfitting)
4. [jet_engine_optimized.ipynb](https://github.com/souvik0306/Jet-Engine-Health-Prediction/blob/main/jet_engine_optimized.ipynb) - Uses a Randomized Search CV from sklearn for hyperparamter optimization.  [Train Acc. - 89.9% vs Test Acc. - 88.9%] (No longer Prone to Overfitting)
5. [jet_eda.ipynb](https://github.com/souvik0306/Jet-Engine-Health-Prediction/blob/main/jet_eda.ipynb) - Heavy use of Seaborn, Matplotlib to study underlying statistical patterns from the data.
6. [jet_data_preprocessing.ipynb](https://github.com/souvik0306/Jet-Engine-Health-Prediction/blob/main/jet_data_preprocessing.ipynb) - Compares RMSE across various test sets. 

### Conclusion - 
• Predicted Remaining Useful Life (RUL) for turbofan jet engines using a Random Forest Classifier Model. 

• Performed Exploratory Data Analysis on NASA’s Dataset and analyzed feature correlation using Seaborn. 

• Applied hyperparameter optimization using Randomized Search CV and increased F1-Score to an overall 91.2%.
