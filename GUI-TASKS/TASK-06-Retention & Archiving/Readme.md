# Task 06 – Retention & Archiving

## Objective
Enable and manage in-place archiving and retention policies in Exchange Online to support mailbox management and organizational compliance.

## Key Concepts
- **In-Place Archiving** – Provides a secondary mailbox for storing older emails, reducing primary mailbox clutter.  
- **Retention Policies** – Define rules to retain or delete emails automatically based on organizational or regulatory requirements.  

## Validation Steps
1. Sign in to **M365 Admin Center → Microsoft Purview (Data Lifecycle Management) → Retention Policies**.  
2. Create a new **Retention Policy** or modify an existing one.  

      <img width="1853" height="846" alt="image" src="https://github.com/user-attachments/assets/ffb2b5f3-0e67-4a0d-9388-8fd31a51de93" />

4. Define retention settings (e.g., Retain for 3 years then delete, or Move to archive after 1 year). 

      <img width="1582" height="848" alt="image" src="https://github.com/user-attachments/assets/5678cfca-5253-41c6-8d9b-5b67e35c50c4" />
 
5. Apply the retention policy to the target mailbox(es).  
6. Navigate to **Recipients → Mailboxes** and ensure the mailbox has **In-Place Archiving** enabled.  
      
      <img width="1558" height="707" alt="image" src="https://github.com/user-attachments/assets/fbce7465-f9d7-4f73-8c1a-9a4f63bdf81b" />

7. Verify that the archive mailbox is accessible in **Outlook Web or Desktop**. 

      <img width="338" height="807" alt="image" src="https://github.com/user-attachments/assets/d8ba13e8-da3b-4f23-bfdf-7394b9b1c41e" />
    
8. Test the policy by moving emails to meet the retention rules or waiting for automatic processing to ensure emails are archived or deleted as configured.  

## Expected Outcome
- Target mailboxes have in-place archiving enabled.  
- Old emails automatically move to the archive mailbox if enabled, or are deleted once the retention period expires.  
- Mailbox management and compliance are maintained according to organizational standards.

---

Note: Microsoft has moved all data retention and lifecycle management features (including Exchange email retention, labels, and policies) from the Security & Compliance Center to the Microsoft Purview portal.
