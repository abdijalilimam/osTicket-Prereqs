<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This brief tutorial demonstrates the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop (RDP)
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b>

<h2>List of Prerequisites</h2>

- Setup Virtual Machine on Azure
- Download and connect to RDP
- Install osTicket installation files 

<h2>Installation Steps</h2>
<p>
  Welcome to this brief tutorial! We will begin by going to portal.azure.com and creating a virtual machine as seen above and you will name it osTicket. A virtual machine in simple terms is a virtual computer within your physical computer and you can run programs on that virtual computer and manipulate it. We use VMs in order to run multiple operations in one physical computer and to save time and cost as well. Once you have created a virtual machine it should also create a bunch of stuff with it like a Resource Group (RG).
</p>
<p>
  <img width="1433" alt="image" src="https://github.com/abdijalilimam/osticket-prereqs/assets/137457871/d37eb18c-3970-47be-82d5-ef6cea31e51f">
</p>
<br />
<p>
Next, connect to your RDP I am using a Mac so I downloaded the Microsoft Remote Desktop app from the Apple Play and connected the osTicket VM we created earlier using the public IPv4 address).
</p>
<p>
  <img width="869" alt="image" src="https://github.com/abdijalilimam/osticket-prereqs/assets/137457871/898321ad-bf4f-41ee-a063-6f2f568ff8ab">
</p>

<br />
<p>
  Next, look up the control panel in the start menu and click on "programs" and under programs click on "Turn Window Features on or off" Then you will be able to enable internet information services as you see above.
</p>
<p>
<img width="1158" alt="image" src="https://github.com/abdijalilimam/osticket-prereqs/assets/137457871/f03a70ae-6243-49e9-9803-cef8ee6c4fb7">
</p>
<p>
  

   <p> Download and install MySQL and   Use this link https://drive.google.com/drive/u/0/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6 to install all the files required for the installation. 
</p>
<p>
  <img width="1137" alt="image" src="https://github.com/abdijalilimam/osticket-prereqs/assets/137457871/58ff3e3a-f1b8-4e92-bf72-c2d070ca2ede"> </p>

 <p>
  <img width="1141" alt="image" src="https://github.com/abdijalilimam/osticket-prereqs/assets/137457871/6bae95da-aa3f-449c-b729-fe12781c2122">
</p>

<p>
  Register new PHP
</p>

<p>
  <img width="1148" alt="image" src="https://github.com/abdijalilimam/osticket-prereqs/assets/137457871/0e9e5f82-2039-4b9d-9f8d-0acbd2c2ac8d">

</p>

<p>
  We will download osTicket the extract and copy the "upload" folder into wwwroot. then, rename the folder to osTicket
</p>

</p>
<img width="1156" alt="image" src="https://github.com/abdijalilimam/osticket-prereqs/assets/137457871/3c3b2a56-59e8-4e78-baed-8868291560f5">
</p>

<p>
  After enabling certain features osTicket is now installed Congratulations 
</p>
<p>
 <img width="1155" alt="image" src="https://github.com/abdijalilimam/osticket-prereqs/assets/137457871/8df7d0f5-bb21-4c02-843a-dea74c03182a">

</p>
<br />
