## Predicción de la Morosidad de Clientes con Créditos Bancarios Utilizando Aprendizaje Automático

### Abstract
En este proyecto se realizan modelos de predicción para conocer si un cliente será moroso en relación a distintas variables como el monto del préstamo, el plazo, entre otras. Esto nos ayuda a anticipar si algún cliente caerá en incumplimiento de pago y así tomar medidas al respecto.

Para lograrlo, se utilizarón los siguientes metodos de aprendizaje automático:

* Regresión Logística.
* Árbol de Decisión.
* Bosque Aleatorio.
* K Vecinos más Cercanos.

A su vez, fue necesario aplicar las siguientes librerías:

```
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import statsmodels.api as sm
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler,RobustScaler,MinMaxScaler
from sklearn.linear_model import LogisticRegression
from sklearn.tree import DecisionTreeClassifier
from sklearn.naive_bayes import GaussianNB
from sklearn.neighbors import KNeighborsClassifier
from sklearn.ensemble import RandomForestClassifier
from sklearn.ensemble import AdaBoostClassifier
from sklearn.metrics import confusion_matrix
from sklearn.metrics import classification_report
from sklearn.metrics import accuracy_score
from sklearn.metrics import roc_curve,roc_auc_score
from sklearn.metrics import ConfusionMatrixDisplay
from sklearn.metrics import accuracy_score, recall_score, precision_score,recall_score, f1_score,confusion_matrix
from imblearn.over_sampling import SMOTE
from sklearn.linear_model import LogisticRegression,RidgeClassifier
import xgboost as xgb

```
