# Lab 04 – Azure Role-Based Access Control (RBAC)

## Objective
Configure role-based access control (RBAC) in Azure to manage permissions at the resource group and resource level.

---

## Resource Group Created
A resource group (IAM-Lab-RG) was created to organize Azure resources.

Screenshot:
![Resource Group Overview](screenshots/resource-group-overview.png)
<img width="3839" height="2176" alt="resource-group-overview" src="https://github.com/user-attachments/assets/aa8ac2fb-3bb9-4d1c-99d2-434774ca0227" />

---

## Initial Role Assignments
Assigned roles to users:
- Jacob Larson → Owner  
- Gary Finance → Reader  

Screenshot:
![Initial RBAC Roles](screenshots/initial-rbac-roles.png)
<img width="3838" height="2176" alt="rbac-initial-roles" src="https://github.com/user-attachments/assets/63aeffb7-b148-49ec-8c3a-1651d961de5c" />

---

## Contributor Role Assignment
Assigned Contributor role to:
- John IT  

Screenshot:
![Contributor Assignment](screenshots/contributor-assignment.png)
<img width="3839" height="2181" alt="rbac-add-contributer" src="https://github.com/user-attachments/assets/29513376-8b94-4abb-92cf-4775b33713ba" />

---

## Group-Based RBAC
Assigned Contributor role to:
- IT Group  

Screenshot:
![Group RBAC](screenshots/group-rbac.png)
<img width="3839" height="2169" alt="rbac-group-contributer" src="https://github.com/user-attachments/assets/5612f5d2-d63a-4f78-89fc-f553bfec749b" />

---

## Resource-Level RBAC
Configured RBAC at the storage account level:
- Jacob Larson → Owner  
- John IT → Contributor  
- Gary Finance → Reader  

Screenshot:
![Storage RBAC](screenshots/storage-rbac.png)
<img width="3839" height="2068" alt="storage-rbac-roles" src="https://github.com/user-attachments/assets/348b0916-8c99-4747-ab92-a566df387ebb" />

---

## Resource Verification
Verified storage account exists within resource group.

Screenshot:
![Resource Group with Storage](screenshots/resource-group-storage.png)
<img width="3839" height="2177" alt="resource-group-storage" src="https://github.com/user-attachments/assets/6539ca42-37f5-43ef-952b-4b1f7695c3a5" />

---

## Outcome
- Implemented RBAC at resource group and resource level  
- Assigned least privilege roles  
- Demonstrated both user and group-based access control  
