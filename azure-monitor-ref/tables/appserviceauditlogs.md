---
title: Azure Monitor Logs reference - AppServiceAuditLogs
description: Reference for AppServiceAuditLogs table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: bwren
author: bwren
ms.date: 4/30/2020
---

# AppServiceAuditLogs

 Logs generated when publishing users successfully log on via one of the App Service publishing protocols.

## Categories

- Azure Resources
## Solutions

- LogManagement
## Resource types

- App Service




## Columns

|Column|Type|Description|
|---|---|---|
|Category|string|Log category name|
|OperationName|string|Name of the operation|
|Protocol|string|Authentication protocol|
|_ResourceId|string||
|SourceSystem|string||
|TenantId|string||
|TimeGenerated|datetime|Time when event is generated|
|Type|string||
|User|string|Username used for publishing access|
|UserAddress|string|Client IP addres of the publishing user|
|UserDisplayName|string|Email address of a user in case publishing was authorized via AAD authentication|
