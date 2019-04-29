# Microsoft-Azure-ARM-AppService-Deployment
This Azure Resource Management solution allows you to deploy an Azure App Service Plan with X-amount of App Services. 

## Instructions
1. Clone repository to workstation/server
2. Open project in Microsoft Visual Studio 2017
3. Create a new deployment to Microsoft Azure
  3.1 Right click Azure-Web-App-Deployment-Template solution in the Solution Explorer
  3.2 Select Deploy
  3.3 Select New
  3.4 Enter Microsoft Azure Credentials for the target Subscription
4. Enter the parameters to define your App Service Plan and App Services (**figure A**):
  * __AppServicePlanName__: *App Service Plan Name*
  * __AppServicePlanSku__: *Defines the resource allocation and cost*
  * __AppServicePlanLocation__: *Defines the App Service Plan's hosted location*
  * __WebAppName__: *An array to set amount and name of App Service to instantiate and assign to the App Service Plan*
    * __*The App Service name must be unique globally on Microsoft Azure*__
5. Select Deploy
6. Upon successful deployment, each Azure resource will be available in target subscription (**figure B**)

## Visuals
### (**figure A**)
![](images/EditParameters.png)

### (**figure B**)
![](images/DeployResults.png)
