---
page_type: sample
languages:
- csharp
products:
- azure
extensions:
  services: Monitor
  platforms: dotnet
---

# Getting metrics and activity logs for a resource. #

 This sample shows examples of retrieving metrics and activity logs for Storage Account.
  - List all metric definitions available for a storage account
  - Retrieve and show metrics for the past 7 days for Transactions where
    - Api name was 'PutBlob' and
    - response type was 'Success' and
    - Geo type was 'Primary'
  -  Retrieve and show all activity logs for the past 7 days for the same Storage account.


## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-net/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/monitor-dotnet-query-metrics-activitylogs.git

    cd monitor-dotnet-query-metrics-activitylogs

    dotnet build

    bin\Debug\net452\QueryMetricsAndActivityLogs.exe

## More information ##

[Azure Management Libraries for C#](https://github.com/Azure/azure-sdk-for-net/tree/Fluent)
[Azure .Net Developer Center](https://azure.microsoft.com/en-us/develop/net/)
If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.