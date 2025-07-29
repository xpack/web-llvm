---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/machinemoduleinfowasm
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MachineModuleInfoWasm` Class

<p><a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfowasm">MachineModuleInfoWasm</a> - This is a <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfoimpl">MachineModuleInfoImpl</a> implementation for Wasm targets. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MachineModuleInfoWasm { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfoimpls-h">llvm/CodeGen/MachineModuleInfoImpls.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfoimpl">MachineModuleInfoImpl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class can be derived from and used by targets to hold private target-specific information for each <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>. <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfoimpl/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e93d8feaab7c70d3624b673601086da">MachineModuleInfoWasm</a> (const MachineModuleInfo &amp;)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58356d53f2588452f8c777d82edb6251">anchor</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5aa57db9835c70f4de98ecc5100ab2f">MachineSymbolsUsed</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfowasm">MachineModuleInfoWasm</a> - This is a <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfoimpl">MachineModuleInfoImpl</a> implementation for Wasm targets.</p>

<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfoimpls-h">MachineModuleInfoImpls.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MachineModuleInfoWasm() {#a6e93d8feaab7c70d3624b673601086da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineModuleInfoWasm::MachineModuleInfoWasm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> &amp;)</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfoimpls-h">MachineModuleInfoImpls.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#a58356d53f2588452f8c777d82edb6251}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineModuleInfoWasm::anchor ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfoimpls-h">MachineModuleInfoImpls.h</a>, definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinemoduleinfoimpls-cpp">MachineModuleInfoImpls.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### MachineSymbolsUsed {#ac5aa57db9835c70f4de98ecc5100ab2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetVector&lt;StringRef&gt; llvm::MachineModuleInfoWasm::MachineSymbolsUsed</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfoimpls-h">MachineModuleInfoImpls.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#aa29ca0ef805870463b1abf3171c5cf1c">llvm::WebAssemblyAsmPrinter::emitDecls</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfoimpls-h">MachineModuleInfoImpls.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinemoduleinfoimpls-cpp">MachineModuleInfoImpls.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
