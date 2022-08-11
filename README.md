# CrmFetchXmlToCSVOrJson
A devops pipeline utility for microsft customer engagement(dataverse) to save fetchxml records in CSV or JSON format.
We can save the fiel in Publish Artifact folder and later can use the save records to migrate data to some other 
Crm organization.
for example, we can move some configuration data from development orginaztion to test or 
production envirnoment.

The usage, csv and json format is shown below.

# Usage
<img src="https://raw.githubusercontent.com/yesadahmed/CrmFetchXmlToJson/main/pipelineimag.png" >

# CSV Output
<img src="https://raw.githubusercontent.com/yesadahmed/CrmFetchXmlToJson/main/csv.png" >

# Json Output
```json
[
  {
    "Key": "ownerid",
    "Type": "Microsoft.Xrm.Sdk.EntityReference",
    "Id": "d0fca0a6-81d3-e911-a97c-000d3ab3f524",
    "Name": "# columbusceadmin",
    "LogicalName": "systemuser",
    "Alias": "",
    "entity": "account",
    "Value": "d0fca0a6-81d3-e911-a97c-000d3ab3f524"
  },
  {
    "Key": "accountid",
    "Type": "System.Guid",
    "Id": "",
    "Name": "",
    "LogicalName": "",
    "Alias": "",
    "entity": "account",
    "Value": "fefcf7a5-3da0-ea11-a812-000d3ad91105"
  },
  {
    "Key": "col_deductablecompany",
    "Type": "System.Boolean",
    "Id": "",
    "Name": "",
    "LogicalName": "",
    "Alias": "",
    "entity": "account",
    "Value": "False"
  },
  {
    "Key": "createdon",
    "Type": "System.DateTime",
    "Id": "",
    "Name": "",
    "LogicalName": "",
    "Alias": "",
    "entity": "account",
    "Value": "01/24/2010 00:00:00"
  },
  {
    "Key": "name",
    "Type": "System.String",
    "Id": "",
    "Name": "",
    "LogicalName": "",
    "Alias": "",
    "entity": "account",
    "Value": "  Arbeidernes Ungdomsfylking (AUF)"
  },
  {
    "Key": "statecode",
    "Type": "Microsoft.Xrm.Sdk.OptionSetValue",
    "Id": "",
    "Name": "",
    "LogicalName": "",
    "Alias": "",
    "entity": "account",
    "Value": "0"
  }
]

```
