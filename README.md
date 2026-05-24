# Urban Flow - Análisis de Multas por Exceso de Velocidad

## Sprint actual: Sprint 2 - Procesamiento visual y reconocimiento de patentes

---

# Objetivo

El objetivo de este proyecto es trabajar sobre un dataset de infracciones por exceso de velocidad, realizando tareas de carga, limpieza, normalización, análisis y procesamiento visual de datos.

Durante los distintos sprints se busca obtener un dataset consistente y confiable que permita generar métricas relevantes, detectar patrones y visualizar información útil para la toma de decisiones.

En el Sprint 2 se incorpora además el procesamiento de imágenes y la extracción automática de patentes mediante OCR.

---

# Introducción y contexto

En este trabajo práctico se analiza un conjunto de datos que contiene registros de infracciones de tránsito por exceso de velocidad.

A lo largo del proyecto se desarrollan distintas etapas del flujo de trabajo de análisis de datos y procesamiento visual, incluyendo:

- Inicialización del proyecto y control de versiones con GitHub.
- Organización de carpetas y estructura de trabajo.
- Limpieza y normalización del dataset.
- Tratamiento de fechas, horarios, ubicaciones y patentes.
- Eliminación de datos inválidos y outliers.
- Generación de nuevas variables de análisis.
- Implementación de clases para encapsular la lógica de análisis.
- Creación de gráficos y visualizaciones.
- Procesamiento de imágenes.
- Extracción automática de patentes mediante OCR.
- Relación entre imágenes y registros del dataset utilizando métricas de similitud.

El enfoque principal del proyecto es aplicar buenas prácticas de programación, análisis de datos y visión por computadora para preparar información consistente y facilitar futuros análisis.

---

# Funcionalidades implementadas

## Sprint 1
- Limpieza y normalización de datos.
- Tratamiento de valores nulos e inconsistentes.
- Eliminación de outliers.
- Generación de métricas.
- Visualización de datos mediante gráficos.
- Implementación de la clase `FineAnalyzer`.

## Sprint 2
- Procesamiento de imágenes de infracciones.
- Extracción de patentes mediante OCR.
- Comparación de similitud entre patentes detectadas y originales.
- Asociación de imágenes con registros del dataset.
- Generación del dataset `speeding_fines_image.csv`.

---
---

# Cómo ejecutar

1. Abrir el archivo `.ipynb` en Google Colab.
2. Ejecutar todas las celdas (`Ctrl + F9`).
3. Verificar la generación de datasets y gráficos.
4. Los resultados se almacenarán en:

```text
urban_flow/data/interim/
urban_flow/data/processed/
```

---

# Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- OpenCV
- OCR
- Google Colab
- Git y GitHub
---
