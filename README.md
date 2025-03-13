<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Creating Virtual Machines (Azure)</h1>
This tutorial outlines the implementation of Virtual Machines within Azure.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Create a Resource Group
- Create a Windows 10 Virtual Machine (VM)
- Create a Linux (Ubuntu) VM
- Observe Your Virtual Network within Network Watcher

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
