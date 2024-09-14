# mulesoft-artifact - Parent POM

## local setup
- add server information on setings.xml
-- <id>anypoint-exchange</id> 

## Replace Anypoint OrgID to correct Anypoint OrgID
- Replace 37513a5c-61c8-4566-8c30-c9d2a08150d8 to your correct OrgID
## Currently works only with 
- https://maven.anypoint.mulesoft.com/api/v2/

## _Known issues
- Issue: https://maven.anypoint.mulesoft.com/api/v3/
-- status: 412 Precondition Failed. Feel free to resolve this

## Mule Connectors
- http-connector
- ftp-connector
- sftp-connector
- vm-connector
- objectstore
- db-connector
- sockets-connector
- wsc-connector
- file-connector

## Mule Modules
- apikit
- secure-configuration-property
- java
- validation
- xml
- soapkit