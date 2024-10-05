# AI-Bootcamp-Project-1

## Overview
This project provides an analysis of the impacts of two specific events - 9/11 and Hurricane Katrina. The data used for the initial analysis ranged from 1983 onwards for the economic factors (GDP, S&P500, Unemployment rate) and from 1985 onwards for the birth rate. 

## Software
The software used for this project was Jupyter notebook and Prophet.

## Data sources
https://www.kaggle.com/datasets/asaniczka/unemployment-rates-by-demographics-1978-2023
https://www.kaggle.com/datasets/henryhan117/sp-500-historical-data
https://www.kaggle.com/datasets/thedevastator/us-monthly-birth-data
https://fred.stlouisfed.org/series/GDPC1 

## Acknowledgements
https://data.world/dataworldadmin for the master birth data referenced by Kaggle


## Repo structure
| Folder/File                   | Description                                      |
|-------------------------------|--------------------------------------------------|
| `resources/`                  | Contains raw and processed data files            |
| `resources/birthdata/`        | Contains cleaned birthdata files                 |
| `resources/images`            | Graphs from the final presentation               |
| `birthdata_master.ipynb`      | Analysis notebook for master birth data          |
| `birthdata_analysis.ipynb`    | Analysis notebook for birthdata                  |
| `GDP_data_visualization.ipynb`| Analysis notebook for GDP Data                   |
| `S&P500_data.ipynb`           | Analysis notebook for S&P500 Data                |
| `unemployment_data.ipynb`     | Analysis notebook for Unemployment Data          |
| `README.md`                   | Project overview and instructions                |
| `requirements.txt`            | List of project dependencies                     |
|-------------------------------|--------------------------------------------------|


## Instructions
1. Birth: Run the `birthdata_master.ipynb` followed by the `birthdata_analysis.ipynb`.
2. GDP: Run the `GDP_data_visualization.ipynb` for GDP data analysis.
3. S&P500: Run the `S&P500_data.ipynb` for S&P500 data analysis.
4. Unemployment: Run the `unemployment_data.ipynb` for unemployment data analysis.

## Installation
To set up the project environment, follow these steps:
Clone the repository:
   ```bash
   git clone https://github.com/yourusername/AI-Bootcamp-Project-1.git
   cd AI-Bootcamp-Project-1
   python3 -m venv env
   source env/bin/activate
   pip install -r requirements.txt