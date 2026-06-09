# ServiceNow ITIL ITSM Workspace & Instance Provisioning Project

## Project Overview
This project demonstrates the setup and execution of an enterprise IT Service Management (ITSM) environment within ServiceNow, following ITIL best practices. The workflow covers provisioning a Personal Developer Instance (PDI), managing backend setup, configuring security controls, and handling live records across Incident, Problem, Change, and CMDB layers.

## Tools Used
* **ITSM Platform:** ServiceNow (Developer System Cloud)
* **Framework:** ITIL v4 Service Operations & Configuration Management

---

## 📸 Project Walkthrough

### Phase 1: Requesting and Provisioning the Service Instance

#### Step 1: Requesting a ServiceNow Personal Developer Instance (PDI)
Initializing the setup sequence by requesting an isolated cloud instance via the ServiceNow developer portal.
![Requesting a PDI](screenshots/screenshot_1.png)

#### Step 2: Fulfilling the Infrastructure Request
Monitoring the automated backend cluster build process as the cloud provider provisions the custom tenant space.
![Fulfilling the Infrastructure Request](screenshots/screenshot_2.png)

#### Step 3: Extracting Administrator Credentials
Accessing the management console to retrieve the unique platform URL, admin username, and temporary password.
![Extracting Administrator Credentials](screenshots/screenshot_3.png)

#### Step 4: Booting the Application Studio Workspace
Launching the App Studio interface to access developer tools, integration suites, and management sandboxes.
![Booting the Application Studio Workspace](screenshots/screenshot_4.png)

---

### Phase 2: Core Platform Configuration & Security Onboarding

#### Step 5: Enforcing the Administrative Password Update
Logging into the new instance for the first time and updating the temporary credentials to a secure password.
![Enforcing the Administrative Password Update](screenshots/screenshot_5.png)

#### Step 6: Navigating to the Global Incident Records Engine
Opening the central Incident table to view, filter, and audit active enterprise support tickets.
![Navigating to the Global Incident Records Engine](screenshots/screenshot_6.png)

---

### Phase 3: ITIL ITSM Live Ticket Automation Lifecycle

#### Step 7: Initializing a New Incident Record Form
Opening a blank incident template (INC0010004) to log a new technical failure or infrastructure disruption.
![Initializing a New Incident Record Form](screenshots/screenshot_7.png)

#### Step 8: Documenting the Incident Scope and Details
Populating the incident record with data, including the caller name, the affected server asset (*ANNIE-IBM), and a description of the symptoms.
![Documenting the Incident Scope and Details](screenshots/screenshot_8.png)

#### Step 9: Committing the Ticket to the Live Incident Queue
Submitting the finalized form and verifying that record INC0010004 appears actively at the top of the incident ledger.
![Committing the Ticket to the Live Incident Queue](screenshots/screenshot_9.png)

#### Step 10: Initializing a Root-Cause Investigation (Problem Management)
Opening a fresh record template (PRB0040001) in the Problem Management table to investigate systemic underlying issues.
![Initializing a Root-Cause Investigation](screenshots/screenshot_10.png)

#### Step 11: Mapping the Problem Scope and Infrastructure Asset
Populating the problem record with technical data, linking it to the degraded server asset (*ANNIE-IBM), and defining the core network failure.
![Mapping the Problem Scope and Infrastructure Asset](screenshots/screenshot_11.png)

#### Step 12: Committing the Record to the Global Problem Ledger
Submitting the problem form and verifying that record PRB0040001 is actively indexed under the global problem view.
![Committing the Record to the Global Problem Ledger](screenshots/screenshot_12.png)

#### Step 13: Initializing a New Change Request (Change Management)
Creating a blank change request record (CHG0030001) to structure and plan structural infrastructure upgrades.
![Initializing a New Change Request](screenshots/screenshot_13.png)

#### Step 14: Documenting the Change Plan and Remediation Scope
Populating the change request with scheduling, risk analysis, and hardware resolution steps to swap out the broken network card on server *ANNIE-IBM.
![Documenting the Change Plan and Remediation Scope](screenshots/screenshot_14.png)

#### Step 15: Committing the Change Record to the Master Governance Ledger
Submitting the change request and auditing the global table to confirm that deployment object CHG0030001 is pending review.
![Committing the Change Record to the Master Governance Ledger](screenshots/screenshot_15.png)

---

### Phase 4: CMDB Asset Registry Configuration & Verification

#### Step 16: Initializing a CMDB Asset Record (Configuration Management)
Accessing the Configuration Management Database (CMDB) schema to register a new hardware asset profile within the Server table.
![Initializing a CMDB Asset Record](screenshots/screenshot_16.png)

#### Step 17: Mapping Configuration Metrics to the Infrastructure CI
Populating the CMDB asset template with server parameters, including the name (ANNIE-IBM), asset tag (AST-2026-9982), IP address (10.10.42.11), and Linux OS platform.
![Mapping Configuration Metrics to the Infrastructure CI](screenshots/screenshot_17.png)

#### Step 18: Structuring Configuration Item Dependencies and Relationships
Using the CI Relationship Editor to establish upstream and downstream dependency mappings for server *ANNIE-IBM.
![Structuring Configuration Item Dependencies and Relationships](screenshots/screenshot_18.png)

#### Step 19: Final Baseline Verification of the CMDB Repository
Auditing the master Server repository table (`cmdb_ci_server_list.do`) to verify that the newly deployed server baseline asset record is actively indexed, classified, and discoverable.
![Final Baseline Verification of the CMDB Repository](screenshots/screenshot_19.png)
