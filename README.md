# Modelo Predictivo de Déficit Habitacional (Deep Learning)

Este repositorio contiene el código fuente en R para la integración y preprocesamiento de datos del proyecto de Tesis: *"Predicción del Déficit Habitacional mediante Redes Neuronales Artificiales"*.

## Descripción
El script realiza las siguientes operaciones de Ingeniería de Datos:
1.  **Carga e Integración:** Fusión de microdatos socioeconómicos (CASEN 2022) con indicadores territoriales (IDE MINVU 2023) mediante código comunal (CUT).
2.  **Limpieza:** Depuración de variables y manejo de valores perdidos (-88).
3.  **Targeting:** Construcción de la variable objetivo (Clase) según metodología oficial del Ministerio de Desarrollo Social, identificando:
    * Hacinamiento Crítico.
    * Allegamiento Externo.
    * Viviendas Irrecuperables (Materialidad).

## Estructura de Datos
El código genera una base de datos consolidada lista para el entrenamiento de modelos de Deep Learning (Perceptrón Multicapa).

* **Entrada:** `Base_Final_Tesis_Definitiva.rds` (No incluido en este repo por tamaño).

* **Librerías:** tidyverse, dplyr, sf.

