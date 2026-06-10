# ServiceNow ITIL ITSM Workspace & Instance Provisioning Project (2026)

## Project Overview
This project demonstrates the setup and execution of an enterprise IT Service Management (ITSM) environment within ServiceNow, following ITIL best practices. The workflow covers provisioning a Personal Developer Instance (PDI), managing backend setup, configuring security controls, and handling live records across Incident, Problem, Change, and CMDB layers.

### Tools Used
* **ITSM Platform:** ServiceNow (Developer System Cloud)
* **Framework:** ITIL v4 Service Operations & Configuration Management

---

## 📸 Project Walkthrough

### Phase 1: Requesting and Provisioning the Service Instance

#### Step 1: Requesting a ServiceNow Personal Developer Instance (PDI)
Initializing the setup sequence by requesting an isolated cloud instance via the ServiceNow developer portal.

![Requesting a ServiceNow PDI via Developer Portal](screenshot_01.png)
*Figure 1: Initializing the PDI cloud instance request sequence.*

#### Step 2: Fulfilling the Infrastructure Request
Monitoring the automated backend cluster build process as the cloud provider provisions the custom tenant space.

![Automated PDI provisioning tracking window](screenshot_02.png)
*Figure 2: ServiceNow automated backend environment deployment in progress.*

#### Step 3: Extracting Administrator Credentials
Accessing the management console to retrieve the unique platform URL, admin username, and temporary password.

![Extracting instance admin credentials from console](screenshot_03.png)
*Figure 3: Secure retrieval of unique tenant routing credentials.*

#### Step 4: Booting the Application Studio Workspace
Launching the App Studio interface to access developer tools, integration suites, and management sandboxes.

![Launching ServiceNow Application Studio](screenshot_04.png)
*Figure 4: Navigating into the centralized application developer workspace.*

---

### Phase 2: Core Platform Configuration & Security Onboarding

#### Step 5: Enforcing the Administrative Password Update
Logging into the new instance for the first time and updating the temporary credentials to a secure password.

![Enforcing the first-time login administrative password change](screenshot_05.png)
*Figure 5: Enforcing administrative user identity access credential rotations.*

#### Step 6: Navigating to the Global Incident Records Engine
Opening the central Incident table to view, filter, and audit active enterprise support tickets.

![Navigating the global incident records system table view](screenshot_06.png)
*Figure 6: Opening the master corporate incident tracking ledger console.*

---

### Phase 3: ITIL ITSM Live Ticket Automation Lifecycle

#### Step 7: Initializing a New Incident Record Form
Opening a blank incident template (INC0010004) to log a new technical failure or infrastructure disruption.

![Opening a blank incident form](screenshot_07.png)
*Figure 7: Initializing record creation matrix for asset failure event INC0010004.*

#### Step 8: Documenting the Incident Scope and Details
Populating the incident record with data, including the caller name, the affected server asset (\*ANNIE-IBM), and a description of the symptoms.

![Populating structural data into incident template](screenshot_08.png)
*Figure 8: Mapping operational parameters and configuration dependencies to the record data block.*

#### Step 9: Committing the Ticket to the Live Incident Queue
Submitting the finalized form and verifying that record INC0010004 appears actively at the top of the incident ledger.

![Committing the incident record to the live queue](screenshot_09.png)
*Figure 9: Verifying active listing profile indexing for INC0010004.*

#### Step 10: Initializing a Root-Cause Investigation (Problem Management)
Opening a fresh record template (PRB0040001) in the Problem Management table to investigate systemic underlying issues.

---

### Phase 4: CMDB Asset Registry Configuration & Verification

#### Step 16: Initializing a CMDB Asset Record (Configuration Management)
Accessing the Configuration Management Database (CMDB) schema to register a new hardware asset profile within the Server table.

#### Step 17: Mapping Configuration Metrics to the Infrastructure CI
Populating the CMDB asset template with server parameters, including the name (ANNIE-IBM), asset tag (AST-2026-9982), IP address (10.10.42.11), and Linux OS platform.

#### Step 18: Structuring Configuration Item Dependencies and Relationships
Using the CI Relationship Editor to establish upstream and downstream dependency mappings for server \*ANNIE-IBM.

#### Step 19: Final Baseline Verification of the CMDB Repository
Auditing the master Server repository table (cmdb_ci_server_list.do) to verify that the newly deployed server baseline asset record is actively indexed, classified, and discoverable.
