<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This Project outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />




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

<p>
<img src="https://i.imgur.com/lzIeCse.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
</p>
<p>
As an end-user:
When I need to create a ticket, I go to the Agent Panel and submit a new request. I would fill out the form to describe my issue, which in this case is that the accounting department needs an Adobe upgrade but the system is broken. I would provide a brief description of the problem and submit the ticket for assistance.

As a Help Desk Agent (John):
Once the ticket is submitted, I, as a Help Desk Agent, would see the new ticket come through in my queue. The ticket will have the following properties visible to me:

Priority: The priority of the ticket will initially be set according to the user’s description or the system’s default setting, but I can modify it if necessary.
Department: Since this is a support-related issue (the Adobe upgrade), the department assigned to this ticket would be Support.
SLA: Based on the severity of the issue, I will assign an appropriate SLA. Since this isn’t an urgent, critical issue, I will set the SLA to Sev-B (4 hours, 24/7). This means I have up to 4 hours to resolve the issue, and it’s a 24/7 support requirement.
Assigned To: This would initially be unassigned, so I can take responsibility for the ticket and assign it to myself or another agent if needed.
Setting the Properties:
I would adjust the properties of the ticket as follows:

Priority: I would confirm that the priority is correctly set to Sev-B because the Adobe upgrade is important but not urgent enough to warrant a Sev-A.
Department: The Support department is correct, as I’m dealing with a software upgrade issue.
SLA: I would verify that the SLA is Sev-B, with a grace period of 4 hours and the requirement for 24/7 support. This ensures I have a reasonable timeframe to resolve it.
Assigned To: I would assign the ticket to myself, John, since I’m the one handling it.
Working the Ticket to Completion:
To work on the ticket, I would first check the specifics of the Adobe upgrade issue. I might need to get some details from the accounting department to understand the exact software version they’re using and what kind of upgrade is required. Once I have all the information, I would proceed to troubleshoot or escalate the issue if necessary.

During this process, I’d keep the user informed about the progress, update the ticket with any actions taken, and finally mark it as resolved once the upgrade is complete. I would ensure everything is done within the 4-hour SLA to meet the required timeframe. After resolution, I would verify that the accounting department is satisfied with the upgrade, close the ticket, and update any relevant notes before finalizing it.
</p>
<br />

<p>
<img src="https://i.imgur.com/Kn3Xa8b.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
</p>
<p>
As an End-User:
When I encounter an issue where the CFO’s laptop will no longer turn on, I go to the Agent Panel and create a new ticket. I describe the issue clearly: the CFO’s laptop is not turning on. I might also include any additional details, such as when the issue first occurred, whether the laptop was working previously, or if there were any error messages. After filling out the form, I submit the ticket, which gets sent to the Help Desk team for resolution.

As a Help Desk Agent (John):
Once the ticket is created by the end-user, I, as a Help Desk Agent, will see it in my queue. Here’s what I observe about the ticket’s properties:

Priority: The priority of the ticket is determined by the nature of the issue. In this case, the laptop not turning on is a significant problem, but not immediately catastrophic. The priority will likely be set to Sev-B initially, though I’ll double-check to make sure it’s appropriate.
Department: The Support department is assigned because this is a technical issue related to hardware and needs support.
SLA: The SLA will likely be set based on the severity of the issue. Since the laptop is important for the CFO’s work but not an emergency, I’ll set the SLA to Sev-B (4 hours, 24/7). This means the issue should be resolved within 4 hours, and support is required 24/7.
Assigned To: This ticket will initially be unassigned. Since I’m handling it, I will assign it to myself.
Setting the Properties:
I review and ensure the ticket properties are correctly set:

Priority: I check that the priority is appropriately set to Sev-B since this is important but not the most critical issue.
Department: The Support department is correct for a technical issue with the laptop.
SLA: I confirm that the SLA is set to Sev-B, giving me 4 hours to resolve the issue and support 24/7.
Assigned To: I assign the ticket to myself as John, since I’m responsible for addressing this issue.
Working the Ticket to Completion:
To work on this ticket, I start by gathering all the relevant information. I might contact the user who submitted the ticket to confirm the problem and check if any other troubleshooting steps have been attempted, like checking the power cable or pressing the power button for a long time.

If the laptop still won’t turn on after basic checks, I would begin troubleshooting in more detail. I may need to ask for the laptop’s model, check for any hardware issues, or suggest bringing it in for a physical inspection if necessary.

If the problem is something that can be resolved remotely, such as a software conflict, I’d attempt to fix it using remote tools. Otherwise, I’d escalate it to a specialized technician or arrange for an in-person fix.

Throughout this process, I keep the user informed of my progress and update the ticket with the steps I’ve taken. I would ensure to resolve the issue within the 4-hour SLA and make sure the CFO’s laptop is working properly before closing the ticket. Once resolved, I would mark the ticket as complete, confirm with the user that everything is functioning correctly, and ensure the ticket is closed properly.
</p>
<br />

<p>
<img src="https://i.imgur.com/rSr858U.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To start, I need to set properties for all the tickets. For instance, I set the priority of each ticket as Sev-A (for the most critical ones), except for the SysAdmins ticket, which I set last. Once I set Sev-A, I observe that the ticket becomes inaccessible. This is likely because Sev-A tickets are treated as high-priority and have restrictions for certain roles, like SysAdmins, especially when access is limited to higher-level users.

Switching to Admin Panel:
Next, I go to the Admin Panel to manage access. I assign myself View-access to SysAdmins so that I can view and handle tickets related to that department. This is important to ensure that I have the right permissions to review and manage tickets that might otherwise be restricted.

Observing the Escalated Ticket:
Switching back to the Agent Panel, I can now see the escalated ticket. I observe that because of the settings I applied earlier, I can no longer make changes to it. This indicates that there are some restrictions in place for higher-priority tickets, likely to ensure they are only modified by authorized users or admins.

Solving All of the Tickets:
I would proceed by solving all the tickets that are accessible to me. Since the Sev-A tickets are critical, I would address them first, ensuring I follow the appropriate protocols for escalation or resolution. For the tickets I can access, I would troubleshoot the issue, update the ticket with my actions, and resolve them accordingly.

Email Capability:
In most ticketing systems, and likely this one too, there is an email capability built into the system. Every time I update a ticket, the user automatically receives a copy of the update via email. This means the user is always informed of any progress on their ticket, and they can also respond directly via email to continue the conversation or provide more information. This feature keeps everyone in the loop, which is crucial for communication.
</p>
<br />
