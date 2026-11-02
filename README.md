# 🌙 MoonPhase-Analysis

Exploring historical moon phases (1900–2100) using the Moonlora API, Python, and Pandas. This project focuses on collecting, cleaning, storing, and analyzing lunar data.

## 📌 Project Overview

MoonPhase-Analysis is a Python data analysis project that uses the [Moonlora API](https://moonlora.com) to retrieve historical moon phase information.

The project collects lunar data, processes API responses using Pandas, and stores the results in CSV files for further analysis.

## 🎯 Project Objectives

- Collect historical moon phase data from 1900 to 2100.
- Retrieve full moon and new moon information.
- Work with REST APIs using Python Requests.
- Clean and organize data using Pandas.
- Store collected lunar data in CSV files.
- Explore patterns and characteristics of lunar cycles.

## 🛠️ Technologies Used

- **Python** – Data collection and processing.
- **Pandas** – Data cleaning and analysis.
- **Requests** – API communication.
- **Jupyter Notebook/Google Colab** – Interactive coding and exploration.
- **Moonlora API** – Lunar data source.

## 📂 Repository Structure

```text
MoonPhase-Analysis/
│
├── Moon_Phase_Analysis.ipynb
│
├── fullmoons.csv
├── newmoons.csv
├── moon_phases_1900_2100.csv
├── moon_phases_backup.csv
│
└── README.md
```

## 📊 Dataset Files

| File | Description |
|---|---|
| `fullmoons.csv` | Collected full moon data. |
| `newmoons.csv` | Collected new moon data. |
| `moon_phases_1900_2100.csv` | Moon phase data covering 1900–2100. |
| `moon_phases_backup.csv` | Backup of moon phase data. |

## 📊 Kaggle Dataset

The collected lunar datasets are also available on Kaggle.

Explore and download the dataset:

[Historical Moon Phases (1900–2100) – Kaggle](https://www.kaggle.com/datasets/parv17/historical-moon-phases-19002100)

## 🌐 API Information

This project uses the **Moonlora Moon API**.

- Website: https://moonlora.com
- Base URL: `https://moonlora.com/api/v1`

### API Endpoints

| Endpoint | Purpose |
|---|---|
| `/phase?date=YYYY-MM-DD` | Retrieves moon phase information for a specific date. |
| `/full-moons/{year}` | Retrieves full moon information for a given year. |
| `/new-moons/{year}` | Retrieves new moon information for a given year. |

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Parv-Pahuja/MoonPhase-Analysis.git
```

### 2. Open the project directory

```bash
cd MoonPhase-Analysis
```

### 3. Install dependencies

```bash
pip install pandas requests tqdm jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `Moon_Phase_Analysis.ipynb` to explore the code and analysis.

## ⚠️ Notes

- The Moonlora API supports dates from 1900 to 2100.
- Large numbers of API requests may cause connection errors or rate limits.
- API requests should use appropriate timeouts and error handling.

## 🙏 Acknowledgements

- [Moonlora](https://moonlora.com) – Lunar data API.
- [Python](https://www.python.org/) – Programming language.
- [Pandas](https://pandas.pydata.org/) – Data analysis library.
- [Jupyter](https://jupyter.org/) – Interactive notebook environment.

## 📜 Data Attribution

Moon phase data is provided by [Moonlora](https://moonlora.com). Please retain the required attribution when using its API.

---

**If you find this project useful, feel free to explore the notebook and datasets!**
