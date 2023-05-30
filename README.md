# Adalab-project-da-promo-A-module-3-team-4
En este repositorio nos vamos a encontrar con el proyecto del equipo 4 del Módulo 3 de la promo D del bootcamp de Data Analytics de Adalab. El nombre del equipo es FemmeMetrics  y las integrantes somos Cassia Dafoe, Lorena Mendoza y Elisa Jiménez.

# Resumen

Este proyecto se centra en en la realización de un estudio que consiste en la predicción de los aspectos que más influyen en la cantidad de bicis que se van a alquilar en un día. 


# Planteamiento

- Establecemos los working agreements y designamos a la Scrum Master
- Creamos repositorio en GitHub
- Iniciamos el proyecto



El repositorio consta de cuatro carpetas:

**datos**

- En esta carpeta nos encontraremos con 18 archivos en formato csv y pikl que hemos ido trasnformando y utilizando en nuestro modelo; junto con un archivo readme donde tenemos la descripción de nuestras columnas del dataset.



**EDA**

- Detalla en dos archivos el proceso de recogida, análisis y limpieza de los datos y otro archivo para la visualización de nuestro datos:

1. Comenzamos por entender nuestros datos, haciendo una explicación de la naturaleza de nuestros estos y decidiendo cual va a ser nuestra variable respuesta, que es la variable que vamos a querer predecir.
En este caso, elegimos hacer dos modelos predictivos para dos variables respuesta por las diferencias de los patrones en los datos. Unos nos muestran el comportamiento para un tipo de cliente concreto (el más habitual) y el otro para un tipo de cliente diferente (de tipo más casual).


2. Continuamos realizando un EDA, analizando los datos, detectando datos nulos, outliers y limpiando algunas columnas: unificación variables categóricas, cambio del tipo de dato de la columna fecha (de string a datetime), recodificación de  0 y 1 en algunas variables numéricas, que finalmente resultan ser categóricas (columnas: "días_laborales" y "festivo").

En el archivo de visualización  encontraréis las gráficas de nuestros datos para tener una idea de cómo están distribuidos los mismos y sus agrupaciones.

Revisamos si queremos contar con todas nuestras variable o tenemos algunas redundantes.



**preprocesamiento** 

- Consta de un archivo dónde desarrollamos el siguiente proceso:

1. Aplicamos los cambios que son necesarios, encoding, normalización y estandarización.

2. Estudiamos las correlaciones y la independencia de nuestras variables.

3. Ponemos en práctica el primer modelo de regresión lineal, para el cual tenemos que contar con el cumplimiento de las asunciones de normalidad, heterocedasticidad, independencia. Dado que nuestros datos no cumplen con dichas asunciones, pasamos a los siguientes modelos.



**preprocesamiento_pruebas**

- En dicha carpeta tenemos visible tres archivos con las distintas pruebas que hemos realizado para poder mejorar las métricas de nuestros modelos.



**modelos**

- En la carpeta modelos os encontraréis dos archivos que corresponden a los modelos de prediccón para nuestras variables respuestas elegidas.

En ellos realizamos el modelo de regresión lineal, para el cual tenemos que contar con el cumplimiento de las asunciones de normalidad, heterocedasticidad, independencia.
En nuestro caso, dado que nuestros datos no cumplían las asunciones para poder realizar el modelo de regresión lineal, pasamos a utilizar dos técnicas de aprendizaje automático supervisado. Estos algoritmos van a tomar una serie de decisiones que finaliza con la predicción que estamos buscando, es decir la solución a nuestro problema. Los logaritmos utilizados son el Decision Tree  y el Random Forest.

Ajustamos los modelos mencionados, con los que vamos a trabajar.

Comprobamos las métricas obtenidas en nuestros modelos.



# Librerías utilizadas:

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








