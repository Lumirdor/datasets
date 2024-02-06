## DESCRIPTION

Este repositorio contiene datasets interesantes para trabajos de Data Science y Machine learning

## Datasets en csv

* pacientes_hospital: Listado de pacientes de un hospital de los cuales algunos han sufrido un ACV
* precio_btc_1m: Precios de bitcoin cada un minuto por un total de 100.000 minutos
* precio_btc_1h: Precios de bitcoin cada una hora por un total de 100.000 horas = 4166 dias = 11,4 años


## Datasets de librerias:
* Fraude: 'https://raw.githubusercontent.com/nsethi31/Kaggle-Data-Credit-Card-Fraud-Detection/master/creditcard.csv'

* Iris: 
    from sklearn.datasets import load_iris
    ris = load_iris()
    X_iris = pd.DataFrame(iris.data, columns=iris.feature_names)
    y_iris = iris.target
    "https://raw.githubusercontent.com/uiuc-cse/data-fa14/gh-pages/data/iris.csv"

* Wines:
    from sklearn.datasets import load_wine
    wine = load_wine()
    X = pd.DataFrame(wine.data, columns=wine.feature_names)
    y = wine.target

* Digitos: 
    from sklearn.datasets import load_digits
    digits = load_digits()
    X_digits = digits.data
    y_digits = digits.target