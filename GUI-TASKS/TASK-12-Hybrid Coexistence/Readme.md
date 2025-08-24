# Task 12 – Hybrid Coexistence 

## Objective
Demonstrate understanding of Exchange Hybrid deployment and mail flow between on-premises Exchange and Exchange Online.

---

## Steps

### 1. Hybrid Configuration Wizard (HCW)
- Normally run on an on-premises Exchange server.
- Connects to Microsoft 365 tenant using admin credentials.
- Configures:
  - Federation
  - Organization relationships
  - Mail flow connectors
  - Autodiscover redirection

### 2. Mail Routing Paths
- **On-Prem → Cloud:** Message routed through Hybrid Connector to Exchange Online.
- **Cloud → On-Prem:** Message routed back through the outbound connector to on-prem Exchange.
- Both environments share the same SMTP namespace (e.g., `@contoso.com`).

      <img width="1888" height="856" alt="image" src="https://github.com/user-attachments/assets/5a6a0c1d-0e0f-4163-b84e-1fafe4c311a4" />

### 3. Identity Synchronization
- Hybrid requires **Microsoft Entra Connect** for syncing on-prem AD objects to Microsoft 365.
- Provides a unified identity across both environments.

### 4. Certificates and Autodiscover
- Valid SSL certificate is needed on on-prem Exchange server.
- Autodiscover service redirects users between on-prem and Exchange Online.

---

## Validation
Since no on-prem Exchange server is available in lab:
- Steps are documented as simulation.
- Demonstrates knowledge of hybrid setup requirements.
