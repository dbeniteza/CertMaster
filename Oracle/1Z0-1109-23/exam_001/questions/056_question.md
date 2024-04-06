# As a DevOps engineer, which method can be used to ensure the authenticity and integrity of container images deployed on OCI Cloud platforms?

> Signing the image using the Container Registry CLI and creating an image signature that associates the image with the master encryption key and key version in the Vault service helps to ensure that the container images have not been modified after being pushed to the OCI Registry. This is because the image signature verifies the integrity of the container image, ensuring that it hasn't been tampered with, and associates the image with the master encryption key and key version in the Vault service, providing an additional layer of security.

1. [ ] Enabling real-time scanning of container images stored in OCI Registry
1. [ ] Comparing the checksum of the container image with the original image after ingestion
1. [x] Signing the container image with the Container Registry CLI and associating it with a master encryption key in the Vault service
1. [ ] Deploying the container image to multiple Kubernetes clusters for redundancy and verification