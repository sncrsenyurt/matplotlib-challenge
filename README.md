# matplotlib-challenge
### Project Overview
This project aims to analyze the efficacy of Capomulin, Infubinol, and Ceftamin in treating squamous cell carcinoma in a cohort of 249 mice. The analysis focuses on the relationship between mouse weight and tumor volume (TV), the comparison of final TV distributions for each drug, and a case study of mouse l509 treated with Capomulin.

### Dataset
The dataset consists of information about 249 mice undergoing treatment for squamous cell carcinoma with Capomulin, Infubinol, and Ceftamin. The dataset includes the following variables:

- Mouse ID
- Drug Regimen
- Weight (grams)
- Timepoint (days)
- Tumor Volume (cubic millimeters)

### Analysis
The analysis includes the following components:

1. Regression analysis to examine the correlation between average mouse weight and average tumor volume (TV).
2. Quartile and box plot analysis to compare the distribution of final TV's for mice treated with Capomulin, Infubinol, and Ceftamin.
3. A case study of mouse l509, one of the 249 mice, focusing on the effectiveness of Capomulin treatment in reducing TV over time.

### Key Findings
- A strong positive correlation (r = 0.84) exists between average mouse weight and average TV.
- Capomulin appears to be more effective at shrinking tumors compared to Infubinol and Ceftamin, with a similar effectiveness to Ramicane.
- Capomulin treatment of mouse l509 demonstrated a reduction in TV over time, but with fluctuations and a non-linear decline.

### Further Research
Additional research is needed to address the following questions:

- What other variables might impact treatment outcomes (e.g., food intake, exercise, socialization)?
- What factors contributed to the initial TV increase and subsequent fluctuations during Capomulin treatment for mouse l509?
- What are the potential side effects of the drug regimens, such as changes in appetite, energy levels, and fur loss?

### Dependencies
- Python 3
- Pandas
- NumPy
- Matplotlib
- Scipy

### Usage
To run the analysis, execute the Jupyter Notebook file ("irfansencersenyurt.ipynb") in a Python environment with the required dependencies installed.
