---
Description: Describes the display mode.
ms.assetid: e83c03ee-2067-45c9-8fd8-8c4db5558df4
title: D3DDISPLAYMODE structure
ms.topic: reference
ms.date: 05/31/2018
topic_type:
- APIRef
- kbSyntax
api_name:
- D3DDISPLAYMODE
api_type:
- HeaderDef
api_location:
- D3D9Types.h
---

# D3DDISPLAYMODE structure

Describes the display mode.

## Syntax


```C++
typedef struct D3DDISPLAYMODE {
  UINT      Width;
  UINT      Height;
  UINT      RefreshRate;
  D3DFORMAT Format;
} D3DDISPLAYMODE, *LPD3DDISPLAYMODE;
```



## Members

<dl> <dt>

**Width**
</dt> <dd>

Type: **[**UINT**](https://msdn.microsoft.com/en-us/library/Aa383751(v=VS.85).aspx)**

</dd> <dd>

Screen width, in pixels.

</dd> <dt>

**Height**
</dt> <dd>

Type: **[**UINT**](https://msdn.microsoft.com/en-us/library/Aa383751(v=VS.85).aspx)**

</dd> <dd>

Screen height, in pixels.

</dd> <dt>

**RefreshRate**
</dt> <dd>

Type: **[**UINT**](https://msdn.microsoft.com/en-us/library/Aa383751(v=VS.85).aspx)**

</dd> <dd>

Refresh rate. The value of 0 indicates an adapter default.

</dd> <dt>

**Format**
</dt> <dd>

Type: **[D3DFORMAT](d3dformat.md)**

</dd> <dd>

Member of the [D3DFORMAT](d3dformat.md) enumerated type, describing the surface format of the display mode.

</dd> </dl>

## Requirements



|                   |                                                                                        |
|-------------------|----------------------------------------------------------------------------------------|
| Header<br/> | <dl> <dt>D3D9Types.h</dt> </dl> |



## See also

<dl> <dt>

[Direct3D Structures](dx9-graphics-reference-d3d-structures.md)
</dt> <dt>

[**EnumAdapterModes**](https://msdn.microsoft.com/library/Bb174314(v=VS.85).aspx)
</dt> <dt>

[**GetAdapterDisplayMode**](https://msdn.microsoft.com/library/Bb174316(v=VS.85).aspx)
</dt> <dt>

[**GetDisplayMode**](https://msdn.microsoft.com/library/Bb174387(v=VS.85).aspx)
</dt> </dl>

 

 




