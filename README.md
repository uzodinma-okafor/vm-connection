<p align="center">
<img src="https://i.imgur.com/TyIUVZZ.png" alt="Microsoft Azure Cloud Logo"/>
</p>

<h1>Connecting to & Utilization of Virtual Machines via Microsoft Remote Desktop Cnnection</h1>
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
After getting to your VM in in the Azure portal, find & copy Public IP address of your Virtual Machine in the top right of page. You can click the copy button that appears when you hover over the IP address and it's instantly copied. 
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
(In left pic) Start typing in the search bar "virtual machines". Click on the virtual machines icon that comes up in the drop down menu. On next page (middle pic), you can click the Create button in the top left or the create button in the center of the page. Click on "Azure virtual machine" from the menu of options that pops up. On the next page (right pic), fill out the required details for your virtual machine (resource group, VM name, region, image, and Administrator account username & password). In this example so far, RG is AD-Lab-RG, VM name is Client-1, Region is East US, and image is Windows 10 Pro version 21H2.
</p>
<br />

<p>
<img src="https://i.imgur.com/svKHavc.png" height="50%" width="33%" alt="Virtual Machine Setup Steps"/>
</p>
<p>
(Left pic) Fill out the remaining required details for your VM (Administrator account username & password). In this example, username is labuserdin and password is Virtual123mach. Leave other required fields with preselected default choices alone. Check the box confirming you have an eligible Windows 10/11 license and then click "Review & create" below. On next page (middle pic), you should see that your VM passed validation. Click "create" at the bottom of the page below. Repeat the steps for filling out info for the VM again IF you click "Review & create" and you don't pass validation soon after. On the next page (left pic), you'll see deployment of your virtual machine is in progress. This will take a few minutes.
</p>
<br />
