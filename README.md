🏎️ Análisis del Rendimiento de Equipos de F1 (Power BI)

📌 Descripción

Este proyecto consiste en el desarrollo de un dashboard interactivo en Power BI para analizar el rendimiento de las escuderías de Fórmula 1 durante las temporadas 2023, 2024 y 2025.

El análisis se centra en evaluar el desempeño de los equipos desde distintas perspectivas: resultados en carrera, consistencia y eficiencia estratégica.

🔄 Pipeline del proyecto

El proyecto sigue un enfoque end-to-end dividido en tres fases:

1️⃣ Extracción de datos (API)

Notebook: conexionAPIF1.ipynb

Obtención de datos desde una API de Fórmula 1

Recopilación de información de carreras, equipos y resultados

2️⃣ Limpieza y transformación de datos

Notebook: limpiezaDatosCsv.ipynb

Tratamiento de valores nulos

Estandarización de datos

Preparación del dataset para análisis

3️⃣ Visualización y análisis

Herramienta: Power BI

Creación de dashboard interactivo

Definición de KPIs y métricas clave

🎯 Objetivos

Analizar el rendimiento global de cada escudería

Comparar equipos entre distintas temporadas

Identificar métricas clave como victorias, podios y abandonos

Evaluar la eficiencia mediante pit stops y ritmo de carrera

🗂️ Modelo de datos

Se ha utilizado un modelo tipo estrella, compuesto por:

Tablas de dimensiones: equipos, pilotos, circuitos

Tablas de hechos: resultados, vueltas, pit stops y campeonato

📊 Características del dashboard

Métricas de rendimiento por equipo (puntos, victorias, podios, abandonos)

Análisis de estrategia y degradación (pit stops y ritmo)

KPIs técnicos por escudería

Filtros interactivos por temporada y equipo

⚙️ Herramientas utilizadas

Power BI

DAX

Modelado de datos

Visualización de datos

🔍 Conclusiones

El análisis muestra diferencias claras entre los equipos líderes y el resto, destacando la importancia de:

La estrategia

La fiabilidad

La consistencia en carrera
