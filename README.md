# ServiceNow ITIL ITSM Lifecycle Project

A complete IT Service Management (ITSM) implementation case study executed within ServiceNow, demonstrating cross-functional workflow automation across Incident, Problem, Change, and CMDB asset mapping.

---

## 📸 Project Walkthrough

### Step 1: Initializing the Incident Record
![Step 1](screenshots/screenshot_1.png)
* Opened a clean tracking row in the `incident` database table to log a production server disruption.

### Step 2: Categorizing the Server Fault
![Step 2](screenshots/screenshot_2.png)
* Classified the incident under Hardware/Network to trigger automated assignment routing.

### Step 3: Mapping the Host and Assignment Group
![Step 3](screenshots/screenshot_3.png)
* Linked the ticket to the affected host (`ANNIE-IBM`) and assigned ownership to the Hardware Engineering team.

### Step 4: Outlining the Incident Scope
![Step 4](screenshots/screenshot_4.png)
* Documented diagnostic symptoms and error metrics to streamline frontline engineering triage.

### Step 5: Incident Record Verification
![Step 5](screenshots/screenshot_5.png)
* Validated live incident record `INC0009005` inside the active service queue against active SLAs.

### Step 6: Initializing the Root-Cause Investigation
![Step 6](screenshots/screenshot_6.png)
* Created a new record in the `problem` table to isolate systemic infrastructure issues from daily firefights.

### Step 7: Structuring the Problem Scope
![Step 7](screenshots/screenshot_7.png)
* Pinned the problem record directly to the `ANNIE-IBM` server asset within the corporate network index.

### Step 8: Documenting Systemic Failure Symptoms
![Step 8](screenshots/screenshot_8.png)
* Logged the recurring nature of the server drops to identify broader infrastructure degradation trends.

### Step 9: Linking Incident to the Problem Record
![Step 9](screenshots/screenshot_9.png)
* Appended `INC0009005` to the Problem ledger to enable multi-ticket status syncing and automated mass resolution.

### Step 10: Committing the Problem Ticket
![Step 10](screenshots/screenshot_10.png)
* Audited the global problem list view to verify the creation of active investigative record `PRB0040001`.

### Step 11: Documenting Root Cause & Workaround
![Step 11](screenshots/screenshot_11.png)
* Isolated the failure to a degraded network interface card (NIC) and logged a temporary system workaround.

### Step 12: Initializing the Change Workflow
![Step 12](screenshots/screenshot_12.png)
* Generated a proactive `change_request` record straight from the Problem UI to maintain data lineage.

### Step 13: Change Template Selection
![Step 13](screenshots/screenshot_13.png)
* Selected the standard risk-governance workspace model to align the deployment with corporate change logic.

### Step 14: Mapping the Change Implementation Plan
![Step 14](screenshots/screenshot_14.png)
* Field-mapped scheduling windows and deployment blueprints for the physical network card hot-swap.

### Step 15: Change Log Queue Verification
![Step 15](screenshots/screenshot_15.png)
* Confirmed the change request was successfully queued inside the enterprise pipeline for administrative review.

### Step 16: CMDB Server Asset Initialization
![Step 16](screenshots/screenshot_16.png)
* Initialized a new Configuration Item (CI) record within the `cmdb_ci_server` class table.

### Step 17: Registering Infrastructure Configuration Data
![Step 17](screenshots/screenshot_17.png)
* Populated host configuration metrics including server name, asset tag, and network IP address (`10.10.42.11`).

### Step 18: Initializing the CMDB Relationship Map
![Step 18](screenshots/screenshot_18.png)
* Opened the Relationship Editor workspace to connect the server to adjacent infrastructure assets.

### Step 19: Configuring Dependency Topology Logic
![Step 19](screenshots/screenshot_19.png)
* Adjusted selection checkboxes within the configuration matrix to isolate individual device dependencies.
