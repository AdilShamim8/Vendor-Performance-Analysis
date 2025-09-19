# Vendor Performance Analysis

![GitHub repo size](https://img.shields.io/github/repo-size/AdilShamim8/Vendor-Performance-Analysis)
![GitHub last commit](https://img.shields.io/github/last-commit/AdilShamim8/Vendor-Performance-Analysis)

A comprehensive data analytics solution that leverages Python and Power BI to analyze vendor performance metrics, identify trends, and generate actionable insights for supply chain optimization and vendor management.

![Vendor Performance Preview](https://github.com/AdilShamim8/Vendor-Performance-Analysis/blob/main/Dashboard/vendor_performance.jpg)

## 📋 Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Key Features](#key-features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Analysis Workflow](#analysis-workflow)
- [Dashboard](#dashboard)
- [Insights](#insights)
- [Contributing](#contributing)
- [License](#license)

## 🔍 Overview

This project provides an end-to-end solution for analyzing vendor performance data. It includes data processing scripts, exploratory data analysis notebooks, interactive Power BI dashboards, and comprehensive reports. The analysis helps businesses evaluate vendor reliability, cost-effectiveness, delivery performance, and quality metrics to make data-driven decisions for vendor management.

## 📂 Project Structure

```
├── data/
│   └── vendor_sales_summary.csv       # Main dataset with vendor performance metrics
├── notebooks/
│   ├── Exploratory Data Analysis.ipynb    # Initial data exploration and visualization
│   └── Vendor Performance Analysis.ipynb  # Detailed vendor performance metrics analysis
├── scripts/
│   ├── get_vendor_summary.py          # Script to extract and process vendor summary data
│   └── ingestion_db.py                # Database ingestion and processing script
├── dashboard/
│   └── vendor_performance.pbix        # Interactive Power BI dashboard
├── reports/
│   └── Vendor Performance Report.pdf  # Comprehensive analysis report
└── README.md                          # Project documentation
```

## ✨ Key Features

- **Comprehensive Vendor Analysis**: Evaluate vendor performance across multiple KPIs
- **Interactive Dashboards**: Power BI visualizations for dynamic data exploration
- **Automated Data Processing**: Python scripts for data collection and preparation
- **In-depth Reporting**: Detailed analysis reports with actionable insights
- **Trend Identification**: Time-series analysis to identify performance patterns
- **Multi-dimensional Analysis**: Compare vendors across different metrics and categories

## 🛠️ Technologies Used

- **Python**: Data processing, analysis, and visualization
- **Pandas**: Data manipulation and analysis
- **Matplotlib/Seaborn**: Data visualization
- **Power BI**: Interactive dashboard creation
- **Jupyter Notebooks**: Exploratory data analysis
- **SQL**: Database queries (via Python)

## 🚀 Setup and Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/AdilShamim8/Vendor-Performance-Analysis.git
   cd Vendor-Performance-Analysis
   ```

2. **Set up Python environment**
   ```bash
   # Create and activate virtual environment (optional but recommended)
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   
   # Install required packages
   pip install pandas numpy matplotlib seaborn jupyter scikit-learn
   ```

3. **Open Power BI Dashboard**
   - Install Power BI Desktop (if not already installed)
   - Open `dashboard/vendor_performance.pbix`

## 📊 Usage

### Data Processing

```bash
# Run data extraction script
python scripts/get_vendor_summary.py

# Run database ingestion script
python scripts/ingestion_db.py
```

### Exploratory Analysis

1. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Navigate to the `notebooks/` directory
3. Open and run the notebooks to perform exploratory analysis

### Power BI Dashboard

The Power BI dashboard (`vendor_performance.pbix`) provides interactive visualizations of:
- Vendor performance comparison
- Delivery time analysis
- Cost-efficiency metrics
- Quality control statistics
- Trend analysis over time

## 🔄 Analysis Workflow

1. **Data Collection & Preparation**: Process raw vendor data using Python scripts
2. **Exploratory Analysis**: Identify patterns and outliers using Jupyter notebooks
3. **In-depth Analysis**: Calculate performance metrics and generate insights
4. **Visualization**: Create interactive dashboards in Power BI
5. **Reporting**: Generate comprehensive reports with findings and recommendations

## 📈 Dashboard

The Power BI dashboard features several interactive views:
- **Vendor Overview**: Summary metrics for all vendors
- **Performance Comparison**: Side-by-side vendor performance metrics
- **Trend Analysis**: Time-series visualizations of key metrics
- **Cost Analysis**: Price variations and cost-efficiency metrics
- **Quality Metrics**: Defect rates, returns, and quality scores

## 💡 Insights

The analysis provides actionable insights including:
- Identification of top and underperforming vendors
- Cost-saving opportunities through vendor optimization
- Delivery reliability patterns and improvement areas
- Quality control issues and potential solutions
- Seasonal variations in vendor performance
- Vendor risk assessment and mitigation strategies

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

Developed by [Adil Shamim](https://github.com/AdilShamim8)
