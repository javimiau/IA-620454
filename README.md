# 620454 - Inteligencia Artificial

Este repositorio contiene el desarrollo de las evaluaciones de la asignatura Inteligencia Artificial, carrera de Ingeniería Civil en Informática, Universidad del Bío-Bío. 

Evaluación 1: El proyecto se enfoca en el pre-procesamiento y limpieza de datos para la plataforma de streaming "StreamFlow".

Evaluación 2: Construcción y comparación de modelos de regresión para predecir ventas semanales en una cadena de tiendas retail.

Evaluación 3: Desarrollo de un modelo de clasificación binaria optimizado mediante `GridSearchCV` para la detección de fraudes financieros en la Fintech "PaySecure", incluyendo un análisis de impacto de negocio según la variación de umbrales (thresholds).

Evaluación 4: Desarrollo de modelos de aprendizaje no supervisado utilizando K-Means para segmentar clientes desde múltiples perspectivas de negocio (Ciclo de Vida/Adopción Digital y Sensibilidad al Precio/Descuentos), optimizando el número de clústeres mediante el Método del Codo y Silhouette Score.

## Integrantes
* **Bastián Cid** - bastian.cid2201@alumnos.ubiobio.cl
* **Javiera Carrasco** - javiera.carrasco2201@alumnos.ubiobio.cl

## Estructura del Proyecto
El repositorio sigue una arquitectura estándar para proyectos de ciencia de datos:

```text
├── data/
│   ├── ingestion/    # Dataset original (StreamFlow Raw Data)
│   └── cleaned/      # Dataset procesado tras el Pipeline de limpieza
├── notebooks/        # Jupyter Notebook (.ipynb) con el código de desarrollo
└── README.md         # Documentación del proyecto