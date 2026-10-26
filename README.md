# Logistics Delivery Analysis

Strategic planning and data exploration for an urban food-delivery platform,
using Python.

## Project overview
This project analyses 1,000 food delivery orders to understand what affects
delivery time, defines logistics KPIs, and builds a model to predict delivery time.

## Files
- `logistics_analysis.ipynb`: Python notebook with data cleaning, exploratory
  analysis, KPIs and predictive modelling
- `Food_Delivery_Times.csv`: dataset (1,000 orders, 9 columns)
- `Logistics_Strategic_Planning_Report.docx`: strategic planning report

## Key KPIs
- Average delivery time: 56.73 minutes
- On-time delivery rate (60 minutes or less): 58.5%
- Delivery minutes per km: 5.64
- High-traffic delay compared with low traffic: 11.92 minutes

## Main findings
- Distance is the strongest driver of delivery time (correlation 0.78).
- High traffic and snowy weather cause the biggest drops in on-time delivery.
- Linear Regression predicts delivery time with an average error of about
  5.9 minutes (R² = 0.826) and performed better than Random Forest.

## How to run
1. Install Python and the libraries: `pip install pandas numpy matplotlib seaborn scikit-learn jupyter`
2. Keep the notebook and the CSV file in the same folder.
3. Open `logistics_analysis.ipynb` in Jupyter and select Kernel > Restart & Run All.

## Author
Maniratan Raj
