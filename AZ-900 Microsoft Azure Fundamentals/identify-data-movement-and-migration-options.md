Microsoft Azure Storage Explorer
- Move conect to azure BLOB and Fileshares
- Also Queues and Tables
- Updload / Download content

Storage browser does the same, but is available in the Azure Portal

Azure File Sync
- Syncgroup
- Server endpoint (upto 100)
- Cloud endpoint (1)
- Cloud tiering (days not used or server storage)

AzCopy
- automation
- Copy / Sync data
- Cloud to Cloud
    - works on server side (direct between services in Azure)
- Also between other clouds

Azure Migrate
- VM / OS
- DB
- can migrate esx servers to azure

# Offline options
'' Azure Data Box ''
- DISK: Disk are shipped to u, you send them back with data and it will be imported in your storage account
- BOX (80TB): Import / Export options. Its a box that you plugin to your network and kopie the data by smb and you send it back and it will be copied in your storage accounts
-  Box Heavy (770TB) 


Offline use Databox
SMB doe cloud sync
for small files storage explorer
for automation use AzCopy
for vms and os use 
