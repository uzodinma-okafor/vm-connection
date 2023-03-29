<p align="center">
<img src="https://i.imgur.com/TyIUVZZ.png" alt="Microsoft Azure Cloud Logo"/>
</p>

<h1>Connecting to & Utilization of Virtual Machines via Microsoft Remote Desktop Connection</h1>
This tutorial outlines connection to an Azure Virtual Machine via Microsoft Remote Desktop Connection.<br/>


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computers)
- Microsoft Remote Desktop Connection

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>
1. Follow tutorial for <a href="https://github.com/uzodinma-okafor/vm-creation">Creation of a Virtual Machine via Microsoft Azure</a>, then go to next step.
2. Find & Copy Public IP address of your Virtual Machine (In Azure Portal)
3. Open up Microsoft Remote Desktop Connection
4. Connect to the Virtual Machine (VM) with its Public IP Address
5. Log into the VM with required login credentials

<h2>Deployment and Configuration Steps</h2> 

<p>
<img src="https://i.imgur.com/Km5cMCW.png" height="80%" width="80%" alt="Virtual Machine Connection Steps"/>
</p>
<p>
This tutorial continues from last point of the previous tutorial, <a href="https://github.com/uzodinma-okafor/vm-creation">Creation of a Virtual Machine via Microsoft Azure</a>, with the same example VM named Client-1. After accessing your VM information page in the Azure portal, find & copy Public IP address of your Virtual Machine in the top right of page. You can click the copy button that appears when you hover over the IP address and it's instantly copied. The IP address for this example is 20.62.170.74.
</p>
<br />

<p>
<img src="https://i.imgur.com/M2lCrKO.png" height="50%" width="33%" alt="Virtual Machine Connection Steps"/><img src="https://i.imgur.com/f39jpDG.png" height="50%" width="33%" alt="Virtual Machine Connection Steps"/>
</p>
<p>
Open up the Start menu on your computer and search for "remote desktop connection". Open up Microsoft Remote Desktop Connection. Paste in the Public IP address of your VM and click "Connect".
</p>
<br />

<p>
<img src="https://i.imgur.com/nBJAGWx.png" height="50%" width="33%" alt="Virtual Machine Setup Steps"/><img src="https://i.imgur.com/BWOg2Ez.png" height="50%" width="33%" alt="Virtual Machine Setup Steps"/><img src="https://i.imgur.com/X4QnLFj.png" height="50%" width="33%" alt="Virtual Machine Setup Steps"/>
</p>
<p>
(Left pic) You'll see new window asking you to enter your credentials (username and password). The username and password for Client-1 is labuserdin and Virtual123mach. Click "OK" after entering the credentials. The next window that comes up(middle pic) specifies it can't verify the computer you're connecting to and wants to ask if you still want to connect to it. The computer it's referring to is your virtual machine. Click "Yes" at the bottom of the window to proceed. (Right pic) A window opens up to your VM logging into its Windows 10 OS. This will take a few minutes. At this point, the public IP address of the VM can be seen at the top of the screen in a central blue bar.
</p>
<br />

<p>
<img src="https://i.imgur.com/svKHavc.png" height="80%" width="80%" alt="Virtual Machine Setup Steps"/>
</p>
<p>
After loading for a few minutes, the Windows 10 desktop of your VM will appear. You can now perform different tasks directly on your VM.
</p>
<br />
