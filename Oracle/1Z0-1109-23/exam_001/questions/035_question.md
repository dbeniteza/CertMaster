# As a DevOps engineer, you are responsible for deploying a new version of an application using the Blue-Green deployment strategy in OCI DevOps service. Which of the following statements about the different stages of this strategy is correct?

> The Blue-Green deployment stage involves selecting the two environments, either for instance group or for OKE, and selecting the artifacts to be deployed. For instance group blue-green traffic shift, a load balancer is selected, whereas for OKE deployment, NGINX ingress controller has to be set up for routing the traffic.

1. [ ] The Manual approval stage is mandatory to approve the deployment in the standby environment before shifting the production traffic.
1. [ ] The Invoke function stage is mandatory to validate the new version before shifting the traffic to the new environment.
1. [x] In the Blue-Green deployment stage, the load balancer is selected for instance group blue-green traffic shift or NGINX ingress controller has to be set up for routing the traffic for OKE deployment.
1. [ ] In the Blue-Green traffic shift stage, 50% of the production traffic is shifted from the current active environment to the standby environment running the validated new version of the application.