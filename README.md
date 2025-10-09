# Weather Inquiry - Rain in Vancouver vs Seattle

> A regional exploration of the amount of rain in the Salish Sea Basin.
> With the intent to undertand, does it rain more in Vancouver or Seattle?

---

## Project Overview

This project aims to explore differences in precipitation, specifically rainfall, within the metro areas of Vancouver and Seattle. Through this work we will be determining what the difference in rainfall is. Moreover, we shall determine the nuances of rainfall of season rainfall within each location around the coast of the Salish Sea. 

- **Objective:** Does it rain more in Vancouver or Seattle?
- **Domain:** Enviromental/Metereological Iquiry.
- **Key Techniques:** Descriptive Statistics (Mean, Proportion Analysis), Inferential Testing (t-Test).

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

- **Source:** NOAA Climate Data Online Portal [(https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND)](https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND)
- **Description:** The working data set used in the analysis phase was compiled from two data sets based on single, representative, weather stations within each metro area. The working data set has values, date,	city,	precipitation,	day_of_year, and is titled 'clean_seattle_vancouver_weather.csv'. This working data is 3316 rows × 4 columns and contains no NaN values. The origional data sets have values STATION, NAME, DATE, DAPR, MDPR, PRCP, SNO, SNWD, WESD, WESF for Seattle and STATION, NAME, DATE, PRCP for Vancouver; they are 1658 rows x 10 columns and 1796 rows x 4 columns, respectively. Each contain NaN values. 
- **License:** (if applicable)

---

## Analysis

All analyses were conducted in JupyterLab using Python 3.11.3 with the Conda base kernel. Code was organized within a single notebook and should be run from top to bottom, running each modular cell in sequence. 

---

## Results

In short, it rains more in Vancouver than Seattle, with an averall average of 0.158 vs 0.113 inches per year, respectively. When the proportion of rainy days were assesed, Vancouver saw more overall months with rainy days, concentrated in the spring and summer, while Seattle saw more months with rainy days in the fall and winter. Months with more mean percipitation saw a similar pattern, with Vancouver dominating in the spring and summer months, while Seattle dominates months in the fall; winters are roughly similar. See Weather_final.ipnyb code within the jupyter notebook OR Weather_Report.pdf for more indepth explanations. 

Overall, it can be concluded from this data that Vancouver is rainier city than that of Seattle. 

---

## Authors

- Carter Ellis Webb - [(https://github.com/EllisWebb)](https://github.com/EllisWebb)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Tools/libraries used: pandas, numpy, matplotlib.pyplot, seaborn, and scipy.
- Tutorials or papers referenced
- Inspiration or collaborators: Inspiration came from courswork completed in DATA 5100 01 25FQ Foundations of Data Science, Seattle University; pursuant to the Master's of Science: Data Science diploma. 
