# AKS-AzuePipeline


az login
You have logged in. Now let us find all the subscriptions to which you have access...
[
  {
    "cloudName": "AzureCloud",
    "homeTenantId": "",
    "id": "",
    "isDefault": true,
    "managedByTenants": [],
    "name": "Pay-As-You-Go",
    "state": "Enabled",
    "tenantId": "",
    "user": {
      "name": "$Name",
      "type": "user"
    }
  }
]


az ad sp create-for-rbac --role="Contributor" --scopes="/subscriptions/4ID"
Creating a role assignment under the scope of "/subscriptions/ID"
  Retrying role assignment creation: 1/36
{
  "appId": "",
  "displayName": "a",
  "name": "NAME",
  "password": "",
  "tenant": ""
  
  
  az aks get-credentials --name test --resource-group test
