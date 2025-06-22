# World Happiness Report: Exploratory Data Analysis & Visualization

## Project Overview

This project delves into the **World Happiness Report** dataset to uncover fascinating insights into global well-being. Through extensive Exploratory Data Analysis (EDA) and compelling data visualizations, we explore the factors contributing to happiness across various countries and years. This project aims to understand trends, correlations, and key drivers of happiness on a global scale.


## Dataset

The analysis is based on the **World Happiness Report** data, which typically includes:

  * **Happiness Score (Ladder Score):** The primary measure of happiness, based on respondents' evaluations of their current life on a scale of 0 to 10.
  * **GDP per Capita:** Economic production per person.
  * **Social Support:** Perceived availability of social support in times of trouble.
  * **Healthy Life Expectancy:** Average years of healthy life.
  * **Freedom to Make Life Choices:** Satisfaction with personal freedom.
  * **Generosity:** Recent donations to charity, adjusted for GDP per capita.
  * **Perceptions of Corruption:** Perceived corruption in government and business.
  * **Country Name, Region, and Year.**

The datasets are sourced from the official [World Happiness Report website](https://worldhappiness.report/data/) or readily available on platforms like Kaggle.

## Key Questions Explored

This project addresses various questions to understand the nuances of global happiness:

  * How has the global happiness score changed over the years?
  * Which countries consistently rank highest/lowest in happiness?
  * What is the correlation between happiness and factors like GDP per capita, social support, and healthy life expectancy?
  * Are there regional differences in happiness levels and their contributing factors?
  * How do freedom and generosity influence a country's happiness score?
  * What is the impact of corruption on perceived happiness?
  * (Add any other specific questions you addressed in your EDA)

## Methodology

The project follows a standard data analysis workflow:

1.  **Data Collection:** Sourcing World Happiness Report datasets for multiple years.
2.  **Data Cleaning & Preprocessing:**
      * Handling missing values.
      * Standardizing column names across different years.
      * Merging datasets to create a comprehensive view.
      * (Mention any specific data transformations like log transformations for GDP, if applied).
3.  **Exploratory Data Analysis (EDA):**
      * Descriptive statistics to understand data distributions.
      * Correlation analysis to identify relationships between variables.
      * Time-series analysis to observe happiness trends over time.
4.  **Data Visualization:**
      * Creating various plots (e.g., scatter plots, bar charts, heatmaps, line plots, box plots) to effectively communicate insights.
      * Utilizing subplots and interactive features where appropriate.

## Key Findings & Visualizations

  * **[Example 1: Global Happiness Trend Over Years]**
        
      * **Insight:** "The average global happiness has shown a slight [increase/decrease/stability] over the past decade, with notable fluctuations in [mention specific years/events if applicable]."

  * **[Example 2: Top 10 Happiest Countries]**

      * **Insight:** "Countries like [Country A], [Country B], and [Country C] consistently rank among the happiest, often characterized by strong social support systems and high GDP per capita."

  * **[Example 3: Correlation Heatmap]**

      * **Insight:** "The heatmap clearly indicates a strong positive correlation between `Happiness Score` and `GDP per Capita`, `Social Support`, and `Healthy Life Expectancy`, highlighting their significant impact on overall well-being."

  * **[Example 4: Regional Happiness Distribution]**

      * **Insight:** "North America and Western Europe generally exhibit higher happiness scores, while certain regions in Africa and Asia face greater challenges in well-being."

  

## Technologies Used

  * **Python:** The primary programming language for data analysis.
  * **Pandas:** For data manipulation and analysis.
  * **NumPy:** For numerical operations.
  * **Matplotlib:** For creating static and interactive visualizations.
  * **Seaborn:** For enhanced statistical data visualization.
  * **Jupyter Notebook:** For interactive development and presentation of the analysis.

## How to Run the Project

To run this project locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/kamya2544/World-Happiness-Report-EDA.git
    cd World-Happiness-Report-EDA
    ```
2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: `venv\Scripts\activate`
    ```
3.  **Install the required libraries:**
    ```bash
    pip install -r requirements.txt
    ```
    (You'll need to create a `requirements.txt` file by running `pip freeze > requirements.txt` after installing all libraries you used in your notebook.)
4.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
5.  Open the `World_Happiness_Report_EDA.ipynb`  notebook and run the cells.

## Future Enhancements

  * Incorporate more years of data (if available).
  * Perform time-series forecasting of happiness scores.
  * Build a machine learning model to predict happiness scores based on the factors.
  * Create an interactive dashboard using tools like Dash or Streamlit.
  * Conduct sentiment analysis on qualitative data related to happiness (if available).
  * Deep dive into specific country or regional analyses.

## Contributing

Contributions are welcome\! If you have suggestions for improvements, new features, or find any issues, please feel free to:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/YourFeature`).
3.  Make your changes.
4.  Commit your changes (`git commit -m 'Add some feature'`).
5.  Push to the branch (`git push origin feature/YourFeature`).
6.  Open a Pull Request.


## Contact

If you have any questions or feedback, feel free to reach out:

  * **Kamya Mehra** - (https://github.com/kamya2544)
  * kmehra_be22@thapar.edu

-----
