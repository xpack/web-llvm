---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/bitintegerstate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `BitIntegerState` Struct Template Reference

<p>Specialization of the integer state for a bit-wise encoding. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename base_ty = uint32_t, base_ty BestState = ~base_ty(0), base_ty WorstState = 0&gt;
struct llvm::BitIntegerState&lt;base_ty, BestState, WorstState&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">llvm/Transforms/IPO/Attributor.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/integerstatebase">IntegerStateBase&lt;base_ty, BestState, WorstState&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Simple state with integers encoding. <a href="/web-llvm/docs/api/structs/llvm/integerstatebase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/statewrapper">StateWrapper&lt;StateTy, BaseType, Ts&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to tie a abstract state implementation to an abstract attribute. <a href="/web-llvm/docs/api/structs/llvm/statewrapper/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/statewrapper">StateWrapper&lt;StateTy, BaseType, Ts&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to tie a abstract state implementation to an abstract attribute. <a href="/web-llvm/docs/api/structs/llvm/statewrapper/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/statewrapper">StateWrapper&lt;StateTy, BaseType, Ts&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to tie a abstract state implementation to an abstract attribute. <a href="/web-llvm/docs/api/structs/llvm/statewrapper/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3d70e405c05068d748368cfebdfc869c">super</a> = <a href="/web-llvm/docs/api/structs/llvm/integerstatebase">IntegerStateBase</a>&lt; base_ty, BestState, WorstState &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac20e8769acb2f2bae9f0c8638aa36d16">base_t</a> = base_ty</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a2b4cbbb411686779c89981fb01c2e8aa">BitIntegerState</a> ()=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a54046f3ad91cdc22d576a21636144a54">BitIntegerState</a> (base_t Assumed)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af53ef7825e1ab608c8b6cc2ab94e5ddf">isKnown</a> (base_t BitsEncoding=BestState) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the bits set in <span class="doxyComputerOutput">BitsEncoding</span> are "known bits". <a href="#af53ef7825e1ab608c8b6cc2ab94e5ddf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a38acb9f66b8669c71052db94e468b3a9">isAssumed</a> (base_t BitsEncoding=BestState) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the bits set in <span class="doxyComputerOutput">BitsEncoding</span> are "assumed bits". <a href="#a38acb9f66b8669c71052db94e468b3a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bitintegerstate">BitIntegerState</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af70049b0ed5edb17a39a0ee788f7b376">addKnownBits</a> (base_t Bits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the bits in <span class="doxyComputerOutput">BitsEncoding</span> to the "known bits". <a href="#af70049b0ed5edb17a39a0ee788f7b376">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bitintegerstate">BitIntegerState</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a69055c62a711a6f503db05930ccb6ce7">removeAssumedBits</a> (base_t BitsEncoding)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the bits in <span class="doxyComputerOutput">BitsEncoding</span> from the "assumed bits" if not known. <a href="#a69055c62a711a6f503db05930ccb6ce7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bitintegerstate">BitIntegerState</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0425a75cf24a26e185ccd7d5673f4d2d">removeKnownBits</a> (base_t BitsEncoding)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the bits in <span class="doxyComputerOutput">BitsEncoding</span> from the "known bits". <a href="#a0425a75cf24a26e185ccd7d5673f4d2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bitintegerstate">BitIntegerState</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6e0463fb784adc7b2cef8dabb69dad32">intersectAssumedBits</a> (base_t BitsEncoding)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep only "assumed bits" also set in <span class="doxyComputerOutput">BitsEncoding</span> but all known ones. <a href="#a6e0463fb784adc7b2cef8dabb69dad32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8e1c213f2a9dab1da7567ab9b67bfec6">handleNewAssumedValue</a> (base_t Value) override</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acd49f9b8670c56560d9073e021ba5461">handleNewKnownValue</a> (base_t Value) override</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3e720ad9051c4b38d98151114807c1c9">joinOR</a> (base_t AssumedValue, base_t KnownValue) override</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aca353818e0a0d0d9a0783b5aaebd73f5">joinAND</a> (base_t AssumedValue, base_t KnownValue) override</td>
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

<p>Specialization of the integer state for a bit-wise encoding.</p>

<p>Definition at line 2753 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### base\_t {#ac20e8769acb2f2bae9f0c8638aa36d16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename base_ty = uint32_t, base_ty BestState = ~base_ty(0), base_ty WorstState = 0&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::BitIntegerState&lt; base_ty, BestState, WorstState &gt;::base_t =  base_ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2756 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### super {#a3d70e405c05068d748368cfebdfc869c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename base_ty = uint32_t, base_ty BestState = ~base_ty(0), base_ty WorstState = 0&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::BitIntegerState&lt; base_ty, BestState, WorstState &gt;::super =  IntegerStateBase&lt;base_ty, BestState, WorstState&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2755 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### BitIntegerState() {#a2b4cbbb411686779c89981fb01c2e8aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename base_ty = uint32_t, base_ty BestState = ~base_ty(0), base_ty WorstState = 0&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BitIntegerState&lt; base_ty, BestState, WorstState &gt;::BitIntegerState ()</td>
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



<p>Definition at line 2757 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="#af70049b0ed5edb17a39a0ee788f7b376">llvm::BitIntegerState&lt; base_ty, BestState, WorstState &gt;::addKnownBits</a>, <a href="#a6e0463fb784adc7b2cef8dabb69dad32">llvm::BitIntegerState&lt; base_ty, BestState, WorstState &gt;::intersectAssumedBits</a>, <a href="#a69055c62a711a6f503db05930ccb6ce7">llvm::BitIntegerState&lt; base_ty, BestState, WorstState &gt;::removeAssumedBits</a> and <a href="#a0425a75cf24a26e185ccd7d5673f4d2d">llvm::BitIntegerState&lt; base_ty, BestState, WorstState &gt;::removeKnownBits</a>.</p>

</div>
</div>

### BitIntegerState() {#a54046f3ad91cdc22d576a21636144a54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename base_ty = uint32_t, base_ty BestState = ~base_ty(0), base_ty WorstState = 0&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BitIntegerState&lt; base_ty, BestState, WorstState &gt;::BitIntegerState (<a href="#ac20e8769acb2f2bae9f0c8638aa36d16">base_t</a> Assumed)</td>
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



<p>Definition at line 2758 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/integerstatebase/#adfec5c3204426cd0056d89fd26b5a117">llvm::IntegerStateBase&lt; uint32_t, ~uint32_t(0), 0 &gt;::Assumed</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addKnownBits() {#af70049b0ed5edb17a39a0ee788f7b376}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename base_ty = uint32_t, base_ty BestState = ~base_ty(0), base_ty WorstState = 0&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitIntegerState &amp; llvm::BitIntegerState&lt; base_ty, BestState, WorstState &gt;::addKnownBits (<a href="#ac20e8769acb2f2bae9f0c8638aa36d16">base_t</a> Bits)</td>
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

<p>Add the bits in <span class="doxyComputerOutput">BitsEncoding</span> to the "known bits".</p>

<p>Definition at line 2771 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/integerstatebase/#adfec5c3204426cd0056d89fd26b5a117">llvm::IntegerStateBase&lt; uint32_t, ~uint32_t(0), 0 &gt;::Assumed</a>, <a href="#a2b4cbbb411686779c89981fb01c2e8aa">llvm::BitIntegerState&lt; base_ty, BestState, WorstState &gt;::BitIntegerState</a> and <a href="/web-llvm/docs/api/structs/llvm/integerstatebase/#ab0c30efb73ca2f8b3dcbd658437a991e">llvm::IntegerStateBase&lt; uint32_t, ~uint32_t(0), 0 &gt;::Known</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdattributesfunction/#a45491e6a28947b2fc05de4cf7cc2b60f">anonymous{AMDGPUAttributor.cpp}::AAAMDAttributesFunction::initialize</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanofpclassimpl/#a15b5bdf6941d33266e2377777aebb9d8">anonymous{AttributorAttributes.cpp}::AANoFPClassImpl::initialize</a>.</p>

</div>
</div>

### intersectAssumedBits() {#a6e0463fb784adc7b2cef8dabb69dad32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename base_ty = uint32_t, base_ty BestState = ~base_ty(0), base_ty WorstState = 0&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitIntegerState &amp; llvm::BitIntegerState&lt; base_ty, BestState, WorstState &gt;::intersectAssumedBits (<a href="#ac20e8769acb2f2bae9f0c8638aa36d16">base_t</a> BitsEncoding)</td>
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

<p>Keep only "assumed bits" also set in <span class="doxyComputerOutput">BitsEncoding</span> but all known ones.</p>

<p>Definition at line 2790 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/integerstatebase/#adfec5c3204426cd0056d89fd26b5a117">llvm::IntegerStateBase&lt; uint32_t, ~uint32_t(0), 0 &gt;::Assumed</a>, <a href="#a2b4cbbb411686779c89981fb01c2e8aa">llvm::BitIntegerState&lt; base_ty, BestState, WorstState &gt;::BitIntegerState</a> and <a href="/web-llvm/docs/api/structs/llvm/integerstatebase/#ab0c30efb73ca2f8b3dcbd658437a991e">llvm::IntegerStateBase&lt; uint32_t, ~uint32_t(0), 0 &gt;::Known</a>.</p>


<p>Referenced by <a href="#a69055c62a711a6f503db05930ccb6ce7">llvm::BitIntegerState&lt; base_ty, BestState, WorstState &gt;::removeAssumedBits</a>.</p>

</div>
</div>

### isAssumed() {#a38acb9f66b8669c71052db94e468b3a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename base_ty = uint32_t, base_ty BestState = ~base_ty(0), base_ty WorstState = 0&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BitIntegerState&lt; base_ty, BestState, WorstState &gt;::isAssumed (<a href="#ac20e8769acb2f2bae9f0c8638aa36d16">base_t</a> BitsEncoding=BestState)</td>
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

<p>Return true if the bits set in <span class="doxyComputerOutput">BitsEncoding</span> are "assumed bits".</p>

<p>Definition at line 2766 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/integerstatebase/#adfec5c3204426cd0056d89fd26b5a117">llvm::IntegerStateBase&lt; uint32_t, ~uint32_t(0), 0 &gt;::Assumed</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdattributesfunction/#abcfc043f77cf8dca5b9a3eebc653621f">anonymous{AMDGPUAttributor.cpp}::AAAMDAttributesFunction::getAsStr</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadvalueimpl/#a2bb5860f88cf615d4ef9b0cc55aa229f">anonymous{AttributorAttributes.cpp}::AAIsDeadValueImpl::isAssumedDead</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfloating/#ad1373816b599022e1b5f8d5c1497f3a8">anonymous{AttributorAttributes.cpp}::AAIsDeadFloating::isRemovableStore</a> and <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdattributesfunction/#a1757cce9d6fc5259895ec599716aa7fc">anonymous{AMDGPUAttributor.cpp}::AAAMDAttributesFunction::updateImpl</a>.</p>

</div>
</div>

### isKnown() {#af53ef7825e1ab608c8b6cc2ab94e5ddf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename base_ty = uint32_t, base_ty BestState = ~base_ty(0), base_ty WorstState = 0&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BitIntegerState&lt; base_ty, BestState, WorstState &gt;::isKnown (<a href="#ac20e8769acb2f2bae9f0c8638aa36d16">base_t</a> BitsEncoding=BestState)</td>
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

<p>Return true if the bits set in <span class="doxyComputerOutput">BitsEncoding</span> are "known bits".</p>

<p>Definition at line 2761 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/integerstatebase/#ab0c30efb73ca2f8b3dcbd658437a991e">llvm::IntegerStateBase&lt; uint32_t, ~uint32_t(0), 0 &gt;::Known</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#a78cf0931abfbc70e124e7c225584b686">llvm::Attributor::isAssumedDead</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadvalueimpl/#a6a5399b31591d3e114d7664b80d4711d">anonymous{AttributorAttributes.cpp}::AAIsDeadValueImpl::isKnownDead</a> and <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdattributesfunction/#a508aceda7d46a30692b5bb3531e16dba">anonymous{AMDGPUAttributor.cpp}::AAAMDAttributesFunction::manifest</a>.</p>

</div>
</div>

### removeAssumedBits() {#a69055c62a711a6f503db05930ccb6ce7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename base_ty = uint32_t, base_ty BestState = ~base_ty(0), base_ty WorstState = 0&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitIntegerState &amp; llvm::BitIntegerState&lt; base_ty, BestState, WorstState &gt;::removeAssumedBits (<a href="#ac20e8769acb2f2bae9f0c8638aa36d16">base_t</a> BitsEncoding)</td>
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

<p>Remove the bits in <span class="doxyComputerOutput">BitsEncoding</span> from the "assumed bits" if not known.</p>

<p>Definition at line 2779 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#a2b4cbbb411686779c89981fb01c2e8aa">llvm::BitIntegerState&lt; base_ty, BestState, WorstState &gt;::BitIntegerState</a> and <a href="#a6e0463fb784adc7b2cef8dabb69dad32">llvm::BitIntegerState&lt; base_ty, BestState, WorstState &gt;::intersectAssumedBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdattributesfunction/#a45491e6a28947b2fc05de4cf7cc2b60f">anonymous{AMDGPUAttributor.cpp}::AAAMDAttributesFunction::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfloating/#a6bb99a515b0f1ece7560275f4c47033c">anonymous{AttributorAttributes.cpp}::AAIsDeadFloating::initialize</a> and <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdattributesfunction/#a1757cce9d6fc5259895ec599716aa7fc">anonymous{AMDGPUAttributor.cpp}::AAAMDAttributesFunction::updateImpl</a>.</p>

</div>
</div>

### removeKnownBits() {#a0425a75cf24a26e185ccd7d5673f4d2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename base_ty = uint32_t, base_ty BestState = ~base_ty(0), base_ty WorstState = 0&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitIntegerState &amp; llvm::BitIntegerState&lt; base_ty, BestState, WorstState &gt;::removeKnownBits (<a href="#ac20e8769acb2f2bae9f0c8638aa36d16">base_t</a> BitsEncoding)</td>
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

<p>Remove the bits in <span class="doxyComputerOutput">BitsEncoding</span> from the "known bits".</p>

<p>Definition at line 2784 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#a2b4cbbb411686779c89981fb01c2e8aa">llvm::BitIntegerState&lt; base_ty, BestState, WorstState &gt;::BitIntegerState</a> and <a href="/web-llvm/docs/api/structs/llvm/integerstatebase/#ab0c30efb73ca2f8b3dcbd658437a991e">llvm::IntegerStateBase&lt; uint32_t, ~uint32_t(0), 0 &gt;::Known</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### handleNewAssumedValue() {#a8e1c213f2a9dab1da7567ab9b67bfec6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename base_ty = uint32_t, base_ty BestState = ~base_ty(0), base_ty WorstState = 0&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitIntegerState&lt; base_ty, BestState, WorstState &gt;::handleNewAssumedValue (<a href="#ac20e8769acb2f2bae9f0c8638aa36d16">base_t</a> Value)</td>
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



<p>Definition at line 2797 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### handleNewKnownValue() {#acd49f9b8670c56560d9073e021ba5461}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename base_ty = uint32_t, base_ty BestState = ~base_ty(0), base_ty WorstState = 0&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitIntegerState&lt; base_ty, BestState, WorstState &gt;::handleNewKnownValue (<a href="#ac20e8769acb2f2bae9f0c8638aa36d16">base_t</a> Value)</td>
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



<p>Definition at line 2800 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### joinAND() {#aca353818e0a0d0d9a0783b5aaebd73f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename base_ty = uint32_t, base_ty BestState = ~base_ty(0), base_ty WorstState = 0&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitIntegerState&lt; base_ty, BestState, WorstState &gt;::joinAND (<a href="#ac20e8769acb2f2bae9f0c8638aa36d16">base_t</a> AssumedValue, <a href="#ac20e8769acb2f2bae9f0c8638aa36d16">base_t</a> KnownValue)</td>
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



<p>Definition at line 2805 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### joinOR() {#a3e720ad9051c4b38d98151114807c1c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename base_ty = uint32_t, base_ty BestState = ~base_ty(0), base_ty WorstState = 0&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitIntegerState&lt; base_ty, BestState, WorstState &gt;::joinOR (<a href="#ac20e8769acb2f2bae9f0c8638aa36d16">base_t</a> AssumedValue, <a href="#ac20e8769acb2f2bae9f0c8638aa36d16">base_t</a> KnownValue)</td>
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



<p>Definition at line 2801 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
