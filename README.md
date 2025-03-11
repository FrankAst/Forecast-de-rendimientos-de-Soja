# Análisis de Series Temporales - TP1

## Descripción

Este repositorio contiene el código y los resultados del análisis de series temporales aplicado a tres conjuntos de datos relacionados con la producción de soja en la provincia de Buenos Aires, Argentina. Se exploran conceptos de estacionariedad, correlaciones y modelado mediante ARIMA, SARIMA y VAR, junto con métricas de performance y análisis de residuos.

## Contenidos

### 1. Introducción

- Definición del problema y selección de las series temporales:
  - **Rendimientos de soja**
  - **Proxy de temperatura**
  - **Proxy de precipitaciones**
- Fuentes de datos
- Ingeniería de variables

### 2. Tratamiento de Series y Modelos Estadísticos

- Transformaciones aplicadas para estabilizar la varianza y lograr estacionariedad (logaritmo, diferenciación, Box-Cox)
- Evaluación de estacionariedad con pruebas de Dickey-Fuller y KPSS
- Modelado con ARIMA, SARIMA y ARIMAX
- Modelado VAR y VECM para analizar relaciones entre series

### 3. Análisis de Resultados

- Comparación de modelos mediante criterios AIC, BIC y pruebas diagnósticas
- Validación cruzada (Walk-Forward) para evaluar la capacidad predictiva
- Evaluación de errores con MAE y RMSE

### 4. Conclusiones

- Identificación de patrones a corto y largo plazo
- Impacto de las precipitaciones en los rendimientos de soja
- Posibles mejoras mediante modelos más complejos (GARCH, redes neuronales, etc.)

