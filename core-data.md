# Describe core data concepts (15–20%) 
##  Describe types of core data workloads 
* ###  describe batch data 
  




* ###  describe streaming data 
* ### describe the difference between batch and streaming data 
* ### describe the characteristics of relational data 
  
    Relational data is commonly known as structured data. 
    Data is stored in table represented in entities. 
    Each instance of an entity is assigned a primary key, keys are used to reference other entities.

## Describe data analytics core concepts 
### describe data visualization (e.g., visualization, reporting, business intelligence (BI)) 
### describe basic chart types such as bar charts and pie charts 
### describe analytics techniques (e.g., descriptive, diagnostic, predictive, prescriptive, cognitive)
*  
### describe ELT and ETL processing 
ETL (Extract, Transform, Load)
### describe the concepts of data processing
* Is read-only or read-mostly systems that store vast volumes of historial data or business metrics. 
* Can be based on snapshot of the data at a given point in time or a series of snapshots. 

Online Transactional Processing (OLTP) 

Data Lakes: Are common in modern data analytical processing scenarios where a large volume of file-based data must be collected and analyzed.

Data Warehouses: Way to store data in a relational schema that is optimized for read operations, like querues for reporting and data visualization. 
May require some denormalization of data in an OLTP data source.

OLAP Online analytical processing: Aggregated type of data storage optimized for analytical worloads. 

## Describe how to work with relational data on Azure (25–30%) 
### Describe relational data workloads  
* ### identify the right data offering for a relational workload 
* ### describe relational data structures (e.g., tables, index, views) 
### Describe relational Azure data services 
* describe and compare PaaS, IaaS, and SaaS solutions 
* ### describe Azure SQL family of products including Azure SQL Database, Azure SQL Managed Instance, and SQL Server on Azure Virtual Machines . 

  * Azure SQL Database: Fully managed PaaS database hosted in Azure
  * Azure SQL Managed Instance: A hosted instance of SQL server with automated maintenance, allows flexible config than Azure SQL DB but with more administrative responsibility. 
  * Azure SQL VM: A VM with an installation of SQL Server allowing max conifgurability with full management responsability. 

* describe Azure Synapse Analytics. 
    * Comprehensive, unified data analytics solution that provides a single service interface for multiple analytical capabilities: 
      * Pipelines: Based on the same technology as Azure Data Factory. 
      * SQL - A highly scalable SQL database engine, optimized for data warehouse workloads. 
      * Apache Spark - Open Source distributed data processing system that supports multiple programming languages and APIs, including Java, Scala, Phyton, and SQL.  
      * Azure Synapse Data Explorer - a high performance data anlytics solution that is optimized for real time querying of log and telemety data using KQL. 
* describe Azure Database for PostgreSQL, Azure Database for MariaDB, and Azure 
Database for MySQL 


### Identify basic management tasks for relational data 
* describe provisioning and deployment of relational data services 
* describe method for deployment including the Azure portal, Azure Resource Manager 
templates, Azure PowerShell, and the Azure command-line interface (CLI) 
* identify data security components (e.g., firewall, authentication) 
* identify basic connectivity issues (e.g., accessing from on-premises, access from Azure VNets, access from Internet, authentication, firewalls)  
* identify query tools (e.g., Azure Data Studio, SQL Server Management Studio, sqlcmd 
utility, etc.) 

### Describe query techniques for data using SQL language  
* compare Data Definition Language (DDL) versus Data Manipulation Language (DML) 
* query relational data in Azure SQL Database, Azure Database for PostgreSQL, and Azure 
Database for MySQL 

### Identify basic management tasks for relational data 
* describe provisioning and deployment of relational data services 
* describe method for deployment including the Azure portal, Azure Resource Manager 
templates, Azure PowerShell, and the Azure command-line interface (CLI) 
* identify data security components (e.g., firewall, authentication) 
* identify basic connectivity issues (e.g., accessing from on-premises, access from Azure 
VNets, access from Internet, authentication, firewalls)  
* identify query tools (e.g., Azure Data Studio, SQL Server Management Studio, sqlcmd 
utility, etc.) 

### Describe query techniques for data using SQL language  
* compare Data Definition Language (DDL) versus Data Manipulation Language (DML) 
* query relational data in Azure SQL Database, Azure Database for PostgreSQL, and Azure 
Database for MySQL 

## Describe how to work with non-relational data on Azure (25–30%) 
### Describe non-relational data workloads 
* describe the characteristics of non-relational data 
* describe the types of non-relational data 
* recommend the correct data store 
* determine when to use non-relational data 

### Describe non-relational data offerings on Azure 
* identify Azure data services for non-relational workloads 
* describe Azure Cosmos DB APIs
    * Is a global-scale non-relational database that supports multiple application programming interfaces (APIs) storing and manage data as JSON documents, key-value pairs, column-families and graphs.  
  
* describe Azure Table storage 
  * Key-value storage for applications that need to read and write data values quickly. 
* describe Azure Blob storage 
  * Scalable, cost-effective storage for **binary files**. 
* describe Azure File storage 
  * Network files shares such as you typically find in corporate networks. 
  
### Identify basic management tasks for non-relational data  
* describe provisioning and deployment of non-relational data services 
* describe method for deployment including the Azure portal, Azure Resource Manager 
templates, Azure PowerShell, and the Azure command-line interface (CLI) 
* identify data security components (e.g., firewall, authentication, encryption) 
* identify basic connectivity issues (e.g., accessing from on-premises, access from Azure 
VNets, access from Internet, authentication, firewalls)  
* identify management tools for non-relational data 


## Describe an analytics workload on Azure (25–30%) 
### Describe analytics workloads 
* describe transactional workloads 
* describe the difference between a transactional and an analytics workload 
* describe the difference between batch and real time 
* describe data warehousing workloads 
* determine when a data warehouse solution is needed 
### Describe the components of a modern data warehouse 
* describe Azure data services for modern data warehousing such as Azure Data Lake Storage Gen2, Azure Synapse Analytics, Azure Databricks, and Azure HDInsight.
   
  * Azure Databricks: Azure-integrated version of Databricks, combines Apache Spark data processing platform with SQL database semantics and an integrated management interface to enable large-scale data analytics. 
  
  * Azue HDInsight: Azure service that provides Azure-hosted cluster for popular Apache open-source big data processing technologies:
    * Apache Spark: Apache Spark - Open Source distributed data processing system that supports multiple programming languages and APIs, including Java, Scala, Phyton, and SQL.  
    * Apache Hadoop: Distributed system that uses MapReduce jobs to process large volumes of data efficiently across multiple cluster nodes. MapReduce jobs can be writen in Java or abstracted by interfaces such as Apache Hive 
    * Apache HBase:
    * Apache Kafka:
    * Apache Storm:   
* describe modern data warehousing architecture and workload 
### Describe data ingestion and processing on Azure  
* describe common practices for data loading 
* describe the components of Azure Data Factory (e.g., pipeline, activities, etc.) 
* describe data processing options (e.g., Azure HDInsight, Azure Databricks, Azure Synapse Analytics, Azure Data Factory)

  * Azure  HDInsight 
    Data engineers can use Azure HDInsight to support big data analytics workloads that depend on multiple open-source technologies.

  * Azure Synapse Analytics: Data engineers can use Azure Synapse Analytics to create a unified data analytics solution that combines data ingestion pipelines, data warehouse storage, and data lake storage through a single service. Data analysts can use SQL and Spark pools through interactive notebooks to explore and analyze data, and take advantage of integration with services such as Azure Machine Learning and Microsoft Power BI to create data models and extract insights from the data. 
  
  * Azure Data Factory: Azure Service that enables you to define and schedule data pipelines to transfer and transform data. Allows the integratin of pipelines with other Azure services, enabling the data ingestion from cloud stores, process the data using cloud-based compute, and persist the results in another data store. Is used by data engineers to build extract, transform and load (ETL) solution that populate analytical data stores with data from transactional systems across the organization. 
  
  * Azure Databricks: Data engineers can use existing Databricks and Spark skills to create analytical data stores in Azure Databricks. Data Analysts can use the native notebook support in Azure Databricks to query and visualize data in an easy to use web-based interface.  
### Describe data visualization in Microsoft Power BI  
* describe the role of paginated reporting 
* describe the role of interactive reports 
* describe the role of dashboards 
* describe the workflow in Power BI 