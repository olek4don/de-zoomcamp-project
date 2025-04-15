# ATP Tennis Data Pipeline and Dashboard Project

## Project Overview

This project aims to build an end-to-end data pipeline and a dashboard using the ATP Tennis dataset. The pipeline will ingest, process, and transform data to provide meaningful insights through visualizations. The dashboard will include two tiles: one showing the distribution of categorical data and another displaying trends over time.

---

## Phase 1: Define the Project Scope & Choose Data

### Problem Statement
The goal of this project is to analyze ATP tennis match data to uncover insights about player performance, tournament trends, and other key metrics. The project will culminate in a dashboard that visualizes these insights for easy interpretation.

---

### Dataset Description

- **Dataset Name**: ATP Tennis Dataset
- **Source**: [Kaggle](https://www.kaggle.com/code/dissfya/atp-tennis-daily-pull?select=atp_tennis.csv)
- **Description**: This dataset contains detailed information about ATP tennis matches, including player statistics, match outcomes, tournament details, and more.
- **Data Dictionary**:
  - `Column 1`: *[Description of column]* (e.g., Player Name)
  - `Column 2`: *[Description of column]* (e.g., Match Date)
  - `Column 3`: *[Description of column]* (e.g., Tournament Name)
  - *(Add more columns as needed)*

---

### Use Case

The project focuses on answering the following key questions:
1. **Categorical Insight**: *Which surface (clay, grass, hard) has the highest win rate for top-ranked players?*  
2. **Temporal Insight**: *Are betting odds becoming more accurate in predicting winners between 2015 and 2025?* 

---

### Pipeline Type

- **Chosen Approach**: Batch  
  - A batch pipeline is chosen because the dataset is historical and periodic updates are sufficient.  

---

### Preliminary Cleaning Plan

The raw dataset will undergo the following cleaning steps:
1. Handle missing or incomplete values (e.g., fill or drop rows with missing match stats).
2. Standardize date formats to `YYYY-MM-DD`.
3. Filter out irrelevant data (e.g., exclude doubles matches if focusing on singles).
4. Normalize categorical fields (e.g., unify player names with consistent capitalization).
---

### Dashboard Metrics

The dashboard will include two tiles:
1. **Categorical Tile**: Distribution of win rates across different surfaces (clay, grass, hard) for top-ranked players. This tile will visually compare the performance of highly ranked players on each surface to determine which surface yields the highest win rate.
2. **Temporal Tile**: *Trends in the accuracy of betting odds in predicting match winners between 2015 and 2025. This tile will display how often the player with higher pre-match odds wins over time, highlighting whether betting odds have become more reliable during the specified period.*  

---

### Scope Phase Summary

1. **Problem Statement**:
   - Analyze ATP tennis data to provide insights into player performance and trends.
2. **Dataset Description**:
   - Detailed information about ATP matches sourced from Kaggle.
3. **Use Case**:
   - Focused on categorical and temporal insights relevant to tennis performance.
4. **Pipeline Type**:
   - Chosen as *[Batch/Stream]* for its suitability to the dataset and use case.
5. **Preliminary Cleaning Plan**:
   - Steps outlined to ensure clean and consistent data for analysis.
6. **Dashboard Metrics**:
   - Two tiles identified for visualization in the dashboard.

---

## Next Steps

With Phase 1 completed, the next phase will focus on Define the Project Scope and Data
