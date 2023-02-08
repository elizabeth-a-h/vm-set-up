
<h1>Azure Virtual Machine Set Up</h1>
This tutorial outlines the set up for an Azure Virtual Machine. <br />


- Microsoft Azure 

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)


<h2>Installation Steps</h2>

1. Set up a new Resouce Group in Azure
2. Name and choose Region for Resource Group
3. Create Virtual Machine
4. Choose Settings for VM
5. Set up Admin Account for VM
6. Create VM
7. Verify VM completion

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/ZcQjgKA.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>   &nbsp;  &nbsp; &nbsp;  &nbsp;  &nbsp; &nbsp;      <img src="https://i.imgur.com/zWu4izo.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Set up a new Resource Group in Azure
Log into your Azure account subscription at portal.azure.com
On home screen, choose "Resource Groups" and click "Create" to create a new Resources Group
</p><hr> 
<br />
<p>
<img src="https://i.imgur.com/DkL2hzc.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>  &nbsp;  &nbsp; &nbsp;  &nbsp;  &nbsp; &nbsp;     <img src="https://i.imgur.com/hIk6ueY.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
2. Name the new Resource Group. Choose the region to save your Resource Group (may be dependent upon your company requirements or region closest to you)
Click "Review and Create"
after the "Validation Passed" message is received, click "Create"
</p><hr>

<br />

<p>
<img src="https://i.imgur.com/hP895L8.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>  &nbsp;  &nbsp; &nbsp;  &nbsp;  &nbsp; &nbsp;     <img src="https://i.imgur.com/JTeobqU.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
3. Create new Virtual Machine in Azure.
Return to the home Azure screen, click on "Virtual Machines", click on "Create", and from the drop down menu, choose "Azure Virtual Machine hosted by Azure"
</p><hr>
<br />

<p>
<img src="https://i.imgur.com/RiaYClk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
4. Click the Drop Down Menu to choose the Resource Group that you created in step 1.
Name your Virtual Machine (ie: I named mine VM1)
Choose the region (I chose the same region that I saved the Resource Group in step 1)
Choose Windows 10 Pro version 21H2 from the Image drop down.
Scroll down and choose a memory size 2-4 Virtual CPUs, being aware of the pricing and the size required.

</p><hr>

<br />

<p>
<img src="https://i.imgur.com/U0H9gSm.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>  &nbsp;  &nbsp; &nbsp;  &nbsp;  &nbsp; &nbsp;     <img src="https://i.imgur.com/9StekB9.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
5. Create your admin account Username and Password. Write this down!
Example:
Username: Labuser
Password: PasswordLab123
Check the licensing box and click "review and create" 

</p><hr>

<br />

<p>
<img src="https://i.imgur.com/w6TpVdx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
6. Wait for "Validation Passed" message, and then click "Create"
Note: "Deployment" of your Virtual Machine may take several minutes
</p><hr>

<br />

<p>
<img src="https://i.imgur.com/EhAiYqW.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>  &nbsp;  &nbsp; &nbsp;  &nbsp;  &nbsp; &nbsp;     <img src="https://i.imgur.com/FdIZbVV.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
7. To verify the completion of your VM, return to the Azure Home screen, by clicking home, or typing portal.azure.com into the browser to refresh, and then click on "Virtual Machines" to see your VM listed. 
</p>

<br />
