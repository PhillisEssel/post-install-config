<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Roles, Help Topics
- Departments
- Teams, SLA
- Agents
- Users

<h2>Configuration Steps</h2>

<p>
<h3>Phase One</h3>

  ![Step 1](https://github.com/PhillisEssel/post-install-config/assets/156061642/243ae024-939a-45a1-a53a-46d58c6512e7)
<p><a href="https://imgur.com/a/DF93hdk">More</a></p>
</p>
<p>
Login to osTicket as an help desk. Go to Admin Panel>Agents>Roles and configure a role, maye "Supreme Admin." Go to Admin Panel>Agents>Departments and create a Department, maybe "System Administrator." Then go to Admin Panel>Agents>Teams  and configure different levels(teams) within a department, maybe "Level 1/Level 2 Support."
</p>
<br />

<p>
<h3>Phase Two</h3>

  ![Step 14](https://github.com/PhillisEssel/post-install-config/assets/156061642/d61e0ae2-5222-4bce-9a15-497a37398c68)
  
<p><a href="https://imgur.com/a/aqwmlq3">More</a></p>
</p>
<p>
Next enable anyone to create tickets(problems/tech issues). Go to Admin Panel>Settings>Users and require registration and login to create tickets. Then configure Agents (actual workers. these workers are responsible for solving tech issues and will be under a specific department within a team solving different help topics.) Go to Admin Panel>Agents>Add New. Example "Jane/Josh" as the tech problem solvers.
</p>
<br />

<p>
<h3>Phase Three</h3>

  ![Step 26](https://github.com/PhillisEssel/post-install-config/assets/156061642/28377351-4ff2-44a7-b177-e8478957a0e0)

<p><a href="https://imgur.com/a/9R7wrCR">More</a></p>
</p>
<p>
Next Configure some users (customers/employees of third parties that are having tech issues. they will be able to put in requests as tickets for the agents) Go to Admin Panel>Users>Add New. Example "Karen/Ken" as the customers/employees of third parties. Then after configure SLA (limited time to fix a specific issue. Go to Admin Panel>Manage>SLA. Examples of time set ups: SEV-A>1 hour, SEV-B>4 hour, SEV-C8 hour(could be business hours) Lastly configure the Help Topics. Go to Admin Panel>Manage>Help Topic. Examples: Business Critical Outage/Personal Computer Issues/Equipment Request/Password Reset.
</p>
<br />
