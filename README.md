# Multiple Disease Predictor
## About
This webapp was developed using Flask Web Framework. The models used to predict the diseases we trained on large Datasets. This webapp can predict following Diseases:
* Diabetes
* Breast Cancer
* Heart Disease
* Kidney Disease
* Liver Disease
* Malaria
* Pneumonia

## Models with their Accuracy of Prediction
Disease | Type of Model | Accuracy
--- | --- | ---
Diabetes | Machine Learning Model | 98.25%
Breast Cancer | Machine Learning Model | 98.25%
Heart Disease | Machine Learning Model | 85.25%
Kidney Disease | Machine Learning Model | 99%
Liver Disease | Machine Learning Model | 78%
Malaria | Deep Learning Model(CNN) | 96%
Pneumonia | Deep Learning Model(CNN) | 95%

## Steps to use
**Step-1:** Download the files in the repository.<br>
**Step-2:** Get into the downloaded folder, open command prompt in that directory and install all the dependencies using following command<br>
```python
pip install -r requirements.txt
```
**Step-3:** After successfull installation of all the dependencies, run the following command<br>
```python
python app.py
```
## Dataset Links
All the datasets were used from kaggle.
* [Diabetes Dataset](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
* [Breast Cancer Dataset](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data)
* [Heart Disease Dataset](https://www.kaggle.com/ronitf/heart-disease-uci)
* [Kidney Disease Dataset](https://www.kaggle.com/mansoordaku/ckdisease)
* [Liver Disease Dataset](https://www.kaggle.com/uciml/indian-liver-patient-records)
* [Malaria Dataset](https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria)
* [Pneumonia Dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)

## Links for Python Notebooks used for model creation
* [Diabetes Notebook](https://github.com/venugopalkadamba/Multi_Disease_Predictor/blob/master/Python%20Notebooks/Diabetes_Prediction.ipynb)
* [Breast Cancer Notebook](https://github.com/venugopalkadamba/Multi_Disease_Predictor/blob/master/Python%20Notebooks/Cancer_Prediction.ipynb)
* [Heart Disease Notebook](https://github.com/venugopalkadamba/Multi_Disease_Predictor/blob/master/Python%20Notebooks/Heart_Disease_Prediction.ipynb)
* [Kidney Disease Notebook](https://github.com/venugopalkadamba/Multi_Disease_Predictor/blob/master/Python%20Notebooks/Kidney_Disease_Prediction.ipynb)
* [Liver Disease Notebook](https://github.com/venugopalkadamba/Multi_Disease_Predictor/blob/master/Python%20Notebooks/Liver_Disease_Prediction.ipynb)
* [Malaria Notebook](https://www.kaggle.com/venugopalkadamba/malaria?scriptVersionId=38537287)
* [Pneumonia Notebook](https://www.kaggle.com/venugopalkadamba/pneumonia-prediction)

## Technologies Used
![alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Scikit_learn_logo_small.svg/330px-Scikit_learn_logo_small.svg.png)
![alt text](https://cdn.analyticsvidhya.com/wp-content/uploads/2017/06/08075935/keras-tensorflow-logo.jpg)
![alt text](https://i1.wp.com/www.corellis.eu/wp-content/uploads/2018/09/logo-flask.png)
![alt text](https://redislabs.com/wp-content/uploads/2016/11/logo-square-heroku.png)
