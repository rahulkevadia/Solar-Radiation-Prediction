# Solar-Radiation-Prediction

Software And Tools Requirements
1. [Github](https://github.com)
2. [VSCodeIDE](https://code.visualstudio.com)

Create a new environment

```
conda create -p venv python==3.7 -y
```

Git steps:
1. To check the status, whether green or red. Green means file/folder is staged, red means needs to staged.
```
git status
``` 
2. To add everything to staged
```
Git add .
```
3. To add a message, and push it to staging env from local.
```
git commit -m "commit-message" 
```
4. To pull the origin destination project.
```
git pull origin main
```
5. To upload on GitHub and push it to main branch.
```
git push origin main
```


Project Overview:

This project aims to predict solar radiation from a given dataset using factors such as Temperature, Pressure, windspeed, Humidity, Date and Time, and Sunrise and sunset.

The dataset comprises ten features, one target variable, and 32686 data instances.

Project Plan:

1. Importing the required libraries.
2. Exploring the dataset (EDA)
3. Data Preprocessing (identifying the missing data, removing outliers, and cleaning data)
4. Feature Selection using Pearson coefficient.
5. Data Scaling and Normalization.
6. Data Splitting into Train and Test.
7. Model Training.(Linear Regression, Random Forest)
8. Predicting on test Dataset.
9. Performance Metric.
10. Hyperparameter Tuning.
11. Pickling The Model file For Deployment 

