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

<h2>Prerequisites</h2>

- Create tickets using the user accounts made in the [osTicket Configuration Post Installation tutorial](https://github.com/CSanders000/post-install-config)

<h2>Lifecycle Stages</h2>

<p>
<img src=https://github.com/CSanders000/ticket-lifecycle/assets/161166823/28bf5e1f-41d5-4272-a6ac-9756855c42d8"/>
</p>
<p>
To start, we will log into osTicket as our System Administrator, Jane. As you can see, we are logged in as Jane and we have the tickets we created as our users Amanda, Ken, and Ryan.
</p>
<br />

<p>
<img src=https://github.com/CSanders000/ticket-lifecycle/assets/161166823/132a155a-3e13-4dd1-acf1-7a886826dada"/>
</p>
<p>
We will first look at Amanda's Ticket. We can see in the ticket thread the details of the ticket. We can also look at the top portion and see things such as the topic, the SLA plan, who the ticket is assigned to, and other helpful information. We can go down the left side to edit things such as the priority (which we deemed to be an emergency as users not being able to pay for their services is an interruption of critical business functions. We sent the ticket to System Administrators since this is urgent and a bit more complex of an issue for our regular support department. We assigned it to Jane (who we are acting as) since she's in the System Administrators department. We also assigned it an SLA plan of Sev-A, indicating the highest severity. We then told Amanda that we would be in contact with our team to resolve this issue as quickly as possible. We can also note that we left the status in the top left as "open" as in this case, we hadn't resolved the ticket.
</p>
<br />

<p>
<img src=https://github.com/CSanders000/ticket-lifecycle/assets/161166823/ad0fda44-19c4-484d-8da6-adc384c6edfe"/>
</p>
<p>
This image shows the lower half of the ticket resolution screen, including who can see the replies to the ticket and where we can write our responses. Here, we can see that we had met with our team to resolve the issue, updated Amanda, and then at the bottom resolved the ticket. 
</p>
<br />

<p>
<img src=https://github.com/CSanders000/ticket-lifecycle/assets/161166823/f83bb6d5-0fe7-4a9c-8afe-119ef6890213"/>
</p>
<p>
Next is a ticket from Ken asking his team will get a hardware refresh. This will be a Sev-C SLA since it's not particularly urgent. We will also hand this one off to John since it can be easily handled by John. We also kept the ticket open since we as Jane are sending it to someone else, and the priority is low.
</p>
<br />

<p>
<img src=https://github.com/CSanders000/ticket-lifecycle/assets/161166823/bf1f9a0f-924c-4df6-8bf9-546d78e76872"/>
</p>
<p>
Here we can see the updates in the ticket thread, as well as the ticket being assigned to John. We then logged in as John and reached out to Ken and provided information about his concerns, and we can see at the bottom of the screen the ticket has been closed with our response. 
</p>
<br />

<p>
<img src=https://github.com/CSanders000/ticket-lifecycle/assets/161166823/b77fd6a8-b889-404a-99aa-6206b425c436"/>
</p>
<p>
Here we can see Ryan's ticket for his issues with Adobe Acrobat Pro on his computer. We can see the help topic is Personal Computer Issues, a Sev-B SLA, we updated the priority level and the reason for the update. We as Jane gave Ryan an update as to what we were doing (in this case we rolled back the update and looked into the reason why there was an issue. We then sent another update informing that the previous update was incompatible with his hardware and that it should be fine to update with the new patch. We also reminded him it was okay to reach out with any concerns and closed the ticket. We can also see that the ticket was left open during the time we were searching for the cause of the issue and closed after we updated Ryan. At the bottom of the screen, it was closed at the same time the second message was sent.
</p>
<br />

<p>
<img src=https://github.com/CSanders000/ticket-lifecycle/assets/161166823/a60bfb9a-0aa3-4d7b-a270-a03e533b3af9"/>
</p>
<p>
Here, we can see that the tickets we created from our three users were all closed and have been moved to the closed tickets sections (Tickets, Closed). 
</p>
<br />

