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
<p>-Download and Install PHP Manager for ISS <p/>
<p>-downnload and install Rewrite Module<p/>
<p>-create a folder in your hardrive C of your computer  and name it 'PHP'. as in (C:\PHP)<p/>
<p>-download PHP 7.3.8 and extract its contents into PHP folder.<p/>
<p>-Download and install VC_redist.x86.exe<p/>
<p>-Download MySQL 5.5.62 and install it as follows:<p/>

<p> -Choose Typical install option<p/>
<p><img src="https://i.imgur.com/SEZoDMZ.png" alt="Typical Installation option"/><p/>
</p>

<p>Launch after installation<p/>
  <img src="https://i.imgur.com/zvzIDYa.png" />
</p>
<p align="left">-choosing  Standard configuration</p>

<p><img src="https://i.imgur.com/wI0yY2q.png" alt="Standard configuration"/></p>

<p align="left">-Choose a password for the 'root' name</p>
<p><img align="left" src="https://i.imgur.com/9RjVJF1.png" alt="choose password"><p/>



<p> <img src="https://i.imgur.com/Iez8cnW.png" alt="IIS in Adminnistrator"/> <p/>

<p align="left">
<img src="https://i.imgur.com/Ko45hhQ.png" alt="IIS Window"/>
</p>
<p align="left">
  
- register PHP Manager.
 <img src="https://i.imgur.com/dJyAp2Q.png" alt="registering PHP"/>
</p>

<p>-IIS Window restart the server at the extreme right side.</p>
<p>-Download and install osTicket 1.15.8</p>
<p align="left">
-Extract and copy the “upload” folder to c:\inetpub\wwwroot</p>
<img align="left" src="https://i.imgur.com/q6cGIVe.png" alt="registering PHP"/>
<img width =600 height=300 src="https://i.imgur.com/Tou7Gfl.png" alt="registering PHP"/>



<p>-Within c:\inetpub\wwwroot, Rename “upload” to “osTicket”</p>
<p>-Restart the  server in IIS.</p>
<p>-Go sites and click on osTicket on the left side of IIS</p>
<p>-On the  right side of  IIS, click on' browse 80'</p>
<p>-it should this message "Thank you for Choosing osTicket' with a list of extension enabled or not.</p>
<p>-Go back to osTicket on the left of IIS </p>
<p>-Double click on PHP Manager to enable extensions highlight in osTicket 'Thank you' page</p>
<p>-Refresh osTicket in the browser to see the changes</p>
<p>-Go drive C, inetpub, then wwwroot and open osTicket folder</p>
<p>-Go to Include folder of  osTicket </p>
<p>-Rename 'ost-sampleconfig.php' to 'ost-config.php'</p>
<p>-Right click 'ost-config.php' and go to Properties, then to Security and click on Advance </p>
<p>-Disable Inheritance and open access to  'Everyone' to make changes</p>

<h3>Download and install HeidiSQL.<h3/>
<p>Open Heidi SQL<p/>
<p>Create a new session, and enter password created for 'root'<p/>
<p>Connect to the session<p/>
<p>Create a database called “osTicket”<p/>

Demonstration (4 points)
Project must have a thorough demonstration section, illustrating the use of the project.

