---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/object/pgoanalysismap/pgobbentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `PGOBBEntry` Struct Reference

<p>Extra basic block data with fields for block frequency and branch probability. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::object::PGOAnalysisMap::PGOBBEntry { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elftypes-h">llvm/Object/ELFTypes.h</a>"
</div>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80c2c9bc206eeba32e5106a27548da9e">operator==</a> (const PGOBBEntry &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abed45a433525f98699a4ce2a58153c6e">BlockFreq</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Block frequency taken from MBFI. <a href="#abed45a433525f98699a4ce2a58153c6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">llvm::SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/object/pgoanalysismap/pgobbentry/successorentry">SuccessorEntry</a>, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad6d601028e0aa7e77b8e18b7d621386">Successors</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of successors of the current block. <a href="#aad6d601028e0aa7e77b8e18b7d621386">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Extra basic block data with fields for block frequency and branch probability.</p>

<p>Definition at line 993 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elftypes-h">ELFTypes.h</a>.</p>


<div class="doxySectionDef">

## Public Operators

### operator==() {#a80c2c9bc206eeba32e5106a27548da9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::PGOAnalysisMap::PGOBBEntry::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/pgoanalysismap/pgobbentry">PGOBBEntry</a> &amp; Other)</td>
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



<p>Definition at line 1012 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elftypes-h">ELFTypes.h</a>.</p>


<p>References <a href="#abed45a433525f98699a4ce2a58153c6e">BlockFreq</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#aad6d601028e0aa7e77b8e18b7d621386">Successors</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BlockFreq {#abed45a433525f98699a4ce2a58153c6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequency llvm::object::PGOAnalysisMap::PGOBBEntry::BlockFreq</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Block frequency taken from MBFI.</p>

<p>Definition at line 1008 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elftypes-h">ELFTypes.h</a>.</p>


<p>Referenced by <a href="#a80c2c9bc206eeba32e5106a27548da9e">operator==</a>.</p>

</div>
</div>

### Successors {#aad6d601028e0aa7e77b8e18b7d621386}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallVector&lt;SuccessorEntry, 2&gt; llvm::object::PGOAnalysisMap::PGOBBEntry::Successors</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of successors of the current block.</p>

<p>Definition at line 1010 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elftypes-h">ELFTypes.h</a>.</p>


<p>Referenced by <a href="#a80c2c9bc206eeba32e5106a27548da9e">operator==</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elftypes-h">ELFTypes.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
