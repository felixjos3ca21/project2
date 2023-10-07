# Proyecto Individual #2 Data Analyst
## Descripción del Problema y Contexto

Los siniestros viales, también conocidos como accidentes de tráfico, son eventos que involucran vehículos en las vías públicas y que pueden tener diversas causas, como colisiones entre automóviles, motocicletas, bicicletas o peatones, atropellos, choques con objetos fijos o caídas de vehículos. Estos incidentes pueden tener consecuencias que van desde daños materiales hasta lesiones graves o fatales para los involucrados.

En el contexto de una ciudad como Buenos Aires, los siniestros viales pueden ser una preocupación importante debido al alto volumen de tráfico y la densidad poblacional. Estos incidentes pueden tener un impacto significativo en la seguridad de los residentes y visitantes de la ciudad, así como en la infraestructura vial y los servicios de emergencia.

Las tasas de mortalidad relacionadas con siniestros viales suelen ser un indicador crítico de la seguridad vial en una región. Reducir estas tasas es un objetivo clave para mejorar la seguridad vial y proteger la vida de las personas en la ciudad.
## Rol desarrollado

Como consultor de datos en FX Data, he tenido el privilegio de llevar a cabo un proyecto en colaboración con el Observatorio de Movilidad y Seguridad Vial (OMSV), un centro de estudios que opera bajo la jurisdicción de la Secretaría de Transporte del Gobierno de la Ciudad Autónoma de Buenos Aires. Nuestra misión consistió en la elaboración de un análisis de datos destinado a proporcionar información esencial que permita a las autoridades locales tomar medidas efectivas para reducir el número de víctimas fatales en siniestros viales. Para llevar a cabo este proyecto, hemos tenido acceso a un valioso conjunto de datos que abarca homicidios en siniestros viales ocurridos en la Ciudad de Buenos Aires durante el período 2016-2021. Este conjunto de datos se presenta en formato xlsx y consta de dos hojas principales: "hechos" y "víctimas". Además, se incluyen dos hojas adicionales con diccionarios de datos que han resultado fundamentales para comprender en profundidad la información compartida.

## Dataset
Los datos utilizados en este proyecto se obtuvieron de la plataforma Buenos Aires Data. Para llevar a cabo el análisis, se empleó específicamente el conjunto de datos titulado 'Homicidios', el cual proporcionó información fundamental sobre siniestros viales y víctimas en la Ciudad de Buenos Aires. Esta fuente confiable y pública ha sido esencial para llevar a cabo un análisis completo y significativo de la seguridad vial en nuestra área de estudio.

- [Buenos Aires Data](https://data.buenosaires.gob.ar/dataset/victimas-siniestros-viales):se utilizo la el dataset de `Homicidios`


## Análisis Exploratorio

Como consultor de datos en FX Data, llevé a cabo un proceso de análisis exploratorio de datos (EDA) en dos archivos de Jupyter Notebook independientes. En el primer archivo, denominado "EDA1.ipynb", me enfoqué en la extracción, transformación y limpieza inicial de los datos. Inicialmente, descargué el conjunto de datos en formato .xlsx, que incluía dos hojas principales: "hechos" y "víctimas". Estas hojas de Excel fueron unidas de manera eficiente utilizando un identificador único de siniestros como clave para garantizar la integridad de los datos.

Luego, en el segundo archivo de Jupyter Notebook, llamado "EDA2.ipynb", procedí a realizar un análisis exhaustivo columna por columna. Cada paso de este análisis fue documentado con claridad, y las conclusiones correspondientes se presentaron en celdas Markdown para una presentación organizada y profesional de los resultados.

Durante el EDA, abordé varios aspectos críticos que son esenciales en cualquier análisis exploratorio de datos. Esto incluyó la búsqueda y el manejo de valores faltantes, la detección y gestión de valores atípicos o extremos (outliers), así como la identificación y gestión de registros duplicados. Además, aseguré que los gráficos utilizados fueran apropiados y coherentes con la tipología de las variables analizadas, lo que facilitó la comprensión y la toma de decisiones posteriores.

## Dashboard Interactivo en Streamlit:

- Presentación visual del dashboard interactivo desarrollado en Streamlit.
- Explicación de las funciones y filtros disponibles en el dashboard para explorar los datos detalladamente.
- Destacar la funcionalidad de selección de variables y la interactividad del dashboard.

## KPIs :
`KPI 1:` Reducción de la Tasa de Homicidios en Siniestros Viales

Gráfico que muestra la evolución de la tasa de homicidios en siniestros viales en CABA en los últimos seis meses.
Cálculo de la tasa de homicidios utilizando la fórmula: (Número de homicidios en siniestros viales / Población total) * 100,000.
Análisis de la tendencia y comparación con el semestre anterior.


`KPI 2:` Reducción de Accidentes Mortales de Motociclistas

Gráfico que muestra la evolución de la cantidad de accidentes mortales de motociclistas en CABA en el último año.
Cálculo de la reducción en un 7% respecto al año anterior.
Análisis de las causas de los accidentes y las estrategias para reducirlos.
Impacto de las medidas de seguridad en los motociclistas.

`KPI 3:` [Tu KPI Propuesto]




















