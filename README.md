# Striatal and Thalamic Sensitivity to Loss Anticipation: How Age Groups Diverge Under the Influence of Psychological Distress 🧠📊

This repository contains the source code and statistical analyses for the research paper of the same name. The project investigates striatal and thalamic sensitivity during loss anticipation, exploring how different age groups diverge under the influence of psychological distress.

The entire workflow is developed in **R** using **Quarto (`.qmd`)** to ensure full reproducibility of the statistical models, data processing, and figures.

## 📋 Prerequisites

To reproduce these analyses, you need **R** (version 4.0 or higher recommended) and **RStudio** (or your preferred editor with the Quarto extension installed).

The script handles package management internally. The primary R packages used in this project include:

*   **Statistical Modeling:** `lme4`, `Matrix`, `emmeans`, `ARTool`, `psych`, `effectsize`, `effsize`, `mclust`, `mousetrap`.
*   **Data Wrangling:** `tidyverse` (`dplyr`, `stringr`), `writexl`.
*   **Data Visualization & Tables:** `ggplot2`, `ggstatsplot`, `ggpubr`, `cowplot`, `ggsignif`, `corrplot`, `corrr`, `gtsummary`, `flextable`, `huxtable`.

## 💾 Data Access

The datasets used in this study are hosted on an **external link**. The `.qmd` file is pre-configured to connect and fetch the required data automatically during runtime, so no manual data downloads are necessary.

## 🚀 How to Reproduce the Analyses

1. **Clone this repository** to your local machine:
   ```bash
   git clone https://github.com
   ```
2. **Open the project** in RStudio.
3. Open the primary Quarto analysis file (the `.qmd` file).
4. Click the **`Render`** button at the top of the RStudio editor panel, or run the following command in your R console:
   ```R
   quarto::quarto_render("Analysis_ROIS_october.qmd")
   ```
5. This process will sequentially run all statistical tests, generate the figures, and compile the final report into an interactive **HTML** document.

## 📄 Repository Structure

*   `*.qmd`: Quarto source file containing the documentation and R code for the statistical analyses.
*   `*.html`: Compiled final report with all results, ready to view in any web browser.
*   `LICENSE`: Legal terms of use under the MIT License.

## 📄 License

This project is licensed under the **MIT License**. You are free to use, modify, and distribute this code. See the `LICENSE` file for more details.
