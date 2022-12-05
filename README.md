# Competicion-Kaggle

- OBJETIVO:
 Predecir con el menor error posible los salarios para trabajos relacionados con data en dólares.
 
- PASOS A SEGUIR: 
1) Exploración de los datos.
2) Limpieza.
3) Prueba de modelos.
4) Calculo del error.
5) Entrenamiento y predicción.
6) Subida a Kaggle

- PROCESO DE LIMPIEZA Y EXPLORACIÓN:
Se exploran los datos, mirando la colinealidad, si existen nulos y viendo cuales son las columnas que no aportan información relevante.
Se eliminan los outliers.
Se unen los dataframes de salarios y testeo para que el proceso de limpieza sea mas rápido.
Se eliminan las columnas de salary, employee_residence y salary_currency.
Se normalizan las columnas year y remote_ratio. Para el resto de columnas, las cuales son categóricas, se utiliza get dummies.

- APLICACION DE MACHINE LEARNING:
Una vez que los datos estan en el formato escogido, se testean en una función para poder conocer cual es el modelo que mejor funciona para los datos.
El modelo que menor error obtenia fue RIDGE, el cual se volvio a entrenar y con el cual se realizo la predicción del testeo.
Para finalizar se subio el archivo a Kaggle para comprobar el error que se obtiene con los datos reales.

