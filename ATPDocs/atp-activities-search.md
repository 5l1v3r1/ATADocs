---
# required metadata

title: Azure Advanced Threat Protection Monitored Activities Filter and Search | Microsoft Docs
description: This article provides an overview of how to filter and search monitored activities using Azure ATP.
keywords:
author: mlottner
ms.author: mlottner
manager: mbaldwin
ms.date: 10/28/2018
ms.topic: conceptual
ms.prod:
ms.service: azure-advanced-threat-protection
ms.technology:
ms.assetid: a546703b-d5a9-404d-9e87-125523bb8421

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


# Azure ATP monitored activities search and filter 

Activities detected by Azure ATP on your network can be searched and filtered for easy drill-down and organization during your research and investigation into security alerts.  

From the Azure ATP timeline, select any entity in your network (DC, machine, or user) as the filter access point. Next, select to filter by the **Security Alert**, **Activity** type, or any combination. Once the filter is applied, the threat timeline of the entity is updated with the filtered information. Your filtered alerts and activities can also be downloaded to continue your investigation or tracking in other tools. 

![Filter alerts and activities](./media/activities-filter.png)

To filter alerts and activities:
 1. Select the entity to investigate from the Azure ATP timeline. 
 2. Click **Filter by**, then select the alerts and/or activities to filter. 
 3. Click **Apply**. The entity timeline is updated according to the filters you selected. 
 4. To download the filtered activities, click **Download activities** and select the date range for your download report. 
 5. To reset the entity timeline to display all alerts and activities, click **Reset** or close the filter. 


## See Also
- [Investigating entities](investigate-entity.md)
- [Monitoring alerts](monitoring-alerts.md)
- [Working with Security Alerts](working-with-suspicious-activities.md)
- [Check out the ATP forum!](https://aka.ms/azureatpcommunity)
