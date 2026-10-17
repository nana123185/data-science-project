# Education, Salary and Working Hours Data Analysis Project

## 1. Research Question
How does education level influence people's annual salary and weekly working hours?

## 2. Dataset source and usage permissions
Dataset name: age_salary_hours.csv
This is an open public dataset for educational practice. The dataset can be used for non-commercial data analysis learning.

## 3. Methods and tools used
Tools: Python, Jupyter Notebook
Libraries: pandas, numpy, matplotlib, seaborn, squarify
Analysis workflow:
1. Load and clean the dataset, filter records where age < 65
2. Calculate the proportion of different education groups
3. Visualize education group distribution with squarify treemap
4. Use violin plots to compare annual salary and weekly working hours across different education levels

## 4. Key findings and one limitation
### Key findings
- People with Bachelor's degree or higher account for 47.4% of all samples, which is the largest group.
- Higher education level generally corresponds to higher annual salary. Bachelor's degree or above group has the widest salary distribution and highest median salary.
- There is no obvious positive link between education level and weekly working hours.

### Limitation
This dataset only contains cross-sectional sample data. We cannot confirm causal relationships between education and salary; correlation does not equal causation.

## 5. Instructions for running the analysis
1. Download all files in this repository to local folder
2. Install required packages:
pip install pandas numpy matplotlib seaborn squarify
3. Open the `.ipynb` file with Jupyter Notebook
4. Run all cells sequentially to reproduce the analysis and visualizations
