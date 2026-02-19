# Explorando drivers de comportamiento en NovaRetail+

## 📌 Contexto
NovaRetail+ es una plataforma de comercio electrónico en Latinoamérica.
Para el cierre de 2024, el equipo de Crecimiento y Retención busca entender:

**¿Qué comportamientos del cliente están más fuertemente asociados con el ingreso anual generado?**

## 🎯 Objetivo
Desarrollar un análisis correlacional claro, responsable y accionable,
sin asumir relaciones causales, que permita identificar asociaciones relevantes
entre comportamiento del cliente, segmentación y valor económico.

## 🧪 Metodología
- Análisis exploratorio de datos (EDA)
- Análisis de correlación:
  - Pearson y Spearman para variables numéricas
  - Punto-biserial para variables binarias
- Visualización mediante heatmaps y scatterplots
- Evaluación de multicolinealidad entre variables clave

## 📁 Origen y preparación de los datos
El dataset utilizado en este proyecto corresponde a una versión **limpia y validada**,
generada a partir de datos académicos provistos por el bootcamp.

Debido a restricciones de acceso al dataset original, se incluye en este repositorio
el archivo `novaretail_analisis_2024.csv`, que representa el **dataset final utilizado
para el análisis correlacional**.

El notebook está diseñado para ejecutarse directamente sobre este dataset,
garantizando la **reproducibilidad completa del análisis** sin dependencias externas.

## 📊 Principales hallazgos
- Correlación muy fuerte entre ingreso anual y compras mensuales (r ≈ 0.97)
- Correlación moderada entre gasto publicitario y visitas (r ≈ 0.58)
- Relación débil entre visitas y compras (r ≈ 0.35)
- Variables binarias y demográficas con impacto marginal

## ⚠️ Consideraciones
- La correlación no implica causalidad
- Los resultados se interpretan con cautela metodológica

## 🛠️ Herramientas
- Python (Pandas, NumPy)
- Matplotlib, Seaborn
- Google Colab
