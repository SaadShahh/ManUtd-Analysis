# ManUtd Analysis 22/23 Season

An in-depth statistical analysis of Manchester United's performance during the 2022/2023 football season using R and Quarto.

## Overview

This project evaluates Manchester United's performance during the 2022/2023 season. Using data visualization and statistical analysis, the report explores:

- Offensive and defensive performance.
- Home vs. away records.
- Performance against Top 6 teams.
- Key metrics like expected goals (xG) and clean sheets.

## Files in this Repository

- **ManUtdSeasonAnalysis.qmd**: Quarto Markdown file containing the source code for the analysis.
- **ManUtdSeasonAnalysis.html**: Rendered HTML report of the analysis.
- **ManUtd 2023 Match Statistics.csv**: Contains the datasets used for this analysis.
- **README.md**: Documentation for the repository.

## Key Findings

- Manchester United scored 58 goals with an xG of 68, indicating underperformance in finishing.
- The team kept 17 clean sheets, showcasing strong defensive organization.
- Performance against Top 6 teams was mixed, with struggles against Manchester City and Liverpool.
- The team performed significantly better at home compared to away games.

## Requirements

To reproduce the analysis, you'll need:

- **R** (version 4.0 or later)
- **Quarto** (version 1.3 or later)
- R Libraries:
  - `tidyverse`
  - `ggplot2`
  - `dplyr`

## How to Reproduce

1. Clone the repository:
2. Install the required R packages listed in the [Requirements](#requirements).
3. Open the `ManUtdSeasonAnalysis.qmd` file in RStudio or any Quarto-compatible editor.
4. Render the report:
   ```bash
   quarto render ManUtdSeasonAnalysis.qmd
   ```
5. The output will be generated as an HTML file.

## Viewing the Report

If viewing locally, open the `ManUtdSeasonAnalysis.html` file in any web browser.

