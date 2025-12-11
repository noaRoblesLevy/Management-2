# 📈 TO-BE Process Design: Automated Insurance Mailbox Routing

## 📋 Executive Summary
This project documents the proposed **future state (TO-BE)** of the insurance mailbox routing process. Moving away from the manual "AS-IS" workflow, this solution introduces **Full Automation (Option B)**.

By leveraging **IDAS (Intelligent Document Analysis System)** and **RPA (Robotic Process Automation)**, the objective is to reduce lead times from days to hours, eliminate manual data entry errors, and allow staff to focus on complex, high-value cases.

## 🧠 Strategic Solution Selection
We evaluated three potential solutions using a **Weighted Criteria Matrix** based on cost, accuracy, lead time, complexity, and customer satisfaction.

| Option | Description | Score | Status |
| :--- | :--- | :--- | :--- |
| **A. Basic Automation** | IDAS integrated, but emails remain manual. | 6.65 | Rejected |
| **B. Full Automation** | **IDAS + Extensive RPA + Automated Output.** | **8.15** | **Selected** |
| **C. Hybrid Model** | IDAS + Partial RPA; humans handle complex routing. | 7.35 | Rejected |

**Why Option B?**
It provides the most significant impact on cost reduction (30% weight) and accuracy (25% weight), aligning best with the strategic goal of maximizing productivity and scalability during seasonal peaks.

## 🛠️ The TO-BE Workflow
The new process integrates Outlook, IDAS, the Policy System, and the Task Distribution System to create a seamless data flow.

### 1. 📥 Automatic Classification (IDAS)
* **Action:** AI/LLM analyzes incoming emails.
* **Benefit:** Extracts policy numbers and client data automatically; drastically reduces classification errors.

### 2. ⚡ Auto-Task Creation & Routing
* **Action:** IDAS creates the task directly in the distribution system without human intervention. A rule-based engine routes the task based on workload and expertise.
* **Benefit:** Eliminates "copy-paste" work and manual parameter entry.

### 3. 🤖 RPA Execution
* **Action:** Robots perform standard, low-risk policy changes (e.g., address updates).
* **Benefit:** Human handlers are relieved of repetitive work to focus on complex exceptions.

### 4. 📧 Automated Confirmation
* **Action:** The system dynamically generates a confirmation email with the updated policy PDF attached.
* **Benefit:** Consistent communication and immediate response to the customer.



## 📊 Feasibility Analysis (COPAFILT)
To ensure viability, we performed a COPAFILT analysis on the Full Automation solution.

* **C - Customer:** Satisfaction increases due to predictable, timely service (hours vs. days).
* **O - Organisation:** Workload restructures; simple tasks disappear. Governance must now include AI drift control and RPA monitoring.
* **P - People:** Roles shift from data entry to quality control. Extensive training and Change Management are required to mitigate resistance.
* **A - Administrative:** SOPs must be updated to define RPA execution steps and escalation paths for when automation fails.
* **F - Finance:** Requires upfront investment in licensing and development, but offers long-term ROI by reducing FTE dependency for repetitive tasks.
* **I - Information:** Requires stable data flow between systems. Dashboards must track RPA success rates and indexing accuracy.
* **L - Legal:** Must ensure GDPR compliance for automated processing and document AI model transparency.
* **T - Technology:** The main challenge is the complex integration effort between IDAS and RPA. Fallback mechanisms are required.

## 🚀 Conclusion
The evaluation confirms that **Option B (Full Automation)** is feasible and highly recommended. While it carries risks regarding change management and integration complexity, it offers the necessary scalability to future-proof the operations department.

---
*Analysis performed by Noa Robles Levy*
