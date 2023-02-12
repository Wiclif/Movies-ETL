# Movies-ETL
Amazing Prime video was a platform for streaming movies and Tv shows on Amazing Prime. Amazing prime video team would like to develop an algorithm to predict which low budget movies being released will become popular so that they can buy the streaming rights at a bargain.
There are two data sources: a scrape of wikipedia for all movies released since 1990 and the rating data from the movie lands website.

## Objective
The task is to extract the data from the two sources, transform it into one clean dataset, and finally load that data set into SQL table

## Methodology
ETL is a flexible process for moving data. It can be as simple as a one-time migration from one database to another, or as complex as an ongoing automated collection of messy, real-time data from many different sources.

In the Extract phase, data is pulled from external or internal sources, possibly disparate. The sources could be flat files, scraped webpages in HTML or JavaScript Object Notation (JSON) format, SQL tables, or even streams of sensor data. The extracted data is held in a staging area in between the data sources and data targets.

After data is extracted, there are many transformations it may need to go through. The data may need to be filtered, parsed, translated, sorted, interpolated, pivoted, summarized, aggregated, merged, or more. The goal is to create a consistent structure in the data. Without a consistent structure in our data, it's almost impossible to perform any meaningful analysis.

Finally, after the data is transformed into a consistent structure, it's loaded into the data target. The data target can be a relational database like PostgreSQL, a non-relational database like MongoDB that stores individual documents, or a data warehouse like Amazon Redshift that optimizes performance specifically for analytics.
