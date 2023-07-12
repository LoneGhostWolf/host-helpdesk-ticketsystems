<!--# host-helpdesk-ticketsystems-->

<h1>Installing Peppermint with LinodeVM</h1>
<img src="https://i.imgur.com/uZvIf7z.png" height="65%" width="65%" alt="blank"/>

<h1>Description</h1>
<p>
 In my 2023 IT home lab, I installed Peppermint as a ticketing system and get myself familiar with this tool of how a Helpdesk Technician's work looks like. I learned to create and close a ticket, write a note on the incident case, and add a client to the internal database. Linode is an IT Linux cloud company that offers different Linux distros, such as Ubuntu, Debian, Fedora, and others. I use their service to deploy Ubuntu VM and run the peppermint After researching cloud service companies on the internet search, I find Linode has a friendly and nice GUI interface I recommend for anyone to run a Linux terminal for their IT project. 

During the installation, I opened the LISH console and used sudo apt install docker.io in the Ubuntu 20.0.4 LTS. The docker.io compose helps run the service. Then, I made a file directory and add docker-compose.yml with the nano editor. Also, I went to the founder's GitHub page and copied and paste the code in the yml file. This contains the default administrator port number, and passcode when I log in with my credential. I execute the program and it creates containers that construct the Peppermint page as you can see in the first screenshot. Once it finishes, I grabbed the reverse DNS address with the port number from the Network tab. I log in to the administrator and the password.
</p>

<h1>Linode Lish Console</h1>
<img src="https://i.imgur.com/hui6g4Z.png" height="65%" width="65%" alt="blank"/>
<p>
 The following commands I use when creating a yml file.
   <ul>
     <li>Sudo apt install docker.io docker-compose -y</li>
     <li>mkdir Peppermint</li>
     <li>cd peppermint</li>
     <li>nano docker-compose.yml</li>
     <li>docker-compose up -d</li>
   </ul>
   <img src="https://i.imgur.com/EQ9eR9l.png" height="65%" width="65%" alt="blank"/>
</p>
<h1>Personal Notebook</h1>
<img src="https://i.imgur.com/c31QhSL.png" height="65%" width="65%" alt="blank"/>
<br>
<img src="https://i.imgur.com/LXN4jAu.png" height="65%" width="65%" alt="blank"/>

<p>
  The Personal Notebook adds quite a nice feature to have. I created a notebook named Daily Logs.
</p>
<h1>Docker-compose.yml Script</h1>
<img src="https://i.imgur.com/hui6g4Z.png" height="65%" width="65%" alt="blank"/>
<p>
  This is a bash script with Nano editor.
</p>

<h1>Internal Users</h1>
<img src="https://i.imgur.com/dPRQ53w.png" height="65%" width="65%" alt="blank"/>
<p>
In the Internal Users, there is only a user and administrator when assigning one of these two roles. 
I can reset a password if the user's email address is correct. On the Peppermint homepage, there is no user, and must enter an email address.
</p>

<h1>Clients</h1>
<img src="https://i.imgur.com/KrR6a8v.png" height="65%" width="65%" alt="blank"/>
<p>
The client as you see is a list of organization names along with email address, job title, and phone number. There are current groups that exist.
</p>


<h1>Tickets</h1>
<p>This is where some tickets show with one of the three priority tags: low, normal, and high. Depending on how long and what kind of technical issue is, I would go through one ticket at a time and look at the description and the picture.</p>

<img src="https://i.imgur.com/vY4gnhT.png" height="65%" width="65%" alt="blank"/>

<h2>Ticket issue Example</h2>
<h3>Ticket #1</h3>
<img src="https://i.imgur.com/dy9mr4h.png" height="65%" width="65%" alt="blank"/>
<br>

<h3>Ticket #2</h3>
<img src="https://i.imgur.com/dy9mr4h.png" height="65%" width="65%" alt="blank"/>
<br>

<h3>Youtube</h3>
https://youtu.be/h_RZMDm7pr4


