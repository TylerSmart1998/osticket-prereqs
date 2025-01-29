<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> 

<h2>List of Prerequisites</h2>

- Install IIS
- Install Rewrite Module
- Install MySQL
- Install C++ 
- Configure Permissions and Install osTicket

<h2>Installation Steps</h2>

<p>


![image](https://github.com/user-attachments/assets/1cd0f3d3-f783-4ce2-8ba2-8748be0ccd18)



</p>
<p>
After downloading the latest verison of osTicket, launch IIS, Go to sites -> Default -> osTicket On the right, click “Browse *:80” Note that some extensions are not enabled. Go back to IIS, sites -> Default -> osTicket, Double-click PHP Manager, Click “Enable or disable an extension” Enable: php_imap.dll Enable: php_intl.dll Enable: php_opcache.dll Refresh the osTicket site in your browser, observe the changes

</p>
<br />

<p>


![image](https://github.com/user-attachments/assets/b741d9cf-3465-4c04-996b-99d3fc23bc95)


</p>
<p>
Rename: ost-config.php From: C:\inetpub\wwwroot\osTicket\include\ost-sampleconfig.php To: C:\inetpub\wwwroot\osTicket\include\ost-config.php Assign Permissions: ost-config.php Disable inheritance -> Remove All New Permissions -> Everyone -> All

</p>
<br />

<p>



![image](https://github.com/user-attachments/assets/d1653bd6-4cfc-478e-a3ff-aa29d0c5ab01)

</p>
<p>
Continue Setting up osTicket in the browser (click Continue) From the “osTicket-Installation-Files” folder, install HeidiSQL. Open Heidi SQL Create a new session, Connect to the session Create a database Continue Setting up osTicket in the browser Click “Install Now!” Congratulations, hopefully it is installed with no errors!
</p>
<br />
