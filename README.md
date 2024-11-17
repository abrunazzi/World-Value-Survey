# Cultural Analysis Using the World Values Survey (WVS)

## Overview

This repository contains the analysis, code, and results of a project exploring global cultural patterns using data from the **World Values Survey (WVS)**. By applying **hierarchical clustering** and **data visualization** techniques, we uncover relationships between cultural values and socioeconomic factors across different countries.

The analysis focuses on clustering countries based on indices like respect for authority, religiosity, autonomy, equality, and other key sociocultural metrics. Additional analyses include correlations with factors like GDP per capita and political regime types.

---

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Data Sources](#data-sources)
4. [Setup](#setup)
5. [Usage](#usage)
6. [Results](#results)
7. [Future Work](#future-work)
8. [Contact](#contact)
9. [License](#license)

---

## Introduction

The **World Values Survey (WVS)** is a global initiative to study changing cultural values, norms, and beliefs across over 100 countries. This project leverages data from WVS Wave 7 (2017-2022) to identify clusters of countries based on cultural similarities and to analyze how these clusters correlate with economic and political variables. The results offer a deeper understanding of how cultural dynamics influence societal development.

---

## Features

- **Hierarchical Clustering**: Classifies countries into distinct cultural clusters.
- **Index-Based Analysis**: Evaluates cultural dimensions like authority, equality, and autonomy.
- **Data Enrichment**: Incorporates external variables like GDP per capita and regime type.
- **Advanced Visualization**: Includes dendrograms, self-organizing maps (SOM), and multidimensional scaling (MDS).
- **Exploratory Analysis**: Examines the impact of socioeconomic and political factors.

---

## Data Sources

The project integrates data from multiple sources:
- **[World Values Survey (WVS)](https://www.worldvaluessurvey.org/wvs.jsp)**: Wave 7 dataset.
- **World Bank**: GDP per capita statistics.
- **The Economist Democracy Index**: Political regime classifications.

---


### Prerequisites
- Python 3.x
- R (for Self-Organizing Maps)
- Required libraries (see `requirements.txt`)

---

##Results
###Key Findings
Clusters: Nine distinct clusters of countries were identified, each with unique cultural, economic, and political characteristics.
Correlation with GDP:
Progressive values (e.g., gender equality) are positively correlated with higher GDP per capita.
Traditional values (e.g., religiosity) are more prevalent in lower-GDP countries.
Political Regime Influence:
Democratic countries exhibit higher levels of personal freedom and civic engagement.
Authoritarian regimes show strong respect for authority and conservative social views.
