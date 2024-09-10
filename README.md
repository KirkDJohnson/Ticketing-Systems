<h1>Exploring Ticketing Systems</h1>

<br />
<h2>Description</h2>
Here I explore two help desk ticketing systems, Spiceworks's Cloud Help Desk, and Fresh Desk. My goal was to gain some hands-on experience and famailiarity with ticketing systems and the ticket lifecycle. With both systems, I experimented with the settings and functionalities including: creating users, assigning roles, modifying ticket rules, generating tickets manually, by email, and through the configured service portal. means, implementing a FAQ for users to reduce tickets, replying to tickets, and closing tickets. While it seems both ticketing systems are solid, I noticed Cloud Help Desk had easier to navigate and configure settings, however, Fresh Desk allowed for more specific and granual settings which could an advantage depending on the organization. Nonetheless, gaining hands-on experience with two ticketing systems was goal of this repository.

<h2>Utilities Used</h2>

- <b>Spiceworks</b> 
- <b>Fresh Desk</b>


<h2>Lab Overview:</h2>

<p align="center">
The first ticketing system that I will explore is Spiceworks's Cloud Help Desk tool. The ticket viewing page is very clean and there are ample settings within the organization that I can customize.<br/>
<img src="https://github.com/user-attachments/assets/b75aca35-9957-4e22-b102-2727595fb14c" alt="Ticketing Systems"/>
 <img src="https://github.com/user-attachments/assets/9bd54629-8190-4034-a856-b6fb66977a10" alt="Ticketing Systems"/>
<br />
<br />
I first begun by just working my way through the different settings and experimenting with the different tools and functions of the ticketing system such as: creating users, ticket categories, and creating a canned response for helpdesk to input when closing a ticket to improve efficency. <br/>
<img src="https://github.com/user-attachments/assets/1d4ea6f1-0391-4bd4-a107-69e4f57eafc5" alt="Ticketing Systems"/>
 <img src="https://github.com/user-attachments/assets/b925b162-7a29-422e-b571-1c78e49287f1" alt="Ticketing Systems"/>
 <img src="https://github.com/user-attachments/assets/875fe53e-f591-4cfd-b68a-b47f10019ee7" alt="Ticketing Systems"/>
<br />
<br />
A useful setting I discovered was Ticket rules. It allows you to customize how tickets are labled and automatically assign them. For example, I created a rule called Priority Tickets that are created when both conditions are met: categority of ticket is Network, and the Organziation is Homelab. It sets the priority of the ticket to high and assigns it to the network specialist Kirk Johnson. This makes it so Kirk is automatically assigned these network tickets rather than having to sort through the ticket queue or wait for other help desk workers to escalate or assign the tickets to him.<br/>
<img src="https://github.com/user-attachments/assets/3b06b079-68c8-4336-abc4-6e90a567e5d6" alt="Ticketing Systems"/>
<br />
<br />
I now began to test creating tickets in different ways. Within the ticketing system, you (as the admin or a manager) can manually create tickets. This would likely happen if instead of a user creating a ticket through the portal or email, they call help desk or IT support and we fill out a ticket for them. Within the ticket, I input the contact or name of user that the ticket belongs to, the summary, description of the problem, assigned it the manager Mr. Mercury, gave it a priority and category. However, if the user provided screenshots or pictures of the issue, they could have also been included here.<br/>
<img src="https://github.com/user-attachments/assets/e9aaec01-9dd0-4573-adc9-22d0fceb1160" alt="Ticketing Systems"/>
<br />
<br />
Another function of Cloud Help Desk was the article page that is shown next to where a user would submit a ticket. This is useful because if there is an influx of a specific kind of ticket, in my example, I chose that users were sending tickets about their outlook mailbox becoming full preventing them from sending and receiving tickets. I made a user friendly article detailing easy solutions for the users to take without needing to submit a ticket and therefore reducing the number of tickets to help desk and empowering users <br/>
<img src="https://github.com/user-attachments/assets/462fbdb5-3549-443f-9da9-a374eecba406" alt="Ticketing Systems"/>
 <img src="https://github.com/user-attachments/assets/2c38fdff-160a-40b0-bfac-4493e8305562" alt="Ticketing Systems"/>
<br />
<br />
I next created a fake email and emailed "help@kirkshomelab.on.spiceworks.com" to see what it is like to make and receive a ticket from email that simulates a user ticket. It appears that the subject of the email became the ticket name and the contents of the email became the description of the ticket. Also, the ticket appeared, but I could accept or close the ticket meaning it was in a state of limbo. This was not the case when creating a ticket manually, likely to prevent possible phishing attempts or fake tickets. Moreover, within the ticket I added a public note with instructions on how the user can fix the problem and it showed up as a reply in my burner email that sent the ticket.<br/>
<img src="https://github.com/user-attachments/assets/788aa206-9719-4fd4-aab7-649b2ea40699" alt="Ticketing Systems"/>
 <img src="https://github.com/user-attachments/assets/8f9d1a11-226e-4ca9-8591-b79d6196d61d" alt="Ticketing Systems"/>
<br />
<br />
Lastly, within Spiceworks, you can change filter of the tickets to show closed, unassigned, past due, ect. and reopen closed tickets or view the past tickets as a means of a knowledge base for current and future tickets.   <br/>
<img src="https://github.com/user-attachments/assets/4487b355-d807-4c9c-8f5e-935e048e25c4" alt="Ticketing Systems"/>
<br />
<br />
Next I pivoted to the second ticketing system Fresh Desk. Within Fresh Desk, I immediately tried two different means of submitting tickets, one through the online portal and the other from my burner email I made previously. Similar to Spiceworks's Cloud Help Desk, submitting a ticket through the portal allowed for a more precise ticket in reagrd what type of ticket is being submitted, the priority of the ticket and the product. In constrast, emailing the support account also used the subject of the email as the name of the ticket and the description of the email as the description of the ticket.  <br/>
<img src="https://github.com/user-attachments/assets/829ba39a-0751-47ea-8285-7106c67d43c2" alt="Ticketing Systems"/>
 <img src="https://github.com/user-attachments/assets/0eeee570-7c87-46f4-a08b-b59c8fee6087" alt="Ticketing Systems"/>
 <img src="https://github.com/user-attachments/assets/8e2e20f4-3729-4408-a6c7-4c0246f2f407" alt="Ticketing Systems"/>
  <img src="https://github.com/user-attachments/assets/26743381-92f8-4b07-a96b-40ed4605fb36" alt="Ticketing Systems"/>
<br />
<br />
I then began exploring the different settings and functionalities of Fresh Desk as I did with Spiceworks and found much overlap. However, I did find there was additional granularity that Spiceworks did not provide. Though Spiceworks had Ticket Rules that under a condition you could assign a ticket to a specific worker, Fresh Desk takes this even further. An example of this was the ability to create "Skills" where you could have conditional operations that match any or all of them and then assign the skill to a help desk employee which would automatically send tickets that match any or all of configured conditions to them. In my exmaple, any ticket that either has a priority of Urgent, the type is an incident, or if the group of tickets is an escalation, it would fall under the skill of Urgent Tickets. I could then assign the "Skill" of Urgent Tickets to the most skilled or Tier 3 help desk who in the example was Mr. Cobain. This was simialr to Ticket Rules but was more advanced.<br/>
<img src="https://github.com/user-attachments/assets/a4f27f8c-2447-43fe-8c7e-10f473c69939" alt="Ticketing Systems"/>
 <img src="https://github.com/user-attachments/assets/0cbf14eb-db3a-4324-90e8-8a7919f641f1" alt="Ticketing Systems"/>
<br />
<br />
Another similarity was the knowledge base or FAQ that allowed help desk or administrators to post articles next to where users would send tickets in the online portal to curtail an influx of tickets. For example, in this hypothetical, many users were sending tickets regarding slow network performance. However, due to maintence occuring on the servers, this will continue for the next several days. To alert users of this, you could make a temporary article detailing the expected network congestion, and mention if users have no internet connection they should then create a ticket, thus reducing the number of same tickets coming in.<br/>
<img src="https://github.com/user-attachments/assets/f5ca83cb-92f0-4a19-a62c-32dfe806aa7e" alt="Ticketing Systems"/>
 <img src="https://github.com/user-attachments/assets/ad5f8dec-d1ef-4a2b-a64b-e1e827095e43" alt="Ticketing Systems"/>
<br />
<br />
Lastly, a great addition that Fresh Desk includes is the ability to merge tickets. In this example, an upset user sends a ticket about an issue they are facing when they arrived to work. Due to the issue not being resolved immediately, they send another ticket about the same issue. Rather than having two open tickets and possibly two different help desk workers applying the same diagnostics and fixes, you can merge the two tickets, into a single ticket to prevent confusion and resource exhaustion.<br/>
<img src="https://github.com/user-attachments/assets/b5adf64a-4070-4cad-ab29-74a532f3d2e0" alt="Ticketing Systems"/>
 <img src="https://github.com/user-attachments/assets/6da9bd5b-b004-47ee-b827-05e2dce19a4c" alt="Ticketing Systems"/>
<br />
<br />



<h2>Thoughts</h2>
As mentioned earlier and throughout the write-up, both ticketing systems were good in their own right. There was not one that was far superior to the other, however, I am still a novice with ticketing systems. In the configuration settings of  Cloud Help Desk, there was the option of integrating it with Active Directory which I am not sure if Fresh Desk also provides, but that seems like another way to streamline the process of creating tickets for the end user as many of the settings and user identity could be pre-loaded in the ticket. I am sure taht depending on the organization and inflow of tickets would change the circumstances, but it was fun creating and responding to tickets. I am a solid writer and communicator so I feel that I would excell when it comes to responding to tickets with users.
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
