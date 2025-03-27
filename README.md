# CS Skin Market Analysis

CS Skin Market Analysis is a data-driven study that examines the impact of professional tournament usage on CS skin prices. The project aims to determine whether skins used by top teams during tournaments experience a price increase compared to the off-season.

## Data Sources
- **Skin Loadouts:** Retrieved from cs2proskin.com, listing skins used by the top 12 teams in the BLAST Open Spring 2025.
- **Skin Prices:** Collected from csgoskins.gg, recording values in December 2024 (off-season) and March 2025 (during the tournament).

## Analysis
### Objective:
- Compare skin values between December 2024 and March 2025.
- Analyze the correlation between skin popularity and price increase.
- Determine if tournament exposure impacts skin prices.

### Methodology:
- **Paired t-test:** To check if the difference in skin prices between the off-season and tournament period is statistically significant.
- **Pearson Correlation:** To measure the relationship between the number of times a skin was used by pros and its price increase.

## Results
- **Paired t-test:** Confirmed that skin prices generally increase during tournaments.
- **Pearson Correlation (0.2964, p = 0.0051):** Shows a weak positive correlation between skin popularity and price increase.

## Features
- Statistical comparison of skin prices between off-season and tournament period.
- Visualization of price changes and correlation analysis.
- Dataset with skin names, types, and price values.
- Jupyter Notebook with complete analysis.

## Setup Instructions
### Requirements:
- Python 3.7+
- Pandas, Matplotlib, Seaborn, SciPy

### Installation:
Clone this repository or download the source code:

```bash
git clone https://github.com/yourusername/CS_Skin_Market_Analysis.git
cd CS_Skin_Market_Analysis
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the analysis:

```bash
jupyter notebook DMProject.ipynb
```

## Scope of Project
This study focuses on skins used by **top 12 teams** in **BLAST Open Spring 2025** and price data from a single off-season period (December 2024). Other external market factors are not considered.

## Credits
**Developed by:** Adrian D Silva
Email: adriansdsilva@gmail.com
GitHub: [LeoSeeker526](https://github.com/LeoSeeker526)  

## License
This project is open-source and available under the MIT License. You are free to use, modify, and distribute it as long as proper credit is given.

