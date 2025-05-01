# Análisis de Series de Tiempo para Pronóstico de Inflación

Este repositorio contiene un análisis para predecir la inflación utilizando técnicas de **nowcast** y **forecast**. En este proyecto, se emplea **Microsoft Excel** para realizar pronósticos de inflación, aplicando métodos sencillos y modelos avanzados como el **AR(2)**. Además, se evalúa la efectividad de estos pronósticos en comparación con las expectativas del Banco Central y otros indicadores económicos actuales.

## Descripción del Proyecto

Este ejercicio académico aborda las limitaciones del análisis presentado en los proyectos anteriores de Series de Tiempo del MBAn. En dichos proyectos, se asumió incorrectamente que el dato de inflación de diciembre de 2011 estaba disponible al final de ese mes, cuando en realidad ese dato no sería conocido hasta el mes siguiente. Este proyecto corrige esa suposición y realiza un análisis realista utilizando datos históricos de inflación actualizados hasta marzo de 2025, junto con las proyecciones más recientes de la Encuesta de Expectativas Económicas (EEE) del Banco Central y del IMCE.

### Objetivos del Proyecto

1. **Nowcast**: Predicción de la inflación para el mes en curso utilizando varios métodos ingenuos y datos disponibles de encuestas.
2. **Forecast**: Predicción de la inflación para el mes siguiente utilizando técnicas sencillas y avanzadas.
3. **Modelo AR(2)**: Construcción de un modelo autorregresivo (AR) para proyectar la inflación a 12 meses.
4. **Comparación de Modelos**: Comparar los resultados de diferentes pronósticos (promedio histórico, último dato disponible, modelo AR(2), etc.) y evaluar su precisión.

### Estructura del Proyecto

El análisis se divide en varias hojas dentro del archivo Excel, que contienen los cálculos y resultados de cada paso del proyecto:

1. **Nowcast**: Pronóstico de la inflación para el mes en curso utilizando métodos como la última observación, promedio histórico, promedio de las últimas 50 observaciones, pronóstico constante, y las encuestas del Banco Central e IMCE.
2. **Pronóstico**: Proyección de la inflación para el mes siguiente utilizando métodos similares y comparación con los resultados de **Nowcast**.
3. **Análisis**: Evaluación crítica del pronóstico de inflación de las encuestas del Banco Central frente al IMCE, utilizando los resultados de proyectos anteriores y del proyecto actual.
4. **Modelo AR(2)**: Pronóstico de la inflación utilizando un modelo AR(2) con parámetros ajustados en ventanas rodantes de 50 observaciones.
5. **Pronóstico con AR(2)**: Pronóstico a 12 meses de inflación usando el modelo AR(2) y evaluación de si la inflación se mantendrá dentro del rango de tolerancia del Banco Central.

## Resultados Clave

- Se realizaron pronósticos tanto para el mes actual (nowcast) como para el mes siguiente (forecast), utilizando modelos simples e incrementales.
- Se construyó un **modelo AR(2)** para estimar la inflación a futuro, utilizando datos históricos y los pronósticos del Banco Central e IMCE.
- Los resultados muestran que el **IMCE** es más preciso que la EEE. Sin embargo, su precisión varía cuando se compara con el método de última observación.
- Los modelos avanzados, como **AR(2)**, muestran una mejor capacidad predictiva para proyecciones.

## Cómo Ejecutar el Proyecto

Este proyecto está completamente documentado en el archivo Excel. Para reproducir los análisis:

1. Abre el archivo y navega por las hojas **Nowcast**, **Pronóstico**, **Análisis**, **Modelo AR(2)** y **Pronóstico con AR(2)** para ver los cálculos y pronósticos realizados.
2. Los cálculos de la **Raíz del Error Cuadrático Medio de Proyección (RECM)** y las comparaciones de los modelos se encuentran detalladas en cada hoja.

## Tecnologías y Herramientas Utilizadas

- **Microsoft Excel**: Para realizar los cálculos de series de tiempo, los pronósticos y el análisis de modelos.
- **Modelos AR(2)**: Implementación de modelos autorregresivos para la proyección de inflación a corto y largo plazo dentro de Excel.

