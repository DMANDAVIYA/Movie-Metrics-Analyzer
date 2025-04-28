# Movie Dataset Analysis

This Python project analyzes a movie dataset to understand trends and correlations between features like budget, gross earnings, and release year. The project uses Python libraries for data processing, cleaning, and visualization.

## Features

1. **Data Analysis**:
   - Identifies and handles missing values.
   - Converts data types for better compatibility.
   - Creates new features like `YearCorrect` from existing data.

2. **Correlation Investigation**:
   - Hypothesizes relationships between variables such as `budget` and gross earnings.
   - Visualizes trends using scatter plots and regression analysis.

3. **Visualization**:
   - Scatter plots for budget vs. gross earnings.
   - Regression plots to highlight correlations.

## Technologies Used

- **Python**:
  - `pandas`: For data manipulation.
  - `numpy`: For numerical operations.
  - `matplotlib`: For creating plots.
  - `seaborn`: For advanced visualizations.

## Dataset

The analysis is performed on a dataset obtained from Kaggle. The dataset contains columns such as:
- `budget`: The budget of the movie.
- `gross`: The gross earnings.
- `company`: The production company.
- `country`: The country of production.
- `released`: The release date.
- `runtime`: The runtime of the movie.
- `genre`: The genre of the movie.

## Usage Instructions

1. Clone the repository:
   

2. Install dependencies:
   pip install -r requirements.txt

3. Run the Jupyter Notebook:
   Open Python_Correlation.ipynb in your browser and execute the cells.

**Outputs**
Scatter plots showing trends between budget and gross earnings.
Regression plots highlighting the strength of correlations.
Insights into missing data and data cleaning processes.
Conclusion:
Budget and Gross Correlation:

1. A strong positive correlation exists between a movie's budget and its gross earnings.
Higher-budget movies tend to generate more revenue, as evidenced by scatter and regression plots.
Data Cleaning Insights:

2. Missing values in certain columns highlight the need for preprocessing in future analyses.
Type conversions were necessary for numerical columns like budget and gross to ensure consistency.
Year Analysis Potential:

3. Extracting release years (YearCorrect) opens possibilities for analyzing trends over time, such as how budget allocation and   revenue patterns have evolved.
