# 🌊 River Plastic Waste Risk Prediction

## Project Overview

Plastic pollution in rivers is one of the main sources of marine pollution worldwide. Rivers transport large quantities of mismanaged plastic waste from land into oceans, contributing to ecosystem damage and environmental degradation. ([ScienceDirect][1])

This project analyzes **river plastic waste risk scenarios** using environmental and waste-management data. The objective is to explore how factors such as waste generation, population growth, and waste management systems influence the risk of plastic leakage into rivers.

Through exploratory data analysis and visualization, this project aims to identify patterns in **plastic waste generation and river pollution risk across global river systems**.

---

# Research Objectives

This project focuses on understanding environmental risks associated with plastic waste in rivers.

Key questions explored include:

1. Which rivers face the **highest risk of plastic waste leakage**?
2. How do **waste generation and management practices** affect pollution risk?
3. How might plastic waste risks change **between 2015 and future projections (e.g., 2060)**?
4. What patterns exist in **regional or global river pollution risks**?

Understanding these patterns can support **environmental policy, waste management planning, and river conservation strategies**.

---

# Dataset

The dataset used in this project simulates global plastic waste generation and leakage risk across thousands of river systems.

It includes environmental and waste management variables used to estimate **river plastic pollution risk levels**.

### Key Variables

| Variable           | Description                               |
| ------------------ | ----------------------------------------- |
| River System       | Name or identifier of river basin         |
| Country            | Country where the river is located        |
| Population         | Population in the river basin             |
| Waste Generation   | Total plastic waste generated             |
| Mismanaged Waste   | Waste not properly disposed               |
| River Leakage Risk | Estimated risk of plastic entering rivers |
| Scenario Year      | Scenario projection (e.g., 2015 vs 2060)  |

These types of datasets are commonly used to model how **mismanaged plastic waste flows through rivers and eventually reaches oceans**. ([kaggle.com][2])

---

# Technologies Used

The project was implemented using the following data science tools:

* **Python**
* **Pandas** – data manipulation and cleaning
* **NumPy** – numerical analysis
* **Matplotlib** – visualization
* **Seaborn** – statistical visualization
* **Jupyter Notebook** – interactive analysis

---

# Project Workflow

The analysis follows a standard environmental data science workflow.

### 1️⃣ Data Loading

Import dataset and inspect structure.

### 2️⃣ Data Cleaning

* Handle missing values
* Validate data types
* Remove duplicates

### 3️⃣ Exploratory Data Analysis

* Summary statistics
* Distribution of plastic waste generation
* Comparison between years and scenarios

### 4️⃣ Visualization

Key visualizations include:

* River plastic waste risk distribution
* Country-level waste generation
* Scenario comparison (2015 vs 2060)
* Relationship between population and waste leakage risk

### 5️⃣ Interpretation

Identify major risk patterns and environmental implications.

---

# Key Insights

The analysis highlights several important trends:

* **Mismanaged plastic waste is a major driver of river pollution risk**
* Rivers in regions with **high population density and weak waste management systems** tend to show higher leakage risk
* Future projections indicate that **plastic waste risk may increase significantly without improved waste management policies**
* Some river systems act as **major pathways transporting plastic pollution toward oceans**

These insights are useful for designing **environmental interventions and sustainable waste management strategies**.

---

# Project Structure

```
River-Plastic-Waste-Risk
│
├── data
│   └── river_plastic_waste_data.csv
│
├── notebooks
│   └── plastic_waste_analysis.ipynb
│
├── report
│   └── River_Plastic_Waste_Risk_Analysis.pdf
│
└── README.md
```

---

# How to Run the Project

### Clone the repository

```bash
git clone https://github.com/MYOILY/River-Plastic-Waste-Risk.git
```

### Install dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

### Run the notebook

Open the notebook and run all cells:

```
plastic_waste_analysis.ipynb
```

---

# Future Improvements

Potential extensions for this project include:

* Building **machine learning models to predict river plastic pollution risk**
* Performing **geospatial analysis of river basins**
* Creating **interactive environmental dashboards**
* Integrating **real-world environmental monitoring datasets**
* Developing **policy simulations for waste reduction strategies**

---

# Author

Lok Yiu

GitHub:
[https://github.com/MYOILY](https://github.com/MYOILY)

---

[1]: https://www.sciencedirect.com/science/article/pii/S0025326X25011257?utm_source=chatgpt.com "Advanced deep learning strategies for detection and ..."
[2]: https://www.kaggle.com/datasets/khushikyad001/river-plastic-waste-risk-scenarios-2015-vs-2060?utm_source=chatgpt.com "River Plastic-Waste Risk Scenarios: 2015 vs 2060"
