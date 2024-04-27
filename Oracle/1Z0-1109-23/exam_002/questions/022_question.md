# You are an administrator of an OKE cluster and want to manage your own master encryption key for encrypting Kubernetes Secrets in the cluster. Which of the following steps are required to achieve this?

> To manage your own master encryption key for an OKE cluster, you need to create a dynamic group in IAM that includes all clusters in the compartment, and create a policy authorizing the group to use the master encryption key. Then, you need to use the Custom Create workflow to create the cluster and select the option to manage the master encryption key yourself. The Quick Create workflow wizard does not provide this option.

1. [x] Create a dynamic group in IAM that includes all clusters in the compartment, and create a policy authorizing the group to use the master encryption key. Use the Custom Create workflow to create the cluster and select the option to manage the master encryption key yourself.
1. [ ] Create a new policy authorizing the cluster to use the master encryption key.
1. [ ] Create a new compartment in the Vault service to store the master encryption key.
1. [ ] Use the Quick Create workflow to create the cluster and select the option to manage the master encryption key yourself.