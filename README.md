# 🚗 Automobile Sales Analysis & Interactive Dashboard

This project provides a comprehensive analysis of automobile sales data, exploring the impact of economic factors such as recession, GDP, unemployment rate, advertising expenditure, and seasonality on vehicle sales. It is divided into two parts: static visualizations and an interactive dashboard.

## 📁 Dataset

The project uses a dataset named `Automobile.csv` which contains the following key columns:

- `Date`, `Year`, `Month`
- `Automobile_Sales`
- `Vehicle_Type`
- `Price`, `Advertising_Expenditure`
- `GDP`, `Growth_Rate`, `unemployment_rate`
- `Seasonality_Weight`, `Consumer_Confidence`
- `Recession`, `Competition`

## 📊 Part 1: Static Visualizations (Matplotlib, Seaborn, Pandas)

A series of visualizations created to answer key business questions and trends:

- `Line_plot_1.png`: Yearly Automobile Sales (Line chart)
- `Line_plot_2.png`: Sales Trends by Vehicle Type during Recession
- `Bar_Chart.png`: Seaborn comparison of Vehicle Type Sales (Recession vs Non-Recession)
- `Subplot.png`: Subplot of GDP during Recession vs Non-Recession
- `Bubble.png`: Bubble Plot showing impact of Seasonality on Sales
- `Scatter.png`: Scatter Plot between Vehicle Price and Sales (Recession Period)
- `Pie_1.png`: Advertising Expenditure (Recession vs Non-Recession)
- `Pie_2.png`: Advertisement Expenditure per Vehicle Type (Recession)
- `Line_plot_3.png`: Unemployment Rate vs Sales per Vehicle Type

## 📈 Part 2: Interactive Dashboard (Plotly Dash)

A responsive web dashboard to dynamically explore the dataset using dropdown filters and callbacks.

### Features:

- Dropdown filters to choose analysis type (Recession or Yearly)
- Interactive charts (line plots, bubble plots, pie charts, etc.)
- Callback functions to update outputs based on user input

### Files:

- `app.py`: Main Dash application
- `Title.png`: Dashboard title screenshot
- `Dropdown.png`: Dropdown components
- `outputdiv.png`: Output division with class/id setup
- `Callbacks.png`: Screenshot of working callbacks
- `RecessionReportgraphs.png`: Recession-related visualizations
- `YearlyReportgraphs.png`: Year-based sales visualizations

## 🛠️ Tools Used

- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- Plotly Express, Dash

## 📌 Getting Started

Clone the repository and install dependencies:

```bash
pip install pandas numpy matplotlib seaborn plotly dash
