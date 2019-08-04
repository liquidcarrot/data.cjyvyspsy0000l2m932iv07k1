# Wine Qaulity Dataset

The Wine Quality Dataset involves predicting the quality of white wines on a scale given chemical measures of each wine.

It is a multi-class classification problem, but could also be framed as a regression problem. The number of observations for each class is not balanced. There are 4,898 observations with 11 input variables and one output variable. The variable names are as follows:

1. Fixed acidity
2. Volatile acidity
3. Citric acid
4. Residual sugar
5. Chlorides
6. Free sulfur dioxide
7. Total sulfur dioxide
8. Density
9. pH
10. Sulphates
11. Alcohol
12. Quality (score between 0 and 10)

The baseline performance of predicting the mean value is an RMSE of approximately 0.148 quality points.

A sample of the first 5 rows is listed below.

**CSV**

```csv
7,0.27,0.36,20.7,0.045,45,170,1.001,3,0.45,8.8,6
6.3,0.3,0.34,1.6,0.049,14,132,0.994,3.3,0.49,9.5,6
8.1,0.28,0.4,6.9,0.05,30,97,0.9951,3.26,0.44,10.1,6
7.2,0.23,0.32,8.5,0.058,47,186,0.9956,3.19,0.4,9.9,6
7.2,0.23,0.32,8.5,0.058,47,186,0.9956,3.19,0.4,9.9,6
```

**JSON**

```json
[{
  "fixed acidity": "7.1",
  "volatile acidity": "0.26",
  "citric acid": "0.29",
  "residual sugar": "12.4",
  "chlorides": "0.044",
  "free sulfur dioxide": "62",
  "total sulfur dioxide": "240",
  "density": "0.9969",
  "pH": "3.04",
  "sulphates": "0.42",
  "alcohol": "9.2",
  "quality": "6"
}, {
  "fixed acidity": "6",
  "volatile acidity": "0.34",
  "citric acid": "0.66",
  "residual sugar": "15.9",
  "chlorides": "0.046",
  "free sulfur dioxide": "26",
  "total sulfur dioxide": "164",
  "density": "0.9979",
  "pH": "3.14",
  "sulphates": "0.5",
  "alcohol": "8.8",
  "quality": "6"
}, {
  "fixed acidity": "8.6",
  "volatile acidity": "0.265",
  "citric acid": "0.36",
  "residual sugar": "1.2",
  "chlorides": "0.034",
  "free sulfur dioxide": "15",
  "total sulfur dioxide": "80",
  "density": "0.9913",
  "pH": "2.95",
  "sulphates": "0.36",
  "alcohol": "11.4",
  "quality": "7"
}, {
  "fixed acidity": "9.8",
  "volatile acidity": "0.36",
  "citric acid": "0.46",
  "residual sugar": "10.5",
  "chlorides": "0.038",
  "free sulfur dioxide": "4",
  "total sulfur dioxide": "83",
  "density": "0.9956",
  "pH": "2.89",
  "sulphates": "0.3",
  "alcohol": "10.1",
  "quality": "4"
}, {
  "fixed acidity": "6",
  "volatile acidity": "0.34",
  "citric acid": "0.66",
  "residual sugar": "15.9",
  "chlorides": "0.046",
  "free sulfur dioxide": "26",
  "total sulfur dioxide": "164",
  "density": "0.9979",
  "pH": "3.14",
  "sulphates": "0.5",
  "alcohol": "8.8",
  "quality": "6"
}]
```