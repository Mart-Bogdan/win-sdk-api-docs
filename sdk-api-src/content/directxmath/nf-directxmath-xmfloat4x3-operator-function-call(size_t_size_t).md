---
UID: NF:directxmath.XMFLOAT4X3.operator-function-call(size_t,size_t)
title: XMFLOAT4X3::operator-function-call(size_t,size_t)
description: Returns a reference to a matrix element of an instance XMFLOAT4X3 as specified by row and column arguments.
helpviewer_keywords: ["XMFLOAT4X3 structure [DirectX Math Support APIs]","operator () method","XMFLOAT4X3.operator ()(size_t","size_t)","XMFLOAT4X3.operator (size_t","size_t)","XMFLOAT4X3.operator()","XMFLOAT4X3.operator-function-call(size_t","size_t)","XMFLOAT4X3::operator()","XMFLOAT4X3::operator-function-call(size_t","size_t)","dxmath.xmfloat4x3_operator_parens_1","operator () method [DirectX Math Support APIs]","operator () method [DirectX Math Support APIs]","XMFLOAT4X3 structure","operator()"]
old-location: dxmath\xmfloat4x3_operator_parens_1.htm
tech.root: dxmath
ms.assetid: M:Microsoft.directx_sdk.reference.XMFLOAT4X3.operator ()(size_t,size_t)
ms.date: 12/05/2018
ms.keywords: XMFLOAT4X3 structure [DirectX Math Support APIs],operator () method, XMFLOAT4X3.operator ()(size_t,size_t), XMFLOAT4X3.operator (size_t,size_t), XMFLOAT4X3.operator(), XMFLOAT4X3.operator-function-call(size_t,size_t), XMFLOAT4X3::operator(), XMFLOAT4X3::operator-function-call(size_t,size_t), dxmath.xmfloat4x3_operator_parens_1, operator () method [DirectX Math Support APIs], operator () method [DirectX Math Support APIs],XMFLOAT4X3 structure, operator()
req.header: directxmath.h
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
req.namespace: Use DirectX.
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
f1_keywords:
 - XMFLOAT4X3::operator()
 - directxmath/XMFLOAT4X3::operator()
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - DirectXMath.h
api_name:
 - XMFLOAT4X3.operator ()
---

# XMFLOAT4X3::operator-function-call(size_t,size_t)


## -description

Returns a <code>reference</code> to a matrix element of an instance <code>XMFLOAT4X3</code> as specified by row and column
  arguments.

This operator returns a <code>reference</code> to a matrix element of an instance <a href="https://msdn.microsoft.com/56bf0a03-e3ea-43ed-a57e-b53f41348ffa">XMFLOAT4X3</a> as
  specified by row and column arguments.
<div class="alert"><b>Note</b>  This operator is only available under C++.</div><div> </div>

## -parameters

### -param Row

Row containing the matrix element of interest. Row specification is 0 based.

### -param Column

Column containing the matrix element of interest. Column specification is 0 based.

## -returns

A <code>reference</code> to the matrix element specified by the operator's <b>Row</b> and <b>Column</b> arguments.

## -remarks

As a <code>reference</code> to the matrix element is returned, this operator can be used to update the value of an element
   of an instance of <code>XMFLOAT4X3</code>.

The following example:

<div class="code"><span codelanguage=""><table>
<tr>
<th></th>
</tr>
<tr>
<td>
<pre>
     XMFLOAT4X3 mat;
     float&amp; a= mat(3,2);
     a=42.0;
    </pre>
</td>
</tr>
</table></span></div>
will set the value of the <i>mat.m[3,2]</i> (or equivalently mat._43) to 42.0.

## -see-also

<b>Reference</b>



<a href="https://msdn.microsoft.com/56bf0a03-e3ea-43ed-a57e-b53f41348ffa">XMFLOAT4X3</a>



<a href="https://msdn.microsoft.com/7abe65f9-41c0-43cd-9f6d-99cee5682191">operator ()</a>

