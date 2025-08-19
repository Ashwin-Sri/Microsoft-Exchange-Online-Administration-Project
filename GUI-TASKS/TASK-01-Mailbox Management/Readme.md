# Task 01- Validated Artifact – Mailbox Management via Exchange Admin Center 

##  Objective
Perform mailbox lifecycle management in Exchange Online using the Exchange Admin Center (EAC).  
This includes creating a new user mailbox, modifying mailbox settings, validating access, and disabling the mailbox.  
Scope executed under **Exchange Online Plan 1** licensing.

---

##  Steps Performed

1. Signed into **Microsoft 365 Admin Center** with **Exchange Administrator** role.
2. Navigated to **Exchange Admin Center** → **Recipients** → **Mailboxes**.
3. Created a new user mailbox by:
   - Adding a user in Microsoft 365 Admin Center.
   - Assigning a license that includes **Exchange Online Plan 1**.
4. Verified the mailbox appeared under Recipients in EAC.

    <img width="1846" height="825" alt="image" src="https://github.com/user-attachments/assets/60556268-af97-47c9-8004-80e8fbf6530c" />
   
6. Modified mailbox settings:
   - Updated **display name**
   - Added an **email alias**
   - Reviewed **mailbox quota** (default applied)

    <img width="1532" height="795" alt="image" src="https://github.com/user-attachments/assets/62fafccc-7221-49cb-bdb6-0b40ebfee82e" />
    <img width="685" height="747" alt="image" src="https://github.com/user-attachments/assets/0796e3c8-f195-49c7-aa75-2282a0826d06" />

7. Logged into **Outlook on the web (OWA)** with the new account.
   - Sent and received test emails to confirm mail flow.
8. Disabled the mailbox by removing the license.
   - Confirmed mailbox was no longer accessible via login or mail flow.
    <img width="815" height="750" alt="image" src="https://github.com/user-attachments/assets/29ea12d1-aa8d-488b-a5d4-91fd6931e690" />
    <img width="1467" height="712" alt="image" src="https://github.com/user-attachments/assets/7a410914-7460-4737-985c-aa01806f1247" />

---

##  Validation Outcomes

| Validation Item | Result |
|-----------------|--------|
| Mailbox provisioning | ✅ Visible in Exchange Admin Center |
| OWA login | ✅ Successful after password reset |
| Mail flow test | ✅ Emails sent and received without error |
| Display name and alias | ✅ Reflected correctly in mailbox properties |
| Mailbox disablement | ✅ Login blocked and mailbox removed from EAC |

---

##  Role & Licensing Notes

- **Role Required**: Exchange Administrator or Global Administrator  
- **License Used**: Microsoft 365 license with **Exchange Online Plan 1**  
- **Scope**: User mailbox lifecycle only (shared/resource mailboxes not included)

---

##  Conclusion

Mailbox lifecycle management was successfully validated in Exchange Admin Center.  
The process covered provisioning, modification, access testing, and deprovisioning, reflecting standard Exchange Online administration practices applicable to Microsoft 365 environments.
