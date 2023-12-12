# Mobile Phone Price Analysis

## Overview

This project aims to provide a comprehensive understanding of the factors influencing mobile phone prices in the competitive market. Through extensive data analysis and visualization, we explore the relationships between various features and price ranges of mobile phones. The ultimate goal is to offer insights that can guide mobile phone companies in making informed decisions about pricing and product positioning.

## Project Components

1. **Data Collection:**
   - Gather a comprehensive dataset containing information about mobile phone models, their features, and corresponding selling prices.

2. **Data Preprocessing:**
   - Clean the dataset by handling missing values, removing outliers, and normalizing numerical features.

3. **Feature Selection:**
   - Identify relevant features likely to have a significant impact on mobile phone prices (e.g., RAM, internal memory, processor, camera quality, display size).

4. **Price Range Categorization:**
   - Group mobile phones into distinct price ranges based on their selling prices.

5. **Statistical Analysis:**
   - Conduct statistical analysis, including correlation analysis, hypothesis testing, and regression analysis, to explore the relationship between selected features and price ranges.

6. **Visualization:**
   - Create visual representations (scatter plots, box plots, histograms) to illustrate the relationship between features and price ranges.

7. **Insights and Recommendations:**
   - Derive insights into the factors that drive mobile phone prices and provide recommendations for pricing strategies based on the identified relationships.

## Key Findings

- Mobile phones are categorized into four price ranges, with an almost equal distribution of items in each range.
  
- Half of the devices have Bluetooth functionality, while the other half lacks this feature.

- There is a progressive boost in battery capacity as the price range increases.

- The amount of RAM consistently increases as the price range escalates from low cost to very high cost.

- Lightweight phones come at a premium price.

- The price range of a mobile phone is heavily influenced by factors such as RAM, battery capacity, and pixel quality.

- Logistic regression and XGBoosting with tuned hyperparameters yielded the most optimal outcomes for predicting mobile phone prices.

## Usage

1. **Data Collection:**
   - Obtain the dataset containing mobile phone information.

2. **Data Preprocessing:**
   - Run the data preprocessing script to clean and normalize the dataset.

3. **Feature Selection:**
   - Execute the feature selection script to identify key features.

4. **Price Range Categorization:**
   - Group mobile phones into price ranges using the categorization script.

5. **Statistical Analysis:**
   - Run statistical analysis scripts to explore feature-price relationships.

6. **Visualization:**
   - Generate visualizations to illustrate insights from the analysis.

7. **Insights and Recommendations:**
   - Review findings and recommendations in the project report.

## Dependencies

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

