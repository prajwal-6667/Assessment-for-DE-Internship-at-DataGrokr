# Datagrokr Assignment

## Data Analysis and API Development Assessment

This repository contains the code and documentation for a comprehensive data analysis and API development assessment. The assessment is divided into three main sections, each contributing to a holistic understanding of data analysis and API creation.

### Section 1: Environment Setup and Data Cleaning

In this initial section, we meticulously set up the development environment using Google Colab. We start by importing and reading a dataset from a CSV file. The data cleaning operations that follow are designed to ensure data integrity and accuracy. Cleaning steps include:

- Removing redundant columns.
- Discarding rows with null values in specific fields.
- Separating the data into two distinct tables: Property_Details and Property_Price_Details.

The cleaned data is then seamlessly integrated into a local SQL database using SQLAlchemy and SQLite for future analysis.

#### Deliverables:

- Jupyter Notebook with comprehensive data cleaning commands and cleaned dataframes.
- Code snippets for establishing a connection to the local SQL database.

### Section 2: Data Analysis

This pivotal section involves querying the cleaned local database to extract valuable insights and answers to a series of data-related questions. The data analysis tasks span a wide spectrum of inquiries, including but not limited to:

- Identifying high-priced properties.
- Categorizing properties by their surface area.
- Finding properties with identical numbers of bedrooms and bathrooms.
- Calculating the average price per square meter.

These tasks, along with others, are tackled using SQL queries to extract meaningful information from the dataset.

#### Deliverables:

- A well-documented Jupyter Notebook featuring SQL queries for each data analysis task.

### Section 3: Expose the Results in API

In the final section, we shift our focus to API development. A Flask server is skillfully set up to create a REST API that responds to GET requests. Each data analysis task from Section 2 is translated into a corresponding API endpoint. The API provides a simple and efficient means of retrieving the results of the analysis queries. Additionally, basic error handling mechanisms are in place to gracefully manage invalid requests.

#### Deliverables:

- A Flask server implemented within a Jupyter Notebook.
- API endpoints meticulously mapped to each data analysis question.
- Robust error handling to cater to a variety of requests.

### Bonus:

As a bonus feature, the repository offers the possibility of deploying the Flask API using ngrok. This deployment option allows you to create a publicly accessible URL for testing and sharing the API with collaborators and stakeholders. Please note that an alternative deployment method using WSGI is also provided.

#### Bonus Deliverables:

- WSGI Flask API for serving API requests.
- Ngrok setup for the Flask API deployment.

### Dataset

The dataset employed for this assessment can be downloaded using the following link: [Dataset Link](#). To utilize the dataset within the assessment, kindly download it and place it in the same directory as the Jupyter Notebook files.

### Usage

To navigate through the assessment, follow these sequential steps:

1. Commence with Section 1 to initiate the data cleaning process and establish the local database.
2. Proceed to Section 2 to conduct in-depth data analysis and execute SQL queries.
3. Advance to Section 3 to set up and run the Flask API, thereby exposing the results of the analysis.

Ensure meticulous adherence to the instructions outlined in each section, and utilize the provided dataset for a comprehensive and insightful assessment.

Feel free to explore the code and accompanying documentation in this repository to gain a detailed understanding of the assessment process and its outcomes.

**Note**: This assessment has been successfully completed in strict accordance with the provided instructions and requirements.
