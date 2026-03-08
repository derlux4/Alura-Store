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


Visualizaciones destacadas
Distribución de Ventas: Análisis de volumen por categoría, donde Muebles y Electrónicos destacan como los pilares de ingresos.
Valoración del Cliente: Comparativa de satisfacción, mostrando una estandarización sólida del servicio en todas las sucursales.
Eficiencia Logística: Gráfico de costos de envío que identifica las brechas operativas entre las tiendas.

Principales Insights
Dominio de Inventario: Los Muebles lideran el volumen de ventas en la red.
Eficiencia en Tienda 4: Es la sucursal con el envío más económico, logrando un ahorro operativo frente a la Tienda 1.
Consistencia de Servicio: La variación en la satisfacción del cliente entre la tienda mejor y peor valorada es mínima (aprox. 0.07 pts).

##Recomendación final
Tras el análisis, se recomienda la venta de la Tienda 1.
Aunque factura el mayor volumen bruto, presenta ineficiencias logísticas críticas (costo de envío promedio de $26,018.61) y la calificación de satisfacción más baja de la red (3.98). Vender este activo permite capitalizar su alto valor comercial mientras se concentra la gestión en tiendas con márgenes logísticos más sanos.

Contacto
👤 Nombre: Luis Rodriguez
📧 Correo: ljrodrigueze@gmail.com
