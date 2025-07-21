# Shark Tank India Season 1 — Startup Investment Analysis

This project presents an end-to-end data analysis of investments made during **Shark Tank India Season 1**. The goal is to understand funding patterns, identify top-performing sectors, and evaluate individual contributions by each shark.

---

## Objective

- Clean and preprocess the raw Shark Tank dataset
- Convert deal status and investor entries to machine-readable format
- Extract funding amounts and individual shark contributions
- Visualize key trends using insightful charts

---

## Dataset Overview

The dataset includes startup-level information such as:

- **Brand**: Name of the startup
- **Industry/Genre**: Sector the startup operates in
- **City** / **State**: Location of the business
- **Deal**: Whether a deal was finalized (Yes/No)
- **Funding**: Total investment offered and equity percentage
- **Shark Columns**: Presence of sharks in each deal (`Namita`, `Anupam`, `Vineeta`, `Aman`, `Peyush`, `Ghazal`) marked as `X` or blank

Derived columns:
- `Funding_Amount_Lakhs`: Cleaned numeric funding value
- `Shark_Investment_Lakhs`: Estimated contribution per shark (assuming equal split)

---

## Tools Used

- **Python**
- **Pandas** for data manipulation
- **Matplotlib** and **Seaborn** for visualizations
- **Google Colab / Jupyter Notebook** for interactive development

---

## Key Visualizations

- Top 10 industries by number of funded startups
- Pie charts showing sector distribution for each shark
- Total investments per shark
- Individual deal-level contributions

---

## How to Run

1. Clone this repository:
git clone https://github.com/your-username/shark-tank-analysis.git
2. Open `Shark_Analysis.ipynb` in Jupyter or Google Colab
3. Upload `Season1_Shark_Tank_Data.csv` if not already present
4. Run all cells to explore insights and visuals
5. You can modify the variable `shark_name = "Aman"` to view breakdowns for any other shark

---

## 📂 Folder Structure

.
├── Season1_Shark_Tank_Data.csv
├── Shark_Analysis.ipynb
├── Aman_Investments.csv
├── visuals/
│ ├── top_industries.png
│ ├── individual_shark_pies/
│ ├── aman.png
│ └── vineeta.png
└── README.md
---

## 👩‍💻 Author

**Dhrumi Shah**  
Data Analyst | Visualization Enthusiast | Python Lover  
📎 [LinkedIn](https://www.linkedin.com/in/dhrumishah23/)  
---

