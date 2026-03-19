# Programming for Data Science Assignment – Resubmission
## Heart Disease Mortality and Lifestyle Risk Factors in the United States

**Author:** Rumman Altaf Shekasan

### Dataset
This project uses the U.S. Chronic Disease Indicators (CDI) dataset from the CDC (Centers for Disease Control and Prevention), which provides state-level public health statistics across the United States. The goal of this analysis is to evaluate observing correlations between state-wide Heart Disease Mortality and three major risk factors (Obesity, Smoking, and Diabetes prevalence).

### Important Note on Data Cleaning
The raw dataset contains identical indicators broken down by multiple demographic stratifications (Age, Race, Gender, etc.). Averaging these groups together yields an invalid mathematical result. A key feature of this notebook is the `build_indicator_overall` function, which strictly isolates the "Overall" and "Age-adjusted" rows before merging, guaranteeing a valid 1:1 state comparison.

### Project Files
- `Fixed_Resubmission.ipynb` - The primary Jupyter notebook containing data extraction, cleaning, cleaning, merging, and visualization.
- `Fixed_DS_Assignment_Presentation.pptx` - A 10-slide presentation detailing the dataset, findings, and coding challenges (includes speaker notes).
- `Data/U.S._Chronic_Disease_Indicators.csv` - The raw dataset required to run the code.

### How to Run
1. Ensure the dataset `U.S._Chronic_Disease_Indicators.csv` is located in the `Data` directory relative to the notebook.
2. Ensure you have the following Python packages installed:
   - `pandas`
   - `numpy`
   - `matplotlib`
   - `seaborn`
3. Open `Fixed_Resubmission.ipynb` in Jupyter Notebook / JupyterLab.
4. Run all cells sequentially. The notebook runs end-to-end without errors or manual intervention.

### Python Packages Used
- `pandas` (for data manipulation, extraction, and merging)
- `numpy` (for mathematical operations)
- `matplotlib` (for plotting framework)
- `seaborn` (for advanced statistical data visualization and trendlines)

### Development History (Git)
A Git repository is included. Multiple commits show the iterative progress of developing the data extraction logic, correcting the stratifications, and designing the visualizations.
