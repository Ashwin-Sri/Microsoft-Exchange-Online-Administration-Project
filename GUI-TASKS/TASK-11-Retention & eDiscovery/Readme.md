# Task 11 – Retention & eDiscovery

## Objective
Configure retention mechanisms in Exchange Online to preserve mailbox data and demonstrate compliance investigation capabilities using Litigation Hold and Content Search in Microsoft Purview.

---

## Steps

### 1. Apply Litigation Hold
1. Sign in to **Exchange Admin Center (EAC)**.
2. Navigate to **Recipients** → **Mailboxes**.
3. Select the target mailbox (e.g., User2).
4. Open **Mailbox features** → enable **Litigation Hold**.
5. Set duration (optional) and add a **Litigation Hold comment** for auditing.
6. Save changes.

    <img width="1918" height="862" alt="image" src="https://github.com/user-attachments/assets/87d5e783-aba8-44c0-ac2d-dfa6d129d8a3" />

 *This ensures all mailbox content is preserved, including deleted and edited items.*

---

### 2. Verify Hold in Microsoft Purview
1. Open **Microsoft Purview portal**.
2. Navigate to **eDiscovery** → **Content search**.
3. Create a new search and select the mailbox placed on Litigation Hold.
4. Add search criteria (e.g., keywords, sender, date range).
5. Run the search and review statistics.
6. Export results if required.

    <img width="1802" height="852" alt="image" src="https://github.com/user-attachments/assets/ae928160-9c78-4622-a951-9aab96504d89" />

    <img width="1802" height="792" alt="image" src="https://github.com/user-attachments/assets/014631f3-e095-45a0-8b6d-a9e3a2418b21" />

 *This demonstrates how compliance teams can search preserved data, even if a user deleted it.*

---

## Validation
- Mailbox on Litigation Hold shows **Hold enabled** in EAC.
- Purview **Content Search** returns items matching queries, regardless of user deletion.
- Exported results confirm preserved data.

---

## Notes
- Litigation Hold applies to **future and existing items** at the time of enabling.
- Changes may take several hours to reflect in Purview searches.
- Retention Policies can also be used for broader, automated compliance needs.

---

## Outcome
Successfully enabled mailbox data preservation and demonstrated compliance investigation workflow using Litigation Hold and Content Search.
