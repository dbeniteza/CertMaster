# In the OCI DevOps service, you define the same parameter in both the build and deployment pipelines with different values. You pass the parameter as an exported value to deploy and run the pipelines. Which of the following statements is true?

> When you define the same parameter with different values in both the build and deployment pipelines, and pass the parameter as an exported value to deploy and run the pipelines, the value set in the build pipeline takes precedence. This is because the build pipeline executes before the deployment pipeline, and any values set in the build pipeline are passed on to the deployment pipeline.

1. [ ] The deployment pipeline fails to run the build when it has a different value.
1. [ ] The values set in the build pipeline and deployment pipeline are concatenated.
1. [x] The value defined in the build pipeline takes precedence over the value defined in the deployment pipeline.
1. [ ] The value defined in the deployment pipeline takes precedence over the value defined in the build pipeline.