# IMDB Movies Analysis

## Project Overview
This project explores **IMDB movie data** containing **10,000+ records**, focusing on:
- **Data cleaning** (missing values, duplicates)
- **Exploratory Data Analysis (EDA)**
- **Visualization** of budget, revenue, profit, and runtime trends
- Identifying **top-performing movies**, **profitable release windows**, and **genre trends**

The analysis produces **industry-level insights** that can guide decision-making for studios, distributors, and marketers.

---

## Objectives
- Clean and preprocess the IMDB dataset for analysis.
- Explore relationships between **budget, revenue, runtime, genre, and profitability**.
- Identify which **genres** and **months** drive the highest revenue and profit.
- Visualize patterns & trends to support movie industry strategies.

---

## Dataset
- **Source**: IMDB-based movies dataset (scraped/aggregated from public sources)
- **Size**: 10K+ movie records
- **Key Columns**:
  - `Title`
  - `Genre`
  - `Release_Date`
  - `Budget`
  - `Revenue`
  - `Runtime`
  - `IMDB_Rating`
  - `Votes`
  - `Director`

---

## Project Workflow

### 1️⃣ Data Cleaning & Preparation
- Removed duplicate records.
- Imputed or removed missing values for budget, revenue, and runtime.
- Converted release dates to datetime format and extracted **month & year**.
- Standardized genres (e.g., handling multiple-genre entries).
- Derived new columns:
  - **Profit** = Revenue - Budget
  - **Profit Margin %**

### 2️⃣ Exploratory Data Analysis
Key analyses performed:
- Distribution of **budget, revenue, and profit**.
- Relationship between **budget & revenue**.
- Profit trends by **release month & year**.
- Average runtime trends across decades.
- Genre-level comparisons for profitability.

### 3️⃣ Data Visualization
Using **Matplotlib** and **Seaborn**:
- **Histograms** — Revenue, budget, runtime.
- **Scatterplots** — Budget vs revenue.
- **Bar charts** — Top 10 highest-grossing movies.
- **Heatmaps** — Correlation between numerical features.
- **Boxplots** — Profit by genre and release month.

---

## Key Insights
- **Top-grossing & most profitable films** tend to release in **May–July** and **December**.
- Certain **genres (Action, Adventure, Sci-Fi)** dominate revenue charts.
- **Runtime sweet spot**: 110–130 minutes for top performers.
- Higher budgets generally lead to higher revenues, but not always higher profitability.
- **Small-budget drama/thrillers** can have very high profit margins.

---

## Tools & Technologies
| Tool / Library  | Purpose |
|-----------------|---------|
| **Python**      | Analysis & processing |
| **Pandas**      | Data cleaning & manipulation |
| **NumPy**       | Numerical operations |
| **Matplotlib**  | Data visualization |
| **Seaborn**     | Statistical plotting |
| **Google Collab** | Interactive analysis |

---

## Visualization Samples
<img width="1470" height="1589" alt="download" src="https://github.com/user-attachments/assets/654fd5e4-0459-4d79-af67-cc276350b052" />

---

