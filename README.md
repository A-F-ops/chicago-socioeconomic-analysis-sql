# 📊 Análisis Socioeconómico de la Ciudad de Chicago (SQL & Python)

Proyecto práctico de auditoría social y análisis estadístico utilizando datos oficiales del Censo de EE.UU. e indicadores socioeconómicos del Chicago Data Portal, procesados mediante consultas SQL integradas en entornos de Python (Jupyter Notebooks).

## 🎯 Hallazgos Clave de Negocio

*   **Volumen de Datos Auditados:** Análisis completo sobre las 78 áreas comunitarias de la ciudad.
*   **Índice de Vulnerabilidad (Hardship Index):** Mediante consultas de agregación, se detectó de manera matemática que el **48.7% de las comunas** (38 áreas) presentan un índice crítico superior a 50.0.
*   **Brecha Socioeconómica Extrema:** El análisis identificó a **Riverdale** como la zona de mayor vulnerabilidad de la ciudad (Índice de dificultad: 98.0), contraponiéndose con **Lake View**, el polo de mayores ingresos per cápita del reporte.
*   **Análisis de Correlación Gráfica:** Utilizando las librerías `seaborn` y `matplotlib`, se generó un gráfico de dispersión (*jointplot*) que demuestra una **correlación negativa robusta**: a medida que el ingreso per cápita se incrementa, el índice de vulnerabilidad socioeconómica disminuye drásticamente siguiendo una tendencia curva predictiva.

## 🛠️ Tecnologías Aplicadas
*   **SQL (Magics `%sql`):** Consultas avanzadas de filtrado (`WHERE`, `HAVING`), funciones de agregación (`COUNT`, `MAX`) y ordenamiento jerárquico.
*   **Python (Pandas):** Conversión de estructuras nativas de bases de datos a DataFrames relacionales.
*   **Visualización de Datos:** Modelado gráfico con Seaborn y Matplotlib.
---
## 🎓 Certificación y Créditos
Este proyecto fue desarrollado como parte del laboratorio práctico oficial para el **Certificado Profesional de Ciencia de Datos de IBM**, validando el dominio en la integración de entornos híbridos de bases de datos relacionales y programación científica.
