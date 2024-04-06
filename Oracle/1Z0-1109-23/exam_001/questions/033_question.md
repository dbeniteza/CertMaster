# Which statement is true about working with DevOps projects and environment variables?

> In a build pipeline, environment variables are used to store and pass information between build stages or steps. When a build is triggered, environment variables can be defined in the build specification file.

However, not all environment variables can be accessed in later build stages or steps. Only variables that are exported can be brought into later stages.

1. [ ] Environment variables are not defined in the build specification file, but are imported from other files when a build is triggered.
1. [x] All environment variables can be brought into later steps, but only exported variables can be brought into later build stages.
1. [ ] Environment variables can include user-defined input but cannot be predefined on the build server.
1. [ ] You can’t ever use a secret in OCI Vault as a variable due to security reasons.