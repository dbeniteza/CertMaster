# What is the role of an NGINX ingress controller in the Canary deployment strategy for OKE?

> As the OKE cluster doesn't have an ingress controller, by default an NGINX ingress controller has to be set up for the Canary deployment strategy. An ingress controller is a Kubernetes application that routes traffic based on ingress specification. The NGINX ingress controller monitors ingress resources for load balancing. The traffic is shifted from staging to the production environment by updating the ingress resource.

1. [x] To approve the deployment in the canary environment before deploying the application in the production environment
1. [ ] To validate the deployment in the canary environment
1. [ ] To deploy artifacts to the production environment
1. [ ] To monitor ingress resources for load balancing