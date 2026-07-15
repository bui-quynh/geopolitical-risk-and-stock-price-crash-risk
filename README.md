# Geopolitical risk and stock price crash risk
## Overview
This repository contains the Python and Stata codes developed for my undergraduate thesis:
**The Impact of Geopolitical Risk on Stock Price Crash Risk: The Moderating Role of Foreign Ownership in Vietnam** 
Python is used for data preprocessing and stock price crash risk calculation, while Stata is used for panel data econometric analysis.
## Research Question
This study investigates:
* Whether geopolitical risk increases stock price crash risk?
* Whether foreign ownership moderates this relationship?
## Research Workflow

The research follows the workflow below:

```text
Raw Daily Stock Price Data (FiinPro)
            │
            ▼
Python
• Data preprocessing
• Weekly return calculation
• Market model estimation
• Firm-specific return calculation
            │
            ▼
Crash Risk Measures
• NCSKEW
• DUVOL
• N_CRASH
• STDEV
            │
            ▼
Firm-Year Dataset
            │
            ▼
Merge with Financial & Macroeconomic Data
            │
            ▼
Stata
• Data cleaning
• Winsorization
• Panel data regression
• Moderation analysis
• Robustness checks
            │
            ▼
Regression Results
```
