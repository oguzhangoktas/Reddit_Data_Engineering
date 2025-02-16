# Reddit Data Processing Using Airflow, Celery, Postgres, S3, AWS Glue, Athena, and Redshift

This initiative offers an all-encompassing approach to constructing a data processing pipeline aimed at fetching, modifying, and loading Reddit content into a Redshift database. The system combines various technologies such as Apache Airflow, Celery, PostgreSQL, Amazon S3, AWS Glue, Amazon Athena, and Amazon Redshift.


## Summary

The core objectives of this pipeline include:

Retrieving Reddit content via its API.
Deposit the initial data into an S3 container through Airflow.
Modify the data utilizing AWS Glue along with Amazon Athena.
Import the restructured data into Amazon Redshift to facilitate analytical processes and queries.


## Structure
![RedditDataEngineering.png](assets%2FRedditDataEngineering.png)
Reddit API: The primary data source.
Apache Airflow & Celery: Coordinates the ETL workflow and oversees task allocation.
PostgreSQL: Serving as a temporary repository and overseeing metadata operations.
Amazon S3: Repository for the original data.
AWS Glue: Facilitates data organization and manages ETL tasks.
Amazon Athena: Enables data transformation through SQL operations.
Amazon Redshift: Acts as the primary data warehouse for storage and analytics.

## Requirements
An active AWS Account with the necessary privileges for S3, Glue, Athena, and Redshift.
Valid credentials for Reddit API access.
Docker software installed.
Python version 3.9 or newer.

In this project, CodeWithYu YouTube channel and Yusuf Ganiyu airscholar github profile were used as sources.