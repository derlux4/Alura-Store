# Análisis Estratégico de Performance: Red de Tiendas Retail

## Tabla de contenido
1. [Objetivos del proyecto](#objetivos-del-proyecto)
2. [Habilidades y herramientas](#habilidades-y-herramientas)
3. [Gestión del proyecto con Trello](#gestión-del-proyecto-con-trello)
4. [Estructura del proyecto](#estructura-del-proyecto)
5. [Visualizaciones destacadas](#visualizaciones-destacadas)
6. [Principales Insights](#principales-insights)
7. [Recomendación final](#recomendación-final)
8. [Contacto](#contacto)

---

## Objetivos del proyecto
El objetivo principal de este análisis es evaluar el desempeño operativo y financiero de cuatro sucursales para proporcionar una recomendación basada en datos sobre la venta de uno de los activos de la red. Se han analizado los siguientes **KPIs**:
* **Ingresos Totales**: Evaluación del volumen de ventas monetarias por tienda.
* **Satisfacción del Cliente**: Análisis de la valoración promedio (escala 1-5).
* **Eficiencia Logística**: Análisis del costo de envío promedio por transacción.
* **Rotación de Inventario**: Identificación de productos estrella vs. productos rezagados.

## Habilidades y herramientas
* **Lenguajes**: Python 3.
* **Análisis de datos**: `pandas`, `numpy`.
* **Visualización**: `matplotlib`, `seaborn`.
* **Entorno**: Google Colab.
* **Metodología**: EDA (Análisis Exploratorio de Datos), limpieza de datos y toma de decisiones estratégica.

## Gestión del proyecto con Trello
El flujo de trabajo se gestionó mediante un tablero de Trello para garantizar el cumplimiento de los tiempos y objetivos. El ciclo incluyó:
* **Backlog**: Definición de métricas a analizar.
* **In Progress**: Carga, limpieza y normalización de los datasets.
* **Testing**: Validación de KPIs y generación de gráficos.
* **Done**: Síntesis del informe final.

## Estructura del proyecto
```text
/
├── data/               # Datasets originales (.csv)
├── notebooks/          # Notebook de trabajo en Google Colab
├── visualizations/     # Gráficos obtenidos del análisis
├── requirements.txt    # Librerías necesarias
└── README.md           # Documentación del proyecto
