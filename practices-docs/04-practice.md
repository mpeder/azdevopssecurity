# #4 Design & Maintain Your Pipelines
- Do the right people have access?
- What are the environments/stages involved?
    - What the flow between stages? Consider artifact/branch filter
    - What is allowed in parallel? Both on the stage and when using multiple agents in a stage
    - What is the triggers(s)?
- Pipelines become very important the more you automate!
    - It may become critical infrastructure
- The application and infrastructure matters
    - IaaS, PaaS, SaaS, Cloud, On-premise, Multi cloud, Azure Stack
- Maintain, test and clean up pipelines
    - Your infrastructure might change this can have an effect on your pipelines
    - Easier if you use IaC and Pipelines as Code
- Provide guidance on ”good” pipelines design in your environments so that projects/teams can easily adopt the practices relevant in your organization

## Links
- Also see #15 [Use Pipeline Decorators][1]

[1]: /practices-docs/15-practice.md


