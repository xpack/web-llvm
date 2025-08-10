---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vpinterleavedaccessinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `VPInterleavedAccessInfo` Class



## Declaration

<div class="doxyDeclaration">
class llvm::VPInterleavedAccessInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">Transforms/Vectorize/VPlan.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa4e6aad5004da321b41dfe6e3f8584a">Old2NewTy</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/interleavegroup">InterleaveGroup</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &gt; *, <a href="/web-llvm/docs/api/classes/llvm/interleavegroup">InterleaveGroup</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> &gt; * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> for mapping of instruction based interleave groups to <a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> interleave groups. <a href="#aaa4e6aad5004da321b41dfe6e3f8584a">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24f3316a0caf6117d7447bda1023823f">VPInterleavedAccessInfo</a> (VPlan &amp;Plan, InterleavedAccessInfo &amp;IAI)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03ca2edb6de0ea9337687586713b3d20">~VPInterleavedAccessInfo</a> ()</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/interleavegroup">InterleaveGroup</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44fe021e1f4e19bb3d99a2a028330b5b">getInterleaveGroup</a> (VPInstruction *Instr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the interleave group that <span class="doxyComputerOutput">Instr</span> belongs to. <a href="#a44fe021e1f4e19bb3d99a2a028330b5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb2a6b577b11f2ba43c61ebba16d7c8c">visitRegion</a> (VPRegionBlock *Region, Old2NewTy &amp;Old2New, InterleavedAccessInfo &amp;IAI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/region">Region</a></span> and populate <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> based interleave groups based on <span class="doxyComputerOutput">IAI</span>. <a href="#aeb2a6b577b11f2ba43c61ebba16d7c8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2858bd62fe9c46e016db0dc9c47e14f8">visitBlock</a> (VPBlockBase *Block, Old2NewTy &amp;Old2New, InterleavedAccessInfo &amp;IAI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively traverse <span class="doxyComputerOutput">Block</span> and populate <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> based interleave groups based on <span class="doxyComputerOutput">IAI</span>. <a href="#a2858bd62fe9c46e016db0dc9c47e14f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> *, <a href="/web-llvm/docs/api/classes/llvm/interleavegroup">InterleaveGroup</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> &gt; * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53864f3d9fcd2511de02e56dd0fcc716">InterleaveGroupMap</a></td>
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


<p>Definition at line 4208 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### Old2NewTy {#aaa4e6aad5004da321b41dfe6e3f8584a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::VPInterleavedAccessInfo::Old2NewTy =  DenseMap&lt;InterleaveGroup&lt;Instruction&gt; *,
                             InterleaveGroup&lt;VPInstruction&gt; *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> for mapping of instruction based interleave groups to <a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> interleave groups.</p>

<p>Definition at line 4214 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### VPInterleavedAccessInfo() {#a24f3316a0caf6117d7447bda1023823f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPInterleavedAccessInfo::VPInterleavedAccessInfo (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan, <a href="/web-llvm/docs/api/classes/llvm/interleavedaccessinfo">InterleavedAccessInfo</a> &amp; IAI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 4227 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 1508 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vplan/#a89f94c49b2cb5daaa93d19c89307c307">llvm::VPlan::getVectorLoopRegion</a> and <a href="/web-llvm/docs/api/structs/llvm/vptransformstate/#ac0b363a134c3bfac25ba209704ef3ee3">llvm::VPTransformState::Plan</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~VPInterleavedAccessInfo() {#a03ca2edb6de0ea9337687586713b3d20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPInterleavedAccessInfo::~VPInterleavedAccessInfo ()</td>
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



<p>Definition at line 4229 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getInterleaveGroup() {#a44fe021e1f4e19bb3d99a2a028330b5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InterleaveGroup&lt; VPInstruction &gt; * llvm::VPInterleavedAccessInfo::getInterleaveGroup (<a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> * Instr)</td>
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

<p>Get the interleave group that <span class="doxyComputerOutput">Instr</span> belongs to.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>nullptr if doesn't have such group.</p></dd>
</dl>


<p>Definition at line 4242 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp/#a4794a235e395504cd97192b10601088f">areConsecutiveOrMatch</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### visitBlock() {#a2858bd62fe9c46e016db0dc9c47e14f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPInterleavedAccessInfo::visitBlock (<a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * Block, <a href="/web-llvm/docs/api/classes/llvm/densemap">Old2NewTy</a> &amp; Old2New, <a href="/web-llvm/docs/api/classes/llvm/interleavedaccessinfo">InterleavedAccessInfo</a> &amp; IAI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recursively traverse <span class="doxyComputerOutput">Block</span> and populate <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> based interleave groups based on <span class="doxyComputerOutput">IAI</span>.</p>

<p>Declaration at line 4223 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 1472 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>

</div>
</div>

### visitRegion() {#aeb2a6b577b11f2ba43c61ebba16d7c8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPInterleavedAccessInfo::visitRegion (<a href="/web-llvm/docs/api/classes/llvm/vpregionblock">VPRegionBlock</a> * Region, <a href="/web-llvm/docs/api/classes/llvm/densemap">Old2NewTy</a> &amp; Old2New, <a href="/web-llvm/docs/api/classes/llvm/interleavedaccessinfo">InterleavedAccessInfo</a> &amp; IAI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recursively <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/region">Region</a></span> and populate <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> based interleave groups based on <span class="doxyComputerOutput">IAI</span>.</p>

<p>Declaration at line 4219 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 1462 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### InterleaveGroupMap {#a53864f3d9fcd2511de02e56dd0fcc716}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;VPInstruction *, InterleaveGroup&lt;VPInstruction&gt; *&gt; llvm::VPInterleavedAccessInfo::InterleaveGroupMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4210 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
