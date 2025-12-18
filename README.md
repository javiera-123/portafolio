# portafolio

# Análisis y Clasificación de la Prosperidad Global (PIB)

## Objetivo del Proyecto
El objetivo principal de este proyecto es construir un modelo de clasificación que permita predecir el nivel de Producto Interno Bruto (PIB) de diversos países. Para ello, se utilizan indicadores económicos, demográficos y sociales provenientes del Banco Mundial, transformando el problema inicial de regresión en un problema de clasificación de cinco niveles (Bajo, Medio-Bajo, Medio, Medio-Alto, Alto).


1.  **Etapa 1: Análisis y Preparación de Datos:** Se realiza un análisis exploratorio, se identifica la presencia de valores nulos y *outliers*, y se aplica una estrategia de imputación o eliminación de variables según sea necesario. Finalmente, se discretiza la variable objetivo (PIB).

**Revisión general del dataset**

- Identificar el número de países, años y variables disponibles.

- Número total de observaciones

- Porcentaje de datos faltantes por variable: En caso que la variable cuente con menos de un 15% de datos NA se recomienda imputar. En caso contrario, eliminar variable.

- Identificación de outliers relevantes

- Otras observaciones relevantes.


**Indicaciones**:

- Generar una tabla de estadísticas descriptivas: media, mediana, desviación estándar, máximo, mínimo.

- Mostrar la distribución del PIB (histograma o boxplot), ya que es la variable objetivo.

- Mapa con la distribución del PIB

- Discretizar la variable dependiente `NY.GDP.MKTP.PP.KD` de aceurdo con la siguiente indicación.

    ```python
    df_wb_raw['NY.GDP.MKTP.PP.KD'] = pd.qcut(df_wb_raw['NY.GDP.MKTP.PP.KD'], q=5, labels=['Low', 'Medium-Low', 'Medium', 'Medium-High', 'High'])

    ```

- Enviar a Github a la rama 1 el notebook ejecutado en esta etapa.

    **Nota**: Debe describir de manera clara y ordenada los pasos realizados durante el desarrollo del proyecto, incorporando una breve justificación para cada uno de ellos, de modo que se expliciten las decisiones adoptadas y su coherencia con los objetivos planteados.

    Esta indicación es válida para todas las etapas del proyecto.

