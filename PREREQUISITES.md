## Pre-Requisites
* Visual Studio 2015, Visual Studio 2013 update 4, or Visual Studio 2012. Enterprise (Ultimate/Premium), Professional, Community editions are supported; Express edition is not supported. Visual Studio 2017 is currently not supported.
* Microsoft Azure SDK for .NET version 2.7.1 or above. Install it using the Web platform installer https://www.microsoft.com/web/downloads/platform.aspx.
* Data Lake Tools for Visual Studio https://www.microsoft.com/en-us/download/details.aspx?id=49504.

  Once Data Lake Tools for Visual Studio is installed, you will see a "Data Lake Analytics" node in Server Explorer under the "Azure" node (you can open Server explorer by pressing Ctrl+Alt+S).
* Data Lake Analytics account and sample data The Data Lake Tools don't support creating Data Lake Analytics accounts. You can create an account using the Azure portal, Azure PowerShell, .NET SDK or Azure CLI. For your convenience, a PowerShell script for creating a Data Lake Analytics service and uploading the source data file can be found in Appx-A PowerShell sample for preparing the tutorial https://docs.microsoft.com/en-us/azure/data-lake-analytics/data-lake-analytics-data-lake-tools-get-started#appx-a-powershell-sample-for-preparing-the-tutorial.

  Optionally, you can go through the following two sections in Get Started with Azure Data Lake Analytics using Azure portal https://docs.microsoft.com/en-us/azure/data-lake-analytics/data-lake-analytics-get-started-portal to create your account and upload data by hand:

1. Create an Azure Data Lake Analytics account https://docs.microsoft.com/en-us/azure/data-lake-analytics/data-lake-analytics-get-started-portal#create-data-lake-analytics-account.

2. Upload SearchLog.tsv to the default Data Lake Storage account https://docs.microsoft.com/en-us/azure/data-lake-analytics/data-lake-analytics-get-started-portal#prepare-source-data.
