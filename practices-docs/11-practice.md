# #11 Share Configuration Across Pipelines
- The features in this section can help you share things across a number of pipelines in a secure way. This can be especially useful when you manage a large number of pipelines.
    - Variable Groups
        - Share variables across pipelines
        - Can be integrated with KeyVault
    - Task Groups
        - Share a number of combined tasks across pipelines
    - Secure Files
        - E.g. keystore files and signing certificates
- Deployment Groups are useful when deploying on a number VMs
    - During deployment you can target a group of machines rather than each individual machines
    - Machines can automatically register and de-register in a groups hence support deployment to machines you don't know about when creatig the pipeline
- All of the above allows you to control Security in details

![securefile][securefile]

[securefile]:  /images/11-secure-file.png "Secure File"
