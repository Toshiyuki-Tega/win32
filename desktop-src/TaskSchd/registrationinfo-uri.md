---
title: RegistrationInfo.URI property
description: For scripting, gets or sets the URI of the task.
ms.assetid: 347898de-7960-42b8-84ff-4734137d0683
keywords:
- URI property Task Scheduler
- URI property Task Scheduler , RegistrationInfo object
- RegistrationInfo object Task Scheduler , URI property
topic_type:
- apiref
api_name:
- RegistrationInfo.URI
api_location:
- taskschd.dll
api_type:
- COM
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# RegistrationInfo.URI property

For scripting, gets or sets the URI of the task.

This property is read/write.

## Syntax


```VB
RegistrationInfo.URI As String
```



## Property value

The URI of the task.

## Remarks

When reading or writing XML for a task, the task URI is specified using the [**URI**](taskschedulerschema-uri-registrationinfotype-element.md) element of the Task Scheduler schema.

## Requirements



|                                     |                                                                                         |
|-------------------------------------|-----------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows Vista \[desktop apps only\]<br/>                                          |
| Minimum supported server<br/> | Windows Server 2008 \[desktop apps only\]<br/>                                    |
| Type library<br/>             | <dl> <dt>Taskschd.tlb</dt> </dl> |
| DLL<br/>                      | <dl> <dt>Taskschd.dll</dt> </dl> |



 

 




