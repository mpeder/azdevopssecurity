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

## Links
- Service Principals [https://docs.microsoft.com/en-us/azure/active-directory/develop/app-objects-and-service-principals][1]

[1]: https://docs.microsoft.com/en-us/azure/active-directory/develop/app-objects-and-service-principals 




