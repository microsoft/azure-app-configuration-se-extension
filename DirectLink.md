# Direct link

On Windows and macOS, Storage Explorer supports URIs with the `storageexplorer://` protocol. These URIs are referred to as direct links. A direct link points to an Azure Storage resource in Storage. Following a direct link will open Storage Explorer and navigate to the resource it points to. The direct link can be a good way to share the location of a particular resource to someone who has access to it.

## Azure App Configuration direct links

The Azure App Configuration extension supports direct link with the following parameters.

Parameter         | Description
:-----------------| :---------
`v`               | Version of the direct link protocol.
`type`            | The type of service the direct link is for. For Azure App Configuration store, this value will be `appConfigStore`.
`id`              | The id of the user's Azure account.
`tenantId`        | The tenant id of the user's Azure account.
`store`           | The name of an Azure App Configuration store.
`serviceEndpoint` | The service endpoint of the Azure App Configuration store.
`resourceGroup`   | The name of the Azure resource group the store belongs to.

Here is an example direct link to an Azure App Configuration store. 

`storageexplorer://?v=1&type=appConfigStore&id=<account_id>&tenantId=<tenant_id>&store=test-store&serviceEndpoint=https%3A%2F%2test-store.azconfig.io&resourceGroup=testResourceGroup`

## Use a direct link in Storage Explorer

Open the context menu of an App Configuration store's node and click the "Copy Direct Link to App Configuration Store" action. It will construct a direct link to the store and copy the direct link to the clipboard.
