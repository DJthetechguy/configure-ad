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
- Deploy Client VM and Configure DNS
- Deploy Domain Controller VM and Assign Static IP
- Join Client VM to Active Directory Domain

<h2>Deployment and Configuration Steps</h2>

<p>
<img width="1920" height="977" alt="image" src="https://github.com/user-attachments/assets/0d865f06-1609-4cc7-9144-5bb2dac81961" />

</p>
This screenshot displays the Azure portal interface where the resource group and network for the Active Directory deployment have been successfully created. The resource group acts as a container for managing related Azure resources, providing a centralized location for organization and access control. The configuration details, such as the resource group name, location, and virtual network address space, are visible, demonstrating the initial steps taken to establish the infrastructure for the lab environment.
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
<img width="1920" height="970" alt="image" src="https://github.com/user-attachments/assets/8cdbe28e-b38c-4709-b8a5-e89ed3cbcbd3" />


</p>
<p>
This screenshot highlights the DNS configuration settings for the client virtual machine in the Azure portal. It shows the specified DNS server settings, with the client VM pointing to the static private IP address of the domain controller. This configuration is essential for enabling the client VM to successfully resolve domain names and communicate with the Active Directory services hosted on the domain controller, ensuring seamless integration within the network.
</p>
<br />

<p>
<img width="1920" height="974" alt="image" src="https://github.com/user-attachments/assets/cd14cbaf-833e-4c57-8364-f3fb303f9ae9" />


</p>
<p>
This screenshot captures the process of joining the client virtual machine to the Active Directory domain in the Azure environment. It displays the system settings where the user initiates the domain join by entering the domain name, which corresponds to the domain controller’s configuration. Confirmation messages indicate the successful connection to the domain, along with prompts to enter domain credentials if necessary. This process is crucial for integrating the client into the directory services, granting access to resources and enabling centralized management of user accounts and permissions within the network.
</p>
<br />
