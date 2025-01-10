# Socio-Economic Determinants of Mental Health in the Netherlands

This project investigates the relationship between socio-economic factors and mental health risks in the Netherlands, focusing on depression and anxiety. Previous research highlights the significant role of socio-economic conditions—such as income, education, and housing—in shaping mental health outcomes. Our study builds on these insights, analyzing neighborhood-level statistics and mental health data to identify key determinants and trends.

## Project Overview

The analysis used neighborhood data from the Centraal Bureau voor de Statistiek (CBS) and mental health risk statistics from RIVM. Data was cleaned by removing empty columns, imputing missing values with kNN, and transforming skewed distributions. Linear Regression, Ridge Regression, and Random Forest Regression models were employed to evaluate feature importance and predict mental health risks, while an Isolation Forest algorithm identified and visualized outliers. Housing-related variables, including home ownership rates, housing corporation properties, and urbanization, emerged as key predictors of mental health outcomes.

## Findings
The analysis revealed that housing-related variables, such as owner-occupied homes, home value, and urbanization, had the strongest influence on mental health risks, underscoring the critical connection between residential stability and well-being. Urbanization trends further highlighted that densely populated provinces like North and South Holland faced higher mental health risks, likely linked to urban stress factors such as crowding and noise. Additionally, the Isolation Forest analysis identified clusters of outliers in urbanized regions, emphasizing significant regional socio-economic disparities that contribute to heightened risks of anxiety and depression.

## Requirements

The following Python libraries are needed:

  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `sklearn`