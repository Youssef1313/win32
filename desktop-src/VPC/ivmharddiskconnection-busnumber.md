---
title: IVMHardDiskConnection BusNumber property
description: Retrieves the bus number to which the drive image is attached.
ms.assetid: 2a792930-d8c9-419d-88eb-ddec7c43c5bc
keywords:
- BusNumber property Virtual PC
- BusNumber property Virtual PC , IVMHardDiskConnection interface
- IVMHardDiskConnection interface Virtual PC , BusNumber property
topic_type:
- apiref
api_name:
- IVMHardDiskConnection.BusNumber
- IVMHardDiskConnection.get_BusNumber
api_location:
- VPCCOMInterfaces.h
api_type:
- COM
ms.topic: reference
ms.date: 05/31/2018
---

# IVMHardDiskConnection::BusNumber property

\[Windows Virtual PC is no longer available for use as of Windows 8. Instead, use the [Hyper-V WMI provider (V2)](https://docs.microsoft.com/windows/desktop/HyperV_v2/windows-virtualization-portal).\]

Retrieves the bus number to which the drive image is attached.

This property is read-only.

## Syntax


```C++
HRESULT get_BusNumber(
  [out, retval] long *vmBusNumber
);
```



## Property value

The bus number that corresponds with this connection.

## Error codes



| Name/value                                                                                                                                                       | Meaning                                                                            |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------|
| <dl> <dt>S\_OK</dt> <dt>0</dt> </dl>                          | The operation was successful.<br/>                                           |
| <dl> <dt>E\_POINTER</dt> <dt>0x80004003</dt> </dl>            | The parameter is **NULL** or not valid.<br/>                                 |
| <dl> <dt>VM\_E\_VM\_UNKNOWN</dt> <dt>0xA0040207</dt> </dl>    | The current virtual machine configuration is not valid.<br/>                 |
| <dl> <dt>VM\_E\_DRIVE\_INVALID</dt> <dt>0xA0040502</dt> </dl> | The bus location for this connection has not been properly initialized.<br/> |
| <dl> <dt>DISP\_E\_EXCEPTION</dt> <dt>0x80020009</dt> </dl>    | An unexpected error has occurred.<br/>                                       |



## Requirements



|                                     |                                                                                               |
|-------------------------------------|-----------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows 7 \[desktop apps only\]<br/>                                                    |
| Minimum supported server<br/> | None supported<br/>                                                                     |
| End of client support<br/>    | Windows 7<br/>                                                                          |
| Product<br/>                  | Windows Virtual PC<br/>                                                                 |
| Header<br/>                   | <dl> <dt>VPCCOMInterfaces.h</dt> </dl> |
| IID<br/>                      | IID\_IVMHardDiskconnection is defined as aefa36a5-463a-46ae-9e6c-a1fb4e12e671<br/>      |



## See also

<dl> <dt>

[**IVMHardDiskConnection**](ivmharddiskconnection.md)
</dt> </dl>

 

 





