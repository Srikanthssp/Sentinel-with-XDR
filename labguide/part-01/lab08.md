## Lab 08 - Ingest Logs from Azure Network security Groups

## Lab scenario

A network security group contains security rules that allow or deny inbound network traffic to, or outbound network traffic from, several types of Azure resources. In this lab, you configure the integration of Network security group logs with a Security Information and Event Management (SIEM) system to enable thorough security monitoring and analysis.

## Lab objectives (Duration: 45 minutes)
In this lab, you will complete the following tasks:
- Task 1: Ingesting logs from Azure Network security Groups to Sentinel

## Architecture Diagram

   ![](../media/Lab-8%20arch.JPG)

### Task 1: Ingesting logs from Azure Network Security Groups to Sentinel 

In this task, you will explore the Microsoft Sentinel .

1. On Azure Portal page, in **Search resources, services and docs (G+/)** box at the top of the portal, enter **Microsoft Sentinel**, and then select **Microsoft Sentinel** under services.
     ![Picture 1](../media/image_7.png)

1. Select  **sentinelworkspace**.

1. Select the **Data Connectors** under **Configuration** and select **Go to content hub**.
 
    ![Picture 1](../media/image_34.png)   

1. Search for and select the **Azure Network Security Groups** connector. Select the AD connector.

   ![Picture 1](../media/image_33.png)

1. Click on **Install**.

## Review
In this lab we have completed Ingesting logs from Azure Network security Groups to Sentinel.
