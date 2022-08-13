# Movies-ETL
## Overview 
Amazing Prime is putting on a hackathon to find the next great movies, in order to do this, the coders in the competition will need a clean set of data to comb through. This cleaned data has had superfluous columns removed, columns with little to know data removed, and combined columns that have the same kind of information, and standardized the information within the columns where possible.
## Resources
- Data Sources: From Kaggle.com (movies_metadata.csv, ratings.csv); wikipedia-movies.json
- Software: Python 3.6.1, Jupyter notebook, VSCode, PostgreSQL, pgAdmin4

## Results
In sum we created a data frame that includes both the wikipedia and the kaggle data, the coders could access just the wikipedia data or the merged data frame of both kaggle and wikipedia data, the latter has more complete data with fewer missing values; both contain reformatted data to be uniform across the column. The other portion of this was processing the ratings data and creating and SQL database that the coders can access; this database contains approxiately 6,000 movies, and about 26 million ratings for those movies. There was a small amount of work done on the ratings but they were left uncombined so that individual statistical analysis could be completed.

## Summary 
The data was made to be usable so the Hackathon should go off without a hitch. The code was refactored so it can be used and changed as needed. 
