# Query your API usage using Genesys Cloud CLI and analyze it with AWS S3/Athena

> View the full [Usage API Blueprint article](https://developer.genesys.cloud/blueprints/usage-api-blueprint/) on the Genesys Cloud Developer Center.

This Genesys Cloud Developer Blueprint demonstrates how to use the Genesys Cloud command line interface (CLI) to query your organization's API usage. Analyzing API usage is essential to optimize and scale any solution that uses the API. The blueprint provides a sample workflow that shows you how to monitor and analyze usage for unexpected issues that have business impact, such as rate limiting. This enables you to adjust any affected applications promptly. This blueprint also includes an example integration that shows how to export the usage data to an AWS S3 bucket and use AWS Athena to process queries against it.

![Usage API Blueprint](blueprint/images/overview.png)
