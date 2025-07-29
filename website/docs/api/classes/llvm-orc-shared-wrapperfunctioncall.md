---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/shared/wrapperfunctioncall
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `WrapperFunctionCall` Class

<p>Represents a serialized wrapper function call. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::shared::WrapperFunctionCall { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">llvm/ExecutionEngine/Orc/Shared/WrapperFunctionUtils.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa437c8c5cbb354584f2b0720610cbe62">ArgDataBufferType</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; char, 24 &gt;</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b49e2199a6fccee2291c60e844958d2">WrapperFunctionCall</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a031b3e710d6b6c861a92e6522b1d6e6b">WrapperFunctionCall</a> (ExecutorAddr FnAddr, ArgDataBufferType ArgData)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunctioncall">WrapperFunctionCall</a> from a target function and arg buffer. <a href="#a031b3e710d6b6c861a92e6522b1d6e6b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa56ea45cb77c8cb023522190f3d9e500">operator bool</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>WrapperFunctionCalls convert to true if the callee is non-null. <a href="#aa56ea45cb77c8cb023522190f3d9e500">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b43fdd6f1bfeb7c83642c0511b3f133">getCallee</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the address to be called. <a href="#a8b43fdd6f1bfeb7c83642c0511b3f133">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aa437c8c5cbb354584f2b0720610cbe62">ArgDataBufferType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01364ab6178342e7860bfb0a53ce0a2c">getArgData</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the argument data. <a href="#a01364ab6178342e7860bfb0a53ce0a2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunctionresult">shared::WrapperFunctionResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf188f257d84897164fe66768f5cb5ba">run</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run call returning raw <a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunctionresult">WrapperFunctionResult</a>. <a href="#abf188f257d84897164fe66768f5cb5ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SPSRetT, typename RetT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a32bc5d50f34fe9e76fbb8014139aa934">runWithSPSRet</a> (RetT &amp;RetVal) const -&gt; std::enable_if_t&lt;!std::is_same&lt; SPSRetT, void &gt;::value, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run call and deserialize result using SPS. <a href="#a32bc5d50f34fe9e76fbb8014139aa934">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SPSRetT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ade4ca36ea655d03e3ddbaeffe375f239">runWithSPSRet</a> () const -&gt; std::enable_if_t&lt; std::is_same&lt; SPSRetT, void &gt;::value, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Overload for SPS functions returning void. <a href="#ade4ca36ea655d03e3ddbaeffe375f239">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d284376f1bf8e8df8a6bf2e307fb396">runWithSPSRetErrorMerged</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run call and deserialize an SPSError result. <a href="#a0d284376f1bf8e8df8a6bf2e307fb396">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">orc::ExecutorAddr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a986c1849e18c9522447c21ea532bc179">FnAddr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa437c8c5cbb354584f2b0720610cbe62">ArgDataBufferType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa25ac807fa1a5129b31163a1776fd7ca">ArgData</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SPSSerializer, typename... ArgTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac924edcd8ad4ceeebcbcea4ca04a793b">Create</a> (ExecutorAddr FnAddr, const ArgTs &amp;...Args) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunctioncall">WrapperFunctionCall</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunctioncall">WrapperFunctionCall</a> using the given SPS serializer to serialize the arguments. <a href="#ac924edcd8ad4ceeebcbcea4ca04a793b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Represents a serialized wrapper function call.</p>


<p>Serializing calls themselves allows us to batch them: We can make one "run-wrapper-functions" utility and send it a list of calls to run.</p>


<p>The motivating use-case for this API is JITLink allocation actions, where we want to run multiple functions to finalize linked memory without having to make separate IPC calls for each one.</p>


<p>Definition at line 630 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">WrapperFunctionUtils.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ArgDataBufferType {#aa437c8c5cbb354584f2b0720610cbe62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::WrapperFunctionCall::ArgDataBufferType =  SmallVector&lt;char, 24&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 632 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">WrapperFunctionUtils.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### WrapperFunctionCall() {#a0b49e2199a6fccee2291c60e844958d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::shared::WrapperFunctionCall::WrapperFunctionCall ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 650 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">WrapperFunctionUtils.h</a>.</p>


<p>Referenced by <a href="#ac924edcd8ad4ceeebcbcea4ca04a793b">Create</a>.</p>

</div>
</div>

### WrapperFunctionCall() {#a031b3e710d6b6c861a92e6522b1d6e6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::shared::WrapperFunctionCall::WrapperFunctionCall (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> FnAddr, <a href="#aa437c8c5cbb354584f2b0720610cbe62">ArgDataBufferType</a> ArgData)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunctioncall">WrapperFunctionCall</a> from a target function and arg buffer.</p>

<p>Definition at line 653 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">WrapperFunctionUtils.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator bool() {#aa56ea45cb77c8cb023522190f3d9e500}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::shared::WrapperFunctionCall::operator bool ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>WrapperFunctionCalls convert to true if the callee is non-null.</p>

<p>Definition at line 663 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">WrapperFunctionUtils.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getArgData() {#a01364ab6178342e7860bfb0a53ce0a2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ArgDataBufferType &amp; llvm::orc::shared::WrapperFunctionCall::getArgData ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the argument data.</p>

<p>Definition at line 660 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">WrapperFunctionUtils.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-6f403f5489d3025cbee03c70dd5dff03/#a4cd986b97fc3b32c9e27328e0215cfc8">llvm::orc::shared::SPSSerializationTraits&lt; SPSWrapperFunctionCall, WrapperFunctionCall &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-6f403f5489d3025cbee03c70dd5dff03/#a3b3e64b40a6e7faca549b6f9639ece22">llvm::orc::shared::SPSSerializationTraits&lt; SPSWrapperFunctionCall, WrapperFunctionCall &gt;::size</a>.</p>

</div>
</div>

### getCallee() {#a8b43fdd6f1bfeb7c83642c0511b3f133}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ExecutorAddr &amp; llvm::orc::shared::WrapperFunctionCall::getCallee ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the address to be called.</p>

<p>Definition at line 657 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">WrapperFunctionUtils.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-6f403f5489d3025cbee03c70dd5dff03/#a4cd986b97fc3b32c9e27328e0215cfc8">llvm::orc::shared::SPSSerializationTraits&lt; SPSWrapperFunctionCall, WrapperFunctionCall &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-6f403f5489d3025cbee03c70dd5dff03/#a3b3e64b40a6e7faca549b6f9639ece22">llvm::orc::shared::SPSSerializationTraits&lt; SPSWrapperFunctionCall, WrapperFunctionCall &gt;::size</a>.</p>

</div>
</div>

### run() {#abf188f257d84897164fe66768f5cb5ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">shared::WrapperFunctionResult llvm::orc::shared::WrapperFunctionCall::run ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run call returning raw <a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunctionresult">WrapperFunctionResult</a>.</p>

<p>Definition at line 666 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">WrapperFunctionUtils.h</a>.</p>


<p>Referenced by <a href="#a32bc5d50f34fe9e76fbb8014139aa934">runWithSPSRet</a>.</p>

</div>
</div>

### runWithSPSRet() {#a32bc5d50f34fe9e76fbb8014139aa934}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SPSRetT, typename RetT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt;!std::is_same&lt; SPSRetT, void &gt;::value, Error &gt; llvm::orc::shared::WrapperFunctionCall::runWithSPSRet (RetT &amp; RetVal)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run call and deserialize result using SPS.</p>

<p>Definition at line 676 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">WrapperFunctionUtils.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="#abf188f257d84897164fe66768f5cb5ba">run</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a0d284376f1bf8e8df8a6bf2e307fb396">runWithSPSRetErrorMerged</a>.</p>

</div>
</div>

### runWithSPSRet() {#ade4ca36ea655d03e3ddbaeffe375f239}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SPSRetT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; std::is_same&lt; SPSRetT, void &gt;::value, Error &gt; llvm::orc::shared::WrapperFunctionCall::runWithSPSRet ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Overload for SPS functions returning void.</p>

<p>Definition at line 691 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">WrapperFunctionUtils.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="#ade4ca36ea655d03e3ddbaeffe375f239">runWithSPSRet</a>.</p>


<p>Referenced by <a href="#ade4ca36ea655d03e3ddbaeffe375f239">runWithSPSRet</a>.</p>

</div>
</div>

### runWithSPSRetErrorMerged() {#a0d284376f1bf8e8df8a6bf2e307fb396}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::shared::WrapperFunctionCall::runWithSPSRetErrorMerged ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run call and deserialize an SPSError result.</p>


<p>SPSError returns and deserialization failures are merged into the returned error.</p>


<p>Definition at line 698 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">WrapperFunctionUtils.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/orc/shared/detail/#abba6e489c8732769239a8efbbf27364a">llvm::orc::shared::detail::fromSPSSerializable</a> and <a href="#a32bc5d50f34fe9e76fbb8014139aa934">runWithSPSRet</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ArgData {#aa25ac807fa1a5129b31163a1776fd7ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgDataBufferType llvm::orc::shared::WrapperFunctionCall::ArgData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 707 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">WrapperFunctionUtils.h</a>.</p>

</div>
</div>

### FnAddr {#a986c1849e18c9522447c21ea532bc179}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">orc::ExecutorAddr llvm::orc::shared::WrapperFunctionCall::FnAddr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 706 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">WrapperFunctionUtils.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### Create() {#ac924edcd8ad4ceeebcbcea4ca04a793b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SPSSerializer, typename... ArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; WrapperFunctionCall &gt; llvm::orc::shared::WrapperFunctionCall::Create (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> FnAddr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ArgTs &amp;... Args)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunctioncall">WrapperFunctionCall</a> using the given SPS serializer to serialize the arguments.</p>

<p>Definition at line 637 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">WrapperFunctionUtils.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="#a0b49e2199a6fccee2291c60e844958d2">WrapperFunctionCall</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-debuggersupportplugin-cpp-/machodebugobjectsynthesizer/#a21d1557ff7212b52d2935836c8619919">anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizer&lt; MachOTraits &gt;::completeSynthesisAndRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericrtdyldmemorymanager/#a0db7d447f814afaee65a64c0419805dd">llvm::orc::EPCGenericRTDyldMemoryManager::finalizeMemory</a>, <a href="/web-llvm/docs/api/classes/anonymous-elfnixplatform-cpp-/elfnixplatformcompletebootstrapmaterializationunit/#aa18b5e663aa3f2116768bde792d2df6f">anonymous{ELFNixPlatform.cpp}::ELFNixPlatformCompleteBootstrapMaterializationUnit::materialize</a>, <a href="/web-llvm/docs/api/classes/anonymous-machoplatform-cpp-/machoplatformcompletebootstrapmaterializationunit/#a333817dbce02ebd241fe922323713900">anonymous{MachOPlatform.cpp}::MachOPlatformCompleteBootstrapMaterializationUnit::materialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/perfsupportplugin/#a0b1cb2049314feb0a29760c548a604af">llvm::orc::PerfSupportPlugin::modifyPassConfig</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/vtunesupportplugin/#a853290f0b4ae904b8ab68e6a06f8bab9">llvm::orc::VTuneSupportPlugin::modifyPassConfig</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">WrapperFunctionUtils.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
