---
title: Azure Monitor Logs reference - ContainerImageInventory
description: Reference for ContainerImageInventory table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: bwren
author: bwren
ms.date: 9/17/2020
---

# ContainerImageInventory

 Inventory of container Images and their attributes that were discovered by the agent

## Categories

- Containers
## Solutions

- Container Monitoring Solution
- ContainerInsights
## Resource types

- Kubernetes Services




## Columns

|Column|Type|Description|
|---|---|---|
|Computer|string|Computer name/Node name|
|Failed|int|Count of containers with this image that are in failed state|
|Image|string|Name of Container Image|
|ImageID|string|Image ID of the container image|
|ImageSize|string|Size of the container image [amount of data (on disk) that is used for the writable layer]|
|ImageTag|string|Tag of the container image|
|Paused|int|Count of containers with this image that are in paused state|
|Repository|string||
|_ResourceId|string|A unique identifier for the resource that the record is associated with|
|Running|int|Count of containers with this image that are in running state|
|SourceSystem|string|Type of agent the data was collected from. This will be 'Containers'|
|Stopped|int|Count of containers with this image that are in stopped state|
|TimeGenerated|datetime|Date and time the record was created.|
|TotalContainer|long|Count of containers with this ContainerImage|
|Type|string|The name of the table|
|VirtualSize|string|Virtual Size of the Container Image [Total amount of disk-space used for the read-only image data]|