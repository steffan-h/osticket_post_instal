<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Installation Configuration</h1>
This section covers the post-instillation configuration of the open-source help desk ticketing system osTicket.
<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles, Departments, and Teams
- Allow anyone to create tickets
- Configure Agents and Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
  Log into osTicket: <i>http://localhost/osTicket/scp/login.php</i>
</p>
<p>
  Configure Roles through <i>Admin Panel -> Agents -> Roles</i>. Create a role. <br /><br />
  <em>Ex: Supreme Admin</em>
  
![image](https://github.com/steffan-h/osticket_post_instal/assets/146549173/70ce208d-7777-4468-96ed-889b1da7eb12)
</p>
<p>
  Configure Departments through <i>Admin Panel -> Agents -> Departments</i>. Create a department. <br /><br />
  <em>Ex: System Administrators</em>
  
 ![image](https://github.com/steffan-h/osticket_post_instal/assets/146549173/db1427f1-ad76-4333-9c2a-9c0264f6f7a8)
</p>
<p>
  Configure Teams through <i>Admin Panel -> Agents -> Teams</i>. Create a team. <br /><br />
  <em>Ex: Level II Support</em>
  
![image](https://github.com/steffan-h/osticket_post_instal/assets/146549173/46e38f44-e2b1-4e80-a01d-1922a49054d4)
</p>
<p>
  Allow anyone to create tickets by going to <i>Admin Panel -> Settings -> User Settings</i>. Require registration and login to create tickets <br /><br />
</p>
<p>
  Configure Agents through <i>Admin Panel -> Agents -> Add New</i>. Create an agent. <br /><br />
  <em>Ex: Agent 1</em>
  
![image](https://github.com/steffan-h/osticket_post_instal/assets/146549173/db634e5d-b161-493d-a4bd-dd14e0fac675)
</p>
<p>
  Configure Users through <i>Agent Panel -> Users -> Add New</i>. Create a user. <br /><br />
  <em>Ex: User 1</em>
  
![image](https://github.com/steffan-h/osticket_post_instal/assets/146549173/9789a757-9f8e-4396-ad79-eecbedf4ff5b)
</p>
<p>
  Configure SLA through <i>Admin Panel -> Manage -> SLA</i>. Create some SLAs. <br /><br />
  <em>Ex: Sev-A, Grace Period 1 hour, Schedule 24/7</em>
  
![image](https://github.com/steffan-h/osticket_post_instal/assets/146549173/071f0fc7-5df4-48b8-8373-2f2a3daec445)
</p>
<p>
  Configure Help Topics through <i>Admin Panel -> Manage -> Help Topics</i>. Create some Help Topics. <br /><br />
  <em>Ex: Password Reset</em>
  
![image](https://github.com/steffan-h/osticket_post_instal/assets/146549173/0645751c-d329-45d2-8bf2-729b3673d85d)
</p>

<br />
<h2>Test out creating and completing tickets</h2>

<p>
  Log into a user account and create a ticket <br /><br />
  <em>Ex: User 1 creates a ticket saying "customers are unable to access online banking"</em>

![image](https://github.com/steffan-h/osticket_post_instal/assets/146549173/24701b29-6c30-4168-846f-acde1f541d10)
</p>
<p>
  Log into an agent account and view the status, priority, contents, etc. of a ticket. Reply to a ticket and/or mark as complete and view the changes. <br/><br/> 
  <em>Ex: Agent First Last assigns the ticket from User 1 to Agent 1 and replies to User 1</em>

![image](https://github.com/steffan-h/osticket_post_instal/assets/146549173/8e909e93-5317-4acb-b146-fbeaaf8e077f)
</p>
