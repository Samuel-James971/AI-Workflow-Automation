# AI-Workflow-Automation

 <h2>Description</h2>
In this AI driven project, I have explored the use of Tines, a workflow automation platform, to better understand how routine proccesses within cybersecurity can be streamlined through automation. The project involved using Elastic SIEM to generate security alerts, which were then automatically ingested by Tines. Tines then processed and evaluated the alerts, ultimately triggering an email notification.
<br />

<h2>Program walk-through:</h2>

<p align="center">
Load a VM and download elastic SIEM. In this case I have used AWS to create a windows VM : <br/>

![image alt](https://github.com/Samuel-James971/AI-Workflow-Automation/blob/main/Screenshot%202025-07-09%20094109.pdf.png?raw=true)
<br />
<br />
Setting up Elastic SIEM on the VM allows for log data to be injested into elastic SIEM, this can be achieved through installing an endpoint detection agent, in this case, elastic defend. This provides security monitioring for the VM.:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
