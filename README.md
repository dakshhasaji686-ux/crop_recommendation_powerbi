# Crop Recommendation Dashboard
<img width="1380" height="731" alt="Screenshot 2026-06-01 162314" src="https://github.com/user-attachments/assets/291206a5-badd-4c4a-ad7a-9887a136aa15" />


## Overview

The Crop Recommendation Dashboard is an interactive Power BI project designed to analyze agricultural data and help users understand crop requirements based on soil and environmental conditions.

The dashboard provides insights into the relationship between soil nutrients, climate factors, and crop suitability through various visualizations and KPIs.

---

## Objectives

- Analyze crop requirements based on environmental conditions.
- Study the impact of soil nutrients (N, P, K) on crop growth.
- Understand the effects of temperature, humidity, rainfall, and pH.
- Provide interactive crop exploration through filters and slicers.
- Support data-driven agricultural decision-making.

---

## Dashboard Features

### KPI Cards

- Average Soil pH
- Average Temperature
- Average Rainfall
- Average Humidity
- Average Nitrogen (N)
- Average Phosphorus (P)
- Average Potassium (K)

### Visualizations

#### 1. Crop Distribution by Soil pH

Displays crop counts across:
- High pH
- Medium pH
- Low pH

#### 2. Crop Distribution

Donut chart showing the percentage distribution of crops by pH category.

#### 3. Rainfall Requirement by Crop

Visualizes the average rainfall required for different crops.

#### 4. NPK Requirement Analysis

Compares Nitrogen (N), Phosphorus (P), and Potassium (K) requirements across crops.

#### 5. Temperature and Humidity Analysis

Shows average temperature and humidity requirements for each crop.

#### 6. Top Crop Analysis

Scatter plot comparing:
- Temperature
- Rainfall
- Crop Categories

#### 7. Soil Fertility Index

Gauge chart representing overall soil fertility based on nutrient values.

#### 8. Interactive Crop Recommendation

Users can filter data using:
- Crop Name
- Climate Category
- Rainfall Category
- pH Category

---

## Dataset Information

The dataset contains the following features:

| Feature | Description |
|----------|------------|
| N | Nitrogen Content |
| P | Phosphorus Content |
| K | Potassium Content |
| Temperature | Temperature in °C |
| Humidity | Relative Humidity (%) |
| pH | Soil pH Value |
| Rainfall | Rainfall in mm |
| Label | Crop Name |

---

## Tools & Technologies

- Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- CSV Dataset

---

## Key Insights

- Soil pH significantly influences crop suitability.
- Different crops require different NPK nutrient levels.
- Rainfall and humidity are important factors in crop selection.
- Soil fertility can be evaluated using nutrient-based indicators.
- Interactive filtering helps users explore crop requirements efficiently.
