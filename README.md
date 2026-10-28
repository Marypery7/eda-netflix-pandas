# EDA: Análisis exploratorio del catálogo de Netflix

## 1. Descripción del proyecto

Este proyecto consiste en realizar un análisis exploratorio de datos (EDA, *Exploratory Data Analysis*) del catálogo de películas y series de Netflix utilizando Python.

El objetivo es explorar, limpiar e interpretar los datos para identificar patrones y responder preguntas sobre los tipos de contenido, las categorías, los años de estreno y los países asociados a los títulos.

## 2. Dataset utilizado

El análisis se realiza a partir de un archivo CSV con información sobre el catálogo de Netflix.

📂 **[Consultar y descargar el archivo CSV](https://github.com/Marypery7/eda-netflix-pandas/blob/main/netflix_titles%202.csv)**

El archivo contiene información como el título, el tipo de contenido, el director, el reparto, el país, el año de estreno, la duración, la clasificación y las categorías.

## 3. Herramientas utilizadas

- **Python:** lenguaje de programación utilizado para el análisis.
- **Pandas:** carga, organización, limpieza y análisis de los datos.
- **NumPy:** herramientas para operaciones numéricas.
- **Matplotlib:** creación de gráficos.
- **Seaborn:** visualización de datos estadísticos.
- **Google Colab:** entorno utilizado para ejecutar el código.

## 4. Proceso de análisis

1. Importación de las librerías necesarias.
2. Carga del archivo CSV y exploración de los primeros registros.
3. Detección de valores ausentes.
4. Tratamiento de los datos incompletos.
5. Comparación entre películas y series mediante un gráfico de barras.
6. Análisis de las categorías más frecuentes, separando las categorías que aparecen juntas.
7. Estudio del número de títulos por año de estreno mediante un gráfico de líneas.
8. Análisis de los países asociados a los títulos mediante un gráfico de barras.
9. Interpretación de los resultados y elaboración de conclusiones.

## 5. Preguntas de investigación y resultados

### ¿Hay más películas o series?

En el archivo analizado hay 6.131 películas y 2.676 series. Por tanto, predominan las películas, que representan aproximadamente el 70 % de los títulos.

### ¿Qué categorías aparecen más?

Al separar las categorías que aparecen juntas, las más frecuentes son:

- International Movies: 2.752 apariciones.
- Dramas: 2.427 apariciones.
- Comedies: 1.674 apariciones.

Un mismo título puede pertenecer a varias categorías, por lo que estos recuentos no representan títulos exclusivos.

### ¿Cómo ha cambiado el número de títulos por año?

El gráfico muestra que el número de títulos aumenta notablemente a partir de los años 2000 y alcanza su punto más alto alrededor de 2018. Después, se observa una disminución.

Es importante recordar que analizamos el año de estreno de las películas y series, no el año en que Netflix las añadió a su catálogo.


### ¿Qué países tienen más títulos asociados?

Tras separar los países que aparecen juntos en una misma celda, los tres primeros son:

- Estados Unidos: 3.689 apariciones.
- India: 1.046 apariciones.
- Reino Unido: 804 apariciones.

Un mismo título puede estar asociado a varios países y contabilizarse una vez para cada uno.

## 6. Conclusiones

El análisis del catálogo de Netflix muestra que hay más películas que series en el conjunto de datos estudiado.

Los géneros con más apariciones son International Movies, Dramas y Comedies. En cuanto a los países, Estados Unidos ocupa el primer lugar, seguido de India y Reino Unido.

La gráfica por año de estreno muestra un crecimiento importante del número de títulos hasta alcanzar un máximo alrededor de 2018, seguido de una disminución.

Este proyecto me ha permitido practicar la limpieza y el análisis de datos con Pandas, así como la creación de gráficos con Matplotlib y Seaborn.

## 7. Limitaciones del análisis

Los resultados describen únicamente los datos del archivo CSV utilizado. No representan toda la producción audiovisual mundial ni necesariamente el catálogo actual completo de Netflix.

Además, existen valores ausentes y títulos asociados a varias categorías o países, aspectos que deben tenerse en cuenta al interpretar los recuentos.



