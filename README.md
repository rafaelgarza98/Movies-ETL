# Movies-ETL
SQL, Python and APIs project

# MoviesETL
The purpose of this project was an introduction ot the EXTRACT, TRANSFORM, and LOAD. We used movie data from Wikipedia, Kaggle, and aggregated ratings to assemble a movie database to create a clean dataset for a fictional hackathon.

To do this, I followed follow the ETL process: extract the Wikipedia and Kaggle data from their respective files, transform the datasets by cleaning them up and joining them together, and load the cleaned dataset into a SQL database.

## The process involved:
JSON data extraction
The clean up process involved dropping data that was beyond repair or not useful here

## Badly damaged data was fixed by:

Filling in missing data by
  -substituting data from another source,
  -interpolating between existing data points, or
  -extrapolating from existing data

Standardizing units of measure (e.g., monetary values stored in multiple currencies)

Consolidating data from multiple columns

### fixing data in the wrong form

  Reshape the data
  Convert data types
  Parse text data to the correct format
  Split columns
 
 Finally data frames were merged and uploaded in Postgres and viewed using pgAdmin to make sure everything loaded properly
