# K-means---Segmentacion--de--Jurisdicciones--Argentinas--por--Viviendas--Habitadas
1.Modelo de aprendizaje no supervisado (K-Means) en Python para agrupar las provincias de Argentina según datos del Censo 2022 (INDEC).

# 🇦🇷 Segmentación de Jurisdicciones Argentinas (K-Means)

Proyecto para la materia **Procesamiento de Aprendizaje Automático**. Utiliza el algoritmo no supervisado **K-Means** para agrupar las jurisdicciones de Argentina según la cantidad de viviendas particulares habitadas (Censo 2022 - INDEC).

## 🚀 Flujo de Trabajo
1. **Datos:** Carga de datos de viviendas por jurisdicción en Pandas.
2. **Clustering:** Aplicación de `KMeans` con 3 clusters.
3. **Etiquetado:** Clasificación automática de los grupos en:
   * 🔴 Pocas viviendas
   * 🔵 Cantidad normal de viviendas
   * 🟢 Muchas viviendas
4. **Visualización:** Gráfico de dispersión con `matplotlib` marcando las provincias y sus centroides.

## 🛠️ Tecnologías
* Python • Pandas • Scikit-Learn • Matplotlib
