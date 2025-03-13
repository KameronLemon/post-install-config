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

![image](https://github.com/user-attachments/assets/504fdaae-247d-4fce-ac7f-0009beabd5db)

![image](https://github.com/user-attachments/assets/c3118ead-4d3d-439a-a4e5-f1e78fee1425)


</p>
<p>
In Admin Panel -> Agents -> Add New create two new agents (Jane in Sysadmins and John in Support)
</p>
<br />

![image](https://github.com/user-attachments/assets/dcca9592-20fa-4ae1-b2f6-2805034f5ac7)

</p>
<p>
In Agent Panel -> Users -> Add New Create a new user.
</p>
<br />

![image](https://github.com/user-attachments/assets/8c9b174a-e7dc-4cee-a7b1-5e017cab2857)

![image](https://github.com/user-attachments/assets/342813a8-191b-4d38-8775-471b683c1bbe)

</p>
<p>
In Admin Panel -> Manage -> SLA and Create a few service level agreements with varying levels of severity.
</p>
<br />

![image](https://github.com/user-attachments/assets/58a93abd-e26e-4e44-83a5-83d83d550dab)

![image](https://github.com/user-attachments/assets/29996e09-0da2-43e3-9f98-d7da30c97758)

</p>
<p>
In Admin Panel -> Manage -> Help Topics and create brand new help topics for inquiry.
</p>
<br />

![image](https://github.com/user-attachments/assets/21204415-a6ef-4031-afcd-05e55966a1ca)

Congratulations! you have Succesfully setup osTicket for user support! If you need help feel free to reach out to me via linkedin!






