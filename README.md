# Ecommerce Sales ETL and Data Visualization

This project involves extracting, transforming, and loading (ETL) ecommerce sales data, followed by data visualization to gain insights into business performance, customer behavior, and revenue trends.

## Notebooks

### [EcommerceSalesETL.ipynb](EcommerceSalesETL.ipynb)

This notebook performs the ETL process on the ecommerce sales data:

- **Extract**: Load the raw data into a DataFrame.
- **Transform**: Clean and preprocess the data.
- **Load**: Save the cleaned data to a CSV file and load it into a SQLite database.

### [DataVisualization.ipynb](DataVisualization.ipynb)

This notebook explores the cleaned dataset through various data visualizations:

- **Sales Distribution**: Analyze the distribution of total sales.
- **Sales Over Time**: Analyze sales trends over time.
- **Top Selling Products**: Identify the most sold products.
- **Revenue by Country**: Visualize revenue contribution by country.
- **Customer Purchasing Patterns**: Analyze customer purchasing behavior.
- **Revenue Trends Analysis**: Detect seasonal demand shifts and sales performance fluctuations.
- **Average Order Value (AOV) Tracking**: Track AOV over time.
- **Customer Retention Rate Analysis**: Analyze customer retention rates.
- **Peak Shopping Hours**: Identify peak shopping hours.
- **Customer Segmentation (RFM Analysis)**: Segment customers based on recency, frequency, and monetary value.

## Getting Started

### Prerequisites

- Python 3.11.2
- Jupyter Notebook
- Required Python packages: `pandas`, `matplotlib`, `seaborn`, `numpy`, `sqlalchemy`, `ucimlrepo`

### Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/zainhaidar16/EcommerceSalesETL.git
    cd EcommerceSalesETL
    ```

2. Install the required packages:

    ```sh
    pip install -r requirements.txt
    ```

3. Open the notebooks in Jupyter:

    ```sh
    jupyter notebook
    ```

## Usage

1. Run the [EcommerceSalesETL.ipynb](EcommerceSalesETL.ipynb) notebook to perform the ETL process.
2. Run the [DataVisualization.ipynb](DataVisualization.ipynb) notebook to visualize the cleaned data.

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## Citation

D. Chen. "Online Retail," UCI Machine Learning Repository, 2015. [Online]. Available: https://doi.org/10.24432/C5BW33.

## Acknowledgments

- The data used in this project is sourced from the UCI Machine Learning Repository.