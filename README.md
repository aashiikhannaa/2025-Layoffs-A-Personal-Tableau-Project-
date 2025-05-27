# 2025 Tech Layoffs Data Visualization

This repository contains the Tableau workbook and cleaned dataset used to analyze and visualize global tech layoffs in 2025.

---

## Contents

- `2025_Tech_Layoffs_Cleaned.csv` — The cleaned and preprocessed layoffs data file used for visualization.
- `2025Layoffs.twbx` — Tableau Packaged Workbook with multiple visualizations and a dashboard built from the cleaned data.

---

## Data Source

The layoffs data was sourced from [layoffs.fyi](https://layoffs.fyi/), a community-driven platform that tracks and aggregates tech layoffs from company announcements and news reports.

---

## Project Overview

The project focuses on visualizing layoffs data across various dimensions such as:

- Monthly layoffs trends in 2025
- US vs Non-US layoffs comparison
- Layoffs by company stage and industry
- Geographic distribution of layoffs on maps
- Other insightful charts like pie charts, area charts, and bar charts

The goal is to provide a clear, interactive dashboard for understanding global layoffs dynamics through 2025.

---

## How to Use

1. **Download the files** from this repository.
2. **Open the Tableau workbook (`.twbx`)** using [Tableau Desktop](https://www.tableau.com/products/desktop) or [Tableau Public](https://public.tableau.com/).
3. The workbook is already connected to the included cleaned CSV dataset, so you can explore and interact with the visualizations immediately.
4. Feel free to modify or extend the dashboard for your own analysis.

---

## Data Preprocessing

- Data was preprocessed using Python to:
  - Filter records only from 2025
  - Extract month names in full text (January, February, etc.)
  - Remove `$` and `%` symbols from relevant numeric columns
  - Create a binary region column (US / Non-US)
  - Remove unnecessary columns like `Source`
  - Fill missing values for cleaner analysis

---

## Dependencies & Requirements

- Tableau Desktop (version 2025.1.2 recommended) or Tableau Public for opening and interacting with the workbook
- Python environment used for preprocessing (code not included in this repo but preprocessing steps are described above)

---

## License

This project is shared for educational and analytical purposes. Feel free to use and adapt the visualizations as needed.

---


*Happy analyzing!*
