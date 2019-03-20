# #12 Secure Service Connections & Service Principals

- Service Principals are the system identities used when doing anything in an Azure subscription
- Service Principals are used in Service Connection to allow Task to do their work
- Keep the keys safe!
- Limit the permissions and scope accordingly
- Service Connection default wizard will use your user and create a - Service Principal, which probably not what you want...
- Use ”Advanced Mode” in Service Connections Setup
    - Allows you to specify a specific Service Principal
    - Consider whether you want to set the Service Connection ”Allow all pipelines to use this endpoint” option
- You can use Management Group to control access across multiple subscriptions
- Familiarize yourself with the build and release permissions and security roles
    - For permissions, you grant or restrict permissions by setting the permission state to Allow or Deny, either for a security group or an individual user
    - You can control who can define new service connections

## Links
- Service Principals [https://docs.microsoft.com/en-us/azure/active-directory/develop/app-objects-and-service-principals][1]
- Build and release permissions and security roles [https://docs.microsoft.com/en-us/azure/devops/pipelines/policies/permissions?view=azure-devops][2]
- Service connections for builds and releases [https://docs.microsoft.com/en-us/azure/devops/pipelines/library/service-endpoints?view=azure-devops#secure-a-service-connection][3]
- Connect to Microsoft Azure [https://docs.microsoft.com/en-us/azure/devops/pipelines/library/connect-to-azure?view=azure-devops][4]

[1]: https://docs.microsoft.com/en-us/azure/active-directory/develop/app-objects-and-service-principals 
[2]: https://docs.microsoft.com/en-us/azure/devops/pipelines/policies/permissions?view=azure-devops
[3]: https://docs.microsoft.com/en-us/azure/devops/pipelines/library/service-endpoints?view=azure-devops#secure-a-service-connection
[4]: https://docs.microsoft.com/en-us/azure/devops/pipelines/library/connect-to-azure?view=azure-devops


