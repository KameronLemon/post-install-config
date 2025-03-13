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

- Configure Roles for Grouping Permissions
- Congifure Departments for Ticket Visibility
- Configure Teams to Assign Agents from Multiple Departments
- Configure Ticket Service Level Agreement
- Configure Help Topics for When Users Creating a Ticket

<h2>Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/34958153-6b84-4875-b0cb-e503e10f8a07)

![image](https://github.com/user-attachments/assets/f281c635-62e1-4efa-84b8-9349935c07fd)

![image](https://github.com/user-attachments/assets/f07f00ef-44e8-473a-9b2b-949bc7667460)



</p>
<p>
In Admin Panel -> Agents -> Roles create a role that has access to all permissions.
</p>
<br />

![image](https://github.com/user-attachments/assets/de12c7ea-6c22-4da7-972f-4b803f074ff5)


</p>
<p>
Create a brand new top level department in Admin Panel -> Agents -> Departments titled "sysadmins"
</p>
<br />


![image](https://github.com/user-attachments/assets/3d982755-63fd-49ff-947d-e48cd80e9461)

</p>
<p>
Create a brand new team from Admin Panel -> Agents -> Teams titled "Online Banking".
</p>
<br />

![image](https://github.com/user-attachments/assets/63bec4f4-82ed-409b-bcfe-953690fe3482)

</p>
<p>
Allow any enduser to create tickets by going to Admin Panel -> Settings -> User Settings and Unchecking "Require Login and Registration to Create Tickets"
</p>
<br />

