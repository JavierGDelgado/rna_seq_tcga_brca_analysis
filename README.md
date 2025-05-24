# Análisis de expresión génica en cáncer de mama (TCGA-BRCA)

Este repositorio contiene un análisis exploratorio de datos de expresión génica y metadatos clínicos de pacientes con cáncer de mama del proyecto TCGA-BRCA. El objetivo es establecer una base sólida para análisis transcriptómicos posteriores, como la identificación de genes diferencialmente expresados, agrupamientos y modelos predictivos.

## Estructura del proyecto

El análisis se ha dividido en notebooks independientes para mejorar la claridad y facilitar su uso y revisión:

- `01_eda_RNA_SEQ_TCGA_BRCA.ipynb`: Exploración inicial de la matriz de expresión y metadatos clínicos. Incluye revisión de formatos, valores ausentes, estructuras de datos y filtrado de muestras compatibles.

## Datos

Los datos se han obtenido de UCSC Xena y contienen:

- Expresión génica (RNA-Seq normalizada, formato log2).
- Metadatos clínicos asociados a las muestras.

## Herramientas utilizadas

- Python 3.9
- Pandas, NumPy, Matplotlib
- Jupyter Notebook

## Autor

Javier García Delgado  
24 de Mayo de 2025  
Proyecto académico orientado a investigación biomédica y ciencia de datos.

