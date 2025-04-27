<center>

![AD](./Configuring%20On-premises%20Active%20Directory%20within%20Azure%20VMs/assets/Active-Directory.png)

</center>

# On-premises Active Directory Deployed in the Cloud (Azure)
Active Directory centrally manages thousands of user accounts in a single place (accounts, passwords and permissions) as well as manage devices on a large scale.
This Section outlines the implementation of on-premises Active Directory within Azure Virtual Machines, as well as how to add capabilities such as Group Policy Objects, Network File Shares, and Domain Name System.

<br />

| Terms | Descriptions|
|-------| ------------|
| Resource Group | is a container that holds related resources for an Azure solution. The resource group can include all the resources for the solution, or only those resources that you want to manage as a group.
| Virtual Machine | is a digital version of a physical computer. Virtual machine software can run programs and operating systems, store data, connect to networks, and do other computing functions, and requires maintenance such as updates and system monitoring
| Remote Desktop | Remote desktop is the ability to connect with and use a faraway desktop computer from a separate computer. Remote desktop users can access their desktop, open and edit files, and use applications as if they were actually sitting at their desktop computer.
| Active Directory Domain Services | are the core functions in Active Directory that manage users and computers and allow sysadmins to organize the data into logical hierarchies.
| Powershell |  is a cross-platform task automation solution made up of a command-line shell, a scripting language, and a configuration management framework. PowerShell runs on Windows, Linux, and macOS.
| Domain Controller |  are the servers in your network that host AD DS. DCs respond to authentication requests and store AD DS data
|Organizational Unit (OU) | Organizational units (OUs) in an Active Directory Domain Services (AD DS) managed domain let you logically group objects such as user accounts, service accounts, or computer accounts. You can then assign administrators to specific OUs, and apply group policy to enforce targeted configuration settings.
|Join Client to Domain | Joining a computer to a domain means connecting that computer to a network that is managed by a centralized server known as a domain controller. A domain is a logical grouping of computers, users, and resources that can be managed centrally by a network administrator. Overall, joining a computer to a domain helps to improve security, simplify network management, and increase productivity. |
| Domain Name System (DNS) | DNS is the name service for Internet addresses that translates friendly domain names to numeric Internet Protocol (IP) addresses. |
|Network File Shares | Network file shares allow computers on a network to access files and folders on another computer, and permissions control who can access them and what they can do. |
|Group Policy Object (GPO) | Tool used in Microsoft Windows Active Directory to manage and standardize settings for computers and users within an organization. Essentially, GPOs are a collection of policies that define how a system will behave and what it will look like for specific groups of users or computers. |

<h2>Table of Contents</h2>

1.  [Configuring On-premises Active Directory within Azure VMs](Configuring%20On-premises%20Active%20Directory%20within%20Azure%20VMs/)

2.  [Networik File Shares and Permissions](Networik%20File%20Shares%20and%20Permissions/)

3.  [Domain Name System (DNS)](./Domain%20Name%20System%20(DNS)/)


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2> Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 Pro (21H2)

## Author

- [@AbdighaniMD](https://github.com/AbdighaniMD)



