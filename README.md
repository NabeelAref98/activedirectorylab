# Active Directory Main Functionalities
<h2>What is 'Active Directory?'</h2>
Active Directory is a centralized location 
within a server. It stores login credentials for accessing a
computer. Login credentials consist of a login ID and
password. Active Directory is accessed through the Windows
Server interface. Login IDs and passwords are used to log into
computers controlled by Active Directory
</br>
</br>
</br>


![1](https://github.com/NabeelAref98/activedirectorylab/assets/140019096/7e9edcea-b810-49bc-abc5-6e4976821995)

First, we will start by locating the Active Directory tool specifically the 'Active Directory Users and Computers' in the start menu. This tool is found under the start folder 'Windows Administrative tools'.

![2](https://github.com/NabeelAref98/activedirectorylab/assets/140019096/862ad449-efe7-4758-8d30-8a027f4088f3)

This is the application window and what it would normally be like. Users are organized into folders within Active Directory. Folders can represent departments or user groups.

![image](https://github.com/NabeelAref98/activedirectorylab/assets/140019096/440b517c-f5fc-4da2-9e5c-9401709ffa9c)


Each user has a login ID and password stored within their respective folder. Organizing users allows for better management of
access permissions. Specific access permissions can be set based on user groups or departments.

![image](https://github.com/NabeelAref98/activedirectorylab/assets/140019096/42c57e3c-0b2a-42fb-a252-40afb1dcf33e)

Upon creating a new user, a temporary password can be assigned, forcing users to change them upon login.

![image](https://github.com/NabeelAref98/activedirectorylab/assets/140019096/5975b7f6-6441-4a37-b321-3f204053823d)


Administrators can reset passwords for users in Active Directory. Password resets help users regain access to their accounts.

![image](https://github.com/NabeelAref98/activedirectorylab/assets/140019096/4f1a48a9-6fd8-4118-9525-dde7682c4e32)

User groups are created to group users with similar access permissions. User groups can represent departments, roles, or projects. Users are added to their respective user groups within Active Directory.

![image](https://github.com/NabeelAref98/activedirectorylab/assets/140019096/6ca5a5fa-f987-4c09-83e7-d3018d96e13c)

Assigning users to user groups ensures consistent access permissions. User groups streamline access management for administrators.


<h2>Here are some common issues that can be handled with Active Directory</h2>

DNS Configuration Problems: Active Directory relies on proper DNS configuration. Misconfigurations can lead to issues with domain name resolution, affecting communication between devices on the network. By correcting the DNS settings in Active Directory, these issues can be resolved.

Active Directory Replication Problems: Changes made on one domain controller (like adding a new user) may not get replicated to other domain controllers, leading to inconsistencies. Active Directory provides tools to troubleshoot and fix replication errors.

Security Issues: Active Directory is key in managing credentials and permissions in the IT infrastructure. Frequent invalid user accesses, account lockouts, permission errors, etc., can be tracked and fixed using Active Directory.

Group Policy Issues: Sometimes, Group Policies may not apply correctly or may cause unexpected behavior on client computers. Active Directory allows administrators to troubleshoot and modify these policies as needed.

User Account Lockouts: Frequent account lockouts can be a significant issue in large organizations. Active Directory provides tools to identify the source of the lockouts and resolve them.

Logon Failures: Logon failures can occur due to various reasons like incorrect credentials, account lockouts, etc. Active Directory helps in diagnosing the cause of these failures and fixing them.
