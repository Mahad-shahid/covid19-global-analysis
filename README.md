🦠 COVID-19 Global Data Analysis — SQL + Python

Analysis of 350,000+ global COVID-19 records using SQL queries inside
Python to investigate case fatality rates, continental death patterns,
and vaccination rollout progress across major nations.

 Project Overview
Using the Our World in Data COVID-19 dataset, this project loads data
into a SQLite database and uses SQL as the primary analysis tool —
covering global totals, continent comparisons, country-level death
rates, and vaccination timelines for key nations including Pakistan.

 Key Findings
- Global case fatality rate: 0.90% across 771 million cases
- Africa and South America had the highest death rates (~1.97%)
  — nearly double Europe (0.83%) reflecting healthcare capacity gaps
- Peru (4.90%) and Mexico (4.35%) had the highest fatality rates
  among countries with 100,000+ cases
- USA recorded 1.13M deaths — highest of any single nation despite
  having among the best healthcare infrastructure globally
- Qatar and UAE exceeded 100% vaccination rate due to large migrant
  worker populations not reflected in official census figures
- Pakistan achieved 59.57% full vaccination — strong result given
  resource constraints, though death rate (1.94%) remained higher
  than USA, UK, India and Germany
- Higher vaccination coverage did not always correlate with lower death
  rates — timing of rollout and variant exposure were equally critical

 SQL Techniques Demonstrated
- Aggregate functions: `MAX`, `SUM`, `ROUND`, `COUNT`
- CTEs (Common Table Expressions) for multi-step queries
- `HAVING` clause for filtering aggregated results
- Death rate calculation using nested aggregations
- Multi-country comparative queries with `GROUP BY`

 Project Structure
- Phase 1 — Global overview (SQL queries for worldwide totals)
- Phase 2 — Death rate analysis by country and continent
- Phase 3 — Vaccination progress analysis and timeline
- Phase 4 — Visualizations (6 charts covering all dimensions)

 Tech Stack
- Python
- SQLite3
- Pandas
- Matplotlib
- Seaborn
- NumPy

 How to Run
1. Install dependencies
   pip install pandas matplotlib seaborn numpy
2. Download the dataset from Kaggle:
   https://www.kaggle.com/datasets/caesarmario/our-world-in-data-covid19-dataset
3. Upload `owid-covid-data.csv` to your Colab session
4. Run all cells in order

 Data Source
Our World in Data — COVID-19 Dataset
350,000+ rows covering 200+ countries from January 2020 to October 2023
