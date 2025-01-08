Matplotlib Challenge: Pymaceuticals Inc.

Overview

This project focuses on analyzing a pharmaceutical study involving several drug regimens tested on mice to observe their effects on tumor volume. Using Python and Matplotlib, we cleaned, visualized, and interpreted the data to uncover insights into drug effectiveness and other key metrics.

Dataset Description

Two datasets were provided:

Mouse_metadata.csv: Contains metadata about the mice, including their ID, gender, age, and drug regimen.

Study_results.csv: Includes measurements from the study, such as tumor volume, metastatic sites, and timepoints.

These datasets were merged using the Mouse ID column to form a comprehensive dataset for analysis.

Analysis Workflow

1. Data Cleaning

Identified and removed duplicate entries based on Mouse ID and Timepoint to ensure data accuracy.

Ensured all data points were uniquely identified and free of inconsistencies.

2. Exploratory Data Analysis (EDA)

Generated bar charts and pie charts to visualize:

The distribution of mice across drug regimens.

Gender distribution (50.4% male and 49.6% female).

3. Tumor Volume Analysis

Box-and-whisker plots were created for four selected treatments: Capomulin, Ramicane, Infubinol, and Ceftamin.

Observed that Capomulin and Ramicane had the lowest median tumor volumes and narrower ranges, indicating greater effectiveness.

Noted an outlier in the Infubinol dataset, which was further investigated.

4. Line Plot for Tumor Progression

Selected a specific mouse treated with Capomulin and plotted the tumor volume over time. The plot revealed a significant decrease in tumor size as time progressed, showcasing the drug's effectiveness.

5. Correlation and Regression Analysis

Performed a scatter plot and linear regression to analyze the relationship between mouse weight and average tumor volume for the Capomulin regimen.

Identified a positive correlation, indicating that larger mice tend to have larger tumor volumes.

Key Findings

Capomulin and Ramicane were the most effective treatments, as evidenced by lower tumor volumes and consistent results.

Infubinol showed more variability and included an outlier that warrants further study.

The relationship between mouse weight and tumor volume suggests potential factors influencing drug efficacy.

Tools Used

Python Libraries: Matplotlib, Pandas, NumPy, SciPy

Visualization Techniques: Bar charts, pie charts, box-and-whisker plots, scatter plots, and line plots.

How to Run the Analysis

Clone this repository:

git clone <repository_url>

Install required Python libraries:

pip install matplotlib pandas numpy scipy

Run the Jupyter Notebook to view the analysis step-by-step:

jupyter notebook pymaceuticals_analysis.ipynb

File Structure

Mouse_metadata.csv: Metadata for the study.

Study_results.csv: Experimental results.

pymaceuticals_analysis.ipynb: Jupyter Notebook containing the analysis.

README.md: This file.

Conclusion

The Matplotlib Challenge highlights the importance of data visualization and statistical analysis in understanding the effects of pharmaceutical treatments. By cleaning and analyzing the data, we identified the most promising drugs and gained insights into factors influencing their effectiveness.
