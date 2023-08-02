# Flow Metrics for Epics & Features (Azure DevOps & Jira)

### What is this report? 
This report will visualize the four flow metrics of Throughput, Cycle Time, Work In Progress and Work Item Age but for your Feature or Epic work item types

### Why shuld you use it? 
Managing the flow of work is not something limited to just teams. Flow should be proactively managed on a regular cadence at all levels (Story/Feature/Epic) of work.

### When should you use it?
Use this at least weekly to understand the ‘flow’ of work items at Epic or Feature level. Use it to look at what has recently finished, how long those items took, if there is anything to learn from those and if we are seeing the projected value from them. Similarly use it to look at what is in flight right now - if you are limiting work in progress, what items have been in progress the longest and what should you be focusing your attention on finishing.

### Prerequisites
* [Make sure you have the latest version of Power BI Desktop](https://aka.ms/pbiSingleInstaller)
* Download the appropriate template file:
  - [Jira version](https://github.com/nbrown02/Flow-Metrics-Epics-Features/raw/main/Flow%20Metrics%20for%20Epics%20and%20Features%20(Jira).pbit)
  - [Azure DevOps version](https://github.com/nbrown02/Flow-Metrics-Epics-Features/raw/main/Flow%20Metrics%20for%20Epics%20and%20Features%20(Azure%20DevOps).pbit)
* If you are setting this up for Jira then [Follow these steps](https://support.atlassian.com/atlassian-account/docs/manage-api-tokens-for-your-atlassian-account/) to setup a Jira API token and note it down (e.g. copy/paste into Notepad)
* If you are setting this up for Azure DevOps then [Follow these steps](https://learn.microsoft.com/en-us/azure/devops/organizations/accounts/use-personal-access-tokens-to-authenticate?view=azure-devops&tabs=Windows#create-a-pat) to setup a Personal Access Token (PAT) and note it down (e.g. copy/paste into Notepad)
* Then you're good to get started!

### Jira Connectivity
* Open the relevant .pbit file in Power BI Desktop
* For Jira:
  - Add your Jira URL
  - Add your Jira Project Key(s)
* For Azure DevOps:
  - Add your Jira URL
  - Add your Jira Project Key(s)

* It should then look something like this (for Jira):
![alt text](https://raw.githubusercontent.com/nbrown02/FlowViz-Jira/main/Screenshots/Login1.PNG)

* Or this (for Azure DevOps):
![alt text](https://raw.githubusercontent.com/nbrown02/FlowViz-Jira/main/Screenshots/Multiple.jpg)

* Hit 'Load' 
* You will be prompted for a login
* For Jira, choose Basic and enter:
  - Your email associated with your Jira account for your username
  - Your API token you created in the Prerequisities

![alt text](https://raw.githubusercontent.com/nbrown02/FlowViz-Jira/main/Screenshots/Login2.png)

* For Azure DevOps, choose Basic and enter:
  - Your email associated with your Jira account for your username
  - Your API token you created in the Prerequisities

![alt text](https://raw.githubusercontent.com/nbrown02/FlowViz-Jira/main/Screenshots/Login2.png)

* Then hit 'Connect' and wait for the data and charts to load!

### Screenshots and questions to ask using these charts


