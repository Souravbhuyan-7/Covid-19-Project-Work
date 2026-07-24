# 🦠 COVID-19 Statistics Analysis

## 📌 Project Overview

This project analyses COVID-19 data from different Indian states and union territories.

The project uses three datasets containing information about:

- Confirmed, recovered and death cases
- State-wise COVID-19 testing
- State-wise COVID-19 vaccination

The complete analysis was performed using **Python in Jupyter Notebook through Visual Studio Code**.

The main purpose of this project is to clean, analyse and visualise COVID-19 data in a simple way so that both technical and non-technical users can understand the results.

---

## Dataset Information

The analysis is based on the "COVID-19 in India" dataset, which provides aggregated historical data on the pandemic's impact within the country.

-Title: COVID-19 in India
-Author: Sudalai Rajkumar
-Source: Kaggle Dataset

## Original Data Sources

The dataset is compiled from publicly available official Indian COVID-19 sources, including:

Ministry of Health and Family Welfare (MoHFW), Government of India
Indian Council of Medical Research (ICMR)
CoWIN Vaccination Programme
State Government Health Bulletins
The Kaggle author cleaned and organized these datasets into structured CSV files for easier analysis.



## 📂 Datasets Used

| Dataset | Description |
|---|---|
| `covid_19_india.csv` | Contains state-wise confirmed, recovered and death cases |
| `covid_vaccine_statewise.csv` | Contains state-wise vaccination information |
| `StatewiseTestingDetails.csv` | Contains state-wise COVID-19 testing information |

The datasets were downloaded from **Kaggle**.

---

## 📥 Downloading the Datasets from Kaggle

The following steps were used to download the datasets:

1. Visit [Kaggle](https://www.kaggle.com/).
2. Search for an Indian COVID-19 dataset.
3. Open the required dataset.
4. Click the **Download** button.
5. Kaggle downloads the dataset as a ZIP file.
6. Extract the downloaded ZIP file.
7. Copy the CSV files into the project folder.

Most Kaggle datasets are already available in `.csv` format after extracting the ZIP file.

### Converting an Excel File into CSV

If a dataset is downloaded in Excel format, it can be converted into CSV using pandas:

```python
import pandas as pd

# Read the Excel file
df = pd.read_excel("dataset.xlsx")

# Convert and save it as a CSV file
df.to_csv("dataset.csv", index=False)

🧹 Data Cleaning Process

Before analysing the datasets, a quality check was performed in the Qualitycheck.ipynb notebook.

📊 Analysis Performed

The Questions_related_Covid.ipynb notebook contains the main analysis and visualisations.


🛠️ Technologies and Tools Used

| Technology or Tool  | Purpose                                         |
|---------------------|-------------------------------------------------|
| Python              | Programming, data cleaning and data analysis    |
| pandas              | Loading, cleaning and manipulating datasets     |
| NumPy               | Performing numerical calculations               |
| Matplotlib          | Creating graphs and charts                      |
| Seaborn             | Creating attractive statistical visualisations |
| Jupyter Notebook    | Writing and executing Python code               |
| Visual Studio Code  | Writing code and managing project files         |
| Kaggle              | Downloading the COVID-19 datasets               |
| CSV                 | Storing and reading dataset information         |
| Git                 | Tracking changes in the project                 |
| GitHub              | Hosting and sharing the project online          |


📚 Python Libraries Used

-Pandas

Used for reading, cleaning, filtering, grouping and analysing datasets.

import pandas as pd

-NumPy

Used for numerical calculations and handling numerical values.

import numpy as np

-Matplotlib

Used for creating graphs such as bar charts and line charts.

import matplotlib.pyplot as plt

-Seaborn

Used for creating attractive statistical visualisations.

import seaborn as sns

⚙️ Installation and Setup

1. Install Python

Download and install Python from:

https://www.python.org/downloads/

During installation, select:

Add Python to PATH

2. Install Visual Studio Code

Download Visual Studio Code from:

https://code.visualstudio.com/

3. Install VS Code Extensions

Open the Extensions section in VS Code and install:

- Python
- Jupyter

📈 Visualisations

The project uses different visualisations, including:

- Bar charts
- Line charts
- State-wise comparison charts
- Top 10 state rankings
- Positivity-rate charts
- Testing and vaccination charts

These visualisations make the analysis easier to understand for non-technical users.

👤 Author

Name: Sourav Bhuyan
GitHub: Souravbhuyan-7