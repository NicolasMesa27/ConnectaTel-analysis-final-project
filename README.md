# Proyecto – Análisis para ConnectaTel

## Objetivo
Analizar el comportamiento de uso de los clientes de ConnectaTel para identificar
segmentos de clientes, detectar patrones de consumo y generar recomendaciones
accionables orientadas a mejorar la oferta de planes.

## Datasets utilizados
- `users` – Información demográfica de 4,000 usuarios (edad, ciudad, plan, fecha de registro).
- `usage` – 40,000 registros de actividad (llamadas y mensajes) por usuario.
- `plans` – Descripción de los planes disponibles (Básico y Premium).

## Etapas del análisis
1. **Carga y exploración inicial** – Revisión de estructura, tipos de datos y estadísticas descriptivas.
2. **Identificación de problemas de calidad** – Detección de valores sentinela, nulos y fechas imposibles.
3. **Limpieza de datos** – Reemplazo de sentinelas por NaN, conversión de fechas y validación de rangos.
4. **Construcción del perfil de usuario** – Agregación de métricas de uso por usuario y merge con datos demográficos.
5. **Análisis estadístico** – Resumen descriptivo, distribución por plan y detección de outliers con método IQR.
6. **Visualización** – Histogramas y countplots segmentados por plan, grupo de edad y nivel de uso.
7. **Insight ejecutivo** – Conclusiones y recomendaciones para stakeholders.

## Cómo ejecutar el notebook

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NicolasMesa27/ConnectaTel-analysis-final-project/blob/main/S7%20Version-Estudiante-Project-ConnectaTel.ipynb)

1. Haz clic en el badge para abrir el notebook directamente en Google Colab.
2. Ve a **Runtime → Run All** para ejecutar todas las celdas.

## Herramientas utilizadas
- Python 3
- pandas, numpy
- matplotlib, seaborn
- Jupyter Notebook / Google Colab
