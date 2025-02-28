# 🚗 Electric Vehicle Market Analysis

[![Python](https://img.shields.io/badge/python-3670A0?logo=python&logoColor=ffdd54)](https://www.python.org)
[![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?logo=jupyter&logoColor=white)](https://jupyter.org)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/stable/index.html)
[![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?logo=TensorFlow&logoColor=white)](https://www.tensorflow.org/)
[![nVIDIA](https://img.shields.io/badge/nVIDIA-%2376B900.svg?logo=nVIDIA&logoColor=white)](https://www.nvidia.com/en-in/geforce/)  
[![Windows](https://badgen.net/badge/icon/windows?icon=windows&label)](https://microsoft.com/windows/)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?logo=visual-studio-code&logoColor=white)
![PyCharm](https://img.shields.io/badge/pycharm-143?logo=pycharm&logoColor=black&color=black&labelColor=green)
![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?logo=microsoft-excel&logoColor=white)

## Overview

This repository contains a comprehensive analysis of the **electric vehicle (EV)** market based on a detailed dataset encompassing demographic and financial information. The aim of this analysis is to understand how various demographic factors impact **EV adoption** and consumer attitudes towards sustainable transportation. Insights generated from this work can inform **marketing strategies**, **product development**, and **policy initiatives** in the EV sector.


## 📂 Contents

- **Dataset**: Original data used for analysis, including demographic and financial attributes.
- **Data Pre-processing**: Steps for cleaning, transforming, and preparing the data for analysis.
- **Segment Extraction**: Implementation of the KMeans clustering algorithm to identify distinct customer segments within the EV market.
- **Profiling and Describing Segments**: Detailed profiles of identified segments, including characteristics and potential market strategies.
- **Marketing Strategies**: Recommendations for customizing the marketing mix to effectively target high-value customers.


## ❓ Problem Statement

The central question driving this analysis is: 

**How do various demographic factors—including age, marital status, education level, profession, and number of dependents—impact the adoption of electric vehicles?**

### 🎯 Specific Goals
1. **Pattern Recognition**: Examine correlations between demographic characteristics and EV adoption rates.
2. **Financial Stability Assessment**: Investigate how family dynamics influence financial health and willingness to invest in EVs.
3. **Impact of Education**: Analyze the connection between education levels and attitudes towards sustainability and EV purchasing decisions.
4. **Profession Comparison**: Compare financial behaviours of salaried individuals and business owners regarding EV ownership.


## 📊 Data Collection

The dataset includes a variety of demographic and financial attributes relevant to EV ownership, including:
- **Age**
- **Profession** (Salaried or Business)
- **Marital Status**
- **Education Level** (Graduate or Postgraduate)
- **Number of Dependents**
- **EV Ownership Status**
- **Total Household Income**
- **Costs/Investments** related to EVs

### ⚠️ Data Quality Considerations
- **Completeness**
- **Consistency**
- **Accuracy**


## 🔧 Data Pre-processing

The data was pre-processed through several key steps:
1. **Data Cleaning**: Identifying and addressing missing values and duplicates.
2. **Data Transformation**: Applying one-hot encoding for categorical variables and standardizing numerical features.
3. **Dimensionality Reduction**: Utilizing **Principal Component Analysis (PCA)** to optimize the dataset for analysis.


## 🗂️ Segment Extraction

The **KMeans** clustering algorithm was utilized to extract **five distinct segments** from the dataset. Each segment was evaluated for stability and characterized by unique attributes.

### 📋 Segment Profiles
1. **Segment 1**: Lower income, seeking affordable EV options.
2. **Segment 2**: High-value customers interested in premium models.
3. **Segment 3**: Middle-income individuals needing tailored financing.
4. **Segment 4**: Moderately aware consumers requiring educational resources.
5. **Segment 5**: Environmentally conscious consumers seeking sustainable practices.


## 📈 Marketing Strategy Implications

Targeting **Segment 2** (high-value customers) is recommended due to their potential for profitability and alignment with premium offerings. Other segments can also be addressed with tailored products and educational initiatives.


## 🏁 Conclusion

This analysis identifies key customer segments within the EV market, providing valuable insights to enhance engagement strategies, improve customer satisfaction, and foster growth in the electric vehicle industry.
