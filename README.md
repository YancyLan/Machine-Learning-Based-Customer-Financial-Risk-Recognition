# Machine-Learning-Based-Customer-Financial-Risk-Recognition
Data is from 2022 Competition in Fintech 
# Machine-Learning-Based Customer Financial Risk Recognition

This project leverages machine learning techniques to identify and predict customer financial risks based on various features. It includes data preprocessing, feature engineering, model development, and evaluation using ensemble methods like Stacking and Voting.

## Project Structure

The project files are organized as follows:

- **Data Files**:
  - `train.csv` and `test.csv`: Primary datasets for model training and testing.
  - `df_train_a1.csv` and `df_test_a1.csv`: Processed datasets for specific experiments.
  - `result1.csv`, `result2.csv`, `result3.csv`: Output results from different models or experiments.

- **Notebooks**:
  - `AutoGluon.ipynb`: AutoML experiments using the AutoGluon framework.
  - `Stacking_模型一.ipynb`: Implementation of the first Stacking model.
  - `寻找baseline+网格调参.ipynb`: Establishing baseline performance and hyperparameter tuning using grid search.
  - `voting.ipynb`: Implementation of Voting ensemble methods.
  - `特征工程_Stacking_模型二.ipynb`: Feature engineering and development of the second Stacking model.

## Key Features

- **Feature Engineering**: Advanced preprocessing techniques to improve model performance.
- **Model Stacking**: Multi-layered model ensemble for robust predictions.
- **Voting Classifier**: Combining predictions from multiple models for improved accuracy.
- **Hyperparameter Tuning**: Optimization using grid search for model fine-tuning.
- **AutoML**: Exploration of automated machine learning techniques using AutoGluon.

