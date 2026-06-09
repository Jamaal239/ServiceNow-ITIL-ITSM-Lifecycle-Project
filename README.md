# ServiceNow ITIL ITSM Lifecycle Project

## Project Overview
A complete IT Service Management (ITSM) implementation case study executed within ServiceNow, demonstrating cross-functional workflow automation across Incident, Problem, Change, and CMDB asset mapping following core ITIL frameworks.

## Tools Used
* **ITSM Platform:** ServiceNow (Developer Instance)
* **Framework Alignment:** ITIL v4 (Incident, Problem, Change, and Asset Management)

---

## 📸 Project Walkthrough

### Phase 1: Incident Management & Ingestion

#### Step 1: Initializing the Incident Record
Opened a clean tracking row in the incident database table to log a production server disruption.
![Initializing the Incident Record](screenshots/screenshot_1.png)

#### Step 2: Categorizing the Server Fault
Classified the incident under Hardware/Network to trigger automated assignment routing.
![Categorizing the Server Fault](screenshots/screenshot_2.png)

#### Step 3: Mapping the Host and Assignment Group
Linked the ticket to the affected host (ANNIE-IBM) and assigned ownership to the Hardware Engineering team.
![Mapping the Host and Assignment Group](screenshots/screenshot_3.png)

#### Step 4: Outlining the Incident Scope
Documented diagnostic symptoms and error metrics to streamline frontline engineering triage.
![Outlining the Incident Scope](screenshots/screenshot_4.png)

#### Step 5: Incident Record Verification
Validated live incident record INC0009005 inside the active service queue against active SLAs.
![Incident Record Verification](screenshots/screenshot_5.png)

---

### Phase 2: Problem Management & Root-Cause Investigation

#### Step 6: Initializing the Root-Cause Investigation
Created a new record in the problem table to isolate systemic infrastructure issues from daily firefights.
![Initializing the Root-Cause Investigation](screenshots/screenshot_6.png)

#### Step 7: Structuring the Problem Scope
Pinned the problem record directly to the ANNIE-IBM server asset within the corporate network index.
![Structuring the Problem Scope](screenshots/screenshot_7.png)

#### Step 8: Documenting Systemic Failure Symptoms
Logged the recurring nature of the server drops to identify broader infrastructure degradation trends.
![Documenting Systemic Failure Symptoms](screenshots/screenshot_8.png)

#### Step 9: Linking Incident to the Problem Record
Appended INC0009005 to the Problem ledger to enable multi-ticket status syncing and automated mass resolution.
![Linking Incident to the Problem Record](screenshots/screenshot_9.png)

#### Step 10: Committing the Problem Ticket
Audited the global problem list view to verify the creation of active investigative record PRB0040001.
![Committing the Problem Ticket](screenshots/screenshot_10.png)

#### Step 11: Documenting Root Cause & Workaround
Isolated the failure to a degraded network interface card (NIC) and logged a temporary system workaround.
![Documenting Root Cause & Workaround](screenshots/screenshot_11.png)

---

### Phase 3: Change Management & Risk Governance

#### Step 12: Initializing the Change Workflow
Generated a proactive change_request record straight from the Problem UI to maintain data lineage.
![Initializing the Change Workflow](screenshots/screenshot_12.png)

#### Step 13: Change Template Selection
Selected the standard risk-governance workspace model to align the deployment with corporate change logic.
![Change Template Selection](screenshots/screenshot_13.png)

#### Step 14: Mapping the Change Implementation Plan
Field-mapped scheduling windows and deployment blueprints for the physical network card hot-swap.
![Mapping the Change Implementation Plan](screenshots/screenshot_14.png)

#### Step 15: Change Log Queue Verification
Confirmed the change request was successfully queued inside the enterprise pipeline for administrative review.
![Change Log Queue Verification](screenshots/screenshot_15.png)

---

### Phase 4: CMDB & Asset Dependency Mapping

#### Step 16: CMDB Server Asset Initialization
Initialized a new Configuration Item (CI) record within the cmdb_ci_server class table.
![CMDB Server Asset Initialization](screenshots/screenshot_16.png)

#### Step 17: Registering Infrastructure Configuration Data
Populated host configuration metrics including server name, asset tag, and network IP address (10.10.42.11).
![Registering Infrastructure Configuration Data](screenshots/screenshot_17.png)

#### Step 18: Initializing the CMDB Relationship Map
Opened the Relationship Editor workspace to connect the server to adjacent infrastructure assets.
![Initializing the CMDB Relationship Map](screenshots/screenshot_18.png)

#### Step 19: Configuring Dependency Topology Logic
Adjusted selection checkboxes within the configuration matrix to isolate individual device dependencies and verify downstream business impacts.
![Configuring Dependency Topology Logic](screenshots/screenshot_19.png)
