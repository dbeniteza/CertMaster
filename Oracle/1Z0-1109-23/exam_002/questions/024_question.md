# A customer has deployed their microservices-based application on Oracle Container Engine for Kubernetes (OKE) using the "custom create" option. The Virtual Cloud Network (VCN) hosting the OKE cluster has three public subnets with associated route tables, security lists, and an internet gateway. However, they are facing an issue where the application containers fail to deploy. The YAML configuration has the correct path to the images in Oracle Cloud Infrastructure Registry (OCIR).

Which two are valid concerns that require further investigation?

- [ ] They need to add a security list rule for TCP port 22 to connect to the OCIR service.
- [ ] The VCN hosting the OKE cluster worker nodes needs to have a NAT gateway to access OCIR repositories.
- [ ] They need to add IAM credentials for each user who deploys applications to the OKE cluster.
- [x] The OKE cluster needs to have a secret with credentials of their OCIR repository and use that secret in the Kubernetes deployment manifest.
- [x] They need to use kubectl to create a Docker registry secret containing the Oracle Cloud Infrastructure credentials to use when pulling the image.