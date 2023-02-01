<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>Virtual Machine and Remote Deskto Set Up</h1>
This tutorial outlines the set up for Azure VM and connecting to that VM using Microsoft Remote Desktop on Mac.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure 
- Microsoft Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Installation Steps</h2>

<p>img1 & img2
<img src="https://imgur.com/ZcQjgKA" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Set up a new Resource Group in Azure
Log into your Azure account subscription at portal.azure.com
On home screen, choose "Resource Groups" and click "Create" to create a new Resources Group
</p>
<br />
<p>img3 & img4
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
2. Name the new Resource Group. Choose the region to save your Resource Group (may be dependent upon your company requirements or region closest to you)
Click "Review and Create"
after the "Validation Passed" message is received, click "Create"
</p>

<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
img 5, 6, 7
<p>
3. Create new Virtual Machine in Azure.
Return to the home Azure screen, click on "Virtual Machines", click on "Create", and from the drop down menu, choose "Azure Virtual Machine hosted by Azure"
</p>
<br />

<p>img 8
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
4. Click the Drop Down Menu to choose the Resource Group that you created in step 1.
Name your Virtual Machine (ie: I named mine VM1)
Choose the region (I chose the same region that I saved the Resource Group in step 1)
Choose Windows 10 Pro version 21H2 from the Image drop down.
Scroll down and choose a memory size 2-4 Virtual CPUs, being aware of the pricing and the size required.

</p>

<br />

<p>img 9 & 10
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
5. Create your admin account Username and Password. Write this down!
Example:
Username: Labuser
Password: PasswordLab123
Check the licensing box and click "review and create" 

</p>

<br />

<p>img 11
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
6. Wait for "Validation Passed" message, and then click "Create"
Note: "Deployment" of your Virtual Machine may take several minutes
</p>

<br />

<p>img 12 & 13
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
7. To verify the completion of your VM, return to the Azure Home screen, by clicking home, or typing portal.azure.com into the browser to refresh, and then click on "Virtual Machines" to see your VM listed. 
</p>

<br />
