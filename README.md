# COVID-19 Impact Analysis

## Overview
This repository contains data analysis and visualizations examining the impact of COVID-19 across various sectors, with a focus on case tracking, hospital utilization, and transportation impacts. The analysis is primarily conducted through a Jupyter notebook that processes multiple COVID-19 datasets.

## Project Contents
- `AAAA(COVID).ipynb`: Main Jupyter notebook containing the COVID-19 data analysis
- Time series datasets:
  - `time_series_covid_19_confirmed.csv`: Global time series of confirmed COVID-19 cases
  - `time_series_covid_19_confirmed_US.csv`: US-specific time series of confirmed cases
  - `covid19_data.csv` and `covid_19_data.csv`: COVID-19 case data
- Impact analysis data:
  - `covid_impact_on_airport_traffic.csv`: Analysis of how the pandemic affected airport traffic
  - `reported_hospital_utilization_timeseries_20.csv`: Time series data on hospital utilization during the pandemic
- Regional data:
  - `all-states-history.csv`: Historical COVID-19 data for all US states
  - `georgia-history.csv`: Georgia-specific COVID-19 historical data

## Analysis Focus
This project examines several key aspects of the COVID-19 pandemic:
- Temporal patterns in COVID-19 case progression
- Impact on transportation systems, particularly airport traffic
- Hospital resource utilization over time
- Regional variations in pandemic impact, with special focus on US states and Georgia

## Using This Repository
1. Clone the repository:
```bash
git clone https://github.com/pngo5/covid_impact.git
cd covid_impact
```

2. Open the main analysis notebook:
```bash
jupyter notebook "AAAA(COVID).ipynb"
```

3. Explore the datasets:
   - CSV files can be viewed directly in Excel, Google Sheets, or any data analysis tool
   - The notebook contains visualizations and analysis of these datasets

## Data Sources
The datasets in this repository are compiled from authoritative sources tracking COVID-19 statistics:
- Johns Hopkins University CSSE COVID-19 data repository
- US hospital utilization statistics
- Transportation data on airport traffic
- State-level health departments

## Requirements
- Python 3.x
- Jupyter Notebook
- pandas
- matplotlib/seaborn
- numpy

## Future Work
- Update datasets with more recent COVID-19 statistics
- Expand analysis to include vaccination data
- Develop predictive models based on historical patterns
- Include economic recovery indicators

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For questions or collaborations, please open an issue on this repository.
