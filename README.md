<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

![image](https://github.com/user-attachments/assets/bf31ad14-46bb-45e5-b43c-bd0dba15f1ec)

First we need to delete the maintenance department to ensure that tickets don't get auto-assigned to it. Just log into osTicket as an admin user, go to admin panel, to agents and departments, and delete the maintenance department. Now we're going to create a ticket. Using one of the end-users we created, create a ticket indicating that the entire mobile/online banking system is down. We will categorize it under report a problem. While this may not be the most accurate option, it's one that an end user is likely to select.
</p>
<br />

![image](https://github.com/user-attachments/assets/6673cd0f-1ef5-47fa-869c-8ce1acc4ca50)

We're now going to log into osTicket as our help desk agent, John, to take a look at the ticket. But first, we need to make sure that John has the proper access to the tickets. As our admin user, we're going to go to admin panel, agents, and change John's access from view only to all access. We also need to make sure that the online banking team has agents assigned to it so we can assign this ticket to the team. Go to agents, teams, and add Jane to the online banking team. Back to John, we're going to mark it as Sev-A as this issue appears to be pretty serious and urgent. We're going to change the help topic to business critical outage as that is more accurate. We will also assign the ticket to the online banking team.
</p>
<br />

![image](https://github.com/user-attachments/assets/672250b9-5ea9-4e6e-a893-bda11eb4ca08)

<p>
We're now going to log into osTicket as Jane, our Sys Admin who is on the online banking team, and assign the ticket to ourselves. We're going to determine that the issue is related to a recent update and roll it back to solve the problem. We will post in the thread to keep everyone updated.
</p>
<br />

![image](https://github.com/user-attachments/assets/a7b206f3-9d1e-449a-863a-9cef9d7fa988)

<p>
Now that the issue has been resolved, we're going to post in the thread that the issue is fixed and what the next steps are. In this case, rolling back the update, notifying the vendor and waiting for a proper fix. Once we've done that, we can change the status of the ticket to resolved and close it.
</p>
<br />
