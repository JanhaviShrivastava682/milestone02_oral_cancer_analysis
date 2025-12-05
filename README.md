Milestone 02-Independent Resarch Analysis
Author: Janhavi Shrivastava
Course: CHIP 690
Research: Oral Cancer Analysis

Overview:
This projevct explores the differences in Oral Cancer risk factors and clinical outcomes between U.S. patients and Global patients using a structured oral cancer dataset. The goal of this milestone is not to achieve perfect research results, but to demonstrate the ability to use Python, pandas, and data visualization to answer research question.

The project structure is 
     --Research plan
     --Milestone02.ipynb
     --oral_cancer_prediction_dataset.csv
     --README.md  
     --plots/ folder
        --risk_factor.png
        --tumor_size.png
        --survival_rate_by_stage.png
        --stage_distribution.png
        --outcome_dashboard.png

The analysis follows the reserach plan submitted in part 1 and focuses on comparing:
1. Major risk factors 
2. Early diagnosis rates
3. Mean tumor size 
4. Mean 5-year survival rate
5. Cancer stage distribution
All analysis and visulaization were completed in a Jupyter Notebook.

Project dataset used: oral_cancer_prediction_dataset.csv

This file consists:
Demographic details: Gender, age, country
Risk factors
Clinical outcomes
A new column named "region" was added to classify patients as US or Global for comparison

Research Question:
How do oral cancer risk factors and clinical outcomes differ between U.S. patients and patients from the rest of the world?
To answer this question, the notebook performs:
Data cleaning
Dataset modification
Descriptive statistics
Visual comparison
Summary interpretations.

How to run the notebook:
1. Ensure the following two files are in the same folder:
    --Milestone02.ipynb
    --oral_cancer_prediction_dataset.csv
2. Open the notebook in Jupyter or VS code.
3. Run all cells from top to bottom.
4. All visulaizations will display inside the notebook and also saved inside the "plots" folder.

The script uses a relative path to run the file.

Python libraries used:
    pandas
    matplotlib
If needed install pandas and matplotlib

Key visualizations Produced:
1. Risk Factor comprison between US and Global
A bar chart showing percentage of each risk factor by region.

2. Tumor size Comparison:
Simple bar charts comparing mean tumor size at diagnosis.

3. Dashboard subset visualization:
A 4-panel outcome dashboard includes:
Patient counts with cancer, Early diagnosis %, mean tumor size, and mean survival rate.

4. 5-Year Survival Rate:
Visualize survival rate based of the stages in US and Globally.


5. Cancer stage distribution: 
Stacked bar chart showing stage progression patterns. 

Summary of findings:
Accross most risk factors, U.S. and Global patients show very similar patterns. The main major difference is betel quid use, kwhich is significantly higher in the Global population.
Early diagnosis is slightly higher in U.S., suggesting effective screening and quick access to healthcare.
Tumor size at diagnosis is almost identical between the two groups, indicating similar levels of late detection.
5-year survival rate is slightly higher in the U.S..
Clinical outco=mes are fairly similar, but lifestyle risk factors vary more significantly. 

Conclusion:
Per the above findings, suggests that improving early detection programs and reducing high-risk behaviors globally could help reduce oral cancer burden.

References:
Oral Cancer Prediction Dataset [Internet]. [cited 2025 Oct 23]. Available from: https://www.kaggle.com/datasets/ankushpanday2/oral-cancer-prediction-dataset
Spelling and grammar check: https://app.grammarly.com/
https://www.w3schools.com/python/pandas/pandas_cleaning.asp
https://www.w3schools.com/python/matplotlib_intro.asp
