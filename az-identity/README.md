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

Located in the `screenshots/` folder:

- `users-list.png` – List of created users
- `user-details.png` – Details of a single user
- `groups-list.png` – Security groups overview
- `group-members-appreaders.png` – Members of AppReaders group
- `group-members-vmcontributors.png` – Members of VMContributors group
- `role-assignment-appreaders.png` – RBAC assignment for AppReaders
- `role-assignment-vmcontributors.png` – RBAC assignment for VMContributors
- `resource-group-context.png` – Target resource group for role assignment
- `first-login-password-change.png` – First login password change prompt
- `mfa-prompt.png` – Microsoft Authenticator prompt at login

---

## 🧠 Learnings

- Users and groups in Entra ID are used for identity management only
- Azure resource access is controlled using RBAC, not Entra ID roles
- Assigning RBAC to groups simplifies permission management
- MFA can block test logins due to default security settings


