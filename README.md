# AzureDataFactory-CICD

This repo contains demo resources for doing CI/CD in Azure Data Factory. This repo can be imported into Azure DevOps.

Instructions:
1. The default "main" branch contains some example GIT data factory resources
2. The ADF default publish branc "adf_publish" contains two .yml files and a powershell script.
    * The .yml file 'deployment-pipeline.yml' ca nbe imported as a pipeline in Azure DevOps. Updating the variables for subscriptionName and subscriptionId should make available a generic ADF CI/CD deployment pipeline in Azure DevOps. 
    * For instructions regarding the powershell script see https://docs.microsoft.com/en-us/azure/data-factory/continuous-integration-deployment
   
