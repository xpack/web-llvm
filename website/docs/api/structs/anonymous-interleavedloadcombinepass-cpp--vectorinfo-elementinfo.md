---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo/elementinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ElementInfo` Struct Reference

<p>Information of a Vector Element. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::ElementInfo { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2982064734c7280051dc1f73be3978b1">ElementInfo</a> (Polynomial Offset=Polynomial(), LoadInst *LI=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-interleavedloadcombinepass-cpp-/polynomial">Polynomial</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39efe97c9d8eb5beb817f438feba50ca">Ofs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Offset <a href="/web-llvm/docs/api/classes/anonymous-interleavedloadcombinepass-cpp-/polynomial">Polynomial</a>. <a href="#a39efe97c9d8eb5beb817f438feba50ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58257478afd480ed1b208a77109e3af0">LI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The Load <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> used to Load the entry. <a href="#a58257478afd480ed1b208a77109e3af0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Information of a Vector Element.</p>

<p>Definition at line 644 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ElementInfo() {#a2982064734c7280051dc1f73be3978b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::ElementInfo::ElementInfo (<a href="/web-llvm/docs/api/classes/anonymous-interleavedloadcombinepass-cpp-/polynomial">Polynomial</a> Offset=<a href="/web-llvm/docs/api/classes/anonymous-interleavedloadcombinepass-cpp-/polynomial">Polynomial</a>(), <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * LI=nullptr)</td>
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



<p>Definition at line 652 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>References <a href="#a58257478afd480ed1b208a77109e3af0">LI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="#a39efe97c9d8eb5beb817f438feba50ca">Ofs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### LI {#a58257478afd480ed1b208a77109e3af0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoadInst* anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::ElementInfo::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The Load <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> used to Load the entry.</p>


<p>LI is null if the pointer of the load instruction does not point on to the entry</p>


<p>Definition at line 650 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo/#a30656b818497e335ff16282be4fe6300">anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::computeFromBCI</a> and <a href="#a2982064734c7280051dc1f73be3978b1">ElementInfo</a>.</p>

</div>
</div>

### Ofs {#a39efe97c9d8eb5beb817f438feba50ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Polynomial anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::ElementInfo::Ofs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Offset <a href="/web-llvm/docs/api/classes/anonymous-interleavedloadcombinepass-cpp-/polynomial">Polynomial</a>.</p>

<p>Definition at line 646 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo/#a30656b818497e335ff16282be4fe6300">anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::computeFromBCI</a> and <a href="#a2982064734c7280051dc1f73be3978b1">ElementInfo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedloadcombinepass-cpp">InterleavedLoadCombinePass.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
