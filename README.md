# Weather Inquiry - Rain in Vancouver vs Seattle

> A regional exploration of the amount of rain in the Salish Sea Basin
> With the intent to undertand, does it rain more in Vancouver or Seattle?

---

## Project Overview

This project aims to explore differences in percipitation, specifically rainfall, within the metro areas of Vancouver and Seattle. Through this work we will be determining what the difference in overall rainfall is, but, moreover, determining the nuances of rainfall caused by the changes in geographic location around the coast of the Salish Sea. 

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
- **Description:** Brief overview of the dataset features, size, and format
- **License:** (if applicable)

---

## Analysis

All analyses were conducted in JupyterLab using Python 3.11.3 with the Conda base kernel. Code was organized within a single notebook and should be run from top to bottom, running each modular cell in sequence. 

---

## Results

In short, it rains more in Vancouver than Seattle, with an averall average of 0.158 vs 0.113 inches per year, respectively. Seattle, however, sees a larger proportion of month with "rainy days" per month, dates where some percipitation was recorded. Vancouver dominated months with more mean percipitation in the spring and summer months, while Seattle dominates months in the fall; winters are roughly similar. See Weather_final.ipnyb code within the jupyter notebook OR Final_Report.pdf for more indepth explanations. 

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
