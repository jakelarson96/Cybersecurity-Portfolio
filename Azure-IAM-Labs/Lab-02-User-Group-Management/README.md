# Lab 02 – Entra ID Group-Based Licensing

## 🎯 Objective
Demonstrate group-based licensing in Microsoft Entra ID by assigning and removing Microsoft 365 licenses through security group membership and observing inheritance behavior.

---

## 👥 HR Group – License Assignment
The Human Resources group was assigned a Microsoft Entra ID P2 license.

📸 Screenshot:
![HR License Assigned](screenshots/hr-license-queued.png)
<img width="3839" height="2176" alt="michael-smith-license-inherited" src="https://github.com/user-attachments/assets/40f45d2a-338e-4e00-8f94-9205b7553816" />
<img width="3839" height="2184" alt="hr-license-queued" src="https://github.com/user-attachments/assets/1e620606-ebdb-44e1-8cb9-88be920bc54a" />

---

## 👤 User License Inheritance (Michael Smith)
Michael Smith inherited the P2 license through membership in the Human Resources group, demonstrating group-based license assignment.

📸 Screenshot:
![Michael Smith License Inherited](screenshots/michael-smith-license-inherited.png)
![Uploading michael-smith-license-inherited.png…]()

---

## 👥 Finance Group Membership
The Finance group contains the following users:
- Gary Finance
- Michael Smith

📸 Screenshot:
![Finance Group Members](screenshots/finance-group-members.png)
<img width="3839" height="2178" alt="finance-group-members" src="https://github.com/user-attachments/assets/88679966-de7c-479b-842d-6f143ad3baef" />

---

## 👤 License Verification (Michael Smith)
Verification of Michael Smith’s assigned P2 license through group inheritance.

📸 Screenshot:
![Michael Smith License Verification](screenshots/michael-smith-license-verification.png)
<img width="3839" height="2174" alt="michael-smith-license-verification" src="https://github.com/user-attachments/assets/bb1991a5-353e-4699-a218-078c2aebc62a" />

---

## 👥 HR Group Membership
Human Resources group members:
- Sandy HR

📸 Screenshot:
![HR Group Members](screenshots/hr-group-members.png)
<img width="3839" height="2174" alt="hr-group-members" src="https://github.com/user-attachments/assets/a5f4efa5-8827-4333-9e9a-c874d449e0ed" />

---

## 🚫 User Account Disabled (Michael Smith)
Michael Smith’s account status was changed to disabled, removing active access.

📸 Screenshot:
![Account Disabled](screenshots/michael-smith-disabled.png)
<img width="3839" height="2170" alt="michael-smith-disabled" src="https://github.com/user-attachments/assets/29201ec0-e946-45f0-a337-709f0a7bdcc5" />

---

## 👥 Group Removal
Michael Smith was removed from all assigned groups.

📸 Screenshot:
![Groups Removed](screenshots/michael-smith-no-groups.png)
<img width="3839" height="2170" alt="michael-smith-no-groups" src="https://github.com/user-attachments/assets/d8556a3f-fead-4660-9591-3cf58c5e3d50" />

---

## ❌ License Removal
After removal from group membership, Michael Smith’s inherited license was removed due to group-based licensing dependency.

📸 Screenshot:
![Licenses Removed](screenshots/michael-smith-no-licenses.png)
<img width="3839" height="2176" alt="michael-smith-no-licenses" src="https://github.com/user-attachments/assets/27d5a56e-72bd-449f-a9f7-9a8838cbaf77" />

---

## 🧠 Outcome
- Demonstrated group-based license assignment in Entra ID  
- Showed inheritance of Microsoft 365 licenses through group membership  
- Verified automatic license removal upon group removal  
- Observed impact of account disabling on access and licensing  
