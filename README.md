# azure-storage-monitoring-lab
Configuring Azure Storage Account diagnostic settings, log routing, and workspace-level operational alerts.
# Azure Storage Account Telemetry & Automated Workspace Monitoring
<img width="1250" height="619" alt="tempsnip" src="https://github.com/user-attachments/assets/7b961054-8628-4f5c-bae4-33866a620247" />


## Project Overview
This lab demonstrates the configuration of telemetry ingestion, log routing, and proactive alerting for an Azure Storage Account. By centralizing operational logs into a Log Analytics workspace, this project establishes continuous visibility and automated incident notification for cloud storage infrastructure.
<img width="1280" height="618" alt="tempsnip2" src="https://github.com/user-attachments/assets/50342fd5-a970-48ef-8612-07e0aa16cafe" />


## Technical Architecture & Implementation
* **Storage Account Setup**: Provisioned an Azure Storage Account to serve as the monitored resource.
* **Telemetry Ingestion**: Configured **Diagnostic Settings** on the storage account to route blob service operational logs (such as Read, Write, and Delete operations) to a centralized Log Analytics workspace.
* **Workspace Monitoring & Alerting**: Created custom log-based workspace alert rules to monitor storage activity and ensure operational thresholds are met.
* **Incident Notification**: Configured an Azure Monitor Action Group to route automated alerts for system health and operational events.

## Key Skills Demonstrated
* Cloud telemetry configuration and log routing
* Centralized monitoring via Azure Monitor and Log Analytics workspaces
* Proactive incident detection and workspace-level alert rule creation
* Infrastructure documentation and version control using GitHub
