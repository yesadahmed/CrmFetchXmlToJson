# CrmFetchXmlToJson
A devops pipeline utility for customer engagement to return fetchxml records in json format.
We can easliy parse json afterwards to get the varaibles we need.
for example, we can move some data from development crm orginaztion to test or 
production envirnoment.
The json will contain atribute name and value so we can use it where it need.

# Usage
<img src="https://raw.githubusercontent.com/yesadahmed/CrmFetchXmlToJson/main/pipelineimag.png" >

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
