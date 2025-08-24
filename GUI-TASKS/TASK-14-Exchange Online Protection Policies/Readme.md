# Task 14 – Exchange Online Protection (EOP) Policies

## Objective
Configure and validate Exchange Online Protection (EOP) policies to protect mail flow against spam, malware, and phishing in Microsoft 365.

---

## Steps

### 1. Anti-Spam Policy
1. Go to **Microsoft 365 Security & Compliance Center** → **Email & collaboration** → **Policies & rules** → **Threat policies**.
2. Select **Anti-spam policies**.
3. Review the **Default policy** or create a **Custom policy**.

      <img width="1852" height="858" alt="image" src="https://github.com/user-attachments/assets/ca467fc3-2d3a-45be-a2ea-0a5790822a0d" />

5. Configure options:
   - Bulk email threshold
   - Spam and high-confidence spam actions
   - Quarantine duration

      <img width="1550" height="802" alt="image" src="https://github.com/user-attachments/assets/e9a9e8a4-de14-4663-a73a-351707c4eb62" />

### 2. Anti-Malware Policy
1. In **Threat policies**, open **Anti-malware**.
2. Edit default or add a new policy.
3. Configure settings:
   - Zero-hour auto purge (ZAP) for malware
   - File type filtering
   - Notification options for senders/recipients

      <img width="1837" height="856" alt="image" src="https://github.com/user-attachments/assets/1afd8331-a189-471a-9a21-0e61af030d36" />

      <img width="1586" height="640" alt="image" src="https://github.com/user-attachments/assets/46e089ae-55f5-433e-9177-a444b4e4a36c" />

### 3. Safe Attachments
1. Navigate to **Policies & rules** → **Safe Attachments**.
2. Create a policy for users/groups.
3. Set action:
   - Dynamic Delivery
   - Block
   - Replace
4. Assign scope (e.g., all users or specific groups).

   <img width="1477" height="800" alt="image" src="https://github.com/user-attachments/assets/c28b747f-74d3-4585-a66b-e9f4cb032e55" />

### 4. Safe Links
1. Go to **Policies & rules** → **Safe Links**.
2. Create or edit policy.
3. Enable:
   - Real-time URL scanning
   - Apply to Office apps (Word, Excel, PowerPoint, Teams, etc.)
   - Click protection for URLs in email

       <img width="1701" height="760" alt="image" src="https://github.com/user-attachments/assets/f4e4f42b-7913-490b-89ec-0cd0468243ea" />

---

## Validation
- Verified Anti-Spam quarantine behavior.
- Confirmed malware filtering with blocked file types.
- Tested Safe Links redirection and protection.
- Captured screenshots of all configured EOP policies.

---
