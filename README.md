# group-project-2

# Movie Data Cleaning and Database Import Project

Welcome to our Movie Data Cleaning and Database Import Project! In this project, we have meticulously cleaned and prepared the "tmdb_5000_movies.csv" dataset, ensuring it is ready for further analysis. Additionally, we loaded the cleaned data into an SQLite database for easier access and querying. We used the Python programming language, Pandas library for data cleaning, and SQLite for data storage.

## Table of Contents

- [Getting Started](#getting-started)
- [Data Cleaning](#data-cleaning)
- [Loading Data into an SQLite Database](#loading-data-into-an-sqlite-database)
- [Exporting Cleaned Data](#exporting-cleaned-data)
- [Contributors](#contributors)
- [Citations](#citations)

## Getting Started

To get started with this project, you will need Python, the Pandas library, and an SQLite database management tool like DB Browser for SQLite installed. You can install Pandas using pip:

## bash
pip install pandas

## Data Cleaning
In this project, our main focus was on data cleaning tasks. We carefully cleaned and prepared the dataset by:

- Extracting relevant information from JSON columns.
- Reordering and renaming columns for better readability.
- Handling missing or inconsistent data.
- Converting data types to their appropriate formats.
- Making sure the dataset is ready for future analysis.
- Loading Data into an SQLite Database
- After completing the data cleaning process, we loaded the cleaned dataset into an SQLite database. This step allows for more efficient data retrieval and querying for future analysis. You can access the database using an SQLite - database management tool of your choice.

## Exporting Cleaned Data
In addition to the database, we retained a cleaned CSV version of the dataset named "movies_data.csv" in UTF-8 encoding without an index for your convenience.

## Contributors
- [Adalbert Payan](https://github.com/AdalbertPayan)
- [Fpolus](https://github.com/Fpolus)
- [vasquezr8](https://github.com/vasquezr8)


-------------------------------------------------------------------------------------------------------------------------------

## Citations
We would like to acknowledge the valuable assistance we received from the Stack Overflow community. In particular, we found the following Stack Overflow thread extremely helpful in learning how to iterate through rows in a Pandas DataFrame:

Stack Overflow Thread: How to Iterate Over Rows in a DataFrame in Pandas

We also acknowledge the article titled "Measurement Problems: Sorting Products" by [Author Name] on [Source URL] for providing insights into the calculation of a weighted rating based on vote_count and vote_average.

Source: Measurement Problems: Sorting Products

Additionally, we learned how to pop multiple columns from a Pandas DataFrame and place them elsewhere from the following Stack Overflow thread:

Stack Overflow Thread: How do you pop multiple columns off a Pandas DataFrame into a new DataFrame?

We extend our gratitude to the contributors and the Stack Overflow community for sharing their expertise and knowledge, which greatly facilitated our data manipulation tasks in this project.

