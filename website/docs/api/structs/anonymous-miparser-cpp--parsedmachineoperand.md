---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-miparser-cpp-/parsedmachineoperand
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ParsedMachineOperand` Struct

<p>A wrapper struct around the '<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a>' struct that includes a source range and other attributes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{MIParser.cpp}::ParsedMachineOperand { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04493a627f2f3c4eaeaf66c59d574bac">ParsedMachineOperand</a> (const MachineOperand &amp;Operand, StringRef::iterator Begin, StringRef::iterator End, std::optional&lt; unsigned &gt; &amp;TiedDefIdx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a617d179dc59bc16992bb3054427fa55a">Operand</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a361486b5a722f9bb1f4b02b382462080">Begin</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a66840aa7996853ac6680761fdc670c">End</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3860aedb5687635f57662225b2328dbe">TiedDefIdx</a></td>
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

<p>A wrapper struct around the '<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a>' struct that includes a source range and other attributes.</p>

<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ParsedMachineOperand() {#a04493a627f2f3c4eaeaf66c59d574bac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MIParser.cpp}::ParsedMachineOperand::ParsedMachineOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Operand, <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a> Begin, <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a> End, std::optional&lt; unsigned &gt; &amp; TiedDefIdx)</td>
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



<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a361486b5a722f9bb1f4b02b382462080">Begin</a>, <a href="#a9a66840aa7996853ac6680761fdc670c">End</a>, <a href="#a617d179dc59bc16992bb3054427fa55a">Operand</a> and <a href="#a3860aedb5687635f57662225b2328dbe">TiedDefIdx</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Begin {#a361486b5a722f9bb1f4b02b382462080}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef::iterator anonymous{MIParser.cpp}::ParsedMachineOperand::Begin</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>Referenced by <a href="#a04493a627f2f3c4eaeaf66c59d574bac">ParsedMachineOperand</a>.</p>

</div>
</div>

### End {#a9a66840aa7996853ac6680761fdc670c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef::iterator anonymous{MIParser.cpp}::ParsedMachineOperand::End</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>Referenced by <a href="#a04493a627f2f3c4eaeaf66c59d574bac">ParsedMachineOperand</a>.</p>

</div>
</div>

### Operand {#a617d179dc59bc16992bb3054427fa55a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand anonymous{MIParser.cpp}::ParsedMachineOperand::Operand</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>Referenced by <a href="#a04493a627f2f3c4eaeaf66c59d574bac">ParsedMachineOperand</a>.</p>

</div>
</div>

### TiedDefIdx {#a3860aedb5687635f57662225b2328dbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;unsigned&gt; anonymous{MIParser.cpp}::ParsedMachineOperand::TiedDefIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a>.</p>


<p>Referenced by <a href="#a04493a627f2f3c4eaeaf66c59d574bac">ParsedMachineOperand</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp">MIParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
