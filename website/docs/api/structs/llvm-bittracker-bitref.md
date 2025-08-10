---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/bittracker/bitref
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `BitRef` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::BitTracker::BitRef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">Target/Hexagon/BitTracker.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cf7823b8cd6042fd0066e527e932f6b">BitRef</a> (unsigned R=0, uint16_t P=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad31446737b9e87bafa14c9da05dcb4cc">operator==</a> (const BitRef &amp;BR) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40e257127c0ff61f7ce778d68468096c">Reg</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab66cddedf2717fe3649ae4aecc6232c5">Pos</a></td>
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


<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BitRef() {#a9cf7823b8cd6042fd0066e527e932f6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BitTracker::BitRef::BitRef (unsigned R=0, uint16_t P=0)</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#ab66cddedf2717fe3649ae4aecc6232c5">Pos</a> and <a href="#a40e257127c0ff61f7ce778d68468096c">Reg</a>.</p>


<p>Referenced by <a href="#ad31446737b9e87bafa14c9da05dcb4cc">operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator==() {#ad31446737b9e87bafa14c9da05dcb4cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BitTracker::BitRef::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitref">BitRef</a> &amp; BR)</td>
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



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>References <a href="#a9cf7823b8cd6042fd0066e527e932f6b">BitRef</a>, <a href="#ab66cddedf2717fe3649ae4aecc6232c5">Pos</a> and <a href="#a40e257127c0ff61f7ce778d68468096c">Reg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Pos {#ab66cddedf2717fe3649ae4aecc6232c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::BitTracker::BitRef::Pos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>Referenced by <a href="#a9cf7823b8cd6042fd0066e527e932f6b">BitRef</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagongeninsert-cpp-/bitvalueordering/#a79d74e7a161f1e6c0e5ec74bc7044e31">anonymous{HexagonGenInsert.cpp}::BitValueOrdering::operator()</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#aedf49831b316ebf268837d62a1f22385">llvm::BitTracker::BitValue::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a125f77300db175faeae41d9a628194d6">llvm::BitTracker::RegisterCell::operator&lt;&lt;</a>, <a href="#ad31446737b9e87bafa14c9da05dcb4cc">operator==</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#ad20a19c881ef4af1b3a270bf06fa8d89">llvm::BitTracker::BitValue::self</a>.</p>

</div>
</div>

### Reg {#a40e257127c0ff61f7ce778d68468096c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::BitTracker::BitRef::Reg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>Referenced by <a href="#a9cf7823b8cd6042fd0066e527e932f6b">BitRef</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagongeninsert-cpp-/bitvalueordering/#a79d74e7a161f1e6c0e5ec74bc7044e31">anonymous{HexagonGenInsert.cpp}::BitValueOrdering::operator()</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#aedf49831b316ebf268837d62a1f22385">llvm::BitTracker::BitValue::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a125f77300db175faeae41d9a628194d6">llvm::BitTracker::RegisterCell::operator&lt;&lt;</a>, <a href="#ad31446737b9e87bafa14c9da05dcb4cc">operator==</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#ad20a19c881ef4af1b3a270bf06fa8d89">llvm::BitTracker::BitValue::self</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
