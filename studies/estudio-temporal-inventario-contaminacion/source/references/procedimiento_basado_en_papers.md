# Procedimiento basado en papers

## 1. Agregacion diaria
- El inventario se resume por dia porque esa es su resolucion natural.
- Los sensores se agregan a medias diarias ciudadanas por parametro.

## 2. Variables principales
- CO2 y NO2 son los contaminantes objetivo.
- Se comparan relaciones directas del mismo dia entre inventario y sensores.
- Se incluye una lectura auxiliar de actividad diaria con trips_total frente a NO2.

## 3. Modelos
- Se calculan correlaciones Pearson y Spearman del mismo dia.
- Se ajustan modelos OLS simples y OLS con meteorologia.

## 4. Lectura
- El estudio estima asociacion temporal diaria, no causalidad fuerte.

## Papers usados
### 2020 - Carbon Monitor: a near-real-time daily dataset of global CO2 emission from fossil fuel and cement production
- Uso en este estudio: Justifica trabajar con emisiones diarias y leer el inventario como una señal temporal de actividad emisora.
- URL: https://arxiv.org/abs/2006.07690

### 2022 - Near-real-time estimates of daily CO2 emissions from 1500 cities worldwide
- Uso en este estudio: Refuerza la relevancia de una lectura diaria de emisiones urbanas y su uso para seguimiento casi en tiempo real.
- URL: https://arxiv.org/abs/2204.07836

### 2018 - Effects of meteorology and emissions on urban air quality: a quantitative statistical approach to long-term records (1999–2016) in Seoul, South Korea
- Uso en este estudio: Sustenta que en estudios temporales urbanos hay que interpretar contaminación y emisiones junto a la meteorología.
- URL: https://acp.copernicus.org/articles/18/16121/2018/

### 2015 - The effect of Beijing's driving restrictions on pollution and economic activity
- Uso en este estudio: Aporta una referencia clásica para leer cambios temporales de contaminación asociados a variaciones del tráfico y la actividad.
- URL: https://mpra.ub.uni-muenchen.de/33009/

### 2025 - Air Quality Assessment During the Initial Implementation Phase of a Traffic-Restricted Zone in an Urban Area: A Case Study Based on NO2 Levels in Seville, Spain
- Uso en este estudio: Contexto español reciente para interpretar patrones temporales de NO2 bajo cambios de movilidad y condiciones meteorológicas.
- URL: https://www.mdpi.com/2227-9717/13/3/645
