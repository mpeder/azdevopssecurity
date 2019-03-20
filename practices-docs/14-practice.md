# #14 Containers at Scale Require Additional Governance
- Security internally in the cluster and network between containers, by default any container can talk to other containers
- A lot of security aspects/configurations are ”hidden” in the Dockerfiles/YAML/Helm Charts
- Use scanning tools for container, image registries and running containers (Aqua, Twistlock, WhiteSource, Blackduck, etc...)
- Use KeyVault for secrets
- Enable RBAC on cluster
- Container tagging strategy is important
- You build both applications and images

![devops][devops]

[devops]:  /images/14-devops-containers.png "DevOps Containers"