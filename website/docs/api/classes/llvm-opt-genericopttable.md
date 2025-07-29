---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/opt/genericopttable
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GenericOptTable` Class

<p>Specialization of <a href="/web-llvm/docs/api/classes/llvm/opt/opttable">OptTable</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::opt::GenericOptTable { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">llvm/Option/OptTable.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/opt/opttable">OptTable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide access to the <a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a> info table. <a href="/web-llvm/docs/api/classes/llvm/opt/opttable/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3179665bf593185b092d08113399ae8">GenericOptTable</a> (const StringTable &amp;StrTable, ArrayRef&lt; StringTable::Offset &gt; PrefixesTable, ArrayRef&lt; Info &gt; OptionInfos, bool IgnoreCase=false)</td>
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

<p>Specialization of <a href="/web-llvm/docs/api/classes/llvm/opt/opttable">OptTable</a>.</p>

<p>Definition at line 426 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### GenericOptTable() {#ac3179665bf593185b092d08113399ae8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericOptTable::GenericOptTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringtable">StringTable</a> &amp; StrTable, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringtable/offset">StringTable::Offset</a> &gt; PrefixesTable, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/opt/opttable/info">Info</a> &gt; OptionInfos, bool IgnoreCase=false)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 428 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a>, definition at line 792 of file <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp">OptTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/opt/opttable/#a01fdf8f5ab053f70c4c67fd8361b60d5">llvm::opt::OptTable::buildPrefixChars</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/opttable/#a17c70cba1015342a5a66a5bf0e110f95">llvm::opt::OptTable::FirstSearchableIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a>, <a href="/web-llvm/docs/api/structs/llvm/opt/opttable/info/#a5d03c89b71f75f63090bf052e415cd41">llvm::opt::OptTable::Info::getPrefixOffsets</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/opttable/#a25c39b3831711b590024c338280aca72">llvm::opt::OptTable::OptTable</a> and <a href="/web-llvm/docs/api/classes/llvm/opt/opttable/#a2f70e420cd97fc15e415b7e4c16c6deb">llvm::opt::OptTable::PrefixesUnion</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/opttable-h">OptTable.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp">OptTable.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
