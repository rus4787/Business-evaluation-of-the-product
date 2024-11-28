# Business-evaluation-of-the-product

## Overview

This repository contains a Jupyter Notebook (`Marina_product.ipynb`) that performs an in-depth analysis of a product dataset for Marina. The notebook is designed to help understand the sales dynamics, product types, and various metrics related to the product offerings. The analysis is structured to provide insights into what is being sold, the types of sales, average sales values, and other key performance indicators.

## Table of Contents

1. [Introduction](#introduction)
2. [Data Sources](#data-sources)
3. [Analysis Structure](#analysis-structure)
4. [Key Findings](#key-findings)
5. [Dependencies](#dependencies)
6. [How to Use](#how-to-use)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction

The notebook is aimed at providing a comprehensive analysis of the product sales data for Marina. It covers various aspects such as the types of products sold, the average sales values, and the conversion rates for different product types. The analysis is structured in a way that each section builds upon the previous one, leading to a holistic understanding of the product sales performance.

## Data Sources

The data used in this analysis is sourced from two main files:
- `marina_table_price.parquet`
- `marina_table_price_nomenklatura.parquet`

These files contain detailed information about the products, sales, and related metrics.

## Analysis Structure

The analysis is structured into several sections, each focusing on a specific aspect of the product sales data:

1. **Introduction to Marina**: Provides an overview of the product offerings and the nature of the sales.
2. **Data Loading and Preparation**: Loads the necessary data and prepares it for analysis.
3. **Product Overview**: Analyzes what products are being sold, including types of sales and average sales values.
4. **Sales Analysis**: Examines the sales dynamics, including the number of sales, average prices, and conversion rates.
5. **Time Series Analysis**: Analyzes the sales performance over time.
6. **Package and Individual Sales Analysis**: Provides insights into the characteristics of package and individual sales.
7. **Sales Improvement Recommendations**: Offers suggestions for improving sales performance based on the analysis.

## Key Findings

- **Total Sales**: The organization has made a total of 69,860 sales, generating a revenue of 858,964,612 rubles.
- **Sales Types**: The majority of sales are individual sales (69,491) compared to package sales (369).
- **Average Sales Values**: The average price of a package sale is significantly higher than that of an individual sale.
- **Conversion Rates**: The conversion rate for package sales is lower compared to individual sales, indicating potential areas for improvement.

## Dependencies

The notebook requires the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- joblib

You can install these dependencies using pip:

```bash
pip install pandas numpy matplotlib seaborn joblib
```

## How to Use

1. **Clone the Repository**: Clone this repository to your local machine using the following command:

   ```bash
   git clone https://github.com/your-username/marina-product-analysis.git
   ```

2. **Navigate to the Directory**: Move into the project directory:

   ```bash
   cd marina-product-analysis
   ```

3. **Open the Notebook**: Launch Jupyter Notebook and open the `Marina_product.ipynb` file:

   ```bash
   jupyter notebook
   ```

4. **Run the Notebook**: Execute the cells in the notebook to perform the analysis.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Feel free to customize this README file to better fit your project's specific details and requirements.
