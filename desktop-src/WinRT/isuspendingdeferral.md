---
Description: Manages a delayed app suspending operation.
ms.assetid: 9F40659E-9B16-4FC9-B320-5679BB8A8161
title: ISuspendingDeferral interface
ms.topic: reference
ms.date: 05/31/2018
topic_type:
- APIRef
- kbSyntax
api_name:
- ISuspendingDeferral
api_type:
- COM
api_location:
- Windows.ApplicationModel.h
---

# ISuspendingDeferral interface

Manages a delayed app suspending operation.

## Members

The **ISuspendingDeferral** interface inherits from [**IInspectable**](https://msdn.microsoft.com/en-us/library/BR205821(v=VS.85).aspx). **ISuspendingDeferral** also has these types of members:

-   [Methods](#methods)

### Methods

The **ISuspendingDeferral** interface has these methods.



| Method                                           | Description                                                                                  |
|:-------------------------------------------------|:---------------------------------------------------------------------------------------------|
| [**Complete**](isuspendingdeferral-complete.md) | Notifies the system that the app has saved its data and is ready to be suspended.<br/> |



 

## Requirements



|                                     |                                                                                                         |
|-------------------------------------|---------------------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows 8 \[desktop apps only\]<br/>                                                              |
| Minimum supported server<br/> | Windows Server 2012 \[desktop apps only\]<br/>                                                    |
| Header<br/>                   | <dl> <dt>Windows.ApplicationModel.h</dt> </dl>   |
| IDL<br/>                      | <dl> <dt>Windows.ApplicationModel.idl</dt> </dl> |



## See also

<dl> <dt>

[**IInspectable**](https://msdn.microsoft.com/en-us/library/BR205821(v=VS.85).aspx)
</dt> <dt>

[**ISuspendingEventArgs**](isuspendingeventargs.md)
</dt> <dt>

[**ISuspendingOperation**](isuspendingoperation.md)
</dt> </dl>

 

 




