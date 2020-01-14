---
page_type: sample
languages:
- csharp
products:
- azure
extensions:
- services: Sql
- platforms: dotnet
---

# Getting started on managing SQL server keys with Azure key vault keys in C# #

 Azure SQL sample for managing SQL secrets (Server Keys) using Azure Key Vault -
  - Create a SQL Server with "system assigned" managed service identity.
  - Create an Azure Key Vault with giving access to the SQL Server
  - Create, get, list and delete SQL Server Keys
  - Delete SQL Server


## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-net/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/sql-database-dotnet-manage-sql-server-keys-with-azure-key-vault.git

    cd sql-database-dotnet-manage-sql-server-keys-with-azure-key-vault

    dotnet build

    bin\Debug\net452\ManageSqlServerKeysWithAzureKeyVaultKey.exe

## More information ##

[Azure Management Libraries for C#](https://github.com/Azure/azure-sdk-for-net/tree/Fluent)
[Azure .Net Developer Center](https://azure.microsoft.com/en-us/develop/net/)
If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.