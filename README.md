# Corruption and Human Development Visualization

## Overview
This project explores the relationship between the Corruption Perceptions Index (CPI) and the Human Development Index (HDI) across various countries and regions. Utilizing data visualization techniques with R and the ggplot2 library, we aim to uncover insights into how corruption levels are associated with human development metrics.

## Data Source
The analysis is based on the Economist_Assignment_Data, which includes the CPI and HDI for numerous countries along with regional classifications. The CPI scores are from 2011 and are on a scale from 10 (least corrupt) to 0 (most corrupt), while the HDI scores are from 2011, on a scale from 0 to 1 (1 being the highest human development).

## Tools and Libraries
- R Programming Language
- ggplot2 for data visualization
- data.table for data manipulation

## Features
The project includes several visualization steps to analyze the data:
1. **Basic Scatter Plot**: Initial visualization of CPI vs. HDI, colored by region.
2. **Enhanced Scatter Plot**: Improved visualization with adjusted point shapes and sizes.
3. **Trend Line**: Addition of a smoothed trend line to highlight the overall relationship.
4. **Linear Model Fit**: Application of a logarithmic linear model to better understand the correlation between CPI and HDI.
5. **Country Labels**: Selective labeling of specific countries to identify outliers or points of interest.
6. **Styling Improvements**: Application of the theme_bw() for a cleaner visual appearance and adjustment of axis titles and scales for better readability.
7. **Final Visualization**: A comprehensive plot titled "Corruption and Human Development", encapsulating all the visual enhancements and analytical insights.

## Conclusion
Through detailed data visualization, this project provides a clear view of the relationship between corruption perceptions and human development across different countries and regions. It highlights the potential impact of corruption on a country's developmental progress and offers a platform for further analysis and discussion.
