# AI-Workflow-Automation

 <h2>Description</h2>
In this AI driven project, I have explored the use of Tines, a workflow automation platform, to better understand how routine proccesses within cybersecurity can be streamlined through automation. The project involved using Elastic SIEM to generate security alerts, which were then automatically ingested by Tines. Tines then processed and evaluated the alerts, ultimately triggering an email notification.
<br />

<h2>Project walk-through:</h2>

<p align="center">
Load a VM and download elastic SIEM. In this case I have used AWS to create a windows VM : <br/>

![image alt](https://github.com/Samuel-James971/AI-Workflow-Automation/blob/main/Screenshot%202025-07-09%20094109.pdf.png?raw=true)
<br />
<br />
Setting up Elastic SIEM on the VM allows for log data to be injested into elastic SIEM, this can be achieved through installing an endpoint detection agent, in this case, elastic defend. This provides security monitioring for the VM:  <br/>
![image alt](https://github.com/Samuel-James971/AI-Workflow-Automation/blob/main/Screenshot%202025-07-08%20141747.png?raw=true)
<br />
<br />
Here a workflow automation is setup using Times, involving a webhook, AI and email: <br/>
![image alt](https://github.com/Samuel-James971/AI-Workflow-Automation/blob/main/Screenshot%202025-07-08%20142236.png?raw=true)
<br />
<br />
A webhook can be used to intergrate with Elastic SIEM by enabling external notifications when specific events occur. For example, by creating a new detection rule in Elastic SIEM that matches event.code:"4672, which corresponds to a log event for administator login, an alert can be triggered:   <br/>
![image alt](https://github.com/Samuel-James971/AI-Workflow-Automation/blob/main/Screenshot%202025-07-08%20161240.png?raw=true)
<br />
<br />
The workflow automation use an AI action to summarise the incoming webhook alert into a concise sentence and genrate bullet points for analysts. the AI proccesses the alert using a prompt and passes the output to an email action which send an email alert to the analsyt.:  <br/>
![image alt](https://github.com/Samuel-James971/AI-Workflow-Automation/blob/main/Screenshot%202025-07-08%20161240.png?raw=true)
<br />
<br />
Here is the email alert sent to the analyst:  <br/>
![image alt](https://github.com/Samuel-James971/AI-Workflow-Automation/blob/main/Screenshot%202025-07-08%20161352.png?raw=true)
<br />
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
