# AwsRestDemo
Demo project to show how a .NET Core REST API can be depoyed to AWS ans hosted publicly. See the acompanying presentation [here]()

### Deploy
For deploy from a local machine use the [Amazon.Lambda.Tools](https://github.com/aws/aws-extensions-for-dotnet-cli#aws-lambda-amazonlambdatools) `dotnet lambda deploy-serverless` command  or alternatively download the [AWS Toolkit for Visual Studio]( https://marketplace.visualstudio.com/items?itemName=AmazonWebServices.AWSToolkitforVisualStudio2017) and use the Publish command.

Deployment prerequisites:
* AWS account
* S3 bucket in the region where you want to deploy the API

### Hosting
For the hosting part, you will need to have:
* A purchased domain. This can be obtained from AWS via Route 53, or from a third party. 
* An ACM certificate for this domain in the region you have deployed the API. This can be set up via AWS ACM



