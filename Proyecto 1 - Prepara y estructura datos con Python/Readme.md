Proyecto 01 - Análisis Exploratorio de Datos - Movilidad urbana y productividad económica en ciudades de LATAM
Este proyecto simula un caso real de análisis de datos para el Latin American Development Bank, cuyo objetivo es entender cómo la movilidad urbana se relaciona con la productividad económica en las principales ciudades de América Latina.

La motivación principal es identificar qué ciudades presentan altos niveles de congestión junto con bajo desempeño económico, y cuáles combinan movilidad eficiente con economías más sólidas, con el fin de apoyar decisiones de inversión en infraestructura de transporte.

Para ello, se integraron datos de tráfico urbano en tiempo real provenientes de TomTom Traffic Index con indicadores económicos urbanos de la OECD.

🎯 Objetivo
Construir un dataset unificado y limpio para el año 2024 que combine variables de movilidad urbana y economía, y realizar un análisis exploratorio que permita:

Identificar ciudades con alta congestión y baja productividad.

Detectar ciudades con mejores indicadores combinados.

Explorar relaciones entre tráfico, tiempos de viaje y variables económicas.

Generar una base lista para futuros análisis o visualizaciones avanzadas.

⚙️ Metodología
El flujo de trabajo incluyó:

Carga y exploración inicial de ambos datasets.

Limpieza de datos y corrección de tipos.

Normalización de nombres de ciudades y países.

Extracción del año desde timestamps y filtrado al período 2024.

Agregación de métricas de tráfico por ciudad.

Unión de datos de movilidad con indicadores económicos.

Análisis exploratorio mediante visualizaciones.

Exportación del dataset final listo para análisis.

El resultado es una tabla consolidada con una fila por ciudad para 2024.

Herramientas utilizadas
Python Jupyter Notebook Pandas Numpy Matplotlib Seaborn

📈 Resultados principales
Se construyó un dataset final unificado por ciudad que integra congestión, tiempos de viaje, PIB per cápita, desempleo y población.

Se identificaron diferencias claras entre ciudades con alta congestión y menor productividad frente a aquellas con movilidad más eficiente y economías más fuertes.

Las visualizaciones permiten observar posibles relaciones entre retrasos promedio, índices de tráfico y desempeño económico.

El proyecto genera una base cuantitativa para priorizar inversiones en transporte urbano orientadas a mejorar la productividad y el bienestar ciudadano.
