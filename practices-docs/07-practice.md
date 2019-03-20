# #7 Use Continuous Security Tools in Pipelines
- Security needs to be evaluated at every step of the process in a continuous process
- Static Code Analysis
    - There is a number of tools available and the best tool for you will also depend on the programming language(s) used
    - Some examples of code analytis tools are Visual Studio Code Analysis, Roslyn Security Analyzers, Checkmarx and BinSkim 
- Vulnerability Scans
    - Modern application development involves using different package managers. By using the you can easily end up using 100s of packages
    - 3rd party packages should be analyzed for vulnarbilities, licensing and old versions
    - WhiteSource and Black Duck are good examples of tools for vulnerability scanning
- Infrastructure as Code Scans
    - By scanning IaC you can find problems before doing actual deployment
    - An example of such a tool is AzSK ARM Template Checker
- Credential Scans
    - Creadentials not never be checked in to your repos
    - These tools look for secrets, password and usernames in the code checked in to your repos and can then fail a build or deployments
    - An example of such a tool is the Credential Scanner (aka CredScan)
- Container Image Scanning
    - There is a lot of extra scanning required when using containers.
    - Some great tools for this is WhiteSource, Black Duck, Aqua and Twistlock
    - These can also be integrated with Azure Container Registry
- Secure DevOps Kit for Azure & Microsoft Security Code Analysis is a great collection of tools that can easily be integrated into Azure DevOps Pipelines
- Define enterprise wide baseline for all these tools
    - Consider also scanning for technical debt using a tool like SonarQube/SonarCloud


## Links
- Security validation in CI/CD pipeline [https://docs.microsoft.com/en-us/azure/devops/articles/security-validation-cicd-pipeline?view=azure-devops][1]
- Secure DevOps Kit for Azure [https://azsk.azurewebsites.net/][2]
- Microsoft Security Code Analysis [https://secdevtools.azurewebsites.net/][3]

[1]: https://docs.microsoft.com/en-us/azure/devops/articles/security-validation-cicd-pipeline?view=azure-devops 
[2]: https://azsk.azurewebsites.net/
[3]: https://secdevtools.azurewebsites.net/