## Hands-On-Lab: Data Scientist

Analyze sales data in dashDB from IBM Data Science Experience using Spark based IPython Notebooks

### Introduction

IBM Data Science Experience is an interactive, collaborative, cloud-based environment where data scientists can use multiple tools to drive analytics and derive insights. Data Scientists can use Python, R, or Scala in Jupyter Notebooks already connected to Spark or RStudio for open source R computing environment.

---

This lab exercise uses an IPython Notebook in Data Science Experience to connect with dashDB, explores sales, product data and analyze sales performance for a specific product line. Pixiedust, a Python based visualization package is used to visualize the results.

![overview](/overview.gif)


---

 Steps for the Lab

---

### Provision dashDB

1.	Login to IBM Bluemix

  a.	For existing accounts use  https://new-console.ng.bluemix.net/login

  b.	Sign-up for a free trial account at https://console.ng.bluemix.net/registration/

2.	Provision dashDB

  a.	From the Bluemix catalog menu search for “dashdb”

  b.	Click on the dashDB Icon

  c.	Accept the default values and rename “Service name:” to ‘DS_Sales_DataStore’

  d.	Select “Entry Pricing Plan” (default) and click “Create” on the right hand panel.

The dashDB service is provisioned along with sample database and lab exercise will use the sample database.

---
### Provision Spark Service in Data Science Experience

1.	Login to IBM Data Science Experience @ http://datascience.ibm.com/

2.	Create a new Notebook

  a.	Click on ‘Start a Notebook” 

    ![overview](/overview.gif)

---
### Create Notebook in Data Science Experience


---
