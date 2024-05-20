# Прогноз оттока клиентов

[HTML](https://github.com/antiren/Portfolio/blob/main/Teledom%20Clents/16-Teledom%20Clients%20-%20clean.html)     
[ipynb](https://github.com/antiren/Portfolio/blob/main/Teledom%20Clents/16-Teledom%20Clients%20-%20clean.ipynb)

## Описание проекта

Требуется настроить модель машинного обучения для прогноза оттока клиентов с показателем качества AUC-ROC не ниже 0.85.

##

## Навыки и инструменты

- **python**
- **pandas**
- **matplotlib**
- **phik**
- sklearn.tree **DecisionTreeClassifier**
- sklearn.ensemble **RandomForestClassifier**
- sklearn.linear_model **LogisticRegression**
- lightgbm **LGBMClassifier**
- sklearn.metrics **roc_auc_score, accuracy_score, roc_curve, confusion_matrix**
- sklearn.model_selection **GridSearchCV, train_test_split**
- sklearn.pipeline **make_pipeline**
- sklearn.preprocessing **OrdinalEncoder, StandardScaler, MinMaxScaler**
- catboost **CatBoostClassifier**

## 

## Общий вывод

Провела обучение выбранных моделей с подбором гиперпараметров, кодированием и масшибированием в зависимости от обучаемой модели. Лучшую модель проверила на тестовом наборе и исследовала её важность показателей и матрицу ошибок.
