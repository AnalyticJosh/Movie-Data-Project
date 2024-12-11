# Movie Data Analysis Project

## **Overview**

This project explores a comprehensive dataset of movies to uncover insights about industry trends, box office performance, and audience preferences. Using Python and its data analysis libraries, the project identifies key factors contributing to successful movies and provides actionable insights for decision-making.

## **Objectives**

- Analyze trends in movie production and performance.
- Explore correlations between budget, genres, and box office success.
- Identify patterns in audience ratings and critical reviews.

## **Key Features**

- **Exploratory Data Analysis (EDA)**: Summarizes and visualizes key attributes like genres, budgets, and revenues.
- **Trend Analysis**: Investigates temporal patterns in movie releases and earnings.
- **Correlation Analysis**: Explores relationships between variables such as budget and box office success.
- **Visualization**: Generates charts and graphs for better data interpretation.

## **Technologies Used**

- **Python**: Main language for analysis.
- **Libraries**:
  - `Pandas` and `NumPy`: Data manipulation and analysis.
  - `Matplotlib` and `Seaborn`: Visualization.
  - `SciPy` or `Statsmodels`: Correlation and regression analysis.
  - `Jupyter Notebook`: Interactive environment for coding and visual exploration.

## **Dataset Information**

- The dataset includes:
  - Movie titles and release years.
  - Budgets, revenues, and profit margins.
  - Genres, cast, and director information.
  - Audience ratings and critic scores.

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/AnalyticJosh/Movie-Data-Project.git
   cd Movie-Data-Project
   ```

2. **Set Up the Environment**:

   - Ensure Python (3.7 or higher) is installed.
   - Install required libraries:
     ```bash
     pip install -r requirements.txt
     ```

3. **Run the Notebook**:

   - Open `Movie Data Project.ipynb` in Jupyter Notebook.
   - Execute cells sequentially to preprocess data, analyze trends, and generate insights.

## **Sample Analysis**

### Budget vs. Revenue Correlation

```python
import seaborn as sns
import matplotlib.pyplot as plt

sns.scatterplot(x='Budget', y='Revenue', data=movies_data)
plt.title('Budget vs. Revenue Correlation')
plt.show()
```

### Top Genres by Revenue

```python
movies_data.groupby('Genre')['Revenue'].mean().sort_values(ascending=False).plot(kind='bar')
plt.title('Top Genres by Average Revenue')
plt.show()
```

## **Results and Insights**

- Key findings:
  - Action and Adventure genres generate the highest revenues on average.
  - Movies with budgets above \$100M tend to have higher profitability margins.
  - Audience ratings and critic scores show moderate correlation with box office success.
- Suggested strategies:
  - Invest more in high-performing genres like Action and Adventure.
  - Allocate marketing budgets based on audience rating trends.

## **Visualizations**

- **Revenue Trends Over Time**: Line chart showing box office trends by year.
- **Top Grossing Genres**: Bar chart of genres sorted by average revenue.
- **Budget vs. Revenue**: Scatter plot showing correlation between production budgets and revenue.

## **Contributions**

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a Pull Request.

## **License**

This project is licensed under the MIT License.

---

For further inquiries or feedback, please contact [Joshua Amusan](mailto\:joshuaanalyst2@gmail.com).

