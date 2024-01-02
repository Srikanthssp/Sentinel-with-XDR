## Lab 01 - Setup sentinel workspace

## Overview
 You are a Security Operations Analyst working at a company . You will start creating a Log Analytics workspace which is a unique environment for log data from Azure Monitor and other Azure services, such as Microsoft Sentinel and Microsoft Defender for Cloud. You will also create Microsoft Sentinel instance to

## Lab objectives ( Duration: 30 minutes)
In this lab, you will complete the following tasks:
- Task 1: Create a Log Analytics Workspace
- Task 2: Create Sentinel Workspace

## Architecture Diagram

![](../media/Lab-1%20arch1.JPG)

### Task 1: Create a Log Analytics Workspace

In this task, you will create a Log Analytics workspace for use with Microsoft Defender for Cloud.

1.  On Azure Portal page, in **Search resources, services and docs (G+/)** box at the top of the portal, enter **Log Analytics workspaces**, and then select **Log Analytics workspaces** under services.
 
     ![](../media/image8.png)

1. Select **+ Create** from the command bar.
    
    ![](../media/image9.png)

1. From the basics tab of the Create Log Analytics workspace, enter the following and Select **Review + Create**.

    | Setting | Action |
    | -- | -- |
    | Subscription |  **Select the given subscription (1)**  |
    | Resource group | select ResourceGroup(sentinel-rg) |
    | Name | **LogAnalyticsworkspaces** |
    | Region | leave this default |
    |||

    ![](../media/Log1.png)

1. Once the workspace validation has passed, select **Create**. Wait for the new workspace to be provisioned, this may take a few minutes.

   ![](../media/image11.png)

### Task 2: Create Sentinel Workspace

In this task, you will create Microsoft Sentinel workspace where you will be monitoring and analyzing security events in upcoming labs.

1.  On Azure Portal page, in **Search resources, services and docs (G+/)** box at the top of the portal, enter **Microsoft Sentinel**, and then select **Microsoft Sentinel** under services.

    ![Picture 1](../media/image_7.png)

1. From the Microsoft Sentinel page, select **+ Create**.

1. From Add Microsoft Sentinel to a workspace, select **+ Create a new workspace**.

1. From the basics tab of the Create Log Analytics workspace, enter the following and click **Review + Create**.   

    | Setting | Action |
    | -- | -- |
    | Subscription |  **Select the given subscription (1)**  |
    | Resource group | select ResourceGroup(sentinel-rg) |
    | Name | sentinelworkspace |
    | Region | leave this default |
    |||

    ![Picture 1](../media/Log2.png)

1. Verify the information you entered then select **Create**.

1. If you don’t see the new workspace listed, select **Refresh**, then select newly created workspace **sentinelworkspace** and click on **Add**.

   ![Picture 1](../media/Log3.png)

1. Once the new workspace is added, the Microsoft Sentinel | News & guides page will display., including that the Microsoft Sentinel free trial is activated. Select **OK**  Note the three steps listed on the Get started page.

   ![Picture 1](../media/image_8.png)
   
   ![Picture 1](../media/image_9.png)

1. Keep this page open, as you will use it in the next task.

## Review
In this lab, you will complete the following tasks:
- Create a Log Analytics Workspace
- Create Sentinel Workspace
