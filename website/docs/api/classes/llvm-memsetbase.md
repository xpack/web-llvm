---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/memsetbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MemSetBase` Class Template

<p>Common base class for all memset intrinsics. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class BaseCL&gt;
class llvm::MemSetBase&lt;BaseCL&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/basecl">BaseCL</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BaseCL&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"> { <a href="#a180bc4672eca46cbfdf04d4545c35749">...</a> }</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BaseCL&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a770c508bbe4f9b480f0d08a839ca94ff">getValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BaseCL&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a721f3340de136afbef54d762e26cf3ec">getValueUse</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BaseCL&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1f07fbd6d409c41efdcc9c32e2c86e4b">getValueUse</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BaseCL&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5145ecc9510133b8db74dfa22bbf5d3d">setValue</a> (Value *Val)</td>
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

## Description {#details}

<p>Common base class for all memset intrinsics.</p>


<p>Simply provides common methods.</p>


<p>Definition at line 1092 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a180bc4672eca46cbfdf04d4545c35749}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARG_VALUE<a id="a180bc4672eca46cbfdf04d4545c35749a0b4400e46b7f8fe6e8d6d9b1a0a9274d"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1094 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getValue() {#a770c508bbe4f9b480f0d08a839ca94ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BaseCL&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::MemSetBase&lt; BaseCL &gt;::getValue ()</td>
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



<p>Definition at line 1097 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktagging-cpp-/initializerbuilder/#a4af002b1cfbc334798f954c0bb59d978">anonymous{AArch64StackTagging.cpp}::InitializerBuilder::addMemSet</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktagging-cpp-/aarch64stacktagging/#ada6b74b298aa932a19fe1ccef722baa5">anonymous{AArch64StackTagging.cpp}::AArch64StackTagging::collectInitializers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff2c3179f5913a4a4d6c80e3d7e564c0">llvm::expandMemSetAsLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b152a4602737ffe1ac280df188402f8">llvm::expandMemSetPatternAsLoop</a>, <a href="#a5145ecc9510133b8db74dfa22bbf5d3d">llvm::MemSetBase&lt; BaseCL &gt;::setValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a0830273a57e2290e00f3ea50b6e082e4">anonymous{DeadStoreElimination.cpp}::DSEState::storeIsNoop</a> and <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a5e2cdb7da821f277764240569336bd07">anonymous{DeadStoreElimination.cpp}::DSEState::tryFoldIntoCalloc</a>.</p>

</div>
</div>

### getValueUse() {#a721f3340de136afbef54d762e26cf3ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BaseCL&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Use &amp; llvm::MemSetBase&lt; BaseCL &gt;::getValueUse ()</td>
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



<p>Definition at line 1100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>

</div>
</div>

### getValueUse() {#a1f07fbd6d409c41efdcc9c32e2c86e4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BaseCL&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Use &amp; llvm::MemSetBase&lt; BaseCL &gt;::getValueUse ()</td>
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



<p>Definition at line 1101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>

</div>
</div>

### setValue() {#a5145ecc9510133b8db74dfa22bbf5d3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BaseCL&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MemSetBase&lt; BaseCL &gt;::setValue (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val)</td>
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



<p>Definition at line 1103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="#a770c508bbe4f9b480f0d08a839ca94ff">llvm::MemSetBase&lt; BaseCL &gt;::getValue</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
