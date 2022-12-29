<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/4z3Uboq.png" height="80%" width="80%" alt=""/>
</p>
<p>
The first step in our Post-install configuration process is to configure Roles. This allows us to add new roles for Agents to determine their level of access and permissions within the department's organization.
</p>
<br />

<p>
<img src="https://i.imgur.com/JiPfjEH.png" height="80%" width="80%" alt=""/>
</p>
<p>
Next, we configure Departments, where we can add new departments or modify the already existing departments. We can then add Agents to the various different departments. Tickets are routed through departments in the help desk, so it is important to have departments organized properly as there are many settings that can be set for each department. 
</p>
<br />

<p>
<img src="https://i.imgur.com/HnTNRX7.png" height="80%" width="80%" alt=""/>
</p>
<p>
While configuring Teams, we can assign Agents from different departments onto one team and organize them to handle specific issues. Teams can also have a team leader who can recieve alerts and notices separate from other team members. 
</p>
<br />
<p>
<img src="https://i.imgur.com/3NNEEdI.png" height="80%" width="80%" alt=""/>
</p>
</br>
<p>
  Agents are the ones who respond to and resolve the tickets. They are assigned to a primary department and given a primary role for the tickets/tasks that are routed to that department. Configuring an Agent's profile is necessary in order for them to be able to work and have access to the appropriate processes. 
</p>
</br>

<p>
<img src="https://i.imgur.com/06n8AJw.png" height="80%" width="80%" alt=""/>
</p>
<p>
  Users are the ones with the issues to be solved. They may need help with a plethora of tasks, such as registering their account, password resets, checking on their tickets, etc. 
</p>
</br>

<p>
<img src="https://i.imgur.com/Wv4P2Qj.png" height="80%" width="80%" alt=""/>
</p>
<p>
  SLA Plans, or Service Level Agreements, differs from company to company, but these are set up to provide the length of time in which the help desk administrator expects tickets to be closed. The SLA plan used on each ticket varies on the severity of the issue and is determined by the Department the ticket is issued to. 
</p>
</br>

<p>
<img src="https://i.imgur.com/176dTW2.png" height="80%" width="80%" alt=""/>
</p>
<p>
  Help Topics help to streamline the end-user's help desk experience and ensures proper assignment and prompt response to the ticket. Help Topics also determine which department the ticket is routed to, which also determines which Agents will have access to the ticket, and can also determine the ticket's SLA and priority level. 
</p>
