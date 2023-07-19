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
- Resolution

<h2>Lifecycle Stages</h2>

<h3>Intake</h3>
<p>
To create a new ticket, go to the <a href="http://localhost/osTicket">Support Center</a>.
<br>Click "Open a New Ticket".
<br>I created the following tickets:
<img src="https://github.com/VTeas2000/ticket-lifecycle/assets/60052902/1799ff97-3ec2-468e-8674-b65fedc5db4e" height="80%" width="80%" alt="Ticket"/>
<img src="https://github.com/VTeas2000/ticket-lifecycle/assets/60052902/7a6ffd60-4ebb-41f3-8419-308e2730bbf5" height="80%" width="80%" alt="Ticket"/>
<img src="https://github.com/VTeas2000/ticket-lifecycle/assets/60052902/ecec2d80-8152-455f-bc72-ea122d7cd78e" height="80%" width="80%" alt="Ticket"/>
</p>

<h3>Assignment and Communication</h3>
<p>
Log in at <a href="http://localhost/osTicket/scp/login.php">osTicket :: Agent Login</a> as the agent you created during the post-install configuration.
<br>You should see the tickets you created as the user.
<img src="https://github.com/VTeas2000/ticket-lifecycle/assets/60052902/0e811817-3dcf-4371-b31d-dbab71e5bdc8" height="80%" width="80%" alt="Open Tickets"/>
<br>I updated the priority, department, SLA plan, and who the ticket was assigned to for the following ticket:
<img src="https://github.com/VTeas2000/ticket-lifecycle/assets/60052902/95162896-b118-4994-9144-911f91605af4" height="80%" width="80%" alt="Updating Ticket"/>
<br>Having the agent respond to the ticket:
<img src="https://github.com/VTeas2000/ticket-lifecycle/assets/60052902/845629fe-4810-4694-8147-146553c983c4" height="80%" width="80%" alt="Ticket Response"/>
<img src="https://github.com/VTeas2000/ticket-lifecycle/assets/60052902/ae278349-dad9-4e55-a703-c6e973948497" height="80%" width="80%" alt="Ticket Response"/>


<h3>Resolution</h3>
<p>
Resolving the ticket and setting the ticket status to "resolved".
<img src="https://github.com/VTeas2000/ticket-lifecycle/assets/60052902/00250305-9481-4381-9d05-62cda8b2bf89" height="80%" width="80%" alt="Ticket Resolution"/>
<br>The resolved ticket should automatically be removed from the open tickets. It can be found in the closed tickets section.
</p>
