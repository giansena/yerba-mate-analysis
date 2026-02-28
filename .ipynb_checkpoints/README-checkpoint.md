# ENGLISH 
(versión en español más abajo)

# From the Field to Data: 50 Years of Yerba Mate Production Analyzed and Modeled with Python

This project analyzes more than five decades of historical yerba mate production data in Argentina, identifying growth patterns, structural anomalies, and production trends.
Through Exploratory Data Analysis (EDA), SQL queries, and predictive modeling using linear regression, the objective was to understand the sector’s evolution and estimate its future behavior.
The goal was not only to analyze data, but to transform historical information into actionable insights.

Yerba mate is one of the most important regional economies in northeastern Argentina. Understanding its production evolution allows us to:
* Detect structural changes in the sector.
* Identify atypical years or statistical jumps.
* Analyze the relationship between harvested area, yield, and total production.
* Generate projections that support production planning.
This analysis becomes particularly relevant when observing extraordinary events, such as the production jump between 1998 and 1999, which required additional contextual investigation to rule out a genuine productivity improvement and instead consider statistical or structural factors.


## This project was developed using:

**Languages & Environment**
* Python 3
* Jupyter Notebook
* Core Libraries
* Pandas for data manipulation and cleaning
* Matplotlib for visualization
* Scikit-learn for predictive modeling
* SQLite for SQL queries on structured data

**Applied Concepts**
* Exploratory Data Analysis (EDA)
* Data cleaning and validation
* Grouping and aggregation
* Supervised predictive modeling
* Interpretation of results within a production/business context


## Analysis Process
**Exploratory Analysis and Data Cleaning (EDA)**
The analysis began with a structural inspection of the dataset:
* Dataset dimensions (shape)
* Data types (dtypes)
* Missing values
* Duplicates
* Descriptive statistics

**Applied Treatment**
* Verified the absence of duplicate records.
* Analyzed missing values and confirmed their impact (or lack thereof).
* Identified outliers in production data (e.g., the 1998–1999 jump).
* Avoided automatic removal of outliers without contextual analysis.
* Used yearly averages to reduce departmental-level bias.
* Prioritized interpretation over automatic data filtering.


## Trend Analysis
The following were analyzed:
* Total production by year.
* Average yield per hectare.
* Relationship between harvested area and total production.
* Ranking of departments by production volume (using SQL).
This allowed the identification of:
* Sustained long-term growth.
* Periods of structural expansion.
* Changes that did not necessarily imply improvements in productive efficiency.


## Predictive Modeling

A Linear Regression model was implemented using:
* Independent variable: Year
* Target variable: Total production
The model was trained on historical data and used to generate predictions through 2030.

The objective was not to build a complex model, but to demonstrate the ability to:
* Prepare data for machine learning workflows.
* Train a supervised model.
* Generate structured predictions.
* Interpret results with business-oriented judgment.


## Results and Conclusions
**Significant Historical Growth**
Production increased by more than 1000% since 1970, reflecting territorial expansion and sector consolidation.
**Identification of Structural Anomalies**
The production jump between 1998 and 1999 was not accompanied by a proportional increase in yield, suggesting methodological changes, area expansion, or statistical restructuring.
**Direct Relationship Between Area and Production**
A strong positive correlation was confirmed between harvested area and total production, indicating that growth was primarily driven by territorial expansion rather than technological efficiency improvements.
**Stable Future Projection**
The predictive model suggests continued growth, which may be useful for strategic planning and capacity analysis.


## Professional Value of the Project
This project demonstrates the ability to:
* Work with large historical datasets.
* Perform contextual and statistically grounded analysis.
* Integrate Python and SQL within a unified workflow.
* Communicate findings in strategic, business-oriented terms.
* Transform raw data into decision-support insights.



# ESPAÑOL

# De la tierra a los datos: 50 años de producción de yerba mate analizados y modelados con Python

Este proyecto analiza más de cinco décadas de datos históricos de producción de yerba mate en Argentina, identificando patrones de crecimiento, anomalías estructurales y tendencias productivas.
A través de análisis exploratorio de datos (EDA), consultas SQL y modelado predictivo con regresión lineal, se busca comprender la evolución del sector y estimar su comportamiento futuro.
El objetivo no fue solo analizar datos, sino transformar información histórica en insights accionables.

La yerba mate es una de las economías regionales más importantes del noreste argentino. Comprender su evolución productiva permite:
* Detectar cambios estructurales en el sector.
* Identificar años atípicos o saltos estadísticos.
* Analizar la relación entre superficie cosechada, rendimiento y producción total.
* Generar proyecciones que ayuden a la planificación productiva.
Este análisis cobra especial relevancia cuando se observan eventos extraordinarios, como el salto productivo entre 1998 y 1999, que requirió investigación contextual adicional para descartar una mejora productiva real y considerar factores estadísticos o estructurales.


## Este proyecto fue desarrollado utilizando:

**Lenguajes y entorno**
* Python 3
* Jupyter Notebook

**Librerías principales**
* Pandas para Manipulación y limpieza de datos
* Matplotlib para Visualización
* Scikit-learn para Modelado predictivo
* SQLite para Consultas SQL sobre base estructurada

**Conceptos aplicados**
* Análisis Exploratorio de Datos (EDA)
* Limpieza y validación de datos
* Agrupaciones y agregaciones
* Modelado predictivo supervisado
* Interpretación de resultados en contexto productivo

## Proceso de análisis

**Exploración y Limpieza (EDA)**
El análisis comenzó con una inspección estructural del dataset:
* Revisión de dimensiones (shape)
* Tipos de datos (dtypes)
* Valores nulos
* Duplicados
* Estadísticas descriptivas

Tratamiento aplicado:
* Se verificó la inexistencia de duplicados.
* Se analizaron valores nulos y se confirmó su impacto (o ausencia).
* Se detectaron valores atípicos en la producción (ej: salto 1998–1999).
* Se evitó eliminar outliers automáticamente sin análisis contextual.
* Se trabajó con promedios por año para reducir sesgos departamentales.
* Se priorizó la interpretación antes que la eliminación automática de datos.

**Análisis de Tendencias**
Se analizaron:
* Producción total por año.
* Rendimiento promedio por hectárea.
* Relación entre superficie cosechada y producción total.
* Ranking de departamentos por volumen productivo (usando SQL).
Esto permitió detectar:
* Crecimiento sostenido a largo plazo.
* Periodos de expansión estructural.
* Cambios que no necesariamente implicaban mejoras en eficiencia productiva.

**Modelado Predictivo**
Se implementó un modelo de Regresión Lineal utilizando el año como variable independiente y la producción como variable objetivo.
El modelo fue entrenado con datos históricos y se realizaron predicciones hasta 2030.
El objetivo no fue construir un modelo complejo, sino demostrar capacidad de:
* Preparar datos para machine learning.
* Entrenar un modelo supervisado.
* Generar predicciones estructuradas.
* Interpretar resultados con criterio.


## Resultados y Conclusiones (En términos de negocio)

**Crecimiento histórico significativo**
La producción mostró un crecimiento acumulado superior al 1000% desde 1970, reflejando expansión territorial y consolidación del sector.

**Identificación de anomalías estructurales**
El salto productivo entre 1998 y 1999 no estuvo acompañado por un incremento proporcional en rendimiento, lo que sugiere cambios metodológicos, ampliación de superficie o reestructuración estadística.

**Relación directa entre superficie y producción**
Se confirmó una correlación positiva fuerte entre superficie cosechada y volumen total producido, indicando que el crecimiento estuvo más asociado a expansión territorial que a mejoras tecnológicas significativas.

**Proyección futura estable**
El modelo predictivo sugiere una tendencia de crecimiento sostenido, útil para planificación estratégica y análisis de capacidad productiva.

## Valor Profesional del Proyecto

Este proyecto demuestra capacidad para:
* Trabajar con datasets históricos extensos.
* Analizar datos con criterio estadístico y contextual.
* Integrar Python y SQL en un mismo flujo de trabajo.
* Comunicar resultados en términos estratégicos.
* Transformar datos en información útil para toma de decisiones.


