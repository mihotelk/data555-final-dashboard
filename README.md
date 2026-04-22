# Diabetes Death Dashboard

An interactive dashboard exploring provisional diabetes-related mortality trends in the United States during 2020.

**Live Dashboard:**  
https://mihotelk.github.io/data555-final-dashboard/

---

## Overview

This dashboard presents provisional diabetes-related death counts in the United States for 2020. It highlights both temporal trends and demographic differences across age groups and sex.

The visualizations allow users to explore how mortality patterns change over time and across populations using interactive charts.

---

## Why This Matters

Understanding when mortality increased and which populations were most affected can support public health surveillance and targeted intervention strategies.

---

## Dataset

This project uses the CDC provisional diabetes death counts dataset for 2020.

- Includes deaths where diabetes is recorded as:
  - an **underlying cause**, or  
  - a **multiple cause of death**
- Data collected through national mortality reporting systems in the United States
- Represents the U.S. population in provisional death reporting
- Focuses on deaths reported during calendar year 2020

---

## Features

- Interactive time series visualization (monthly trends)
- Grouped bar chart comparing age groups and sex
- Hover tooltips for detailed exploration
- Interactive data table showing raw dataset sample

---

## Methods

- Data cleaning and transformation performed in **R**
- Visualization built using:
  - `plotly` for interactive charts
  - `flexdashboard` for layout and deployment
- Dataset processed using `tidyverse`

## Repository Structure

``` id="d0lgvt"
data555-final-dashboard/
│── index.Rmd        # Dashboard source code
│── index.html       # Rendered dashboard (GitHub Pages)
│── data/            # Dataset (if included)
│── README.md        # Project documentation
