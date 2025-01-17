---
UID: NS:dvdmedia._AM_DVDCOPY_CHLGKEY
title: AM_DVDCOPY_CHLGKEY (dvdmedia.h)
description: Identifies the DVD challenge key.
helpviewer_keywords: ["*PAM_DVDCOPY_CHLGKEY","AM_DVDCOPY_CHLGKEY","AM_DVDCOPY_CHLGKEY structure [DirectShow]","PAM_DVDCOPY_CHLGKEY","PAM_DVDCOPY_CHLGKEY structure pointer [DirectShow]","dshow.am_dvdcopy_chlgkey","dvdmedia/AM_DVDCOPY_CHLGKEY","dvdmedia/PAM_DVDCOPY_CHLGKEY"]
old-location: dshow\am_dvdcopy_chlgkey.htm
tech.root: dshow
ms.assetid: da129f9c-fe30-42f7-b7ca-dfb352b1810d
ms.date: 4/26/2023
ms.keywords: '*PAM_DVDCOPY_CHLGKEY, AM_DVDCOPY_CHLGKEY, AM_DVDCOPY_CHLGKEY structure [DirectShow], PAM_DVDCOPY_CHLGKEY, PAM_DVDCOPY_CHLGKEY structure pointer [DirectShow], dshow.am_dvdcopy_chlgkey, dvdmedia/AM_DVDCOPY_CHLGKEY, dvdmedia/PAM_DVDCOPY_CHLGKEY'
req.header: dvdmedia.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
req.typenames: AM_DVDCOPY_CHLGKEY, *PAM_DVDCOPY_CHLGKEY
req.redist: 
ms.custom: 19H1
f1_keywords:
 - _AM_DVDCOPY_CHLGKEY
 - dvdmedia/_AM_DVDCOPY_CHLGKEY
 - PAM_DVDCOPY_CHLGKEY
 - dvdmedia/PAM_DVDCOPY_CHLGKEY
 - AM_DVDCOPY_CHLGKEY
 - dvdmedia/AM_DVDCOPY_CHLGKEY
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - Dvdmedia.h
api_name:
 - AM_DVDCOPY_CHLGKEY
---

# AM_DVDCOPY_CHLGKEY structure


## -description

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

Identifies the DVD challenge key.

## -struct-fields

### -field ChlgKey

Challenge key.

### -field Reserved

Reserved.

## -remarks

The AM_PROPERTY_DVDCOPY_CHLG_KEY property uses this structure.

A challenge key is used for the DVD CSS key exchange for decryption. Implementors should get a CSS license and further instructions from CSS.

## -see-also

<a href="/windows/desktop/DirectShow/dvd-copy-protection-property-set">DVD Copy Protection Property Set</a>