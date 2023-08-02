# Flow Metrics for Epics & Features (Azure DevOps & Jira)

### What is this report? 
This report will visualize the four flow metrics of Throughput, Cycle Time, Work In Progress and Work Item Age for Feature or Epic work item types

### Why shuld you use it? 
Managing the flow of work is not something limited to just teams. Flow should be proactively managed on a regular cadence at all levels (Story/Feature/Epic) of work.

### When should you use it?
Use this at least weekly to understand the ‘flow’ of work items at Epic or Feature level. Use it to look at what has recently finished, how long those items took, if there is anything to learn from those and if we are seeing the projected value from them. Similarly use it to look at what is in flight right now - if you are limiting work in progress, what items have been in progress the longest and what should you be focusing your attention on finishing.

### Prerequisites
* [Make sure you have the latest version of Power BI Desktop](https://aka.ms/pbiSingleInstaller)
* Download the appropriate template file:
  - [Jira version](https://github.com/nbrown02/Flow-Metrics-Epics-Features/raw/main/Flow%20Metrics%20for%20Epics%20and%20Features%20(Jira).pbit)
  - [Azure DevOps version](https://github.com/nbrown02/Flow-Metrics-Epics-Features/raw/main/Flow%20Metrics%20for%20Epics%20and%20Features%20(Azure%20DevOps).pbit)
* If you are setting this up for Jira then [follow these steps](https://support.atlassian.com/atlassian-account/docs/manage-api-tokens-for-your-atlassian-account/) to setup a Jira API token and note it down (e.g. copy/paste into Notepad)
* If you are setting this up for Azure DevOps then [follow these steps](https://learn.microsoft.com/en-us/azure/devops/organizations/accounts/use-personal-access-tokens-to-authenticate?view=azure-devops&tabs=Windows#create-a-pat) to setup a Personal Access Token (PAT) with full access and note it down (e.g. copy/paste into Notepad)
* Then you're good to get started!

### Connectivity & Data Load
* Open the relevant .pbit file in Power BI Desktop
* For Jira:
  - Add your Jira URL
  - Add your Jira Project Key(s)
* For Azure DevOps:
  - Add your Jira URL
  - Add your Jira Project Key(s)

* It should then look something like this (for Jira):
![alt text](https://raw.githubusercontent.com/nbrown02/Flow-Metrics-Epics-Features/main/Screenshots/1%20-%20Jira.jpg)

* Or this (for Azure DevOps):
![alt text](https://raw.githubusercontent.com/nbrown02/Flow-Metrics-Epics-Features/main/Screenshots/1%20-%20ADO.jpg)

* Hit 'Load' 
* You will be prompted for a login
* For Jira, choose Basic and enter:
  - Your email associated with your Jira account for your username
  - Your API token you created in the Prerequisities

![alt text](https://raw.githubusercontent.com/nbrown02/FlowViz-Jira/main/Screenshots/Login2.png)

* For Azure DevOps, choose Basic and enter:
  - Your Personal Access Token (PAT) to login, entering it in the password field (user can be left as blank - make sure it has 'Read' access to Analytics)

![alt text](https://docs.microsoft.com/en-us/azure/devops/report/powerbi/media/authentication-7.png?view=azure-devops)

* Then hit 'Connect' and wait for the data and charts to load!

### Screenshots and questions to ask using these charts
![alt text](https://raw.githubusercontent.com/nbrown02/Flow-Metrics-Epics-Features/main/Screenshots/Flow1.png)

![alt text](https://raw.githubusercontent.com/nbrown02/Flow-Metrics-Epics-Features/main/Screenshots/TPGuide.png)

![alt text](https://raw.githubusercontent.com/nbrown02/Flow-Metrics-Epics-Features/main/Screenshots/CTGuide.png)

![alt text](https://raw.githubusercontent.com/nbrown02/Flow-Metrics-Epics-Features/main/Screenshots/WIPGuide.png)

![alt text](https://raw.githubusercontent.com/nbrown02/Flow-Metrics-Epics-Features/main/Screenshots/WIAgeGuide.png)

### Feedback
This template is built and maintained by [Nicolas Brown](https://www.nicolasbrown.co.uk/) use [the issues section](https://github.com/nbrown02/Flow-Metrics-Epics-Features/issues) for any bugs you find and [the discussion section](https://github.com/nbrown02/Flow-Metrics-Epics-Features/discussions) for any question, ideas and/or feature requests.
