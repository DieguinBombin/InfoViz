---
layout: default
title: Inicio
---

# Análisis de Letalidad: Top 9 Hospitales vs. Cronología Temporal

Este gráfico representa la evolución de la tasa de **letalidad** en los 10 centros hospitalarios con los índices más altos del dataset, permitiendo observar la consistencia de este indicador a lo largo del tiempo.


### Visualización de Resultados

A continuación se presenta el gráfico que correlaciona a los 9 hospitales con mayores índices de letalidad frente a la línea de tiempo del estudio:

![Top 10 Hospitales Letalidad vs Cronología](graph.png)


## **Detalles de la Visualización**
* **Eje X (Cronología):** Muestra la evolución temporal de los registros.
* **Eje Y (Tasa de Letalidad):** Representa el porcentaje de egresos fallecidos en relación al total de egresos.
* **Representación Visual:** Se utiliza una combinación de **gráficos de líneas** para seguir la tendencia y para la clasificación de cada una, se optó por colores clasificando su **hospital correspondiente**.

## **Hallazgos**
1.  **Centros de Alta Complejidad:** El gráfico identifica que centros como el **Hospital Metropolitano** y el **HUAP** lideran la tasa de letalidad, lo cual es consistente con su rol como centros de derivación para pacientes en estado crítico.
2.  **Variabilidad y Outliers:** Se observan picos pronunciados que alcanzan el **50% de letalidad** en ciertos periodos. Técnicamente, esto sugiere muestras pequeñas (pocos egresos en ese mes) o una alta concentración de pacientes críticos durante contingencias sanitarias.
3.  **Comparativa de Estabilidad:** A diferencia de otros indicadores, la letalidad en este "Top 9" no es uniforme; muestra una dispersión relativamente alta, lo que indica que la mortalidad hospitalaria está fuertemente ligada a eventos temporales específicos y no solo a la gestión estructural del centro.

> **Nota técnica:** Para la construcción de este gráfico se filtraron los establecimientos con datos inconsistentes y se calcularon promedios móviles para suavizar las tendencias donde la dispersión era excesiva. Además se espera implementación en HTML en el próximo avance...
