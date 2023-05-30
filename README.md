# Adalab-project-da-promo-A-module-3-team-4
En este repositorio nos vamos a encontrar con el proyecto del equipo 4 del Módulo 3 de la promo D del bootcamp de Data Analytics de Adalab. El nombre del equipo es FemmeMetrics  y las integrantes somos Cassia Dafoe, Lorena Mendoza y Elisa Jiménez.

# Resumen

Este proyecto se centra en en la realización de un estudio que consiste en la predicción de los aspectos que más influyen en la cantidad de bicis que se van a alquilar en un día. 


# Planteamiento

- Establecemos los working agreements y designamos a la Scrum Master
- Creamos repositorio en GitHub
- Iniciamos el proyecto, analizando los datos con los que vamos a trabajar. 


# Procedimiento

- RECOGIDA Y LIMPIEZA DE DATOS:
1. Comenzamos por entender nuestros datos, haciendo una explicación de la naturaleza de nuestros estos y decidiendo cual va a ser nuestra variable respuesta, que es la variable que vamos a querer predecir.

2. Continuamos realizando un EDA, analizando los datos, detectando datos nulos, outliers y limpiando algunas columnas: unificación variables categóricas, cambio del tipo de dato de la columna fecha (de string a datetime), recodificación de  0 y 1 en algunas variables numéricas, que finalmente resultan ser categóricas (columnas: "días_laborales" y "festivo").
Contamos también con un archivo de visualización de nuestros datos para tener una idea de cómo están distribuidos nuestros datos y sus agrupaciones.
Revisar si queremos contar con todas nuestras variable o tenemos algunas redundantes.
Aplicamos los cambios que son necesarios, encoding, normalización y estandarización.

3. Estudiamos las correlaciones y la independencia de nuestras variables.

4. El siguiente paso es realizar el modelo de regresión lineal, para el cual tenemos que contar con el cumplimiento de las asunciones de normalidad, heterocedasticidad, independencia.
En nuestro caso, nuestros datos no cumplían las asunciones para poder realizar el modelo, por lo que pasamos a utilizar dos técnicas de aprendizaje automático supervisado. Estos algoritmos van a tomar una serie de decisiones que finaliza con la predicción que estamos buscando, es decir la solución a nuestro problema. Los logaritmos utilizados son el Decision Tree  y el Random Forest.

Ajuustamos los modelos mencionados, con los que vamos a trabajar.

Comprobamos las métricas obtenidas en nuestros modelos.


>Las librerías con las que hemos trabajado en este repositorio son:
>
>- [NumPy](https://numpy.org/)
>- [Pandas](https://pandas.pydata.org/) 
>- [Matplotlib](https://matplotlib.org/)
>- [Seaborn](https://seaborn.pydata.org/)
>- [Datetime](https://docs.python.org/es/3/library/datetime.html)
>- [SciPy](https://scipy.org/)
>- [Statsmodels](https://www.statsmodels.org/stable/index.html)
>- [Sklearn](https://scikit-learn.org/stable/)
>- [Imblearn](https://imbalanced-learn.org/stable/)
>- [Researchpy](https://researchpy.readthedocs.io/en/latest/)
>- [Itertools](https://docs.python.org/3/library/itertools.html)
>








