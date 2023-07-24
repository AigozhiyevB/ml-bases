# ml-bases
Some Machine Learning projects

## Repository structure

This project has the following structure:

```
- Machine_Translator.ipynb - Example of unsupervied machine translation via Linear Algebra
- ML_SVM - Example of SVM model usage on classification with different kernels
- classification/
    - bank churn/ - Bank customer churn classification
        - inputs/
            - Bank Customer Churn Prediction.csv - data from kaggle
        - jupyter/
            - project.ipynb - model training ipynb
        - models/
            - model.cbm - trained CatBoost model
    - customer/ - Customer classification
        - inputs/
            - Train.csv
            - Test.csv
        - jupyter/
            - customer classification.ipynb - model training ipynb
        - models/
            - best_model.cbm - trained CatBoost model
            - target_dict.json - labeling JSON file
    - scoring/ - Credit scoring
        - Main.ipynb - model training ipynb
        - test.csv
        - train.csv
    
```