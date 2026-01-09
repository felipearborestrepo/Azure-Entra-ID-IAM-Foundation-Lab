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

<img width="1356" height="608" alt="Screenshot 2026-01-08 210210" src="https://github.com/user-attachments/assets/a49ef005-a384-4ad5-9fc7-a82f66faaece" />

## Evidence (Screenshots)

## Groups created: 

<img width="224" height="122" alt="Screenshot 2026-01-08 210241" src="https://github.com/user-attachments/assets/827e122b-ff64-46af-ac4e-63eebd627e5a" />

<img width="151" height="46" alt="Screenshot 2026-01-08 210323" src="https://github.com/user-attachments/assets/5b1c6d82-d6ba-4448-8bf4-081b2c273de3" />

<img width="1358" height="602" alt="Screenshot 2026-01-08 210549" src="https://github.com/user-attachments/assets/5467f010-022b-4cc2-aec5-5280820ee1c2" />



## User creation:

<img width="355" height="183" alt="Screenshot 2026-01-08 211028" src="https://github.com/user-attachments/assets/c3094ef3-6342-4d29-9216-39bad6086896" />

<img width="840" height="597" alt="Screenshot 2026-01-08 210942" src="https://github.com/user-attachments/assets/2d57e092-a332-4ada-b2ab-35d3e948c4eb" />

## Users list: 

<img width="1364" height="602" alt="Screenshot 2026-01-08 211234" src="https://github.com/user-attachments/assets/0d0656f2-1fce-41b2-b8d1-105cbc1d3dc3" />

## IT admin group membership: 

<img width="423" height="135" alt="Screenshot 2026-01-08 211408" src="https://github.com/user-attachments/assets/2620fb20-831e-4931-9565-d9ecc0b32dcc" />

<img width="443" height="54" alt="Screenshot 2026-01-08 211423" src="https://github.com/user-attachments/assets/06a83ec2-977b-4dd0-a2b8-b2b2a6e17711" />

<img width="955" height="447" alt="Screenshot 2026-01-08 211501" src="https://github.com/user-attachments/assets/56e6734f-9140-42d3-85de-48402ea13c5f" />

<img width="950" height="520" alt="Screenshot 2026-01-08 211708" src="https://github.com/user-attachments/assets/3df20dd2-38cc-4e6e-a6c1-94a475835339" />

<img width="949" height="557" alt="Screenshot 2026-01-08 211802" src="https://github.com/user-attachments/assets/e43f223f-67c4-4518-8ae7-4fa94e4355c6" />

<img width="942" height="532" alt="Screenshot 2026-01-08 211901" src="https://github.com/user-attachments/assets/f949213c-d130-4afa-89d9-da3b41aed33a" />

## Role assignment (User Administrator): 

<img width="596" height="313" alt="Screenshot 2026-01-08 212012" src="https://github.com/user-attachments/assets/9237ca4a-3cfb-41f8-a626-e431215f365e" />

<img width="420" height="122" alt="Screenshot 2026-01-08 212029" src="https://github.com/user-attachments/assets/4a4752d2-2e81-457c-af05-76801678d72e" />

<img width="755" height="317" alt="Screenshot 2026-01-08 212051" src="https://github.com/user-attachments/assets/96f0d6a0-7b19-443e-86bd-dcf1692b7246" />

<img width="1359" height="605" alt="Screenshot 2026-01-08 212106" src="https://github.com/user-attachments/assets/5fdd6880-5f77-4e66-8ef5-a579e072ab6a" />

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
