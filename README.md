<h1>Introduction to Os-Ticket-Creation-and-Lifecycle</h1>

![servicenow-ticketing-04-the-ticket-life-cycle](https://github.com/G-Code6/osTicket-Ticket-Creation-and-Lifecycle/assets/163748328/a897236f-e9bd-4349-af14-be7a721147ff)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10 / MacOs </b> 

<h2>List of Prerequisites</h2>

- Azure Account: Sign up for Azure if you haven't already.
- Virtual Machine: Create a VM on Azure to host osTicket.
- Web Server: Choose Apache or Nginx. We'll install it on the VM.
- PHP: Install PHP on the VM.
- Database: Decide between MySQL or MariaDB. We'll set it up on the VM too.
- SMTP Server (Optional): Set up an SMTP server for email communication.

<h3>Installation Steps:<h3>

<h3>1. Ticket Creation:</h3> 

- A ticket is created when a user submits a request for support or assistance. This can be done through various channels such as email, web form, or API - Application Programming Interface.

![Screenshot 2024-05-05 at 10 52 20 AM](https://github.com/G-Code6/osTicket-Ticket-Creation-and-Lifecycle/assets/163748328/c7226ad1-884b-411b-96df-141b55373c4f)

![Screenshot 2024-05-05 at 11 09 11 AM](https://github.com/G-Code6/osTicket-Ticket-Creation-and-Lifecycle/assets/163748328/5e7af4c2-d18f-4016-b929-4b7b0cc41134)


<h3>2. Assignment:</h3>

- Once a ticket is created, it must be assigned to an agent or a team responsible for handling such requests. An administrator can do this manually or automatically based on predefined rules or round-robin assignments.

![Screenshot 2024-05-05 at 1 35 27 PM](https://github.com/G-Code6/osTicket-Ticket-Creation-and-Lifecycle/assets/163748328/50e0d90f-ea55-486a-9a27-5ea55d6269ee)


<h3>3.Investigation/Work:</h3>

- The assigned agent or team begins investigating the issue described in the ticket and takes necessary actions to resolve it. This may involve gathering additional information from the user, performing troubleshooting steps, or coordinating with other departments or individuals.


<h3>4.Resolution:</h3>

- After completing the necessary work, the agent provides a resolution to the issue reported in the ticket. This could be a solution to a problem, an answer to a question, or any other form of assistance requested by the user.

<h3>5.Closure:</h3>

Once the ticket is resolved, it is marked as closed. This indicates that the reported issue has been addressed to the user's satisfaction. Depending on the configuration, closure may require confirmation from the user or it may be done solely by the agent.

![Screenshot 2024-05-05 at 2 17 28 PM](https://github.com/G-Code6/osTicket-Ticket-Creation-and-Lifecycle/assets/163748328/29fc1b88-d936-49c8-b687-03996a87023e)

<h3>6.Follow-up (Optional):</h3>

In some cases, it may be necessary to follow up with the user after the ticket has been closed to ensure that the resolution provided is satisfactory and that there are no further issues or questions.

<h3>7.Reopening (Optional):</h3>

If the user is not satisfied with the resolution provided or if the issue reoccurs, they may reopen the ticket, initiating the support process again. This allows for further investigation and resolution of the issue.


