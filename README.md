<p align="center">
<img src="https://i.imgur.com/TyIUVZZ.png" alt="Microsoft Azure Cloud Logo"/>
</p>

<h1>Connecting to & Utilization of Virtual Machines via Microsoft Remote Desktop</h1>
This tutorial outlines connection to an Azure Virtual Machine via Microsoft Remote Desktop Connection.<br/>


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computers)
- Microsoft Remote Desktop Connection

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>
1. Find & Copy Public IP address of your Virtual Machine (In Azure Portal)
2. Open up Microsoft Remote Desktop Connection
3. Connect to the Virtual Machine (VM) with its Public IP Address
4. Log into the VM with required login credentials

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/RIlGKUA.png" height="50%" width="33%" alt="Virtual Machine Setup Steps"/><img src="https://i.imgur.com/EO2Ya60.png" height="50%" width="33%" alt="Virtual Machine Setup Steps"/><img src="https://i.imgur.com/eTcgsMY.png" height="50%" width="33%" alt="Virtual Machine Setup Steps"/>
</p>
<p>
Set up your Azure subscription and log into portal.azure.com. On the home page (1st pic from left), click on Resource Groups icon under "Azure services" or type in Resource Groups in search bar and then click on the same icon. You'll arrive at the dashboard page (2nd pic in middle) for all your resource groups (RGs) in your subscription. Click on the blue "Create resource group" button or click on "+Create" underlined on top left of page to create a new RG. On the next page (3rd pic on right), choose your RG name and its region. For this example, this RG is "AD-Lab-RG" and its chosen region is "East US". After that, click "Review + Create".
</p>
<br />

<p>
<img src="https://i.imgur.com/nk9zIGY.png" height="50%" width="50%" alt="Virtual Machine Setup Steps"/><img src="https://i.imgur.com/S3kaKBv.png" height="50%" width="50%" alt="Virtual Machine Setup Steps"/>
</p>
<p>
The RG will pass through validation. After it passes validation, click on "Create" button. Now the RG is built, we'll move on to creating the virtual machine (VM) that will be assigned to it.
</p>
<br />

<p>
<img src="https://i.imgur.com/ap8qlP9.png" height="50%" width="33%" alt="Virtual Machine Setup Steps"/><img src="https://i.imgur.com/xXkRlKg.png" height="50%" width="33%" alt="Virtual Machine Setup Steps"/><img src="https://i.imgur.com/LzB0D9x.png" height="50%" width="33%" alt="Virtual Machine Setup Steps"/>
</p>
<p>
(In left pic) Start typing in the search bar "virtual machines". Click on the virtual machines icon that comes up in the drop down menu. On next page (middle pic), you can click the Create button in the top left or the create button in the center of the page. Click on "Azure virtual machine" from the menu of options that pops up. On the next page (right pic), fill out the required details for your virtual machine (resource group, VM name, region, image, and Administrator account username & password). In this example so far, RG is AD-Lab-RG, VM name is Client-1, Region is East US, and image is Windows 10 Pro version 21H2.
</p>
<br />

<p>
<img src="https://i.imgur.com/uzNVsRC.png" height="50%" width="33%" alt="Virtual Machine Setup Steps"/><img src="https://i.imgur.com/vb818Li.png" height="50%" width="33%" alt="Virtual Machine Setup Steps"/><img src="https://i.imgur.com/e7OFZRn.png" height="50%" width="33%" alt="Virtual Machine Setup Steps"/>
</p>
<p>
(Left pic) Fill out the remaining required details for your VM (Administrator account username & password). In this example, username is labuserdin and password is Virtual123mach. Leave other required fields with preselected default choices alone. Check the box confirming you have an eligible Windows 10/11 license and then click "Review & create" below. On next page (middle pic), you should see that your VM passed validation. Click "create" at the bottom of the page below. Repeat the steps for filling out info for the VM again IF you click "Review & create" and you don't pass validation soon after. On the next page (left pic), you'll see deployment of your virtual machine is in progress. This will take a few minutes.
</p>
<br />

<p>
<img src="https://i.imgur.com/9MJk1O0.png" height="50%" width="50%" alt="Virtual Machine Setup Steps"/><img src="https://i.imgur.com/s4hNF03.png" height="50%" width="50%" alt="Virtual Machine Setup Steps"/>
</p>
<p>
(Left pic) In a few minutes, deployment of your VM will complete as shown. Click on "Go to resource" button. (right pic) On the next page, you have all the info listed for your new VM including Public IP address, private IP address, virtual network, and more.
</p>
<br />
