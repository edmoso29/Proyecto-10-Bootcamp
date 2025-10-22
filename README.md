# Proyecto-10-Bootcamp

•	Objetivo general: Priorización de Hipótesis y Análisis de Pruebas A/B para una Tienda Online

•	Librerías importadas: pandas, numpy, matplotlib.pyplot, seaborn, scipy.stats y/o statsmodels (posible uso de sklearn para modelado), además de utilidades de fecha/hora.

•	Carga de datos: lectura de uno o más CSV/TSV (ruta relativa/absoluta), renombrado de columnas y conversión de tipos (fechas a datetime, IDs a str).

•	Preprocesamiento:

o	Filtrado por rango de fechas y/o condiciones de negocio.

o	Limpieza de duplicados y manejo básico de nulos (dropna / fillna).

o	Creación de columnas derivadas (fechas: day/hour, flags binarios, agregados por usuario).

o	Uso de .groupby() y pivot_table para agregados por usuario/evento/grupo experimental.

•	Análisis exploratorio:

o	Conteos y tasas (eventos totales, usuarios únicos, recurrencia).

o	Visualizaciones tipo histogramas, barplots y heatmaps para distribuciones temporales y por categoría.

o	Construcción de un embudo/flow de eventos con cálculo de tasas de conversión entre etapas.

•	Pruebas estadísticas / validación:

o	Comparaciones de proporciones o test z para diferencias entre grupos (A/A o A/B), cálculo de p-values y decisión según alpha (0.05).

o	Construcción de tablas resumen con p-values por evento/medida.

•	Output y conclusiones: generación de tablas y gráficos que sintetizan hallazgos (usuarios por evento, conversion rates, resultados de tests); bloques finales con recomendaciones o conclusiones del análisis.
