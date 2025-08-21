## Task 10 – Mail Flow Security

**Objective:**  
Ensure secure and compliant mail flow by validating email authentication and managing quarantined messages in Microsoft 365.

---

### Overview
Mail flow security involves making sure outbound emails from your organization are trusted and inbound suspicious messages are handled properly.  
Key components include:

- **Domain Authentication:** SPF, DKIM, and DMARC help prevent spoofing and phishing.  
- **Quarantine Management:** Review, release, or block suspicious messages caught by Microsoft 365’s security systems.

> Note: In a lab tenant without a custom domain, SPF/DKIM configuration is simulated and documented. Quarantine review can be performed in the portal.

---

### Steps

1. **Verify Custom Domain (Prerequisite)**
   - Navigate to **Microsoft 365 Admin Center → Settings → Domains → [Select Domain]**  
   - Ensure the domain is verified in Microsoft 365.  

      <img width="1846" height="862" alt="image" src="https://github.com/user-attachments/assets/0c8adf4a-e8dd-4a59-863b-d4efc6f4a1cf" />

2. **Configure DKIM for the Domain**
   - Go to **Microsoft 365 Defender portal → Email & Collaboration → Policies & Rules → Threat Policies → DKIM**  
   - Select the domain and enable DKIM signing.  

      <img width="1857" height="848" alt="image" src="https://github.com/user-attachments/assets/8a86ea32-aa3a-4f61-8e61-9eb20a08abf0" />
 
3. **Monitor Quarantine**
   - Navigate to **Microsoft 365 Defender portal → Email & Collaboration → Review → Quarantine**  
   - Review messages flagged as spam/phishing or containing malware.  
   - Release legitimate messages or report false positives.  

      <img width="1847" height="866" alt="image" src="https://github.com/user-attachments/assets/353b8ef6-66f4-4150-a710-ddf897d53a8a" />


4. **Validate Mail Flow Security**
   - Send a test email from a domain-enabled mailbox to an external address.  
   - Check headers for **DKIM-Signature** and verify SPF/DMARC pass.  
   

---

### Expected Outcomes

- Outbound emails from the domain are digitally signed using DKIM.  
- SPF, DKIM, and DMARC authentication passes successfully for the domain.  
- Suspicious or harmful messages are quarantined and actionable.  
- Documentation clearly shows workflow and portal navigation.

---
