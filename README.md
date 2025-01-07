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

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Access the Admin Panel

Open a web browser and navigate to http://localhost/osTicket/scp.
Log in with the admin credentials set during installation.
Configure General Settings

Navigate to Admin Panel > Settings > System.
Update the "Helpdesk Name" and "Default Email Address" to match your organization.
Set Up Email Settings

Go to Admin Panel > Emails > Settings.
Configure email fetching and sending options (IMAP/SMTP).
Add a new email under Emails > Add New Email for ticket notifications.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create Departments

Navigate to Admin Panel > Agents > Departments.
Add departments like Support, IT, or HR to categorize tickets.
Define Help Topics

Go to Admin Panel > Manage > Help Topics.
Add help topics such as "Technical Support" or "Billing Inquiry" to organize tickets.
Configure SLA Plans

Navigate to Admin Panel > Manage > SLA Plans.
Set up response time targets for different ticket priorities.
Add Agents and Assign Roles

Go to Admin Panel > Agents > Add New Agent.
Assign roles (e.g., Admin, Staff) and set permissions for each agent.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Customize Ticket Settings

Navigate to Admin Panel > Settings > Tickets.
Adjust ticket creation rules, auto-responses, and alerts.
Enable Plugins (Optional)

Go to Admin Panel > Manage > Plugins.
Install and configure any desired plugins, like LDAP or Authentication plugins.
Review System Information

Navigate to Admin Panel > Dashboard > Information.
Verify server settings and osTicket version to ensure everything is functioning correctly.
<br />
