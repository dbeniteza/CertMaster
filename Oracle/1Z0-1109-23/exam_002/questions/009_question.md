# You made a mistake adding variables to your build_spec.yaml file, which caused the build pipeline to fail. What could have possibly gone wrong?

> Hint

1. [x] You defined all the variables as vaultVariables to make them available in subsequent stages of the same pipeline.
1. [ ] You defined a field such as type: DOCKER_IMAGE in the outputArtifacts: section to specify the docker image produced by the Build stage.
1. [ ] You defined parameters such as the ${VARIABLE_NAME} file and later assigned their values on the Parameters tab of the build pipeline.
1. [ ] You defined variables as vaultVariables to hold the OCID of the secret from the vault. The value for these variables is retrieved from the vault.