# 
As a DevOps engineer, you are tasked with managing deployments on OCI Container Engine for Kubernetes (OKE). Which step is NOT required for setting up cluster access using a local installation of kubectl?

> To set up cluster access using a local installation of kubectl, you need to generate an API signing key pair (if you don't already have one) and upload the public key of the API signing key pair. You also need to install and configure the OCI CLI, and set up the kubeconfig file. However, generating an auth token from the OCI console is not required for setting up cluster access using kubectl.

1. [x] Generate an auth token from the OCI console to access the OKE cluster using kubectl.
1. [ ] Set up the kubeconfig file.
1. [ ] Generate an API signing key pair (if you don't already have one) and upload the public key of the API signing key pair.
1. [ ] Install and configure the OCI CLI.