# Azure-blob-storage-project
This project demonstrates how to use AzCopy to upload files to Azure Blob Storage

Project overview
- created standard blob storage account named portfolioblob1 with hot access tier,enabled blob soft delete, container soft delete & visioning.
- created container named portfolioblob
- On how to use :
 1. download and install azcopy
 2. Used azcopy CLI to transfer files from local storage to Azure Blob Storage
 3. run command below:
    - azcopy copy "C:\azcopy" "here use SAS URL as the destination"
- created block blob inside the container using azcopy command prompt.
- Learned how to troubleshoot common AzCopy errors
- Technologies used are :
  1. Microsoft Azure Portal
  2. azcopy CLI
- Screenshots of successful upload are included
