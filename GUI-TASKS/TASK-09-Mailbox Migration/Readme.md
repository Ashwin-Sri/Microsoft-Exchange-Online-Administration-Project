# Task 09 – Mailbox Migration 

## Objective  
Understand how mailbox migrations are initiated, monitored, and managed in Exchange Online. While this task does not involve a live hybrid setup, it demonstrates awareness of the migration process and admin responsibilities.  

---

## Key Concepts  
- **Mailbox Migration** – Moving user mailboxes from on-premises Exchange to Exchange Online, or between tenants.  
- **Migration Batch** – A collection of mailboxes scheduled to be migrated together.  
- **Status Tracking** – Migration jobs pass through stages like *Queued, Syncing, Completed, or Failed*.  
- **Admin Role** – Admins plan, start, and monitor migrations, resolving issues such as mailbox size limits or corrupted items.  

---

## Steps   
1. Sign in to **Exchange Admin Center → Recipients → Migration**.  
2. Click **Add Migration Batch** and select an available option (e.g., Remote move, Cutover).  
3. Add a mailbox or group (for demonstration purposes, a test user can be selected).  
4. Start the migration batch – the job appears in the **Migration dashboard**.  
5. Observe the **Job Status**:  
   - *Queued* – Job created, waiting to process.  
   - *Syncing* – Data being migrated.  
   - *Completed* – Migration successful.  
   - *Failed* – Migration failed due to errors.  

---

## Expected Outcome  
- Administrator understands where mailbox migrations are configured.  
- Able to explain how migration batches are created and tracked.  
- Demonstrates knowledge of common migration statuses (*Queued, Syncing, Completed, Failed*).  
- Awareness of real-world use cases (on-prem to cloud or tenant-to-tenant migrations).  

---

## Notes  
- In this lab setup, migrations remain in **Queued** state since no hybrid or secondary tenant is available.  
- For production, admins must ensure prerequisites such as hybrid connectivity, proper licensing, and mailbox size checks.  
