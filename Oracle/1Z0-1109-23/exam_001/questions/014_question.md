# Suppose you have pushed a Docker image to your Container Registry repository in Oracle Cloud Infrastructure (OCI), and now you want to get that image onto your local machine so that you can run it locally. Which command should you use to achieve this?

> The docker pull <region-key>.ocir.io/<tenancy-namespace>/<repo-name>:<tag> command pulls the specified image from the registry to the local machine, where it can be run using the docker run command.

1. [ ] docker tag <region-key>.ocir.io/<tenancy-namespace>/<repo-name>:<tag>
1. [x] docker pull <region-key>.ocir.io/<tenancy-namespace>/<repo-name>:<tag>
1. [ ] docker fetch <region-key>.ocir.io/<tenancy-namespace>/<repo-name>:<tag>
1. [ ] docker push<region-key>.ocir.io/<tenancy-namespace>/<repo-name>:<tag>