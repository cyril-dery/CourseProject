# CourseProject

<h1> How to Install and Work on osTicketing System on Azure</h1>
<p align="left">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h2>Project Summary</h2> 
This is a brief walkthrough how to install and use osTicketing System for an organisation.
<h3>First step: Create a Virtual Machine (VM) on Azure. For my case I used Windows 10 Pro.</h3>
<h3>Second Step: Access the VM on through RDP client on your own computer.</h3>
<h3>Third Step: Install all the must-have software before osTicket can work. Before the installation,you need to turn on some features of Windows. You can find them through Control Panel\Programs and Features\Turn Windows Features on or off. Check Internet Informations, World Wide Web Services, CGI and Common HTTP Features. See the picture below</h3>
<p align="left">
<img src="https://i.imgur.com/RsYPw50.png" alt="Window Features"/>
</p>
-Download and Install PHP Manager for ISS 
-downnload and install Rewrite Module
-create a folder in your hardrive C of your computer  and name it 'PHP'. as in (C:\PHP)
-download PHP 7.3.8 and extract its contents into PHP folder.
-Download and install VC_redist.x86.exe
-Download MySQL 5.5.62 and install it as follows:
<p align="left">
  -Choose Typical install option
  <img src="https://i.imgur.com/SEZoDMZ.png" alt="Typical Installation option"/>
</p>
<p align="left">
  Launch after installation
  <img src="https://i.imgur.com/zvzIDYa.png" />
</p>
<p align="left">
  -choosing  Standard configuration

  <img src="https://i.imgur.com/wI0yY2q.png" alt="Standard configuration"/>
</p>
<p align="left">
  -Choose a password for the 'root' name
  <img src="https://i.imgur.com/9RjVJF1.png" alt="choose password"/>
</p>
<p align="left">
  
-Open IIS in Adminnistrator mode and register PHP.
 <img src="https://i.imgur.com/Iez8cnW.png" alt="IIS in Adminnistrator"/>
</p>
<p align="left">

 <img src="https://i.imgur.com/Ko45hhQ.png" alt="IIS Window"/>
</p>
<p align="left">
  
- register PHP.
 <img src="https://i.imgur.com/dJyAp2Q.png" alt="registering PHP"/>
</p>

-IIS Window restart the server at the extreme right side.
-Download and install osTicket 1.15.8
<p align="left">
-Extract and copy the “upload” folder to c:\inetpub\wwwroot
<img  src="https://i.imgur.com/q6cGIVe.png" alt="registering PHP"/>
<img width =600 height=300 src="https://i.imgur.com/Tou7Gfl.png" alt="registering PHP"/>

</p>

-Within c:\inetpub\wwwroot, Rename “upload” to “osTicket”
-Restart the  server in IIS.
-Go sites and click on osTicket on the left side of IIS
-On the  right side of  IIS, click on' browse 80'
-it should this message "Thank you for Choosing osTicket' with a list of extension enabled or not.
-Go back to osTicket on the left of IIS 
-Double click on PHP Manager to enable extensions highlight in osTicket 'Thank you' page
-Refresh osTicket in the browser to see the changes
-Go drive C, inetpub, then wwwroot and open osTicket folder
-Go to Include folder of  osTicket 
-Rename 'ost-sampleconfig.php' to 'ost-config.php'
-Right click 'ost-config.php' and go to Properties, then to Security and click on Advance 
-Disable Inheritance and open access to  'Everyone' to make changes


Demonstration (4 points)
Project must have a thorough demonstration section, illustrating the use of the project.

