# Airflow
Apache Airflow is a tool that can create, organize, and monitor workflows. It is open-source hence it is free and has a wide range of support as well. It is one of the most trusted platforms that is used for orchestrating workflows and is widely used and recommended by top data engineers. This tool provides many features like a proper visualization of the data pipelines and workflows, the status of the workflows, the data logs, and codes as well in quite a detail. The process to Install Airflow is a difficult one but it provides the following benefits.
# Airflow 2.0 Installation
This page describes Airflow 2.0 installations using AWS EC2(uduntu) server. 

The process to Install airflow is 4 steps. 

Step 1: Airflow Python Module Installation   
Step 2: Create Airflow Account   
Step 3: Install Postgre for Database on Airflow  
Step 4: Initialize Airflow Environment  
Step 5: Start Webserver and Scheduler
## Step 1: Airflow Python Module Installation

First, update ***apt-get*** and install ***python 3.0 ver***

```
sudo apt-get update
sudo apt-get install -y python3-pip
```

The apache-airflow PyPI basic package only installs what’s needed to get started. Subpackages can be installed depending on what will be useful in your environment.

```
sudo apt-get install -y postgresql-server-dev-all
sudo apt-get install -y libmysqlclient-dev
sudo pip3 install numpy
sudo pip3 install pandas
sudo pip3 install apache-airflow==2.2.5
sudo pip3 install apache-airflow-providers-postgres==2.2.0
sudo pip3 install apache-airflow-providers-mysql==2.2.0
sudo pip3 install apache-airflow-providers-amazon==2.3.0
sudo pip3 install apache.airflow.providers.slack
sudo pip3 install apache.airflow.providers.google
sudo pip3 install SQLAlchemy==1.3.23
sudo pip3 install oauth2client
sudo pip3 install gspread
sudo pip3 install typing_extensions
```

## Create Airflow Account

## Install Postgre Database on Airflow

## Initialize Airflow Environment

## Start Webserver and Scheduler
