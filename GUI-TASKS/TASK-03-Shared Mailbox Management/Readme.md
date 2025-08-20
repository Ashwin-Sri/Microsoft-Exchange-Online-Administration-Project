# Task 03 – Shared Mailbox Management

## Shared Mailbox

A Shared Mailbox in Microsoft 365 (Exchange Online) is a mailbox that multiple users can access to send and receive emails from a common address. It allows a team or group to manage emails collectively without needing to create separate user accounts.

---

## Objective
Configure and validate **Shared Mailboxes** in Exchange Online using the Exchange Admin Center (EAC).  
Covers mailbox creation, permission assignment, access validation, and mail flow testing.

---

## Steps Performed

1. Signed into **Exchange Admin Center (EAC)** → **Recipients** → **Mailboxes** → **Shared**.
2. Created a **new shared mailbox** with a display name and email address.
3. Assigned **Full Access** and **Send As** permissions to delegated users.
     
     <img width="1555" height="801" alt="image" src="https://github.com/user-attachments/assets/b981ce62-97cd-45d4-a337-edba1b9ac195" />

     <img width="737" height="790" alt="image" src="https://github.com/user-attachments/assets/804c086d-214c-42f7-9663-177eccc1e195" />

4. Verified mailbox availability:
   - Delegated user logged into **Outlook Web App (OWA)** and accessed the shared mailbox.
   - Sent a test email from the shared mailbox to confirm *Send As* worked.
   - Received a test email in the shared mailbox to confirm mail flow.

---

## Validation Outcomes

| Validation Item         | Result |
|--------------------------|--------|
| Shared mailbox created   | ✅ Visible in EAC → Mailboxes → Shared |
| Full Access permissions  | ✅ Delegated user opened mailbox in OWA |
| Send As functionality    | ✅ Delegated user sent email as shared mailbox |
| Mail flow test           | ✅ Emails received in shared mailbox without issue |

---

## Conclusion
Shared mailbox lifecycle tasks — provisioning, permissions, and functionality validation — were successfully performed in the Exchange Admin Center.  
This demonstrates real-world delegation and shared access scenarios in Exchange Online.
