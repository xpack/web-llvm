---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvmorccdependencemappair
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `LLVMOrcCDependenceMapPair` Struct

<p>Represents a pair of a JITDylib and <a href="/web-llvm/docs/api/structs/llvmorccsymbolslist">LLVMOrcCSymbolsList</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct LLVMOrcCDependenceMapPair { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/orc-h">llvm-c/Orc.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaf57ee27735dc1436c076c9579d074869">LLVMOrcJITDylibRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7608f62e5066cd60e26e066d8eba4c60">JD</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvmorccsymbolslist">LLVMOrcCSymbolsList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5189d2c4ab9ad944f768a4f59f3b79e">Names</a></td>
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

<p>Represents a pair of a JITDylib and <a href="/web-llvm/docs/api/structs/llvmorccsymbolslist">LLVMOrcCSymbolsList</a>.</p>

<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/orc-h">Orc.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### JD {#a7608f62e5066cd60e26e066d8eba4c60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMOrcJITDylibRef LLVMOrcCDependenceMapPair::JD</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/orc-h">Orc.h</a>.</p>

</div>
</div>

### Names {#ac5189d2c4ab9ad944f768a4f59f3b79e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMOrcCSymbolsList LLVMOrcCDependenceMapPair::Names</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/orc-h">Orc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvmorclazycallthroughmanagerref/#ac2cd4bbc01d2cd5cd5ba1cb37b7b4140">LLVMOrcLazyCallThroughManagerRef::toSymbolDependenceMap</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm-c/orc-h">Orc.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
