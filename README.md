# AQI-MX-SIC
# Modelos de aprendizaje automático para predicción del AQI en la Ciudad de México, Monterrey y Guadalajara

Para las ciudades: Ciudad de México (CMX), Monterrey (MTY) y Guadalajara (GDL), desarrollar y evaluar modelos de predicción utilizando algoritmos de aprendizaje automático para predecir las concentraciones de los contaminantes relevantes para el Índice de Calidad del Aire (AQI) según IMECA, como lo son: PM10, NO₂, O₃ y CO. 
---

## Descripción
A partir de estaciones de monitoreo de las principales ciudades de México: Ciudad de México (CMX), Monterrey (MTY) y Guadalajara (GDL), desarrollar y evaluar modelos de predicción utilizando algoritmos de aprendizaje automático para predecir las concentraciones de los contaminantes relevantes para el Índice de Calidad del Aire (AQI) según IMECA, como lo son: PM10, NO₂, O₃ y CO. Con el fin de prever los niveles de contaminación atmosférica, optimizar las estrategias de monitoreo de la calidad del aire, y proporcionar información confiable para la toma de decisiones ambientales y de salud pública.
## Características
PM10, NO₂, O₃, CO, network_code
## Uso
A través de la predicción, prever los niveles de contaminación atmosférica, optimizar las estrategias de monitoreo de la calidad del aire, y proporcionar información confiable para la toma de decisiones ambientales y de salud pública.
## Librerías
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler
from sklearn.linear_model import LinearRegression
from sklearn.neighbors import KNeighborsRegressor
from sklearn.svm import SVR
from sklearn.metrics import mean_absolute_error, mean_squared_error
## Autores
- Reyes García Diego
- Santibáñez Rivero Gabriela

## Pasos para clonar el proyecto en local
Pasos para clonar y ejecutar el proyecto en local.
Asegurate de tener los datos crudos en la misma carpeta que los Notebooks

Requisitos previos: Para compilar el programa debes asegurarte de tener todas las librerías mencionadas, el programa fue compilado en Google Colab
