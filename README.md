# Python-WhatsApp-Data-Analysis

**Exploratory Data Analysis of WhatsApp Global Usage and Privacy Metrics**

## Project Overview

This project analyzes a global dataset of WhatsApp accounts leaked in a security study conducted by IT-Security researchers from the University of Vienna and SBA Research. The study uncovered a vulnerability in WhatsApp's contact discovery mechanism, exposing metadata for over 3.5 billion accounts worldwide. This analysis explores platform adoption, privacy behaviors, business usage, and multi-device patterns across countries and continents.

---

## Dataset

The dataset contains the following columns:

| Column | Description |
|--------|-------------|
| Country | Name of the country |
| Accounts | Total WhatsApp accounts in the country |
| Global Share | Percentage of global WhatsApp accounts |
| Accounts Per 100 Capita | WhatsApp penetration per 100 people |
| Android | Percentage of Android users |
| iOS | Percentage of iOS users |
| Picture | Percentage of users with public profile pictures |
| Status | Percentage of users with public status messages |
| Business | Percentage of users using WhatsApp Business |
| Companions | Average number of linked devices per user |

---

## Project Structure

```
Python-WhatsApp-Data-Analysis/
│
├── data/
│ ├── raw_whatsapp-data.csv
│ ├── clean_whatsapp.csv
│
├── report/
│ └── WhatsApp_Global_Usage_Analysis.pdf
│
├── Charts/
│ └── All generated visualizations (OS usage, privacy, penetration, correlation, etc.)
│
├── notebook/
│ └── WhatsApp_Global_Usage_Analysis.ipnyb
│
├── requirements.txt
│
└── README.md
```
---

## Key Analyses

1. **WhatsApp Penetration:** Identified countries with the highest per-capita usage.  
2. **Global Usage:** Ranked countries by total WhatsApp accounts and global share.  
3. **Operating System Adoption:** Analyzed Android vs iOS usage by continent.  
4. **Privacy Behavior:** Examined profile picture and status visibility across regions.  
5. **Business Usage:** Highlighted countries with the highest WhatsApp Business adoption.  
6. **Companion Devices:** Explored correlations between platform type and multiple devices.  
7. **Correlation Analysis:** Studied relationships among numeric metrics like penetration, OS, privacy, business, and companions.  
8. **Outliers & Anomalies:** Detected small islands with unusually high penetration, iOS-dominant regions, and extreme companion device usage.

---

## Visualizations

- Bar charts for top countries by penetration and total accounts.  
- Continent-wise OS usage comparison.  
- Heatmap of correlation matrix for numeric metrics.  
- Privacy behavior and companion device distribution charts.  

All charts are saved in the `Charts/` folder.

---

## Tools & Libraries

- Python 3.x  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- pycountry-convert  

---

## Conclusion

This analysis provides insights into global WhatsApp usage patterns, privacy behaviors, and technology adoption trends. It demonstrates the power of Python for exploratory data analysis and data visualization in real-world, security-related datasets.
