
# The small projects

As we get into this course's tools, we will have 3-8 'small projects' done with a 2-3 person group where each of you must commit to working equally on the task.  

- **When:** Aligned with different tools during the semester.
- **Duration:** Each project will last 3-7 days.
- **How:** In groups of 2-3, the work will be presented to another team.

## At some point, we need to Docker

Docker is used everywhere the cloud is used.  Both data scientists and computer scientists leverage Docker in their workflows.  We will gain familiarity with the docker process but primarily use Docker as a pre-developed tool to access tools like Jupyter Notebooks, Spark, Python, and R without needing to configure our computers.

### Docker 101

- __Partner__, _3-days_

Complete the [Docker 101 Tutorial](https://www.docker.com/101-tutorial) and put together a one-slide overview of what Docker is and how it is used.

### Docker Deep Dive

- __Partner__, _3-days_

Find your passion with Docker as it relates to data science.  Look into building your own images, finding new packages or tools to add to an image, or teach new tricks.

### Figuring out Docker for Data Science

- __Team__, _5-days_

We will use the [all-spark-notebook](https://hub.docker.com/r/jupyter/all-spark-notebook) to create our data science container where we will examine the [IRS 990 Master Files](https://drive.google.com/drive/folders/1uqm_nH0D6U8Beqyr7jLrPO1Scl5tJbKs?usp=sharing). You can download the files from the links in the [readme](https://docs.google.com/document/d/1ph6YioRu3aeXBM4IEIOS7kbUuwJyhz0yxCOIyxatffU/edit?usp=sharing) or use your BYUI login to Google drive to see the files in Google Drive.

The IRS provides a few Master Files that list all [Exempt Organizations](https://www.irs.gov/charities-non-profits/exempt-organizations-business-master-file-extract-eo-bmf) with over 2 million organizations listed. 

Complete an exploratory analysis that provides a summary and story of the data provided.  This report should include at least ten charts, three tables, and multiple paragraphs.

1. Python and pandas
2. R and dplyr


## Finding that Spark

Apache Spark is an open-source, distributed processing system used for big data workloads. It utilizes in-memory caching and optimized query execution for fast queries against data of any size. Simply put, Spark is a fast and general engine for large-scale data processing.

The fast part means that it’s faster than previous approaches to work with Big Data like classical MapReduce. The secret for being faster is that Spark runs on memory (RAM), making the processing much faster than on disk drives.

The general part means that it can be used for multiple things like running distributed SQL, creating data pipelines, ingesting data into a database, running Machine Learning algorithms, working with graphs or data streams, and much more. [ref](https://chartio.com/learn/data-analytics/what-is-spark/)

### Spark and SQL

- __3-Team__, _5-days_

Repeat the __Figuring out Docker for Data Science__ project using;

1. pyspark and sparksql
2. sparklyr or sparkr 

### Machine Learning with Spark (MLib)

- __3-Team__, _5-days_

We will work through two examples to make sure we understand how Machine Learning works in Spark.

- [City Population and Median Sale Price](https://databricks.com/spark/getting-started-with-apache-spark/machine-learning)
- [Predicting Survival on the Titanic](https://github.com/BYUI451/spark_ml)

## Brick by Databricks

We are going to use Azure Databricks to experience Spark in the cloud.
