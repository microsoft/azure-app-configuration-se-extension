# Getting started

## Prerequisites

Microsoft Azure Storage Explorer is a standalone app that makes it easy to work with Azure Storage data on Windows, macOS and Linux. You need to install Storage Explorer 1.25.0 or later to be able to use this extension. To download and install the latest version of Storage Explorer, see [download Microsoft Azure Storage Explorer](https://azure.microsoft.com/features/storage-explorer/).

The extension requires the **App Configuration Data Owner** or **App Configuration Data Reader** role on your user account to grant permissions for accessing the resources. You can configure the role assignments of your Azure App Configuration resources from [Azure Portal](https://portal.azure.com).

## Download and install the extension

- Download the Azure App Configuration extension for Storage Explorer from [here](https://127.0.0.1)
- On Windows or macOS, you can launch the extension bundle (.seix) to install. It will automatically open Storage Explorer with the extension enabled. On Linux, you can use the "File" → "Open Extension" item in the app menu and select the extension bundle to install.
- Once the extension is installed, it will show up in the extensions panel in Storage Explorer.

![Installed extension](./images/InsatlledExtension.PNG)

## Sign-in to Azure account

Use the Connect dialog to sign-in to your Azure account.

(todo) screenshots of sign-in flow

## Access Azure App Configuration resources

Once signed-in, you can expand the subscription nodes to access your Azure App Configuration stores. You can also open the data explorer for a store to manage the key-values in it.

![Extension tree explorer](./images/ExtensionTreeExplorer.PNG)

 The extension provides the basic features to manage your key-values in your stores. If you would like to see additional features, please open a feature request using [Issues](link_to_issues_with_feature_request_template).