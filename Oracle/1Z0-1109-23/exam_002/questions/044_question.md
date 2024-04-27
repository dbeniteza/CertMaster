# You are a Kubernetes administrator in charge of managing a cluster in OCI Container Engine for Kubernetes. Your team is considering making some modifications to the cluster properties to optimize performance and resource utilization. However, you are unsure about which modifications are possible and which are not. Which two statements regarding modifying Kubernetes cluster properties are FALSE?

> The version of Kubernetes can be changed for both control plane nodes and worker nodes. The number of node pools in a cluster can be changed by adding or deleting node pools, and the number of worker nodes in a node pool, as well as the availability domains and subnets in which to place them, can also be changed. However, the image and shape used by the existing worker nodes cannot be changed; if you want to change the image or shape, you must create a new node pool with the desired configuration and migrate your workloads to the new node pool.

- [x] You can change the image and shape used by the existing worker nodes.
- [ ] You can change the number of worker nodes in a node pool, and the availability domains and subnets in which to place them.
- [x] You can change the version of Kubernetes to run on control plane nodes but cannot change the version of Kubernetes on worker nodes.
- [ ] You can change the version of Kubernetes to run on control plane nodes and worker nodes.
- [ ] You can change the number of node pools in a cluster by adding new node pools or deleting existing node pools.