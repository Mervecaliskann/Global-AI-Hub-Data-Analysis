# Jobs in Data Analysis

This project explores the **Jobs in Data** dataset to analyze job roles and their features, with a special focus on handling missing data. The dataset was modified to include random missing values for the purpose of simulating real-world data challenges.

## Dataset
- **Source:** [Jobs in Data (Kaggle)](https://www.kaggle.com/datasets/hummaamqaasim/jobs-in-data)
- **Contents:** Information about job roles, descriptions, and other features in various data-related fields.

## Steps
1. **Data Preparation:** Import and preprocess the dataset.
2. **Simulating Missing Data:**  
   Random missing values were added to simulate real-world challenges, with approximately 3% of the dataset being replaced with `NaN`. These missing values were then handled using techniques such as:
   - Identifying columns with the highest missing value ratios.
   - Using statistical measures (mean, median, mode) to fill missing values.
   - Evaluating the impact of missing data on analysis results.

3. **Visualization:**  
   Various visualizations were created using `Seaborn` and `Matplotlib` to analyze job roles and other features in the dataset.

## Libraries Used
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

## Key Insights
- How job roles are distributed across the dataset.
- The importance of handling missing data effectively and its impact on insights.
- Visualization of trends and relationships within the dataset.

## How to Use
1. Clone the repository: `git clone <repo-url>`
2. Open the notebook in Jupyter or any compatible environment.
3. Run the cells to reproduce the analysis and visualizations.

## Highlights
- **Missing Data Simulation:** Introduced and resolved missing data to mimic real-world data issues.
- **Insightful Visualizations:** Clear and concise graphs to explore relationships in the dataset.
