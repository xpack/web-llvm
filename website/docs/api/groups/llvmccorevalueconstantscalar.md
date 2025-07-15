---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/llvmccorevalueconstantscalar
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# The Scalar constants Reference

<p>Functions in this group model <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> instances that correspond to constants referring to scalar types. <a href="#details">More...</a></p>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga06540cbed28286f40b0f625bf05d0233">LLVMConstInt</a> (LLVMTypeRef IntTy, unsigned long long N, LLVMBool SignExtend)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain a constant value for an integer type. <a href="#ga06540cbed28286f40b0f625bf05d0233">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga3ce3363ae52e157bbc63c9fde4aa3821">LLVMConstIntOfArbitraryPrecision</a> (LLVMTypeRef IntTy, unsigned NumWords, const uint64_t Words[])</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain a constant value for an integer of arbitrary precision. <a href="#ga3ce3363ae52e157bbc63c9fde4aa3821">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga6bac11b610129646607e77d41f8d245c">LLVMConstIntOfString</a> (LLVMTypeRef IntTy, const char *Text, uint8_t Radix)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain a constant value for an integer parsed from a string. <a href="#ga6bac11b610129646607e77d41f8d245c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gadef5d5bf755485cad711fbc7b71a2f46">LLVMConstIntOfStringAndSize</a> (LLVMTypeRef IntTy, const char *Text, unsigned SLen, uint8_t Radix)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain a constant value for an integer parsed from a string with specified length. <a href="#gadef5d5bf755485cad711fbc7b71a2f46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaff70032ea5d57ea05794aa42e83ccd44">LLVMConstReal</a> (LLVMTypeRef RealTy, double N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain a constant value referring to a double floating point value. <a href="#gaff70032ea5d57ea05794aa42e83ccd44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaa0e9de3c235f88f2622a88fdd090fe66">LLVMConstRealOfString</a> (LLVMTypeRef RealTy, const char *Text)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain a constant for a floating point value parsed from a string. <a href="#gaa0e9de3c235f88f2622a88fdd090fe66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaaa30ff0f360f30ce9f7810be85bac110">LLVMConstRealOfStringAndSize</a> (LLVMTypeRef RealTy, const char *Text, unsigned SLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain a constant for a floating point value parsed from a string. <a href="#gaaa30ff0f360f30ce9f7810be85bac110">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned long long</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gacbe23851fcf22d025edd2e803be9006f">LLVMConstIntGetZExtValue</a> (LLVMValueRef ConstantVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the zero extended value for an integer constant value. <a href="#gacbe23851fcf22d025edd2e803be9006f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">long long</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gabdc6d4d289016024f2e818cfad078872">LLVMConstIntGetSExtValue</a> (LLVMValueRef ConstantVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the sign extended value for an integer constant value. <a href="#gabdc6d4d289016024f2e818cfad078872">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gab5d3d570a38c53cd67c5288df7d8fdd5">LLVMConstRealGetDouble</a> (LLVMValueRef ConstantVal, LLVMBool *losesInfo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the double value for an floating point constant value. <a href="#gab5d3d570a38c53cd67c5288df7d8fdd5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Functions in this group model <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> instances that correspond to constants referring to scalar types.</p>


<p>For integer types, the <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a> parameter should correspond to a <a href="/web-llvm/docs/api/classes/llvm/integertype">llvm::IntegerType</a> instance and the returned <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> will correspond to a <a href="/web-llvm/docs/api/classes/llvm/constantint">llvm::ConstantInt</a>.</p>


<p>For floating point types, the <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a> returned corresponds to a <a href="/web-llvm/docs/api/classes/llvm/constantfp">llvm::ConstantFP</a>.</p>


<div class="doxySectionDef">

## Functions

### LLVMConstInt() {#ga06540cbed28286f40b0f625bf05d0233}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMValueRef LLVMConstInt (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a> IntTy, unsigned long long N, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> SignExtend)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain a constant value for an integer type.</p>


<p>The returned value corresponds to a <a href="/web-llvm/docs/api/classes/llvm/constantint">llvm::ConstantInt</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>llvm::ConstantInt::get()</p></dd>
</dl>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">IntTy</td>
<td class="doxyParamItemDescription"><p>Integer type to obtain value of.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">N</td>
<td class="doxyParamItemDescription"><p>The value the returned instance should refer to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SignExtend</td>
<td class="doxyParamItemDescription"><p>Whether to sign extend the produced value.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 2227 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 1539 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMConstIntGetSExtValue() {#gabdc6d4d289016024f2e818cfad078872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">long long LLVMConstIntGetSExtValue (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> ConstantVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the sign extended value for an integer constant value.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/constantint/#aa8f4be0661aa64f5b1f20b15e93bb403">llvm::ConstantInt::getSExtValue()</a></p></dd>
</dl>


<p>Declaration at line 2291 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 1581 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMConstIntGetZExtValue() {#gacbe23851fcf22d025edd2e803be9006f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned long long LLVMConstIntGetZExtValue (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> ConstantVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the zero extended value for an integer constant value.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/constantint/#ac09a21c371a9c535cbc13e8f82503aec">llvm::ConstantInt::getZExtValue()</a></p></dd>
</dl>


<p>Declaration at line 2284 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 1577 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMConstIntOfArbitraryPrecision() {#ga3ce3363ae52e157bbc63c9fde4aa3821}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMValueRef LLVMConstIntOfArbitraryPrecision (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a> IntTy, unsigned NumWords, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t Words=[])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain a constant value for an integer of arbitrary precision.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>llvm::ConstantInt::get()</p></dd>
</dl>


<p>Declaration at line 2235 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 1544 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMConstIntOfString() {#ga6bac11b610129646607e77d41f8d245c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMValueRef LLVMConstIntOfString (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a> IntTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Text, uint8_t Radix)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain a constant value for an integer parsed from a string.</p>


<p>A similar API, LLVMConstIntOfStringAndSize is also available. If the string's length is available, it is preferred to call that function instead.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>llvm::ConstantInt::get()</p></dd>
</dl>


<p>Definition at line 2248 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>.</p>

</div>
</div>

### LLVMConstIntOfStringAndSize() {#gadef5d5bf755485cad711fbc7b71a2f46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMValueRef LLVMConstIntOfStringAndSize (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a> IntTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Text, unsigned SLen, uint8_t Radix)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain a constant value for an integer parsed from a string with specified length.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>llvm::ConstantInt::get()</p></dd>
</dl>


<p>Definition at line 2257 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### LLVMConstReal() {#gaff70032ea5d57ea05794aa42e83ccd44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMValueRef LLVMConstReal (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a> RealTy, double N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain a constant value referring to a double floating point value.</p>

<p>Declaration at line 2263 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 1564 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMConstRealGetDouble() {#gab5d3d570a38c53cd67c5288df7d8fdd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double LLVMConstRealGetDouble (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> ConstantVal, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> * losesInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the double value for an floating point constant value.</p>


<p>losesInfo indicates if some precision was lost in the conversion.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>llvm::ConstantFP::getDoubleValue</p></dd>
</dl>


<p>Declaration at line 2299 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 1585 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a257e3cb529defa79ad7a9f42072f339a">llvm::APFloat::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a37733c4c22afc6a48194783dbd25487c">llvm::APFloat::convertToDouble</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a32aa14715eeb813d764fcf20f161f0a1">llvm::ConstantFP::getValueAPF</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a6ba7c3d54a5a714f7a27861ee114cce3">llvm::APFloatBase::IEEEdouble</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMConstRealOfString() {#gaa0e9de3c235f88f2622a88fdd090fe66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMValueRef LLVMConstRealOfString (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a> RealTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Text)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain a constant for a floating point value parsed from a string.</p>


<p>A similar API, LLVMConstRealOfStringAndSize is also available. It should be used if the input string's length is known.</p>


<p>Declaration at line 2271 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 1568 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMConstRealOfStringAndSize() {#gaaa30ff0f360f30ce9f7810be85bac110}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMValueRef LLVMConstRealOfStringAndSize (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a> RealTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Text, unsigned SLen)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain a constant for a floating point value parsed from a string.</p>

<p>Definition at line 2276 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a1960c14773241d6a238d2db593abe552">C</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
