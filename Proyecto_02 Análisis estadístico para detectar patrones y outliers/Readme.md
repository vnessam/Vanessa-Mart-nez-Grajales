📊 Proyecto 2 — Análisis de una Empresa de Telecomunicaciones (ConnectaTel)
🧠 Objetivo del Proyecto
El objetivo de este proyecto es analizar el comportamiento real de uso de los clientes de ConnectaTel, una empresa de telecomunicaciones con operaciones en México y Colombia, para identificar patrones de consumo, segmentos de clientes y oportunidades de mejora en la oferta de planes.

El análisis busca responder preguntas clave del negocio relacionadas con:

Uso de llamadas y mensajes
Segmentación por edad y nivel de consumo
Identificación de comportamientos atípicos (outliers)
Generación de insights accionables para optimizar la oferta comercial
📁 Datasets Utilizados
El análisis se basa en tres fuentes de datos:

plans.csv
Información de los planes disponibles: precio, minutos incluidos, GB incluidos y costos adicionales.

users_latam.csv
Datos demográficos de los clientes: edad, ciudad, país, fecha de registro, plan contratado y churn.

usage.csv
Uso real del servicio por usuario: llamadas realizadas, duración de llamadas y cantidad de mensajes.

Estos datasets fueron integrados para construir un perfil completo de cada usuario.

🔄 Etapas del Análisis
El proyecto sigue un flujo estructurado de análisis de datos:

Carga y exploración de datos
Revisión de estructura, tipos de datos y primeras estadísticas descriptivas.

Identificación de problemas de calidad
Detección de valores nulos, formatos incorrectos y registros inconsistentes.

Limpieza y preparación de datos
Conversión de tipos de datos, tratamiento de valores faltantes y agregación a nivel usuario.

Análisis descriptivo
Cálculo de estadísticas resumen para entender el comportamiento típico y extremo.

Visualización y detección de outliers
Uso de histogramas, boxplots y método IQR para identificar valores atípicos.

Segmentación de clientes

Segmentación por nivel de uso (Bajo, Medio, Alto)
Segmentación por edad (Joven, Adulto, Adulto Mayor)
Insights ejecutivos
Interpretación de resultados y recomendaciones comerciales basadas en los datos.

📌 Principales Hallazgos
Existen diferencias claras en el uso del servicio según la edad y el nivel de consumo.
Los outliers identificados representan usuarios intensivos reales, no errores de datos.
Los clientes de alto uso constituyen un segmento clave para estrategias de upselling y planes premium.
La segmentación permite diseñar ofertas más ajustadas a las necesidades reales de los usuarios.
🛠️ Herramientas Utilizadas
Python
Jupyter Notebook / Google Colab
pandas, numpy
matplotlib, seaborn
GitHub para control de versiones
📈 Este repositorio presenta un análisis reproducible y orientado a negocio, enfocado en transformar datos en decisiones accionables.
