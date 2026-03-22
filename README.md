# Big Data Wrangling with Google Books Ngrams
This project leveraged a cloud-based distributed computing environment (Apache Hadoop, Apache Spark, Amazon S3) to load, filter, and visualize a large real-world dataset.

## Project Overview
Briefly describe:
- Project goal was to leverage big data resources to filter and present the count of historical texts from the 1800s to the 2000s that have been digitized by Google Books.
- Library historians, archivists, and those interested in the potential of big data proecessing technology would be interested in the results of the exercise.
- The data processing, visualization, and analysis was presented in a pdf report.

## Business / Research Problem
- An exercise like this demonstrates the potential of Big Data processing.

## Datasets
- eng_1M_1gram.csv file, found on a public S3 bucket at: s3://brainstation-dsft/eng_1M_1gram.csv
- Rows: 261,823,225 / Columns: 5, string data types
- Data was conveniently houses as a CSV file on a public BrainStation S3 bucket


## Results & Insights
- The count of texts that were digitized (or available for digitization) increased exponentially from the 1800s to the 2000s.

## Visualizations
- An interactive visual that the user could zoom or pan to see the frequency count across all years.

## Tools & Technologies
- Python packages: numpy, pandas 1.0.5, matplotlib 3.7.5, %matplotlib notebook, pyspark.sql.functions

## Methodology
- See the report added to the repository.
