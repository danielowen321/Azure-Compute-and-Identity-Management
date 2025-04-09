<h1>Azure Compute and Identity Management</h1>

<h2>Description</h2>
This project involves deploying a virtual machine, securing it using RBAC,
applying Azure Policies for resource governance, encrypting sensitive data,
and monitoring costs. It teaches foundational concepts for managing Azure identities, governance, and compute resources.
<br />
<br />
<h2>Scenario</h2>
A company wants to deploy a virtual machine for their web application, secure it with role-based access control,
enforce a policy for naming conventions, encrypt sensitive data, and monitor the cost of the deployed resources.
<br />
<br />

<h2>Utilities Used</h2>

- <b>VMs</b>
- <b>RBAC</b>
- <b>Policies</b>
- <b>Encryption</b>
- <b>Cost Management</b>
- <b>Azure AD</b>
<br />
<br />


<h2>Environments Used </h2>

- <b>Microsoft Azure</b>
<br />
<br />


<h2>I have included images of the project below:</h2>

<p align="center">
1. Create a Virtual Machine
    - Go to Azure Portal > Virtual Machines > Create.
    - Select subscription, resource group, region, VM size, and OS (Windows/Linux).
    - Configure an admin username/password or SSH key.
    - Add a data disk during creation.
        - Create a new disk > None.
        - If you select Storage Blob, this allows you to reuse disks from outside Azure or custom configurations you uploaded..  <br/>
<img src="https://imgur.com/Zq4eSom.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
I created a user account "PC1", from there I was able to successfully ping my Active Directory server at 192.168.20.10 which verified they were connected on the same network<br/>
<img src="https://imgur.com/pufsLxn.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
Assigning a static IP address for my user account "PC1" and allocating the preferred DNS server to 192.168.20.10 (AD Domain Controller) <br/>
<img src="https://imgur.com/V7gtZYq.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
 <br/> 
 Accessing user "PC1" via remote desktop<br/>
<img src="https://imgur.com/HBIjkah.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
Here I used a PowerShell script which gathered information on the amount of computers, workstations, servers, users and groups<br/>
 <img src="https://imgur.com/my3YCdm.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
