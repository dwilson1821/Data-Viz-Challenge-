# Data Visualization Challenge: Pymaceuticals Inc.  

## Background  

Welcome to **Pymaceuticals, Inc.**, a pharmaceutical company dedicated to advancing cancer treatments. This project involves analyzing clinical trial data for squamous cell carcinoma (SCC) treatments. As the **Senior Data Analyst**, your task is to explore, visualize, and summarize the data, focusing on the effectiveness of Capomulin and other drug regimens.  

The executive team requires comprehensive tables, figures, and a top-level summary of the study results to guide future decisions.  

---

## Repository Structure  

The repository is organized as follows:  

```
matplotlib-challenge/  
│  
├── Pymaceuticals/  
│   ├── pymaceuticals_study.ipynb    # Jupyter Notebook containing the analysis  
│   ├── Resources/                   # Folder containing input CSV files  
│   └── analysis/                    # Folder for generated figures and results (optional)  
│  
└── README.md                        # This README file  
```

---

## Objectives  

The project focuses on applying **Matplotlib** for visualizing and interpreting clinical data. The analysis involves data preparation, statistical summaries, and advanced visualizations to highlight key insights.

### Deliverables:  
1. **Data Preparation**:  
   - Merge datasets and clean duplicate data.  
   - Ensure accurate and reliable data for analysis.  

2. **Summary Statistics**:  
   - Calculate mean, median, variance, standard deviation, and SEM for tumor volumes across drug regimens.  

3. **Visualizations**:  
   - **Bar Charts**: Total data points for each drug regimen.  
   - **Pie Charts**: Distribution of male and female mice in the study.  
   - **Box Plot**: Tumor volume distributions for key treatment regimens, highlighting potential outliers.  
   - **Line Plot**: Tumor volume over time for a specific Capomulin-treated mouse.  
   - **Scatter Plot**: Mouse weight vs. average tumor volume for Capomulin treatment.  

4. **Correlation and Regression**:  
   - Calculate the correlation coefficient and linear regression between mouse weight and tumor volume.  
   - Overlay regression line on the scatter plot for Capomulin treatment.  

---

## Installation and Usage  

### Prerequisites:  
- Python 3.x  
- Jupyter Notebook  
- Required Libraries: Pandas, Matplotlib, NumPy, SciPy  

### Steps to Run the Analysis:  

1. **Clone the Repository**:  
   ```bash  
   git clone https://github.com/your-username/matplotlib-challenge.git  
   cd matplotlib-challenge/Pymaceuticals  
   ```  

2. **Install Required Libraries** (if not already installed):  
   ```bash  
   pip install pandas matplotlib numpy scipy  
   ```  

3. **Run the Notebook**:  
   - Open the Jupyter Notebook:  
     ```bash  
     jupyter notebook pymaceuticals_study.ipynb  
     ```  
   - Follow the step-by-step analysis in the notebook.  

4. **View Results**:  
   - Tables and visualizations will be generated directly in the notebook.  
   - Save or export any results to the `analysis/` folder if needed.  

---

## Data Overview  

The analysis uses two primary CSV files:  

- **Mouse Metadata**: Contains details about each mouse, such as sex and treatment regimen.  
- **Study Results**: Contains tumor volume measurements and time points for each mouse.  

---

## Key Features  

1. **Data Cleaning**:  
   - Identifies and removes duplicate entries for accurate analysis.  

2. **Statistical Insights**:  
   - Provides summary statistics for tumor volumes under different drug regimens.  

3. **Advanced Visualizations**:  
   - Bar charts, pie charts, box plots, and line plots to explore treatment effectiveness.  

4. **Correlation and Regression Analysis**:  
   - Establishes relationships between mouse weight and tumor volume.  

5. **Outlier Detection**:  
   - Highlights potential outliers in tumor volume data using IQR and box plots.  

---

## Observed Trends  

1. **Capomulin Effectiveness**:  
   - Capomulin consistently reduced tumor volumes, as observed in line and scatter plots.  

2. **Mouse Weight Correlation**:  
   - A positive correlation exists between mouse weight and average tumor volume under Capomulin treatment, suggesting further research is needed.  

3. **Outliers in Regimens**:  
   - Certain treatment regimens showed significant variability, with a few potential outliers.  
