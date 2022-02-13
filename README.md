# Movies-ETL

## Project Overview

The intent of this project was to create a Extract-Transform-Load automated pipeline for movie data gathered from Kaggle and Wikipedia. The wikipedia data was provided in json format and consists of general movie information. The two kaggle datasets were provided in csv format and consist of general movie information and rating information from the MovieLens dataset. The deliverables of this project merge the datasets into one transformed data frame using Python in Jupyter Notebook. During this process, null columns were removed, datatypes were adjusted, similar columns were resolved, and the data was cleaned to produce a workable file. The dataframe was subsequently loaded into a postgreSQL database for future analysis.
