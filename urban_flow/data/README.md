
# Conclusión

A lo largo del análisis del dataset de infracciones por exceso de velocidad, se pudo observar que los datos originales presentaban distintos problemas de calidad, como formatos inconsistentes, valores faltantes y registros erróneos en campos importantes como fecha, hora, ubicación y patente.

Durante el proceso de limpieza y normalización, estos datos fueron corregidos para poder trabajar de manera más confiable. En algunos casos, los valores inválidos fueron reemplazados por valores por defecto, lo que permitió conservar los registros, aunque también generó ciertos sesgos visibles en algunos análisis.

Además del análisis de datos, en este trabajo práctico se integró información visual mediante el uso de OCR con EasyOCR para extraer patentes desde imágenes de vehículos. Luego, estas patentes fueron comparadas con las registradas en el dataset utilizando un criterio de coincidencia de caracteres de izquierda a derecha con un porcentaje mínimo del 80%.

Los resultados obtenidos permitieron relacionar correctamente una gran cantidad de imágenes con infracciones reales, aunque también se detectaron limitaciones propias del OCR, como errores provocados por imágenes borrosas, mala iluminación, ángulos de captura o textos incompletos.

Finalmente, el trabajo permitió obtener métricas relevantes sobre multas con y sin imágenes, imágenes sin coincidencias y multas pendientes de pago, integrando procesamiento de datos e información visual en un mismo flujo de análisis.
# Conclusión

A lo largo de este trabajo práctico se integraron distintas herramientas y conceptos fundamentales vinculados al manejo y almacenamiento de datos.
En primer lugar, se incorporó DVC como herramienta de versionado de datos, permitiendo gestionar archivos binarios de manera independiente al repositorio Git. Esto facilitó la administración de imágenes y otros recursos de gran tamaño, manteniendo el control de versiones del proyecto de forma ordenada.
Posteriormente, se diseñó un modelo lógico y un modelo relacional para representar las infracciones de tránsito, los vehículos involucrados, los radares utilizados y las evidencias asociadas. A partir de este diseño se implementó una base de datos relacional utilizando SQLAlchemy, permitiendo almacenar y consultar la información de manera estructurada.
Una vez poblada la base de datos, se desarrollaron diversas consultas que permitieron identificar vehículos reincidentes, radares con mayor actividad, multas sin evidencia visual y estadísticas generales sobre las infracciones registradas. Estas consultas demostraron el valor de organizar la información mediante un modelo relacional adecuado.
Finalmente, se incorporó una base de datos vectorial utilizando ChromaDB y OpenCLIP. Mediante la generación de embeddings de imágenes fue posible relacionar información visual con los registros almacenados en la base de datos relacional. Esto permitió implementar un mecanismo de búsqueda por similitud capaz de recuperar información de un vehículo a partir de una imagen, integrando conceptos de visión artificial, búsqueda semántica y bases de datos vectoriales.
En conjunto, el trabajo permitió recorrer un flujo completo de gestión de datos que incluyó versionado, modelado, persistencia, consulta y recuperación de información tanto estructurada como visual, aplicando tecnologías modernas utilizadas actualmente en proyectos de ciencia de datos e inteligencia artificial.
# Conclusión

A lo largo de este trabajo práctico se integraron distintas herramientas y conceptos fundamentales vinculados al manejo y almacenamiento de datos.
En primer lugar, se incorporó DVC como herramienta de versionado de datos, permitiendo gestionar archivos binarios de manera independiente al repositorio Git. Esto facilitó la administración de imágenes y otros recursos de gran tamaño, manteniendo el control de versiones del proyecto de forma ordenada.
Posteriormente, se diseñó un modelo lógico y un modelo relacional para representar las infracciones de tránsito, los vehículos involucrados, los radares utilizados y las evidencias asociadas. A partir de este diseño se implementó una base de datos relacional utilizando SQLAlchemy, permitiendo almacenar y consultar la información de manera estructurada.
Una vez poblada la base de datos, se desarrollaron diversas consultas que permitieron identificar vehículos reincidentes, radares con mayor actividad, multas sin evidencia visual y estadísticas generales sobre las infracciones registradas. Estas consultas demostraron el valor de organizar la información mediante un modelo relacional adecuado.
Finalmente, se incorporó una base de datos vectorial utilizando ChromaDB y OpenCLIP. Mediante la generación de embeddings de imágenes fue posible relacionar información visual con los registros almacenados en la base de datos relacional. Esto permitió implementar un mecanismo de búsqueda por similitud capaz de recuperar información de un vehículo a partir de una imagen, integrando conceptos de visión artificial, búsqueda semántica y bases de datos vectoriales.
En conjunto, el trabajo permitió recorrer un flujo completo de gestión de datos que incluyó versionado, modelado, persistencia, consulta y recuperación de información tanto estructurada como visual, aplicando tecnologías modernas utilizadas actualmente en proyectos de ciencia de datos e inteligencia artificial.
