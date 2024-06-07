<h1>Elastic Cloud- SIEM dashboard</h1>

<h2>Description</h2>
Description
This project involves setting up a Security Information and Event Management (SIEM) dashboard using Elastic Cloud. The goal is to enhance visibility into security events and improve incident detection and response capabilities. The project includes configuring Elastic Cloud, integrating various data sources, creating alerts, and visualising security-related data.

<h2>Key Objectives:</h2>
Set up Elastic Cloud account and basic configurations: Establishing a new account on Elastic Cloud and configuring the necessary settings to get started.
Integrate Kali Linux with Elastic Defend: Connecting a Kali Linux machine with Elastic Defend by installing and configuring the Elastic Agent.
Implement Packetbeat: Using Packetbeat to collect and send data to Elastic Cloud, providing insights into network activities.
Create and manage security alerts: Configuring alerts to monitor specific security events, such as network scans detected by nmap.
Data visualisation and dashboard creation: Utilising Elastic Cloud's visualisation features to create informative and actionable dashboards.
Proactive monitoring: Setting up the system to proactively monitor for suspicious activities and potential security threats.
Creating rules and setting up network packet capture: Integrating and configuring rules on Elastic Cloud to capture and analyse network packets effectively.


<h2>Languages and Utilities Used</h2>

- <b><body>Languages:</body> Bash, Command Prompt (CMD)</b> 
- <b><body>Utillities:</bdoy> OBS Studio, Elastic Cloud, Packetbeat, Elastic Agent, Nmap, Wireshark</b>

<h2>Environments Used </h2>

- <b><body>Operating Systems:</body> Windows 10 Pro, Kali Linux</b> (21H2)
- <b><body>Virtual Machines:</body> Oracle VM VirtualBox for running Kali Linux</b>
-<b><body>Tools:</body> Elastic Cloud, CMD, Bash</br>

<h2>Program walk-through:</h2>

<p align="center">
Search Virtual Box: <br/>
<img src="https://i.imgur.com/X6uR4vz.png"/>
<br />
<br />
Click on Download:  <br/>
<img src="https://i.imgur.com/cKK6yQI.jpeg"/>
<br />
<br />
Pick the correct OS: <br/>
<img src="https://i.imgur.com/rXKhvAB.png"/>
<br />
<br />
Next is Kali Linux:  <br/>
<img src="https://i.imgur.com/ummw1KN.png"/>
<br />
<br />
Click on Installer Images:  <br/>
<img src="https://i.imgur.com/lmUzZRe.png"/>
<br />
<br />
Pick any Kali ISO:  <br/>
<img src="https://i.imgur.com/fSZs8jp.jpeg"/>
<br />
<br />
Click on new:  <br/>
<img src="https://i.imgur.com/Hnhtqmi.jpeg"/>
<br />
<br />
Click on the dropbox:  <br/>
<img src="https://i.imgur.com/UBzbAH5.jpeg"/>
<br />
<br />
It would pop up like this: <br/>
<img src="https://i.imgur.com/CRNN4g4.png"/>
<br />
<br />
When ISO image is chosen click on "Next": <br/>
<img src="https://i.imgur.com/f6afjpb.png"/>
<br />
<br />
Pick a reasonable Ram and process recommend 4GB RAM 2 CPU: <br/>
<img src="https://i.imgur.com/uKdMIRL.png"/>
<br />
<br />
Chose a appropriate size of storage recommend 80GB: <br/>
<img src="https://i.imgur.com/HVXAVtI.png"/>
<br />
<br />
The Finally Page of installing Kali linux on VM: <br/>
<img src="https://i.imgur.com/scgZT6A.png"/>
<br />
<br />
After head towards settings to configure the machine: <br/>
<img src="https://i.imgur.com/RAhtdax.png"/>
<br />
<br />
Firsly tick the box to turn of floppy disk: <br/>
<img src="https://i.imgur.com/RAhtdax.png"/>
<br />
<br />
Using your mouse dragging the toggle to correct video memory 128MB: <br/>
<img src="https://i.imgur.com/EojFLSy.png"/>
<br />
<br />
Scroll down and pick Network: <br/>
<img src="https://i.imgur.com/qEC6sHX.png"/>
<br />
<br />
Chose Bridge Adapter will show why later on: <br/>
<img src="https://i.imgur.com/ywPHgXl.png"/>
<br />
<br />
Now click on start to setup Kali Linux: <br/>
<img src="https://i.imgur.com/SQK7JeJ.jpeg"/>
<br />
<br />
Pick the option Graphical Install: <br/>
<img src="https://i.imgur.com/3XgbZsn.png"/>
<br />
<br />
Go through the whole process, pick your language: <br/>
<img src="https://i.imgur.com/nrVtOlT.png"/>
<br />
<br />
Next is keyboard: <br/>
<img src="https://i.imgur.com/JkpTVC9.png"/>
<br />
<br />
Let that process complete: <br/>
<img src="https://i.imgur.com/nAwoqnf.png"/>
<br />
<br />
Type a hostname: <br/>
<img src="https://i.imgur.com/lhtqwjq.png"/>
<br />
<br />
Create a strong password: <br/>
<img src="https://i.imgur.com/D7ibCrd.png"/>
<br />
<br />
When clicked on Continue let the progress bar complete: <br/>
<img src="https://i.imgur.com/L3TIrQW.png"/>
<br />
<br />
When clicked on Continue let the progress bar complete: <br/>
<img src="https://i.imgur.com/6hWIOG4.png"/>
<br />
<br />
When clicked on Continue let the progress bar complete: <br/>
<img src="https://i.imgur.com/6hWIOG4.png"/>
<br />
<br />
When the progress bar completed click on continue on this page: <br/>
<img src="https://i.imgur.com/yIcqvZ7.png"/>
<br />
<br />
It will load back on page where you could wait up to 5 minutes: <br/>
<img src="https://i.imgur.com/RgeoUpC.png"/>
<br />
<br />
Click the box YES then proceed to contuine: <br/>
<img src="https://i.imgur.com/MYzld0h.png"/>
<br />
<br />
Then click on the second option: <br/>
<img src="https://i.imgur.com/WnEsHcI.png"/>
<br />
<br />
Then this would be the last loading page: <br/>
<img src="https://i.imgur.com/gGojo23.png"/>
<br />
<br />
Click on Contuine: <br/>
<img src="https://i.imgur.com/SoSrFxu.png"/>
<br />
<br />
Loading onto the Kali Linux Machine: <br/>
<img src="https://i.imgur.com/sQ6NVog.png"/>
<br />
<br />
Click on switch however if you don't want to be in full screen CTRL + F: <br/>
<img src="https://i.imgur.com/mNkhvFP.png"/>
<br />
<br />
Input your username and password you created while setting up Kali Linux: <br/>
<img src="https://i.imgur.com/a4DHPlN.png"/>
<br />
<br />
Now you have access to Kali Linux: <br/>
<img src="https://i.imgur.com/pqilXA2.png"/>
<br />
<br />
Go back to your preferred search engine then input elastic cloud: <br/>
<img src="https://i.imgur.com/Yl0kjHg.png"/>
<br />
<br />
First Link click on it: <br/>
<img src="https://i.imgur.com/cPUIBBu.png"/>
<br />
<br />
Create a account with gmail sign up or input manually: <br/>
<img src="https://i.imgur.com/iCmiTqJ.png"/>
<br />
<br />
Input your name and a company as this only a 14 day's trial: <br/>
<img src="https://i.imgur.com/nUcHHAX.png"/>
<br />
<br />
After clicking on Next, create your deployment: <br/>
<img src="https://i.imgur.com/gVjkZsh.png"/>
<br />
<br />
Remember to save your username & password credentials  <br/>
<img src="https://i.imgur.com/cremJNL.png"/>
<br />
<br />
It could take 5 minutes or 10 to create your deployment: <br/>
<img src="https://i.imgur.com/iT75K84.png"/>
<br />
<br />
Well waiting we can setup root privilege (Error shown and resolved) Seen in the screenshot needing to input the command "sudo passwd" then root privilege will work: <br/>
<img src="https://i.imgur.com/7DvJ5jk.png"/>
<br />
<br />
Then remember to input the command "sudo apt update && sudo apt upgrade" reasons are: <br>
<h1>Importance of Updating and Upgrading Kali Linux </h1>
<h2>Security:</h2> Updates include patches for security vulnerabilities, keeping your system safe from threats.
<h2>Stability:</h2> Bug fixes and updated dependencies enhance system stability and prevent crashes.
<h2>Features:</h2> Upgrades bring new tools and improvements, essential for effective security testing.
<h2>Compatibility:</h2> Updates ensure better compatibility with the latest hardware and software.
<h2>Support:</h2> Staying up-to-date makes it easier to get help and use current documentation.
Maintaining an updated Kali Linux system ensures it remains secure, stable, and equipped with the latest tools for cybersecurity tasks.<br />
<img src="https://i.imgur.com/mWri9Jf.png" height="500" width="600"/>
<br />
<br />
When the deployment is ready click on continue: <br/>
<img src="https://i.imgur.com/eYNFAnt.png"/>
<br />
<br />
This page will pop up, click on "I'd like to explore on my own.": <br/>
<img src="https://i.imgur.com/nz0WkOl.jpeg"/>
<br />
<br />
In the Top Left their is three lines click on it: <br/>
<img src="https://i.imgur.com/KAlWoP8.jpeg"/>
<br />
<br />
Scroll down until you find "Management" under it will be text that goes by "Integrations": <br/>
<img src="https://i.imgur.com/Lx9Q4sX.jpeg"/>
<br />
<br />
When loaded on Integrations first page, Elastic Defend would be click on it: <br/>
<img src="https://i.imgur.com/IuUwrQF.jpeg"/>
<br />
<br />
When Elastic Defend pops up below click on Install Elastic Agent: <br/>
<img src="https://i.imgur.com/srWZqp1.jpeg"/>
<br />
<br />
Now this page where you would have to copy the command onto your kali linux machine, however needing to click on devices, drag and drop then picking the option bidirectional this will let us drag any image's, text and information from our main computer to the kali linux also allowing us to do the same. Proceed to copy to clipboard the code from elastic cloud then input into the bash terminal: <br/>
<img src="https://i.imgur.com/kTi6kOP.jpeg"/>
<br />
<br />
Start a New terminal: <br/>
<img src="https://i.imgur.com/uDsnM7q.jpeg"/>
<br />
<br />
Why it's not sending data through Kali linux to my main machine, when i was talking about the network if you're not connected it won't be able to send data (bytes) over:
<img src="https://i.imgur.com/ocKMDJR.png">
<br />
<br />
Open up VM in the window's search then find network:
<img src="https://i.imgur.com/YtleL7k.png"/>
<br />
<br />
Change it to a Bridged Adapter (Next time we setup our own NAT interent with Static IP): <br/>
<img src="https://i.imgur.com/K9xAvyJ.png"/>
<br />
<br />
Now you see it's sending data through my Kali Linux Machine to my main computuer: <br/>
<img src="https://i.imgur.com/ik8yGOf.png"/>
<br />
<br />
When this text pop's up just confirm inputing "Y": <br/>
<img src="https://i.imgur.com/kWIImmq.png"/>
<br />
<br />
When this text pop's up just confirm inputing "Y": <br/>
<img src="https://i.imgur.com/kWIImmq.png"/>
<br />
<br />
Finally Elastic Agent is downloaded: <br/>  
<img src="https://i.imgur.com/CtPjYR6.png"
<br />
<br />
First find out what is your ip address for your kali linux machine "ifconfig":
<img src="https://i.imgur.com/RBMTF8u.png" #
<br />
<br />
You would find it starting with 192 your ip address for that computer specifically inputing in the BASH terminal:
<br />
<img src="https://i.imgur.com/cHb3ZXx.png"
<br />
<br />
To find your ip address for windows OS, search command prompt but run as administrator:
<img src="https://i.imgur.com/FxPKqMg.png"
<br />
<br />
Input the command ipconfig or ipconfig all: 
<img src="https://i.imgur.com/UZcnlEx.png"
<br />
<br />
Let's ping the kali linux machine on our cmd, you can see it's sending data:
<img src="https://i.imgur.com/Xxo71jL.png"> <img src="https://i.imgur.com/9YaNmb4.png">
<br />
<br />
You see if we ping on the kali linux machine, it's not sending data through we need to resolve the connection between each machines: 
<br />
<img src="https://i.imgur.com/copsjhf.png"
<br />
<br />
Follow steps to resolve the issue, search on your windows OS windows defender firewall with advanced security:
<br />
<img src="https://i.imgur.com/XZbyU6W.png"
<br />
<br />
Click on inbound rules then procced to following next steps:
<img src="https://i.imgur.com/DlrbpsB.jpg"
<br />
<br />
Scroll down until you find "file and print sharing (echo requesting) IPV4 and IPV6 however IPV4 would still work.
<img src="https://i.imgur.com/K74A9S4.png"
<br />
<br />
Now you see their is connecton between both machines and allowing data to be sent across the systems:
<br />
<img src="https://i.imgur.com/PEoeKxm.png"
<br />
<br />
Process to input a nmap command, i am going to show you how you can find it in the logs:
<br />
<img src="https://i.imgur.com/wz8q8tL.png"
<br />
<br />
Now click on the three lines where the red arrow is pointing towards to then find "Observability" click on logs:
<img src="https://i.imgur.com/49f5STH.jpg"
<br />
<br />
This page will pop up where it show's your recent actions you can change the to show information up to two weeks or every one hour:
<img src="https://i.imgur.com/u9npZO7.png"
<br />
<br />
Search "Process:args: nmap" then procced to click on the three dots then view details:
<img src="https://i.imgur.com/2Fk2txX.png"> <img src="https://i.imgur.com/eJjhrdc.png"> <img src="https://i.imgur.com/G0mae01.png"> 
<br />
Then scroll down and you will find the latest command you inputed in the terminal bash:
<br />
<br />
Now Click on the three lines and find dashboard we will be creating a "SAMPLE" SIEM dashboard basic understandment of how it works:
<img src="https://i.imgur.com/JvyRPRN.png">
Click on create visualization:
<img src="https://i.imgur.com/zWJ1eBZ.jpg">
Firsly click on horizontal axis, pick @timestamp:
<img src="https://i.imgur.com/yUrJpBE.png"> <img src="https://i.imgur.com/l66zovN.png">
<br />
Secondly click on Vertical axis, chose count:
<img src="https://i.imgur.com/1YDDfpx.png"> <img src="https://i.imgur.com/cBD2nCz.png">
<br />
<br />
Now you have created a  dashboard on Elastic Cloud displays a graph with the horizontal axis representing timestamps and the vertical axis representing the count of records. This graph shows the number of records collected over time, allowing you to monitor data trends and activity levels from your Kali Linux machine.
<img src="https://i.imgur.com/isRINdd.png">
<br />
<br />
You even have the option, to pick different Visualization types for example:
<img src="https://i.imgur.com/WhNIOmb.png"> <img src="https://i.imgur.com/AAw5U4w.png">
<br />
<br />
Now when you're done remember to save and return:
<img src="https://i.imgur.com/VY5f7yK.png">
<br />
<br />
When saved and return click on add panel then procced to click on log stream:
<img src="https://i.imgur.com/amZg2Mg.png">
<br />
You will be able to see, recent logs from you Kali linux machine:
<img src="https://i.imgur.com/TdKHTa4.png">
<br /?
Remember to save your dashboard and give it a ttile, if you desire write a description as this is just a sample:
<img src="https://i.imgur.com/CpdGPu7.png">
<br />
<br />
However with Elastic cloud, it comes with perapred dashboard for example Detection rule monitoring:
<img src="https://i.imgur.com/p2Rs57M.png"> <img src="https://i.imgur.com/hK9OBZp.png">
<br />
<br />
Let's configure elastic agent on kali linux starting off inputing these two commands shown in the screenshot also for this example we won't be setting up API KEYS OR SSL certification :
<img src="https://i.imgur.com/QoPiZZR.png">
<br />
As seen in the screen shot we need to find you elastic search endpoint:
<img src="https://i.imgur.com/DOQSsZj.png"> <img src="https://i.imgur.com/hLpzO9C.png">
<br />
When you copied the elastic search endpoint, remember those credentials you saved well creating your deployment did you save it in secure place? 
<img src="https://i.imgur.com/cremJNL.png"> <br /> input those credentails where it shows username & password: then click on your <body> KEYBOARD </body> CTRL X then CTRL YES then click on ENTER <br /> <img src="https://i.imgur.com/hkwDtzX.png"> 
<br /> 
<br />
Now we have configured elastic agent let's download packetbeat from my example i have shown on word document:
<img src="https://i.imgur.com/dPPd3hr.png">
<br />
Skip this part click on "Cancel":
<img src="https://i.imgur.com/45ODYfm.png">
<br />
<br />
Now input the command shown on the screen shot, to check if it's running and active, it's unactive so let's fix this:
<img src="https://i.imgur.com/FIqYMoe.png"> <br />
Input the command shown in the screen shot below:
<img src="https://i.imgur.com/pd5GGz4.png">
<br />
Then scroll down until you find elastic cloud:
<img src="https://i.imgur.com/rt9M8hO.png">
<br />
Afterwards input the elastic cloud id and your username shown in the screen shot:
<img src="https://i.imgur.com/IW5Jk3f.png">
<br /> 
Scroll down to below outputs, elastic search output we will be including elastic search end point url, username & password:
<img src="https://i.imgur.com/ENyF6kQ.png"> <img src="https://i.imgur.com/mRW9TI3.png">
<br />
<br />
When configured, input the command to see if the config is ensure working, then next command "sudo journalctl -u packetbeat":
<img src="https://i.imgur.com/0RV97QQ.png"> <br />
You can seen in the screenshot below, their is a mistake configured on packetbeat.yml, let's resolve this issue:
<img src="https://i.imgur.com/AzwMlCi.png">
<br />
<br />
Input the command again "sudo nano /etc/packetbeat/packetbeat.yml" then scroll down until you find Kibana input the host:
<img src="https://i.imgur.com/pd5GGz4.png"> <img src="https://i.imgur.com/F2UCTD6.png"> <br> <img src="https://i.imgur.com/gMjGuFp.png"> 
<br />
We will be having to create a Kibana Admin account, click on the three lines scroll down until you find "Stack Management":
<img src="https://i.imgur.com/z40hnfC.png"> <img src="https://i.imgur.com/bAGI52A.png">
<br /> 
<br />
See on Security in bold, under it users click on "create user" 
<img src="https://i.imgur.com/4KyifdQ.png">
<br />
Create the username, then a password below it pick the role kibana_admin then save the user:
<img src="https://i.imgur.com/4N3COCz.png"> 
<br />
Now input those credentials that you created into packetbeat.yml then exit remember how to? it's CTRL X, CTRL YES then click on enter to save the configuration:
<img src="https://i.imgur.com/iBH99Rm.png">
<br />
<br />
Now input this command "packetbeat devices" you would see which of your ip address is assigned such mine is eth1:
<img src="https://i.imgur.com/4aoavWJ.png">
<br />
Go back onto <body> SUDO NANO /ETC/PACKETBEAT/PACKETBEAT.YML </body> then find interfaces devices change it to the device that is assigned to a ip address:
<img src="https://i.imgur.com/J7lsGt2.png"> <img src="https://i.imgur.com/5U0CtF3.png">
<br />
<br />
Now let's setup packetbeat: 
<br />
<img src="https://i.imgur.com/3djW0fR.png"> <br> You can cleary see that their is a mistake in the packetbeat.yml configuration:    
<img src="https://i.imgur.com/qjDgVfy.png">
<br />
Below setup.kibana type this correctly, shown below:
<img src="https://i.imgur.com/x9LiJaY.png"> <img src="https://i.imgur.com/d67xUHO.png">
<br /> 
Do you see what was another mistake, just simple mistakes like this these programs won't work we copied the elastic search end point not the kibana end point and having <body> # after username and password it needs to be deleted for the command can WORK</body>: 
<img src="https://i.imgur.com/mO3loJ3.png"> 
<br />
<br />
Now input the command below let it go through it process: 
<img src="https://i.imgur.com/gUxSz8h.png"> <img src="https://i.imgur.com/WjqXXmN.png">
<br />
Then check status of packetbeat you see now it's active and running <em> perfect </em>:
<img src="https://i.imgur.com/gUGWqaB.png">
<br />
<br />
<h2> Let's go into discover </h2>
<br />
click on the drop box and chose packetbeat-* then proceed to click on dashboard you see DNS traffic and if you click "dashboards" many other dashboards that is assigned with packetbeat specifically: 
<img src="https://i.imgur.com/Cn2M8yf.png"> <img src="https://i.imgur.com/nAdbLVE.png"> <img src="https://i.imgur.com/lglls2u.png"> <img src="https://i.imgur.com/A07O7L3.png">
<h1> Here is addition </h1> you can configure on elastic cloud, and network packet capture a intergraton that will be automatically created for you and your machine instead of manually setting it up with packetbeat or another service:                                                             <br />
<body> let's create a rule </body> starting off find Oversability then rules, click on create new rule after creating a name click on elastic search query for this example: 
<img src="https://i.imgur.com/MhbsnB0.png">
<br />
Chose KQL or Lucene, then scroll down you will find in big text <body> Actions </body> their is many optioins you can pick this is great espcially if it's big team or anything for example a hacker could gain acess to confidential information you can send a warning and send alerts:
<img src="https://i.imgur.com/JkX5dRK.png"> <img src="https://i.imgur.com/t1VH3Xu.png">
<br />
Set up a email, you can chose mutiple it doesn't need to be gmail.com, create subject and message:
<img src="https://i.imgur.com/CqmTNkv.png"> 
<br /> 
<br />
<h3> Finally Let's show you hwo to setup Network Packet Capture </h3>
Firstly begin to click on the three lines and find at the below intergration's it will pop up immediately Network Packet Capture:
<img src="https://i.imgur.com/5IzYpWC.png">
Then click on add, we will need to configure how elastic agent on our elastic agent.
<img src="https://i.imgur.com/LWXphfD.png"> <br /> <img src="https://i.imgur.com/qQvgp0b.png">
<br /> <img src="https://i.imgur.com/dtZQOZB.png"> 
<br />
<br />
Go on to elastic agent and find Inputs:
<img src="https://i.imgur.com/sL8ZcPl.png">
<br />
<br />
Then click on the copy symbol:
<img src="https://i.imgur.com/8BNUsHC.png">
<br /> 
Under <body> INPUTS: </body> the commands you just copied from network packet caputre paste it in CTRL + C + V:
<br />
<img src="https://i.imgur.com/aDefpgu.png">
<br />
Now go back onto your dashboard's, the netwrok packet captures dashboard that they provid will be available<br/>
<img src="https://i.imgur.com/aft20fG.png">
</p>
