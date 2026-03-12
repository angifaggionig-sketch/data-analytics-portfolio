# Ecosistema Global de Startups — Análisis de Inversión

![Dashboard Preview](dashboard-preview.PNG)

## Resumen Ejecutivo

Este proyecto analiza el comportamiento de inversión en el ecosistema mundial 
de startups utilizando datos reales de Crunchbase con más de 50,000 registros 
de empresas a nivel global. El objetivo es identificar patrones geográficos, 
sectoriales e históricos que expliquen cómo se distribuye el capital de riesgo 
a nivel mundial.

## Contexto del Negocio

La inversión en startups es uno de los indicadores más relevantes del dinamismo 
económico e innovador de un país. Comprender dónde se concentra el capital, en 
qué sectores y bajo qué tendencias históricas permite tomar decisiones 
estratégicas de mercado, expansión o inversión.

## Preguntas de Negocio

1. ¿Qué mercados geográficos concentran la mayor parte del capital de riesgo global?
2. ¿Qué sectores representan las mayores oportunidades de inversión?
3. ¿Cuál ha sido la evolución histórica del ecosistema startup a nivel mundial?
4. ¿Qué empresas han captado el mayor volumen de financiamiento acumulado?

## Metodología

### Fuente de datos
Dataset de inversiones en startups obtenido de Crunchbase a través de Kaggle,
con registros históricos desde 1900 hasta 2015.

### Proceso de limpieza y transformación
- Conversión de la columna `funding_total_usd` de tipo texto a número decimal
- Eliminación de registros con valores nulos en variables clave (`country_code`, `category_list`)
- Normalización de la columna `category_list` eliminando caracteres especiales
- Depuración de columnas irrelevantes para el análisis (`permalink`, `homepage_url`)

### Herramientas

| Herramienta | Propósito |
|---|---|
| Power BI Desktop | Desarrollo del dashboard interactivo |
| Power Query | Limpieza y transformación de datos |
| Excel | Exploración y validación inicial del dataset |

## Hallazgos Principales

**1. Concentración geográfica extrema en USA**

Estados Unidos concentra aproximadamente el triple de inversión que Reino Unido,
el segundo país en el ranking. Esta concentración sugiere una dependencia 
estructural del ecosistema global respecto al mercado norteamericano, con 
implicaciones importantes para startups que buscan escalar internacionalmente.

**2. Software como sector dominante**

El sector Software lidera la inversión de forma contundente, seguido por 
E-Commerce y Biotecnología. Esto refleja la demanda sostenida de soluciones 
tecnológicas para automatizar y optimizar procesos en todas las industrias —
un patrón que abre oportunidades de análisis sectorial más profundo.

**3. Punto de inflexión en 2012**

Los datos muestran un crecimiento exponencial de la inversión a partir de 2012,
superando los 20 mil millones en volumen acumulado. Este punto de inflexión 
coincide con la masificación del smartphone y el surgimiento de modelos de 
negocio basados en plataformas digitales.

**4. Diversificación sectorial como ventaja competitiva**

A diferencia de otros países que concentran inversión en uno o dos sectores,
USA distribuye capital de riesgo en todos los segmentos del ranking. Esta 
diversificación reduce el riesgo sistémico y acelera la innovación transversal.

## Visualizaciones del Dashboard

| Visualización | Descripción |
|---|---|
| Top 10 Países por Inversión | Comparativa geográfica del capital de riesgo global |
| Top 10 Sectores por Inversión | Distribución sectorial del financiamiento |
| Evolución Histórica de Inversión | Tendencia anual desde 1900 hasta 2015 |
| Top 10 Startups por Financiamiento | Ranking de empresas por inversión acumulada |

## Conclusiones y Próximos Pasos

El análisis confirma que el ecosistema startup global está altamente 
concentrado geográfica y sectorialmente. Como siguiente paso, se propone 
un análisis más granular sobre qué tipos de industrias están adoptando 
soluciones de software para automatización de procesos, cruzando datos 
de inversión con métricas de crecimiento por sector.

## Fuente de datos

[Crunchbase Startup Investments — Kaggle](https://www.kaggle.com/datasets/arindam235/startup-investments-crunchbase)

---

**Angelina Faggioni** · Ingeniera en Sistemas | Analista de Datos · Ecuador  
[LinkedIn](www.linkedin.com/in/angelina-faggioni-game) · [Portafolio](../../README.md)
