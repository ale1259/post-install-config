<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket. We are going to add some roles, departments, agents and a coulpe end-users as an example. <br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2
                                         
  - NOTE: All the emails and names is for the example. Ex: karen@osticket.com                                       
  - First we login with your user and password on the link for the helpdesk page http://localhost/osTicket/scp/login.php
   <img src="https://i.imgur.com/pe4GOKK.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
   
  - When you login we need to go to Admin Panel
 <img src="https://i.imgur.com/J5H85v5.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  - Configure Roles: Admin Panel -> Agents -> Roles 

 <img src="https://i.imgur.com/udcb7TJ.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>

- And we are going to add a new Role "Supreme Admin" and we are going to grant it all the permissions
   
  <img src="https://i.imgur.com/hZqzvo4.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/> 

- Configure Departments: Admin Panel -> Agents -> Departments 

 <img src="https://i.imgur.com/M5PH3HD.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 
  -  Let's add a new Department: "System Administrators" you don't need to configure anything else this is just an example
 <img src="https://i.imgur.com/u3svZyc.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>

- Now we need a new team let's add Level II Suport
  <img src="https://i.imgur.com/Au9e0q0.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
  <img src="https://i.imgur.com/9WTCawO.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>

- Now we need to allow anyone to create tickets go to Admin Panel -> Settings -> User Settings
Registration Required: Require registration and login to create tickets it's has to be unchecked
<img src="https://i.imgur.com/z7nSdZW.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>

- Now a couple Agents to add(workers) Admin Panel -> Agents -> Add New: Jane and John and set the password for each one you can use the same so you don't get confused 
 <img src="https://i.imgur.com/OfDUAtl.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src="https://i.imgur.com/EmWThu0.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 
 - When setting the password unchecked "Send the agent a password reset email" and "Require password change at next login"
  <img src="https://i.imgur.com/Ly64p7b.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
 - And let's assign Jane the new Role: "Supreme Admin" and Deparment: "System Administrators" we created and add extended access to "Support" Department, do the same with John but with Department "Support" and Role "All Access"
  <img src="https://i.imgur.com/GIsCdlx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 
 - Next a couple Users(customers) go back to Agent Panel -> Users -> User Directory -> Add New: Karen and Ken
<img src="https://i.imgur.com/HV8Avmm.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>  <img src="https://i.imgur.com/dDeP1Fu.png)" height="60%" width="60%" alt="Disk Sanitization Steps"/> 


- Now baCK to Admin Panel to Configure SLA Admin Panel -> Manage -> SLA  

<img src="https://i.imgur.com/hS9Bmhg.png)" height="60%" width="60%" alt="Disk Sanitization Steps"/> \
- Add New SLA Plan: Sev-A (1 hour, 24/7), Sev-B (4 hours, 24/7), Sev-C (8 hours, business hours)

<img src="https://i.imgur.com/FkIzHbw.png)" height="60%" width="60%" alt="Disk Sanitization Steps"/>

- Sev-A (1 hour, 24/7)
<img src="https://i.imgur.com/EgCVOaY.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>

 - Sev-B (4 hours, 24/7)
<img src="https://i.imgur.com/4kYNjcy.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>

- Sev-C (8 hours, business hours)
<img src="https://i.imgur.com/8knTJ6K.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>

- For the last step let's configure "Help Topics". Go to Admin Panel -> Manage -> Help Topics -> Add New Help Topic
 <img src="https://i.imgur.com/Trpvbm1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

- "Business Critical Outage"
 <img src="https://i.imgur.com/XByWPS4.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>

- And "Personal Computer Issues"
 <img src="https://i.imgur.com/GzTY8eh.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>

- Now we are READY for create, triage and solve some tickets!!! 

  


