<h1 align=center> PROYECTO INDIVIDUAL</h1>
<h2 align=center> Data Analytics - Mercado bursátil</h2>

<p align="center"> <img src="img\Big-Data-Analyticsq.jpg"  height=250 ></p>
<br>
Se simulara una situación en donde una empresa que busca invertir en el mercado bursátil. Considerando que la empresa no conoce esta área financiera, se solicita una explicación de qué ha sucedido en este mercado en los últimos años en el rubro de la salud, recomendaciones de inversión y otra información complementaria. Teniendo en cuenta la cantidad de empresas existentes en el mercado bursátil, se le pide limitar el análisis a las empresas pertenecientes al índice Standard & Poor's 500 (S&P 500).

<hr><br>

## Objetivos
En primera instancia, ingestar los datos desde  API de [yahoo finance](https://pypi.org/project/yfinance/) y los indices por empresa, como alguna otra informacion relevante en [Lista índice SP500](https://en.wikipedia.org/wiki/List_of_S%26P_500_companies). Sobre los mismos hacer las transformaciones necesarias. Luego realizar el Análisis Exploratorio de Datos (EDA) mediante `Pandas`, para armar el dashborad mediante `Power BI`. Finalmente analizar la información obtenida y realizar las conclusiones.

<br>

:large_blue_circle: **INICIO** :large_blue_circle:

* [**Datasets**](Datasets): Bases de datos
* [_Análisis de inversión_](Analisis_inversion): Dashboards referentes al analisis exploratorio del indice S&P500
* [_EDA_](EDA.ipynb): cuaderno de notebook, el cual contiene el análisis exploratorio de los datos. <br>
<br>


## EDA

En el mismo se visualizaron los valores nulos, se identificaron y eliminaron duplicados, se imputaron valores faltantes y se procedió a la eliminación de columnas irrelevantes.
El analisis exploratorio de datos se realizó con:    
:small_blue_diamond:**pandas:** Se utilizó para visualizar datos nulos y duplicados de los datasets, junto al formato de los mismos.  
:small_blue_diamond:**yfinance:** Se utilizó para importar los datos desde yahoo finance.   
:small_blue_diamond:**matplotlib y seaborn:** Se utilizó en conjunto para graficar.
<br><br>
