# Practica Aprendizaje Automatico
Guzmán Muñoz Revuelta: https://github.com/guzzmanmr/GMR_FCP.git
guzman.munoz@cunef.edu
guzzmanmr@gmail.com

Fernando Caruana del Pino: https://github.com/fernandocaruana/GMR_FCP.git
fernando.caruana@cunef.edu
caruanafernando@gmail.com   

OBJETIVOS DEL TRABAJO:
En este trabajo, simularemos un "business case" con nuestra base de datos 'Base', donde la variable target es la de 'fraud_bool', que indica el número de fraudes que hay en el dataframe. En este trabajo crearemos un DICCIONARIO DE VARIABLES, en primer lugar las variables originales (raw) y procesadas. En este paso se intentará sacar valor de las variables. La evaluación de este modelo no es una tarea fácil, por lo que se varias realizarán métricas para observar su desempeño:

FEATURE ENGINEERING y SELECCIÓN DE VARIABLES: proceso de ML que consiste en la creación y selección de características para mejorar el rendimiento de nuestro modelo predictivo. Para ello, se tratarán las variables relevantes para su correcto uso. Por ejemplo, cambiaremos el formato de las fechas de str (2019-01-01) a datetime.

MODELAJE DE LAS VARIABLES: en este apartado se realizarán diferentes modelos como pueden ser árboles de decisión, Bayes o GLM. Además, en el modelo base se imputa la clase mayoritaria, como hicimos en nuestra práctica de Titanic.

MÉTRICA: matriz de confusión (absolutos y relativos %), curva ROC, curva de Ganancia, curva Lift (parecida a la curva de Ganancia pero expresada en otra forma), F1, etc.

En resumen, nuestro objetivo es convertir nuestra base, desde la transformación de datos a hasta la construcción de modelos variados, respaldado por una evaluación exhaustiva que nos permita entender el trabajo realizado. Además, se escogerá el mejor modelo de todos los trabajados en clase en la última parte de este trabajo. Para optimizarlo, se añadirán una serie de hiperparámetros.