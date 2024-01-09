## Lab 02 - Enabling Microsoft Defender for Cloud

## Lab overview

Enabling Microsoft Defender for Cloud is a proactive measure to secure Azure resources, identify vulnerabilities, and respond to potential security threats. This process enhances the overall security posture and ensures compliance in the dynamic cloud computing landscape. Subsequently, onboarding on-premises servers extends the security framework to cover both Azure and local infrastructure.

## Lab scenario
In this lab, you will enable Microsoft Defender for Cloud on your Azure subscription, configure Defender plans, and seamlessly onboard on-premises Windows servers for enhanced security, threat detection, and compliance management across your hybrid cloud environment

## Lab objectives (Duration: 120 minutes)

In this lab, you will complete the following tasks:
+ Task 1: Enabling Microsoft Defender for Cloud
+ Task 2: Onboard Servers to Defender for Cloud

## Architecture Diagram

![](../media/Lab-2%20arch1.JPG)


### Task 1: Enabling Microsoft Defender for Cloud
In this task, you will be getting started with the functionality of Microsoft Defender for Cloud and how to enable Microsoft Defender for Cloud on a subscription.

   >**Note**: Enabling Microsoft Defender for Cloud is a proactive step toward securing your Azure resources, identifying vulnerabilities, and responding to potential security threats. It helps organizations maintain a robust security posture and adhere to compliance standards in the dynamic landscape of cloud computing.

1.  On Azure Portal page, in **Search resources, services and docs (G+/)** box at the top of the portal, enter **Microsoft Defender for Cloud**, and then select **Microsoft Defender for Cloud** under services.

    ![](../media/image1.png)

1. From left navigation menu and click on **Getting started**.

1. On the **Getting Started** page, under the **Upgrade** tab, make sure **sentinelworkspace** is selected and then select the **Upgrade** button at the bottom of the page.

    ![](../media/s11.png)

1. From the left menu, select **Environment settings** under **Management** section and select the subscription.

     ![Picture 1](../media/image_50.png)

1. Review the Azure resources that are now protected with the Defender for Cloud plans.


1. Click on **Defender Plans** on left blade. Then you need to click on **Settings&Monitoring** inbetween the page at top left.

    ![](../media/image_49.png)

1. Review the monitoring extensions ,Confirm that **Log Analytics agent/Azure Monitor agent** is **Off**  and press **continue** on the top of right side
   
   ![](../media/image4-lab2.png)
    
1. Back on **Settings | Defender plans** blade and click on **Save**.

    ![](../media/image5-lab2.png)

1. To go back to the **Environment settings** and  Close the **Settings | Defender plans** blade by selecting the 'X' on the upper right of the page.

1. Back on **Environment settings** page expand subscription and Select the Log Analytics workspace you created earlier **sentinelworkspace** to review the available options and pricing.

1. Select **Enable all plans** for  services (**servers**) which you want to onboard (to the right of Select Defender plan) and then select **Save**. Wait for the **"Microsoft Defender plan for workspace LogAnalytics-workspace- was saved successfully!"** notification to appear.

   ![](../media/image_4.png)

   >**Note:** If the page is not being displayed, refresh your Edge browser and try again and if Plans are already enable no need to change anything.
   
   >**Note:** Skip this step if services already enabled
   
1. Close the Defender plans page by selecting the 'X' on the upper right of the page to go back to the **Environment settings**

   >**Note**: Enabling Microsoft Defender for Cloud enhances the security of your Azure environment by providing personalized security recommendations, detecting and responding to threats, conducting vulnerability assessments, and ensuring compliance with regulatory standards. It centralizes security management, offers just-in-time access control, and integrates with Azure Policy for enforcing organizational standards.
   
### Task 2: Onboard Servers to Defender for Cloud  
After you connect Defender for Cloud to your Azure subscription, you can start connecting your on-premises machines from the Getting started page in Defender for Cloud.

  >**Note**: In this lab, a pre-created virtual machine (LabVM) will be used to simulate an on-premises server for the onboarding process to Microsoft Defender for Cloud. This virtual machine represents an example of an on-premises Windows server in a controlled environment.

1.  On Azure Portal page, in **Search resources, services and docs (G+/)** box at the top of the portal, enter **Microsoft Defender for Cloud**, and then select **Microsoft Defender for Cloud** under services.

1. On the Defender for Cloud menu, select Getting started.

1. Select the Get started tab.

1. Find Add non-Azure servers and select Configure.

1. Select sentialworkspace Log Analytics workspaces that appears.

1. From the list of workspaces, select Upgrade for the relevant workspace to turn on Defender for Cloud paid plans for 30 free days.

1. From the list of workspaces, select Add Servers for the relevant workspace.

1. On **sentinelworkspace | Agents management** page, expand **Log Analytics agent instructions** copy the Workspace ID and Primary key in notepad you needs this values in next step.

   >**Note**: When you add a Windows server, you need to get the information on the Agents management page and download the appropriate agent file

1. Click on **Download Windows Agent(64 bit)** link.

1. Open downloaded **MMASetup-AMD64.exe** file

1. On **Welcome to the Microsoft Monitoring Agent Setup Wizard** window, click **Next**.

1. On the **Important Notice** window, click **I Agree**.

1. On **Destination Folder** window, click **Next**.

1. On **Agent Setup Option** window select the option **Connect the agent to Azure Log Ananlytics(OMS)**.

1. On **Azure Log Analytics** window, Paste Workspace ID and Primart Key and click **Next** > **Install**.

1. On **Microsoft Monitoring Agent configuration completed successfully**, click finish.

1. From the start menu  search and select **Control panel** then select **System and Security**.

1. Select **Microsoft Monitoring Agent** and on **Microsoft Monitoring Agent properties** window. You can review your configuration there and verify that the agent is connected.

>**Note**: These steps guide you through setting up the necessary components to connect your on-premises Windows servers to Microsoft Defender for Cloud. This integration allows you to leverage the security features, threat detection, and compliance management provided by Defender for Cloud for both your Azure and on-premises infrastructure.

### Conclusion

Enabling Defender for Cloud on Azure subscriptions and extending its coverage to on-premises servers. The proactive security measures align with broader organizational goals, emphasizing continuous monitoring, threat detection, and compliance adherence across the entire hybrid cloud environment. This comprehensive approach ensures a holistic and effective security posture for both Azure and local infrastructure.

### Review
In this lab, you will complete the following tasks:
Enabling Microsoft Defender for Cloud
Onboard Servers to Defender for Cloud
