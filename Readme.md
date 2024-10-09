# Customer Segmentation using Clustering

## Overview

Customer segmentation is the process of dividing a company's customer base into groups that reflect similarities among customers in each group. This project applies clustering techniques, specifically **K-Means Clustering**, to perform customer segmentation. The goal is to identify distinct customer segments based on their purchasing behavior and demographics, which can be used for targeted marketing strategies.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)



## Dataset

The dataset used in this project contains information about customers, including demographic data (e.g., age, income) and purchasing patterns. It is stored in the `data/customers.csv` file.

The dataset contains the following columns:
- **CustomerID**: Unique identifier for each customer
- **Age**: Age of the customer
- **Annual Income (k$)**: Annual income of the customer in thousands of dollars
- **Spending Score (1-100)**: Score assigned to the customer based on their spending behavior

### Sample Data:

| CustomerID | Age  | Annual Income (k$) | Spending Score (1-100) |
|------------|------|--------------------|------------------------|
| 1          | 19   | 15                 | 39                     |
| 2          | 21   | 15                 | 81                     |
| 3          | 20   | 16                 | 6                      |

## Installation

To get started with this project, follow the instructions below.

### Prerequisites

- Python 3.7+
- Jupyter Notebook (for running the notebooks)

### Step-by-step Guide

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/Customer-Segmentation-using-Clustering.git
   cd Customer-Segmentation-using-Clustering
   ```

2. **Create a virtual environment (optional but recommended):**

   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```

3. **Install the required dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run Jupyter Notebook:**

   ```bash
   jupyter notebook
   ```

5. **Open the notebook and run the analysis:**

   - Open `EDA.ipynb` for exploratory data analysis
   - Open `Clustering.ipynb` for clustering implementation

## Usage

You can use this project to segment customers by following these steps:

1. Perform **Exploratory Data Analysis (EDA)** to understand the patterns in customer behavior.
2. Apply **K-Means Clustering** to segment customers based on their spending habits and demographics.
3. Visualize the clusters to interpret the different customer groups and their characteristics.

## Results

After running the clustering algorithm, you'll obtain different customer segments that can be visualized in a scatter plot, similar to the example below:

![Clusters](output.png)

Each color in the plot represents a distinct customer segment. This helps in understanding the behaviors and traits of different groups of customers.

## Technologies Used

- **Python**: Core programming language
- **Pandas**: For data manipulation and analysis
- **Matplotlib & Seaborn**: For data visualization
- **Scikit-learn**: For clustering algorithms (K-Means)

## Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Please ensure that your code follows best practices and is well-documented.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

This README serves as a general guide. You can further personalize it by adjusting the dataset details, results, and contributing guidelines based on your specific project.