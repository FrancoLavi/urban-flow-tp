
A lo largo del análisis del dataset de infracciones por exceso de velocidad,
se pudo observar que los datos originales presentaban varios problemas de
calidad, como formatos inconsistentes, valores faltantes y registros
erróneos en campos importantes como fecha, hora, ubicación y patente.

Durante el proceso de limpieza, se normalizaron estos datos para poder
trabajar de manera más confiable. Sin embargo, se detectó que una gran
cantidad de registros tenían valores inválidos, los cuales fueron
reemplazados por valores por defecto (como la fecha 1932-01-01 y la hora
00:00). Esto permitió mantener los datos, pero también generó ciertos
sesgos que se reflejan en algunos análisis, como el alto porcentaje de
infracciones en esas fechas y horarios.

En cuanto al análisis, se pudieron identificar algunas tendencias, como
las patentes más reincidentes y la distribución de infracciones a lo largo
del tiempo. También se observó que los excesos de velocidad varían bastante
entre registros, aunque en general se mantienen dentro de un rango lógico
luego de eliminar los valores extremos.

En conclusión, el dataset permitió obtener información relevante sobre las
infracciones, pero también dejó en evidencia la importancia de realizar un
buen proceso de limpieza y validación de datos antes de analizarlos, ya que
los errores en los datos pueden influir directamente en los resultados.
