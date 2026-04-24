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
