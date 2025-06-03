This script demonstrates how to use the Pandas library in Python to load, inspect, and explore data from various file formats, including CSV, JSON, and Excel. It serves as a basic example of data handling and exploratory data analysis.

Loading Data from Different Formats
The script reads data from:

A CSV file containing country-level data.

A JSON file with structured data.

An Excel workbook with world population statistics.

Exploring the Data
After loading the data into Pandas DataFrames, it performs a basic exploration that includes:

Checking the structure and data types (info()).

Viewing the number of rows and columns (shape).

Displaying the first and last 10 rows of the dataset (head() and tail()).

Accessing a specific column (Rank) to understand its contents.

Data Display Settings
The script modifies default display settings in Pandas to show more rows and columns for better visibility during analysis.

Column Name Verification and Indexing Advice
It includes detailed comments guiding how to:

Check for correct column names.

Set a specific column (e.g., a country name) as the index.

Handle issues like extra spaces in column names.

Access specific country data (e.g., "Uzbekistan") once the index is correctly set.

Accessing Specific Data
Finally, the script retrieves a specific row from the DataFrame using its position (the 225th row) for inspection.

