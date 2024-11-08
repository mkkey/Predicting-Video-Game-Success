# Predicting Success in Video Games: An Analytical Case Study

## Project Overview

This project provides a comprehensive analysis of video game sales data. Using historical data, we aim to identify factors that influence the success of games across different platforms and regions. By analyzing sales trends, genre popularity, and the impact of user and critic reviews, we provide insights to guide marketing and inventory strategies.

## Project Objectives

The main objectives of this analysis are:
1. Identify trends in game sales across platforms and regions.
2. Determine top-performing platforms and genres.
3. Analyze the impact of user and critic reviews on game sales.
4. Test statistical hypotheses regarding platform and genre ratings.

## Features

### 1. Data Preparation
- Loading and inspecting the dataset (`games.csv`).
- Cleaning data by handling missing values and standardizing data types.
- Adding calculated fields like total global sales.

### 2. Exploratory Data Analysis
- Analyzing release trends to determine relevant time periods.
- Examining sales distribution across different platforms and genres.
- Creating interactive visualizations to illustrate key trends.

### 3. Regional Analysis
- Identifying top platforms and genres for North America, Europe, and Japan.
- Analyzing variations in platform and genre popularity by region.
- Investigating the influence of ESRB ratings on sales across regions.

### 4. Statistical Hypothesis Testing
- Testing hypotheses on user ratings:
  - Comparing Xbox One and PC average user ratings.
  - Comparing Action and Sports genres’ average user ratings.
- Using t-tests to assess statistical significance.

## Technologies Used

- **Python**: Core programming language for analysis.
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical computations.
- **Plotly Express**: Interactive visualizations.
- **Matplotlib**: Data visualization.
- **SciPy**: Statistical hypothesis testing.
- **Jupyter Notebook**: Interactive environment for running the analysis.

## Dataset

The analysis uses a single dataset, `games.csv`, which includes:
- **Name**: Title of the game.
- **Platform**: Gaming platform (e.g., Xbox, PlayStation).
- **Year_of_Release**: Year the game was released.
- **Genre**: Genre of the game (e.g., Action, Sports).
- **NA_sales, EU_sales, JP_sales, Other_sales**: Regional sales in millions.
- **Critic_Score**: Aggregate critic score (out of 100).
- **User_Score**: User rating (out of 10).
- **Rating**: ESRB rating (e.g., E for Everyone, T for Teen).

## Analysis Workflow

### 1. Data Preparation
   - Load and clean data.
   - Handle missing values and data type inconsistencies.
   - Add calculated fields such as total sales.

### 2. Exploratory Data Analysis
   - Analyze trends in game releases and sales.
   - Visualize key patterns across platforms and genres.

### 3. Regional Analysis
   - Identify top platforms and genres in North America, Europe, and Japan.
   - Analyze ESRB rating impacts on regional sales.

### 4. Hypothesis Testing
   - Test for differences in user ratings across platforms and genres.
   - Interpret p-values to accept or reject hypotheses.

## Findings

1. **Top Platforms**: PS2, X360, and Wii are among the highest-selling platforms historically, while newer platforms show different levels of adoption by region.
2. **Popular Genres**: Action, Sports, and Shooter genres dominate in terms of sales, suggesting strong demand.
3. **Regional Preferences**: North America and Europe share similar preferences, while Japan has a distinct preference for portable platforms.
4. **ESRB Ratings**: Ratings show varied impacts on sales by region, with notable differences in Japan.

## Recommendations

1. **Marketing Strategy**: Focus on popular genres and region-specific platform preferences for more effective advertising.
2. **Inventory Management**: Prioritize top-selling platforms and genres, and consider discontinuing low-demand categories.
3. **Further Analysis**: Continue monitoring user and critic review impacts on game success.

## Project Structure

- `notebooks/`
  - `video_game_analysis.ipynb`: Jupyter Notebook containing the analysis and visualizations.
- `README.md`: Overview of the project and findings.
