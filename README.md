# Python Final Project: Upward Mobility in Fresno County

## Project Overview
This project uses Python data analysis tools to explore upward mobility and inequality in Fresno County. Using public data from the Urban Institute’s Mobility Metrics / Fresno DRIVE dashboard

## Project Structure
```

├── data_raw/                          # Original CSV files (downloaded from Urban Institute)
│   ├── 19_mobility-metrics_county_industry_longitudinal.csv
│   ├── 20_mobility-metrics_county_mothers_education_longitudinal.csv
│   ├── 64_mobility-metrics_place_income_longitudinal.csv
│   └── 67_mobility-metrics_place_tenure_longitudinal.csv
├── data/                              # (Optional) cleaned/filtered data saved by notebook
│   └── *.csv
├── notebook.ipynb                     # Main analysis notebook (Google Colab / Jupyter)
└── README.md                          # This file


```

## Requirements
- Python 3.7+
- pandas
- matplotlib
- numpy
- jupyter (for local execution)

## Installation and Setup

### Local Execution
1. Clone this repository:
   ```bash
   https://github.com/Branmejia1/math120_final/
   cd python_final_project
   ```

2. Install required packages (if needed):
   ```bash
   pip install pandas matplotlib numpy jupyter
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook notebook.ipynb
   ```

### Google Colab Execution
1. Open [Google Colab](https://colab.research.google.com/)
2. Upload the `notebook.ipynb` file or connect to your GitHub repository
3. Run the first cell to automatically set up the environment

## Data Description
Data loading and cleaning
Exploratory analysis and summary statistics
Data visualisation with matplotlib
Connection to upward mobility


## Analysis Features
- Data loading and cleaning
- Data merging operations
- Summary statistics calculation
- Sales analysis by category and region
- Data visualization with matplotlib
- Modular code organization

## Key Learning Objectives Demonstrated
- File I/O operations with pandas
- Data cleaning and preprocessing
- Data merging and joining
- Statistical analysis
- Data visualisation
- Function creation and modular programming
- Environment compatibility (local vs. cloud)

## Usage
Run all cells in `notebook.ipynb` sequentially. The notebook will:
1. Set up the environment automatically
2. Load and clean the raw data
3. Perform statistical analysis
4. Generate visualisations
5. Save processed data to the `data/` folder

## Author
Brandon Mejia
Math 120 - Fall 2025 
