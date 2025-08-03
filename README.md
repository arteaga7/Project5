# Project5
This project analyzes the information of two different telecommunication plans (Surf and Ultimate). The information is in 5 different datasets. Visualizations and hypotheses tests are performed.

**Objective:** To clean data to perform hypotheses tests (Levene and T tests) to make decisive decisions.

## Overview
First, the exploratory data analysis (EDA) is performed to show the data in the non-cleaned datasets. Second, the data preprocessing is made, which consist of filling null values, dropping duplicates, verifying if data format is correct and processing the outliers. Third, the formal Levene and T tests are performed to determine if the following hypotheses are true:

• Ultimate Plan earnings <= Surf Plan earnings

• New York mean earnings <= Non-New York mean earnings

Finally, some decisive conclusions are given.

🛠️**Libraries used**: Pandas, Matplotlib, NumPy, SciPy.

The Jupyter Notebook is in scripts/project5.ipynb.

## 🚀 Installation
1. Clone this repository:
```
git clone https://github.com/arteaga7/Project5.git
```
2. Set virtual environment and install dependencies:
```
python3 -m venv env
source env/bin/activate
pip3 install -r requirements.txt
```
3. Run Jupyter Notebook in scripts/project5.ipynb.