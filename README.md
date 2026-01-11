<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Create Azure Resource Group and Virtual Network
- Deploy Domain Controller VM and Assign Static IP
- Deploy Client VM and Configure DNS
- Join Client VM to Active Directory Domain

<h2>Deployment and Configuration Steps</h2>

<p>
<img width="1920" height="977" alt="image" src="https://github.com/user-attachments/assets/0d865f06-1609-4cc7-9144-5bb2dac81961" />

</p>
This screenshot displays the Azure portal interface where the resource group for the Active Directory deployment have been successfully created. The resource group acts as a container for managing related Azure resources, providing a centralized location for organization and access control. 
</p>
<br />

<p>
<img width="1920" height="944" alt="image" src="https://github.com/user-attachments/assets/efe32fa6-361e-4399-b7ba-d4d7772853ed" />

</p>
<p>
Here displays the completion of the virtual network being successfully completed. The virtual network facilitates secure communication between all deployed resources within the group, ensuring that the domain controller and client VMs can interact seamlessly. The configuration details, such as the resource group name, location, and virtual network address space, are visible, demonstrating the initial steps taken to establish the infrastructure for the lab environment.
</p>
<br />

<p>
<img width="1920" height="974" alt="image" src="https://github.com/user-attachments/assets/b1ef1525-2541-4acc-a676-bb8a5d4a5022" />

</p>
<p>
This screenshot showcases the Azure portal displaying the deployment details of the Windows Server virtual machine, configured to act as the domain controller. Key information includes the VM name, resource group, type, status, and operation specifications. The configuration settings confirm that the VM is ready for deployment, establishing the foundation for Active Directory services in the Azure environment.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
