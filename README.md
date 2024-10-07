# Recipe-Dataset-Analysis

This project involves cleaning, exploring, and visualizing the **EpiRecipes** dataset to derive meaningful insights about recipe trends. The analysis is conducted using Python and PySpark on Google Colab, with various data processing techniques and visualization libraries.

## Project Overview
- **Data Cleaning**: Handled missing values, dropped unnecessary columns, normalized column names, and removed outliers.
- **Exploratory Data Analysis (EDA)**:
  - Analyzed recipe ratings using histograms and boxplots.
  - Investigated correlations between nutritional components (e.g., calories, fat, protein).
  - Used stacked bar plots to show dietary preferences across calorie ranges.
  - Created scatter plots to identify patterns between calories and other nutritional factors.
  - Visualized seasonal recipe distribution using pie charts.

## Key Visualizations
1. **Top 5 High-Calorie Foods**: Bar plot showcasing the recipes with the highest calorie content.
2. **Calories vs. Fat & Protein**: Scatter plots to show relationships between nutritional elements.
3. **Dietary Preference Count**: Bar plot highlighting popular dietary trends (e.g., vegan, gluten-free).
4. **Seasonal Distribution**: Pie chart displaying recipe counts for different seasons.

## Technologies Used
- **Python**: Pandas, NumPy, Seaborn, Matplotlib.
- **PySpark**: For large-scale data processing.
- **Google Colab**: Interactive development environment.

## How to Run
1. Clone the repository and upload the dataset to Google Colab.
2. Install the required libraries (`pyspark`, `unidecode`).
3. Run the cells in sequence for data loading, cleaning, analysis, and visualization.

## Insights Gained
- **Vegan Recipes** tend to have fewer calories compared to non-vegan options.
- **Peanut-Free Recipes** are gaining popularity, while low-sugar options are less common.
- **Summer Recipes** dominate, while spring has the least.
