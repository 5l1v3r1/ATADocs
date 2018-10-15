---
# required metadata

title: Change Azure Advanced Threat Protection config - domain connectivity password | Microsoft Docs
description: Describes how to change the Domain Connectivity Password on the Azure ATP standalone sensor.
keywords:
author: mlottner
ms.author: mlottner
manager: mbaldwin
ms.date: 10/04/2018
ms.topic: conceptual
ms.prod:
ms.service: azure-advanced-threat-protection
ms.technology:
ms.assetid: e7f065fa-1ad1-4e87-bd80-99cc695efbf5

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
ms.reviewer: itargoet
ms.suite: ems
#ms.tgt_pltfrm:
#ms.custom:

---

*Applies to: Azure Advanced Threat Protection*



# Change Azure ATP workspace portal configuration - domain connectivity password



## Change the domain connectivity password
If you need to modify the Domain Connectivity Password, make sure that the password you enter is correct. If it is not, the Azure ATP sensor service stops for all deployed sensors.

If you suspect that this happened, on the Azure ATP standalone sensor, look at the Microsoft.Tri.sensor-Errors.log file for the following errors:
`The supplied credential is invalid.`

Follow this procedure to update the Domain Connectivity password on the Azure ATP portal:

> [!NOTE]
> This is the user name and password from the Active Directory on-premises deployment and not from Azure AD.

1.  Open the Azure ATP portal on the by accessing the workspace URL.

2.  Select the settings option on the toolbar and select **Configuration**.

    ![Azure ATP configuration settings icon](media/atp-config-menu.png)

3.  Select **Directory Services**.

    ![Azure ATP standalone sensor change password image](media/directory-services.png)

4.  Under **Password**, change the password.

 > [!NOTE]
 > Enter an Active Directory user and password here, not Azure Active Directory.

5.  Click **Save**.

6.  After changing the password, manually check that the Azure ATP standalone sensor service is running on the Azure ATP standalone sensor servers.

7. In the Azure ATP portal, under **Configuration**, go to the **Sensor** page and check the status of the sensors.

## See Also

- [Integration with Windows Defender ATP](integrate-wd-atp.md)
- [Check out the Azure ATP forum!](https://aka.ms/azureatpcommunity)