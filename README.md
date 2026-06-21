## 📄 Informe del análisis sísmico

<p align="center">

<a href="https://github.com/linis28/ANALISIS_DE_SISMOS_CON_R/raw/main/docs/Junio_07_06_2020.pdf">
  <img src="https://img.shields.io/badge/📥%20Descargar%20PDF-Informe%20Sísmico-red?style=for-the-badge&logo=adobeacrobatreader&logoColor=white">
</a>

</p>


# Descarga pdf:
# https://github.com/linis28/ANALISIS_DE_SISMOS_CON_R/raw/main/docs/Junio_07_06_2020.pdf



Análisis Espacial y Temporal de la Actividad Sísmica mediante Métodos de Estadística Espacial con R
Resumen (Abstract)

Este trabajo presenta un análisis estadístico de la actividad sísmica mediante técnicas de estadística espacial y temporal implementadas en el entorno de programación R. El objetivo es caracterizar la distribución geográfica, la intensidad y los patrones de ocurrencia de eventos sísmicos en una región determinada. Se emplean métodos de análisis exploratorio de datos, estimación de densidad kernel, clustering espacial y visualización georreferenciada para identificar estructuras espaciales significativas. Los resultados evidencian que la actividad sísmica no se distribuye de forma aleatoria, sino que presenta agrupamientos asociados a estructuras tectónicas. El enfoque computacional adoptado permite la reproducibilidad del análisis y su extensión a nuevos conjuntos de datos.

Palabras clave: sismología, estadística espacial, R, análisis de clusters, kernel density, series temporales.

1. Introducción

El análisis de la actividad sísmica es fundamental para la comprensión de los procesos geodinámicos de la Tierra y la evaluación del riesgo sísmico. Los eventos sísmicos presentan una naturaleza altamente espacial y temporal, lo que hace necesario el uso de herramientas estadísticas avanzadas para su estudio.

En este trabajo se propone un enfoque basado en estadística espacial y análisis computacional utilizando R, con el objetivo de identificar patrones de distribución y concentración de eventos sísmicos.

2. Datos y Metodología
2.1 Datos

Se utilizaron registros sísmicos que incluyen variables como:

Latitud
Longitud
Profundidad
Magnitud
Fecha y hora del evento

Los datos fueron sometidos a procesos de limpieza, depuración y estructuración para garantizar consistencia analítica.

2.2 Métodos estadísticos

Se aplicaron las siguientes técnicas:

Análisis exploratorio de datos (EDA): evaluación de distribuciones de magnitud y profundidad.
Estimación de densidad kernel (KDE): identificación de zonas de alta concentración sísmica.
Clustering espacial: agrupamiento de eventos mediante métodos basados en distancia geográfica (p.ej., K-means).
Análisis de series temporales: estudio de la frecuencia de ocurrencia de eventos.
Visualización geoespacial: mapas de puntos y superficies de densidad.
2.3 Herramientas computacionales

El análisis fue desarrollado en el lenguaje de programación R, utilizando los siguientes paquetes:

sf (manipulación de datos espaciales)
sp (estructuras espaciales)
ggplot2 (visualización)
tmap (cartografía temática)
raster (análisis espacial continuo)

El flujo de trabajo fue diseñado para ser reproducible y escalable.

3. Resultados

Los resultados del análisis muestran que la distribución de eventos sísmicos presenta patrones espaciales claramente no aleatorios. La estimación de densidad kernel permite identificar regiones con alta concentración de actividad sísmica, las cuales se asocian a estructuras tectónicas conocidas.

El análisis de clustering confirma la existencia de agrupamientos espaciales significativos, mientras que el análisis temporal sugiere episodios de concentración de eventos en periodos específicos.

4. Discusión

Los resultados obtenidos son consistentes con la teoría sismológica, que establece que los eventos sísmicos tienden a concentrarse en zonas de interacción de placas tectónicas. La combinación de métodos estadísticos espaciales y herramientas computacionales permite una caracterización más precisa de estos patrones.

El uso de R como entorno de análisis facilita la reproducibilidad del estudio y la integración de nuevas fuentes de datos.

5. Conclusiones
   
La actividad sísmica presenta una estructura espacial claramente no aleatoria.
Las técnicas de KDE y clustering permiten identificar zonas de alta recurrencia sísmica.
Existe evidencia de agrupamientos temporales en la ocurrencia de eventos.
El enfoque basado en R es adecuado para análisis reproducibles en sismología computacional.
Este estudio proporciona una base metodológica para futuras investigaciones en riesgo sísmico y modelización estadística.

7. Referencias 
[1] Cressie, N. (1993). Statistics for Spatial Data. Wiley.
[2] Pebesma, E. (2018). Simple Features for R: Standardized Support for Spatial Vector Data.
[3] Bivand, R. et al. (2013). Applied Spatial Data Analysis with R.
[4] Chambers, J. (2008). Software for Data Analysis: Programming with R.










