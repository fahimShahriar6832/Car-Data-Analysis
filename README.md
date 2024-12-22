# Data Analysis of Vehicle Categories and Engine Types

## Overview
This project conducts a comprehensive analysis of vehicle mileage and pricing across various categories and engine types. It aims to provide insights into trends that can assist consumers and manufacturers in making informed decisions.

## Table of Contents
1. [Import Necessary Libraries & Datasets](#import-necessary-libraries--datasets)
2. [Data Preparation](#data-preparation)
   - 2.1 [Engine Type](#engine-type)
     - 2.1.1 [extract_engine_type Function](#extract_engine_type-function)
   - 2.2 [Category](#category)
     - 2.2.1 [map_category Function](#map_category-function)
     - 2.2.2 [categorize_entry](#categorize_entry)
3. [Data Cleaning](#data-cleaning)
   - 3.1 [Title and Category Mismatch](#title-and-category-mismatch)
   - 3.2 [Multiple Engine Types in Title](#multiple-engine-types-in-title)
   - 3.3 [Engine Type and Fuel Type Mismatch](#engine-type-and-fuel-type-mismatch)
   - 3.4 [Contradictions in Title and Transmission](#contradictions-in-title-and-transmission)
     - 3.4.1 [Contradiction in Title (DSG & Hand)](#contradiction-in-title-dsg--hand)
     - 3.4.2 [Title (Hand) and Transmission (Automatic) Mismatch](#title-hand-and-transmission-automatic-mismatch)
     - 3.4.3 [Title (DSG) and Transmission Mismatch (Manual)](#title-dsg-and-transmission-mismatch-manual)
4. [Plotting Results](#plotting-results)

## Import Necessary Libraries & Datasets
In this section, we import the necessary libraries for data manipulation, analysis, and visualization, as well as load the datasets used throughout the project.


## Data Preparation

### 2.1 Engine Type

#### extract_engine_type Function
This function extracts the engine type from the dataset based on predefined criteria.


### 2.2 Category

#### map_category Function
This function maps vehicle titles to their respective categories.


#### categorize_entry
This function applies the mapping to each entry in the dataset.


## Data Cleaning

### 3.1 Title and Category Mismatch
Identify and resolve discrepancies between the vehicle title and its assigned category.

### 3.2 Multiple Engine Types in Title
Handle cases where a single entry may contain multiple engine types, ensuring clarity in classification.

### 3.3 Engine Type and Fuel Type Mismatch
Check for inconsistencies between the recorded engine type and fuel type, correcting any errors found.

### 3.4 Contradictions in Title and Transmission

#### 3.4.1 Contradiction in Title (DSG & Hand)
Address cases where the title indicates a DSG transmission but also mentions "hand."

#### 3.4.2 Title (Hand) and Transmission (Automatic) Mismatch
Resolve entries where the title specifies "hand" but the transmission type is recorded as automatic.

#### 3.4.3 Title (DSG) and Transmission Mismatch (Manual)
Correct instances where the title indicates DSG but is recorded as manual transmission.

## Plotting Results
Visualize key findings from the analysis using appropriate plots to illustrate trends in mileage, pricing, and engine types across different vehicle categories.


## Conclusion 
This project provides valuable insights into vehicle performance metrics across different categories and engine types, highlighting trends that can inform consumer choices and manufacturing strategies.


