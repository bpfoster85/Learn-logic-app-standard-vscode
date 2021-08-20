# Learn-logic-app-standard-vscode
A second interation of Logic Apps has been in the works for a bit now. It is know by a few names; Logic Apps V2, Logic Apps Single Tenant, Logic Apps Standard.



- In multi-tenant Azure Logic Apps, ARM templates pose a challenge when you have to maintain environment variables for logic apps across across various dev, test, and production environments. Everything in an ARM template is defined at deployment. If you need to change just a single variable, you have to redeploy everything.

- workflow folder structure
    Sits on root level of the project, so it is nice to have a defined naming convention. I personally use wk_[trigger]_[OutcomeAction]_[friendlyName].json

- In Visual Studio Code, when you use the designer to develop or make changes to your workflows, the Logic Apps engine automatically generates any necessary connection metadata in your project's connections.json file.

### Reference Documentation
- Overview of Single Tenant
    https://docs.microsoft.com/en-us/azure/logic-apps/single-tenant-overview-compare
- Set up devops 
     https://docs.microsoft.com/en-us/azure/logic-apps/set-up-devops-deployment-single-tenant-azure-logic-apps?tabs=github

- Estimate Storage costs for workflow
    https://docs.microsoft.com/en-us/azure/logic-apps/estimate-storage-costs