# Azure / Microsoft Entra ID IAM Foundation Lab (Beginner)

This repo documents a hands-on Identity & Access Management (IAM) lab built in **Microsoft Azure** using **Microsoft Entra ID**.

## What I built

- Created security groups for departments (**IT-Admins**, **HR-Users**, **Finance-Users**, **Sales-Users**)
- Created internal users and assigned them to the correct groups
- Assigned an administrative role (**User Administrator**) to an IT admin account
- Enabled **Security Defaults** to enforce MFA enrollment
- Tested first sign-in in a private/incognito session and completed **Microsoft Authenticator** setup
- Captured evidence (screenshots) and documented steps

> Note: Screenshots in this repo are **redacted** (tenant/email + MFA QR/code removed) so they’re safe to publish.

## Azure Entra ID

<img width="519" height="81" alt="Screenshot 2026-01-08 210202" src="https://github.com/user-attachments/assets/bf5df2d5-3002-42c4-8b24-fb9444fdfcb9" />


## Evidence (Screenshots)

- Groups created: ![Groups](screenshots/01-groups-all.png)
- User creation: ![Create user](screenshots/02-create-user.png)
- Users list: ![Users](screenshots/03-users-all.png)
- IT admin group membership: ![IT Admins](screenshots/04-it-admins-members.png)
- Role assignment (User Administrator): ![Role](screenshots/10-user-admin-role-assignments.png)
- Security defaults enabled: ![Security defaults](screenshots/11-security-defaults-enabled.png)
- MFA enrollment flow:  
  ![MFA](screenshots/12-mfa-keep-account-secure.png)  
  ![MFA install](screenshots/13-mfa-install-authenticator.png)  
  ![MFA number match](screenshots/16-mfa-number-match.png)  
  ![MFA added](screenshots/17-mfa-authenticator-added.png)

## Documentation

- **Build steps:** `docs/build-steps.md`
- **Troubleshooting notes:** `docs/troubleshooting.md`
- **Lessons learned:** `docs/lessons-learned.md`

## Skills demonstrated

**IAM / Identity**
- Microsoft Entra ID user & group management
- Role-Based Access Control (RBAC) / Admin role assignment
- MFA onboarding using Microsoft Authenticator (Security Defaults)

**Operations**
- Documentation + evidence capture
- Access troubleshooting mindset (first sign-in, password change, MFA enrollment)
