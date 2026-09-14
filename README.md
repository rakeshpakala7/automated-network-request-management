# Automated Network Request Management

A ServiceNow application that automates network access and connectivity requests from employees.

## 📌 Project Overview

Employees can submit different network-related requests through the ServiceNow Service Catalog.

The system automatically:
- Creates REQ and RITM
- Sends manager approval for access requests
- Creates a Network Task after approval
- Assigns the task to the Network Team
- Automatically closes the RITM when the task is completed

## 📋 Catalog Items

1. Network Access Request
2. VPN Access Request
3. Firewall Access Request
4. Wi-Fi Access Request
5. Network Issue / Connectivity Request

## ⚙️ ServiceNow Features Used

- Service Catalog
- Catalog Variables & Variable Sets
- Catalog UI Policies
- Catalog Client Scripts
- Flow Designer
- Approvals
- Custom Network Task table
- Scoped Application
- GitHub Source Control

## 🔄 Workflow

Employee Request  
↓  
REQ → RITM  
↓  
Manager Approval *(for access requests)*  
↓  
Network Task  
↓  
Network Team  
↓  
Task Completed  
↓  
RITM Completed

## 📸 Screenshots

### Request Forms
Screenshots of all 5 catalog request forms.

### Process
Screenshots of variables, approval, Network Task and completed RITM.

### Flow Design
Screenshots of the automation flows.

## 🛠️ Technology

**ServiceNow | Flow Designer | JavaScript | Service Catalog | GitHub**

## 👨‍💻 Author

**Rakesh Pakala**
