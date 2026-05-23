
# Conclusión

A lo largo del análisis del dataset de infracciones por exceso de velocidad, se pudo observar que los datos originales presentaban distintos problemas de calidad, como formatos inconsistentes, valores faltantes y registros erróneos en campos importantes como fecha, hora, ubicación y patente.

Durante el proceso de limpieza y normalización, estos datos fueron corregidos para poder trabajar de manera más confiable. En algunos casos, los valores inválidos fueron reemplazados por valores por defecto, lo que permitió conservar los registros, aunque también generó ciertos sesgos visibles en algunos análisis.

Además del análisis de datos, en este trabajo práctico se integró información visual mediante el uso de OCR con EasyOCR para extraer patentes desde imágenes de vehículos. Luego, estas patentes fueron comparadas con las registradas en el dataset utilizando un criterio de coincidencia de caracteres de izquierda a derecha con un porcentaje mínimo del 80%.

Los resultados obtenidos permitieron relacionar correctamente una gran cantidad de imágenes con infracciones reales, aunque también se detectaron limitaciones propias del OCR, como errores provocados por imágenes borrosas, mala iluminación, ángulos de captura o textos incompletos.

Finalmente, el trabajo permitió obtener métricas relevantes sobre multas con y sin imágenes, imágenes sin coincidencias y multas pendientes de pago, integrando procesamiento de datos e información visual en un mismo flujo de análisis.
