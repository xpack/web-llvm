---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/memtransferbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MemTransferBase` Class Template

<p>Common base class for all memory transfer intrinsics. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class BaseCL&gt;
class llvm::MemTransferBase&lt;BaseCL&gt; { ... }
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"> { <a href="#a8f0cd4aae33baf502992d3a3162100e7">...</a> }</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa3c771310b66362b6a032071f63776bb">getRawSource</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the arguments to the instruction. <a href="#aa3c771310b66362b6a032071f63776bb">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acea9d313124ba590956257da392c4304">getRawSourceUse</a> () const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a25a6743832c01c180f4e20feaf93a83c">getRawSourceUse</a> ()</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaebde92913b64b73fa77dd6e8767d9d9">getSource</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is just like getRawSource, but it strips off any cast instructions that feed it, giving the original input. <a href="#aaebde92913b64b73fa77dd6e8767d9d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BaseCL&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa4905f44616de7dcca8ce3d51685a60b">getSourceAddressSpace</a> () const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1da765247b4f3e983736b6fd4dc52c71">getSourceAlignment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FIXME: Remove this function once transition to <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> is over. <a href="#a1da765247b4f3e983736b6fd4dc52c71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BaseCL&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa512958c35cfdd696c21623a964fc2d9">getSourceAlign</a> () const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5127b9bac226020bc936ecdedcf72e0d">setSource</a> (Value *Ptr)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab5f836ddc7548470c429fd5daaea2784">setSourceAlignment</a> (MaybeAlign Alignment)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac4c3eecc7e156718cb3f01dacdc0631a">setSourceAlignment</a> (Align Alignment)</td>
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

<p>Common base class for all memory transfer intrinsics.</p>


<p>Simply provides common methods.</p>


<p>Definition at line 1034 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a8f0cd4aae33baf502992d3a3162100e7}

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
<td class="doxyEnumItemName">ARG_SOURCE<a id="a8f0cd4aae33baf502992d3a3162100e7a4e8073fe79c84e3dcc7d8b7d231b0cf7"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1036 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getRawSource() {#aa3c771310b66362b6a032071f63776bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BaseCL&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::MemTransferBase&lt; BaseCL &gt;::getRawSource ()</td>
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

<p>Return the arguments to the instruction.</p>

<p>Definition at line 1040 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#a233a4dda6b9b4c37b906fa288ffb1807">canOverlap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad71302bd643143c32b34b01104c2e364">llvm::expandAtomicMemCpyAsLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad5625618c73d17563d851631e27444e6">llvm::expandMemCpyAsLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a35f13ead4222c0c45fb21f7e63025bbc">llvm::expandMemMoveAsLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a3d9eb53bc6802953e1a03c1acc8feb7b">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#af438c8da3109f9d2b1530aed2771b88e">llvm::MemoryLocation::getForSource</a>, <a href="#aaebde92913b64b73fa77dd6e8767d9d9">llvm::MemTransferBase&lt; BaseCL &gt;::getSource</a>, <a href="#aa4905f44616de7dcca8ce3d51685a60b">llvm::MemTransferBase&lt; BaseCL &gt;::getSourceAddressSpace</a> and <a href="#a5127b9bac226020bc936ecdedcf72e0d">llvm::MemTransferBase&lt; BaseCL &gt;::setSource</a>.</p>

</div>
</div>

### getRawSourceUse() {#acea9d313124ba590956257da392c4304}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BaseCL&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Use &amp; llvm::MemTransferBase&lt; BaseCL &gt;::getRawSourceUse ()</td>
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



<p>Definition at line 1043 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>

</div>
</div>

### getRawSourceUse() {#a25a6743832c01c180f4e20feaf93a83c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BaseCL&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Use &amp; llvm::MemTransferBase&lt; BaseCL &gt;::getRawSourceUse ()</td>
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



<p>Definition at line 1046 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>

</div>
</div>

### getSource() {#aaebde92913b64b73fa77dd6e8767d9d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BaseCL&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::MemTransferBase&lt; BaseCL &gt;::getSource ()</td>
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

<p>This is just like getRawSource, but it strips off any cast instructions that feed it, giving the original input.</p>


<p>The returned value is guaranteed to be a pointer.</p>


<p>Definition at line 1051 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>References <a href="#aa3c771310b66362b6a032071f63776bb">llvm::MemTransferBase&lt; BaseCL &gt;::getRawSource</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a966eb231e7d4e572874d2cb49b18faea">llvm::Value::stripPointerCasts</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#ab7c3af18d8706c2d91fd7e2f88424336">llvm::VNCoercion::analyzeLoadFromClobberingMemInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#aa4b66161f15587adee19725b89fec713">llvm::VNCoercion::getConstantMemInstValueForLoad</a> and <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#a6b72d403292d9dddd1ef1ce3e8bc394c">llvm::VNCoercion::getMemInstValueForLoad</a>.</p>

</div>
</div>

### getSourceAddressSpace() {#aa4905f44616de7dcca8ce3d51685a60b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BaseCL&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MemTransferBase&lt; BaseCL &gt;::getSourceAddressSpace ()</td>
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



<p>Definition at line 1053 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#aa3c771310b66362b6a032071f63776bb">llvm::MemTransferBase&lt; BaseCL &gt;::getRawSource</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a3d9eb53bc6802953e1a03c1acc8feb7b">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerIntrinsicCall</a>.</p>

</div>
</div>

### getSourceAlign() {#aa512958c35cfdd696c21623a964fc2d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BaseCL&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaybeAlign llvm::MemTransferBase&lt; BaseCL &gt;::getSourceAlign ()</td>
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



<p>Definition at line 1066 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad71302bd643143c32b34b01104c2e364">llvm::expandAtomicMemCpyAsLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad5625618c73d17563d851631e27444e6">llvm::expandMemCpyAsLoop</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a35f13ead4222c0c45fb21f7e63025bbc">llvm::expandMemMoveAsLoop</a>.</p>

</div>
</div>

### getSourceAlignment() {#a1da765247b4f3e983736b6fd4dc52c71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BaseCL&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MemTransferBase&lt; BaseCL &gt;::getSourceAlignment ()</td>
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

<p>FIXME: Remove this function once transition to <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> is over.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> <a href="#aa512958c35cfdd696c21623a964fc2d9">getSourceAlign()</a> instead.</p>


<p>Definition at line 1060 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>Reference <a href="#a1da765247b4f3e983736b6fd4dc52c71">llvm::MemTransferBase&lt; BaseCL &gt;::getSourceAlignment</a>.</p>


<p>Referenced by <a href="#a1da765247b4f3e983736b6fd4dc52c71">llvm::MemTransferBase&lt; BaseCL &gt;::getSourceAlignment</a>.</p>

</div>
</div>

### setSource() {#a5127b9bac226020bc936ecdedcf72e0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BaseCL&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MemTransferBase&lt; BaseCL &gt;::setSource (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr)</td>
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



<p>Definition at line 1070 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa3c771310b66362b6a032071f63776bb">llvm::MemTransferBase&lt; BaseCL &gt;::getRawSource</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### setSourceAlignment() {#ab5f836ddc7548470c429fd5daaea2784}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BaseCL&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MemTransferBase&lt; BaseCL &gt;::setSourceAlignment (<a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> Alignment)</td>
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



<p>Definition at line 1076 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/attribute/#afb8975f28d8418cad8ea770575736b81">llvm::Attribute::getWithAlignment</a>.</p>

</div>
</div>

### setSourceAlignment() {#ac4c3eecc7e156718cb3f01dacdc0631a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BaseCL&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MemTransferBase&lt; BaseCL &gt;::setSourceAlignment (<a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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



<p>Definition at line 1083 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">IntrinsicInst.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/attribute/#afb8975f28d8418cad8ea770575736b81">llvm::Attribute::getWithAlignment</a>.</p>

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
