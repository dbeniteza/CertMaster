# A DevOps engineer is asked to access an Oracle Cloud Infrastructure Container Engine for Kubernetes (OKE) cluster to deploy new applications and manage existing ones. Which two statements are false?

> You must configure a Kubernetes configuration file for the cluster in order to use kubectl to access the cluster. The $HOME/.kube directory contains the config file, which by default has the name config. There are two ways for accessing a cluster with a public IP endpoint for the Kubernetes API: one is through a cloud shell, and the other is through local access.

- [x] The only available option when a cluster's Kubernetes API endpoint has a public IP address is to control the cluster locally using kubectl and the Kubernetes Dashboard.
- [x] To access the cluster using kubectl, you have to set up a Kubernetes manifest file for the cluster. The kubeconfig file by default is named config and stored in the $HOME/.manifest directory.
- [ ] Generating an API signing key pair is a mandatory step while setting up cluster access using local machine if the public key is not already uploaded in the console.
- [ ] When a cluster's Kubernetes API endpoint has a public IP address, you can access the cluster in Cloud Shell by setting up a kubeconfig file.
- [ ] To access the cluster using kubectl, you have to set up a Kubernetes configuration file for the cluster. The kubeconfig file by default is named config and stored in the $HOME/.kube directory.