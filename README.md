# 🏏 T20 World Cup Player Analysis

A Python-based data analysis project focused on analyzing **T20 World Cup player performances**, with separate analysis of batting and bowling statistics.

## 📌 Project Overview

This project uses T20 World Cup match data stored in JSON files to clean, transform, analyze, and extract insights from player performance data.

The analysis covers:

* Match summaries
* Batting performance
* Bowling performance
* Player information
* Top run scorers
* Top wicket-takers

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* JSON
* Jupyter Notebook

## 📂 Dataset

The project works with the following JSON datasets:

* `t20_wc_match_results.json`
* `t20_wc_batting_summary.json`
* `t20_wc_bowling_summary.json`
* `t20_wc_player_info.json`

## 🔍 Analysis Performed

### Match Analysis

* Loaded and structured match summary data.
* Checked dataset shape, duplicates, and missing values.
* Converted match dates into datetime format.
* Classified matches into **Qualifier** and **Super12** stages.
* Exported the processed match summary to CSV.

### 🏏 Batting Analysis

* Combined batting records from multiple matches into a single DataFrame.
* Performed data quality checks and type conversions.
* Created an `out` indicator based on dismissal information.
* Cleaned batting strike-rate values.
* Removed unnecessary columns and special characters from player names.
* Linked batting records with match IDs.
* Calculated total runs for each batsman.
* Identified and visualized the **Top 5 run scorers** using Matplotlib.
* Exported the processed batting data to CSV.

### 🎯 Bowling Analysis

* Combined bowling records from multiple matches into a single DataFrame.
* Performed exploratory data checks.
* Separated overs into overs and balls.
* Converted numerical columns to appropriate data types.
* Calculated total balls bowled.
* Calculated total wickets for each bowler.
* Linked bowling records with match IDs.
* Removed unnecessary columns.
* Identified and visualized the **Top 5 wicket-takers** using Matplotlib.
* Exported the processed bowling data to CSV.

### 👤 Player Information

* Loaded player information from JSON.
* Cleaned player names and removed captain indicators.
* Checked for duplicates and missing values.
* Removed unwanted special characters.
* Exported cleaned player information to CSV.

## 📊 Key Outputs

The analysis produces:

* Top 5 batsmen by total runs
* Top 5 bowlers by total wickets
* Cleaned batting dataset
* Cleaned bowling dataset
* Processed match summary
* Cleaned player information dataset

## 📁 Project Structure

```text
T20-WC-Player-Analysis/
│
├── T20 WC Analysis.ipynb
│
├── t20_json_files/
│   ├── t20_wc_match_results.json
│   ├── t20_wc_batting_summary.json
│   ├── t20_wc_bowling_summary.json
│   └── t20_wc_player_info.json
│
├── matchsummary.csv
├── battingsummary.csv
├── bowlingsummary.csv
└── playerInformation.csv
```

## 🚀 How to Run

1. Clone the repository.
2. Place the T20 World Cup JSON datasets in the appropriate folder.
3. Open `T20 WC Analysis.ipynb` in Jupyter Notebook or JupyterLab.
4. Update the dataset paths according to your local directory.
5. Run the notebook cells sequentially.

## 📌 Project Focus

The primary objective of this project is to demonstrate **Python-based sports data analysis**, including data cleaning, transformation, exploratory analysis, aggregation, and visualization of T20 World Cup player performance.
