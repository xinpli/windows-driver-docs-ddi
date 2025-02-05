---
UID: NF:wdtfedtaction.IWDTFEnhancedDeviceTestSupportActions2.Disable
title: IWDTFEnhancedDeviceTestSupportActions2::Disable (wdtfedtaction.h)
description: Learn how the method disables the Enhanced Device Test (EDT) filter driver on the target device.
old-location: dtf\iwdtfenhanceddevicetestsupportactions2_disable.htm
tech.root: dtf
ms.date: 04/04/2018
keywords: ["IWDTFEnhancedDeviceTestSupportActions2::Disable"]
ms.keywords: Disable, Disable method [Windows Device Testing Framework], Disable method [Windows Device Testing Framework],IWDTFEnhancedDeviceTestSupportActions2 interface, IWDTFEnhancedDeviceTestSupportActions2 interface [Windows Device Testing Framework],Disable method, IWDTFEnhancedDeviceTestSupportActions2.Disable, IWDTFEnhancedDeviceTestSupportActions2::Disable, dtf.iwdtfenhanceddevicetestsupportactions2_disable, wdtfedtaction/IWDTFEnhancedDeviceTestSupportActions2::Disable
req.header: wdtfedtaction.h
req.include-header: 
req.target-type: Desktop
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: WDTFEDTAction.idl
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
f1_keywords:
 - IWDTFEnhancedDeviceTestSupportActions2::Disable
 - wdtfedtaction/IWDTFEnhancedDeviceTestSupportActions2::Disable
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - wdtfedtaction.h
api_name:
 - IWDTFEnhancedDeviceTestSupportActions2::Disable
---

# IWDTFEnhancedDeviceTestSupportActions2::Disable


## -description

Disables the Enhanced Device Test (EDT) filter driver on the target device.

## -parameters

### -param pbRebootRequired 

[out, retval]
True if the operation requires a restart to complete; otherwise, false.

## -returns

If this method succeeds, it returns **S_OK**. Otherwise, it returns an **HRESULT** error code.

