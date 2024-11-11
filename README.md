# Detección predictiva de fallos en inversores fotovoltaicos mediante aprendizaje semi-supervisado

![Photovoltaic Fault Detection Project](https://jdelectricos.com.co/wp-content/uploads/2017/12/EPM-Granja-solar.jpg))

## Introducción

Este proyecto aborda el problema de la detección y prevención de fallos en inversores fotovoltaicos a través del análisis predictivo mediante técnicas de aprendizaje automático semi-supervisado. Los inversores fotovoltaicos, componentes esenciales para la conversión de energía solar, pueden experimentar fallos que disminuyen su eficiencia y disponibilidad, impactando negativamente en la producción de energía. El objetivo principal es predecir fallos y anomalías en estos inversores utilizando datos operativos y meteorológicos.

La solución propuesta implica desarrollar un modelo de predicción de fallos basado en redes neuronales de memoria a largo corto plazo (LSTM) y técnicas de detección de anomalías como el Isolation Forest. Se procesaron más de 2 millones de puntos de datos operativos de cinco inversores ubicados en una planta fotovoltaica, integrando información meteorológica adicional obtenida a través de la API de Open-Meteo. Se aplicaron técnicas de reducción de dimensionalidad y normalización para optimizar el rendimiento de los modelos.

Esta solución es ventajosa porque, a diferencia de los enfoques convencionales, puede predecir fallos de forma proactiva, permitiendo tomar medidas preventivas y reduciendo el tiempo de inactividad. Además, el uso de modelos basados en series temporales permite captar patrones más complejos y específicos, mejorando la precisión de la predicción.

Los resultados obtenidos demuestran que el modelo LSTM predijo con precisión las anomalías, aunque existen oportunidades de mejora en términos de anticipación temporal. Este trabajo sienta las bases para futuras investigaciones detalladas sobre la implementación de estos modelos en entornos reales y su optimización para mejorar aún más la eficiencia de las plantas fotovoltaicas.

## Objetivos

- Desarrollar un modelo predictivo para la detección de fallos en inversores fotovoltaicos.
- Analizar datos operativos y meteorológicos para identificar patrones que conduzcan a fallos.
- Implementar y evaluar técnicas de aprendizaje automático, incluidas LSTM e Isolation Forest.

## Datos

- **Confidencial:** Los datos de esta tesis son confidenciales.
- **Datos Operativos:** Más de 2 millones de registros de cinco inversores fotovoltaicos.
- **Datos Meteorológicos:** Recopilados a través de la API de Open-Meteo.

## Metodología

1. **Recopilación de Datos:** Obtención de datos operativos y meteorológicos.
2. **Preprocesamiento de Datos:** Aplicación de normalización y reducción de dimensionalidad.
3. **Desarrollo del Modelo:** Utilización de redes LSTM y técnicas de detección de anomalías.
4. **Evaluación:** Valoración del rendimiento del modelo en términos de precisión y capacidad de predicción.

## Resultados

- El modelo LSTM predijo con éxito anomalías con una precisión considerable.
- Se identificaron áreas de mejora en la anticipación de ocurrencias de fallos.

## Trabajo Futuro

- Explorar mejoras adicionales en la arquitectura y los hiperparámetros del modelo.
- Implementar el modelo en escenarios del mundo real para evaluar su aplicabilidad práctica.
- Investigar la integración de fuentes de datos adicionales para una mejor predicción.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT; consulte el archivo [LICENSE](LICENSE) para obtener más detalles.
