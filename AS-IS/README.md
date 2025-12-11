# 📉 AS-IS Process Analysis: Insurance Mailbox Routing

## 📋 Project Summary
This project documents the **current state (AS-IS)** of the inbound mailbox routing process for an insurance company. The analysis reveals a process that is 100% manual, stable but slow, and prone to errors due to high administrative burdens. The primary goal is to map the bottlenecks caused by the lack of integration between Outlook, the task system, and the policy system.

## 🛠️ Analysis Frameworks

### 1. 🐢 Turtle Diagram (Process Scope)
Defines the boundaries of the manual indexing process.
* **Inputs:** Emails from clients/brokers with attachments (PDFs, forms) and internal classification guidelines.
* **Resources (With What):** Outlook, in-house task distribution system, and the core insurance system.
* **Process (How):** Manual interpretation of email content $\rightarrow$ Manual task creation $\rightarrow$ Manual assignment to a handler.
* **Metrics:** Lead time from email to task creation; classification accuracy.

### 2. 🔄 SIPOC Model
Maps the high-level flow from external request to internal execution.
* **Suppliers:** Clients and Brokers (external); Policy System (internal).
* **Inputs:** Change requests (Address, Contract, Bank details, Beneficiaries).
* **Process:** 6-step flow starting with Email Receipt and ending with Policy Adjustment Confirmation.
* **Outputs:** Manually classified tasks and confirmation emails with PDF policies.
* **Customers:** Internal Policy Handlers and the Indexing Team.

### 3. 🦴 Fishbone Diagram (Root Cause Analysis)
Investigates the main problem: **"Too long lead times and error-prone manual processing"**.
* **People:** Fatigue from repetitive work increases error risk; variation in knowledge between employees.
* **Process:** Too many steps; lack of standardization; reliance on individual interpretation.
* **Technology:** No automatic classification or data extraction; no integration between mailbox and core systems.
* **Environment:** Seasonal peaks lead to task accumulation.


### 4. 🔀 BPMN (AS-IS Workflow)
A visual flowchart detailing the manual "handoff" between teams.
* **Indexing Team:** Opens email (2-3 min), creates task (3-5 min), searches policy info (3-8 min), and assigns to handler.
* **Policy Handler:** Receives notification, opens task, executes change (10-30 min), and sends confirmation.
* **Bottleneck:** The process is strictly linear and relies on manual data entry at every stage.

### 5. ⚖️ SWOT Analysis (Current State)
Evaluates the strategic position of the current operation.
* **Strengths:** Employees possess deep knowledge of policy management; the process is stable.
* **Weaknesses:** 100% manual process; insufficient scalability during peaks; high administrative load.
* **Opportunities:** Automation using IDAS + RPA; improved customer satisfaction via faster processing.
* **Threats:** Errors leading to compliance issues; competitors digitizing faster.

---
*Analysis performed by Noa Robles Levy*

