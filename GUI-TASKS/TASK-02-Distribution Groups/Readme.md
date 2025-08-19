# Task 02 – Distribution Group Management via Exchange Admin Center

## Objective
Create and manage distribution groups in Exchange Online using the Exchange Admin Center (EAC).  
Covers provisioning a group, modifying settings, validating mail flow, and disabling/deleting the group.

---

## Steps Performed
1. Signed into **Exchange Admin Center** with **Exchange Admin** role.  
2. Navigated to **Recipients → Groups**.  
3. Created a new **Distribution Group**:  
   - Assigned name, alias, and primary email address.  
   - Added test members (User1, User2).  
4. Modified group settings:  
   - Enabled or disabled external senders.  
       <img width="1540" height="803" alt="image" src="https://github.com/user-attachments/assets/962471d9-bba4-484a-9774-4f5429027b07" />

       <img width="791" height="555" alt="image" src="https://github.com/user-attachments/assets/ecc9bd80-a5f4-4306-9aac-f933a4a1e261" />

   - Updated membership and ownership.  

       <img width="1271" height="732" alt="image" src="https://github.com/user-attachments/assets/8de4fedf-bffc-40f1-aa08-f3ecb249f53e" />

5. Validated functionality:  
   - Sent a test mail to the group address.  
   - Confirmed all members received the message.  

       <img width="1901" height="467" alt="image" src="https://github.com/user-attachments/assets/bebb19eb-dc5d-458d-ba41-fb2fb1033d1f" />

--- 

## Validation Outcomes

| Validation Item | Result |
|-----------------|--------|
| Distribution group visible in EAC | ✅ Confirmed under Recipients → Groups |
| Test mail delivery | ✅ Members received mail successfully |
| Membership updates | ✅ Reflected in group properties |
| External sender restriction | ✅ Applied as configured |

---

## Conclusion
Distribution group lifecycle management (create, modify, validate, and delete) was successfully performed in Exchange Admin Center.  
This validates day-to-day administrative tasks for group mail flow and membership in Exchange Online.
