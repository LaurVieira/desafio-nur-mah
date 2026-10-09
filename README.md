# Nur Mah Museum: Market Intelligence

## Overview

This project presents an exploratory and predictive analysis of the financial health and geographic distribution of cultural institutions in the United States. The goal is to extract insights from public IMLS data to support the fundraising and partnership strategy of the **Nur Mah Museum**.

## Key Insights and Recommendations

The analysis identified three strategic fronts:

1. **Realistic goals:** fundraising targets should use the median revenue of Art Museums as a baseline.
2. **Strategic partnerships:** Science Museums and Zoos operate with much higher revenues. Creating hybrid exhibitions is suggested to attract funding from these sectors.
3. **Geographic expansion:** marketing campaigns should focus on highly populated states (such as CA and NY), while also looking for regions with less direct competition.

## Predictive Modeling

A machine learning model based on a **Random Forest Regressor** was built to estimate an institution's revenue from its type and state.

The model works as a baseline and shows that a museum's financial success depends on external variables that are missing from the dataset, such as marketing investment, local tourism and prestige.

## Tech Stack

- **Language:** Python 3
- **Data manipulation:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Machine learning:** Scikit-Learn (Random Forest, OneHotEncoder)
- **Environment:** Jupyter Notebook (VS Code)

## Project Structure

```
.
├── nur_mah_analysis.ipynb   # Main notebook: analysis, charts and machine learning model
├── data/
│   └── museums.csv          # Original dataset
├── requirements.txt         # Python dependencies
└── README.md                # Project documentation
```

## Getting Started

### Prerequisites

- Python 3 installed
- VS Code or Jupyter

### Running the project

1. Clone the repository.
2. (Optional) Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open `nur_mah_analysis.ipynb` in VS Code or Jupyter.
4. The first cell of the notebook installs the required libraries.
5. Click **Run All** to see the analyses and the generated charts.

## Author

Laura Vieira ([@LaurVieira](https://github.com/LaurVieira))
