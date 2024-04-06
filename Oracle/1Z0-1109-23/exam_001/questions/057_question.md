# As a DevOps engineer, you need to test the execution of a particular container image even though it violates the cluster's image verification policy. What step can you take to allow a specific pod to pull such an image?

> According to the scenario, if a particular pod needs to pull an image that violates the cluster's image verification policy, the annotation oracle.image-policy.k8s.io/break-glass: "true" can be added to the pod spec. This annotation will allow the pod to pull any signed and unsigned images from Oracle Cloud Infrastructure Registry, regardless of the cluster's image verification policy.

1. [ ] By manually modifying the image signature of the image in Oracle Cloud Infrastructure Registry
1. [ ] By adding the oracle.image-policy.k8s.io/allow-unsafe-images: "true" annotation to the pod spec
1. [ ] By modifying the image verification policy for the entire cluster
1. [x] By adding the oracle.image-policy.k8s.io/break-glass: "true" annotation to the pod spec