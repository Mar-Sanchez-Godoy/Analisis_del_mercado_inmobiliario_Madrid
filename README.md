# Analisis_del_mercado_inmobiliario_Madrid
Proyecto dedicado al analisis de la evolucion del precio por m2 en Madrid desde el 2007 hasta el 2024 basado en datos estatales (Ayuntamiento de madrid e INE)

# Analisis de mercado inmobiliario – Madrid (2007–2024)

Análisis del mercado inmobiliario en Madrid utilizando Sheets y Power BI, con limpieza de datos, modelado, visualización avanzada y conclusiones orientadas a negocio.

![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Visualization-F2C811)

![DAX](https://img.shields.io/badge/DAX-Data%20Modeling-0A66C2)

![Google Sheets](https://img.shields.io/badge/Google%20Sheets-Data%20Cleaning-34A853)



## Objetivo del proyecto

Comprender la evolución del precio por metro cuadrado (m²) en los distritos de Madrid entre 2007 y 2024, identificando:

- Variación anual del mercado
- Distritos con mayor y menor crecimiento
- Patrones de comportamiento por zona
- Tendencias útiles para compradores, inversores y analistas


## Vista previa del Panel de visualización

🟦 Página 1 — Ranking de precios por distrito
<p align="center">
<img src="Images/Visualizacion_Ranking por distritos.png" width="750">
</p>

🟦 Página 2 — Mapa de calor por distrito y año
<p align="center">
<img src="Images/Visualizacion_Heatmap.png" width="750">
</p>

🟦 Página 3 — Conclusiones clave + Variación YoY
<p align="center">
<img src="Images/Visualizacion_Conclusiones y tendencia" width="750">
</p>


## Conclusiones clave

- El distrito con mayor crecimiento acumulado es Salamanca (+3,43%).
- El distrito con peor evolución es Villaverde (-1,0%).
- El mejor año del mercado fue 2018 (+14,81%).
- El peor año fue 2012 (-9,32%).
- La tendencia general del mercado es alcista, con un crecimiento medio anual del 1,99%.


## Proceso del análisis

1. Recolección del dataset CSV
Datos oficiales del Ayuntamiento de Madrid:
https://servpub.madrid.es/CSEBD_WBINTER/seleccionSerie.html?numSerie=0504030000152

2. Limpieza y transformación en Google Sheets y Power Query

- Normalización de columnas
- Corrección de valores atípicos
- Estandarización de distritos y fechas
- Eliminación de inconsistencias

3. Modelado en Power BI

- Relaciones entre tablas
- Creación de medidas DAX
- Segmentación por distrito y año
- Cálculo de variación YoY y acumulada

4. Visualización

- Ranking de precios por distrito
- Mapa de calor de evolución anual
- Conclusiones automáticas generadas con DAX
- Tema visual estilo consultora


## Estructura del repositorio

Código: Real-Estate-Madrid-Analysis/

/Images
 Capturas del proceso:
- Conclusiones y tendencia.png
- Heatmap.png
- Modelo de estrella.png
- Plantilla de precios de Madrid en bruto.png
- Ranking por distritos.png
- Tabla transformada.png
- Tablas.png

/ dataset
 Archivos utilizados
- Datos inmobiliarios - Visualizacion.pdf
- Datos inmobiliarios.pbix
- Precios historicos Madrid - Ayuntamiento.xlsx


 README.md



## Archivos incluidos

- Datos inmobiliarios.pbix → Dashboard final
- Datos inmobiliarios - Visualizacion.pdf → Informe exportado
- Dataset/ → Datos originales
- Images/ → Capturas del dashboard


## Aprendizajes

- Diseño de dashboards con enfoque consultivo
- Creación de medidas DAX para análisis dinámico
- Limpieza y normalización de datos reales
- Documentación clara del proceso analítico

## Conclusiones

### ¿Por qué están aumentando los precios?

El análisis sugiere que el incremento a largo plazo de los precios de la vivienda en Madrid está relacionado principalmente con la interacción entre una demanda creciente y una oferta residencial relativamente limitada. No obstante, los precios de la vivienda también se ven influidos por condiciones económicas y financieras más amplias que afectan a la capacidad de compra de los hogares, al acceso al crédito y a las decisiones de inversión.

Diversos factores estructurales y macroeconómicos pueden ayudar a explicar la evolución del mercado:

* **Demanda creciente:** Madrid continúa atrayendo población, empleo y actividad económica, lo que incrementa la demanda de vivienda.

* **Oferta residencial limitada:** La construcción de nueva vivienda no siempre ha ido al mismo ritmo que la demanda, generando una presión al alza continuada sobre los precios.

* **Disponibilidad limitada de suelo:** La disponibilidad y el desarrollo de suelo urbanizable condicionan la capacidad de aumentar la oferta con rapidez, especialmente en zonas con fuerte demanda.

* **Tipos de interés más bajos:** La reducción de los tipos de interés europeos ha mejorado las condiciones de financiación en comparación con el entorno de tipos altos de 2023–2024. El tipo principal de refinanciación del BCE bajó del 4,25 % en junio de 2024 al 2,40 % en junio de 2026, reduciendo el coste de financiación bancaria y favoreciendo una mejora gradual del crédito.

* **Mejora de las condiciones económicas:** Tras la fuerte contracción de la economía española en 2020, la actividad se recuperó con fuerza. El PIB de España creció un 5,5 % en 2021 y, tras posteriores revisiones estadísticas, un 6,2 % en 2022. Un entorno económico más sólido respalda la demanda de vivienda al mejorar el empleo, las expectativas de ingresos de los hogares y la confianza del consumidor.

* **Menor desempleo:** La tasa de paro en España descendió del 15,53 % en 2020 al 12,92 % en 2022, lo que refleja una mejora significativa de las condiciones del mercado laboral durante el periodo de recuperación.

* **Mejor acceso a la financiación hipotecaria:** A medida que mejoran las condiciones financieras, más hogares recuperan el acceso al crédito hipotecario o se muestran dispuestos a entrar en el mercado inmobiliario. Esto puede incrementar la demanda efectiva, especialmente cuando se combina con una oferta de vivienda limitada.

* **Costes de construcción:** El encarecimiento de los materiales y de la construcción puede elevar el precio final de la nueva vivienda y ralentizar el ritmo al que la nueva oferta entra en el mercado.

* **Concentración económica:** El posicionamiento de Madrid como gran centro económico y de empleo aumenta su atractivo para trabajadores, empresas e inversores, sosteniendo una demanda continua de vivienda.

* **Demanda de inversión:** La vivienda también atrae a inversores que buscan rentabilidad a largo plazo, añadiendo otra fuente de demanda, especialmente en zonas con un mercado de alquiler dinámico y expectativas de revalorización del capital.

Estos factores no deben interpretarse como causas directas derivadas exclusivamente del conjunto de datos analizado. El proyecto identifica patrones históricos de precios, mientras que la interpretación económica general se apoya en investigación externa e indicadores macroeconómicos de instituciones como el Banco de España, el BCE y el INE.

Sin embargo, esta proyección debe tratarse como un escenario basado en tendencias históricas y no como un pronóstico definitivo de precios. Un modelo de predicción más robusto requeriría variables adicionales como los tipos de interés, el crecimiento demográfico, la renta disponible, la actividad de construcción, la concesión de hipotecas y el empleo.

Esto representa una oportunidad para futuros análisis y para el desarrollo de modelos más complejos.


### Contacto

LinkedIn: https://www.linkedin.com/in/mar-sanchez-g/  
