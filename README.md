# Amazon Electronic Product Recommender System

Our goal is to create a sophisticated machine learning model to build an Amazon electronic product recommender system.

## Data Processing and Filtering

We perform basic data exploratory data analysis (EDA) and data filtering using the `data_processing.ipynb` notebook.

The filtered data is saved as `filtered_data.csv`.

**Data Filter:**
![Data Filter](./figures/data_filter.png)

**Filtered Data Distribution:**
![Filtered Data - Average User](./figures/after_avguser.jpg)
![Filtered Data - Average Product](./figures/after_avgproduct.jpg)

## Baseline Models Implementation

We implement several basic models, including SVD, SVD++, KNN, and KNN Baseline. The entire process can be found in `/baselinemodel/BaselineModels.ipynb`.

The training process includes grid search for optimizing hyperparameters and cross-validation for evaluating model performance.

**Baseline Model Performance:**
![Baseline Model Performance](./figures/baseline_performance.jpg)

## LSTM Implementation

We implement lstm to take the timestamp feature in our dataset. The entire process can be found in `/lstm model/lstm.ipynb`.

**LSTM learning curve :**
![LSTM learning curve](https://github.com/Jingxuan-Bao/Amazon_Product_Recommendation/blob/3065b013da3554c327e987c971a3658ed180be46/lstm%20model/figure/learning_curve.png)

## Neural Network Implementation

We've also implemented basic fully connect neural network. The entire process can be found in `/neural network model/neural_net.ipynb`.

**Neural Network learning curve :**
![Neural Network learning curve](./figures/learning_curve.png)