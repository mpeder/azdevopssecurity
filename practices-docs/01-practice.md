# #1 Secure Your Azure DevOps Account
- Connect to Azure AD and use MFA
- Azure DevOps can also use AAD Conditional Access 
    - You can require conditions, such as security group membership, location and network identity, a specific OS, an enabled device in a management system, and so on.
- If possible use AD Groups not individual user accounts
    - Note: Nested groups is currently not supported
- Consider connecting to Express Route
- User Azure DevOps Audit feature

## Links
- Azure AD [https://docs.microsoft.com/en-us/azure/devops/organizations/accounts/connect-organization-to-azure-ad?view=azure-devops][1]
- Conditional Access [https://docs.microsoft.com/en-us/azure/devops/organizations/accounts/manage-conditional-access?view=azure-devops][2]
- ExpressRoute [https://devblogs.microsoft.com/devops/expressroute-for-azure-devops][3] 
- Azure DevOps Audit [https://docs.microsoft.com/en-us/azure/devops/organizations/settings/azure-devops-auditing?view=azure-devops][4]

[1]: https://docs.microsoft.com/en-us/azure/devops/organizations/accounts/connect-organization-to-azure-ad?view=azure-devops
[2]: https://docs.microsoft.com/en-us/azure/devops/organizations/accounts/manage-conditional-access?view=azure-devops
[3]: https://devblogs.microsoft.com/devops/expressroute-for-azure-devops
[4]: https://docs.microsoft.com/en-us/azure/devops/organizations/settings/azure-devops-auditing?view=azure-devops
