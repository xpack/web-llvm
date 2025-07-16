---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/asmcond
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AsmCond` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/asmcond">AsmCond</a> - Class to support conditional assembly. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AsmCond { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmcond-h">llvm/MC/MCParser/AsmCond.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ConditionalAssemblyType { <a href="#aff544130617462052044ecd6b065bf60">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aff544130617462052044ecd6b065bf60">ConditionalAssemblyType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5ad0559afdf12eaa55b0e4f3165d08b">TheCond</a> = <a href="#aff544130617462052044ecd6b065bf60a349f6da2e3e0e73737f2b7f657521651">NoCond</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa4c4a0b442e11247ebcad181efb556c">CondMet</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab86a4572bd9b87223e026101d390cb46">Ignore</a> = false</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/asmcond">AsmCond</a> - Class to support conditional assembly.</p>


<p>The conditional assembly feature (.if, .else, .elseif and .endif) is implemented with <a href="/web-llvm/docs/api/classes/llvm/asmcond">AsmCond</a> that tells us what we are in the middle of processing. Ignore can be either true or false. When true we are ignoring the block of code in the middle of a conditional.</p>


<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmcond-h">AsmCond.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### ConditionalAssemblyType {#aff544130617462052044ecd6b065bf60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AsmCond::ConditionalAssemblyType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoCond<a id="aff544130617462052044ecd6b065bf60a349f6da2e3e0e73737f2b7f657521651"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IfCond<a id="aff544130617462052044ecd6b065bf60aaa805018402e7bb125924a3d0057656d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ElseIfCond<a id="aff544130617462052044ecd6b065bf60ae3658550bda145f097d2524419cbf7a7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ElseCond<a id="aff544130617462052044ecd6b065bf60a933d3702a50109e4d49c0d23a01ecfaa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmcond-h">AsmCond.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CondMet {#afa4c4a0b442e11247ebcad181efb556c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AsmCond::CondMet = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmcond-h">AsmCond.h</a>.</p>

</div>
</div>

### Ignore {#ab86a4572bd9b87223e026101d390cb46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AsmCond::Ignore = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmcond-h">AsmCond.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a1f9777a39f525bf9f8a85ce9d52cccd9">anonymous{AsmParser.cpp}::AsmParser::Run</a> and <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a46449244c1f2d4e4b2022d1126e7c5ab">anonymous{MasmParser.cpp}::MasmParser::Run</a>.</p>

</div>
</div>

### TheCond {#ab5ad0559afdf12eaa55b0e4f3165d08b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConditionalAssemblyType llvm::AsmCond::TheCond = <a href="#aff544130617462052044ecd6b065bf60a349f6da2e3e0e73737f2b7f657521651">NoCond</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmcond-h">AsmCond.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a1f9777a39f525bf9f8a85ce9d52cccd9">anonymous{AsmParser.cpp}::AsmParser::Run</a> and <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a46449244c1f2d4e4b2022d1126e7c5ab">anonymous{MasmParser.cpp}::MasmParser::Run</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/asmcond-h">AsmCond.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
