# Autonomous Vehicles Strategy & Ethics Analysis

## Overview

This repository contains a Quarto book project that analyzes consumer sentiment regarding Autonomous Vehicles (AVs). The analysis leverages survey data to provide strategic recommendations on scaling AV technology and navigating ethical/regulatory landscapes.

## Project Structure

  * **`index.qmd`**: Preface and landing page.
  * **`intro.qmd`**: Industry overview, Porter's 5 Forces, and data description.
  * **`objectives_1.qmd`**: Analysis of Willingness to Pay (WTP), Confidence, and Scaling Strategy.
  * **`objectives_2.qmd`**: Analysis of Consumer Concerns, Regulation preferences, and Liability.
  * **`conclusion.qmd`**: Final strategic synthesis.
  * **`data/`**: Contains the `AVsurvey.csv` and questionnaire documents.

## Key Technologies

  * **Language:** R
  * **Framework:** Quarto (renders to HTML, PDF, DOCX)
  * **Libraries:** `tidyverse`, `plotly` (interactive plots), `gtsummary` (publication-ready tables), `ggthemr` (scientific plotting themes).

## How to Run

1.  Ensure you have R and Quarto installed.
2.  Install required packages:
    ```r
    install.packages(c("tidyverse", "plotly", "ggpubr", "rstatix", "gtsummary", "gt", "broom", "ggthemr", "fresh", "tidytext", "wordcloud", "DT"))
    ```
3.  Render the book:
      * **HTML:** `quarto render` or `quarto preview`
      * **PDF:** `quarto render --to pdf`

## Features

  * **Hybrid Rendering:** Automatically switches between interactive Plotly charts for HTML and static ggplot2 charts for PDF/Word to ensure compatibility.
  * **Statistical Rigor:** Includes ANOVA, T-tests, and Chi-Square tests formatted with `gtsummary`.
  
## References

  * Quarto Documentation: [https://quarto.org/docs/](https://quarto.org/docs/)
  * Plotly for R: [https://plotly.com/r/](https://plotly.com/r/)
  * gtsummary Package: [https://www.danieldsjoberg.com/gtsummary/](https://www.danieldsjoberg.com/gtsummary/)
  * ggthemr Package
  * Tidyverse: [https://www.tidyverse.org/](https://www.tidyverse.org/)
  * R Statistical Software: [https://www.r-project.org/](https://www.r-project.org/)
  * Google Gemini 3 for framing analysis
  * Notebooklm by Google for research assistance