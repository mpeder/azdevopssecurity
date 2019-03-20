# #6 Use Approvals, Gates & Pull Requests
- Use approvals to control deployment stages
    - Can be set both pre and post deployment
    - You can also include manual intervention task inside a pipeline
- Use gates to control deployment stages 
    - Can be set both pre and post deployment
- Use Pull Request for QA 
    - Both for security and general quality
    - Run builds and deployments before merging to Master
- If you use 3rd party solutions for e.g. Feature Toggling consider the security aspects of these services
    - And who controls the feature toggle?
    - This can also be automated via Pipelines with e.g. LaunchDarkly

![gates][gates]

[gates]:  /images/06-gates.png "Gates"