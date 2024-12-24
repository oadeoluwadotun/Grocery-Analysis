# Grocery Dataset Analysis and Dashboard Project

## Overview
This project analyses grocery-related data to derive insights into consumer trends, product pricing, and sustainability features. Using Python for data cleaning and exploratory analysis, and Power BI for visualization, this project aims to demonstrate how data analysis can inform sustainability efforts in retail.

## Key Objectives
- Understand trends in grocery prices, discounts, and consumer ratings.
- Identify sustainable products using feature engineering.
- Build an interactive Power BI dashboard to communicate insights.

## Tools and Technologies
- **Python**: Data cleaning, feature engineering, and exploratory analysis.
  - Libraries: Pandas, NumPy, Matplotlib, Seaborn
- **Power BI**: Dashboard creation and visualizations.

## Dataset
The dataset contains the following key columns:
- **Sub Category**: Product classification.
- **Price**: Product price (post-cleaning).
- **Discount**: Discounts applied.
- **Rating**: Customer ratings.
- **Title**: Product names.
- **Currency**: Price currency.
- **Feature**: Product-specific attributes.
- **Product Description**: Details about the product.

### Source
The dataset was sourced from Kaggle and provides information about grocery items.

## Process

### 1. Data Analysis and Cleaning (Python)
- **Loading the Dataset**:
  Loaded into Pandas for data wrangling.

- **Data Cleaning**:
  - Missing values handled (e.g., imputing prices and ratings).
  - Duplicates removed.
  - `Price` and `Discount` fields cleaned and converted to numerical formats.

- **Feature Engineering**:
  - Added a `Sustainability` column, marking items as sustainable or not based on keywords (e.g., "organic", "eco-friendly").

- **Exploratory Data Analysis (EDA)**:
  - Summary statistics of price, rating, and discount.
  - Visualizations of key trends (e.g., `Price` vs `Rating`, `Sustainable` vs `Non-sustainable`).

### 2. Visualization and Dashboard (Power BI)
[Planned]
- Build an interactive dashboard with:
  - Sales trends by sub-category.
  - Sustainability analysis.
  - Insights from ratings and pricing.

## Key Results
1. Insights into price ranges and their correlation with ratings.
2. Patterns in discounts and their impact on ratings and potential purchases.
3. Identification of sustainable products and trends in their consumption.

## Files in the Repository
```
├── data/
│   ├── raw_grocery_data.csv     # Original dataset.
│   ├── cleaned_grocery_data.csv # Post-cleaning dataset for Power BI.
│
├── notebooks/
│   ├── data_cleaning.ipynb       # Jupyter notebook with data cleaning and EDA.
│
├── README.md                     # Project documentation.
│
├── requirements.txt              # Python dependencies.
```

## Next Steps
- Finalize visualizations and insights in Power BI.
- Share the Power BI dashboard with stakeholders.

## How to Use the Repository
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Grocery-Analysis.git
   ```

2. Install Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook for data analysis:
   ```bash
   jupyter notebook notebooks/data_cleaning.ipynb
   ```

4. Explore the `cleaned_grocery_data.csv` file with Power BI.

## Contributing
Feedback and contributions are always welcome. Please open an issue or submit a pull request for any suggestions.

## Acknowledgments
Thanks to Kaggle for providing the dataset and to God for the strength and insight to work on this project.

---
*Developed by [Adeoluwa Ogundele](https://github.com/oadeoluwadotun)*
