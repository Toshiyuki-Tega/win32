---
Description: The current latitude/longitude report event interval in milliseconds.
ms.assetid: bb33c4c1-805d-4519-8363-b0221d420b36
title: LocationDisp.LatLongReportFactory.ReportInterval property
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
topic_type: 
- APIRef
- kbSyntax
api_name: 
- LocationDisp.LatLongReportFactory.ReportInterval
api_type: 
- COM
api_location: 
---

# LocationDisp.LatLongReportFactory.ReportInterval property

\[The Location API object model is available for use in the operating systems specified in the Requirements section. It may be altered or unavailable in subsequent versions. Instead, to access location from a website, use the [W3C Geolocation API](https://msdn.microsoft.com/library/gg589513). To access location from a desktop application, use the [**Windows.Devices.Geolocation**](https://msdn.microsoft.com/library/windows/apps/br225603) API.\]

The current latitude/longitude report event interval in milliseconds.

This property is read/write.

## Syntax


```JScript
ReportInterval = LocationDisp.LatLongReportFactory.ReportInterval
LocationDisp.LatLongReportFactory.ReportInterval = ReportInterval
```



## Property value

This property is a read/write **ULONG**.

## Remarks

This value is a request to the location provider. The location provider is not required to provide reports at the interval that you request. Read the value of this property to discover the true report interval setting.

## Requirements



|                                     |                                            |
|-------------------------------------|--------------------------------------------|
| Minimum supported client<br/> | Windows 7 \[desktop apps only\]<br/> |
| Minimum supported server<br/> | None supported<br/>                  |



 

 



