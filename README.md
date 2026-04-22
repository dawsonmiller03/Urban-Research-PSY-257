# Urban Influence Analysis
A research project investigating the impact of urban environments on socio-economic and environmental metrics through R-based statistical modeling and spatial visualization.

---

## 👥 Research Team

| Role | Name | Email |
|---|---|---|
| Principal Investigator | Dawson Miller | dawsonrmiller03@gmail.com |

**Institution:** Gordon College  
**Status:** Completed (May 2025)

---

## 📄 Project Overview

The goal of this project was to analyze how specific urban factors influence environmental and socio-economic outcomes. By processing raw urban datasets, this workflow identifies key correlations and trends using spatial data, distribution analysis, and comparative modeling.

**Key Objectives:**
* Process and clean raw urban datasets for statistical reliability.
* Explore correlations between urban density and target metrics.
* Visualize findings through spatial heat maps and comparative box plots.

---

## 🧪 Analysis Methodology

### Statistical Approach
The analysis was conducted using R, focusing on exploratory data analysis (EDA) followed by formal statistical modeling. The workflow includes:
* **Initial EDA:** Handled in `urban.Rmd` to identify outliers and distribution patterns.
* **Refined Modeling:** Finalized in `Final_Urban_Influence.Rmd`, utilizing R-based modeling to generate core insights.

### Visualization Strategy
Data insights are communicated through a multi-modal visualization suite:
* **Correlation:** Scatter plots to identify relationships between variables.
* **Distribution:** Box plots (`AE_Box`, `SE_Box`, `Total_Box_Plot`) to compare distributions across urban categories.
* **Density:** Heat maps to visualize spatial or correlation density within the data.

---

## 📁 Repository Structure
urban-influence-analysis/
│
├── Data/
│   ├── urban.csv                 # Raw input data
│   ├── final_urban_data.csv      # Cleaned/transformed dataset
│   └── final_urban_data_2.csv    # Transformed dataset for final models
│
├── Analysis Scripts/
│   ├── urban.Rmd                 # Initial Exploratory Data Analysis (EDA)
│   └── Final_Urban_Influence.Rmd # Primary R Markdown with final models
│
├── Visualizations/
│   ├── heat_map.png              # Spatial/correlation density map
│   ├── Scatter_Plot.png          # Key variable correlation analysis
│   ├── Total_Box_Plot.png        # General distribution overview
│   ├── AE_Box.png                # Distribution of AE metrics
│   ├── SE_Box.png                # Distribution of SE metrics
│   └── Bar_Graph.png             # Categorical breakdown of findings
│
├── .gitignore
└── README.md
---

## 🛠️ Technology Stack

- **Language:** R
- **Key Libraries:** `tidyverse`, `ggplot2`, `dplyr`, `rmarkdown`
- **Environment:** RStudio

---

## 🚀 How to Run the Analysis

1. **Prerequisites:** Ensure you have R and RStudio installed on your machine.
2. **Clone the Repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/urban-influence-analysis.git](https://github.com/YOUR_USERNAME/urban-influence-analysis.git)

---

## 📄 License
Internal research project — Gordon College, 2025.
