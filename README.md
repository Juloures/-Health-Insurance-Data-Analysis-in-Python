# Health Insurance Data Analysis

## Project Overview
This project is designed to analyze health insurance data to help optimize pricing strategies and understand customer profiles. The analysis includes demographic data, health claims, risk patterns, and correlations between variables influencing insurance pricing.

## Features
- **Data Loading**: Handles CSV data files from public Google Drive links or direct URLs.
- **Exploratory Data Analysis (EDA)**: 
  - Displays first rows of data, information about data types, and descriptive statistics.
  - Generates visualizations such as histograms, bar charts, pie charts, line plots, scatter plots, boxplots, and a correlation matrix.

## Functions
### `carregar_dados(url, tipo_arquivo='CSV')`
- Loads data from CSV files, including Google Drive links.
- Processes data into a DataFrame for analysis.

### `analise_exploratoria(df)`
- Displays the first rows of data and descriptive statistics.
- Calls visualization functions to create various types of plots.

### `plot_histograma(df)`
- Generates a histogram for a numeric variable.

### `plot_grafico_de_barras(df)`
- Generates a bar chart for categorical variables.

### `plot_grafico_de_pizza(df)`
- Generates a pie chart for categorical variables.

### `plot_grafico_de_linha(df)`
- Creates a line plot comparing two numeric variables.

### `plot_grafico_de_dispersao(df)`
- Generates a scatter plot to analyze relationships between two numeric variables.

### `plot_boxplot(df)`
- Creates a boxplot to visualize numeric variable distributions.

### `identificacao_correlacoes(df)`
- Displays a correlation matrix for numeric variables to identify relationships.

### `analise_especialista()`
- Adds personalized analysis and conclusions based on the exploratory analysis results.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/health-insurance-analysis.git
   cd health-insurance-analysis
