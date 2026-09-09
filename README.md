# Seasonal Performance Study of Indian Farms

An independent data-analytics investigation into how season shapes agricultural
performance, built for the AICTE/VOIS Major Project brief on Seasonal
Agriculture Performance Analysis.

## Guiding Questions
1. Does the season a crop is grown in meaningfully change its yield and profitability?
2. What resource and environmental factors move together with performance?
3. Are seasonal patterns consistent across states, or do they vary regionally?
4. Where is the financial and agronomic risk concentrated?

## Dataset
`data/seasonal_agriculture_performance_dataset.csv` — 4,000 farm-level records
across 8 states, 8 crops and 3 growing seasons (Kharif, Rabi, Zaid), covering
environmental conditions, resource usage, yield, and financial outcomes.

## Contents
| Path | Description |
|---|---|
| `notebook/Seasonal_Agriculture_Original_Analysis.ipynb` | Full analysis: cleaning, EDA, seasonal comparisons, and three original follow-up investigations |
| `data/seasonal_agriculture_performance_dataset.csv` | Source dataset |
| `slides/VOIS_Major_Project_PPT_Original_Analysis.pptx` | Project submission slide deck |

## Key Findings
- Kharif consistently outperforms Rabi and Zaid on both yield and profit;
  Zaid is the only season with a net loss and the highest share of
  loss-making farms.
- Water efficiency tracks yield far more closely than rainfall or fertilizer dose.
- Regional performance is inconsistent across seasons — Tamil Nadu holds a
  steady mid-table rank in every season, while Punjab swings from #1 (Rabi)
  to last (Kharif).
- Average profit scales with farm size, but yield per hectare stays roughly
  flat across size groups — profit growth appears driven mainly by land
  area rather than efficiency.
- Disease/pest risk concentrates heavily in Kharif, peaking with Wheat (~55.6%).

See the notebook's closing sections for the full list of insights,
recommendations, and limitations.

## Running the Notebook
Open `notebook/Seasonal_Agriculture_Original_Analysis.ipynb` in
[Google Colab](https://colab.research.google.com/). The data-loading cell
will prompt a file upload if the CSV isn't already present — select
`seasonal_agriculture_performance_dataset.csv` when asked.

## Tech Stack
Python 3 · Pandas · NumPy · Matplotlib · Seaborn · Google Colab / Jupyter Notebook
