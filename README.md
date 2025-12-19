# Fitbit Data Analysis
Simple analysis and visualization of Fitbit CSVs, with SQLite-backed tables and Plotly charts.
Using data from multiple users, this project analyzes how factors such as sleep quality, physical activity, and workout habits relate to overall health and workout efficiency.
## Project Structure
Fitbit_Data_Analysis
|
├── Data/Fitbase_Data
│   └── *.csv  <- all CSV files
│
├── Data/fitbitdata.db  <- database file created by notebooks
|
├── Notebooks/
│   └── Data_Cleaning.ipynb
|
├── pictures/
│   └── images and other miscellaneous files
|
├── README.md
|
└── requirements.txt
## Getting Started
- Fork and clone this repository. 
- From project directory
- Create virtual enviroment
- Bash: python -m venv venv
  source venv/Scripts/activate
- mac/linux: python3 -m venv venv
  source venv/bin/activate
- Install requirements.txt: pip install -r requirements.t
- In VS Code, open Notebooks/Data_Cleaning.ipynb and select the python venv kernel
- press the the Run All button (Ctrl+Shift+Alt+Enter) 

## Source
- CSV files were obtained from:
- https://www.kaggle.com/datasets/arashnic/fitbit

## Conclusion
- Some data was insufficient to obtain strong results. Due to how the data was collected, portions may be imperfect and possibly inaccurate.
- Higher physical activity was observed to slightly improve sleep quality.
- Higher intensity, with the same amount of workload, may increase calories burned.

## Notes
- AI tools such as ChatGPT were used for learning, research, and troubleshooting. All content was developed and tested by the user.