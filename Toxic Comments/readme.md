# Анализ текста

[HTML](https://github.com/antiren/Portfolio/blob/main/Toxic%20Comments/14-ToxicComments%20-%20clean.html)     [ipynb](https://github.com/antiren/Portfolio/blob/main/Toxic%20Comments/14-ToxicComments%20-%20clean.ipynb)

## Описание проекта

Требуется обучить модель классифицировать комментарии на позитивные и негативные со значением метрики качества F1 не меньше 0.75.

##

## Навыки и инструменты

- **python**
- **pandas**
- **spacy**
- **nltk**
- nltk.corpus **stopwords as nltk_stopwords**
- sklearn.model_selection **train_test_split**
- sklearn.metrics **f1_score**
- sklearn.feature_extraction.text **TfidfVectorizer**
- sklearn.linear_model **LogisticRegression**
- sklearn.tree **DecisionTreeClassifier**
- catboost **CatBoostClassifier**
- lightgbm **LGBMClassifier**

## 

## Общий вывод

Провела очистку текста от лишних символов, лемматизацию, а также обучение выбранных моделей. Для лучшей модели проверила качество на тестовом наборе.

