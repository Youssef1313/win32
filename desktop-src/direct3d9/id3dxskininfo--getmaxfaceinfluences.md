---
Description: Gets the maximum face influences in a triangle mesh with the specified index buffer.
ms.assetid: 72dc2440-87df-461e-80d0-9ad9b1e4d8ee
title: ID3DXSkinInfo::GetMaxFaceInfluences method
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# ID3DXSkinInfo::GetMaxFaceInfluences method

Gets the maximum face influences in a triangle mesh with the specified index buffer.

## Syntax


```C++
HRESULT GetMaxFaceInfluences(
  [in] LPDIRECT3DINDEXBUFFER9 pIB,
  [in] DWORD                  NumFaces,
  [in] DWORD                  *maxFaceInfluences
);
```



## Parameters

<dl> <dt>

*pIB* \[in\]
</dt> <dd>

Type: **[**LPDIRECT3DINDEXBUFFER9**](/windows/desktop/api/d3d9helper/nn-d3d9-idirect3dindexbuffer9)**

Pointer to the index buffer that contains the mesh index data.

</dd> <dt>

*NumFaces* \[in\]
</dt> <dd>

Type: **[**DWORD**](https://msdn.microsoft.com/windows/desktop/4553cafc-450e-4493-a4d4-cb6e2f274d46)**

Number of faces in the mesh.

</dd> <dt>

*maxFaceInfluences* \[in\]
</dt> <dd>

Type: **[**DWORD**](https://msdn.microsoft.com/windows/desktop/4553cafc-450e-4493-a4d4-cb6e2f274d46)\***

Pointer to the maximum face influences.

</dd> </dl>

## Return value

Type: **[**HRESULT**](https://msdn.microsoft.com/windows/desktop/455d07e9-52c3-4efb-a9dc-2955cbfd38cc)**

If the method succeeds, the return value is D3D\_OK. If the method fails, the return value can be D3DERR\_INVALIDCALL.

## Requirements



|                    |                                                                                        |
|--------------------|----------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>D3DX9Mesh.h</dt> </dl> |
| Library<br/> | <dl> <dt>D3dx9.lib</dt> </dl>   |



## See also

<dl> <dt>

[ID3DXSkinInfo](id3dxskininfo.md)
</dt> </dl>

 

 



