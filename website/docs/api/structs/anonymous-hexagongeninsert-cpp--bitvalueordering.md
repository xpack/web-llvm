---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-hexagongeninsert-cpp-/bitvalueordering
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `BitValueOrdering` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{HexagonGenInsert.cpp}::BitValueOrdering { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf2a415387d2a2d69c06e409f67f523f">BitValueOrdering</a> (const RegisterOrdering &amp;RB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79d74e7a161f1e6c0e5ec74bc7044e31">operator()</a> (const BitTracker::BitValue &amp;V1, const BitTracker::BitValue &amp;V2) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagongeninsert-cpp-/registerordering">RegisterOrdering</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97125a3c0ca530d263a0ec2e9cb55ea6">BaseOrd</a></td>
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


<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongeninsert-cpp">HexagonGenInsert.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BitValueOrdering() {#aaf2a415387d2a2d69c06e409f67f523f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{HexagonGenInsert.cpp}::BitValueOrdering::BitValueOrdering (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagongeninsert-cpp-/registerordering">RegisterOrdering</a> &amp; RB)</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongeninsert-cpp">HexagonGenInsert.cpp</a>.</p>


<p>Reference <a href="#a97125a3c0ca530d263a0ec2e9cb55ea6">BaseOrd</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator()() {#a79d74e7a161f1e6c0e5ec74bc7044e31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BitValueOrdering::operator() (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue">BitTracker::BitValue</a> &amp; V1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue">BitTracker::BitValue</a> &amp; V2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongeninsert-cpp">HexagonGenInsert.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a97125a3c0ca530d263a0ec2e9cb55ea6">BaseOrd</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#abdda211d574b7a9074aa1cdb1b0b204b">llvm::BitTracker::BitValue::is</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitref/#ab66cddedf2717fe3649ae4aecc6232c5">llvm::BitTracker::BitRef::Pos</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#a6430b3f9e35d7d7e83399a565cfd143e">llvm::BitTracker::BitValue::RefI</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitref/#a40e257127c0ff61f7ce778d68468096c">llvm::BitTracker::BitRef::Reg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BaseOrd {#a97125a3c0ca530d263a0ec2e9cb55ea6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterOrdering&amp; anonymous{HexagonGenInsert.cpp}::BitValueOrdering::BaseOrd</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongeninsert-cpp">HexagonGenInsert.cpp</a>.</p>


<p>Referenced by <a href="#aaf2a415387d2a2d69c06e409f67f523f">BitValueOrdering</a> and <a href="#a79d74e7a161f1e6c0e5ec74bc7044e31">operator()</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongeninsert-cpp">HexagonGenInsert.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
