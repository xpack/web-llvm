---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ssaupdatertraits-36e5fa5b110a1852d0627da33930e4d4
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SSAUpdaterTraits` Class Template Reference

<p>Template specialization to give <a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> access to CFG and value information. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SSAUpdaterTraits&lt;LDVSSAUpdater&gt; { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7604fac2103840a396b49e95b9ba546e">BlkT</a> = LDVSSABlock</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed1981dd0e865bb20cebfa9cbfb6568c">ValT</a> = BlockValueNum</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a897a36c61777b2428a0bd38d79f70a38">PhiT</a> = LDVSSAPhi</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00dee8613a6bcca61ed2158fadf9ef3c">BlkSucc_iterator</a> = LDVSSABlockIterator</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a00dee8613a6bcca61ed2158fadf9ef3c">BlkSucc_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff0300fb8cbdf8778eeb19d4d5440660">BlkSucc_begin</a> (BlkT *BB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a00dee8613a6bcca61ed2158fadf9ef3c">BlkSucc_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a9c3fa37350ad4b187055d61b48ff16">BlkSucc_end</a> (BlkT *BB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits/phi-iterator-6378c5910886d7a8595c30cf77f6df16">PHI_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77330dfa97bc91b53a5e9e1d6f75cab1">PHI_begin</a> (PhiT *PHI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits/phi-iterator-6378c5910886d7a8595c30cf77f6df16">PHI_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af172763cc276913cd13e89b5b2bcbc69">PHI_end</a> (PhiT *PHI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac031b6154536f289d3c8962a2d9efd48">FindPredecessorBlocks</a> (LDVSSABlock *BB, SmallVectorImpl&lt; LDVSSABlock * &gt; *Preds)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FindPredecessorBlocks - Put the predecessors of BB into the Preds vector. <a href="#ac031b6154536f289d3c8962a2d9efd48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static BlockValueNum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33333fff376eea6f32493439a84c72d0">GetPoisonVal</a> (LDVSSABlock *BB, LDVSSAUpdater *Updater)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetPoisonVal - Normally creates an IMPLICIT_DEF instruction with a new register. <a href="#a33333fff376eea6f32493439a84c72d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static BlockValueNum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ba7a4f9025c38ba1d2d612e49551dcb">CreateEmptyPHI</a> (LDVSSABlock *BB, unsigned NumPreds, LDVSSAUpdater *Updater)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CreateEmptyPHI - Create a (representation of a) PHI in the given block. <a href="#a1ba7a4f9025c38ba1d2d612e49551dcb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84a697406586a81c7ece9b9818929ab6">AddPHIOperand</a> (LDVSSAPhi *PHI, BlockValueNum Val, LDVSSABlock *Pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AddPHIOperand - Add the specified value as an operand of the PHI for the specified predecessor block. <a href="#a84a697406586a81c7ece9b9818929ab6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static LDVSSAPhi *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afeb156ea118a9cafd6b686d2cd469ae6">ValueIsPHI</a> (BlockValueNum Val, LDVSSAUpdater *Updater)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ValueIsPHI - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the instruction that defines the specified value is a PHI instruction. <a href="#afeb156ea118a9cafd6b686d2cd469ae6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static LDVSSAPhi *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac74aed32bcd3712e2746bbf208229c2e">ValueIsNewPHI</a> (BlockValueNum Val, LDVSSAUpdater *Updater)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ValueIsNewPHI - Like ValueIsPHI but also check if the PHI has no source operands, i.e., it was just added. <a href="#ac74aed32bcd3712e2746bbf208229c2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static BlockValueNum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac588486afd7ad9e56feeeaf30a2db1c0">GetPHIValue</a> (LDVSSAPhi *PHI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetPHIValue - For the specified PHI instruction, return the value that it defines. <a href="#ac588486afd7ad9e56feeeaf30a2db1c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Template specialization to give <a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> access to CFG and value information.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> calls methods in these traits, passing in the LDVSSAUpdater object, to learn about blocks and the values they define. It also provides methods to create PHI nodes and track them.</p>


<p>Definition at line 4016 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### BlkSucc\_iterator {#a00dee8613a6bcca61ed2158fadf9ef3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SSAUpdaterTraits&lt; LDVSSAUpdater &gt;::BlkSucc_iterator =  LDVSSABlockIterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4021 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### BlkT {#a7604fac2103840a396b49e95b9ba546e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SSAUpdaterTraits&lt; LDVSSAUpdater &gt;::BlkT =  LDVSSABlock</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4018 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### PhiT {#a897a36c61777b2428a0bd38d79f70a38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SSAUpdaterTraits&lt; LDVSSAUpdater &gt;::PhiT =  LDVSSAPhi</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4020 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### ValT {#aed1981dd0e865bb20cebfa9cbfb6568c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SSAUpdaterTraits&lt; LDVSSAUpdater &gt;::ValT =  BlockValueNum</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4019 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### AddPHIOperand() {#a84a697406586a81c7ece9b9818929ab6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SSAUpdaterTraits&lt; LDVSSAUpdater &gt;::AddPHIOperand (LDVSSAPhi * PHI, BlockValueNum Val, LDVSSABlock * Pred)</td>
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

<p>AddPHIOperand - Add the specified value as an operand of the PHI for the specified predecessor block.</p>

<p>Definition at line 4092 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>.</p>

</div>
</div>

### BlkSucc\_begin() {#aff0300fb8cbdf8778eeb19d4d5440660}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlkSucc_iterator llvm::SSAUpdaterTraits&lt; LDVSSAUpdater &gt;::BlkSucc_begin (<a href="#a7604fac2103840a396b49e95b9ba546e">BlkT</a> * BB)</td>
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



<p>Definition at line 4024 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### BlkSucc\_end() {#a5a9c3fa37350ad4b187055d61b48ff16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlkSucc_iterator llvm::SSAUpdaterTraits&lt; LDVSSAUpdater &gt;::BlkSucc_end (<a href="#a7604fac2103840a396b49e95b9ba546e">BlkT</a> * BB)</td>
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



<p>Definition at line 4025 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### CreateEmptyPHI() {#a1ba7a4f9025c38ba1d2d612e49551dcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockValueNum llvm::SSAUpdaterTraits&lt; LDVSSAUpdater &gt;::CreateEmptyPHI (LDVSSABlock * BB, unsigned NumPreds, LDVSSAUpdater * Updater)</td>
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

<p>CreateEmptyPHI - Create a (representation of a) PHI in the given block.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> will populate it with information about incoming values. The value number of this PHI is whatever the machine value number problem solution determined it to be. This includes non-phi values if <a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> tries to create a PHI where the incoming values are identical.</p>


<p>Definition at line 4082 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>.</p>

</div>
</div>

### FindPredecessorBlocks() {#ac031b6154536f289d3c8962a2d9efd48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SSAUpdaterTraits&lt; LDVSSAUpdater &gt;::FindPredecessorBlocks (LDVSSABlock * BB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; LDVSSABlock * &gt; * Preds)</td>
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

<p>FindPredecessorBlocks - Put the predecessors of BB into the Preds vector.</p>

<p>Definition at line 4059 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### GetPHIValue() {#ac588486afd7ad9e56feeeaf30a2db1c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockValueNum llvm::SSAUpdaterTraits&lt; LDVSSAUpdater &gt;::GetPHIValue (LDVSSAPhi * PHI)</td>
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

<p>GetPHIValue - For the specified PHI instruction, return the value that it defines.</p>

<p>Definition at line 4113 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>.</p>

</div>
</div>

### GetPoisonVal() {#a33333fff376eea6f32493439a84c72d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockValueNum llvm::SSAUpdaterTraits&lt; LDVSSAUpdater &gt;::GetPoisonVal (LDVSSABlock * BB, LDVSSAUpdater * Updater)</td>
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

<p>GetPoisonVal - Normally creates an IMPLICIT_DEF instruction with a new register.</p>


<p>For <a href="/web-llvm/docs/api/namespaces/livedebugvalues">LiveDebugValues</a>, represents a block identified as not having any DBG_PHI predecessors.</p>


<p>Definition at line 4068 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum/#ab797179b6d9bdda6c2f182fbb8011704">LiveDebugValues::ValueIDNum::asU64</a>.</p>

</div>
</div>

### PHI\_begin() {#a77330dfa97bc91b53a5e9e1d6f75cab1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PHI_iterator llvm::SSAUpdaterTraits&lt; LDVSSAUpdater &gt;::PHI_begin (<a href="#a897a36c61777b2428a0bd38d79f70a38">PhiT</a> * PHI)</td>
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



<p>Definition at line 4051 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>.</p>

</div>
</div>

### PHI\_end() {#af172763cc276913cd13e89b5b2bcbc69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PHI_iterator llvm::SSAUpdaterTraits&lt; LDVSSAUpdater &gt;::PHI_end (<a href="#a897a36c61777b2428a0bd38d79f70a38">PhiT</a> * PHI)</td>
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



<p>Definition at line 4053 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>.</p>

</div>
</div>

### ValueIsNewPHI() {#ac74aed32bcd3712e2746bbf208229c2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LDVSSAPhi * llvm::SSAUpdaterTraits&lt; LDVSSAUpdater &gt;::ValueIsNewPHI (BlockValueNum Val, LDVSSAUpdater * Updater)</td>
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

<p>ValueIsNewPHI - Like ValueIsPHI but also check if the PHI has no source operands, i.e., it was just added.</p>

<p>Definition at line 4104 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a> and <a href="#afeb156ea118a9cafd6b686d2cd469ae6">ValueIsPHI</a>.</p>

</div>
</div>

### ValueIsPHI() {#afeb156ea118a9cafd6b686d2cd469ae6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LDVSSAPhi * llvm::SSAUpdaterTraits&lt; LDVSSAUpdater &gt;::ValueIsPHI (BlockValueNum Val, LDVSSAUpdater * Updater)</td>
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

<p>ValueIsPHI - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the instruction that defines the specified value is a PHI instruction.</p>

<p>Definition at line 4098 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#ac74aed32bcd3712e2746bbf208229c2e">ValueIsNewPHI</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
