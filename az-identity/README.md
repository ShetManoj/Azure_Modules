# 🔐 Module: Administer Identity 

This module covers user and group management in Microsoft Entra ID (Azure AD), and role-based access control (RBAC) in Azure.

---

## ✅ Tasks Performed

- Created 6 Azure AD users manually
- Created 2 security groups: `AppReaders` and `VMContributors`
- Added 3 users to each group
- Assigned:
  - **Reader** role to `AppReaders`
  - **Virtual Machine Contributor** role to `VMContributors`
- Attempted login as test users and encountered Microsoft Authenticator prompt
- Understood impact of Security Defaults on MFA behavior

---

## 📸 Screenshots

- ![Users List](./screenshots/users-list.PNG)
- ![User Details](./screenshots/user-details.PNG)
- ![Groups List](./screenshots/groups-list.PNG)
- ![AppReaders Members](./screenshots/group-members-appreaders.PNG)
- ![VMContributors Members](./screenshots/group-members-vmcontributors.PNG)
- ![RBAC AppReaders](./screenshots/role-assignment-appreaders.PNG)
- ![RBAC VMContributors](./screenshots/role-assignment-vmcontributors.PNG)
- ![Resource Group Context](./screenshots/resource-group-context.PNG)
- ![First Login Password Change](./screenshots/first-login-password-change.png.PNG)
- ![MFA Prompt](./screenshots/mfa-prompt.PNG)


---

## 🧠 Learnings

- Users and groups in Entra ID are used for identity management only
- Azure resource access is controlled using RBAC, not Entra ID roles
- Assigning RBAC to groups simplifies permission management
- MFA can block test logins due to default security settings


