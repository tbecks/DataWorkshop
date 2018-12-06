# DataWorkshop #

### Inital Setup ###

* Create a Storage Account in Azure
* Open Azure Storage Explorer and connect to the new Storage Account
* Add a connection to lab storage account by selecting Add Account on the left and "Use Storage Account Name and Key" option:
  * Account Name: beckerlabs
  * Account Key: AMhXmGQChw8WxrNt4G/v4d5yKtbWvB8ClweS6Qb8k9QAlMh7jxpT0ljX0nDt+s7mBNT4BXU2yelkMJ97bKLZcA== 
* Copy the following container from the lab account to your account: 
  * nycbike
* In your storage account create the following blank container:
  * nycbike-parquet
  * adf

### Lab Information ###

1. Hands on with Databricks using NYC CitiBike Data: https://github.com/tbecks/DataWorkshop/blob/master/citibike_nyc_analysis.html

2. Detailed Workshop: https://github.com/tbecks/DataWorkshop/blob/master/Workshop.zip

3. ADF - Immersion Database: 
* Server name: immersiondb.database.windows.net
* Database: AdventureWorksDW2014
* Username: immersionuser
* Password: pass@word1
* Table: dbo.DimCustomer

4. ADF - KittiRoad Data Web Files (HTTP Linked Service):
* Base URL: https://s3.eu-central-1.amazonaws.com
* Server Certificate Validation: Enable
* Authentication Type: Anonymous
* Relative URL: /avg-kitti/raw_data/2011_09_26_drive_0028/2011_09_26_drive_0028_extract.zip
* Binary Copy: Checked
* Destination File Path: adf / data_road.zip

5. Customer Parquet Conversion Notebook (for Azure Data Factory): 
