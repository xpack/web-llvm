---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/regionnodebase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RegionNodeBase` Class Template

<p>A <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> represents a subregion or a <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> that is part of a <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class Tr&gt;
class llvm::RegionNodeBase&lt;Tr&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">llvm/Analysis/RegionInfo.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regionbase">RegionBase&lt;Tr&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A single entry single exit <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>. <a href="/web-llvm/docs/api/classes/llvm/regionbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a99eb170338216f790c45a3657d45ed42">BlockT</a> = typename Tr::BlockT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0235447603be9046b403ba6910756030">RegionT</a> = typename Tr::RegionT</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9ada9295e8da866c659015248e8279e8">RegionBase&lt; Tr &gt;</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a984f8cf1a5a3e96d9e6030a0e5803c1b">RegionNodeBase</a> (const RegionNodeBase &amp;)=delete</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a1aeba8f7fe748620d637ae2c1352b91c">RegionNodeBase</a> (RegionT *Parent, BlockT *Entry, bool isSubRegion=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a>. <a href="#a1aeba8f7fe748620d637ae2c1352b91c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regionnodebase">RegionNodeBase</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a158c159769fc47b214f55d41dc2920c0">operator=</a> (const RegionNodeBase &amp;)=delete</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a0235447603be9046b403ba6910756030">RegionT</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a79b09475f3753504a26dc312d572112e">getParent</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the parent <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> of this <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a>. <a href="#a79b09475f3753504a26dc312d572112e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a99eb170338216f790c45a3657d45ed42">BlockT</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac5e41c46fb95e445164aae977ba0f911">getEntry</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the entry <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> of this <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a>. <a href="#ac5e41c46fb95e445164aae977ba0f911">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a88ded0e066636a1da09e307e75c9c880">getNodeAs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the content of this <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a>. <a href="#a88ded0e066636a1da09e307e75c9c880">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5c6251a6a2d27bec3ef89b0f6b3ad188">isSubRegion</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is this <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> a subregion? <a href="#a5c6251a6a2d27bec3ef89b0f6b3ad188">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac7a247b3585a3954ab1281e92de480bc">getNodeAs</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/region">Region</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adecf7296641e6866d7ee074f72befbec">getNodeAs</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4fba8bc7399cd4547b52de4c15fb109e">getNodeAs</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregion">MachineRegion</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9fdaab81e5a5f87bf8484a579be84a8e">getNodeAs</a> () const</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a>&lt; <a href="#a99eb170338216f790c45a3657d45ed42">BlockT</a> *, 1, bool &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9d90c68111dc3faef3cb59b676d767ff">entry</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the entry basic block that starts this region node. <a href="#a9d90c68111dc3faef3cb59b676d767ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Tr&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a0235447603be9046b403ba6910756030">RegionT</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0445e341e6a9c352cf6a5b98a8684ddb">parent</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The parent <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> of this <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a>. <a href="#a0445e341e6a9c352cf6a5b98a8684ddb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> represents a subregion or a <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> that is part of a <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>.</p>

<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### BlockT {#a99eb170338216f790c45a3657d45ed42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RegionNodeBase&lt; Tr &gt;::BlockT =  typename Tr::BlockT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### RegionT {#a0235447603be9046b403ba6910756030}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RegionNodeBase&lt; Tr &gt;::RegionT =  typename Tr::RegionT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### RegionBase&lt; Tr &gt; {#a9ada9295e8da866c659015248e8279e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/regionbase">RegionBase</a>&lt; Tr &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### RegionNodeBase() {#a984f8cf1a5a3e96d9e6030a0e5803c1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegionNodeBase&lt; Tr &gt;::RegionNodeBase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/regionnodebase">RegionNodeBase</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>Reference <a href="#a1aeba8f7fe748620d637ae2c1352b91c">llvm::RegionNodeBase&lt; Tr &gt;::RegionNodeBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### RegionNodeBase() {#a1aeba8f7fe748620d637ae2c1352b91c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegionNodeBase&lt; Tr &gt;::RegionNodeBase (<a href="#a0235447603be9046b403ba6910756030">RegionT</a> * Parent, <a href="#a99eb170338216f790c45a3657d45ed42">BlockT</a> * Entry, bool isSubRegion=false)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Parent</td>
<td class="doxyParamItemDescription"><p>The parent of this <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Entry</td>
<td class="doxyParamItemDescription"><p>The entry <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> of the <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a>. If this <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> represents a <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>, this is the <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> itself. If it represents a subregion, this is the entry <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> of the subregion.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">isSubRegion</td>
<td class="doxyParamItemDescription"><p>If this <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> represents a SubRegion.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>Reference <a href="#a5c6251a6a2d27bec3ef89b0f6b3ad188">llvm::RegionNodeBase&lt; Tr &gt;::isSubRegion</a>.</p>


<p>Referenced by <a href="#a158c159769fc47b214f55d41dc2920c0">llvm::RegionNodeBase&lt; Tr &gt;::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/regionbase/#aaeb673bce3fe39f6a04bcc5cb93c83c8">llvm::RegionBase&lt; Tr &gt;::RegionBase</a> and <a href="#a984f8cf1a5a3e96d9e6030a0e5803c1b">llvm::RegionNodeBase&lt; Tr &gt;::RegionNodeBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a158c159769fc47b214f55d41dc2920c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegionNodeBase &amp; llvm::RegionNodeBase&lt; Tr &gt;::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/regionnodebase">RegionNodeBase</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>Reference <a href="#a1aeba8f7fe748620d637ae2c1352b91c">llvm::RegionNodeBase&lt; Tr &gt;::RegionNodeBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getEntry() {#ac5e41c46fb95e445164aae977ba0f911}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockT * llvm::RegionNodeBase&lt; Tr &gt;::getEntry ()</td>
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

<p>Get the entry <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> of this <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a>.</p>


<p>If this <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> represents a <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> this is just the <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> itself, otherwise we return the entry <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> of the Subregion</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The entry <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> of this <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a>.</p></dd>
</dl>


<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regionbase/#a88f49bb38a082837dd19ff5b4a062045">llvm::RegionBase&lt; Tr &gt;::getEntry</a>.</p>

</div>
</div>

### getNodeAs() {#a88ded0e066636a1da09e307e75c9c880}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T * llvm::RegionNodeBase&lt; Tr &gt;::getNodeAs ()</td>
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

<p>Get the content of this <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a>.</p>


<p>This can be either a <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> or a subregion. Before calling <a href="#a88ded0e066636a1da09e307e75c9c880">getNodeAs()</a> check the type of the content with the <a href="#a5c6251a6a2d27bec3ef89b0f6b3ad188">isSubRegion()</a> function call.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The content of this <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a>.</p></dd>
</dl>


<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### getNodeAs() {#ac7a247b3585a3954ab1281e92de480bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::RegionNodeBase&lt; RegionTraits&lt; Function &gt; &gt;::getNodeAs&lt; BasicBlock &gt; ()</td>
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



<p>Definition at line 996 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-e5b50eb34ec0db639bdb467f977dace6/#a8fe81aa588d38fa5cde97367d0cfc478">llvm::DOTGraphTraits&lt; RegionInfo * &gt;::getEdgeAttributes</a>.</p>

</div>
</div>

### getNodeAs() {#adecf7296641e6866d7ee074f72befbec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Region * llvm::RegionNodeBase&lt; RegionTraits&lt; Function &gt; &gt;::getNodeAs&lt; Region &gt; ()</td>
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



<p>Definition at line 1004 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### getNodeAs() {#a4fba8bc7399cd4547b52de4c15fb109e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * llvm::RegionNodeBase&lt; RegionTraits&lt; MachineFunction &gt; &gt;::getNodeAs&lt; MachineBasicBlock &gt; ()</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregioninfo-h">MachineRegionInfo.h</a>.</p>

</div>
</div>

### getNodeAs() {#a9fdaab81e5a5f87bf8484a579be84a8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegion * llvm::RegionNodeBase&lt; RegionTraits&lt; MachineFunction &gt; &gt;::getNodeAs&lt; MachineRegion &gt; ()</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregioninfo-h">MachineRegionInfo.h</a>.</p>

</div>
</div>

### getParent() {#a79b09475f3753504a26dc312d572112e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegionT * llvm::RegionNodeBase&lt; Tr &gt;::getParent ()</td>
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

<p>Get the parent <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> of this <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a>.</p>


<p>The parent <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> is the <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> this <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> belongs to. If for example a <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> is element of two Regions, there exist two RegionNodes for this <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>. Each with the <a href="#a79b09475f3753504a26dc312d572112e">getParent()</a> function pointing to the <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> this <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> belongs to.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Get the parent <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> of this <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a>.</p></dd>
</dl>


<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regionbase/#a7ed9c79ac80ed5996c7e241814302eab">llvm::RegionBase&lt; Tr &gt;::getParent</a>.</p>

</div>
</div>

### isSubRegion() {#a5c6251a6a2d27bec3ef89b0f6b3ad188}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RegionNodeBase&lt; Tr &gt;::isSubRegion ()</td>
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

<p>Is this <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> a subregion?</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if it contains a subregion. False if it contains a <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>.</p></dd>
</dl>


<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-e5b50eb34ec0db639bdb467f977dace6/#a8fe81aa588d38fa5cde97367d0cfc478">llvm::DOTGraphTraits&lt; RegionInfo * &gt;::getEdgeAttributes</a> and <a href="#a1aeba8f7fe748620d637ae2c1352b91c">llvm::RegionNodeBase&lt; Tr &gt;::RegionNodeBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### entry {#a9d90c68111dc3faef3cb59b676d767ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerIntPair&lt;BlockT *, 1, bool&gt; llvm::RegionNodeBase&lt; Tr &gt;::entry</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is the entry basic block that starts this region node.</p>


<p>If this is a <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a>, then entry is just the basic block, that this <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> represents. Otherwise it is the entry of this (Sub)<a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a>.</p>


<p>In the BBtoRegionNode map of the parent of this node, BB will always map to this node no matter which kind of node this one is.</p>


<p>The node can hold either a <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> or a <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> one bit to save, if this <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> is a subregion or <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a>.</p>


<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

### parent {#a0445e341e6a9c352cf6a5b98a8684ddb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tr&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegionT* llvm::RegionNodeBase&lt; Tr &gt;::parent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The parent <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> of this <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#a79b09475f3753504a26dc312d572112e">getParent()</a></p></dd>
</dl>


<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregioninfo-h">MachineRegionInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
