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

- Configure osTicket to create realistic help desk ticketing system environment for both administators and users
- Gain understanding of ticketing system components such as Ticket Properties, SLAs, Departments, Permissions, and Users

<h2>Configuration Steps</h2>

<p>
Once successfully logged into osTicket Admin Panel, navigate to Agents/Roles.
</p>
<br />

![image](https://github.com/yohan-perera/post-install-config/assets/156178441/ec7ee8de-d817-41db-beae-9a24e1dec34a)


<p>
Add new role called ‘Supreme Admin’ and give all permissions, complete access to manage platform.
</p>
<br />

![image](https://github.com/yohan-perera/post-install-config/assets/156178441/85ac3e49-7dfc-4b43-a563-30dccd699ffc)
![image](https://github.com/yohan-perera/post-install-config/assets/156178441/a9e5a2e4-d6b7-4263-a663-bef7ea9754d7)

<p>
Navigate to Agents/Departments, then create new department called ‘System Administrators’.
</p>
<br />

![image](https://github.com/yohan-perera/post-install-config/assets/156178441/6c0a3528-8406-4782-83b3-845cac683809)
![image](https://github.com/yohan-perera/post-install-config/assets/156178441/778cadf4-e3aa-4065-a9ca-eea65eebf624)

<p>
Navigate to Agents/Teams, then create new team called ‘Level II Support’.
</p>
<br />

![image](https://github.com/yohan-perera/post-install-config/assets/156178441/127f54ff-5f52-4692-8991-cc098d71b1aa)
![image](https://github.com/yohan-perera/post-install-config/assets/156178441/37330f6d-26a5-49fe-b075-df10205ccf38)

<p>
Navigate to Settings/Users and ensure that ‘Require registration and login to create ticket’ is not checked which will allow any user to create tickets, even if they are anonymous and not registered.
</p>
<br />

![image](https://github.com/yohan-perera/post-install-config/assets/156178441/104ce658-4c1e-4f50-8af3-0b2094e71a1b)

<p>
Navigate to top ‘Agents’ section and and fill in details for new agents as per the following examples.
</p>
<br />

![image](https://github.com/yohan-perera/post-install-config/assets/156178441/6e8a1b16-60a6-4299-99e6-613a22847dd3)
![image](https://github.com/yohan-perera/post-install-config/assets/156178441/bd66244f-a693-4b8e-8244-0343861e5314)
![image](https://github.com/yohan-perera/post-install-config/assets/156178441/e1faec6b-7365-44ed-9de5-5f72576e4a7a)

<p>
Switch to ‘Agent Panel’, navigate to ‘Users’, and create users as per the following examples.
</p>
<br />

![image](https://github.com/yohan-perera/post-install-config/assets/156178441/ca938f6c-4542-44cd-afaa-5626ce42e659)
![image](https://github.com/yohan-perera/post-install-config/assets/156178441/2b204da2-0c6a-41bb-b272-1097402fd3db)
![image](https://github.com/yohan-perera/post-install-config/assets/156178441/6a147319-93d5-4d97-9c64-de05748112a5)

<p>
Switch to ‘Admin Panel’, navigate to ‘Manage/SLA’ and add SLA plans as per the following examples.
</p>
<br />

![image](https://github.com/yohan-perera/post-install-config/assets/156178441/277bf546-2420-4d63-aeb3-81bf3e16636c)
![image](https://github.com/yohan-perera/post-install-config/assets/156178441/4d6d5808-8229-4e98-a8ba-7f2bd9820e0b)
![image](https://github.com/yohan-perera/post-install-config/assets/156178441/18dde732-6d3b-4e19-b79f-7a6631098c5c)
![image](https://github.com/yohan-perera/post-install-config/assets/156178441/3bbf4dec-5c2c-480f-a397-4e9449f54f1b)

<p>
Navigate to ‘Manage/Help Topics’ and add help topic information as per the following examples.
</p>
<br />

![image](https://github.com/yohan-perera/post-install-config/assets/156178441/40bf8e3f-e684-4b70-b624-544cf8600e02)
![image](https://github.com/yohan-perera/post-install-config/assets/156178441/d06846c1-044e-4d65-b9e7-c9a29cc3f348)
![image](https://github.com/yohan-perera/post-install-config/assets/156178441/aaedcac7-52ed-46aa-8779-35941eb46298)
![image](https://github.com/yohan-perera/post-install-config/assets/156178441/94d370c4-0e7a-49f0-ba64-bf0b52b3a805)
![image](https://github.com/yohan-perera/post-install-config/assets/156178441/cd55d5ce-5747-4608-bbff-ca1de4377980)
