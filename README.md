# Análisis de Churn de Clientes - TelecomX

## Propósito del Análisis

El propósito principal de este proyecto es analizar los datos de clientes de TelecomX para identificar los factores que contribuyen a la pérdida de clientes (churn). Comprender las razones detrás del churn es crucial para que la empresa pueda desarrollar estrategias de retención efectivas, mejorar la satisfacción del cliente y optimizar sus operaciones comerciales.

## Estructura del Proyecto

El proyecto consta de un cuaderno de Jupyter (`.ipynb`) que contiene todo el código y el análisis. La estructura del cuaderno sigue un flujo lógico:

1.  **Extracción**: Carga de los datos desde la fuente original.
2.  **Transformación**: Limpieza, preprocesamiento y preparación de los datos para el análisis.
3.  **Carga y Análisis**: Realización del análisis exploratorio de datos (EDA) y visualizaciones.
4.  **Informe final**: Resumen de los hallazgos, conclusiones y recomendaciones.

Los gráficos generados durante el análisis se guardan como archivos `.png` o `.html` en el mismo directorio donde se ejecuta el cuaderno.

## Ejemplos de Gráficos e Insights

Durante el análisis exploratorio, se generaron varios gráficos para visualizar las relaciones entre las variables y el churn. Algunos ejemplos notables incluyen:

*   **Distribución de Evasión de Clientes (Churn)**: Muestra la proporción de clientes que se han dado de baja.
    *   *Insight:* Una porción significativa de clientes ha churneado, lo que resalta la necesidad de estrategias de retención.

*   **Tasa de Churn (%) por Meses de Contrato**: Ilustra cómo la antigüedad del cliente (`tenure`) afecta la tasa de churn.
    *   *Insight:* Los clientes con menor antigüedad tienen una tasa de churn considerablemente más alta, indicando que los primeros meses son críticos para la retención.

*   **Distribución de Clientes por Método de Pago y Churn**: Compara la tasa de churn entre diferentes métodos de pago.
    *   *Insight:* Los clientes que utilizan el cheque electrónico muestran una tasa de churn notablemente superior.

*   **Meses de Contrato (Tenure) vs. Cargos Mensuales por Churn**: Visualiza la relación entre tenure, cargos mensuales y churn.
    *   *Insight:* Los clientes con poca antigüedad y altos cargos mensuales son más propensos al churn.

Puedes encontrar estos y otros gráficos generados en el cuaderno.

## Instrucciones para Ejecutar el Notebook

Para ejecutar este cuaderno y replicar el análisis, sigue estos pasos:

1.  **Clonar el repositorio (si aplica)**: Si el cuaderno está en un repositorio de Git, clónalo a tu máquina local.
2.  **Abrir en Google Colab o entorno Jupyter**: Abre el archivo `.ipynb` en Google Colab o en un entorno local con Jupyter Notebook/JupyterLab instalado.
3.  **Ejecutar las celdas en orden**: Ejecuta cada celda de código secuencialmente. Asegúrate de que las celdas anteriores hayan terminado de ejecutarse antes de pasar a la siguiente.
4.  **Requisitos**: El cuaderno utiliza las bibliotecas `pandas`, `requests`, `matplotlib`, `seaborn`, y `plotly`. Asegúrate de tener estas bibliotecas instaladas en tu entorno si no estás usando Google Colab (que generalmente las incluye por defecto). Puedes instalarlas usando pip:
