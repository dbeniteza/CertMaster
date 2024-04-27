# What is the result of enabling a cluster to use its image verification policy but not specifying the master encryption key(s) that must have been used to sign an image?

> When a cluster's image verification policy is enabled but the master encryption key(s) that must have been used to sign an image are not specified, any signed image can be pulled from Oracle Cloud Infrastructure Registry, regardless of the master encryption keys used to sign it. Additionally, any unsigned image can be pulled from the registry. This means that the image verification policy will not have any effect in this case and any image can be deployed to the cluster. Therefore, it is important to specify the master encryption key(s) in the cluster's image verification policy to enforce the use of suitably signed images.

1. [ ] Only images signed using the default master encryption key can be pulled from Oracle Cloud Infrastructure Registry.
1. [x] Any signed image can be pulled from Oracle Cloud Infrastructure Registry, regardless of the master encryption keys used to sign it.
1. [ ] No images can be pulled from Oracle Cloud Infrastructure Registry.
1. [ ] Any unsigned image can be pulled from Oracle Cloud Infrastructure Registry.