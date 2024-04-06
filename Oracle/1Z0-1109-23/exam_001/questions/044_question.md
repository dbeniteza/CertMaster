# Which three statements are true about using Ansible on OCI?

> While Ansible can perform various tasks related to configuration, deployment, and orchestration, it is not designed for collecting billing and usage data for OCI tenancy. You can use OCI APIs, the Console, or other billing tools for that purpose. The task sequence in an Ansible playbook matters, and Ansible executes tasks in the order they are defined in the playbook. Ansible evaluates dependencies, but it will still execute tasks in the order specified in the playbook.

- [ ] The task sequence in your Ansible playbook does not matter. Ansible will evaluate dependencies and execute tasks in the most effective sequence.
- [x] You can use Ansible to create and destroy OCI resources, such as compute instances and load balancers.
- [ ] You can use Ansible to collect billing and usage data for your OCI tenancy.
- [x] You can use Ansible to restart Apache on all web servers as defined in inventory.
- [ ] You can use Ansible to execute a shell command on a collection of hosts.