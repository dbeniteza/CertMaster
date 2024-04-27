# As you automate software releases using the Oracle Cloud Infrastructure (OCI) DevOps service to enhance frequent and error-free feature releases, you encounter a deployment stage failure while updating production. What action should you take in your deployment pipeline?

> When a deployment stage fails in the pipeline, the recommended action is to roll back to the last known good state, which is the previous successfully released version. This means reverting the pipeline to a state where the application was stable and functional. By doing this, you can avoid deploying potentially faulty code to production and ensure that your application remains in a reliable state. Once the issue causing the failure is identified and resolved, you can then proceed with re-deploying the updated version through the pipeline, ensuring a smooth and error-free release.

1. [ ] Utilize the OCI DevOps Trigger and Rerun tool to minimize downtime.
1. [x] Roll back the pipeline's failed stage to the previous successfully released version.
1. [ ] Include Rescue and Trigger stages to automatically trigger the failed deployment.
1. [ ] Implement an automated backup and utilize the re-release stage in the deployment pipeline.