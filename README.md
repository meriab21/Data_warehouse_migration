# Data_warehouse_migration
**Table of content**

- [Overview](#overview)
- [Install](#install)
- [Data](#data)
- [Tech-Stack](#tech-Stack)
- [Description](#description)

## Overview
![ELT](https://user-images.githubusercontent.com/45142893/180853321-b0b130ca-ed6c-4564-914f-76f88516a4ce.png)

The purpose of this week’s challenge is to build a data engineering data warehouse should take into account future needs, organise data such that a number of downstream projects query the data efficiently. You should use the Extract Load Transform (ELT) framework using DBT.

## Install

```
git clone https://github.com/meriab21/Data_warehouse_migration.git
cd Data-watehouse_migration
pip install -r requirements.txt
```
     docker-compose up airflow-init

     docker-compose up
    

## Data

Data can be found [here](https://open-traffic.epfl.ch/index.php/downloads/#1599047632450-ebe509c8-1330)

## Tech-Stack
Tech Stack used in this project

-   [Apache Airflow](https://airflow.apache.org/docs/apache-airflow/stable/)
-   [MySQL](https://www.mysql.com/)
-   [dbt](https://docs.getdbt.com/)
-   [Superset](https://superset.apache.org/)

## Description

Building a scalable data warehouse that will host the vehicle trajectory data extracted by analysing footage taken by swarm drones and static roadside cameras.
The data warehouse should take into account future needs, organise data such that a number of downstream projects query the data efficiently. You should use the Extract Load Transform (ELT) framework using DBT.

## Author

- 👤 **Meron Abate**
- meriab1234@gmail.com

## Show your support

Give a ⭐ if you like this project!
