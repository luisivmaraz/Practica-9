# Práctica 9: Sistema de Recomendación de Netflix

## Descripción General

En esta práctica, el estudiante explora el funcionamiento de un sistema de recomendación utilizando un dataset de películas y series de Netflix. El objetivo es analizar y comprender las librerías, algoritmos y procedimientos empleados para elaborar recomendaciones de contenido mediante técnicas de machine learning.

## Actividades Realizadas

1. **Revisión de recursos**  
    Se revisó el recurso de Kaggle: [Netflix Recommendation System](https://www.kaggle.com/code/mirajshah07/netflix-recommendation-system).

2. **Conceptos teóricos**  
    Se respondieron preguntas clave sobre sistemas de recomendación, actores involucrados, entidades de datos requeridas y el tipo de sistema implementado.

3. **Importación de librerías**  
    Se importaron librerías esenciales como `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`, entre otras.

4. **Carga y exploración del dataset**  
    Se descargó y cargó localmente el dataset de Netflix, explorando su naturaleza y atributos principales.

5. **Análisis exploratorio de datos**  
    - Conteo de series, películas y títulos totales.
    - Identificación de atributos clave.
    - Gráficas de barras y mapas de calor para visualizar la distribución de títulos, fechas de lanzamiento y clasificación de contenido.
    - Análisis por país y año de liberación.

6. **Integración de ratings**  
    Se creó un nuevo dataset combinando títulos y ratings desde IMDB, permitiendo identificar las 10 series/películas mejor evaluadas y visualizarlas mediante un gráfico de pastel anidado.

7. **Análisis específico de películas y series**  
    - Gráficos de totales por país y duración de películas.
    - Conteo de temporadas para las series más largas.

8. **Construcción del sistema de recomendación basado en contenido**  
    - Uso de `TfidfVectorizer` para procesar descripciones.
    - Limpieza de datos y construcción de la matriz de frecuencias.
    - Cálculo de matriz de similaridad y creación de un mapa reverso de índices.
    - Implementación y pruebas de la función de recomendación con títulos específicos.

## Archivos Incluidos

- `Practica-09.ipynb`: Notebook principal con todo el desarrollo.
- Dataset de Netflix (2021) y dataset de ratings IMDB.
- Otros dataset de la practica

---
Práctica realizada como parte del curso de sistemas de recomendación, utilizando recursos de Kaggle y datasets públicos.

