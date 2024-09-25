# Advanced House Price Prediction

![Python](https://img.shields.io/badge/python-3.6%2B-blue.svg)
![Data Science](https://img.shields.io/badge/field-Data%20Science-green.svg)

## Table of Contents

- [Introduction](#introduction)
- [Motivation](#motivation)
- [Project Goals](#project-goals)
- [Project Outline](#project-outline)
- [Data Exploration](#data-exploration)
- [Advanced Regression Techniques](#advanced-regression-techniques)


## Introduction

Accurately predicting house prices is a complex task influenced by a myriad of factors, both tangible and intrinsic. While features like the quality and size of a house are straightforward, elements such as economic performance add layers of complexity to the prediction models. This project delves into advanced regression techniques to uncover the most impactful features affecting house prices, providing insights that go beyond mere predictions.

## Motivation

Before the 2007-2008 housing crisis, the prevailing belief was that house prices would consistently rise, assuring returns for property investors. However, the crisis exposed vulnerabilities in the housing market, highlighting how internal factors (like loan approvals) and external factors (economic downturns) can drastically influence house prices. Understanding these factors is crucial for developing robust predictive models that can withstand such fluctuations.

## Project Goals

The project is divided into two main phases:

1. **Exploratory Data Analysis (EDA):**
   - Gain a comprehensive understanding of the dataset.
   - Identify and focus on features with the highest correlation to house prices.
   
2. **Advanced Regression:**
   - Implement sophisticated regression models to predict house sale prices accurately.

## Project Outline

### I. Understanding Our Data
   - **Splitting into Different Categories**
   - **Gathering Basic Insights**

### II. Economic Activity

### III. Outside Surroundings
   - **Type of Zoning**
   - **Neighborhoods**

### IV. Areas of the House
   - **The Impact of Space on Price**

### V. Building Characteristics
   - **Correlations with SalePrice**
   - **Insights from Garage Features**

### VI. Miscellaneous and Utilities
   - **Determining House Quality**
   - **Interesting Insights**
   - **Material Combinations Impacting Prices**

### VII. Quality of Neighborhoods

### VIII. The Purpose of Using Log Transformations
   - **Log Transformations**
   - **Skewness and Kurtosis**
   - **Outlier Analysis**
   - **Bivariate Analysis**

### IX. Feature Engineering
   - **Dealing with Missing Values**
   - **Transforming Values**
   - **Combining Attributes**
   - **Handling Numerical and Categorical Values**

### X. Scaling
   - **Categorical Encoding**
   - **Combining Attributes**
   - **Pipelines**

### XI. Predictive Models
   - **Residual Plot Analysis**
   - **Random Forest Regressor**
   - **Gradient Boosting Regressor**
   - **Stacking Regressor**

## Data Exploration

Before diving into model building, an extensive analysis of the dataset is performed. This includes examining distributions, identifying missing values, and creating visualizations to understand the underlying patterns and relationships within the data.

> "I'd rather have a full house at a medium price than a half-full at a high price." - George Shinn

## Advanced Regression Techniques

Post data exploration, the project leverages advanced regression models to predict house prices. By identifying and engineering key features, the models aim to achieve high accuracy and reliability in various economic scenarios.


## Installation

### Prerequisites

- Python 3.6 or higher
- [Anaconda](https://www.anaconda.com/) (recommended)


```bash
git clone https://github.com/abdullah-khaled0/Advanced-House-Price-Prediction-and-EDA.git
cd advanced-house-price-prediction
```

```bash
conda create -n house_price_env python=3.8
conda activate house_price_env
```

```bash
conda install --file requirements.txt
```
