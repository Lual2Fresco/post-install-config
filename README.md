<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial provides a detailed guide for configuring osTicket after installation, ensuring optimal functionality of the open-source help desk ticketing system.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

This repository is a continuation of the previous project, focusing on the configuration of osTicket within a Windows 10 Virtual Machine (VM) to transform it into a practical ticketing system.

<h2>Configuration Steps</h2>

- Step 1: Ensure that you are logged in as an Admin and navigate to the Admin Panel. You can confirm being on the Admin panel if the top right corner displays "Agent Panel," indicating the option to switch to the Agent Panel if needed.
  
- Step 2: Navigate to the Agents tab and click on "Agents." Then, select "Add New Agent." 

- Step 3: From there, you can adjust the access, permissions, and team that the agent falls under. Additionally, you can set the status of their account and reset passwords as needed.

  Below are the images illustrating the process of creating new Agents within osTicket.
<p>
<img src="https://i.imgur.com/hIjfZWo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> <img src="https://imgur.com/tCfTqx9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Accessing features within osTicket follows a consistent process, akin to creating Agents. The key is to navigate to either the Admin or Agent panel, depending on the desired functionality, and locate the relevant tab containing the required section.

- To access Service Level Agreements (SLA), navigate to the Admin Panel. From there, go to the "Manage" tab and select "SLA."

- Once in the SLA section, you can configure each agreement to align with the company's requirements. This includes setting the grace period for issue resolution and adjusting other relevant configurations as needed.
</p>
<br />

<p>
<img src="https://i.imgur.com/CLV90yC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> <img src="https://i.imgur.com/4asFyof.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

  While in the Admin Panel, I also implemented Help Topics and fine-tuned User Settings.
  
  - Help Topics, similar to SLA, can be found under the Manage tab within the Admin Panel.
  
  - To configure User Settings, I navigated to the Settings tab and accessed the Users section.
</p>
<br />

<p>
<img src="https://i.imgur.com/mTg2bFo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> <img src="https://i.imgur.com/sCXIBtU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
</p>
<p>
To create Users, it's necessary to switch from the Admin Panel to the Agent Panel.

  - Once in the User Panel, navigate to the User tab and access the User Directory. Then, select "Add New User" to proceed with creating a new user.
  
  - You can input user information, assign a username, password, and other settings such as email activation or requiring a password change upon first login. 
</p>
<br />

<p>
<img src="https://i.imgur.com/JbHVvOM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> <img src="https://i.imgur.com/pYd3SdH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> <img src="https://i.imgur.com/6JHVy7p.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

  Below is an example of the ticketing workflow:

1. User creates a ticket by submitting their request or issue.
2. Admin receives the ticket and assigns it to an Agent for resolution.
3. Agent addresses the ticket and provides assistance or resolves the issue.
4. Agent then closes the ticket once the matter is resolved.

  This seamless process ensures efficient handling of user inquiries and effective resolution of issues.
</p>
<br />
<p>
<img src="https://imgur.com/0uGu3kB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> <img src="https://imgur.com/GhqEoHf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> <img src="https://imgur.com/XnfIvl3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> <img src="https://imgur.com/NkjrGfe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> <img src="https://imgur.com/yztjxfl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> <img src="https://imgur.com/ZORWlkM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> <img src="https://imgur.com/cpw5bcC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
