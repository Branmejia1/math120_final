Python Final Project: Upward Mobility in Fresno County
Project Overview
This project uses Python data analysis tools to explore upward mobility and inequality in Fresno County. Using public data from the Urban Institute’s Mobility Metrics / Fresno DRIVE dashboard

Project Structure
fresno_upward_mobility_project/
├── data_raw/                          # Original CSV files (downloaded from Urban Institute)
│   ├── 19_mobility-metrics_county_industry_longitudinal.csv
│   ├── 20_mobility-metrics_county_mothers_education_longitudinal.csv
│   ├── 64_mobility-metrics_place_income_longitudinal.csv
│   └── 67_mobility-metrics_place_tenure_longitudinal.csv
├── data/                              # (Optional) cleaned/filtered data saved by notebook
│   └── *.csv
├── notebook.ipynb                     # Main analysis notebook (Google Colab / Jupyter)
└── README.md                          # This file

Requirements
Python 3.7+
pandas
matplotlib
numpy
jupyter (for local execution)
Installation and Setup
Local Execution
Clone this repository:

git clone https://github.com/Branmejia1/math120_final.git
cd python_final_project
Install required packages (if needed):

pip install pandas matplotlib numpy jupyter
Launch Jupyter Notebook:

jupyter notebook notebook.ipynb
Google Colab Execution
Open Google Colab
Upload the notebook.ipynb file or connect to your GitHub repository
Run the first cell to automatically set up the environment
Data Description
All data comes from the Urban Institute Mobility Metrics / Fresno DRIVE dashboard. Data Includes Industry data, Mothers' Education & infant Health, Place Income / Upward Mobility (Fresno City), and Housing Tenure & Affordability
Analysis Features
Data loading and cleaning
Exploratory analysis and summary statistics
Data visualization with matplotlib
Connection to upward mobility
Key Learning Objectives Demonstrated
File I/O operations with pandas
Data cleaning and preprocessing
Data merging and joining
Statistical analysis
Data visualization
Function creation and modular programming
Environment compatibility (local vs. cloud)
Usage
Run all cells in notebook.ipynb sequentially. The notebook will:

Set up the environment automatically
Load and clean the raw data
Perform statistical analysis
Generate visualizations
Save processed data to the data/ folder
Author
Brandon Mejia
Math 120 - Fall 2025 
