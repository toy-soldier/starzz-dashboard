# STARZZ Dashboard

*A statistics dashboard for astronomy data.*

This project is part of my **STARZZ series**.

It demonstrates my ability to **analyze structured datasets using statistical methods and clear visualizations**. The goal is to show how I extract insights, highlight meaningful patterns, and communicate findings in a way that stakeholders can understand — even when working with science-inspired data.

---

## Executive Summary

In this project, I demonstrate how to perform **statistical analysis and visualization** using a synthetic astronomy dataset:

- Explore stars, constellations, and galaxies.
- Run descriptive statistics, distributions, correlations, and regressions.

I split the dashboard into multiple notebookks for clarity.

---

## Dataset

This project uses a database of fictional galaxies, constellations and stars.  

Here is a diagram to describe the tables and their relationships:

![Datasets used chart showing 4 datasets combined for analysis](assets/schema.png)

- **users** → common user information.
- **galaxies** → mix of spiral, elliptical, irregular, with distances, redshift, and mass.  
- **constellations** → list of constellations, linked to galaxies.  
- **stars** → brightness, spectral type, distance, temperature; linked to constellations.

Stars are located in constellations, which are in turn located in galaxies.

The **galaxies**, **constellations** and **stars** tables contain the additional
fields `added_by` and `verified_by` to indicate the id of the users who discovered and verified it, respectively.

---

### Data Quality Note

To keep this project realistic, I injected intentional “mess” into the CSVs (typos, missing values, invalid ranges, orphan records).  
This demonstrates my ability to detect and clean noisy datasets — a core part of analytics work — before moving into descriptive and inferential statistics.  

---

## Tools

- **Jupyter Notebook** (analysis + storytelling)  
- **Pandas** (data manipulation)  
- **Seaborn** (statistical visualization)  
