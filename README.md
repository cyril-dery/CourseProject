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
  




Project must have a summary section, that outlines and discusses the following:
Brief description of what the project is (tutorial, walkthrough, technology implementation, etc.)
Languages used, if any (PowerShell, etc.)
Environments used, if any (Azure, Windows 10, Windows Server, etc.)
Technology/Applications/Services used if any (osTicket, Azure Storage, Azure Virtual Machines)

Media (Images and/or Video) (3 points)
Project must contain an appropriate amount of images and/or video, demonstrating the implementation

Demonstration (4 points)
Project must have a thorough demonstration section, illustrating the use of the project.

