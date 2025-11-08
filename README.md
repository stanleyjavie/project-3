# IS 362 – Project 3: Chinook Database Analysis

## Project Overview
This project uses the Chinook database to analyze customers’ purchases. 
We retrieved customers' last and first names, the tracks they purchased, 
and the corresponding album titles using SQL queries joined across five tables.

## Steps Performed
1. Installed required Python libraries (`pandas` and `sqlalchemy`).
2. Connected to the Chinook SQLite database.
3. Wrote a SQL query joining `Customer`, `Invoice`, `InvoiceLine`, `Track`, and `Album` tables.
4. Loaded the results into a pandas DataFrame.
5. Displayed the first 5 rows in the notebook.
6. Exported the DataFrame to a CSV file (`customer_tracks.csv`).

## Files in this Repository
- `Chinook_Sqlite.sqlite` – the database file
- `project3.ipynb` – Jupyter notebook with code and comments
- `customer_tracks.csv` – exported DataFrame
- `README.md` – project description

## Conclusion
This project demonstrates how SQL and pandas can be combined 
to extract and analyze relational database information efficiently. 
We successfully retrieved customers’ purchased tracks and album titles, 
sorted the data, and exported it for further analysis.
