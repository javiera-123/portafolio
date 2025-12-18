# portafolio

# Análisis y Clasificación de la Prosperidad Global (PIB)

## Objetivo del Proyecto
El objetivo principal de este proyecto es construir un modelo de clasificación que permita predecir el nivel de Producto Interno Bruto (PIB) de diversos países. Para ello, se utilizan indicadores económicos, demográficos y sociales provenientes del Banco Mundial, transformando el problema inicial de regresión en un problema de clasificación de cinco niveles (Bajo, Medio-Bajo, Medio, Medio-Alto, Alto).


1.  **Etapa 1: Análisis y Preparación de Datos:** Se realiza un análisis exploratorio, se identifica la presencia de valores nulos y *outliers*, y se aplica una estrategia de imputación o eliminación de variables según sea necesario. Finalmente, se discretiza la variable objetivo (PIB).


## Estructura del Repositorio
* `main/`: Contiene los datos crudos iniciales del Banco Mundial (extraídos en la Etapa Previa).
* `etapa-1`: Avances del análisis descriptivo e imputación.
* `etapa-2`: Desarrollo del PCA y creación del nuevo *dataset* de componentes.
* `etapa-3`: Implementación y evaluación de los modelos de clasificación.

El historial de la rama `main` refleja la versión más actualizada y consolidada del proyecto después de cada unión (`merge`).
