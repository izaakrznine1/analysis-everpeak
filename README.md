# Contexto y Objetivo
El objetivo de este análisis fue estudiar la relación entre la movilidad urbana y la productividad económica en distintas ciudades de América Latina durante 2024. Para ello, se integraron datos de tráfico urbano provenientes de TomTom con indicadores económicos de la OCDE, incluyendo PIB per cápita, desempleo, contaminación y población

# Cobertura de datos:
El análisis se enfocó en el año 2024 y utilizó información agregada a nivel ciudad. Se combinaron indicadores de congestión vehicular, retrasos de viaje y tiempos promedio de traslado con variables económicas y demográficas. La integración permitió construir una base consolidada para comparar desempeño económico y movilidad urbana.

# Metodología (alto nivel):
Se realizó un proceso de limpieza y transformación de datos que incluyó la conversión de fechas, corrección de formatos numéricos, estandarización de nombres de columnas y creación de variables derivadas. Posteriormente, los datos de tráfico fueron agregados por ciudad y año, y se utilizó una unión tipo INNER JOIN para integrar la información económica y de movilidad. Finalmente, se generaron visualizaciones para analizar distribuciones y posibles relaciones entre las variables.

# Hallazgos iniciales:

Los resultados muestran que no existe una relación directa y uniforme entre el PIB per cápita y los niveles de congestión vehicular. Algunas ciudades con altos niveles de ingreso presentan también altos niveles de tráfico, mientras que otras mantienen niveles moderados de congestión. Se identificó a Ciudad de México como una de las ciudades con mayores niveles promedio de retraso por congestión, evidenciando la importancia de considerar factores adicionales como infraestructura urbana, densidad poblacional y planeación del transporte.

# Recomendaciones:
Con base en el análisis exploratorio realizado, no se identificó una correlación fuerte y directa entre el PIB per cápita y la congestión vehicular. Sin embargo, ciudades como Bogotá y Ciudad de México presentan niveles elevados de congestión que justifican un análisis más profundo para evaluar posibles inversiones en infraestructura de transporte. Se recomienda ampliar este estudio incorporando variables relacionadas con la infraestructura de transporte público, el crecimiento urbano y la distribución poblacional, así como complementar el análisis con indicadores adicionales que permitan una evaluación más integral. Asimismo, las ciudades con altos niveles de congestión y un desempeño económico moderado podrían considerarse candidatas prioritarias para futuras inversiones en movilidad urbana, dado que el fortalecimiento de la infraestructura de transporte puede contribuir a mejorar la productividad y la calidad de vida de la población.
