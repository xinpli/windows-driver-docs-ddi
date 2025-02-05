---
UID: NS:d3dkmddi._DXGKARGCB_PINFRAMEBUFFERFORSAVE
title: DXGKARGCB_PINFRAMEBUFFERFORSAVE (d3dkmddi.h)
description: The DXGKARGCB_PINFRAMEBUFFERFORSAVE structure contains the arguments used by the DXGKCB_PINFRAMEBUFFERFORSAVE callback function, to pin the frame buffer for save.
ms.date: 07/22/2021
keywords: ["DXGKARGCB_PINFRAMEBUFFERFORSAVE structure"]
ms.keywords: _DXGKARGCB_PINFRAMEBUFFERFORSAVE, DXGKARGCB_PINFRAMEBUFFERFORSAVE, *INOUT_PDXGKARGCB_PINFRAMEBUFFERFORSAVE
req.header: d3dkmddi.h
req.include-header: 
req.target-type: 
req.target-min-winverclnt: Windows 10, version 1803
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.lib: 
req.dll: 
req.ddi-compliance: 
req.unicode-ansi: 
req.max-support: 
req.typenames: DXGKARGCB_PINFRAMEBUFFERFORSAVE
targetos: Windows
tech.root: display
f1_keywords:
 - _DXGKARGCB_PINFRAMEBUFFERFORSAVE
 - d3dkmddi/_DXGKARGCB_PINFRAMEBUFFERFORSAVE
 - DXGKARGCB_PINFRAMEBUFFERFORSAVE
 - d3dkmddi/DXGKARGCB_PINFRAMEBUFFERFORSAVE
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - d3dkmddi.h
api_name:
 - _DXGKARGCB_PINFRAMEBUFFERFORSAVE
 - DXGKARGCB_PINFRAMEBUFFERFORSAVE
product:
 - Windows
---

# DXGKARGCB_PINFRAMEBUFFERFORSAVE structure

## -description

The **DXGKARGCB_PINFRAMEBUFFERFORSAVE** structure contains the arguments used by the [**DXGKCB_PINFRAMEBUFFERFORSAVE**](nc-d3dkmddi-dxgkcb_pinframebufferforsave.md) callback function, to pin the frame buffer for save.

## -struct-fields

### -field PhysicalAdapterIndex

[in] The index of the physical adapter.

### -field CommitSize

[in] The size, in bytes, that the driver requires to pin. This size must be a multiple of PAGE_SIZE and must be less than or equal to the maximum size specified by the driver during initialization in [**DXGK_FRAMEBUFFERSAVEAREA**](ns-d3dkmddi-_dxgk_framebuffersavearea.md) (during [**DXGKQAITYPE_FRAMEBUFFERSAVESIZE**](ne-d3dkmddi-_dxgk_queryadapterinfotype.md)).

### -field pMdl

[out] An MDL pointing to the pages of the frame buffer save area. These pages are guaranteed to be mapped to the IoMmu.

## -remarks

See [IOMMU-based GPU isolation](/windows-hardware/drivers/display/iommu-based-gpu-isolation) for more information.

## -see-also

[**DXGKCB_PINFRAMEBUFFERFORSAVE**](nc-d3dkmddi-dxgkcb_pinframebufferforsave.md)
