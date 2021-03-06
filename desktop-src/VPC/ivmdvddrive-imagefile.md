---
title: IVMDVDDrive ImageFile property
description: Retrieves the full path of the image file set for this device.
ms.assetid: e7910d37-d3a5-4291-b374-aaa67db50f1b
keywords:
- ImageFile property Virtual PC
- ImageFile property Virtual PC , IVMDVDDrive interface
- IVMDVDDrive interface Virtual PC , ImageFile property
topic_type:
- apiref
api_name:
- IVMDVDDrive.ImageFile
- IVMDVDDrive.get_ImageFile
api_location:
- VPCCOMInterfaces.h
api_type:
- COM
ms.topic: reference
ms.date: 05/31/2018
---

# IVMDVDDrive::ImageFile property

\[Windows Virtual PC is no longer available for use as of Windows 8. Instead, use the [Hyper-V WMI provider (V2)](https://docs.microsoft.com/windows/desktop/HyperV_v2/windows-virtualization-portal).\]

Retrieves the full path of the image file set for this device.

This property is read-only.

## Syntax


```C++
HRESULT get_ImageFile(
  [out, retval] BSTR *imagePath
);
```



## Property value

The full path to the image file.

## Error codes



| Name/value                                                                                                                                                            | Meaning                                                                   |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------|
| <dl> <dt>S\_OK</dt> <dt>0</dt> </dl>                               | The operation was successful.<br/>                                  |
| <dl> <dt>E\_POINTER</dt> <dt>0x80004003</dt> </dl>                 | The parameter is **NULL**.<br/>                                     |
| <dl> <dt>E\_FAIL</dt> <dt>0x80004005</dt> </dl>                    | An unexpected error has occurred.<br/>                              |
| <dl> <dt>VM\_E\_VM\_UNKNOWN</dt> <dt>0xA0040207</dt> </dl>         | The virtual machine could not be found.<br/>                        |
| <dl> <dt>VM\_E\_DRIVE\_INVALID</dt> <dt>0xA0040502</dt> </dl>      | The bus location for this drive is not valid.<br/>                  |
| <dl> <dt>VM\_E\_MEDIA\_WRONG\_TYPE</dt> <dt>0xA00400728</dt> </dl> | The media captured by this DVD drive is not an ISO image file.<br/> |
| <dl> <dt>DISP\_E\_EXCEPTION</dt> <dt>0x80020009</dt> </dl>         | An unexpected error has occurred.<br/>                              |



## Requirements



|                                     |                                                                                               |
|-------------------------------------|-----------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows 7 \[desktop apps only\]<br/>                                                    |
| Minimum supported server<br/> | None supported<br/>                                                                     |
| End of client support<br/>    | Windows 7<br/>                                                                          |
| Product<br/>                  | Windows Virtual PC<br/>                                                                 |
| Header<br/>                   | <dl> <dt>VPCCOMInterfaces.h</dt> </dl> |
| IID<br/>                      | IID\_IVMDVDDrive is defined as b96328f6-6732-437d-a00d-ffa47e43971c<br/>                |



## See also

<dl> <dt>

[**IVMDVDDrive**](ivmdvddrive.md)
</dt> </dl>

 

 





