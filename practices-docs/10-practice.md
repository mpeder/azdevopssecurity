# #10 Understand Security in Agents and Agent Pools
- Pipeline use Agents to do all of the actual work
- Agents are grouped in Agent Pools on which you can control security
- Agent can be hosted by Azure DevOps or yourself
    - Hosted agents are patched and update by Azure DevOps
    - You can easily have your own in container, in VM, on laptops or on-premise
    - But you need proper admin permissions to connect them to Azure DevOps Agent Pools
- Agents required outbound port 443 and line of sight for deployment tasks

![agents com][agents-com1]
![agents com][agents-com2]

## Links
- Agent communication [https://docs.microsoft.com/en-us/azure/devops/pipelines/agents/agents?view=azure-devops#communication][1]

[1]: https://docs.microsoft.com/en-us/azure/devops/pipelines/agents/agents?view=azure-devops#communication 

[agents-com1]:  /images/10-agent-com-01.png "Agent Communication"
[agents-com2]:  /images/10-agent-com-02.png "Agent Communication"

