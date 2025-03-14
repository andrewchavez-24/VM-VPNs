<p align="center">
<img src="https://github.com/user-attachments/assets/d0730697-2b21-4429-a3ff-109284cf2ee9" />
</p>

<h1>Creating Virtual Machines (Azure) for Remote Desktop</h1>
This tutorial outlines the implementation of Virtual Machines within Azure.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Create a Resource Group
- Create a Windows 10 Virtual Machine (VM)
- Create a Linux (Ubuntu) VM
- Observe Your Virtual Network within Network Watcher
- Set up Remote Desktop

<h2>Deployment and Configuration Steps</h2>

<p>All you need to start this project is the Azure Tenant and Subcription. Get logged in to the Azure Portal.</p>

<h3>
Create a Resource Group
</h3>
<p>
  <img src="https://github.com/user-attachments/assets/f6c8f4c9-d2f5-44dd-9457-706c1814755b" height="80%" width="80%"/>
</p>

<br>
<h3>Create a Windows 10 Virtual Machine (VM)</h3>
<p>While creating the VM, select the previously created Resource Group. For the size, select something with at least 2vcpus. </p>
<p><b>*Open a notepad and take note of the usernames and passwords you create*</b></p>
<p>
  <img src="https://github.com/user-attachments/assets/f7f67eed-102d-4522-b8f6-a35bfc236fea" height="80%" width="80%"/>
</p>

<br>
<p>
  While creating the VM, allow it to create a new Virtual Network (Vnet) and Subnet.
<p>
  <img src="https://github.com/user-attachments/assets/aaf4bf8e-9576-41f6-a02a-12416e040712" height="80%" width="80%"/>
</p>

<br>
<h3>Create a Linux (Ubuntu) VM</h3>
<p>While creating the VM, select the previously created Resource Group and Vnet
</p>
<p>
  <img src="https://github.com/user-attachments/assets/702237df-603f-4026-9b22-c861fee9c350" height="80%" width="80%"/>
</p>

<br>
<p>While creating the VM, select "password" for authentication type.
</p>
<p>
  <img src="https://github.com/user-attachments/assets/0f260ee4-058a-46d8-aeab-7b66229fbca4" height="80%" width="80%"/>
</p>

<br>
<p>While creating the VM, select "Lab2-Vnet" for Virtual Network.
</p>
<p>
  <img src="https://github.com/user-attachments/assets/56ba70d4-3e42-418d-957c-de88f4dabfa4" height="80%" width="80%"/>
</p>

<br>
<h3>Observe Your Virtual Network within Network Watcher</h3>
<p>Ensure both VMs are in the same Virtual Network / Subnet by navigating to "Virtual Machines"</p>
<p>
  <img src="https://github.com/user-attachments/assets/398d1fc0-1257-48d3-82be-604b5b313864" height="80%" width="80%"/>
</p>

<br>
<p>Click on "linux-vm" to observe the Virtual Network / Subnet it is assigned to.</p>
<p>
  <img src="https://github.com/user-attachments/assets/385215f2-26e2-43dc-9524-708dc53fa50f" height="80%" width="80%"/>
</p>

<br>
<p>Then, do the same for "windows-vm"</p>
<p>
  <img src="https://github.com/user-attachments/assets/db55e41e-011f-446e-b014-a640caa66ca6" height="80%" width="80%"/>
</p>

<br>
<h3>Use Remote Desktop to connect to your Windows 10 Virtual Machine</h3>
<p>If using Mac, install Windows App (Previously, Microsoft Remote Desktop)</p>
<p>
  <img src="https://github.com/user-attachments/assets/03a223d4-9abe-4e45-b0b7-e620a4cd78da" height="80%" width="80%"/>
</p>

<br>
<p>Copy the Public IP address for windows-vm</p>
<p>
  <img src="https://github.com/user-attachments/assets/b0dc3fce-69c8-4347-a29b-46f5db79d1b2" height="80%" width="80%"/>
</p>

<br>
<p>Open the Windows App, click add PC at the top right corner, paste the IP address here and make sure to name it.</p>
<p>
  <img src="https://github.com/user-attachments/assets/17f0b014-8b5f-4899-aa7b-689ceb7c2809" height="80%" width="80%"/>
</p>

<br>
<p>Log in using the username and password you created.</p>
<p>
  <img src="https://github.com/user-attachments/assets/ac4417ec-a234-425f-9663-8326b43e0e36" height="80%" width="80%"/>
</p>
