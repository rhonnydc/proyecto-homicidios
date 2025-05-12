Proyecto de Análisis de Homicidios por País y Región

Este proyecto es un análisis exploratorio de datos de homicidios a nivel global usando Python y bibliotecas como `pandas`, `matplotlib`, `seaborn` y `plotly`. Los datos se obtienen de una fuente pública alojada en GitHub, y contienen información
como tasa de homicidios, cantidad de casos, regiones y subregiones desde 2017 a 2021.

Herramientas utilizadas:
- Python 3
- Pandas
- Matplotlib
- Seaborn
- Plotly
- Google Colab

Objetivos del proyecto:
- Practicar transformación de datos (`groupby`, `sort_values`, `unstack`, etc)
- Visualizar las diferencias por año y región con gráficos de pastel, barras y líneas
- Identificar países con mayores tasas y cantidades absolutas de homicidios

Estructura del notebook:
1. Carga y visualización del dataset
2. Limpieza básica de datos
3. Conversión de tipos (`astype`)
4. Agrupaciones por año, región y subregión
5. Visualizaciones:
   - Gráfico de pastel: Top 5 países por número de homicidios
   - Barras por región
   - Línea temporal de homicidios por año y región
  

Fuente de datos: https://raw.githubusercontent.com/Rruhid/data/refs/heads/master/homicide_by_countries.csv

 Cómo ver/usar este proyecto:
1. Abre el archivo `Proyecto_Homicidios.ipynb` en Google Colab o Jupyter Notebook.
2. Ejecuta las celdas paso a paso.
3. Se puede modificar los filtros o visualizaciones para analizar otras regiones o años.

