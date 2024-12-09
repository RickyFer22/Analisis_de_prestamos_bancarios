# Análisis de préstamos bancarios
Preentrega Trabajo Final - para Curso Data Science Coder House 

## Introducción
Este proyecto de análisis de préstamos bancarios se centra en evaluar patrones y tendencias en la solicitud de crédito en un banco. A partir de los datos recopilados, se pueden obtener recomendaciones para mejorar la eficiencia en la asignación de recursos y optimizar la salud financiera del banco.

## Datos del análisis
Los datos utilizados en este análisis indican que el 79,3% de los préstamos son aprobados, mientras que el 20,7% son rechazados. Además, la mayoría de los préstamos son de corto plazo, con más de 25,000 créditos, mientras que solo alrededor de 10.000 son de largo plazo. La mayoría de los solicitantes tienen una vivienda hipotecada o viven de alquiler, y el propósito más común de los préstamos es la consolidación de deudas.

## Librerías utilizadas
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Missingno
- Plotly
- WordCloud
- Scipy

## Secuencia de pasos

### Limpieza y preparación de datos
El dataset tenía muchos datos faltantes y valores atípicos. Utilicé Pandas y NumPy en Python para limpiar y transformar los datos, preparándolos para el análisis. Se eliminaron columnas con más del 50% de valores nulos, se reemplazaron los valores faltantes con la mediana de cada columna y se eliminaron duplicados.

### Análisis exploratorio de datos (EDA)
Realicé un análisis exhaustivo para entender las variables que más influían en la cancelación de préstamos. Utilicé gráficos y visualizaciones con Matplotlib, Seaborn y Plotly para identificar patrones y relaciones entre las variables. Se analizaron aspectos como el estado del préstamo, el plazo, la puntuación de crédito, el ingreso anual, la antigüedad en el trabajo actual, la propiedad de la vivienda y el propósito del préstamo.

### Correlaciones y dependencias
Se creó una matriz de correlación para identificar relaciones entre las variables numéricas. Se utilizaron gráficos de dispersión y histogramas para visualizar las relaciones entre variables específicas, como el número de problemas de crédito y las quiebras, el crédito máximo abierto y el saldo actual de crédito, y el número de problemas de crédito y los gravámenes fiscales. Se aplicó la correlación de Pearson para cuantificar estas relaciones.

## Visualizaciones y resultados clave

### Préstamos aprobados y rechazados
Se creó un gráfico de pastel que muestra el porcentaje de préstamos aprobados y rechazados, lo que permite una rápida visualización de la distribución de los préstamos.

### Conteo de préstamos por plazo
Se creó un gráfico de barras que muestra la cantidad de préstamos por plazo, lo que ayuda a identificar la popularidad de los diferentes plazos de préstamo.

### Años en el trabajo actual
Se creó un gráfico de barras que muestra la cantidad de veces que aparece cada valor en la columna "Años en el trabajo actual", lo que permite identificar la distribución de la antigüedad laboral de los solicitantes.

### Propiedad de la vivienda
Se creó un gráfico de barras que muestra la cantidad de veces que aparece cada valor en la columna "Propiedad de la vivienda", lo que permite identificar la distribución de la propiedad de la vivienda de los solicitantes.

### Propósitos de préstamo más frecuentes
Se creó un gráfico de barras horizontal que muestra los propósitos de préstamo más frecuentes, lo que permite identificar los principales motivos para los que se solicitan los préstamos.

### Nube de palabras de propósitos de préstamo
Se creó una nube de palabras que muestra las palabras más frecuentes en la columna "Propósito", lo que permite identificar los temas más comunes en los propósitos de préstamo.

### Matriz de correlación
Se creó una matriz de correlación que muestra las relaciones entre las variables numéricas, lo que permite identificar las variables más correlacionadas.

### Gráficos de dispersión y histogramas
Se crearon gráficos de dispersión y histogramas para visualizar las relaciones entre variables específicas, como el número de problemas de crédito y las quiebras, el crédito máximo abierto y el saldo actual de crédito, y el número de problemas de crédito y los gravámenes fiscales.

## Recomendaciones
Las tendencias en la toma de préstamos bancarios pueden ser evaluadas a través del análisis de datos, lo que permite identificar patrones y tendencias en la solicitud de crédito. El banco podría considerar el uso de técnicas de análisis de datos para identificar áreas problemáticas y oportunidades de crecimiento.

El análisis de datos de préstamos bancarios es importante para mejorar la eficiencia en la asignación de recursos y optimizar la salud financiera del banco. Al analizar los datos de los préstamos, el banco puede identificar áreas problemáticas y tomar medidas para mitigar los riesgos y mejorar la eficiencia en la asignación de recursos.

Los segmentos de clientes con un historial crediticio débil y ingresos inestables presentan un mayor riesgo de impagos. El banco puede mitigar este riesgo a través de una evaluación cuidadosa de la información del solicitante y la implementación de medidas de mitigación adecuadas.

A través del análisis de datos de préstamos bancarios, el banco puede identificar oportunidades de crecimiento en determinados segmentos de mercado y realizar ajustes en sus estrategias de préstamos para aprovechar estas oportunidades.

## Conclusiones
En resumen, este proyecto de análisis de préstamos bancarios proporciona información valiosa para el banco sobre patrones y tendencias en la solicitud de crédito. A partir de este análisis, se pueden obtener recomendaciones para mejorar la eficiencia en la asignación de recursos, mitigar riesgos y aprovechar oportunidades de crecimiento. Al utilizar técnicas de análisis de datos, el banco puede mejorar su salud financiera y proporcionar un mejor servicio a sus clientes.
