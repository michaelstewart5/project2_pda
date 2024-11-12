# Project 2: Identifying Key Predictors of Smoking Abstinence through Lasso Regression and Best Subset Modeling

## Overview

This project, in collaboration with Dr. George Papandonatos from Brown University’s Biostatistics Department, explores factors impacting smoking cessation in adults with major depressive disorder (MDD). 
In our analysis, we examined baseline characteristics as potential moderators of treatment effects on end-of-treatment abstinence, applying Lasso and Best Subset regression models to uncover key predictors. 

## Data

The trial enrolled 300 adult smokers with current or past MDD, who were randomly assigned to one of four treatment groups: varenicline with behavioral activation for smoking cessation (BASC), varenicline with standard treatment (ST), placebo with BASC, or placebo with ST. BASC is a behavioral approach that aims to increase engagement in rewarding, non-smoking-related activities to counteract depressive symptoms, while ST focuses on general smoking cessation counseling without targeted behavioral activation. 

Variables in this data include demographic factors (age, sex, race/ethnicity), nicotine dependence indicators (such as the FTCD score and Nicotine Metabolism Ratio [NMR]), and psychological variables (including the Beck Depression Depression Inventory [BDI] score and readiness to quit).

## Key Files

- `project2_edit.qmd`: Quarto file containing the raw code, analysis, and interpretations.
- `project2_edit.pdf`: Final report summarizing the findings and interpretations.


## Main Dependencies:
The project uses R (version 4.2.3) for analysis. The following R packages are required:

- `tidyverse` (version 2.0.0)
- `gtsummary`(version 1.7.2)
- `pROC` (version 1.18.5)
- `L0Learn` (version 2.1.0)
- `glmnet` (version 4.1-8)
- `randomForest` (version 4.7-1.1)
- `reshape2`(version 1.4.4)
- `kableExtra` (version 1.4.0)
- `caret` (version 6.0-94)
- `corrplot` (version 0.92)
- `mice` (version 3.16.0)
