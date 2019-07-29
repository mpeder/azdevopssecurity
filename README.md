# Azure DevOps: Recommended Practices for Secure Pipelines

## Introduction
This repos started as part of building a customer presentation. After digging into it I found that I could keep on adding content related to this topic. So this is an attempt on doing so in a structured way. 

I would love to get feedback on the content and would like to keep expanding and updating the content. So please add your comments/issues and I will look into it when I have time :-)

Pipelines in the context of Azure DevOps covers both build (CI) and release pipelines (CD). Most of the stuff here is related to Azure DevOps when deploying to Azure, but might be equally applicable in many other situations as well. Feel free to use the information anyway you want - see the [LICENSE](LICENSE). These are my _personal_ recommendations! No guarantees of any kind given and I am not responsible for any damages :-)

For a general introduction to the security in the Azure DevOps service please see the [security whitepaper](https://docs.microsoft.com/en-us/azure/devops/articles/team-services-security-whitepaper?view=azure-devops).

If you are interested in DevSecOps from a cultural perspective I would recommend this article: [https://docs.microsoft.com/en-us/azure/devops/learn/devops-at-microsoft/security-in-devops](https://docs.microsoft.com/en-us/azure/devops/learn/devops-at-microsoft/security-in-devops)

## Practices
 1. [Secure Your Azure DevOps Account][1]
 2. [Know Your Azure DevOps Account & Projects][2]
 3. [Understand the Main Security Concepts in Azure DevOps][3]
 4. [Design & Maintain Your Pipelines][4]
 5. [Setup Detailed Permissions for Pipeline][5]
 6. [Use Approvals, Gates & Pull Requests][6]
 7. [Use Continuous Security Tools in Pipelines][7]
 8. [Use Artifacts for Package Management][8]
 9. [Implement Regular Azure Governance][9]
 10. [Understand Security in Agents and Agent Pools][10]
 11. [Share Configuration Across Pipelines][11]
 12. [Secure Service Connections & Service Principals][12]
 13. [Use Azure Key Vault][13]
 14. [Manage Extensions][14]
 15. [Use Pipeline Decorators][15]


[1]: /practices-docs/01-practice.md
[2]: /practices-docs/02-practice.md
[3]: /practices-docs/03-practice.md
[4]: /practices-docs/04-practice.md
[5]: /practices-docs/05-practice.md
[6]: /practices-docs/06-practice.md
[7]: /practices-docs/07-practice.md
[8]: /practices-docs/08-practice.md
[9]: /practices-docs/09-practice.md
[10]: /practices-docs/10-practice.md
[11]: /practices-docs/11-practice.md
[12]: /practices-docs/12-practice.md
[13]: /practices-docs/13-practice.md
[14]: /practices-docs/14-practice.md
[15]: /practices-docs/15-practice.md

Current version: v1.2
Last update: 29-07-2019
Major changes: Added #15 "Use Pipeline Decorators"