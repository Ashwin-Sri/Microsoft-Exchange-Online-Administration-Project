# Task 04 – Permissions & Delegation

---

## Objective
Manage mailbox access and delegation in Exchange Online so team members can send, receive, and manage emails on behalf of other users or shared mailboxes. This reflects real-world Exchange Online admin responsibilities.

## Key Concepts
- **Full Access** – Allows a user to open and manage another mailbox.  
- **Send As** – Allows a user to send emails as the mailbox owner.  
  
    
## Use Cases
- Shared team inboxes handled by multiple users.  
- Executive assistants sending emails on behalf of executives.  
- Temporary mailbox delegation for projects or leave coverage.

## Validation Steps 
1. Go to **Exchange Admin Center → Recipients → Mailboxes**.  
2. Select the mailbox you want to configure.  
3. Open the **Mailbox Delegation** tab.  
4. Assign required permissions- 
       
   <img width="1565" height="645" alt="image" src="https://github.com/user-attachments/assets/a8e3db9e-534f-47ad-8795-e9131b5da9d9" />


  
  - **Full Access** – Read/manage mailbox content.  
       
   <img width="737" height="535" alt="image" src="https://github.com/user-attachments/assets/d7d88284-9f14-4e9d-80e1-fd5231571a62" />

  
  - **Send As** – Send as the mailbox owner.  

   <img width="732" height="420" alt="image" src="https://github.com/user-attachments/assets/3e6977f6-0193-460e-84af-cacd797e3ebd" />

       

6. Verify delegated users can access the mailbox in **Outlook Web or Desktop** and perform actions as per assigned permissions.
   
   * User1 can send emails as the mailbox owner. 
   
     <img width="1576" height="333" alt="image" src="https://github.com/user-attachments/assets/83fea9c1-9fa4-4031-afbb-f7ee10215973" />

   * User2 can manage mailbox content but cannot send as the owner.

    <img width="1910" height="533" alt="image" src="https://github.com/user-attachments/assets/18f9d420-e703-434d-b78c-a51339a8e14e" />

## Expected Outcome
- Delegated users can manage mailbox content according to permissions.  
- Emails sent by delegates display the correct delegation type.  
- Delegation is set up in line with enterprise-level Exchange Online practices.
