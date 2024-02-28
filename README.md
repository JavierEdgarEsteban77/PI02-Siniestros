![Logo.png](https://github.com/JavierEdgarEsteban77/PI02/blob/7df46b2900c4000f56edb63e079ad3b8cdcf5115/Archivos%20ETL%20y%20EDA/Logo%20Siniestros.png)


# Proyecto de Inteligencia de Datos y Análisis de Siniestros Viales en la Ciudad Autónoma de Buenos Aires (CABA)

Este repositorio contiene el trabajo realizado en el análisis de siniestros viales en la Ciudad Autónoma de Buenos Aires (CABA). El proyecto se divide en dos partes principales: la Extracción, Transformación y Carga (ETL) de los datos y el Análisis Exploratorio de Datos (EDA).

## Extracción, Transformación y Carga (ETL)

En el archivo `ETL.ipynb`, se realiza la extracción de los datos de las fuentes relevantes, se transforman en un formato adecuado para el análisis y se cargan en una base de datos MySQL. Se utilizan varias bibliotecas de Python, como pandas y numpy, para manipular los datos y prepararlos para el análisis.

## Análisis Exploratorio de Datos (EDA)

En el archivo `EDA.ipynb`, se realiza un análisis exploratorio de los datos. Se utilizan varias bibliotecas de Python, como matplotlib y seaborn, para visualizar los datos y entender las relaciones entre las diferentes variables.

## Visualización de Archivos Grandes con Git LFS

Este repositorio utiliza Git LFS (Large File Storage) para gestionar archivos grandes, como el archivo 2_EDA.ipynb. Asegúrese de seguir estos pasos para visualizar y trabajar con estos archivos correctamente.

Pasos para Visualizar EDA.ipynb:

Clone el repositorio: git clone https://github.com/JavierEdgarEsteban77/PI02-Siniestros.git

Instale y Configure Git LFS: git lfs install

Descargue el archivo LFS: git lfs pull

Ya descargado el archivo podrá abrirlo en su entorno local de Jupyter Notebook.

## Resultados

El análisis de los datos revela varias conclusiones importantes sobre los siniestros viales en la CABA:

1. La mayoría de los siniestros viales que resultaron en homicidios involucran a una sola víctima, con muy pocos casos que involucran a dos víctimas.

2. En los siniestros viales que resultaron en lesiones, la mayoría también involucra a una sola víctima. Sin embargo, a diferencia de los homicidios, hay una mayor diversidad en el número de víctimas en los casos de lesiones.

3. La distribución geográfica de los siniestros viales muestra que estos ocurren en toda la CABA, con cada punto en el gráfico representando un siniestro vial.

4. Los siniestros viales parecen ser más frecuentes durante ciertos meses como febrero, noviembre y diciembre.

5. La distribución de siniestros viales es bastante uniforme a lo largo de los días de la semana, lo que sugiere que no hay un día particularmente más peligroso que otro en términos de siniestros viales.

6. Las horas más peligrosas del día, donde se registran más siniestros viales, son las que se muestran en el gráfico de las "Top 5 Horas con Más Siniestros Viales".

7. El 76% de las víctimas son masculinas, mientras que el 24% restante son femeninas.

Estos resultados proporcionan una visión clara de la gravedad y el alcance de los siniestros viales en términos del número de víctimas involucradas. Los hallazgos pueden ser útiles para las autoridades y los planificadores de la ciudad para crear campañas de concientización y planificar intervenciones de seguridad vial.

## Librerías y paquetes utilizados

Este proyecto utiliza varias librerías y paquetes de Python, incluyendo pandas, numpy, matplotlib, seaborn y mysql-connector-python.


