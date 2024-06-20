# Diabetes-Analysis-Project

## Descripción
Este trabajo fue realizado para la asignatura de Minería de Datos de mi grado universitario en Estadística y Empresa, y en el se realiza un análisis exhaustivo de un conjunto de datos relacionado con la diabetes. Se abordan diversas técnicas de minería de datos, incluyendo imputación de datos faltantes, análisis de componentes principales (PCA), clustering y predicciones usando varios modelos de clasificación.

## Índice
1. [Introducción](#introducción)
2. [Imputación](#imputación)
3. [Relación entre las Variables](#relación-entre-las-variables)
4. [Análisis de Componentes Principales](#análisis-de-componentes-principales)
5. [Análisis Cluster](#análisis-cluster)
6. [Predicciones](#predicciones)
7. [Instalación](#instalación)


## Introducción
Este análisis utiliza datos de 768 mujeres, cada una con 9 variables incluyendo la variable respuesta que indica la presencia de diabetes. El análisis incluye un procesamiento y transformación detallada de los datos para facilitar el análisis subsecuente.

## Imputación
Se utiliza el paquete `mice` para imputar valores faltantes en los datos. La imputación se realiza usando un método multivariante para predecir los valores faltantes basados en otras variables presentes.

## Relación entre las Variables
Se exploran gráficamente las relaciones entre las diferentes variables del conjunto de datos. Se utilizan las librerías `tidyverse` y `ggplot2` para visualizar estas relaciones y obtener una comprensión inicial de las correlaciones entre variables.

## Análisis de Componentes Principales
El PCA se realiza para reducir la dimensionalidad de los datos y visualizar la varianza explicada por cada componente principal. Se calcula la matriz de correlaciones y se explora la relación entre los componentes principales y las variables originales.

## Análisis Cluster
Se realizan análisis de clustering utilizando métodos jerárquicos aglomerativos y K-means. Estos métodos permiten identificar grupos dentro de los datos que comparten características similares.

## Predicciones
Se implementan varios modelos de predicción, incluyendo SVM sin ajuste de hiperparámetros, SVM con ajuste de hiperparámetros, regresión logística y análisis discriminante lineal mediante la aproximación de Fisher. Cada modelo se evalúa en términos de su capacidad para predecir la variable respuesta.

## Instalación
Para reproducir este análisis, primero clona el repositorio y luego instala las dependencias necesarias.
git clone https://github.com/tuusuario/diabetes-analysis-project.git
cd diabetes-analysis-project

### Librerías necesarias en R
install.packages(c("skimr", "mice", "VIM", "tidyverse", "ggplot2"))





