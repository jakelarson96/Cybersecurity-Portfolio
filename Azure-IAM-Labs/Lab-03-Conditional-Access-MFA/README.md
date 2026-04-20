# Lab 03 – Conditional Access & Multi-Factor Authentication (MFA)

## 🎯 Objective
Configure Conditional Access policies in Microsoft Entra ID to enforce Multi-Factor Authentication (MFA) and block legacy authentication for improved security.

---

## 🔐 Policy 1 – Require MFA for Finance Group

A Conditional Access policy was created targeting the Finance group to require MFA for access.

### Configuration:
- Users: Finance Group  
- Target Resources: All cloud apps  
- Grant Control: Require Multi-Factor Authentication  

📸 Screenshot:
![Finance Group Selected](screenshots/mfa-policy-users.png)
<img width="3839" height="2172" alt="mfa-policy-users" src="https://github.com/user-attachments/assets/34ac2393-74e1-47fd-a460-bcff8f841872" />

📸 Screenshot:
![All Cloud Apps](screenshots/mfa-policy-resources.png)
<img width="3839" height="2170" alt="mfa-policy-resources" src="https://github.com/user-attachments/assets/00d8a246-8333-4284-8dcf-470a1649ee84" />

📸 Screenshot:
![Require MFA](screenshots/mfa-policy-grant.png)
<img width="3839" height="2173" alt="mfa-policy-grant" src="https://github.com/user-attachments/assets/2f7d822c-8e09-4b9d-bf79-6edf4bf74e89" />

---

## ✅ Policy Enabled

The “Require MFA for Finance” policy was successfully created and enabled.

📸 Screenshot:
![MFA Policy Enabled](screenshots/mfa-policy-enabled.png)
<img width="3839" height="2184" alt="mfa-policy-enabled" src="https://github.com/user-attachments/assets/14dd691b-3fff-461b-bbfc-701745aa4d78" />

---

## 🚫 Policy 2 – Block Legacy Authentication

A second Conditional Access policy was created to block legacy authentication for the Finance group.

### Configuration:
- Users: Finance Group  
- Target Resources: All cloud apps  
- Grant Control: Block access  

📸 Screenshot:
![Finance Group Selected](screenshots/block-legacy-users.png)
<img width="3839" height="2175" alt="block-legacy-users" src="https://github.com/user-attachments/assets/3cf5d0f6-4522-4d5e-b0dc-34fd8e8a820d" />

📸 Screenshot:
![All Cloud Apps](screenshots/block-legacy-resources.png)
<img width="3839" height="2175" alt="block-legacy-resources" src="https://github.com/user-attachments/assets/729c23c2-8325-462c-a62c-8548dd400e3b" />

📸 Screenshot:
![Block Access](screenshots/block-legacy-block.png)
<img width="3834" height="2177" alt="block-legacy-block" src="https://github.com/user-attachments/assets/ced0489b-e4f4-487e-a3c2-3e3cda2f0147" />

---

## ✅ Policy Enabled

The “Block Legacy Authentication” policy was successfully enabled.

📸 Screenshot:
![Legacy Policy Enabled](screenshots/block-legacy-enabled.png)
<img width="3836" height="2177" alt="block-legacy-enabled" src="https://github.com/user-attachments/assets/822917bc-8f36-490e-9c1d-9b13878dd25b" />

---

## 🧪 Testing – User Sign-In (Gary Finance)

A test login was performed using a Finance user to validate the policies.

📸 Screenshot:
![Gary Login](screenshots/gary-login.png)
<img width="3832" height="2152" alt="gary-login" src="https://github.com/user-attachments/assets/3ea49180-e7c8-4aad-8bdf-6c6c0d858ded" />

---

## 🔒 MFA Enforcement

The user was prompted to configure Microsoft Authenticator, confirming MFA enforcement.

📸 Screenshot:
![MFA Prompt](screenshots/mfa-prompt.png)
<img width="3839" height="2155" alt="mfa-prompt" src="https://github.com/user-attachments/assets/51407716-8676-4ded-b975-512459e2d79e" />

---

## 🧠 Outcome
- Configured Conditional Access policies in Entra ID  
- Enforced MFA for a specific user group  
- Blocked legacy authentication methods  
- Validated policy enforcement through real user login testing  
