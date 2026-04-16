# Google Play Store Data Analysis Project

## Project Overview
- This repository contains a comprehensive Exploratory Data Analysis (EDA) of the Google Play Store ecosystem.
- The objective is to analyze app characteristics, user ratings, pricing strategies, and content categories to uncover data-driven insights.
- The findings are intended to help stakeholders understand market trends and optimize app performance strategies.

## Repository Structure
- **data/**: Stores all raw and intermediate datasets used for analysis.
- **notebooks/**: Contains the core analytical workflows.
  - `01_cleaning.ipynb`: Scripts for handling missing values, data type conversions, and outlier treatment.
  - `02_eda.ipynb`: Scripts for generating summary statistics and initial data visualizations.
- **output/**: Houses the finalized, cleaned dataset (`playstore_clean.csv`) prepared for dashboard integration.
- **images/**: Contains all programmatic plots, charts, and graphical outputs.
- **Dashboard/**: Includes the final interactive Tableau workbook (`playstore_dashboard.twbx`) summarizing all key metrics.

## Key Insights and Visualizations
The analysis resulted in several significant findings regarding how apps are categorized and consumed. Below is a selection of the core plots generated during the EDA phase.

### Distribution by Category
- Highlights the concentration of apps across various genres and categories.
![Category Distribution](images/chart1_categories.png)

### Monetization Strategy
- Compares the proportion of free versus paid applications.
![Free vs Paid](images/chart2_free_vs_paid.png)

### User Ratings
- Examines the overall distribution and frequency of user ratings.
![Rating Distribution](images/chart3_rating_dist.png)

### Engagement Metrics
- Visualizes the total number of installations grouped by category.
![Installs by Category](images/chart4_installs_by_category.png)

### Rating Variance
- Displays the spread and outliers in application ratings across categories.
![Ratings Boxplot](images/chart5_boxplot_rating.png)

### App Relationships
- Investigates the correlation between different continuous variables such as price, size, and user rating.
![Scatter Plot](images/chart6_scatter.png)

### Target Audience
- Breaks down the market share of applications based on content rating (e.g., Everyone, Teen, Mature).
![Content Rating](images/chart7_content_rating.png)

### Maintenance and Updates
- Tracks the volume of app updates published per year to gauge developer activity.
![Updates by Year](images/chart8_updates_by_year.png)

### File Size Optimization
- Illustrates the distribution of application file sizes across the ecosystem.
![Size Distribution](images/chart9_size_dist.png)

### Variable Correlation
- A statistical heatmap showing the relationships and dependencies between dataset features.
![Correlation Heatmap](images/chart10_heatmap.png)

## Final Dashboard
- The culmination of the project is centralized in an interactive dashboard for high-level business intelligence.
- It provides a consolidated view of top-performing categories, app engagement, and market saturation.
- You can find the core dashboard file in the `Dashboard/` directory.

![EDA PlayStore Dashboard](EDA_PlayStore_Dashboard.png)

## Usage Instructions
- Clone the repository to your local environment.
- Install the required Python dependencies (e.g., pandas, matplotlib, seaborn).
- Run the notebooks sequentially from `01_cleaning.ipynb` to `02_eda.ipynb` to reproduce the analysis.
- Open the Tableau workbook in the `Dashboard/` folder to interact with the final presentation.
