<h1>Elastic Cloud- SIEM dashboard</h1>

<h2>Description</h2>
Description
This project involves setting up a Security Information and Event Management (SIEM) dashboard using Elastic Cloud. The goal is to enhance visibility into security events and improve incident detection and response capabilities. The project includes configuring Elastic Cloud, integrating various data sources, creating alerts, and visualising security-related data.</br>

<h2>Key Objectives:</h2>
Set up Elastic Cloud account and basic configurations: Establishing a new account on Elastic Cloud and configuring the necessary settings to get started.
Integrate Kali Linux with Elastic Defend: Connecting a Kali Linux machine with Elastic Defend by installing and configuring the Elastic Agent.
Implement Packetbeat: Using Packetbeat to collect and send data to Elastic Cloud, providing insights into network activities.
Create and manage security alerts: Configuring alerts to monitor specific security events, such as network scans detected by nmap.
Data visualisation and dashboard creation: Utilising Elastic Cloud's visualisation features to create informative and actionable dashboards.
Proactive monitoring: Setting up the system to proactively monitor for suspicious activities and potential security threats..
</br>


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
<img src="https://i.imgur.com/hNE3MHf.png" height="500" width="500"/>
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
In the Top Left their is three lines click on it": <br/>
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
Why it's not sending data through Kali linux to my main machine, when i was talking about the network if you're not connected it won't be able to send data (bytes) over: <br/>
<img src="https://i.imgur.com/ocKMDJR.png"/>
<br />
<br />
Open up VM in the window's search then find network: <br/>
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
<br />
<br />
When this text pop's up just confirm inputing "Y": <br/>
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
