# Análisis del Cambio Climático en República Dominicana con R

## Descripción

Este proyecto tiene como objetivo analizar datos climáticos históricos de la República Dominicana para identificar patrones de cambio y proponer planes de mitigación. Utiliza R y RStudio para la manipulación, análisis y visualización de los datos, centrándose en variables clave como la temperatura y la precipitación.

## Estructura del Proyecto

`SIG_Trabajo-Final-Script.R`: Script principal que realiza la limpieza, análisis y visualización de los datos.

`climate_data_rd.csv`: Dataset generado con 500 registros simulados sobre temperatura, precipitación y región en República Dominicana.

## Instalación

1. Clona este repositorio:
```
https://github.com/simelbarranco/Proyecto-Cambio-Climatico-SIG.git
```
2. Abre el proyecto en RStudio.
3. Instala los paquetes necesarios:
```
install.packages(c("tidyverse", "lubridate", "ggplot2", "dplyr", "sf", "raster", "leaflet", "plotly"))
```

## Uso

1. Ejecuta el script `SIG_Trabajo-Final-Script.R` para:

- Limpiar y explorar los datos.
- Generar visualizaciones de temperatura y precipitación.
- Identificar regiones críticas y proponer planes de mitigación.

2. El informe final se genera automáticamente al ejecutar el script.

## Resultados Esperados

- Identificación de tendencias de temperatura y precipitación.
- Reconocimiento de regiones críticas.
- Propuestas de acciones para mitigar los efectos del cambio climático.