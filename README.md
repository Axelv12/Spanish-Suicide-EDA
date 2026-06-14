# Spanish Suicide Exploratory Data Analysis (EDA)

This repository contains an Exploratory Data Analysis (EDA) on suicide mortality in Spain during the period 2014-2023. The project aims to identify patterns, trends, and demographic, geographic, and age-related disparities using official data from the Spanish National Statistics Institute (INE).

## 👥 Authors
- Fabián Calvo Castillo
- Mario Martínez Guillen
- Axel Valton Juan

*Máster Universitario en Ciencia de Datos - Universitat de València (ETSE)*

## 📊 Overview

Suicide represents a serious public health issue. This study analyzes recorded suicide mortality data in Spain to better understand the magnitude of this problem and identify possible relationships between various factors.

The analysis is structured around different datasets:
- Annual distribution by Autonomous Community, sex, and age.
- Monthly distribution of cases across the studied years.
- Distribution of cases by nationality.

## 🛠️ Technologies Used

The entire analysis and data visualization pipeline is built using **R**. The main libraries utilized include:
- `tidyverse` (Data manipulation and cleaning)
- `ggplot2` (Data visualization)
- `mapSpain` & `sf` (Geographical data and mapping)
- `lubridate` (Date and time manipulation)
- `knitr` & `rmarkdown` (Document generation)

## 📁 Repository Structure

- `Spanish-Suicide-EDA.Rmd`: The main R Markdown document containing the source code, analysis, and visualizations.
- `Spanish-Suicide-EDA.pdf`: The compiled report containing the results of the analysis.
- `data/`: Directory containing the raw `.csv` datasets obtained from INE.
- `mybibfile.bib`: Bibliography file for references used in the analysis.

## 📈 Data Source

The data analyzed in this study is publicly available and was obtained from the **Instituto Nacional de Estadística (INE)**:
[INE - Estadísticas de defunciones según la causa de muerte](https://ine.es/dyngs/INEbase/operacion.htm?c=Estadistica_C&cid=1254736176780&menu=resultados&idp=1254735573175#_tabs-1254736194710)