# Purpose

The purpose of this lab is to demonstrate competency within OS Ticket and troubleshooting common Active Directory issues.

<ins>Examples Included:</ins>
- User Creation
- File Sharing
- GPO Update
- Account/Authentication Issues
 - Network Issues
# Specifications

| Type | Specifications |
| ------------- | ------------- |
| OS | Windows Server 2025 |
| Memory | 4096MB |
| CPU | 4 Cores |
| Drive | 50GB |
| Network | NAT & Internal |

| Type | Specifications |
| ------------- | ------------- |
| OS | Windows 11 Pro |
| Memory | 4096MB |
| CPU | 4 Cores |
| Drive | 64GB |
| Network | Internal |

| Type | Specifications |
| ------------- | ------------- |
| OS | Windows 10 Pro |
| Memory | 8192MB |
| CPU | 2 Cores |
| Drive | 50GB |
| Network | NAT |

# User Creation

A new user has been hired in the Marketing Department. 

The first step is to assign the ticket to myself before I begin the process.
<img width="1051" height="399" alt="Screenshot 2026-10-07 135714" src="https://github.com/user-attachments/assets/fce78cea-19a4-4565-a28d-8dda538c8ed8" />

The ticket created by the HR Manager has asked us to create a new user, Noel Smith, and give them Read and Write to the Marketing Drive Folder with read and Write Access.
<img width="934" height="292" alt="Screenshot 2026-10-07 135959" src="https://github.com/user-attachments/assets/b5f7a87c-4664-4bbc-951e-5b623f85c54d" />

In Windows Server 2025, navigate to **Tools>Active Directory Users and Computers>Marketing**

In this example, there are no users, but in a real environment there are users.

<img width="779" height="436" alt="image" src="https://github.com/user-attachments/assets/3f520ba7-dcde-48ab-bd1e-a5ecf39c3f8b" />


Now create the user with credentials, according to company policy. For this example, the user login is "(first letter of first name)(lastname)@corp.local)"

<img width="620" height="525" alt="Screenshot 2026-10-07 141844" src="https://github.com/user-attachments/assets/4cb4ba61-f5ca-4795-a0ff-a4aeb8f48a3d" />

Next, assign them an easy password to login and click on the box "User must change password at next logon".

<img width="602" height="507" alt="Screenshot 2026-10-07 142343" src="https://github.com/user-attachments/assets/94db7b1d-d9c4-4d2b-ae3c-2bae5a7205d0" />

After we created the user, we must add them to their respective Security group. Right-click on the user and navigate to **Properties>Member Of>Add...**

<img width="676" height="495" alt="Screenshot 2026-10-07 143050" src="https://github.com/user-attachments/assets/6ee85eef-e51d-451c-bc51-46354f94e5fe" />

Type in the "Enter the object names to select box" the security group they are assigned to.

<img width="622" height="329" alt="Screenshot 2026-10-07 143208" src="https://github.com/user-attachments/assets/89186bd4-696a-4e64-97fc-8212ff707d16" />


Afterwards, select **Check Names>OK>Apply>OK**

<img width="603" height="728" alt="Screenshot 2026-10-07 143335" src="https://github.com/user-attachments/assets/9c40f44f-2b28-4b00-8b4b-bbefc96f5cfc" />

You have now created a new user!

# File Sharing


