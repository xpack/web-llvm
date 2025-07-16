---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-varlocbasedimpl-cpp-/varlocbasedldv/varlocmap
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `VarLocMap` Class Reference

<p>VarLocMap is used for two things: 1) Assigning <a href="/web-llvm/docs/api/namespaces/anonymous-varlocbasedimpl-cpp-/#a1a71406009b70e55de914dc6374ce484">LocIndices</a> to a VarLoc. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLocMap { ... }
</div>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> VarLoc &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3553e1c6b52ae59b4ab7ffda565a973">operator[]</a> (LocIndex ID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve the unique VarLoc associated with <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a></span>. <a href="#ae3553e1c6b52ae59b4ab7ffda565a973">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-varlocbasedimpl-cpp-/#a1a71406009b70e55de914dc6374ce484">LocIndices</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9733e0076f3e32e8d3fa76041c3f538b">insert</a> (const VarLoc &amp;VL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve <a href="/web-llvm/docs/api/namespaces/anonymous-varlocbasedimpl-cpp-/#a1a71406009b70e55de914dc6374ce484">LocIndices</a> for <span class="doxyComputerOutput">VL</span>. <a href="#a9733e0076f3e32e8d3fa76041c3f538b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-varlocbasedimpl-cpp-/#a1a71406009b70e55de914dc6374ce484">LocIndices</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e0fadebc596b875011d003c2d4e7351">getAllIndices</a> (const VarLoc &amp;VL) const</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; VarLoc, <a href="/web-llvm/docs/api/namespaces/anonymous-varlocbasedimpl-cpp-/#a1a71406009b70e55de914dc6374ce484">LocIndices</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45a77def47096d81761da069cfab283b">Var2Indices</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map a VarLoc to an index within the vector reserved for its location within Loc2Vars. <a href="#a45a77def47096d81761da069cfab283b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-varlocbasedimpl-cpp-/locindex/#a626afd7de7fed611fa6307b8d3f40f6f">LocIndex::u32_location_t</a>, std::vector&lt; VarLoc &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2fa91ccccb6033615887c92399e4e18">Loc2Vars</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map a location to a vector which holds VarLocs which live in that location. <a href="#ae2fa91ccccb6033615887c92399e4e18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>VarLocMap is used for two things: 1) Assigning <a href="/web-llvm/docs/api/namespaces/anonymous-varlocbasedimpl-cpp-/#a1a71406009b70e55de914dc6374ce484">LocIndices</a> to a VarLoc.</p>


<p>The <a href="/web-llvm/docs/api/namespaces/anonymous-varlocbasedimpl-cpp-/#a1a71406009b70e55de914dc6374ce484">LocIndices</a> can be used to virtually insert a VarLoc into a <a href="/web-llvm/docs/api/namespaces/anonymous-varlocbasedimpl-cpp-/#a0fcac79d5789c3482f72fdb2eb8d0a32">VarLocSet</a>. 2) Given a <a href="/web-llvm/docs/api/structs/anonymous-varlocbasedimpl-cpp-/locindex">LocIndex</a>, look up the unique associated VarLoc.</p>


<p>Definition at line 790 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>


<div class="doxySectionDef">

## Public Operators

### operator\[\]() {#ae3553e1c6b52ae59b4ab7ffda565a973}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VarLoc &amp; anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLocMap::operator[] (<a href="/web-llvm/docs/api/structs/anonymous-varlocbasedimpl-cpp-/locindex">LocIndex</a> ID)</td>
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

<p>Retrieve the unique VarLoc associated with <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a></span>.</p>

<p>Definition at line 845 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAllIndices() {#a5e0fadebc596b875011d003c2d4e7351}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocIndices anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLocMap::getAllIndices (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> VarLoc &amp; VL)</td>
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



<p>Definition at line 838 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### insert() {#a9733e0076f3e32e8d3fa76041c3f538b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocIndices anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLocMap::insert (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> VarLoc &amp; VL)</td>
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

<p>Retrieve <a href="/web-llvm/docs/api/namespaces/anonymous-varlocbasedimpl-cpp-/#a1a71406009b70e55de914dc6374ce484">LocIndices</a> for <span class="doxyComputerOutput">VL</span>.</p>

<p>Definition at line 801 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Loc2Vars {#ae2fa91ccccb6033615887c92399e4e18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;LocIndex::u32_location_t, std::vector&lt;VarLoc&gt; &gt; anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLocMap::Loc2Vars</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map a location to a vector which holds VarLocs which live in that location.</p>

<p>Definition at line 797 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### Var2Indices {#a45a77def47096d81761da069cfab283b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;VarLoc, LocIndices&gt; anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLocMap::Var2Indices</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map a VarLoc to an index within the vector reserved for its location within Loc2Vars.</p>

<p>Definition at line 793 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
