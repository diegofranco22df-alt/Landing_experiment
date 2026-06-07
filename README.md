# Landing experiment
Validando hipótesis de negocio con pruebas estadísticas:

Este repositorio contiene el análisis realizado a un experimento A/B en la página de inicio (landing page), comparando
dos versiones (A y B) con el objetivo de mejorar la tasa de conversión y el valor económico por usuario.

## 🧠 Objetivo del análisis

- La empresa necesita una decisión basada en datos para definir qué versión implementar, considerando la tasa de conversión, el gasto promedio y el comportamiento por canal de tráfico y tipo de usuario.

El proyecto incluye 1 dataset:

- /datasets/landing_experiment.csv:

información de usuarios expuestos a las versiones A y B, incluyendo región, dispositivo, fuente de tráfico, tipo de usuario, conversión y gasto.

## 📂 Contenido del repositorio

- `S9 Version_Student_Proyecto_Landing_Experiment.ipynb`
→ Notebook principal con limpieza, EDA, distribuciones, outliers y conclusiones.

## ▶ Cómo abrir el notebook en Google Colab
Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/github/diegofranco22df-alt/Landing_experiment/blob/main/S9_Version_Student_Proyecto_Landing_Experiment.ipynb)

O:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

## 📘 Cómo reproducir el análisis

1. Abre `S9 Version_Student_Proyecto_Landing_Experiment.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)

## Etapas de análisis realizadas

- Cargar y validar datos.
- Comparar gasto promedio (A vs. B).
- Comparar tasa de conversión (A vs. B).
- Analizar tráfico y conversión.
- Analizar tipo de usuario y conversión.
- Visualización.
- Insight ejecutivo.
