---
title: "yammerDeviceUsageDistributionUserCounts resource type"
description: "The following is a JSON representation of the resource."
ms.localizationpriority: medium
ms.prod: "reports"
author: "sarahwxy"
doc_type: resourcePageType
---

# yammerDeviceUsageDistributionUserCounts resource type

Namespace: microsoft.graph

## Properties

| Property          | Type   |
| :---------------- | :----- |
| reportRefreshDate | Date   |
| web               | Int32  |
| windowsPhone      | Int32  |
| androidPhone      | Int32  |
| iPhone            | Int32  |
| iPad              | Int32  |
| other             | Int32  |
| reportPeriod      | String |

## JSON representation

The following is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.yammerDeviceUsageDistributionUserCounts"
} -->

```json
{
  "reportRefreshDate": "Date", 
  "web": 1024, 
  "windowsPhone": 1024, 
  "androidPhone": 1024, 
  "iPhone": 1024, 
  "iPad": 1024, 
  "other": 1024, 
  "reportPeriod": "String"
}
```


