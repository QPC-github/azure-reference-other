---
title: Azure Monitor Logs reference - ExchangeOnlineAssessmentRecommendation
description: Reference for ExchangeOnlineAssessmentRecommendation table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: bwren
author: bwren
ms.date: 9/17/2020
---

# ExchangeOnlineAssessmentRecommendation

 Recommendations generated by Exchange Online assessments that are started through a scheduled task. When you schedule the assessment it runs by default every 7 days and upload the data into Azure Log Analytics

## Categories

- Workloads
## Solutions

- ExchangeOnlineAssessment




## Columns

|Column|Type|Description|
|---|---|---|
|ActionArea|string|The segment in which action is to be performed|
|ActionAreaId|string|ID generated for Action Area|
|AffectedObjectName|string|Name of the affected object|
|AffectedObjectType|string|Type of object which is affected|
|AssessmentId|string|ID of the assessment|
|Computer|string|The machine from which data is uploaded|
|CustomData|string||
|Description|string|Description of the recommendation|
|Domain|string|Domain of the system|
|ExchangeOrganization|string||
|FocusArea|string|Area to be focussed on|
|FocusAreaId|string|ID of the Focus Area|
|O365TenantId|string|ID of O365 Tenant|
|Recommendation|string|Generated recommendation|
|RecommendationId|string|ID of the recommendation generated|
|RecommendationResult|string|Result of the recommendation generated|
|RecommendationWeight|real|Weight of recommendation|
|SourceSystem|string||
|Technology|string||
|TenantName|string|Name of the Tenant|
|TimeGenerated|datetime|Date and time the record was created.|
|Type|string|The name of the table|