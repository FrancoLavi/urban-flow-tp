## Día 1 - Inicialización del proyecto
- Creación del repositorio en GitHub
- Configuración inicial del entorno de trabajo en Google Colab
- Agregado de los integrantes del grupo en el notebook
- Invitación y configuración de colaboradores en el repositorio
- Verificación del funcionamiento del control de versiones
- Realizacion de ejercicios 1 y 2
  
## Día 2 - Limpieza y normalización del dataset
- Normalización de fechas al formato YYYY-MM-DD
- Tratamiento de fechas inválidas asignando valor por defecto (1932-01-01)
- Normalización de horas al formato 24hs
- Tratamiento de horas inválidas asignando 00:00
- Limpieza y estandarización de ubicaciones (eliminación de caracteres especiales y conversión a mayúsculas)
- Limpieza y normalización de patentes (eliminación de caracteres especiales, conversión a mayúsculas y manejo de valores inválidos con pd.NA)
- Eliminación de registros con valores nulos en columnas relevantes
- Detección y eliminación de outliers en variables de velocidad
- Creación de la columna exceso_velocidad_real
- Creación de la columna exceso_velocidad
- Eliminación de registros sin infracción
- Generación del dataset limpio y almacenamiento en la carpeta interim

## Día 3 - Análisis y visualización de datos
- Implementación de la clase FineAnalyzer para encapsular el DataFrame limpio
- Desarrollo de métodos para análisis de multas:
  - Ranking de patentes más multadas
  - Ranking de horarios con mayor cantidad de infracciones
  - Cálculo del exceso promedio de velocidad
  - Cálculo del exceso real promedio de velocidad
  - Conteo de multas por ubicación
- Creación de instancia de la clase y ejecución de cada método en celdas separadas

- Generación de visualizaciones:
  - Gráfico de barras del ranking de las 10 patentes más reincidentes
  - Gráfico de torta del porcentaje de infracciones por hora (agrupadas correctamente)
  - Gráfico de barras horizontal de infracciones por mes (excluyendo fechas inválidas)
  - Gráfico de líneas del exceso promedio de velocidad por hora (agrupado por hora)
  - Gráfico de líneas del exceso promedio de velocidad por fecha (filtrado y suavizado)

- Exportación de todos los gráficos en la carpeta urban_flow/data/interim/plots

## Día 4 - Interpretación y conclusiones
- Análisis de los resultados obtenidos a partir de los gráficos
- Identificación de patrones en las infracciones (patentes reincidentes, horarios y distribución temporal)
- Detección de sesgos en los datos debido a valores imputados (1932-01-01 y 00:00)
- Evaluación de la calidad de los datos originales y su impacto en el análisis
- Redacción de la conclusión final del dataset
- Incorporación de la conclusión en el archivo README.md
