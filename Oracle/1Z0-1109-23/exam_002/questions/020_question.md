# As a DevOps engineer managing artifacts for a microservices application in OCI DevOps, which statement is correct?

> In OCI DevOps, making artifacts immutable means that once they are uploaded or created, they cannot be modified or changed. This is a recommended practice to maintain the integrity and reliability of the artifacts throughout their life cycle. Immutable artifacts ensure that you have a consistent and reliable build and deployment process, as any changes to artifacts could introduce unintended errors or inconsistencies. By enforcing immutability, you can ensure that the same version of the artifact is used throughout the entire CI/CD pipeline, reducing the risk of potential issues caused by version discrepancies or accidental modifications.

1. [ ] An OCI Function is needed to store Managed Build stage output artifacts in the build pipeline.
1. [ ] Artifacts can be directly used by OCI DevOps without needing to be located or mirrored in an OCI Artifact or Container registry.
1. [x] It is recommended that you make artifacts immutable to prevent any modifications after they are uploaded.
1. [ ] The name, type, and source of artifacts cannot be modified after they are created.