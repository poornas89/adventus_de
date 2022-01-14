# Data Engineer / BigQuery & Python Challenge

## Idea of the task 

This task will involve creating a table in BigQuery and loading data into it via Python. 

## Technologies to use

* BigQuery (Free trial GCP account)
* Python

## Acceptance criteria

3 files are provided:

1. customers_1.json
2. customers_2.json
3. customers_3.json

Each file contains a few records of customer data (in newline delimited json format). Start by creating a project in BigQuery - you'll be able to complete this exercise using a free trial GCP account. Then create a Python script that accomplishes the following three tasks:

1. Use customers_1.json to create a table in Python and load the data into it.
2. Load customers_2.json into the table using a load job.
    * Note: The file customers_2.json has additional fields, and you'll need to update the schema of your table. Try to do this without manually specifying the names of the new fields.
3. Load the file customers_3.json into the table using a streaming insert.
    * Note: As before, the file customers_3.json includes another schema change.

## Things to keep in mind 🚨

* Your code will be evaluated based on: code structure, programming best practices, legibility (and not number of features implemented or speed). 
* The git commit history (and git commit messages) will also be evaluated.
* Please include an overview of your solution and the reasons for your decisions (patterns, libraries etc.) in the README.
* Please include instructions on how to run the project locally in the README.

## How to submit the challenge solution? 

Once you have finished your app and pushed it to your GitHub account, please follow the instructions below:

1. Set the Repo privacy to public. If you have any conserns with this let us know.
2. Add the repo link to Coderbyte.
