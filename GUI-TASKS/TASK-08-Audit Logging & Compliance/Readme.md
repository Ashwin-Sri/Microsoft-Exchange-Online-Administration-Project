# Task 08 – Audit Logs & Compliance Monitoring

## Objective
Use Microsoft Purview Audit to track and investigate user/admin activities in Exchange Online for security, compliance, and troubleshooting.

## Key Concepts
- **Audit Logging** – Records actions such as mailbox sign-ins, Send As/Send on Behalf, message moves/deletes.
- **Unified Audit Log (Purview)** – Central search across Microsoft 365 services, including Exchange.

## Validation Steps
1. Sign in to **Microsoft Purview → Audit**.
2. Click **Audit (Standard)** and start a **New search**.
3. Configure filters:
   - **Activities**: e.g., *MailboxLogin*, *SendAs*, *SendOnBehalf*, *MovedToDeletedItems*, *HardDelete*.
   - **Users**: select target user(s) or shared mailbox delegates.
   - **Date range**: up to **90 days** (E3).
   - **Workload**: **Exchange** (optional but recommended).
4. Submit the search. The job status will progress:
   - **Queued** → waiting to start.
   - **Running** → query processing.
   - **Completed** → results ready.
5. Open the completed job → review entries (Timestamp, User/Actor, Activity, Item/Target, IP, Client/App).
6. **Export** results to **CSV** (for evidence or offline analysis).

## Expected Outcome
- Tenant audit logging is active and searchable in Purview.
- Exchange-related activities (logins, Send As/On Behalf, message operations) are visible and exportable.
- Provides a reliable audit trail for investigations and compliance reporting.
