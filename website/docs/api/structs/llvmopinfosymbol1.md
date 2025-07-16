---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvmopinfosymbol1
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LLVMOpInfoSymbol1` Struct Reference

<p>The initial support in LLVM MC for the most general form of a relocatable expression is "AddSymbol - SubtractSymbol + Offset". <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct LLVMOpInfoSymbol1 { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">llvm-c/DisassemblerTypes.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03a90bff1e766901579a900fd4f870a1">Present</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60a11f3a829fd9bbeb3071bf372bcef0">Name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada98ba08ab672b331d230197a788e625">Value</a></td>
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

<p>The initial support in LLVM MC for the most general form of a relocatable expression is "AddSymbol - SubtractSymbol + Offset".</p>


<p>For some Darwin targets this full form is encoded in the relocation information so that AddSymbol and SubtractSymbol can be link edited independent of each other. Many other platforms only allow a relocatable expression of the form AddSymbol + Offset to be encoded.</p>


<p>The <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gaa8eb7ea1e53fd6e7a11b6aa4749c6e60">LLVMOpInfoCallback()</a> for the TagType value of 1 uses the struct <a href="/web-llvm/docs/api/structs/llvmopinfo1">LLVMOpInfo1</a>. The value of the relocatable expression for the operand, including any PC adjustment, is passed in to the call back in the Value field. The symbolic information about the operand is returned using all the fields of the structure with the Offset of the relocatable expression returned in the Value field. It is possible that some symbols in the relocatable expression were assembly temporary symbols, for example "Ldata - LpicBase + constant", and only the Values of the symbols without symbol names are present in the relocation information. The VariantKind type is one of the Target specific #defines below and is used to print operands like "_foo@GOT", ":lower16:_foo", etc.</p>


<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Name {#a60a11f3a829fd9bbeb3071bf372bcef0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* LLVMOpInfoSymbol1::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#aadc518cf2b179163c8eca58f17e333b2">llvm::AArch64ExternalSymbolizer::tryAddingSymbolicOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#aa4807aa3571299368e6d9b5c3d39893a">llvm::MCExternalSymbolizer::tryAddingSymbolicOperand</a>.</p>

</div>
</div>

### Present {#a03a90bff1e766901579a900fd4f870a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t LLVMOpInfoSymbol1::Present</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#aadc518cf2b179163c8eca58f17e333b2">llvm::AArch64ExternalSymbolizer::tryAddingSymbolicOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#aa4807aa3571299368e6d9b5c3d39893a">llvm::MCExternalSymbolizer::tryAddingSymbolicOperand</a>.</p>

</div>
</div>

### Value {#ada98ba08ab672b331d230197a788e625}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t LLVMOpInfoSymbol1::Value</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#aadc518cf2b179163c8eca58f17e333b2">llvm::AArch64ExternalSymbolizer::tryAddingSymbolicOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#aa4807aa3571299368e6d9b5c3d39893a">llvm::MCExternalSymbolizer::tryAddingSymbolicOperand</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
