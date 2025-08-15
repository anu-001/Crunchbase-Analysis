# Crunchbase-Analysis
# Startup Acquisition Analysis: A Comprehensive Study of Crunchbase Data

The startup ecosystem has experienced unprecedented growth, with acquisitions serving as a critical mechanism for innovation and economic development. Understanding the factors that predict a successful exit is crucial for entrepreneurs, investors, and potential acquirers. This project delves into Crunchbase data to investigate the complex interplay between company characteristics—such as **funding**, **industry**, and **age**—and their influence on acquisition outcomes.

Our analysis provides data-driven insights, demonstrating that factors like higher funding levels and specific industry sectors are significantly associated with a greater likelihood of being acquired.

---

### **Project Structure**

The repository is organized to ensure the analysis is clear and reproducible.
.
├── README.md
├── data/
│   ├── crunchbase_data/
│   └── master_data/
├── outputs/
│   ├── reports/
│   │   ├── analysis_report.pdf
│   │   └── Startup Acquisition Analysis...pdf
│   │   └── index.html
│   ├── images/
│   └── ...
├── scripts/
│   └── index.Rmd


-   **`data/`**: Stores the raw and processed datasets used for the analysis.
-   **`outputs/`**: Contains all final deliverables, including PDF reports and generated PNG images.
-   **`scripts/`**: Houses the R Markdown script (`run_script.Rmd`) that performs the entire analysis.

---

### **Tools and Processes**

The analysis was conducted using **R** and **R Markdown**. The workflow followed a systematic process:

1.  **Data Preparation**: Loading and cleaning raw Crunchbase data.
2.  **Exploratory Data Analysis (EDA)**: Visualizing distributions and relationships between key variables.
3.  **Statistical Analysis**: Performing formal tests, including a **Wilcoxon Rank Sum Test**, **Chi-square test**, and **Mediation Analysis**, to uncover statistically significant relationships.
4.  **Reporting**: Generating the final reports and visual outputs directly from the R Markdown script.

---

### **Downloadable Files**

The full reports and the R Markdown script are available for direct download.

-   **Analysis Report**: [analysis_report.pdf](https://github.com/anu-001/Crunchbase-Analysis/raw/main/outputs/reports/analysis_report.pdf)
-   **Full Report**: [Startup Acquisition Analysis: A Comprehensive Study of Crunchbase Data.pdf](https://github.com/anu-001/Crunchbase-Analysis/raw/main/outputs/reports/Startup%20Acquisition%20Analysis%20A%20Comprehensive%20Study%20of%20Crunchbase%20Data.pdf)
-   **R Markdown Script**: [index.Rmd](https://github.com/anu-001/Crunchbase-Analysis/raw/main/scripts/index.Rmd)