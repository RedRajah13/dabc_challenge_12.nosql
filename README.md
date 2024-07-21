# dabc_challenge_12.nosql
Module 12 - NoSQL homework

In this challenge, I was given data from the UK Food Standards Agency with hygiene rating data from different eating establishments and tasked with analyzing it for a food magazine. I used Mongo and Python to work with this NoSQL data set.

In the NoSQL_setup_starter notebook, I imported the given database using PyMongo and updated the database by adding information for a new restaurant and dropping data from a town the magazine was not interested in. Data types and null values were also manipulated for future handling.

In the No SQL_analysis_starter notebook, I connected to my updated database and explored several queries given by the magazine, creating dataframes for each for analysis by the magazine. Query 1 finds 41 establishments with hygiene scores of exactly 20, which readers of the magazine might want to avoid. Query 2 finds 33 establishments in London with ratings of at least 4 out of 5, which should be desirable for readers. Query 3 finds the top 5 establishments with ratings of 5, sorted by lowest hygiene score, nearest in location to the new restaurant I added to the database. These restaurants will be desirable by readers in the area listed. Query 4 lists the 55 establishments that have hygiene scores of 0, which are the cleanest restaurants judged by the UK Food Standards Agency.