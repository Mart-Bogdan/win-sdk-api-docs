---
UID: NN:shobjidl_core.IAssocHandlerInvoker
title: IAssocHandlerInvoker (shobjidl_core.h)
description: Exposes methods that invoke an associated application handler.
helpviewer_keywords: ["IAssocHandlerInvoker","IAssocHandlerInvoker interface [Windows Shell]","IAssocHandlerInvoker interface [Windows Shell]","described","_shell_IAssocHandlerInvoker","shell.IAssocHandlerInvoker","shobjidl_core/IAssocHandlerInvoker"]
old-location: shell\IAssocHandlerInvoker.htm
tech.root: shell
ms.assetid: b602280e-4237-4539-9a10-cec21c65e90d
ms.date: 12/05/2018
ms.keywords: IAssocHandlerInvoker, IAssocHandlerInvoker interface [Windows Shell], IAssocHandlerInvoker interface [Windows Shell],described, _shell_IAssocHandlerInvoker, shell.IAssocHandlerInvoker, shobjidl_core/IAssocHandlerInvoker
req.header: shobjidl_core.h
req.include-header: Shobjidl.h
req.target-type: Windows
req.target-min-winverclnt: Windows Vista [desktop apps only]
req.target-min-winversvr: Windows Server 2008 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Shobjidl.idl
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - IAssocHandlerInvoker
 - shobjidl_core/IAssocHandlerInvoker
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - shobjidl_core.h
api_name:
 - IAssocHandlerInvoker
---

# IAssocHandlerInvoker interface


## -description

Exposes methods that invoke an associated application handler.

## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">IAssocHandlerInvoker</b> interface inherits from the <a href="/windows/desktop/api/unknwn/nn-unknwn-iunknown">IUnknown</a> interface. <b>IAssocHandlerInvoker</b> also has these types of members:
<ul>
<li><a href="https://docs.microsoft.com/">Methods</a></li>
</ul>

## -members

The <b>IAssocHandlerInvoker</b> interface has these methods.
<table class="members" id="memberListMethods">
<tr>
<th align="left" width="37%">Method</th>
<th align="left" width="63%">Description</th>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="/windows/desktop/api/shobjidl_core/nf-shobjidl_core-iassochandlerinvoker-invoke">Invoke</a>
</td>
<td align="left" width="63%">
Invokes an associated application handler.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="/windows/desktop/api/shobjidl_core/nf-shobjidl_core-iassochandlerinvoker-supportsselection">SupportsSelection</a>
</td>
<td align="left" width="63%">
Determines whether an invoker supports its selection.

</td>
</tr>
</table>

## -see-also

<a href="/windows/desktop/api/shobjidl_core/nn-shobjidl_core-iassochandler">IAssocHandler</a>



<a href="/windows/desktop/api/shobjidl_core/nn-shobjidl_core-ienumassochandlers">IEnumAssocHandlers</a>



<a href="/windows/desktop/api/shobjidl_core/nf-shobjidl_core-shassocenumhandlers">SHAssocEnumHandlers</a>