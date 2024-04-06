# Which statement best describes how the DevOps team should proceed when using the Blue-Green deployment strategy in the OCI DevOps service to deploy a new version of their application to their production environment to ensure that the production environment is not affected by any potential issues caused by the new version?

> A custom function can be added to the Invoke function stage in the Blue-Green deployment strategy to validate the application in the standby environment before shifting the production traffic. This function can be used to perform additional testing and validation of the new version, such as running automated tests or checking the application's functionality. Once the validation is complete, the traffic shift can be performed to make the new version the production environment.

1. [x] The Invoke function stage in the Blue-Green deployment strategy is an optional stage that can be used to validate the new version before shifting the traffic to the new environment.
1. [ ] The Blue-Green deployment strategy does not involve any manual approval stage.
1. [ ] The Production stage in the Blue-Green deployment strategy deploys the new version to the standby environment without any manual approval.
1. [ ] The Blue-Green deployment strategy supports pipeline redeployment for both instance group and OKE.