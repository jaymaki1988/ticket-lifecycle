# ticket-lifecycle
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com)

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
<img src="https://i.imgur.com/5Fg3AVt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this demonstration, we will be acting as a help desk professional. We are going to use rescources to role play a help desk professional. We are going to start off by going to http://localhost/osTicket. We will create a few tickets. You are going to enter the name of the user and their email. We have the help topics we made previously to help idetify what is going on. Create a few tickets from the users we made in the past demo.
</p>
<br />


- Business Critical: The entire mobile banking is down.
- Personal Computer Issue: Entire accounting department Adobe Reader is down
- Inquiry: Wondering when getting upgraded to new Hardware. Team members tablets and computers getting slow
</p>

We will be using a Business critical outage topic, Personal Computer issues, and a general inquery. That way we have a range of issues in which to triage. In the Admin panel, click on the "Agents" tab and under the "Agents" tab click on "Jane Doe". Click on the "Access" tab and under the extended access select "Support" under the drop down and then select "Supreme Admin" from the drop down. On the osTicket admin screen, hit the "Log Out" button on the top right. That will log us out so we can log in as Jane Doe to look at the tickets. 
</p>
<br />

<p>
<img src="https://i.imgur.com/dEsuSfp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once we log in with Jane, we will see the tickets we created as the user. Start by clicking the "entire mobile banking is down" ticket. From ther we can click on the "Normal" under priority. This is a business impacting event and should not be under Normal. Select "Emergency" and note that this is a bisiness impacting event and save. Then assign the ticket to Jane. Select the SLA Plan and change it to SEV-A and notate that this is a business impacting event. Change the department on the ticket to "System Administrators" and note that Sys Admins responsible for mobile banking infrastructure.
</p>
<br />

<p>
<img src="https://i.imgur.com/4MIpK9P.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Notice at the bottom that it is showing us updates that Jane has been making. The key to this is that if someone else gets assigned to it, they can read to see whats been going on. Post a response from Jane and say "Coordinating with Sys Admin team to bring mobile banking back online". As you post it, you will see it pop up in the Ticket Thread.
</p>
<br />

<p>
<img src="https://i.imgur.com/mj2pxFa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
When we go back to the ticket screen, we will see that the ticket is assigned to Jane Doe and marked as Emergency. Click back in the ticket and post a comment to the Ticket Thread "Steven from System Engineering found and corrected a failed load balancer. Mobile Banking should be back online". Under the Ticket status, select "Resolved" and select the "Post Reply" button. Now go back to the Tickets tab and notice that the ticket is no longer their. If you click on the "Closed" tab, you will see the resolved ticket.
</p>
<br />

<p>
<img src="https://i.imgur.com/8z2Y9s2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now go back to the Tickets screen and click on the "Entire Account Dept Adobe Reader" ticket. Set the Priority to High since it's the Accounting Department and Assign the ticket to John Doe. Change the SLA to SEV-B since it should be a priority. Post a comment on the Ticket Thread about "Reassigned to John and set SLA to SEV-B. Reached out to John for a warm handoff". Click on Post Reply. Notice that the ticket has now been assigned to John. When we go back into the Ticket Tab, we will also see that it is assigned to John Doe.
</p>
<br />

<p>
<img src="https://i.imgur.com/tpcbXpm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Finally click on the last Ticket about the hardware reset. Set the priority to low and change the SLA to SEV-C. We will assign it to Jane Doe pretending that she is aware of the new hardware. Post a comment on the Thread "Hardware refresh is slated for Q1. If you like, you and your dept can start testing newer units today.Please shoot me an email." Resolve the ticket and notice we still have another ticket from John. We will log out from Jane and log back in with John.
<br />

<p>
<img src="https://i.imgur.com/zra4X35.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
As we log in with John, notice the ticket assigned to him and click on the ticket. John can now see the info regarding the ticket and can see the comments that Jane has posted about the ticket. Comment " Rolled back version of Adobe Reader. Accounting is back up and running. Will research why the new version doesn't work on the accounting departments hardware". Change Ticket status to resolved and post the note. As you will tell, John does not have the permissions to do it. We will have to log in as the admin to give John permission. 
</p>
<br />

<p>
<img src="https://i.imgur.com/nmq4tlM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Log out of John and log in with user_admin. In the Admin Panel, Click on the "Agents" tab and select the "Departments" tab. Click on support. Click on the "Access" tab and change John's View Only to Supreme Admin so we can close the ticket. Log out of user_admin and log back in with John. Click on the ticket. Post a new reply "Figured out the problem, re-upgraded everyone and now everything is working". Change Ticket status to "Resolved" and Post reply.
</p>
<br />

