# Netflix Data Analysis 📺

Exploratory Data Analysis (EDA) on the Netflix Movies and TV Shows dataset using Python and Jupyter Notebooks. This project uncovers content trends, geographic distribution, genre evolution, and release patterns across Netflix's catalog.

---

## 📊 Dataset

**Source:** [Netflix Movies and TV Shows on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)  
**Records:** ~8,800 titles  
**Features:** show_id, type, title, director, cast, country, date_added, release_year, rating, duration, listed_in (genres), description

---

## 🎯 Analysis Objectives

- Content type distribution (Movies vs TV Shows)
- Geographic content production & availability
- Genre trends over time
- Release year vs. date added patterns
- Rating distributions
- Top directors, actors, and countries
- Duration analysis (movies: minutes, TV shows: seasons)

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| `Python 3.10+` | Core language |
| `Pandas` | Data manipulation & cleaning |
| `NumPy` | Numerical operations |
| `Matplotlib` | Static visualizations |
| `Seaborn` | Statistical visualizations |
| `Plotly` | Interactive charts |
| `Jupyter Notebook` | Development environment |

---

## 📁 Project Structure

```
Netflix-Analysis/
├── data/
│   └── netflix_titles.csv
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_exploratory_analysis.ipynb
│   ├── 03_visualizations.ipynb
│   └── 04_insights_summary.ipynb
├── src/
│   ├── utils.py
│   └── visualizations.py
├── outputs/
│   ├── charts/
│   └── reports/
├── requirements.txt
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

- Python 3.10+
- pip / conda

### Installation

```bash
git clone https://github.com/dineshreddypothula/Netflix-Analysis.git
cd Netflix-Analysis

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
```

### requirements.txt

```txt
pandas>=2.0
numpy>=1.24
matplotlib>=3.7
seaborn>=0.12
plotly>=5.15
jupyter>=1.0
notebook>=7.0
```

---

## 📈 Key Visualizations

| Notebook | Charts |
|----------|--------|
| **01 Data Cleaning** | Missing value heatmap, duplicate analysis, type conversion |
| **02 EDA** | Content type pie, release year histogram, top 10 countries bar, rating distribution |
| **03 Visualizations** | Genre treemap, country choropleth, director network, duration boxplots, timeline area chart |
| **04 Insights** | Executive summary dashboard with key metrics |

---

## 🔍 Key Findings (Preview)

- **Movies dominate** (~70% of catalog) but TV Shows growing faster recently
- **USA & India** lead content production; international content rising
- **Drama, Comedy, Action** are top genres across all years
- **2018-2021** saw explosive content acquisition
- **TV-MA & TV-14** are most common ratings
- **Median movie duration:** ~95 minutes; **Median TV show:** 1-2 seasons

---

## 📄 License

MIT License — free to use and adapt.

---

## 👨‍💻 Author

**Dinesh Reddy Pothula**  
Data Analytics • Python • Visualization  

[GitHub](https://github.com/dineshreddypothula) • [LinkedIn](https://www.linkedin.com/in/dinesh-reddy-pothula/)