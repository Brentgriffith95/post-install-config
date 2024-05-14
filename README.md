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

- Create Roles
- Create Departments
- Create Teams
- Allow Ticket Creation
- Create Agents
- Create Users
- Create SLA
- Create Help Topics


<h2>Configuration Steps</h2>

![WHhLSng - Imgur](https://github.com/Brentgriffith95/post-install-config/assets/150200843/d42f29bc-0449-44da-aca7-707aa4658d99)

To begin this tutorial first login into (http://localhost/osTicket/scp/login.php) in order to login with the admin credentials. It will be the same account as the previous tutorial.


![zlL3xwC - Imgur](https://github.com/Brentgriffith95/post-install-config/assets/150200843/86a413df-cec4-4a41-a179-1330a71e210a)

Click on the admin panel at the top right of the sreen. This will change to the "Agent Panel" when click inside the admin panel.


![VfNQ3r9 - Imgur](https://github.com/Brentgriffith95/post-install-config/assets/150200843/b754992a-0a9d-4b81-abd9-1a6980e5a60b)

Now go to Agents > Roles > Add New Role


![nfj9GZY - Imgur](https://github.com/Brentgriffith95/post-install-config/assets/150200843/4003d9ac-becc-4bc9-84fa-c5c86492f66b)

Name the new role to "Supreme Admin" then click allow all permissions in the next tab. Then click "Add Role"






![jKZmIcJ - Imgur](https://github.com/Brentgriffith95/post-install-config/assets/150200843/22948b85-aade-4cf3-b6e8-7dee27305356)

Click on the "Departments" tab and then click "Add New Department".


![xWDQhF5 - Imgur](https://github.com/Brentgriffith95/post-install-config/assets/150200843/4db23483-1133-43a9-a48d-ec9f62df1710)

We now want to name the department "SysAdmins" and then click "Create Dept".


![rdkk550 - Imgur](https://github.com/Brentgriffith95/post-install-config/assets/150200843/526ced2d-f411-44f0-bcb4-26fe8a88695f)

Then head over to the "Teams" tab and click "Create New Team". We will name this "Level II Support" and click create.




![J6u9Sqw - Imgur](https://github.com/Brentgriffith95/post-install-config/assets/150200843/f585180c-d4b9-4234-b6d5-8d5a2e8450a2)

After creating the new team, now go to "Settings" > Users. Uncheck the box for registration requirement, then make Registration Method public. Finally click Save Changes.




![JomSxnT - Imgur](https://github.com/Brentgriffith95/post-install-config/assets/150200843/9bb2c1f6-b6da-4ad7-bd6c-2b4c1f58f7b2)

Now navigate over to the "Agents" tab and click Add New Agent.


![JPYjAFt - Imgur](https://github.com/Brentgriffith95/post-install-config/assets/150200843/57e9c327-eac1-4a8a-a560-5ef5639164a2)


