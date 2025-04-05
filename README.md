# 🌍Análisis del Flujo de Radiación de Onda Larga Saliente (ULWRF) en Estados Unidos

[![Python Version](https://img.shields.io/badge/python-3.10-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Project Status](https://img.shields.io/badge/estado-en%20desarrollado-green)]()

Este proyecto analiza el Flujo de Radiación de Onda Larga Saliente (ULWRF) en la superficie a partir de datos climáticos en formato NetCDF. Se realizan estudios espaciales y temporales para entender la variabilidad y tendencias en los Estados Unidos, incluyendo:

- 🌍 Climatología mensual y anual

- 📉 Anomalías climáticas

- 🔄 Comparaciones entre eventos ENSO (El Niño, La Niña, Neutro)

- 📊 Representación gráfica de los resultados


---

## 📊 Contenido del análisis

- ✅ Carga y procesamiento de datos NetCDF con `xarray` y `netCDF4`.
- ✅ Visualización de mapas y series temporales con `matplotlib` y `cartopy`.
- ✅ Cálculo de climatología media y anomalías mensuales.
- ✅ Análisis mensual y distribución estacional del ULWRF.
- ✅ Comparación espacial de eventos ENSO (El Niño, La Niña, Neutro).
- ✅ Animación del ciclo anual multianual (GIF).
- ✅ Análisis tipo artículo en PDF.

---

## 🧰 Tecnologías utilizadas y requisitos

- Python 3.10
- Jupyter Notebook
- xarray
- netCDF4
- numpy
- pandas
- matplotlib
- seaborn
- cartopy
- imageio

---

## 📁 Estructura del repositorio

```bash
📦ulwrf-analysis/
 |-- 7_ciclo_multianual/
        |-- 00_Enero_ULWRF.png
        |-- 01_Febrero_ULWRF.png
        |-- ...
        |-- 11_Diciembre_ULWRF.png
        |-- 2_dispersión_ulwrf.png
        |-- 3_mapa_climatologia_ulwrf.png
        |-- 4_promedio_espacial_serie.png
        |-- 5_caja_bigotes_mes.png
        |-- 5_diagrama_caja_bigotes.png
        |-- 5_histograma.png
        |-- 6_anomalias_mensuales.png
        |-- 7_ciclo_multianual.gif
        |-- 8_anomalias_climaticas.png
        |-- 8_mapas_subgraficos.png
    |-- index.ipynb
    |-- README.md
    |-- Análisis.pdf
    |-- ulwrf.sfc.mon.mean.nc
```

## 🚀 Uso
1. Abre el archivo index.ipynb en Jupyter Notebook.

2. Ejecuta las celdas para cargar y analizar los datos de ULWRF.

3. Los resultados gráficos se guardan en la carpeta 7_ciclo_multianual/.

## 📊 Resultados

Se incluyen representaciones visuales como:

- 🗺️ Mapas climatológicos

- 📊 Análisis de anomalías

- 📈 Histogramas y diagramas de caja

- ⏳ Serie temporal del promedio espacial

## 📜 Licencia
MIT © [JuDa](https://github.com/Juda-Tech-Green)
Hecho con 💚 & Python

![Pro environmentalist badge](https://img.shields.io/badge/dev-environmentalist-green)

