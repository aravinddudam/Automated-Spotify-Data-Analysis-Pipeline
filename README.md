## Automated Spotify Data Analysis Pipeline with Python, AWS, and Snowflake

## Overview
Effortlessly connected with the Spotify API to harvest and scrutinize music data, utilizing Python, Amazon Web Services (AWS), and Snowflake to establish a thorough data pipeline for processing, refining, and depicting the extensive music data from Spotify. The chief aim was to derive meaningful insights from Spotify's vast music collection and to develop a full-scale data pipeline for automating the workflow.

## Project Architecture

1. Data Extraction: Utilized Python and the Spotipy library to collect music information from Spotify, which was then stored on AWS S3.
2. Automated Data Transformation: I implemented AWS Lambda functions for the seamless transformation of JSON data into structured formats, covering songs, albums, and artists.
3. AWS Lambda Functions: These functions facilitated the automation of the data processing pipeline, activating upon the arrival of new data.
4. Amazon S3 & Snowflake Integration: After transformation, the data was kept in AWS S3 before being efficiently transferred into Snowflake, where it was organized into tables ready for analytics.


## Technology Stack
1. Python
2. AWS Lambda
3. AWS S3
4. Apache Spark
5. Snowflake
