# You intend to ensure that only container images that have been signed with an OCI Vault master encryption key are used for deployments to an Oracle Container Engine for Kubernetes (OKE) cluster. Which of the following statements is correct?

> Image signature verification policies can only be enabled at the OKE cluster level by an administrator. The administrator needs to enable the policy for image signature verification in the OKE cluster configuration. Image signature verification is not required for all deployments to an OKE cluster in a production environment by default, but it can be enforced by the administrator through configuration.

1. [ ] Image signature verification policies are enabled at the kubernetes pod level.
1. [ ] Image signature verification is required for all deployments to an OKE cluster in a production environment.
1. [ ] Image signature verification policies are explicitly disabled or enabled for each image by the developer when uploading to Oracle Container Registry (OCIR).
1. [x] Image signature verification policies can only be enabled at the OKE cluster level by an administrator.