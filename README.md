# osticket-prereqs<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />






<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Enable IIS in Windows with CGI
- Enable Microsoft C++
- Enable MySQL
- Enable OS Ticket


<h2>Installation Steps</h2>

<p>

<img src="https://i.imgur.com/jl0F6qn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
For the fist prerequisite in order to enable IIS in Windows with CGI I had to go to the control panel, select programs then turn Windows Feature on or off. After selecting the feature I clicked IIS, expanded World Wide Web Services, expanded Application Development Feature, and then turned on CGI.
</p>
<br />

<p>

<img src="https://i.imgur.com/SQZVlSP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
For the second prerequisite I installed Microsoft C++
</p>
<br />

<p>

<img src="https://i.imgur.com/4hweNC4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
For the third prerequistie I installed MySQL. I had to make sure to choose a Typical setup and once ready I clicked finish. I then had to make some credentials for MySQL so I chose standard configuration and then made a new password for the new user (root).
</p>
<br />

<p>

<img src="https://i.imgur.com/jDckMfu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
For the fourth prerequiste I installled OS Ticket. Before installing I had open IIS as an admin and register PHP from within IIS.I then downloaded OS Ticket, extracted and copied the upload foler to c:\inetpub\wwwroot, then renamed the upload folder to OS Ticket.  
</p>
<br />
