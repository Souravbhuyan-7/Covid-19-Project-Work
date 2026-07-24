# 🦠 COVID-19 in India: Statistical Analysis and Visualization

## 📌 Project Overview

This project presents a comprehensive statistical analysis and visualization of the COVID-19 pandemic in India using historical datasets. It analyzes the spread of the virus, testing trends, recovery rates, mortality, and vaccination progress across different states and union territories.

The complete project was developed using **Python** in **Jupyter Notebook** through **Visual Studio Code**. The primary objective is to clean, analyze, and visualize COVID-19 data in an easy-to-understand manner for both technical and non-technical users.

---

# 🎯 Objectives

- Analyze the spread of COVID-19 across India.
- Study confirmed, recovered, and death cases over time.
- Compare state-wise COVID-19 statistics.
- Analyze testing and vaccination progress.
- Perform data cleaning and quality assessment.
- Create meaningful visualizations for better understanding.

---

# 📂 Project Structure

```
COVID-19-Statistics-Analysis/
│
├── covid_19_india.csv
├── covid_vaccine_statewise.csv
├── StatewiseTestingDetails.csv
│
├── data_visualisation.ipynb
├── Questions_related_Covid.ipynb
├── Qualitycheck.ipynb
│
├── README.md
└── requirements.txt
```

### Files Description

| File | Description |
|------|-------------|
| `covid_19_india.csv` | State-wise daily confirmed, recovered and death cases |
| `covid_vaccine_statewise.csv` | State-wise COVID-19 vaccination data |
| `StatewiseTestingDetails.csv` | State-wise COVID-19 testing data |
| `Qualitycheck.ipynb` | Data cleaning and quality assurance |
| `Questions_related_Covid.ipynb` | Exploratory data analysis based on research questions |
| `data_visualisation.ipynb` | Statistical analysis and visualizations |

---

# 📊 Dataset Information

The analysis is based on the **COVID-19 in India** dataset, which provides aggregated historical data on the pandemic's impact within the country.

**Title:** COVID-19 in India

**Author:** Sudalai Rajkumar

**Source:** Kaggle

---

# 📥 Downloading the Dataset

The datasets were downloaded from Kaggle using the following steps:

1. Visit Kaggle.
2. Search for **COVID-19 in India**.
3. Open the dataset.
4. Click **Download**.
5. Extract the downloaded ZIP file.
6. Copy the required CSV files into the project directory.

Most Kaggle datasets are already available in **CSV** format.

---

# 📄 Dataset Credibility Assessment

| Item | Status |
|------|--------|
| Dataset Author | Sudalai Rajkumar (Kaggle Contributor) |
| Dataset Type | Aggregated Historical COVID-19 Dataset |
| Government Dataset | ❌ No |
| Uses Government Sources | ✅ Yes |
| Synthetic Dataset | ❌ No Evidence |
| Suitable for College Projects | ✅ Yes |
| Suitable for Research | ✅ Yes |
| Suitable for Medical or Legal Decisions | ❌ No |

---

# 🏛 Original Data Sources

The dataset has been compiled from publicly available official Indian government sources, including:

- Ministry of Health and Family Welfare (MoHFW)
- Indian Council of Medical Research (ICMR)
- CoWIN Vaccination Programme
- State Government Health Bulletins

The Kaggle author collected, cleaned, and organized these official datasets into structured CSV files for easier analysis.

---

# ✅ Dataset Authenticity Statement

> This project uses the **COVID-19 in India** dataset published by **Sudalai Rajkumar** on Kaggle. The dataset is a curated collection of publicly available COVID-19 statistics compiled from official Indian government sources such as the Ministry of Health and Family Welfare (MoHFW), the Indian Council of Medical Research (ICMR), CoWIN vaccination records, and State Government Health Bulletins.
>
> The dataset itself is **not an official Government of India publication**, but rather a community-maintained aggregation of official public data. There is **no evidence that the dataset is synthetic or artificially generated**. It is widely used for educational purposes, data analysis, machine learning projects, and academic demonstrations. Historical datasets may contain revisions or corrections introduced during data collection and aggregation.

---

# 🧹 Data Cleaning Process

Before performing the analysis, data quality checks were carried out in **Qualitycheck.ipynb**.

The cleaning process includes:

- Handling missing values
- Removing duplicate records
- Checking data types
- Correcting inconsistent values
- Formatting date columns
- Preparing datasets for analysis

---

# 📊 Statistical Analysis

The notebook **Questions_related_Covid.ipynb** contains exploratory data analysis and answers several analytical questions based on the datasets.

The analysis includes:

- Top affected states
- Highest recovery states
- Highest mortality states
- State-wise comparison
- Testing trends
- Vaccination progress
- Correlation analysis

---

# 📈 Data Visualizations

The notebook **data_visualisation.ipynb** contains multiple statistical visualizations, including:

### Trend Analysis

- Confirmed Cases Over Time
- Recovered Cases Over Time
- Death Cases Over Time

### State-wise Analysis

- Top 10 States by Confirmed Cases
- Top 10 States by Recoveries
- Top 10 States by Deaths
- Recovery Rate Comparison

### Testing Analysis

- Daily Testing Trends
- Testing vs Confirmed Cases
- Positivity Rate Analysis

### Vaccination Analysis

- State-wise Vaccination Progress
- Cumulative Vaccination Trends

### Charts Used

- Line Charts
- Bar Charts
- Pie Charts
- Scatter Plots
- Heatmaps
- Correlation Matrix
- State-wise Comparison Charts

---

# 📚 Python Libraries Used

### Pandas

Used for reading, cleaning, filtering, grouping, and analyzing datasets.

```python
import pandas as pd
```

### NumPy

Used for numerical calculations and handling numerical data.

```python
import numpy as np
```

### Matplotlib

Used for creating various graphs and charts.

```python
import matplotlib.pyplot as plt
```

### Seaborn

Used for creating attractive statistical visualizations.

```python
import seaborn as sns
```

---

# 🛠 Technologies and Tools Used

| Technology | Purpose |
|------------|---------|
| Python | Programming and Data Analysis |
| Pandas | Data Manipulation |
| NumPy | Numerical Computation |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Jupyter Notebook | Interactive Coding |
| Visual Studio Code | Code Development |
| Kaggle | Dataset Source |
| CSV | Dataset Storage |
| Git | Version Control |
| GitHub | Project Hosting |

---

# ⚙️ Installation and Setup

## Step 1: Install Python

Download Python from:

https://www.python.org/downloads/

During installation, enable:

- Add Python to PATH

---

## Step 2: Install Visual Studio Code

Download Visual Studio Code:

https://code.visualstudio.com/

---

## Step 3: Install Required VS Code Extensions

Install:

- Python
- Jupyter

---

## Step 4: Install Required Python Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

---

# 📄 Converting Excel Files to CSV (Optional)

If your dataset is in Excel format:

```python
import pandas as pd

# Read Excel file
df = pd.read_excel("dataset.xlsx")

# Save as CSV
df.to_csv("dataset.csv", index=False)
```

---

# 🚀 How to Run the Project

1. Clone the repository.

```bash
git clone https://github.com/yourusername/COVID-19-Statistics-Analysis.git
```

2. Open the project folder in Visual Studio Code.

3. Launch Jupyter Notebook.

4. Open and run the notebooks in the following order:

- `Qualitycheck.ipynb`
- `Questions_related_Covid.ipynb`
- `data_visualisation.ipynb`

---

# 📌 Key Features

- Comprehensive COVID-19 statistical analysis
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- State-wise comparison
- Testing analysis
- Vaccination analysis
- Multiple visualizations
- Well-documented Jupyter notebooks
- Easy to understand for beginners

---

# 👨‍💻 Authors

**Project Analysis By**

- Rati Ranjan Mohapatra
- Sudeshna Bal
- Sourav Bhuyan

---

# 🙏 Data Credits

**Dataset:** COVID-19 in India

**Dataset Author:** Sudalai Rajkumar

**Dataset Platform:** Kaggle

The dataset is based on publicly available official Indian COVID-19 data compiled and organized by the author for educational and analytical purposes.

---

# 📜 License

This project is created for **educational, research, and academic purposes only**.

The datasets belong to their respective owners and are used under the terms provided by the Kaggle dataset author.

---

⭐ If you found this project useful, consider giving the repository a star on GitHub.