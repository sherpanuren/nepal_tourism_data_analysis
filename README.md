# Nepal Tourism Data Analysis

## About This Project

This project analyzes Nepal's tourism arrival data to help tourism stakeholders make better decisions. It processes tourist arrival data from multiple sources and creates easy-to-understand visualizations and dashboards.

## What's Inside

```
tourism-analysis/
├── 📁 datasets/          # Your raw CSV files go here
├── 📁 notebooks/         # Jupyter notebooks with analysis code
├── 📁 outputs/          # Cleaned and merged data files
└── 📁 powerbi/          # Files ready for Power BI dashboards
```

## How to Use

### 1. Set Up Your Data
- Put all your CSV files in the `datasets/` folder
- Make sure they have similar column names

### 2. Run the Analysis
Open `Tourism_Analysis.ipynb` in Jupyter Notebook and run all cells. This will:
- Merge all your CSV files
- Clean the data
- Create useful charts and insights
- Prepare files for Power BI

### 3. Create Power BI Dashboard
1. Open Power BI Desktop
2. Import the files from the `powerbi/` folder
3. Connect the tables in the Model view:
   - Link Date columns between tables
   - Link Nationality columns
4. Build your dashboard with:
   - Arrival trends over time
   - Top source countries
   - Seasonality patterns
   - Recovery analysis

## Key Analysis Areas

- **Market Trends**: See which countries send the most tourists
- **Seasonality**: Find busy vs slow months
- **Recovery**: Track post-COVID tourism recovery
- **Growth Opportunities**: Identify fast-growing markets

## Tips for Better Results

1. **Keep Data Consistent**: Make sure all CSV files have the same column structure
2. **Update Regularly**: Add new monthly data to the datasets folder
3. **Customize for Your Needs**: Adjust the code for your specific questions
