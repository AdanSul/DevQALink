# DevQALink  

## High-Level Goal  
A **framework** that bridges **QA and development teams**, enabling **test scheduling**, **automated execution**, and **report generation** for efficient **bug tracking and resource management**.

---

## 🏗️ **Core Entities**  

### ✅ **QA Tests**  
**Define and manage QA test cases efficiently.**  
- **Title & Description** – Clearly document test cases.  
- **Steps** – Define step-by-step execution.  
- **Automated Test Trigger** – Run using CLI (e.g., `python3.9 test_runner.py --arg1 value1 ...`).  

---

### 🏗 **Dev Builds**  
**Track and preview application versions & builds.**  
- **Daily Build Updates** – Example: `1.0.0-100` today, `1.0.0-101` tomorrow.  
- **Fetched from 3rd Party APIs** – Displayed within the framework.  

---

### ⚙️ **Resources Management**  
**Manage servers & resource allocation for test execution.**  
- **Pool** → Contains clusters.  
- **Cluster** → Contains multiple servers.  
- **Server** → Identified by an **IP address**.  
- ✅ Mark a **server as a test runner** for automated test execution.  

---

### 📅 **Scheduler**  
**Automate test execution on development builds.**  
- **One-time & recurring test runs**.  
- **Modify, delete, or activate/inactivate jobs**.  
- **Priority-based scheduling algorithm (1-10 levels).**  

---

### 📊 **Executions**  
**Monitor active jobs and execution status.**  
- **Live status updates** – Waiting, Running, Available.  
- **Track job progress & resource allocation**.  

---

### 📜 **Reports**  
**Generate detailed reports post-execution.**  
- **Includes Test, Version-Build, Cluster Details, Test Result, Failure Reason, Runtime, Date, and User.**  
- **Open a bug ticket** (e.g., Jira Integration).  
- **Send reports to the user who triggered the job.**  

---

## 🎁 **Bonus Feature: AI-Powered Analysis**  
**Leverage AI to analyze execution logs** and suggest potential failure causes:  
- **Real version-build bug**  
- **Test issue**  
- **Cluster-related problem**  

---

