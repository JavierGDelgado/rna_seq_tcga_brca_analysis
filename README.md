# Análisis de expresión génica en cáncer de mama (TCGA-BRCA)

Este repositorio contiene un análisis exploratorio de datos de expresión génica y metadatos clínicos de pacientes con cáncer de mama del proyecto TCGA-BRCA. El objetivo es establecer una base sólida para análisis transcriptómicos posteriores, como la identificación de genes diferencialmente expresados, agrupamientos y modelos predictivos.

## Estructura del proyecto

El análisis se ha dividido en notebooks independientes para mejorar la claridad y facilitar su uso y revisión:

- `01_eda_RNA_SEQ_TCGA_BRCA.ipynb`: Exploración inicial de la matriz de expresión y metadatos clínicos. Incluye revisión de formatos, valores ausentes, estructuras de datos y filtrado de muestras compatibles.
- `02_preprocesamiento_filtrado_TCGA_BRCA.ipynb`: Filtrado, selección de muestras relevantes y preparación de datos para análisis de expresión.
- `03_analisis_preprocesamiento_datos_clave_TCGA_BRCA.ipynb`: Identificación de genes diferencialmente expresados (DEGs) entre grupos.
- `04_visualizacion_resultados_TCGA_BRCA.ipynb`: Representación gráfica y validación de resultados (heatmaps, boxplots, volcano plots).
- `05_funcional_enrichment_GO_KEGG_TCGA_BRCA.ipynb`: Interpretación biológica mediante análisis de enriquecimiento funcional (GO, KEGG).

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

## Notas personales
- ⚠️ **Nota**: Este análisis ha sido desarrollado desde una perspectiva de ciencia de datos aplicada.  
- No soy genetista clínico, sino profesional en formación en el ámbito de la ciencia de datos con interés en su aplicación a datos biomédicos.  
- Las decisiones técnicas y clínicas se han fundamentado en literatura científica, buenas prácticas reproducibles y, en algunos casos, con apoyo experto para garantizar la solidez del enfoque.

