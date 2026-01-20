📊 Shopify Trending Products 2025 - Data Analysis Project
📋 Project Overview
A comprehensive data analysis of 1,000 trending Shopify products from 2025, examining pricing strategies, sales performance, trend patterns, and predictive modeling to identify success factors in e-commerce.

🎯 Objectives
Analyze product pricing strategies and their impact on sales

Identify top-performing categories and trend sources

Build predictive models for product success

Generate actionable business insights for e-commerce optimization

Create a reproducible analysis pipeline

📁 Project Structure
text
shopify_trending_product_analysis/
├── data/
│   ├── raw/                          # Original dataset
│   │   └── shopify_trending_products_2025.csv
│   └── processed/                    # Cleaned and transformed data
│       └── shopify_products_processed.csv
├── visualizations/                   # All generated plots and charts
│   ├── price_analysis_showcase.png
│   ├── advanced_analysis_showcase.png
│   └── individual_plots/             # Individual visualization files
│       ├── 1_price_distribution.png
│       ├── 2_price_vs_sales.png
│       ├── 3_price_by_category.png
│       ├── 4_correlation_heatmap.png
│       └── 5_top_categories.png
├── reports/                          # Analysis reports and summaries
│   └── analysis_summary.csv
├── notebooks/                        # Jupyter notebooks
│   └── shopify_trending_products_analysis.ipynb
├── src/                              # Source code modules
│   ├── __init__.py
│   ├── data_loader.py
│   ├── preprocessing.py
│   └── analysis.py
├── requirements.txt                  # Python dependencies
├── README.md                         # This file
└── .gitignore                        # Git ignore file
🚀 Quick Start
Prerequisites
Python 3.8+

Jupyter Notebook

Git

Installation
Clone the repository:

bash
git clone https://github.com/snow6060/shopify-trending-products-analysis.git
cd shopify-trending-products-analysis
Create a virtual environment (optional but recommended):

bash
python -m venv venv
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate
Install dependencies:

bash
pip install -r requirements.txt
Run the analysis:

bash
# Launch Jupyter Notebook
jupyter notebook notebooks/shopify_trending_products_analysis.ipynb
📊 Dataset Description
Original Data Features:
Product_ID: Unique identifier for each product

Product_Name: Name of the product

Category & Subcategory: Product classification

Estimated_Total_Units_Sold_in_2025: Projected sales volume

Estimated_Revenue_in_2025_USD: Projected revenue

Price_Range_USD: Price range (min-max)

Trend_Score: Popularity score (0-100)

Trend_Source: Source of trend data

Notes: Additional information

Derived Features (Created in Analysis):
Price_Min, Price_Max, Price_Avg: Extracted from price range

Success_Score: Composite score combining trend and sales

Price_Category: Budget/Mid-Range/Premium/Luxury classification

Revenue_Per_Unit: Revenue divided by units sold

Price_Range_Width: Difference between max and min price

🔍 Analysis Highlights
Key Findings:
Price Optimization: Identified optimal price range for maximum success

Category Performance: Discovered top-performing product categories

Trend Sources: Analyzed most effective marketing channels

Success Predictors: Built ML model to predict product success

Business Insights: Generated actionable recommendations

Visualizations Created:
Price distribution analysis

Category performance charts

Correlation heatmaps

Success prediction models

Multivariate analysis plots

🛠️ Technical Implementation
Libraries Used:
Pandas & NumPy: Data manipulation

Matplotlib & Seaborn: Data visualization

Scikit-learn: Machine learning models

SciPy: Statistical analysis

Analysis Pipeline:
Data Loading & Cleaning: Extract and clean price data

Feature Engineering: Create success metrics and categories

Exploratory Analysis: Statistical insights and visualizations

Model Building: Predictive modeling with Random Forest

Insight Generation: Business recommendations

📈 Results
Model Performance:
Random Forest Regressor: R² = [Your Model Score]

Top Predictors: [Most important features]

Accuracy: [Model accuracy metrics]

Business Recommendations:
Pricing Strategy: Optimal price range identified

Category Focus: Recommended product categories

Marketing Channels: Most effective trend sources

Product Development: Features that drive success

📝 Usage Examples
1. Run Complete Analysis:
python
# Execute the Jupyter notebook cells in order
# All visualizations and reports will be generated automatically
2. Make Predictions:
python
# Use the trained model to predict new product success
example_product = {
    'Price_Avg': 75.0,
    'Trend_Score': 85.0,
    'Estimated_Total_Units_Sold_in_2025': 50000
}
predicted_success = model.predict(example_product)
🧪 Testing
bash
# Run tests (if available)
python -m pytest tests/
🤝 Contributing
Contributions are welcome! Please follow these steps:

Fork the repository

Create a feature branch (git checkout -b feature/AmazingFeature)

Commit changes (git commit -m 'Add AmazingFeature')

Push to branch (git push origin feature/AmazingFeature)

Open a Pull Request

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🙏 Acknowledgments
Dataset source: Kaggle

Inspiration from e-commerce analytics projects

Open-source community for amazing libraries

📧 Contact
Inzamam Ul Haque - inzh@itu.dk
Project Link: https://github.com/snow6060/shopify-trending-products-analysis

