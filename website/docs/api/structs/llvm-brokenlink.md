---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/brokenlink
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `BrokenLink` Struct Reference

<p>A broken link in the keep chain. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::BrokenLink { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c9283f2eef5ac80854bc8b226694c6c">BrokenLink</a> (DWARFDie Parent, DWARFDie Child)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40eaa74bacded0e57e9d9c79c49920ea">Parent</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af64390f74646910a7c6b5979fc84ba94">Child</a></td>
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

<p>A broken link in the keep chain.</p>


<p>By recording both the parent and the child we can show only broken links for DIEs with multiple children.</p>


<p>Definition at line 955 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BrokenLink() {#a4c9283f2eef5ac80854bc8b226694c6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BrokenLink::BrokenLink (<a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> Parent, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> Child)</td>
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



<p>Definition at line 956 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>


<p>References <a href="#af64390f74646910a7c6b5979fc84ba94">Child</a> and <a href="#a40eaa74bacded0e57e9d9c79c49920ea">Parent</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Child {#af64390f74646910a7c6b5979fc84ba94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie llvm::BrokenLink::Child</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 958 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>


<p>Referenced by <a href="#a4c9283f2eef5ac80854bc8b226694c6c">BrokenLink</a>.</p>

</div>
</div>

### Parent {#a40eaa74bacded0e57e9d9c79c49920ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie llvm::BrokenLink::Parent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 957 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>


<p>Referenced by <a href="#a4c9283f2eef5ac80854bc8b226694c6c">BrokenLink</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
