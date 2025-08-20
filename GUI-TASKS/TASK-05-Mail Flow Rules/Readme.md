# Task 05 – Mail Flow Rules

## Objective
Configure mail flow rules in Exchange Online to control email processing, enforce organizational policies, and manage message routing based on conditions and exceptions.

## Key Concepts
- **Mail Flow (Transport) Rules** – Rules that apply actions to emails as they pass through the Exchange Online service.  
- **Conditions** – Criteria to identify messages, e.g., sender, recipient, keywords, or message size.  
- **Actions** – Tasks performed on messages, such as redirecting, blocking, adding disclaimers, or applying encryption.  
- **Exceptions** – Criteria to exclude certain messages from the rule.  

## Use Cases
- Block emails from specific senders or domains.  
- Apply disclaimers to outgoing emails for legal or compliance reasons.  
- Redirect or forward messages based on content or recipients.  
- Enforce organizational email policies automatically.

## Validation Steps
1. Go to **Exchange Admin Center → Mail Flow → Rules**.
    
    <img width="1792" height="837" alt="image" src="https://github.com/user-attachments/assets/29d148b3-3b00-45a9-a757-96e896b912ec" />
  
2. Click **+ → Create a new rule**.  
3. Set the rule **Name** and define **Conditions**, **Actions**, and **Exceptions** as required. 

    <img width="1338" height="805" alt="image" src="https://github.com/user-attachments/assets/d5597447-ceff-4c2f-9f74-b5cbb7110067" />
 
    - For this Testing I have used my own Gmail to test the Rule.
   
    <img width="1380" height="850" alt="image" src="https://github.com/user-attachments/assets/3b401fdb-c145-465a-83ef-bd9b5a8d6495" />
    
    <img width="1205" height="816" alt="image" src="https://github.com/user-attachments/assets/a98a8f31-d671-450e-901c-334f829adb00" />
     
    - We can enable to disable the Rule when required.
   
    <img width="1556" height="806" alt="image" src="https://github.com/user-attachments/assets/98f0eda8-d83a-487b-9a81-c4cf97d00873" />

5. Save the rule and ensure it appears in the rule list.  
6. Test the rule by sending emails that meet the conditions and verify the expected action occurs.  

      - Tested by sending an Email, got response back as shown below in the snap
    
    <img width="938" height="510" alt="image" src="https://github.com/user-attachments/assets/08179f88-629f-4ad7-a14e-9eac81c6b83b" />

## Expected Outcome
- Emails matching the defined conditions are processed according to the rule actions.  
- Exceptions are respected, and compliant messages flow normally.  
- The mail flow setup reflects enterprise-level email management and policy enforcement.
