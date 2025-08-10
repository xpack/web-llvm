---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `DXILOpBuilder.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-h">DXILOpBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilconstants-h">DXILConstants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dxilabi-h">llvm/Support/DXILABI.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include &lt;optional&gt;
#include "DXILOperation.inc"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-dxilopbuilder-cpp-">anonymous{DXILOpBuilder.cpp}</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dxil">dxil</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-dxilopbuilder-cpp-/version">Version</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-dxilopbuilder-cpp-/opoverload">OpOverload</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/opstage">OpStage</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/opcodeproperty">OpCodeProperty</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c94374db169a7d5de14925f8e8d1415">getOverloadTypeName</a> (OverloadKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static OverloadKind</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b04886780c4fb4764f2b6dbc1d3d2d9">getOverloadKind</a> (Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b3a962dc6532bf208fdccf1055119f0">getTypeName</a> (OverloadKind Kind, Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac921fd99ff39f6037d7f82d81ee8d87a">constructOverloadName</a> (OverloadKind Kind, Type *Ty, const OpCodeProperty &amp;Prop)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad247e8449783ab17d92c38551d61f09e">constructOverloadTypeName</a> (OverloadKind Kind, StringRef TypeName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b36c3934c9c2e8a2dc9fcb4cdee876b">getOrCreateStructType</a> (StringRef Name, ArrayRef&lt; Type * &gt; EltTys, LLVMContext &amp;Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05bf02ad372b0e58afd80f2378cfac94">getResRetType</a> (Type *ElementTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa998073715bffba8d6e44ddcf3e19f2b">getHandleType</a> (LLVMContext &amp;Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff234d51ccd591da6c1332a3d52fbe1e">getResBindType</a> (LLVMContext &amp;Context)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af69be60078714a34c733e198b5aab9af">getResPropsType</a> (LLVMContext &amp;Context)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f6846040fc48f21e5969492bbb88fdc">getSplitDoubleType</a> (LLVMContext &amp;Context)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c4f92e821d5bc282b226a8ba057a213">getTypeFromOpParamType</a> (OpParamType Kind, LLVMContext &amp;Ctx, Type *OverloadTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static ShaderKind</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18cba992d12aa58de48357908b9e1169">getShaderKindEnum</a> (Triple::EnvironmentType EnvType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36bdcdb68f8b041f4f5886de8da52bc1">getArgTypesFromOpParamTypes</a> (ArrayRef&lt; dxil::OpParamType &gt; Types, LLVMContext &amp;Context, Type *OverloadTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc8e6bea7e5502aec0248a1441e9b720">getDXILOpFunctionType</a> (dxil::OpCode OpCode, LLVMContext &amp;Context, Type *OverloadTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct DXIL function type. <a href="#acc8e6bea7e5502aec0248a1441e9b720">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3030fa8e5d4a78aef7c5a7fa00294ac6">getPropIndex</a> (ArrayRef&lt; T &gt; PropList, const VersionTuple DXILVer) -&gt; std::optional&lt; size_t &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get index of the property from PropList valid for the most recent DXIL version not greater than DXILVer. <a href="#a3030fa8e5d4a78aef7c5a7fa00294ac6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e1fd5d9c5ee4c9aac8931011337fced">computeSwitchEnum</a> (dxil::OpCode OpCode, uint16_t VersionMajor, uint16_t VersionMinor)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/dxil/attributes">dxil::Attributes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf6c1a9b39b2459374f41ddd34153b6f">getDXILAttributes</a> (dxil::OpCode OpCode, VersionTuple DXILVersion)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f67233011e3c2264e7806412baa1595">setDXILAttributes</a> (CallInst *CI, dxil::OpCode OpCode, VersionTuple DXILVersion)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0fa85ab79bac10513060a1db62093c8">DXILOpNamePrefix</a> = "dx.op."</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7941b1cd5e48ddf5c7eb63fb43d8d71c">DXIL_OP_OPERATION_TABLE</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a409cc48873cd68306603991ea3837b33">DXIL_OP_FUNCTION_TYPE</a>(OpCode, RetType, ...)&nbsp;&nbsp;&nbsp;...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adeff96061c4fb93b4754a0334bbfe1a7">DXIL_VERSION</a>(MAJOR, MINOR)&nbsp;&nbsp;&nbsp;{MAJOR, MINOR},</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b17cd335de5fc6606b2477ea5122746">DXIL_OP_ATTRIBUTES</a>(OpCode, VersionMajor, VersionMinor, ...)&nbsp;&nbsp;&nbsp;...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### computeSwitchEnum() {#a7e1fd5d9c5ee4c9aac8931011337fced}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr uint64_t computeSwitchEnum (<a href="/web-llvm/docs/api/namespaces/llvm/dxil/#ac64683c1985c78d81b50819a0b733f48">dxil::OpCode</a> OpCode, uint16_t VersionMajor, uint16_t VersionMinor)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>


<p>Referenced by <a href="#abf6c1a9b39b2459374f41ddd34153b6f">getDXILAttributes</a>.</p>

</div>
</div>

### constructOverloadName() {#ac921fd99ff39f6037d7f82d81ee8d87a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string constructOverloadName (OverloadKind Kind, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/opcodeproperty">OpCodeProperty</a> &amp; Prop)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>


<p>References <a href="#ad0fa85ab79bac10513060a1db62093c8">DXILOpNamePrefix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac1b702e99f1978f2dd36cac2f7400f">llvm::getTypeName</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-dxilopbuilder-cpp-/#a3fe8fcf1f03e5da864eb86be303a3216a024a9a32ecf675c926c758581f6bf9bd">anonymous{DXILOpBuilder.cpp}::VOID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/dxilopbuilder/#a871def99cd40b0a7df2e3f22387198cc">llvm::dxil::DXILOpBuilder::tryCreateOp</a>.</p>

</div>
</div>

### constructOverloadTypeName() {#ad247e8449783ab17d92c38551d61f09e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string constructOverloadTypeName (OverloadKind Kind, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TypeName)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4c94374db169a7d5de14925f8e8d1415">getOverloadTypeName</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxilopbuilder-cpp-/#a3fe8fcf1f03e5da864eb86be303a3216acf3f514bb7a7f97c8c6bc38334ffb02f">anonymous{DXILOpBuilder.cpp}::UserDefineType</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-dxilopbuilder-cpp-/#a3fe8fcf1f03e5da864eb86be303a3216a024a9a32ecf675c926c758581f6bf9bd">anonymous{DXILOpBuilder.cpp}::VOID</a>.</p>


<p>Referenced by <a href="#a05bf02ad372b0e58afd80f2378cfac94">getResRetType</a>.</p>

</div>
</div>

### getArgTypesFromOpParamTypes() {#a36bdcdb68f8b041f4f5886de8da52bc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; Type * &gt; getArgTypesFromOpParamTypes (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a66c1660c700858728695b449589b8866">dxil::OpParamType</a> &gt; Types, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * OverloadTy)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a> and <a href="#a2c4f92e821d5bc282b226a8ba057a213">getTypeFromOpParamType</a>.</p>

</div>
</div>

### getDXILAttributes() {#abf6c1a9b39b2459374f41ddd34153b6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dxil::Attributes getDXILAttributes (<a href="/web-llvm/docs/api/namespaces/llvm/dxil/#ac64683c1985c78d81b50819a0b733f48">dxil::OpCode</a> OpCode, <a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a> DXILVersion)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>


<p>References <a href="#a7e1fd5d9c5ee4c9aac8931011337fced">computeSwitchEnum</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>


<p>Referenced by <a href="#a3f67233011e3c2264e7806412baa1595">setDXILAttributes</a>.</p>

</div>
</div>

### getDXILOpFunctionType() {#acc8e6bea7e5502aec0248a1441e9b720}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType * getDXILOpFunctionType (<a href="/web-llvm/docs/api/namespaces/llvm/dxil/#ac64683c1985c78d81b50819a0b733f48">dxil::OpCode</a> OpCode, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * OverloadTy)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct DXIL function type.</p>


<p>This is the type of a function with the following prototype OverloadType dx.op.&lt;opclass&gt;.&lt;return-type&gt;(int opcode, ) &lt;param-types&gt; are constructed from types in Prop.</p>


<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/dxilopbuilder/#a871def99cd40b0a7df2e3f22387198cc">llvm::dxil::DXILOpBuilder::tryCreateOp</a>.</p>

</div>
</div>

### getHandleType() {#aa998073715bffba8d6e44ddcf3e19f2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructType * getHandleType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>


<p>References <a href="#a9b36c3934c9c2e8a2dc9fcb4cdee876b">getOrCreateStructType</a> and <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>.</p>


<p>Referenced by <a href="#a2c4f92e821d5bc282b226a8ba057a213">getTypeFromOpParamType</a>.</p>

</div>
</div>

### getOrCreateStructType() {#a9b36c3934c9c2e8a2dc9fcb4cdee876b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructType * getOrCreateStructType (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; EltTys, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/structtype/#a82648246c07eb8a33f628eea28cb988c">llvm::StructType::create</a> and <a href="/web-llvm/docs/api/classes/llvm/structtype/#a75a89f1513d9f9bdcf0366a436ca43b5">llvm::StructType::getTypeByName</a>.</p>


<p>Referenced by <a href="#aa998073715bffba8d6e44ddcf3e19f2b">getHandleType</a> and <a href="#a05bf02ad372b0e58afd80f2378cfac94">getResRetType</a>.</p>

</div>
</div>

### getOverloadKind() {#a6b04886780c4fb4764f2b6dbc1d3d2d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OverloadKind getOverloadKind (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxilopbuilder-cpp-/#a3fe8fcf1f03e5da864eb86be303a3216a2101ebdffa84e38fb11a5cb6b68b04d9">anonymous{DXILOpBuilder.cpp}::DOUBLE</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabc549945f13bb5d5f5b80c550d2b92f5">llvm::Type::DoubleTyID</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxilopbuilder-cpp-/#a3fe8fcf1f03e5da864eb86be303a3216a0cb2f05d3d3bae54de28f97a63bc7609">anonymous{DXILOpBuilder.cpp}::FLOAT</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15">llvm::Type::FloatTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a90b790ccb1af4ea5ccd69db4b8cd2d81">llvm::IntegerType::getBitWidth</a>, <a href="#a6b04886780c4fb4764f2b6dbc1d3d2d9">getOverloadKind</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxilopbuilder-cpp-/#a3fe8fcf1f03e5da864eb86be303a3216a7335e3c4796125b052339203e9bee87c">anonymous{DXILOpBuilder.cpp}::HALF</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa301c3a4cc2bfd399628cfd473f383ff9">llvm::Type::HalfTyID</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxilopbuilder-cpp-/#a3fe8fcf1f03e5da864eb86be303a3216a0bfbc695c285082c59ed77069aafbfae">anonymous{DXILOpBuilder.cpp}::I1</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxilopbuilder-cpp-/#a3fe8fcf1f03e5da864eb86be303a3216a5526adc82ddfe412c99755949207ecf0">anonymous{DXILOpBuilder.cpp}::I16</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxilopbuilder-cpp-/#a3fe8fcf1f03e5da864eb86be303a3216a1f0bcb70cad1532c77dd33155ac68acc">anonymous{DXILOpBuilder.cpp}::I32</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxilopbuilder-cpp-/#a3fe8fcf1f03e5da864eb86be303a3216a22de29aa2be8f8e321df4e69eded5d07">anonymous{DXILOpBuilder.cpp}::I64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxilopbuilder-cpp-/#a3fe8fcf1f03e5da864eb86be303a3216ac383fd0eb699cf3a30312ec776eebaa2">anonymous{DXILOpBuilder.cpp}::I8</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa8e724092b0496fe3d16e29863b46c249">llvm::Type::IntegerTyID</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaae68df805bc15b023748c2a78b80563ff">llvm::Type::PointerTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa812a573d23fbb37aacd025e2a0588156">llvm::Type::StructTyID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxilopbuilder-cpp-/#a3fe8fcf1f03e5da864eb86be303a3216a9045349aadd51459c6dbe4f3b1c43217">anonymous{DXILOpBuilder.cpp}::UNDEFINED</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxilopbuilder-cpp-/#a3fe8fcf1f03e5da864eb86be303a3216acf3f514bb7a7f97c8c6bc38334ffb02f">anonymous{DXILOpBuilder.cpp}::UserDefineType</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxilopbuilder-cpp-/#a3fe8fcf1f03e5da864eb86be303a3216a024a9a32ecf675c926c758581f6bf9bd">anonymous{DXILOpBuilder.cpp}::VOID</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa567ac2c7944f770cfb2c2cffc94b3520">llvm::Type::VoidTyID</a>.</p>


<p>Referenced by <a href="#a6b04886780c4fb4764f2b6dbc1d3d2d9">getOverloadKind</a>, <a href="#a05bf02ad372b0e58afd80f2378cfac94">getResRetType</a> and <a href="/web-llvm/docs/api/classes/llvm/dxil/dxilopbuilder/#a871def99cd40b0a7df2e3f22387198cc">llvm::dxil::DXILOpBuilder::tryCreateOp</a>.</p>

</div>
</div>

### getOverloadTypeName() {#a4c94374db169a7d5de14925f8e8d1415}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * getOverloadTypeName (OverloadKind Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-dxilopbuilder-cpp-/#a3fe8fcf1f03e5da864eb86be303a3216a2101ebdffa84e38fb11a5cb6b68b04d9">anonymous{DXILOpBuilder.cpp}::DOUBLE</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxilopbuilder-cpp-/#a3fe8fcf1f03e5da864eb86be303a3216a0cb2f05d3d3bae54de28f97a63bc7609">anonymous{DXILOpBuilder.cpp}::FLOAT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxilopbuilder-cpp-/#a3fe8fcf1f03e5da864eb86be303a3216a7335e3c4796125b052339203e9bee87c">anonymous{DXILOpBuilder.cpp}::HALF</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxilopbuilder-cpp-/#a3fe8fcf1f03e5da864eb86be303a3216a0bfbc695c285082c59ed77069aafbfae">anonymous{DXILOpBuilder.cpp}::I1</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxilopbuilder-cpp-/#a3fe8fcf1f03e5da864eb86be303a3216a5526adc82ddfe412c99755949207ecf0">anonymous{DXILOpBuilder.cpp}::I16</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxilopbuilder-cpp-/#a3fe8fcf1f03e5da864eb86be303a3216a1f0bcb70cad1532c77dd33155ac68acc">anonymous{DXILOpBuilder.cpp}::I32</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxilopbuilder-cpp-/#a3fe8fcf1f03e5da864eb86be303a3216a22de29aa2be8f8e321df4e69eded5d07">anonymous{DXILOpBuilder.cpp}::I64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxilopbuilder-cpp-/#a3fe8fcf1f03e5da864eb86be303a3216ac383fd0eb699cf3a30312ec776eebaa2">anonymous{DXILOpBuilder.cpp}::I8</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxilopbuilder-cpp-/#a3fe8fcf1f03e5da864eb86be303a3216a1955f73644e78a3ffadcf645300a22c2">anonymous{DXILOpBuilder.cpp}::ObjectType</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxilopbuilder-cpp-/#a3fe8fcf1f03e5da864eb86be303a3216a9045349aadd51459c6dbe4f3b1c43217">anonymous{DXILOpBuilder.cpp}::UNDEFINED</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxilopbuilder-cpp-/#a3fe8fcf1f03e5da864eb86be303a3216acf3f514bb7a7f97c8c6bc38334ffb02f">anonymous{DXILOpBuilder.cpp}::UserDefineType</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-dxilopbuilder-cpp-/#a3fe8fcf1f03e5da864eb86be303a3216a024a9a32ecf675c926c758581f6bf9bd">anonymous{DXILOpBuilder.cpp}::VOID</a>.</p>


<p>Referenced by <a href="#ad247e8449783ab17d92c38551d61f09e">constructOverloadTypeName</a> and <a href="#a5b3a962dc6532bf208fdccf1055119f0">getTypeName</a>.</p>

</div>
</div>

### getPropIndex() {#a3030fa8e5d4a78aef7c5a7fa00294ac6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; size_t &gt; getPropIndex (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt; PropList, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a> DXILVer)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get index of the property from PropList valid for the most recent DXIL version not greater than DXILVer.</p>


<p>PropList is expected to be sorted in ascending order of DXIL version.</p>


<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aebe6da1ab4a07020669f3d6148c0b559">llvm::ArrayRef&lt; T &gt;::rbegin</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a709f5d7f042648ec20197939d9a6805f">llvm::ArrayRef&lt; T &gt;::rend</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/dxilopbuilder/#a871def99cd40b0a7df2e3f22387198cc">llvm::dxil::DXILOpBuilder::tryCreateOp</a>.</p>

</div>
</div>

### getResBindType() {#aff234d51ccd591da6c1332a3d52fbe1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructType * getResBindType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/structtype/#a82648246c07eb8a33f628eea28cb988c">llvm::StructType::create</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7ba5de75f50bb4a4ba920698edf39b28">llvm::Type::getInt8Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a75a89f1513d9f9bdcf0366a436ca43b5">llvm::StructType::getTypeByName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a23f9ec4bb2576ca8738f3edc9c4f5cdf">llvm::Int32Ty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/dxilopbuilder/#aa522833bf3162eb609d51cefb341314f">llvm::dxil::DXILOpBuilder::getResBind</a> and <a href="#a2c4f92e821d5bc282b226a8ba057a213">getTypeFromOpParamType</a>.</p>

</div>
</div>

### getResPropsType() {#af69be60078714a34c733e198b5aab9af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructType * getResPropsType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/structtype/#a82648246c07eb8a33f628eea28cb988c">llvm::StructType::create</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a75a89f1513d9f9bdcf0366a436ca43b5">llvm::StructType::getTypeByName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a23f9ec4bb2576ca8738f3edc9c4f5cdf">llvm::Int32Ty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/dxilopbuilder/#ae2a45afdcb63e6c39a556e3e5b9610bc">llvm::dxil::DXILOpBuilder::getResProps</a> and <a href="#a2c4f92e821d5bc282b226a8ba057a213">getTypeFromOpParamType</a>.</p>

</div>
</div>

### getResRetType() {#a05bf02ad372b0e58afd80f2378cfac94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructType * getResRetType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElementTy)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>


<p>References <a href="#ad247e8449783ab17d92c38551d61f09e">constructOverloadTypeName</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a909eca4ba9e5eefc203c8e3770bdab25">llvm::Type::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="#a9b36c3934c9c2e8a2dc9fcb4cdee876b">getOrCreateStructType</a> and <a href="#a6b04886780c4fb4764f2b6dbc1d3d2d9">getOverloadKind</a>.</p>


<p>Referenced by <a href="#a2c4f92e821d5bc282b226a8ba057a213">getTypeFromOpParamType</a>.</p>

</div>
</div>

### getShaderKindEnum() {#a18cba992d12aa58de48357908b9e1169}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ShaderKind getShaderKindEnum (<a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324">Triple::EnvironmentType</a> EnvType)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324ab926bec66aeb0288525973f203bcb94a">llvm::Triple::Amplification</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324ab73388cc76387a636177ac9e405d0b39">llvm::Triple::AnyHit</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324adf4a58c1d4eb1aeba280a3fc580e9f8d">llvm::Triple::Callable</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a783d818fcc0a9d1e095674aa7b255082">llvm::Triple::ClosestHit</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a35a7d7865588f76c4f300fb1f07ee1bc">llvm::Triple::Compute</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a9250a1f506b7407b838bf0b494f9cd33">llvm::Triple::Domain</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324ade3aad57a34a47654ebeee1a2d4ab960">llvm::Triple::Geometry</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324ac8bc9b9934c75b722dcdde3b705c0a51">llvm::Triple::Hull</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324ac5ff0a8f8e278b84cdd8518a6e0c67d8">llvm::Triple::Intersection</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a38ed328b8551b06c5a133e54867110bf">llvm::Triple::Library</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324aa1a97c079fbb80fcd9ab0f5fa24f3025">llvm::Triple::Mesh</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324ad6c99823a0c7477c6412728485bb0fe7">llvm::Triple::Miss</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a4bd403d91c4535171833f92e0ce36137">llvm::Triple::Pixel</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a15bc4c083c1cda54e3011297b4bf8351">llvm::Triple::RayGeneration</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a71b983b2a1bf8a46c5ac7d21de26fb4a">llvm::Triple::Vertex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/dxilopbuilder/#a871def99cd40b0a7df2e3f22387198cc">llvm::dxil::DXILOpBuilder::tryCreateOp</a>.</p>

</div>
</div>

### getSplitDoubleType() {#a5f6846040fc48f21e5969492bbb88fdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructType * getSplitDoubleType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/structtype/#a82648246c07eb8a33f628eea28cb988c">llvm::StructType::create</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a75a89f1513d9f9bdcf0366a436ca43b5">llvm::StructType::getTypeByName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a23f9ec4bb2576ca8738f3edc9c4f5cdf">llvm::Int32Ty</a>.</p>


<p>Referenced by <a href="#a2c4f92e821d5bc282b226a8ba057a213">getTypeFromOpParamType</a>.</p>

</div>
</div>

### getTypeFromOpParamType() {#a2c4f92e821d5bc282b226a8ba057a213}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * getTypeFromOpParamType (<a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a66c1660c700858728695b449589b8866">OpParamType</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * OverloadTy)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#acb145f988329d1d621f73abcafea21d8">llvm::Type::getDoubleTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ad5e0fe0efdd88f98a5b5eb512d5351c2">llvm::Type::getFloatTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ae550f2e9436b395b614b4377ba27007f">llvm::Type::getHalfTy</a>, <a href="#aa998073715bffba8d6e44ddcf3e19f2b">getHandleType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a87f56db834c58ca630624956ecf6972f">llvm::Type::getInt16Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa75984a442f2379de0c66018201fa628">llvm::Type::getInt1Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7ba5de75f50bb4a4ba920698edf39b28">llvm::Type::getInt8Ty</a>, <a href="#aff234d51ccd591da6c1332a3d52fbe1e">getResBindType</a>, <a href="#af69be60078714a34c733e198b5aab9af">getResPropsType</a>, <a href="#a05bf02ad372b0e58afd80f2378cfac94">getResRetType</a>, <a href="#a5f6846040fc48f21e5969492bbb88fdc">getSplitDoubleType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a6e20e76960d952de088354cbcd14c3ab">llvm::Type::getVoidTy</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a36bdcdb68f8b041f4f5886de8da52bc1">getArgTypesFromOpParamTypes</a>.</p>

</div>
</div>

### getTypeName() {#a5b3a962dc6532bf208fdccf1055119f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string getTypeName (OverloadKind Kind, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a4c94374db169a7d5de14925f8e8d1415">getOverloadTypeName</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dxilopbuilder-cpp-/#a3fe8fcf1f03e5da864eb86be303a3216a1955f73644e78a3ffadcf645300a22c2">anonymous{DXILOpBuilder.cpp}::ObjectType</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-dxilopbuilder-cpp-/#a3fe8fcf1f03e5da864eb86be303a3216acf3f514bb7a7f97c8c6bc38334ffb02f">anonymous{DXILOpBuilder.cpp}::UserDefineType</a>.</p>

</div>
</div>

### setDXILAttributes() {#a3f67233011e3c2264e7806412baa1595}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void setDXILAttributes (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#ac64683c1985c78d81b50819a0b733f48">dxil::OpCode</a> OpCode, <a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a> DXILVersion)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>


<p>References <a href="#abf6c1a9b39b2459374f41ddd34153b6f">getDXILAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ab343ed4a791fff67f7ab395b08b9a1e0">llvm::CallBase::setCannotDuplicate</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2db9f3ffecc57cf9333d355927413fbf">llvm::CallBase::setDoesNotAccessMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a086ea083312d974694676dcde76a1e65">llvm::CallBase::setDoesNotReturn</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#a68bd81d0004f8cc3cdcef6151677c673">llvm::CallBase::setOnlyReadsMemory</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxil/dxilopbuilder/#a871def99cd40b0a7df2e3f22387198cc">llvm::dxil::DXILOpBuilder::tryCreateOp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DXILOpNamePrefix {#ad0fa85ab79bac10513060a1db62093c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringLiteral DXILOpNamePrefix = "dx.op."</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>


<p>Referenced by <a href="#ac921fd99ff39f6037d7f82d81ee8d87a">constructOverloadName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DXIL\_OP\_ATTRIBUTES {#a5b17cd335de5fc6606b2477ea5122746}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DXIL_OP_ATTRIBUTES(OpCode, VersionMajor, VersionMinor, ...)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case <a href="#a7e1fd5d9c5ee4c9aac8931011337fced">computeSwitchEnum</a>(OpCode, VersionMajor, VersionMinor): {                \
    auto Other = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelattributes-cpp/#a5a7ac0d6f6157bfa62400fdc021157dc">dxil::Attributes</a>{__VA_ARGS__};                                \
    <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelattributes-cpp/#a5a7ac0d6f6157bfa62400fdc021157dc">Attributes</a> |= Other;                                                       \
    break;                                                                     \
  };
</div>
</dd>
</dl>

<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>

</div>
</div>

### DXIL\_OP\_FUNCTION\_TYPE {#a409cc48873cd68306603991ea3837b33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DXIL_OP_FUNCTION_TYPE(OpCode, RetType, ...)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case OpCode:                                                                 \
    return FunctionType::get(                                                  \
        <a href="#a2c4f92e821d5bc282b226a8ba057a213">getTypeFromOpParamType</a>(RetType, Context, OverloadTy),                  \
        <a href="#a36bdcdb68f8b041f4f5886de8da52bc1">getArgTypesFromOpParamTypes</a>({__VA_ARGS__}, Context, OverloadTy),       \
        /*isVarArg=*/false);
</div>
</dd>
</dl>

<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>

</div>
</div>

### DXIL\_OP\_OPERATION\_TABLE {#a7941b1cd5e48ddf5c7eb63fb43d8d71c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DXIL_OP_OPERATION_TABLE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>

</div>
</div>

### DXIL\_VERSION {#adeff96061c4fb93b4754a0334bbfe1a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DXIL_VERSION(MAJOR, MINOR)&nbsp;&nbsp;&nbsp;{MAJOR, MINOR},</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
