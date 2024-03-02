# Kaggle Dataset to Snowflake ETL Pipeline

This project demonstrates how to create an ETL (Extract, Transform, Load) pipeline using Databricks, Spark, and Snowflake. It downloads a dataset from Kaggle using the Kaggle API, processes it within a Databricks notebook, and loads the transformed data into a Snowflake database.

## Table of Contents
- [Introduction](#introduction)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

In this project, we utilize Databricks, an analytics platform built on Apache Spark, to ingest data from Kaggle using the Kaggle API. The dataset is then processed and transformed within a Databricks notebook using Spark DataFrame operations. Finally, the transformed data is loaded into a Snowflake database for further analysis.

## Setup

1. **Databricks Account**: Ensure you have access to a Databricks account. If not, sign up for a free account [here](https://databricks.com/try-databricks).

2. **Kaggle API Token**: Generate a Kaggle API token from your Kaggle account settings. Instructions can be found [here](https://www.kaggle.com/docs/api#authentication). Place the generated `kaggle.json` file in your Databricks File System (DBFS).

3. **Snowflake Account**: You need access to a Snowflake account. If you don't have one, sign up for a free trial [here](https://www.snowflake.com/free-trial/).


## Usage

1. Clone this repository to your Databricks workspace or upload the notebook (`etl_pipeline.ipynb`) directly to your workspace.

2. Open the notebook in your Databricks workspace and follow the instructions within to execute the ETL pipeline.


## Contributing

Contributions are welcome! Please feel free to open an issue or submit a pull request for any improvements or additional features.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

