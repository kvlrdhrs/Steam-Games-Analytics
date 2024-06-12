
# Steam Games Analytics

## Overview

This project aims to analyze data from Steam games to derive meaningful insights and patterns. It involves various data analysis techniques, including data cleaning, exploratory data analysis (EDA), and visualization. The goal is to understand trends in game popularity, user ratings, and other key metrics.

Additionally, the project incorporates machine learning (ML) and artificial intelligence (AI) techniques to enhance the analysis and provide deeper insights. Various ML models were trained to predict game performance metrics such as peak concurrent users (CCU), leveraging feature engineering and data preprocessing steps like target encoding and one-hot encoding.

Moreover, an interactive dashboard was created using Power BI, allowing for dynamic exploration of the data. This dashboard provides a comprehensive view of game statistics, seasonal trends, and top-performing games, offering a user-friendly interface for stakeholders to derive actionable insights.

## Project Structure

- **main.ipynb**: The Jupyter Notebook containing all the analysis and visualizations.
- **data**: Directory containing the raw and processed data files.
- **scripts**: Directory containing any auxiliary Python scripts used in the analysis.
- **dashboard.pbix**: The Power BI dashboard created using the analyzed data.

## Getting Started

### Prerequisites

To run the notebook, you need the following Python libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install these packages using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Running the Notebook

1. Clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/steam-games-analytics.git
```

2. Navigate to the project directory:

```bash
cd steam-games-analytics
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook main.ipynb
```

4. Run the cells in the notebook to execute the analysis.

## Analysis Summary

The analysis covers the following aspects:

- Data Cleaning: Handling missing values, duplicate entries, and data type conversions.
- Exploratory Data Analysis (EDA): Visualizing distributions, correlations, and trends.
- Machine Learning: Applying clustering or predictive models to the data.

## Power BI Dashboard

A comprehensive Power BI dashboard was created to visualize the analyzed data. The dashboard provides insights into various metrics, including the number of games released over the years, average game prices, and the most played games by current connected users (CCU). Below is a screenshot of the dashboard:

![Steam Games Analytics Dashboard](./dashboard.png)

## Results

- Insights into the most popular genres and games.
- Trends in game ratings and user reviews.
- Predictive models for game success based on various features.

## Conclusion

This project provides a comprehensive analysis of Steam games data, offering valuable insights for gamers, developers, and analysts interested in the gaming industry.

## Contributors

- Kanan Shukurlu

## License

This project is licensed under the MIT License - see the LICENSE file for details.
