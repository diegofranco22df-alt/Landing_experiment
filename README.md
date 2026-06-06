Landing experiment
Validando hipótesis de negocio con pruebas estadísticas

Este repositorio contiene el análisis realizado a un experimento A/B en la página de inicio (landing page), comparando
dos versiones (A y B) con el objetivo de mejorar la tasa de conversión y el valor económico por usuario.

🧠 Objetivo del análisis
La empresa necesita una decisión basada en datos para definir qué versión implementar, considerando la tasa de conversión, el gasto promedio y el comportamiento por canal de tráfico y tipo de usuario.


El proyecto incluye 3 datasets:

plans.csv → información de los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra)
users.csv → información de los clientes (edad, ciudad, fecha de registro, plan, churn)
usage.csv → detalle del uso real de los servicios (llamadas y mensajes)
📂 Contenido del repositorio
S7 Version-Estudiante-Project-ConnectaTel.ipynb → Notebook principal con limpieza, EDA, distribuciones, outliers y conclusiones.
▶ Cómo abrir el notebook en Google Colab
Haz clic en el siguiente botón:

Open In Colab

O:

Abre el archivo .ipynb en GitHub
Haz clic en Open in Colab
📘 Cómo reproducir el análisis
Abre S7_Version_Estudiante_Project_ConnectaTel.ipynb
Ejecuta las celdas en orden
El notebook carga automáticamente el dataset desde /data/ o desde un enlace público (según corresponda)
Etapas de análisis realizadas
Exploración de la estructura de los datasets.
Revisión de valores nulos.
Detección de valores inválidos y sentinels.
Revisión y estandarización de fechas.
Limpieza básica de datos.
Summary statistics de uso por usuario.
Visualización de distribuciones (uso y clientes) y outliers.
Segmentación de Clientes.
Insight Ejecutivo para Stakeholders.
