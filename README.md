🌍 Global Suicide Rates — Exploratory Data Analysis (EDA)
📌 Project Overview

This project presents a comprehensive Exploratory Data Analysis (EDA) of global suicide data to understand how suicide rates vary across time, gender, age groups, countries, and economic conditions. The analysis focuses on identifying key demographic and temporal patterns using population-normalized suicide rates.

The goal of this project is descriptive and analytical, not predictive, and all findings are presented as associations, not causal claims.

🎯 Objectives

Analyze global suicide rate trends over time

Examine gender-based differences in suicide rates

Study age-group–specific suicide risk patterns

Identify countries with consistently high suicide rates

Compare total suicide burden versus population-normalized risk

Explore the relationship between economic indicators and suicide rates

📂 Dataset Description

The dataset contains suicide statistics reported across multiple countries and years, including demographic and socioeconomic attributes.

Key variables include:

Country

Year

Sex

Age group

Number of suicides

Population

Suicide rate per 100,000 population

GDP per capita

Decade (derived)

Age order (derived for correct age sorting)

The dataset was cleaned and preprocessed prior to analysis to ensure consistency, accuracy, and usability.

🧹 Data Cleaning & Preparation

The following steps were performed before analysis:

Removed duplicate records

Standardized column names and data types

Converted GDP fields to numeric values

Created derived features such as:

Decade (from year)

Age order (to preserve logical age progression)

Validated ranges for numeric variables

Ensured consistent categorical labels

A clean, analysis-ready dataset was then used for all EDA tasks.

📊 Exploratory Data Analysis
1️⃣ Distribution Analysis

Suicide rates per 100,000 population show a strong right-skewed distribution

Most observations cluster at lower rates, with a small number of extreme values

2️⃣ Time Trends

Global suicide rates increased from the late 1980s, peaked in the mid-1990s, and declined thereafter

This temporal pattern is consistent across multiple demographic groups

3️⃣ Gender-Based Analysis

Males consistently exhibit higher suicide rates than females across all years

The gender gap persists over decades despite overall declines in suicide rates

4️⃣ Age-Group Analysis

Suicide rates increase markedly with age

The highest rates are observed in individuals aged 55–74 years and 75+ years

Suicide rates among children aged 5–14 years remain consistently low

5️⃣ Age × Sex Interaction

Elderly males represent the highest-risk demographic group

The male–female gap widens substantially with increasing age

This interaction explains much of the observed global suicide burden

6️⃣ Country-Level Comparisons

Countries with the highest average suicide rates differ from those with the highest total suicide counts

Total suicides are influenced strongly by population size, whereas suicide rates reflect population-normalized risk

7️⃣ Economic Patterns

GDP per capita shows no strong linear relationship with suicide rates

High suicide rates occur across low-, middle-, and high-income countries

Economic prosperity alone does not explain suicide risk

8️⃣ Correlation Analysis

Strong correlation between population size and total suicide counts

Weak correlations between economic indicators and suicide rates

Positive association between age order and suicide rates

🧠 Key Insights

Suicide rates exhibit clear global temporal trends with a mid-1990s peak

Males consistently experience higher suicide rates than females

Suicide risk increases significantly with age

Elderly males are the most vulnerable demographic group

Geographic patterns reveal substantial cross-country heterogeneity

Suicide burden (counts) and suicide risk (rates) tell different stories

Economic indicators alone do not adequately explain suicide patterns

⚠️ Limitations

Possible underreporting and cultural stigma surrounding suicide

Differences in reporting standards across countries

Missing or incomplete socioeconomic indicators (e.g., HDI)

Aggregated data may mask within-country and within-group variation

All findings are associational, not causal

🛠 Tools & Technologies

Python

Pandas, NumPy

Matplotlib, Seaborn

Visual Studio Code

Jupyter Notebook

📌 Conclusion

This project demonstrates a structured, ethical, and data-driven exploratory analysis of global suicide patterns. By combining demographic, temporal, geographic, and economic perspectives, the analysis highlights the multifactorial nature of suicide risk and underscores the importance of targeted, demographic-specific prevention strategies.
