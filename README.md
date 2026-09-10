<img src="assets/img/Tinder-Symbole.png" alt="Tinder Logo" width="300"/>

> **Exploratory data analysis uncovering behavioral patterns in speed dating decisions.**  
> Statistical analysis and visualization of 8,000+ speed dating interactions to identify key factors influencing mutual attraction and second-date decisions.

---

## 📋 Table of Contents

- [📋 Table of Contents](#-table-of-contents)
- [🎯 About](#-about)
- [🎯 Project Goals](#-project-goals)
- [⚙️ Tech Stack](#️-tech-stack)
- [✨ Key Features](#-key-features)
  - [**Data Preparation \& Exploration**](#data-preparation--exploration)
  - [**Behavioral Analysis**](#behavioral-analysis)
- [📊 Key Insights](#-key-insights)
- [📓 Notebooks](#-notebooks)
- [🚀 Quick Start](#-quick-start)
- [📜 License](#-license)
- [🎓 Portfolio Context](#-portfolio-context)
- [Author](#author)

---

## 🎯 About

Tinder's marketing team is experiencing a decrease in matches and needs to understand **what makes people interested in each other** for second dates.

This project analyzes data from experimental speed dating events (2002-2004) where participants had 4-minute dates and rated each other on six attributes: Attractiveness, Sincerity, Intelligence, Fun, Ambition, and Shared Interests. The dataset includes demographics, dating habits, self-perception, and lifestyle information.

[⬆ Back to top](#-table-of-contents)

---

## 🎯 Project Goals

1. **Identify decision drivers**: What attributes most influence positive second-date decisions?
2. **Demographic patterns**: How do age, gender, and background affect dating preferences?
3. **Self-perception vs reality**: Compare participants' self-ratings with how they're perceived by dates
4. **Behavioral insights**: Discover actionable patterns to improve Tinder's matching algorithm

[⬆ Back to top](#-table-of-contents)

---

## ⚙️ Tech Stack

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.x-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-1.26-013243?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.8-11557C?logo=matplotlib&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12-4C9A2A?logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-5.x-3F4F75?logo=plotly&logoColor=white)

[⬆ Back to top](#-table-of-contents)

---

## ✨ Key Features

### **Data Preparation & Exploration**
Comprehensive missing value analysis, irrelevant column removal, and data quality validation. Distribution analysis across demographic groups and correlation heatmaps for attribute ratings.

### **Behavioral Analysis**
- Gender-based preference patterns (rating criteria differences)
- Self-perception bias quantification (self-rating vs partner-rating gaps)
- Mutual match rate analysis and decision symmetry patterns

[⬆ Back to top](#-table-of-contents)

---

## 📊 Key Insights

**Dataset:** 8,378 speed dating interactions from 551 participants (2002-2004)

1. **Least desirable attributes**: Shared interests (women), ambition (men)
2. **Attractiveness** (varies by gender) has less weight than presumed in final decision
3. **Shared interests more important than ethnic origin** are a predominant criterion beyond a certain number of interests. Hypothesis: they are descriptors of values and lifestyle
4. **Optimistic initial self-perception** - participants estimate that others perceive them as they perceive themselves
5. **Importance of meeting order**. More positive responses at the beginning and end
6. **Difference in selectivity by professional categories** depending on gender

[⬆ Back to top](#-table-of-contents)

---

## 📓 Notebooks

**[eda.ipynb](notebooks/eda.ipynb)** - Complete Exploratory Data Analysis
- Missing value handling and cleaning
- Demographic distribution analysis
- Attribute correlation analysis
- Decision pattern visualization
- Gender comparison and bias detection
- Mutual match rate analysis
- Key insights

[⬆ Back to top](#-table-of-contents)

---

## 🚀 Quick Start

**Prerequisites:**
- Python ≥ 3.8
- `pip` and virtual environment (`venv` recommended)

**Installation:**
```bash
# 1. Clone repository
git clone https://github.com/fabthenabab/eda-tinder.git
cd eda-tinder

# 2. Create and activate virtual environment
python3 -m venv .venv-tinder
source .venv-tinder/bin/activate

# 3. Install dependencies
pip install --upgrade pip
pip install --no-cache-dir -r requirements.txt

# 4. Install Jupyter
pip install jupyterlab ipykernel

# 5. Launch notebook
jupyter lab
# Open eda.ipynb
```

[⬆ Back to top](#-table-of-contents)

---

## 📜 License

This project is licensed under the GPL-3.0 License — see the [LICENSE](./LICENSE) file for details.

[⬆ Back to top](#-table-of-contents)

---

## 🎓 Portfolio Context

**Project Type:** Exploratory Data Analysis (EDA) - Behavioral Statistics  
**Focus:** Insight discovery and data storytelling over modeling

**Demonstrates:**
- **Data cleaning methodology** (missing value strategies, feature selection)
- **Visualization techniques** (Matplotlib, Seaborn, Plotly)
- **Correlation analysis** across categorical and continuous variables
- **Statistical analysis** of human behavioral patterns (8,378 interactions)
- **Business insight generation** from experimental data

## Author

**Fabien Messinger** — Data Engineer, certified AI Architect (RNCP7, Jedha)
[GitHub](https://github.com/f-msngr) · [LinkedIn](https://www.linkedin.com/in/fabien-messinger)

[⬆ Back to top](#-table-of-contents)