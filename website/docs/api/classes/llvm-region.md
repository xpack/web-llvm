---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/region
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Region` Class



## Declaration

<div class="doxyDeclaration">
class llvm::Region { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">llvm/Analysis/RegionInfo.h</a>"
</div>

## Base class

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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5663f2b2d561b78cda5e41644423f50">Region</a> (BasicBlock *Entry, BasicBlock *Exit, RegionInfo *RI, DominatorTree *DT, Region *Parent=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c3670fff78f7511d156e3b2f0bc6266">~Region</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41bc01a00d7a6ae1acd4f3b1e9c0e13e">operator==</a> (const RegionNode &amp;RN) const</td>
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


<p>Definition at line 887 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Region() {#ac5663f2b2d561b78cda5e41644423f50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Region::Region (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Entry, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Exit, <a href="/web-llvm/docs/api/classes/llvm/regioninfo">RegionInfo</a> * RI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> * Parent=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 889 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regioninfo-cpp">RegionInfo.cpp</a>.</p>


<p>References <a href="#ac5663f2b2d561b78cda5e41644423f50">Region</a> and <a href="/web-llvm/docs/api/classes/llvm/regionbase/#aaeb673bce3fe39f6a04bcc5cb93c83c8">llvm::RegionBase&lt; RegionTraits&lt; Function &gt; &gt;::RegionBase</a>.</p>


<p>Referenced by <a href="#ac5663f2b2d561b78cda5e41644423f50">Region</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~Region() {#a3c3670fff78f7511d156e3b2f0bc6266}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Region::~Region ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 891 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator==() {#a41bc01a00d7a6ae1acd4f3b1e9c0e13e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Region::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> &amp; RN)</td>
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



<p>Definition at line 893 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/regioninfo-cpp">RegionInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
