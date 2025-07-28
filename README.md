# osTicket---Post-Install-Configuration

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

Before osTicket is fully functioning after installation, it needs to be further configured using the admin interface or panel. Only staff with admin rights can access the admin panel. It essentially comes down to modifying departments, members, agents, hot topics, emails, and system preferences in the post-installation setup. Please be aware that you must use the login and password you set during installation to log in to the post-installation configuration. Thus, in this project, we will...

* Configure Roles
* Create Departments
* Configure Teams
* Configure System Preferences
* Configure Users
* Configure SLAs
* Configure Hot Topics

<h2>Configuration Steps</h2>

<p>
<h3><strong> Log In to osTicket & Configure Roles </strong></h3>
  
![image](https://github.com/user-attachments/assets/dc9d4ca3-3bbb-4cbf-9bcd-1b401607751a)
![image](https://github.com/user-attachments/assets/3aad4832-1ce2-48a3-9655-baed68d4ec64)
![image](https://github.com/user-attachments/assets/96f70941-9faa-4c77-a4f2-3ee32fda9091)
![image](https://github.com/user-attachments/assets/ff0caf5a-b7de-4dd6-b277-ca9f84f6ab8f)
![image](https://github.com/user-attachments/assets/d73f36c8-751f-409e-aa57-d47fbbe9bbaf)
![image](https://github.com/user-attachments/assets/2358c4c1-403c-4d63-8934-3917e5c2e8fa)
![image](https://github.com/user-attachments/assets/33b662bd-9fcb-4129-af34-504b6fe1a883)
![image](https://github.com/user-attachments/assets/41b0ffe8-dd08-4f52-8e14-e6ba61173043)
![image](https://github.com/user-attachments/assets/e99c6771-8d61-4452-8c77-72fe2f680dd1)
![image](https://github.com/user-attachments/assets/48714453-0f63-412c-8827-e378a2a551fa)
![image](https://github.com/user-attachments/assets/48a75909-8ea7-41f9-8b9e-e655c54e4a27)
 
</p>
<p>
  
* Open (http://localhost/osTicket/scp/login.php) in broswer
* Log in
* Locate "Admin Panel" and open
* Locate "Agents" and open
* Locate "Roles" and open
* Locate "Add New Role" and open
* Choose a desired name for role
* Click "Permissions" tab
* Under "Tickets" "Tasks" & "Knowledgebase" check all boxes
* After all boxes are checked, click "Add Role"

  
</p>
<br />
<h3><strong> Configure Departments </strong></h3>
<p>
  
![image](https://github.com/user-attachments/assets/f37dc7be-3f16-49d3-993a-c840d5792484)
![image](https://github.com/user-attachments/assets/ec71e4bf-a2d4-4c06-8ffc-773d7488570a)
![image](https://github.com/user-attachments/assets/9fcb7fb3-abcf-4d8a-86f9-f5c71fbc8c00)

</p>
<p>
  
* Under the "Agents" tab, locate "Departments" and open
* Locate "Add New Department" and open
* Fill form with the applicable information 
* Click "Create Department"

<br />
<h3><strong> Configure Teams </strong></h3>
<p>
</p>

![image](https://github.com/user-attachments/assets/5163c556-699a-40fe-9e59-ebb084dd2b33)
![image](https://github.com/user-attachments/assets/f3339da7-1329-4d7d-8326-7283f9ce7bcc)
![image](https://github.com/user-attachments/assets/2f1af984-169a-4c6b-a5ca-1216e404a224)
![image](https://github.com/user-attachments/assets/b2008e63-5c73-44fa-9f2a-fb951081b8a5)


<p>

* Under the "Agents" tab, locate "Teams" and open
* Locate "Add New Team" and open
* Fill form with the applicable information 
* Click "Create Team"
</p>
<br />

<h3><strong> Configure User Settings </strong></h3>

![image](https://github.com/user-attachments/assets/e1bc6480-59aa-4b70-a230-f903deb9e002)
![image](https://github.com/user-attachments/assets/4b18c3bf-889f-4e24-82da-16ede3ded6f3)
![image](https://github.com/user-attachments/assets/28c3e677-5774-47fe-91b7-2ab045835125)
![image](https://github.com/user-attachments/assets/13e2e777-cb9c-4f47-bef1-5bc65dffd22b)

* Under the "Settings" tab, locate "Users" and open
* Under the "Authentication Settings" segment, locate "Registration Required"
* Make sure the "Require registration and login to create tickets" box is unchecked
* Click "Save Changes"

<h3><strong> Configure Agents </strong></h3>

![image](https://github.com/user-attachments/assets/7a8fd167-6f0e-4d3c-a38c-ae45acda9522)
![image](https://github.com/user-attachments/assets/05e8df3e-0bda-41b2-8be6-74b33cf432d6)
![image](https://github.com/user-attachments/assets/7a03fd54-5106-4621-9b25-2f9cdc65944b)
![image](https://github.com/user-attachments/assets/e9d2fd27-340b-4b88-9a35-3d5cd649ea4a)
![image](https://github.com/user-attachments/assets/b401b45f-faaa-47bc-83a7-1a7dafb580d9)
![image](https://github.com/user-attachments/assets/a19bb763-4f8b-40d6-b5ce-91ae687d756b)
![image](https://github.com/user-attachments/assets/a6b889f4-9d1a-49ce-aa94-e0ade2ec5c23)
![image](https://github.com/user-attachments/assets/8253700c-5dba-4da8-8aa9-872e1a57915f)

![image](https://github.com/user-attachments/assets/dd5a8e56-2f13-4d9b-b05f-d3b8ed9e4749)
![image](https://github.com/user-attachments/assets/2d16a6ca-792c-4b82-8f58-58bcf270827f)
![image](https://github.com/user-attachments/assets/6c7745a0-a29a-4a51-a5fd-3e78ce7e18e4)


* Under "Agents" tab, locate "Add New Agent" and open
* Under "Account" tab, fill form with the applicable information and set password
* Under "Access" tab, locate Primary Depart Segment
* Choose applicable options for both "Select Department" and "Select Role"
* Under "Teams" tab, choose applicable option for "Select Team"
* Click "Create"
* (Follow the same steps for following agent additions)


<h3><strong> Configure Users </strong></h3>

![image](https://github.com/user-attachments/assets/6d1b67a8-b2ed-41a6-94da-5757b5374e62)
![image](https://github.com/user-attachments/assets/88ab51af-7a21-4da0-9bef-42c0c0135e81)
![image](https://github.com/user-attachments/assets/be3c95e2-c4a5-4bba-ba04-ac47072a4303)
![image](https://github.com/user-attachments/assets/65eeda0f-edcd-43ca-a786-140cef8260d9)
![image](https://github.com/user-attachments/assets/a3582b05-6887-4936-81dd-3dcafeb31d57)

* Click "Agent Panel"
* Under "Users" tab, locate "Add User" and open
* Fill form with the applicable information
* Click "Add User"


<h3><strong> Configure SLAs </strong></h3>

![image](https://github.com/user-attachments/assets/cdbc0deb-7e74-4f92-8a71-15048090517d)
![image](https://github.com/user-attachments/assets/ac37c200-b8d6-4ee3-a611-364d1c292b72)
![image](https://github.com/user-attachments/assets/283dbe4c-6293-4f51-aaa1-a0ebbdd8103c)
![image](https://github.com/user-attachments/assets/92895957-9a0e-4fff-aa17-10561232a429)
![image](https://github.com/user-attachments/assets/dd74ed28-b73c-4470-9845-3d525ce51721)
![image](https://github.com/user-attachments/assets/e1031ed6-c590-4cc6-a168-6f267e3d38bb)
![image](https://github.com/user-attachments/assets/39ca3290-2e71-4554-bd44-b461e4e77c0f)
![image](https://github.com/user-attachments/assets/e02ffbd6-2089-477a-b01b-3dbcc4e7e233)
![image](https://github.com/user-attachments/assets/8fde43cc-1ebe-47e5-81b2-e09bd0c52864)


* Click "Admin Panel"
* Under "Manage" tab, locate "SLA" and open
* Locate "Add New SLA Plan"
* Fill form with the applicable information
* Click "Add Plan"
* (Follow the same steps for following SLA additions)


<h3><strong> Configure Help Topics </strong></h3>

![image](https://github.com/user-attachments/assets/5761019c-5cce-4070-986d-5a4ea8c65853)
![image](https://github.com/user-attachments/assets/027a4a5e-c5fa-48da-a711-4fc63d27cb70)
![image](https://github.com/user-attachments/assets/7dd47a2d-6aec-4e6d-82cb-2c0f0fd58088)
![image](https://github.com/user-attachments/assets/e2456e5f-9165-41ae-9cf3-0b6d6b81515f)
![image](https://github.com/user-attachments/assets/49c3583f-2be6-4ebb-aefc-62d3c577ff05)
![image](https://github.com/user-attachments/assets/5f71b226-3d32-46a8-a484-c8f17c80da45)
![image](https://github.com/user-attachments/assets/75bc9495-dbc2-419d-8dad-b4880293b42d)
![image](https://github.com/user-attachments/assets/377109b3-0b35-416e-a1cb-fd2634840f7d)
![image](https://github.com/user-attachments/assets/d214f316-de7d-42b6-b755-4114325fe859)
![image](https://github.com/user-attachments/assets/50da7bf5-3b77-4229-b634-b26d78805b0b)
![image](https://github.com/user-attachments/assets/a90247f6-e553-411c-bc74-d1102c208d54)
![image](https://github.com/user-attachments/assets/7ebe4c93-2f9f-4696-a08a-c6a143549b09)

* Click "Admin Panel"
* Under "Manage" tab, locate "Help Topics" and open
* Locate "Add New Help Topic"
* Fill form with the applicable information
* Click "Add Topic"
* (Follow the same steps for following Help Topic additions)











