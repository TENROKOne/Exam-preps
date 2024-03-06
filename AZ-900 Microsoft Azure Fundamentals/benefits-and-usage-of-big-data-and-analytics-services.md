# Benefits and Usage of Big Data and Analytics Services

## Extract transform load (ETL)
- Data lake can handle a lot of unstructured data
- RAW format is send to datalake (on blob) and kept here in the original format
- Data is transformed when it is taken out of the datalake

## Transfer
- Cleanup the data
- Deduplicate the data
- Wrangle the data into a new format
- load it to another service, like sql db

## orchestration
- Azure Data Factory is managing the above flow 
- Manage the end-to-end flow of the data

## Key Services
- HDInsight
    - Opensource analitic service, ao:(Hadoop, STORM, SPARK, Kafka, HIVE LLAP, HBase)
- Databricks (build on apache spark) managed databricks solution in Azure
- Azure Synapps Analitics
    - uses a workspace
    - complete analitic solution
    - uses other components and uses it in the workspace