# Quantitative Analysis

![Github Header](https://github.com/anaemcaro/QuantitativeAnalysis/assets/162106147/45f5881d-c4be-4e2e-8585-9fccb39bd06b)

[En Español, por favor.](https://github.com/anaemcaro/QuantitativeAnalysis?tab=readme-ov-file#an%C3%A1lisis-cuantitativo)
### Basic Quantitative Analysis of Market Indexes

## Overview
In this project I am going to make a basic quantitative analysis of the three principal market indexes: Dow Jones, S&P500 and Nasdaq; in order to compare them and answer the research question:
* **Do the three principal indexes behave the same way, even though they are a representation of different sectors of the market?**

These three indexes are also calculated with different methodologies. The result of this analysis can lead to a better understanding of the U.S. stock market and answering to this question can help a normal person to decide where to invest their savings and how to balance the investment of that money to obtain a better revenue in the mid- to long-term.

## Setup
The code used was Python on Google Colaboratory, but the notebook can be downloaded and read with Jupyter.

### Packages
* yfinance for collecting the data
* pandas, datetime for data manipulation
* plotly for data visualization

## Data
The data used was this [dataset](https://github.com/anaemcaro/QuantitativeAnalysis/blob/main/index_data.csv), I collected using yfinance API and then  preprocessed to obtain a simplified dataset with the Daily Closing Price for each of the three indexes during a 2-year period.

## Structure
The structure here is pretty straightforward:
* Notebook: [Data_yfinance.ipynb](https://github.com/anaemcaro/QuantitativeAnalysis/blob/main/Data_yfinance.ipynb) for collecting and preprocessing the data
* Data [indexes_data.csv](https://github.com/anaemcaro/QuantitativeAnalysis/blob/main/index_data.csv)
* Notebook [Quantitative_Analysis_ipynb](https://github.com/anaemcaro/QuantitativeAnalysis/blob/main/Quantitative_Analysis_1.ipynb) where the analysis was carried out 

## Results
The answer to the research question **Do the three principal indexes behave the same way, even though they are a representation of different sectors of the market?**  is **YES**:

The Dow Jones, S&P500 and Nasdaq indexes have a strong Correlation and are similar in terms of Volatility, Performance, Risk and Trends. So, any of them showed a good picture of the market during the 2-year period.

## Reflection
Here, I have chosen to perform a Basic Quantitative Analysis of the three most representative indexes in the stock market. It turned out that the three of them have very similar characteristics. I think this happens because the indexes, each one in its particular area, reflect the market in general.

That raises other questions to me:

What could be the impact on the economy if the indexes didn’t behave in a similar way? What event could cause such a behavior?

How will look this analysis if it is applied to other investments, such as stocks that are in and out of the indexes, or crypto?

These questions could lead to a more in depth understanding of the market and help investors that are willing to take more risks with their investments.


## Acknowledges/References
* The project was inspired on [Quantitative Analysis of Stock Market using Python](https://thecleverprogrammer.com/2024/01/15/quantitative-analysis-of-stock-market-using-python/) by Aman Kharwal
* Header: Image by <a href="https://pixabay.com/users/u_3u3n7wt5sr-39571676/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=8305514">u_3u3n7wt5sr</a> from <a href="https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=8305514">Pixabay</a>
* Divider: Image by <a href="https://pixabay.com/users/gdj-1086657/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=7551966">Gordon Johnson</a> from <a href="https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=7551966">Pixabay</a>

![divider](https://github.com/anaemcaro/QuantitativeAnalysis/assets/162106147/67c3d010-dc03-4571-9603-91df391776e6)


# Análisis Cuantitativo
### Análisis Cuantitativo Básico para los Índices de Mercado

## Descripción
En este proyecto voy a hacer un análisis cuantitativo básico de los tres principales índices del mercado: Dow Jones, S&P500 y Nasdaq; con el fin de compararlos y responder la pregunta:
* **¿Los tres indices principales se comportan de la misma forma, incluso cuando representan diferentes sectores del mismo?**

Estos tres índices son calculados con diferentes metodologías. El resultado de este análisis puede producir un mejor entendimiento del mercado de los E.U., y la respuesta a esta pregunta puede ayudar a cualquier persona a decidir dónde inventir sus ahorros y cómo balancear la inversión de ese dinero para obtener un mejor rendimiento de mediano a largo plazo.

## Configuración
El lenguaje usado fue Python en un cuaderno Google Colaboratory, el cual puede ser bajado y leído con Jupyter Notebooks.

### Paquetes
* yfinance para reclectar la data
* pandas, datetime para la maipulación de la data
* plotly para la visualización de la data

## Data
Se utilizó este [dataset](https://github.com/anaemcaro/QuantitativeAnalysis/blob/main/index_data.csv), el cual creé usando la API yfinance y luego lo preprocesé para obtener un dataset simplificado con los Precios de Cierre Diarios para cada uno de los índices durante un período de 2 años.

## Estructura
La estructura aquí es bastante sencilla:
* Cuaderno: [Data_yfinance.ipynb](https://github.com/anaemcaro/QuantitativeAnalysis/blob/main/Data_yfinance.ipynb) para recolectar y preprocesar la data
* Dataset: [indexes_data.csv](https://github.com/anaemcaro/QuantitativeAnalysis/blob/main/index_data.csv)
* Cuaderno: [Quantitative_Analysis_ipynb](https://github.com/anaemcaro/QuantitativeAnalysis/blob/main/Quantitative_Analysis_1.ipynb) donde realicé el análisis como tal.

## Resultados
La respuesta a la pregunta **¿Los tres indices principales se comportan de la misma forma, incluso cuando representan diferentes sectores del mismo?**  es **SI**:

Los índices Dow Jones, S&P500 and Nasdaq tienen una fuerte correlación y son similares en términos de volatilidad, rendimiento, riesgo y tendencias. Por lo tanto, cualquiera de ellos es una buena representación del mercado durante el período de 2 años estudiado.

## Reflection
En este análisis, yo escogí desarrollar un Análisis Cuantitativo Básico de los tres índices del mercado más importantes.  Resultó que tienen características similares. Pienso que es porque cada índice, de alguna manera representa al mercado en general desde su sector en particular. 

Esta conclusión me hace plantear otras preguntas:

* ¿Cuál podría ser el impacoto en la economía si los índices no tuvieran un comportamiento similar? ¿Qué tipo de eventos podrían causar un comportamiento así?
* ¿Cuál sería el análisis si se aplicara a otro tipo de instrumentos, como acciones que estén dentro y fuera de los índices, o incluso criptomonedas?

Estas preguntas podrían llevar a un entendimiento más profundo del mercado de capitales y ayudar a inversores dispuestos a tomar más riesgos a decidir sobre sus inversiones.

## Agradecimientos/Referencias
* Este proyecto fue inspirado en [Quantitative Analysis of Stock Market using Python](https://thecleverprogrammer.com/2024/01/15/quantitative-analysis-of-stock-market-using-python/) por Aman Kharwal
* Imagen de principal: Image by <a href="https://pixabay.com/users/u_3u3n7wt5sr-39571676/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=8305514">u_3u3n7wt5sr</a> from <a href="https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=8305514">Pixabay</a>
* Imagen divisora: Image by <a href="https://pixabay.com/users/gdj-1086657/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=7551966">Gordon Johnson</a> from <a href="https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=7551966">Pixabay</a>


