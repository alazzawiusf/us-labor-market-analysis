# \# U.S. Labor Market Analysis

# 

# An end-to-end labor market analytics project examining how employment, pay, industry structure, and occupational opportunity vary across U.S. states.

# 

# The project combines \*\*U.S. Bureau of Labor Statistics (BLS)\*\* data from the \*\*Quarterly Census of Employment and Wages (QCEW)\*\* and \*\*Occupational Employment and Wage Statistics (OEWS)\*\* with Python-based data preparation, validation, exploratory analysis, and interactive Tableau dashboards.

# 

# The analysis is designed to answer a central question:

# 

# > \*\*How is the U.S. labor market changing across locations, industries, and occupations, and where are the strongest opportunities or challenges?\*\*

# 

# \---

# 

# \## Project Overview

# 

# The project is organized into three connected analytical layers:

# 

# 1\. \*\*State Performance\*\* — How employment and average pay changed across U.S. states from 2015–2025.

# 2\. \*\*Industry Dynamics\*\* — Which industries contributed most to employment gains or losses within individual states.

# 3\. \*\*Occupational Opportunity\*\* — How occupational groups differ in employment scale, wages, and local employment concentration.

# 

# This structure moves from broad state-level performance to the industries underlying that performance and finally to the occupational structure within individual states.

# 

# \---

# 

# \# Interactive Tableau Dashboards

# 

# \## 1. U.S. Labor Market Performance

# 

# The first dashboard provides an executive view of state labor-market performance and industry dynamics.

# 

# It allows users to:

# 

# \- Compare employment and pay indicators across states.

# \- Examine long-term state employment growth.

# \- Identify industries contributing to employment gains or losses.

# \- Compare industry employment between two states.

# \- Examine industry employment trajectories from 2015–2024.

# 

# !\[U.S. Labor Market Performance Dashboard](dashboards/labor\_market\_performance.png)

# 

# \### Interactive Version

# 

# \[\*\*View the U.S. Labor Market Performance Dashboard on Tableau Public\*\*](https://public.tableau.com/shared/ZRMKGCPDJ?:display\_count=n\&:origin=viz\_share\_link)

# 

# \---

# 

# \## 2. U.S. Occupational Opportunity

# 

# The second dashboard examines occupational opportunity within a selected state using employment scale, wages, and \*\*Location Quotient (LQ)\*\*.

# 

# Users can:

# 

# \- Compare major occupational groups.

# \- Identify occupations combining above-state-median wages with above-national employment concentration.

# \- Examine the employment composition of different occupational opportunity profiles.

# \- Drill down from major occupational groups into detailed occupations.

# 

# !\[U.S. Occupational Opportunity Dashboard](dashboards/occupational\_opportunity.png)

# 

# \### Interactive Version

# 

# \[\*\*View the U.S. Occupational Opportunity Dashboard on Tableau Public\*\*](https://public.tableau.com/views/Workforce-project-Public/U\_S\_OCCUPATIONALOPPORTUNITYDashboard?:language=en-US\&:display\_count=n\&:origin=viz\_share\_link)

# 

# \---

# 

# \# Key Findings

# 

# \## State Employment Growth

# 

# Long-term employment growth differed substantially across U.S. states.

# 

# From 2015 to 2025, some of the strongest employment growth occurred in:

# 

# | State | Employment Growth |

# |---|---:|

# | Idaho | 31.51% |

# | Utah | 29.87% |

# | Nevada | 26.08% |

# | Arizona | 23.95% |

# | Florida | 23.32% |

# | Texas | 21.05% |

# 

# The median state employment growth rate over the period was approximately \*\*8.44%\*\*.

# 

# The underlying trajectories also differed.

# 

# Idaho and Utah demonstrated sustained expansion with relatively rapid recovery following the 2020 labor-market disruption. Florida experienced a larger 2020 decline but a strong subsequent rebound.

# 

# Other states followed very different patterns. North Dakota's weakness, for example, began before the pandemic and was compounded by another decline in 2020.

# 

# These differences demonstrate that similar endpoint growth rates do not necessarily imply similar labor-market trajectories.

# 

# \---

# 

# \## Employment and Pay Growth

# 

# Employment growth and nominal average annual pay growth were positively related across states.

# 

# The correlation between 2015–2025 employment growth and average annual pay growth was approximately:

# 

# \*\*0.60\*\*

# 

# This indicates a meaningful positive relationship, but the relationship was not uniform.

# 

# States could exhibit:

# 

# \- High employment growth and high pay growth.

# \- High employment growth but lower relative pay growth.

# \- Stronger pay growth despite weaker employment expansion.

# \- Below-median performance on both dimensions.

# 

# This distinction helps separate labor-market expansion from changes in compensation.

# 

# > \*\*Important:\*\* Pay growth is nominal and is not adjusted for inflation. It should therefore not be interpreted as growth in purchasing power.

# 

# \---

# 

# \# Industry Growth Drivers

# 

# Industry-level analysis showed that employment growth was not driven by the same sectors everywhere.

# 

# For systematic cross-state comparison, the industry-driver analysis uses \*\*2015–2024\*\* rather than 2015–2025 because 2025 QCEW industry coverage was incomplete for several states.

# 

# Among \*\*50 states with sufficient endpoint data coverage\*\*:

# 

# \- \*\*Health Care and Social Assistance\*\* ranked among the top three industries for employment gains in \*\*47 of 50 states\*\*.

# \- Health Care and Social Assistance was the \*\*single largest employment-growth contributor in 36 states\*\*.

# \- \*\*Professional, Scientific, and Technical Services\*\* ranked among the top three growth industries in \*\*33 states\*\*.

# \- \*\*Construction\*\* ranked among the top three in \*\*24 states\*\*.

# \- \*\*Transportation and Warehousing\*\* ranked among the top three in \*\*20 states\*\*.

# 

# Health Care and Social Assistance therefore emerged as the most geographically widespread employment-growth engine across U.S. states.

# 

# Secondary growth drivers were more geographically differentiated.

# 

# \---

# 

# \## Different States, Different Growth Structures

# 

# Even rapidly expanding states did not grow through identical industry structures.

# 

# \### Florida

# 

# Major employment additions included:

# 

# \- Health Care and Social Assistance: \*\*+333,648\*\*

# \- Professional, Scientific, and Technical Services: \*\*+256,459\*\*

# \- Construction: \*\*+228,144\*\*

# \- Transportation and Warehousing: \*\*+178,131\*\*

# \- Accommodation and Food Services: \*\*+147,126\*\*

# 

# Florida therefore experienced relatively broad-based employment expansion across several major industries.

# 

# \### Idaho

# 

# Idaho's major employment gains included:

# 

# \- Health Care and Social Assistance: \*\*+38,691\*\*

# \- Construction: \*\*+36,954\*\*

# \- Accommodation and Food Services: \*\*+20,886\*\*

# \- Professional, Scientific, and Technical Services: \*\*+19,709\*\*

# 

# Construction employment increased by more than \*\*100%\*\* over the period, making it a particularly important component of Idaho's labor-market expansion.

# 

# \### Texas

# 

# Texas generated substantial employment gains across several industries, including:

# 

# \- Health Care and Social Assistance: \*\*+392,834\*\*

# \- Professional, Scientific, and Technical Services: \*\*+354,280\*\*

# \- Accommodation and Food Services: \*\*+244,890\*\*

# \- Construction: \*\*+222,918\*\*

# \- Transportation and Warehousing: \*\*+217,157\*\*

# 

# At the same time, Mining, Quarrying, and Oil and Gas Extraction declined by approximately \*\*60,000 jobs\*\*.

# 

# This illustrates how strong aggregate state employment growth can coexist with contraction in historically important industries.

# 

# \---

# 

# \# Occupational Opportunity Framework

# 

# The occupational component uses OEWS data from \*\*2021–2025\*\* to examine the structure of employment opportunities within individual states.

# 

# Three primary dimensions are used:

# 

# \### Employment

# 

# Represents the scale of an occupation within the selected state's labor market.

# 

# \### Median Annual Wage

# 

# Provides a measure of occupational compensation.

# 

# \### Location Quotient (LQ)

# 

# Measures how concentrated an occupation is within a state's employment structure relative to the national labor market.

# 

# An LQ of:

# 

# \- \*\*1.0\*\* indicates concentration approximately equal to the national level.

# \- \*\*Above 1.0\*\* indicates higher local concentration.

# \- \*\*Below 1.0\*\* indicates lower local concentration.

# 

# The dashboard compares occupational wages with the selected state's overall median wage while using \*\*LQ = 1.0\*\* as the national concentration benchmark.

# 

# This creates four descriptive occupational profiles:

# 

# 1\. \*\*High Pay / High Concentration\*\*

# 2\. \*\*High Pay / Low Concentration\*\*

# 3\. \*\*Low Pay / High Concentration\*\*

# 4\. \*\*Low Pay / Low Concentration\*\*

# 

# These categories are designed to describe occupational structure and should not be interpreted as a ranking of the "best" or "worst" occupations.

# 

# \---

# 

# \# Data Sources

# 

# \## Quarterly Census of Employment and Wages (QCEW)

# 

# \*\*Source:\*\* U.S. Bureau of Labor Statistics

# 

# Used for:

# 

# \- Employment

# \- Establishments

# \- Total wages

# \- Average annual pay

# \- Average weekly wage

# \- State-level labor-market analysis

# \- State × industry employment analysis

# 

# \*\*Analysis period:\*\* 2015–2025

# 

# \---

# 

# \## Occupational Employment and Wage Statistics (OEWS)

# 

# \*\*Source:\*\* U.S. Bureau of Labor Statistics

# 

# Used for:

# 

# \- Occupational employment

# \- Mean and median wages

# \- Wage percentiles

# \- Jobs per 1,000 workers

# \- Location Quotient

# \- Major occupational groups

# \- Detailed occupations

# 

# \*\*Analysis period:\*\* 2021–2025

# 

# \---

# 

# \# Analytical Workflow

# 

# The project follows an end-to-end analytical workflow:

# 

# ```text

# BLS Source Data

# &#x20;     ↓

# Python Data Preparation

# &#x20;     ↓

# Data Cleaning \& Transformation

# &#x20;     ↓

# Data Validation \& Quality Control

# &#x20;     ↓

# Exploratory Data Analysis

# &#x20;     ↓

# Analytical Findings

# &#x20;     ↓

# Tableau Data Model

# &#x20;     ↓

# Interactive Dashboards

# ```

# 

# Python was used to prepare, transform, validate, and analyze the source data before visualization.

# 

# The final analytical datasets used by Tableau are included in the `data/` directory.

# 

# \---

# 

# \# Data Quality and Methodological Considerations

# 

# \## QCEW Suppression

# 

# Some industry-level QCEW observations are suppressed by BLS for confidentiality.

# 

# Suppressed values were \*\*not imputed\*\*.

# 

# The industry dataset therefore contains a suppression indicator identifying state-industry observations where at least one underlying ownership component was suppressed.

# 

# Industry-level employment totals were also compared with official state employment totals to evaluate practical data coverage.

# 

# Coverage was generally very high from 2015–2024, while 2025 contained substantial coverage gaps for several states.

# 

# For this reason, the systematic cross-state industry-driver analysis uses \*\*2015–2024\*\*.

# 

# \---

# 

# \## OEWS Time Comparisons

# 

# OEWS estimates are produced using a multi-panel methodology.

# 

# Therefore, the 2021–2025 OEWS data in this project are primarily used to analyze recent occupational structure, employment scale, wages, and geographic concentration.

# 

# Changes between individual OEWS years should not automatically be interpreted as simple annual occupational job growth.

# 

# \---

# 

# \## Wage Interpretation

# 

# QCEW average-pay measures are nominal.

# 

# They have not been adjusted for inflation and therefore should not be interpreted directly as changes in real purchasing power.

# 

# Average pay can also be affected by changes in workforce composition.

# 

# For example, periods in which lower-wage employment declines disproportionately can produce increases in average pay even without equivalent wage increases for individual workers.

# 

# \---

# 

# \# Repository Structure

# 

# ```text

# us-labor-market-analysis/

# │

# ├── analysis/

# │   ├── 01\_QCEW\_Data\_Preparation.ipynb

# │   ├── 02\_OEWS\_Data\_Preparation.ipynb

# │   └── 03\_Labor\_Market\_EDA.ipynb

# │

# ├── dashboards/

# │   ├── labor\_market\_performance.png

# │   └── occupational\_opportunity.png

# │

# ├── data/

# │   ├── qcew\_state\_totals\_2015\_2025.csv

# │   ├── qcew\_state\_industry\_2015\_2025.csv

# │   └── oews\_state\_occupation\_2021\_2025.csv

# │

# ├── tableau/

# │   └── US\_Labor\_Market\_Analysis.twbx

# │

# ├── LICENSE

# └── README.md

# ```

# 

# \---

# 

# \# Notebooks

# 

# \### `01\_QCEW\_Data\_Preparation.ipynb`

# 

# Preparation and validation of QCEW state and industry-level labor-market data.

# 

# \### `02\_OEWS\_Data\_Preparation.ipynb`

# 

# Preparation, transformation, and quality-control workflow for OEWS state occupational data covering 2021–2025.

# 

# \### `03\_Labor\_Market\_EDA.ipynb`

# 

# Exploratory analysis used to evaluate state employment trends, pay growth, industry growth drivers, data coverage, and other patterns that informed the final Tableau dashboards.

# 

# \---

# 

# \# Tools \& Technologies

# 

# \- \*\*Python\*\*

# \- \*\*Pandas\*\*

# \- \*\*NumPy\*\*

# \- \*\*Jupyter Notebook\*\*

# \- \*\*Tableau\*\*

# \- \*\*Git\*\*

# \- \*\*GitHub\*\*

# \- \*\*BLS QCEW\*\*

# \- \*\*BLS OEWS\*\*

# 

# \---

# 

# \# Project Deliverables

# 

# This repository contains:

# 

# \- Reproducible Python data-preparation workflows.

# \- Data validation and quality-control steps.

# \- Exploratory labor-market analysis.

# \- Final analytical datasets used by Tableau.

# \- Tableau packaged workbook (`.twbx`).

# \- Final dashboard images.

# \- Interactive Tableau Public dashboards.

# 

# \---

# 

# \# Author

# 

# \*\*Ahmed Alazzawi\*\*

# 

# Data Analytics | Business Intelligence | Data Visualization

