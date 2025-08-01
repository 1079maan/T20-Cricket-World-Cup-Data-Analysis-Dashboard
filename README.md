# T20 Cricket World Cup Data Analysis & Dashboard

## Project Overview
This project showcases an end-to-end data analytics pipeline, from raw data extraction and transformation to interactive dashboard visualization, using T20 Cricket World Cup statistics. The goal is to provide comprehensive insights into player and team performance.

## Technologies Used
* **Data Preprocessing & ETL:** Python (Pandas)
* **Data Modeling & Analysis:** Power BI, DAX
* **Visualization:** Power BI
* **Version Control:** Git/GitHub

## Data Sources
The data for this project was sourced from various cricket statistics platforms (or specify if it's a publicly available dataset you found). The following CSV files are included:
* `dim_batting_summary.csv`: Detailed batting performance data.
* `dim_bowling_summary.csv`: Detailed bowling performance data.
* `dim_match_summary.csv`: Summary of matches, including winners and venues.
* `dim_players.csv`: Player information (name, team, batting style, bowling style, playing role, description).
* `DAX Measures and Calculated columns.xlsx - metrics_list.csv`: List of DAX measures and their formulas.
* `DAX Measures and Calculated columns.xlsx - Sheet1.csv`: Additional parameters for analysis.

## Project Steps
1.  **Data Collection:** Initial raw data was gathered related to T20 Cricket World Cup matches, batting, bowling, and player profiles.
2.  **Data Preprocessing (Python - `T20_Data.ipynb`):**
    * The raw data was cleaned, transformed, and structured into suitable dimensions and fact tables using Python's Pandas library.
    * Handled missing values, corrected data types, and performed necessary aggregations to prepare data for analysis.
    * Generated the clean CSV files used for Power BI.
3.  **Data Modeling (Power BI):**
    * Imported the processed CSV files into Power BI Desktop.
    * Established relationships between tables (e.g., `fact_batting_summary` with `dim_players` and `dim_match_summary`).
    * Created calculated columns and a wide range of custom DAX measures to compute key cricket metrics such as:
        * `Total Runs`
        * `Batting Average`
        * `Strike Rate`
        * `Total Innings Batted/Dismissed`
        * `Bowling Economy`
        * `Bowling Strike Rate`
        * `Dot Ball %`
        * `Boundary Runs` & `Boundary %`
        * And many more (refer to `DAX Measures and Calculated columns.xlsx - metrics_list.csv` for a full list).
4.  **Interactive Dashboard Creation (`T20_cric.pbix`):**
    * Designed and developed an interactive Power BI dashboard to visualize the data.
    * Incorporated various visualizations (bar charts, line charts, cards, tables) to present insights effectively.
    * Implemented filters and slicers to allow users to drill down into specific players, teams, matches, or performance parameters.
    * The dashboard includes sections for overall performance, batting statistics, and bowling statistics.

## Key Insights / Features
* Detailed player profiles and their performance metrics.
* Comparison of batting and bowling statistics across players and teams.
* Analysis of boundary scoring and dot ball percentages.
* Match-wise performance tracking.
* Dynamic filtering for in-depth analysis.

## How to Use
1.  Clone the repository: `git clone []`
2.  Open `T20_Data.ipynb` in a Jupyter environment to understand the data preprocessing steps.
3.  Open `T20_cric.pbix` in Power BI Desktop to explore the data model and interactive dashboard.
4.  Refer to `DAX Measures and Calculated columns.xlsx - metrics_list.csv` for a comprehensive list of all calculated measures and columns used.

## Contact
Maan Vaishnani - http://www.linkedin.com/in/maan-vaishnani
maanvaishnani2004@gmail.oom
