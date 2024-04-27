# Which two statements about a Dockerfile are false?

> Docker WORKDIR is a Dockerfile instruction that is used to set the working directory for any instructions, such as RUN, CMD, ENTRYPOINT, COPY, and ADD. This means that any command mentioned after these instructions will be executed in the working directory that is specified using the WORKDIR instruction in the Dockerfile. If the CMD instruction provides default arguments for the ENTRYPOINT instruction, both should be specified in JSON format.

- [x] If the COMMAND instruction provides default arguments for the ENTRYPOINT instruction, both should be specified in JSON format.
- [ ] The ENV instruction sets the environment value to the key, and it is available for the subsequent build steps and in the running container as well.
- [ ] The EXPOSE instruction maps a port into the container. The ports can be TCP or UDP, but by default, they are TCP.
- [ ] The RUN instruction executes any commands in a new layer on top of the current image and commits the results.
- [x] The WORKDIR instruction sets the working directory for any RUN, CMD, and ENTRYPOINT instructions and not for the COPY and ADD instructions in the Dockerfile.