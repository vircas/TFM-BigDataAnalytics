# Trabajo Fin de Máster - Máster Big Data Analytics (UPV)

---

# Análisis de la Eutrofización del Mar Menor con Datos Sintéticos

Este proyecto se centra en la eutrofización del Mar Menor, una laguna costera que ha experimentado una degradación ambiental significativa desde 2016, especialmente con el evento de la "Sopa Verde". Este fenómeno ha afectado notablemente al turismo, la pesca y la agricultura de la región.

## Objetivo del Proyecto

Debido a la falta de datos consistentes sobre las causas del problema, el objetivo principal de este trabajo es **generar datos sintéticos** para construir una **serie temporal continua** de los niveles de Clorofila A y Turbidez del agua desde 2016 hasta la actualidad. Para ello, se emplean datos de cuatro fuentes distintas, incluyendo mediciones terrestres y satelitales.

## Desafíos y Enfoque Metodológico

Las mediciones satelitales presentan desviaciones respecto a las terrestres, las cuales son consideradas más precisas. En este proyecto:

1. **Análisis independiente de las fuentes de datos** para comprender las variaciones y consistencias en cada conjunto.
2. **Integración de datos** mediante técnicas de modelado para reducir diferencias en frecuencias de medición y precisión.

## Tecnología Implementada

Para superar las diferencias en las frecuencias de medición y garantizar una serie temporal consistente, el proyecto implementa una **Red Adversaria Generativa (GAN)**, utilizando el modelo **DGAN** de la librería *Gretel-synthetics*. Este enfoque permite la creación de datos sintéticos realistas que reflejan con precisión los patrones de Clorofila A y Turbidez en el tiempo.

## Contribuciones

Este trabajo proporciona una base de datos temporal continua para el análisis de la eutrofización del Mar Menor, lo que puede ser útil para futuras investigaciones y esfuerzos de conservación.

---

