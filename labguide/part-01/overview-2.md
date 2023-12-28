# SIEM with Microsoft Sentinel 

## Overview

Microsoft Sentinel is a powerful tool for collecting, analyzing, and responding to security data, while threat hunting is a proactive approach that complements automated security measures by actively searching for hidden threats. Together, they form a comprehensive strategy to enhance an organization's cybersecurity posture and protect against a wide range of threats.

### Key features of Microsoft Sentinel

- Log Collection: Microsoft Sentinel collects and centralizes log data from a wide range of sources, including servers, applications, devices, and cloud services.
- Threat Detection: It uses built-in and custom detection rules to identify suspicious activities and security threats in real-time.
- Incident Investigation: Security analysts can use Microsoft Sentinel to investigate incidents, analyze logs, and visualize the scope of security threats.
- Automation: Sentinel offers automation capabilities to respond to common security incidents and orchestrate complex security workflows.
- Threat Intelligence: It integrates with threat intelligence feeds to enrich data and improve threat detection.
Integration: Microsoft Sentinel seamlessly integrates with other Microsoft security solutions and third-party tools.


## Sandbox Scenario
Contoso is a global organization with a complex IT infrastructure that includes a combination of on-premises data centers and cloud-based resources. They are looking to enhance their security posture by deploying Azure Sentinel, Microsoft's cloud-native security information and event management (SIEM), and security orchestration automation and response (SOAR) solution. Additionally, Contoso aims to onboard its cloud resources and servers to Azure Sentinel to gain better visibility and proactive threat detection and response capabilities.

By implementing a robust log analytics and threat detection program, Contoso aims to proactively identify and mitigate threats, reduce the risk of security breaches, and maintain a strong security posture in an ever-evolving threat landscape. This approach will enable Contoso to stay ahead of potential threats and protect its digital assets effectively.

## About the Sandbox

Using this environment, You'll be able to explore complete features and offerings offered by Microsoft Sentinel. Please find the detailed overview of the sandbox environment below.

### Pre-provisioned resources

#### **Virtual Machines**: 

- 2 *Windows Server 2019 Datacenter* Virtual machines, virtual machine-related resources like Virtual networks, Network security groups, managed disks, Network interface cards, and IP addresses are deployed as part of the automation.

  You are recommended to use the same virtual machine throughout the lab for the best experience through out the lab.

#### **License and subscription**: 

- You'll have access to a pre-configured Microsoft user account with an active Azure subscription, a tenant, and a Microsoft 365 E5 license assigned to the user. 
   
  User account has assigned as Owner at subscription and Global administrator at the tenant level. You need to use the same user account throughout the lab to get the most out of the lab. 

#### **Azure Credits**: 

- You have been given a quota of **$83 USD** which includes the running cost of Pre-deployed resources, license cost, and other resources deployed while running through the lab.

  You will receive **cost alerts** to your registered email address at **50%/75%/90%/95%/100%** of the allotted Azure Credit is spent.

  You can visit the Azure Subscription page to check the current Azure credit spend and Analysis on **Cost analysis** tab under the Cost Management option.

  ![Picture 1](../media/o1.jpg)

#### **Duration and Deletion of sandbox**:  

- The sandbox environment will be active for **30 days/730** hours from the time of registration. 
- The allowed uptime of the virtual machine is **40 hours**.
- when 100% of Azure credits are spent, the sandbox environment will get automatically deleted without any prior notification. To retain the environment for a longer period and to get the most out of the environment, please follow the best practices mentioned below.

#### **Best practices**: 

- **Resources usage**: Please stop the virtual machines and other resources when not in use in order to minimize the Azure spend.

- **Azure Cost Analysis**: Maintain a practice of checking the Cost Analysis report of the assigned Azure subscription oftenly in check the Azure spend so that enviornment for a longer duration of time.

- **Alert notifications**: Make sure to check your registered email's inbox for any alert-related mails. Alerts give you can head start to keep your Azure spending in control and to plan out the remaining credits in the best way possible.
## Lab guide Content:

You will have access to a lab guide which is a reference material to assist you in getting started with the exploration. You are encouraged to explore Microsoft Purview further based on your interests and preferences.

- Lab 01 - Setup Sentinel Environment
- Lab 02 - Onboard Server Defender for Cloud
- Lab 03 - Deploy Microsoft Defender for Endpoint
- Lab 04 - Ingest Logs from Microsoft Defender for Cloud
- Lab 05 - Ingest Logs from Microsoft Defender for Endpoint
- Lab 06 - Ingest Logs from Microsoft Entra ID
- Lab 07 - Ingest Logs from Microsoft Purview
- Lab 08 - Ingest Logs from Azure Network Security Groups
- Lab 09 - Ingest Logs from Microsoft 365
- Lab 10 - Ingest Logs from Microsoft Azure Activity
- Lab 11 - Create a Watchlist, Threat Indicator
- Lab 12 - Configure Log Retention
- Lab 13 - Using Sentinel Training Lab
- Lab 14 - Create queries for Microsoft Sentinel using Kusto Query Language (KQL)
- Lab 15 - Use Repositories in Microsoft Sentinel
- Lab 16 - Create workbooks

### Azure services and related products

- Log Analytics Workspace
- Microsoft Defender for Cloud
- Microsoft Defender for Endpoint
- Microsoft Entra ID
- Microsoft Sentinel

