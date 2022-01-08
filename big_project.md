

# The big project

We will focus on one full-semester project that starts the first week of class. You will find a `project_XXXX` repo in the pinned repository section that provides more details.

- **When:** Starts week 1.
- **Duration:** This project will flow throughout the entire semester.
- **How:** We will work in 3-5 member teams, but we will work together as a class.  

Finally, your team will present to the entire class at each step. As a complete 'company,' we will then agree on a standard path for all groups to move to the next step.

## Step 1: Connecting and exploring the Data

> - __large team__, _3-days_

We need to explore our data and prepare a proposal for our work.

- What variables are available to us?
- Are there concerns about the data structure?
- How reliable are the primary features?

__Deliverable: Your work proposal based on the big project requirements__


## Step 2: Processing data into our Spark environment

> - __large team__, _4-days_

We need to leverage the data source's tools to parse the data and ingest it into Spark tables for further project development.  

- Can you leverage the API to pull data?
- Can you parse the API data into the proper format for ingestion?
- How will you handle any complexities with the data?

__Deliverable: Your parsed data in Databricks, final scripts for parsing, and data documentation.__

## Step 3: Secondary data sources

> - __large team__, _6-days_

What other data sources can we leverage to add to the primary data source? What wrangling will be done on each source to leverage them in our final model?

__Deliverable: Your additional data sources parsed and wrangled into Databricks, your final scripts, and data documentation.__

## Step 4: Feature Creation

> - __large team__, _10-days_

We now have our data sources in a format to work towards our predictive model. We will most likely iterate between Step 5 and this step as we progress.  

Your goal is to build features that you think would be valuable in predicting your target variable. Each member of your team is responsible for developing 1-2 features.  

__Deliverables: A table of your final model data, your final scripts, a report with visualizations displaying each feature's relationship to the target variable.__

## Step 5: Modeling and Predictions

> - __5-team__, _6-days_

The moment of truth is here. We will use [MLlib](https://docs.databricks.com/applications/machine-learning/train-model/mllib/index.html) on Databricks.

__Deliverables: A validated model with model performance summarized.__

## Step 6:  Application development

> - __5-team__, _6-days_

Let's get our model out of Databricks and into a Docker container to publish our app in the cloud. We should also have a way to handle updated data from the API.

__Deliverables: A prototype app.__