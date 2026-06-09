# ServiceNow ITIL ITSM Workspace & Instance Provisioning Project

## Project Overview
This project demonstrates the foundational administrative setup of an enterprise IT Service Management (ITSM) environment within ServiceNow. Grounded in ITIL infrastructure delivery best practices, the workflow captures the complete lifecycle of provisioning an isolated corporate platform sandbox: registering for a ServiceNow Personal Developer Instance (PDI), managing backend cluster deployment states, configuring administrator role governance, and deploying core development workspaces to prepare the ecosystem for live ITSM ticket pipeline automation.

## Tools Used
* **ITSM Infrastructure Platform:** ServiceNow (Developer System Cloud)
* **Framework Alignment:** ITIL v4 Service Configuration & Environment Deployment

---

## 📸 Project Walkthrough

### Phase 1: Requesting and Provisioning the Service Instance

#### Step 1: Requesting a ServiceNow Personal Developer Instance (PDI)
Initializing the environment setup sequence by requesting an isolated cloud instance via the developer portal, selecting the target architecture release (Australia/Zurich/Yokohama) to match organizational compliance.
![Requesting a ServiceNow Personal Developer Instance (PDI)](screenshots/screenshot_1.png)

#### Step 2: Fulfilling the Infrastructure Request
Monitoring the automated backend cluster build process as the cloud provider spins up database tables, applications, and routing engines for the custom tenant space.
![Fulfilling the Infrastructure Request](screenshots/screenshot_2.png)

#### Step 3: Extracting Administrator Credentials
Accessing the central cloud instance management console to extract key instance parameters, including the unique platform routing URL, dedicated admin account username, and temporary root passwords.
![Extracting Administrator Credentials](screenshots/screenshot_3.png)

#### Step 4: Booting the Application Studio Workspace
Launching into the operational developer engine view to access advanced application-building suites, integration tools, and automation script sandboxes.
![Booting the Application Studio Workspace](screenshots/screenshot_4.png)

---

### Phase 2: Core Platform Configuration & Dashboard Optimization

#### Step 5: Initializing the Global Service Dashboards
Navigating through the unified user interface (UI) to review default system monitoring panels, operational KPIs, and administrative layout tables.
![Initializing the Global Service Dashboards](screenshots/screenshot_5.png)

#### Step 6: Setting Up Core System Properties
Adjusting fundamental workspace settings, including localized system parameters, base timezones, and display banner preferences to align with enterprise interface guidelines.
![Setting Up Core System Properties](screenshots/screenshot_6.png)

#### Step 7: Accessing the Application Configuration Navigator
Utilizing the left-hand main navigation index to query specific ITSM tables, application modules, and security control files.
![Accessing the Application Configuration Navigator](screenshots/screenshot_7.png)

#### Step 8: Reviewing Active System Plugins
Auditing the pre-installed platform plugins list to verify core capabilities like the Incident, Problem, Change, and Configuration Management Database (CMDB) schemas are active.
![Reviewing Active System Plugins](screenshots/screenshot_8.png)

---

### Phase 3: ITIL Table Auditing & Schema Inspections

#### Step 9: Reviewing the Base Incident Table Layout
Opening a fresh, unpopulated incident data record matrix to analyze required fields, urgency metrics, and priority assignment matrix rules.
![Reviewing the Base Incident Table Layout](screenshots/screenshot_9.png)

#### Step 10: Mapping Choice List Definitions
Inspecting table dictionary entries to evaluate custom dropdown fields, status indicators, and categorization tags across core support tables.
![Mapping Choice List Definitions](screenshots/screenshot_10.png)

#### Step 11: Auditing out-of-the-box Assignment Rules
Reviewing automatic ticket routing scripts to understand how inbound work objects map directly to dedicated physical hardware and network support engineering queues.
![Auditing out-of-the-box Assignment Rules](screenshots/screenshot_11.png)

#### Step 12: Inspecting SLA Definition Maps
Locating the active Service Level Agreement (SLA) properties file to ensure internal reaction times and target resolution timers bind perfectly to high-priority tickets.
![Inspecting SLA Definition Maps](screenshots/screenshot_12.png)

---

### Phase 4: Data Schema Testing & Workspace Validation

#### Step 13: Staging a Mock Configuration Item (CI)
Reviewing the structure of the Base Configuration Item table to prepare for asset mapping and data relationships across the CMDB layer.
![Staging a Mock Configuration Item (CI)](screenshots/screenshot_13.png)

#### Step 14: Verifying the Change Request Workflow Engine
Opening the change control visual task map layout to inspect approval paths and peer-review gates for standard, normal, and emergency changes.
![Verifying the Change Request Workflow Engine](screenshots/screenshot_14.png)

#### Step 15: Validating the Problem Management Database Layout
Inspecting the backend problem tracking schema to verify that downstream links can tie multiple parent/child incidents together seamlessly.
![Validating the Problem Management Database Layout](screenshots/screenshot_15.png)

#### Step 16: Reviewing System Access Control Lists (ACLs)
Inspecting the global user database configuration to see how IT Support profiles, customer profiles, and administrator security groups are segregated.
![Reviewing System Access Control Lists (ACLs)](screenshots/screenshot_16.png)

#### Step 17: Testing Cross-Table Referencing Capabilities
Running sample search queries across separate infrastructure fields to ensure dependent items link correctly between incidents and assets.
![Testing Cross-Table Referencing Capabilities](screenshots/screenshot_17.png)

#### Step 18: Evaluating Global Search Index Performance
Testing the AI search and system-wide index bars from the perspective of an IT service agent searching for historical knowledge blocks.
![Evaluating Global Search Index Performance](screenshots/screenshot_18.png)

#### Step 19: Final Workspace Readiness Sign-Off
Reviewing the verified, optimized, and fully accessible ServiceNow developer instance dashboard, completely prepared to handle live operational tracking data.
![Final Workspace Readiness Sign-Off](screenshots/screenshot_19.png)
