# 🚀 Project 3 – Azure Monitoring, Backup & Recovery (AZ-104)

## 📌 Overview  
This project demonstrates how to monitor Azure virtual machines using Azure Monitor and VM Insights, configure alerts for performance thresholds, enable Azure Backup for recovery, query logs using KQL in Log Analytics, and validate encryption for secure backup and recovery operations. 

---

## 🎯 Objectives  
- Enable Azure Monitor and VM Insights for performance monitoring  
- Create alerts for high CPU usage with Action Groups  
- Configure Azure Backup using a Recovery Services Vault  
- Query and visualise logs using Log Analytics (KQL)  
- Validate encryption for backup and data in transit  
- Understand disaster recovery concepts using Azure Site Recovery (cost-aware)  

---

## 🧱 Architecture  
- Existing Azure VM (from Project 1)  
- Azure Monitor + VM Insights  
- Log Analytics Workspace  
- Alert Rule + Action Group  
- Recovery Services Vault (Azure Backup)  
- Azure Site Recovery (conceptual / test only)  


## 🛠️ Implementation

### 1️⃣ Azure Monitor & VM Insights  
Enabled VM Insights to collect performance metrics (CPU, memory, disk, network).



### 2️⃣ Alerts & Action Groups  
Created an alert rule to notify when CPU usage exceeds 80%, using an Action Group for email notifications.



### 3️⃣ Azure Backup (Recovery Services Vault)  
Created a Recovery Services Vault and configured daily backups with 7-day retention.  
Triggered a manual backup and verified successful completion.



### 4️⃣ Log Analytics (KQL Queries)  
Queried VM performance data using KQL and visualised average CPU usage over time.


