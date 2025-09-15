# Proyecto DataProject - Dashboard de Análisis de Datos (Fútbol de Selecciones)

Dashboard en Excel sobre partidos de fútbol de selecciones nacionales entre 2000 y 2021. Incluye datos originales y análisis exploratorio.

## Datos
- Archivo de datos originales: `international_matches.csv`
- Fuente de los datos: [OpenDataBay](https://www.opendatabay.com/data/dataset/2cf0122c-a2b3-4994-8b89-e603b4bc4a49)

## Pasos del análisis
1. Recolección de datos desde fuentes libres en Internet.  
2. Limpieza y transformación de los datos en Excel.  
3. Creación del dashboard con gráficos, tablas y KPIs.  
4. Interpretación de los resultados y hallazgos principales.  

## Conclusiones / Insights
- Se pueden destacar patrones como el **crecimiento y decrecimiento de los goles anotados por año**, en paralelo con el aumento o disminución de partidos, lo cual es un patrón normal y esperable. Cabe mencionar cómo en el año 2020 el número de goles y partidos fue mucho menor; en este caso asociamos dicha anomalía con la pandemia mundial provocada por el Covid-19.  
- Gracias al gráfico de barras inferior se aprecia cómo las **selecciones europeas dominan en goles y partidos**, lo que indica que su nivel es mayor y que, por lo tanto, participan en más competiciones y alcanzan fases más avanzadas en torneos como el Mundial. También destaca que el **continente africano suma más goles que el asiático** pese a tener aproximadamente 500 apariciones menos. Esto podría indicar que los equipos africanos son más ofensivos (meten más goles) o más vulnerables defensivamente (conceden más tantos). Por último, se observa que **Oceanía es el continente con menos goles y partidos**, algo lógico considerando el número de países que lo componen y la menor relevancia del fútbol en la región.  
- En el apartado de países anfitriones sorprende **Estados Unidos**, que, a pesar de no ser un país donde el fútbol sea el deporte principal, se coloca como el que más partidos de selecciones ha albergado en esos 21 años. También llama la atención la **escasa aparición de países europeos** en esta gráfica: pese a ser estadísticamente los más dominantes del deporte rey, no disfrutan de más partidos en territorio propio (quizás debido al tamaño de los países o a la distribución más dispersa de los encuentros).  
- Tras revisar el número de partidos y goles anotados, se obtiene una media aproximada de **2,6 goles por partido**.  

## Estructura del repositorio
- `README.md` → este archivo con explicación del proyecto  
- `international_matches.csv` → archivo CSV con los datos originales  
- `Dashboard_Proyecto.xlsx` → archivo de Excel con el dashboard completo
