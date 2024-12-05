<p align="center">
  <img src="https://i.imgur.com/OTEjkDv.png" height="70%" width="70%" alt="Virtual Machines"/>
  <br /><br />
</p>

<h1>Creating Virtual Machines and Accessing via Remote Desktop</h1>

<h2>Description</h2>
This tutorial explains what Virtual Machines are, how to set them up, and how to access them via Remote Desktop on both Windows and Mac.

<h2>What Are Virtual Machines?</h2>
A Virtual Machine (VM) is an emulation of a physical computer. It runs an operating system (OS), which manages the computer's hardware and applications. VMs allow you to run multiple OSes on a single physical device, offering flexibility and isolation between environments.

<h2>Why Use Virtual Machines?</h2>
Virtual machines let you run multiple operating systems on a single computer. They help you test different software, run apps that need different systems, and create safe, isolated spaces. VMs also save money and space by allowing you to use one computer for tasks that would normally need many.

<h2>Tools Needed for Virtual Machines</h2>

- A computer with an internet connection  
- An active Azure Subscription

<h2>Setting up Virtual Machines</h2>

1. Open a browser and go to [Azure's Portal](https://portal.azure.com/#home).
<p align="center">
  <img src="https://i.imgur.com/xErpDMq.png" height="70%" width="70%" alt="Azure Portal"/>
  <br /><br />
</p>

2. Create a Resource Group to store your VMs"
<p align="center">
  <img src="https://i.imgur.com/QbYs8La.png" height="70%" width="70%" alt="Click on Resource Group"/>
  <br /><br />
</p>

3. Click on **"Create"**.
<p align="center">
  <img src="https://i.imgur.com/p4mtvKR.png" height="70%" width="70%" alt="Click on Create"/>
  <br /><br />
</p>

4. Name your Resource Group and create it.  
   **Note**: *Ensure your Resource Group and Virtual Machine are in the same region.*
<p align="center">
  <img src="https://i.imgur.com/ER3sqGO.png" height="70%" width="70%" alt="Creating Resource Group"/>
  <br /><br />
</p>

5. Return to the [Azure's Portal](https://portal.azure.com/#home). Click on **"Virtual Machines"**.
<p align="center">
  <img src="https://i.imgur.com/UU4kE8K.png" height="70%" width="70%" alt="Virtual Machines"/>
  <br /><br />
</p>

6. Click **"Create"** and then select **"Azure Virtual Machine"**.
<p align="center">
  <img src="https://i.imgur.com/NEAcIGO.png" height="70%" width="70%" alt="Create Virtual Machine"/>
  <br /><br />
</p>

7. Configure the Virtual Machine.

- Attach it to the Resource Group your created earlier.
- Give your Virtual Machine a name.
- Select the same region as your Resource Group.
<p align="center">
  <img src="https://i.imgur.com/hwvtR7N.png" height="70%" width="70%" alt="Attach VM to Resource Group"/>
  <br /><br />
</p>

8. Choose an image type for the Virtual Machine from the dropdown menu.
<p align="center">
<img src="https://i.imgur.com/HSt0Z3e.png" height="70%" width="70%" alt" drop-down computer list"/>

9. Create a username and password for your Virtual Machine.

**"Note:"** Check the box confirming you have an eligible Windows 10/11 license. 
<p align="center">
<img src="https://i.imgur.com/vy3ATYD.png" height="70%" width="70%" alt"Create Username and Password"/>

10. Once validation passes, click **"Create"**. Azure will deploy your Virtual Machine in a few minutes. 
<p align="center">
<img src="https://i.imgur.com/lE05Jqp.png" height="70%" width="70%" alt"Deployed Virtual Machine"/>
<p align="center">
<img src="https://i.imgur.com/1gJAxJG.png" height="70%" width="70%" alt"Deployed Virtual Machine"/>

<h2>Connecting to our VM in Windows</h2>

1.

<h2>Connecting to our VM in MacOs</h2>

1. Find your VM's IP Address by clicking on the Virtual Machine in the Azure Portal. 
<p align="center">
<img src="https://i.imgur.com/Zb7CbPp.png" height="70%" width="70%" alt"Click on Virtual Machine for Details"/>

2. Copy the public IP address displayed in the VM details.
<p align="center">
<img src="https://i.imgur.com/ve9YxYL.png" height="70%" width="70%" alt"Copy IP Address"/>

3. Download **"Windows App"** from the Mac App Store.
<p align="center">
<img src="https://i.imgur.com/QwMvLNX.png" height="70%" width="70%" alt"Windows App in App Store"/>

4. Start the **"Windows App"**, click on the **"+"**, and select **"Add PC"**
<p align="center">
<img src="https://i.imgur.com/nDfqklr.png" height="70%" width="70%" alt"Adding New PC to Remote Desktop"/>

5. Enter your Virtual Machine's IP Address in **"PC Name"** and give it a **"Friendly Name"** Click **"Add"**.
<p align="center">
<img src="https://i.imgur.com/ZUscUQ6.png" height="70%" width="70%" alt"IP Address in Remote Desktop"/>






