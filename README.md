# ARDL Model Analysis on Unemployment and Economic Indicators in Africa
**Project Overview**
This project analyzes the relationship between unemployment and key economic indicators—GDP, Foreign Direct Investment (FDI), inflation, and population growth—across five African countries: Kenya, Nigeria, South Africa, Egypt, and the Republic of Congo. The analysis employs the Autoregressive Distributed Lag (ARDL) model and the Error Correction Model (ECM) to explore both short-run and long-run dynamics.
**
Objectives**
The primary goal of this project is to investigate the applicability of Okun's Law, which suggests an inverse relationship between unemployment and GDP growth, within these selected African countries. The study also expands on this by incorporating additional variables such as FDI, inflation, and population growth to understand unemployment patterns in the region better.

**Key Objectives:**
Analyze the relationship between GDP growth and unemployment based on Okun’s Law.
Extend the analysis by including FDI, inflation, and population growth to assess their impact on unemployment.
Conduct stationarity tests, cointegration analysis, and estimate the ECM to capture both short-run and long-run relationships.
Methodology

**The following steps were undertaken in this analysis:**

Data Collection: Data from 1992 to 2022 was sourced from the World Bank, including unemployment rates, GDP, FDI, inflation, and population growth for the five countries.
Stationarity Tests: The Im-Pesaran-Shin (IPS) unit root test was applied to determine whether the data series are stationary at levels or after first differencing.
Lag Length Selection: Optimal lag lengths for the ARDL model were selected using the Akaike Information Criterion (AIC) and Schwarz Criterion (SC).
Cointegration Test: The Augmented Dickey-Fuller (ADF) test was used to check for long-run equilibrium relationships among the variables.
Error Correction Model (ECM): ECM was employed to capture the speed of adjustment back to long-run equilibrium after shocks.
File Structure
Countries.csv: The dataset containing the time series data for the five African countries.
ARDL_Project.Rmd: The RMarkdown file containing the full analysis code, including data preprocessing, model fitting, and results generation.
README.md: This file, providing a detailed overview of the project, including objectives, methodology, and instructions.
