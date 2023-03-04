<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- PHP Manager for IIS
- Rewrite Module
- PHP 7.3.8
- VC_redlist.x86.exe
- MySQL 5.5.62

<h2>Installation Steps</h2>

<p>
<img src="https://imgur.com/NSF6Fki.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/TqRPPdW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Start by loading up your Azure Virtual Machine. Once it is done, Right click the windows button and click run. Once the prompt loads, type 'control' and the control panel should come in. Click programs, then click "turn windows features on and off". Once you find Internet Information Services, click it on then expand. Expand "World Wide Web", then expand "Application Developer". Then finally, look for and click "CGI".
</p>
<br />

<p>
<img src="https://imgur.com/du2o2la.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once all of that is done, Download "PHP Manager" to your Virtual Machine. You can look for said application through google. (PHPManagerForIIS_V1.5.0 msi)
</p>
<br />

<p>
<img src="https://imgur.com/7BoCNnq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, Download the Rewrite Module (rewrite_amd64_en-US msi) and finish the installation setup.
</p>
<br />

<p>
<img src="https://imgur.com/Wy82CoG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>In the file explorer, go into the C: drive ("Windows (C:)) and create a new folder labeled "PHP". Then Download PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86 zip). Once it's done, right click the new download and click extract. Click 'browse other options' and look for the folder you've just created, then click extract.
</p>
<br />

<p>
<img src="https://imgur.com/5YiueEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Next, download Redistribution (VC redistx86.exe) and go through the installation setup. You'll need to create a username and password. Afterwards, check everything and finish the installation.
</p>
<br />

<p>
<img src="https://imgur.com/xbPCeex.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Next, you have to register PHP in IIS. Open IIS in the downloads and click PHP Mananger. Click "register new PHP version". Click the three dots on the right side then go in the PHP folder and look for "php-cgi". Click it, then click ok.
</p>
<br />

<p>
<img src="https://imgur.com/Iyf1knF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Now download 'OsTicket' (osTicket v1.15.8 zip) and extract the upload folder (in the os ticket file you've downloaded) it into c:/inetpub/wwwroot (you can type it into the search bar in the file explorer.) and let it do its thing. (it may take a while.) once finished, rename the file to "OsTicket". Then reload IIS.
</p>
<br />

<p>
<img src="https://imgur.com/EUdmAnA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>To reload the network, Click 'Restart' on the right-hand side of the screen, and wait a bit. Then, to load OsTicket, click 'sites', 'Default web site', then 'OsTicket', and the page should load.
</p>
<br />

<p>
<img src="https://imgur.com/u4TjLj3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>There are a couple more things you'll need to do before it's ready to go. Open PHP manager in the osTicket folder in IIS. Then click 'Enable or disable Extentions'. Look for and click on "php_imap.dll", "php_intl.dll" and "php_opcache.dll". Then refresh OsTicket.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>null
</p>
<br />
