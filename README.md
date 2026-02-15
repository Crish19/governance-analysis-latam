# Governance Indicators Analysis: Latin America (2010-2023)

## Overview
This project analyzes governance trends across five Latin American countries using World Bank's Worldwide Governance Indicators (WGI). The analysis examines changes in governance quality over a 13-year period to identify which countries improved or declined.

## Research Questions
1. Which country improved the most in governance?
2. Which governance dimension is weakest in the region?
3. How did each country perform across different governance indicators?

## Data Source
- **Source:** World Bank - Worldwide Governance Indicators (WGI)
- **URL:** https://info.worldbank.org/governance/wgi/
- **Period:** 2010-2023
- **Countries:** Ecuador, Venezuela, Uruguay, Peru, Chile

## Indicators Analyzed
| Indicator | Description |
|-----------|-------------|
| Control of Corruption | Perceptions of corruption in public power |
| Government Effectiveness | Quality of public services and policy implementation |
| Political Stability | Likelihood of political instability or violence |
| Regulatory Quality | Ability to formulate sound policies and regulations |
| Rule of Law | Confidence in and adherence to rules of society |
| Voice and Accountability | Citizens' participation in government selection |

*Note: Indicators range from -2.5 (weak) to +2.5 (strong governance)*

## Key Findings

### Country Performance (2010-2023)
| Country | Avg Change | Status | Indicators Improved |
|---------|------------|--------|---------------------|
| Ecuador | +0.21 | Improved | 6 of 6 |
| Uruguay | +0.13 | Improved | 5 of 6 |
| Peru | -0.06 | Declined | 2 of 6 |
| Venezuela | -0.42 | Declined | 1 of 6 |
| Chile | -0.44 | Declined | 0 of 6 |

### Main Insights
- **Ecuador** showed the strongest improvement, with positive changes across all six governance indicators
- **Chile** experienced the largest decline, with all indicators worsening over the period
- **Rule of Law** was the weakest dimension across the region overall
- Only 2 of 5 countries showed overall governance improvement

## Tools & Skills Used

### Spreadsheet Functions
| Function | Purpose |
|----------|---------|
| AVERAGEIF | Calculate average change per country |
| COUNTIFS | Count indicators that improved |
| MAXIFS / MINIFS | Find best and worst performing indicators |
| INDEX + MATCH | Retrieve indicator names based on values |
| ROUND | Format numerical outputs |
| IF | Classify countries as "Improved" or "Declined" |
| RANK | Rank countries by performance |

### Other Skills
- Conditional formatting (color-coding by status)
- Data visualization (bar charts)
- Pivot tables for data exploration

## File Structure
```
├── README.md
├── 2026-02-15_Governance_LatAm-2010-2023_v01.xlsx
    ├── raw_data (Original WGI data with calculated changes)
    ├── analysis_summary (Country comparison table)
    └── pivot_analysis (Pivot table exploration)
```

## How to Use
1. Download the Excel file
2. Open in Google Sheets or Microsoft Excel
3. Explore the `analysis_summary` tab for key findings
4. Use `pivot_analysis` to explore data interactively

## Author
Created as part of the Google Data Analytics Certificate program.

## License
This project uses publicly available data from the World Bank.
