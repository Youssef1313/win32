---
Description: Specifies whether Real-Time Streaming Protocol (RTSP) transport is enabled in the network source.
ms.assetid: 299393d2-7949-48ef-a36d-19bb8760fc4e
title: MFNETSOURCE_ENABLE_RTSP property
ms.topic: reference
ms.date: 05/31/2018
---

# MFNETSOURCE\_ENABLE\_RTSP property

Specifies whether Real-Time Streaming Protocol (RTSP) transport is enabled in the network source.



Data type

PROPVARIANT type (vt)

PROPVARIANT member

Boolean (**LONG**)

VT\_I4

**lVal**



## Remarks

The constant **MFNETSOURCE\_ENABLE\_RTSP** defines the GUID for this property key. The property identifier (PID) is zero.

Applications can use this property to configure the network source. To set the property, pass an **IPropertyStore** pointer to the source resolver. For more information, see [Configuring a Media Source](configuring-a-media-source.md).

## Requirements



|                                     |                                                                                    |
|-------------------------------------|------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows Vista \[desktop apps only\]<br/>                                     |
| Minimum supported server<br/> | Windows Server 2008 \[desktop apps only\]<br/>                               |
| Header<br/>                   | <dl> <dt>Mfidl.h</dt> </dl> |



## See also

<dl> <dt>

[Media Foundation Properties](media-foundation-properties.md)
</dt> <dt>

[Networking in Media Foundation](networking-in-media-foundation.md)
</dt> <dt>

[Supported Protocols](supported-protocols.md)
</dt> </dl>

 

 




