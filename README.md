<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - After Install Setup</h1>
This tutorial outlines the after setup of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration (Still Not Mine)</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)


<h2>Configuration Steps</h2>

<p>
<img src="https://imgur.com/H1YyJG5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/E3ompb3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now that the installation is complete, It's time to set roles for your "employees". Click the 'Agent Panel' on the top left, then click 'Agents', then 'Roles'. Click "Add New Role". Create an Overall Admin for yourself to be your own Manager and grant all permissions. When you're done, hit 'save changes'.
</p>
<br />

<p>
<img src="https://imgur.com/ilwXN16.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, it's time to setup a department. Go back to the admin panel, click on 'agents' again, then click 'departments'. Create your department as "System Administrators", then click "create department".
</p>
<br />

<p>
<img src="https://imgur.com/FnP0ki6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now, let's setup a new team. If you see the team tab already, click it. Otherwise, go to the "Admin Panel", "Agents", then "teams". Create two support teams Like "level I" or "level II" Support teams. Make sure not to check the registration required box, or else any tickets you send to yourself won't go through without another login.
</p>
<br />

<p>
<img src="https://imgur.com/fVMTo3m.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now it's time to add your "agents". Go to 'agent panel', 'settings', then 'teams'. Make up anyone you want to 'work' for you (at least 2), but remember the credentials you give them. You'll need to log into their account once you're done here. Also, make sure to add one of them to you're 'system admins' group in the access tab. There's no need to add a phone number.
</p>
<br />

<p>
<img src="https://imgur.com/SuXTnUm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now, let's create your "customers". Go to the 'agent panel', then 'users', and click 'add new'. Now create your user! 
</p>
<br />

<p>
<img src="https://imgur.com/dbsr0Ni.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, it's time to create the 'SLA' (Service Level Agreement) for each team. Go to the 'Admin Panel',then 'Manage', and click 'SLA'. Add three new SLA's each with different timing on when tickets are expected to be done.
</p>
<br />

<p>
<img src="https://imgur.com/oQzmuIL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lastly, let's create some help topics for 'people' to select. Go to the 'Access Panel', then click 'manage', and 'Help Topics'. Create various topics such as: "Business Critical Outage" or "Password Reset", and make sure they're public for all to see. After you're done with each topic, Click 'Add' to finish!
</p>
<br />


