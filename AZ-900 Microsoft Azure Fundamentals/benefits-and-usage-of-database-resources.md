managed database (PAAS service)
microsoft, thirth party opensource

SQL Server
- Relational DB
- Fixed Schema
    - Rows
    - Records
- each row has a key to setup relationshipes

Azure SQL DB
- managament offering PAAS
Azure SQL MI (managed instance)
- SQL server in your vnet
- Compatibility

Open Source DB
- MySQL
- PostgreSQL
 - CITUS (hyperscale)
    Multiserver
    Shadig data

Cosmos DB
- multi models
    - Documents - API: SQL, MangoDB
    - Collums - Casandra
    - Tables (key value)
    - Graph relationships
- multi consistenct options
- noSQL of schemaless

When you need a azure sql db use Azure SQL DB
when you need a sql db intergrated in you vnet or need certain compatiblity features, use Azure SQL Managed Instances
When you need MySQL or Postgress use Mangaged Database
When tou need highperformance for Postgress use hyperscaling
