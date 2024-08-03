
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

- Create Departments, roles, and teams within the ticketing system.
- Create Agents' accounts along with their username and passwords 
- Assign each agent to their department, role, and team. 
- Establish SLAs and help topics. 
  

<h2>Configuration Steps</h2>


(https://github.com/user-attachments/assets/a0545ff0-5045-419e-97d9-ecff3fba1238)

(https://github.com/user-attachments/assets/391b867f-22bf-4369-9e5b-2a2c5e88a6f8)

(https://github.com/user-attachments/assets/c4f24388-9059-4b39-8662-fcc8b24d0f47)




The first step I did was create a role called "Supreme Admin". Essentially, people assigned this role have no limitations when it comes to accessing, editing, assigning, etc. in this ticketing system. Secondly, I created a "System administrators" department. This department will be for all agents that are assigned the "supreme admin" role I created. Lastly, I created two teams; one being called "A team support" and the other being "Level ll suport". Hypothetically, the default team,  "level l support" could be for C tier tickets, "level ll support" could be for B tier tickets, and "A team support" could be for A tier tickets. 
</p>
<br />

<p>
(https://github.com/user-attachments/assets/1f4e209c-cc10-46e5-8237-195a14bd5e8a)

  (https://github.com/user-attachments/assets/e9ac341c-b78e-448f-8542-4463c8385ef1)

<p>
These screenshots show the creation of two agents, Kevin Hart and Will Smith. I set up their OsTicket profiles by setting up their usernames and passwords, along with assigning them to their department, role, and team.  </p>
<br />
<p>
(https://github.com/user-attachments/assets/a6f37234-adce-49c4-801b-3245dfcf39a6)

(https://github.com/user-attachments/assets/abd1c687-c654-4013-8453-488dfbe996fe)


  Lastly, I set up the SLAs and Help topics for this ticketing systems. I implemented SEV A, SEV B, and SEV C so agents can decipher the importance of each ticket and the timeframe the each ticket needs to be resolved in. I also created help topics so it will be easier for end-users select their issues so proper assignment will occur. 
