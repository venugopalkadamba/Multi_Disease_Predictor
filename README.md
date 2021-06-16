# Multiple Disease Predictor

## About

This webapp was developed using Flask Web Framework and was deployed on Heroku server. The models used to predict the diseases were trained on large Datasets. All the links for datasets and the python notebooks used for model creation are mentioned below in this readme. The webapp can predict following Diseases:

- Diabetes
- Breast Cancer
- Heart Disease
- Kidney Disease
- Liver Disease
- Malaria
- Pneumonia

## Models with their Accuracy of Prediction

| Disease        | Type of Model            | Accuracy |
| -------------- | ------------------------ | -------- |
| Diabetes       | Machine Learning Model   | 98.25%   |
| Breast Cancer  | Machine Learning Model   | 98.25%   |
| Heart Disease  | Machine Learning Model   | 85.25%   |
| Kidney Disease | Machine Learning Model   | 99%      |
| Liver Disease  | Machine Learning Model   | 78%      |
| Malaria        | Deep Learning Model(CNN) | 96%      |
| Pneumonia      | Deep Learning Model(CNN) | 95%      |

## NOTE

==> You can access the website live at: https://kvg-disease-predictor.herokuapp.com <br>
==> Python version 3.6.8 was used for the whole project.<br>
==> You can find all the models in [models](https://github.com/venugopalkadamba/Multi_Disease_Predictor/tree/master/models) folder.

## Steps to run this application in your system

1. Clone or download the repo.
2. Open command prompt in the downloaded folder.
3. Create a virtual environment

```
mkvirtualenv environment_name
```

4. Install all the dependencies:

```
pip install -r requirements.txt
```

5. Run the application

```
python app.py
```

## Dataset Links

All the datasets were used from kaggle.

- [Diabetes Dataset](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
- [Breast Cancer Dataset](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data)
- [Heart Disease Dataset](https://www.kaggle.com/ronitf/heart-disease-uci)
- [Kidney Disease Dataset](https://www.kaggle.com/mansoordaku/ckdisease)
- [Liver Disease Dataset](https://www.kaggle.com/uciml/indian-liver-patient-records)
- [Malaria Dataset](https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria)
- [Pneumonia Dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)

## Links for Python Notebooks used for model creation

- [Diabetes Notebook](https://github.com/venugopalkadamba/Multi_Disease_Predictor/blob/master/Python%20Notebooks/Diabetes_Prediction.ipynb)
- [Breast Cancer Notebook](https://github.com/venugopalkadamba/Multi_Disease_Predictor/blob/master/Python%20Notebooks/Cancer_Prediction.ipynb)
- [Heart Disease Notebook](https://github.com/venugopalkadamba/Multi_Disease_Predictor/blob/master/Python%20Notebooks/Heart_Disease_Prediction.ipynb)
- [Kidney Disease Notebook](https://github.com/venugopalkadamba/Multi_Disease_Predictor/blob/master/Python%20Notebooks/Kidney_Disease_Prediction.ipynb)
- [Liver Disease Notebook](https://github.com/venugopalkadamba/Multi_Disease_Predictor/blob/master/Python%20Notebooks/Liver_Disease_Prediction.ipynb)
