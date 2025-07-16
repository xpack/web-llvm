---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/regionnode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RegionNode` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::RegionNode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">llvm/Analysis/RegionInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regionnodebase">RegionNodeBase&lt;Tr&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> represents a subregion or a <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> that is part of a <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>. <a href="/web-llvm/docs/api/classes/llvm/regionnodebase/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43a131df7003bfa82aadda4907be5814">RegionNode</a> (Region *Parent, BasicBlock *Entry, bool isSubRegion=false)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79be7958b88ea3c0f5fa4404787b5302">operator==</a> (const Region &amp;RN) const</td>
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


<p>Definition at line 877 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RegionNode() {#a43a131df7003bfa82aadda4907be5814}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegionNode::RegionNode (<a href="/web-llvm/docs/api/classes/llvm/region">Region</a> * Parent, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Entry, bool isSubRegion=false)</td>
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



<p>Definition at line 879 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/regionnodebase/#a5c6251a6a2d27bec3ef89b0f6b3ad188">llvm::RegionNodeBase&lt; RegionTraits&lt; Function &gt; &gt;::isSubRegion</a> and <a href="/web-llvm/docs/api/classes/llvm/regionnodebase/#a1aeba8f7fe748620d637ae2c1352b91c">llvm::RegionNodeBase&lt; RegionTraits&lt; Function &gt; &gt;::RegionNodeBase</a>.</p>


<p>Referenced by <a href="#a79be7958b88ea3c0f5fa4404787b5302">operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator==() {#a79be7958b88ea3c0f5fa4404787b5302}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RegionNode::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> &amp; RN)</td>
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



<p>Definition at line 882 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>Reference <a href="#a43a131df7003bfa82aadda4907be5814">RegionNode</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
