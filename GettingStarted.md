# Getting started

## Prerequisites

Microsoft Azure Storage Explorer is a standalone app that makes it easy to work with Azure Storage data on Windows, macOS and Linux. You need to install Storage Explorer 1.25.0 or later to be able to use this extension. To download and install the latest version of Storage Explorer, see [download Microsoft Azure Storage Explorer](https://azure.microsoft.com/en-us/features/storage-explorer/).

## Download and install the extension

- Download and install the Azure App Configuration extension for Storage Explorer from [download link](https://127.0.0.1)
- On Windows or macOS, you can launch the extension bundle (.seix) to install. It will automatically open Storage Explorer with the extension enabled. On Linux, you can use the "File" → "Open Extension" item in the app menu and select the extension bundle to install.
- Once the extension is installed, it will show up in the extensions panel in Storage Explorer.

(todo) screenshot of successfully installed extension

## Sign-in to Azure account

Use the Connect dialog to sign-in to your Azure account.

(todo) screenshots of sign-in flow

## Access Azure App Configuration resources

Once signed-in, you can expand the subscription nodes to access your Azure App Configuration stores. You can also open the data explorer for a store to manage the key-values in it.

(todo) screenshots of tree view and the in explorer view

 The extension provides the basic features to manage your key-values in your stores. If you would like to see additional features, please open a feature request using [Issues](link_to_issues_with_feature_request_template).

## Common Issues

- The extension requires certain Role based Access Control (RBAC) permissions on your Azure account to be able to access the resources. It is common for a user to be missing the App Configuration Data roles for a store which will block reading or writing key-values in the store. If you encounter an error while trying to access your data and the error message suggests it is an authorization error, please follow the instructions to configure your RBAC permissions for your resources.