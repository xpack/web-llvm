---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/ir/fpenv-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `FPEnv.cpp` File

<p>This file contains the implementations of entities that describe floating point environment. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fpenv-h">llvm/IR/FPEnv.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">llvm/ADT/StringSwitch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">llvm/IR/Intrinsics.h</a>"
#include &lt;optional&gt;
#include "llvm/IR/ConstrainedOps.def"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb1562b4fc2af28e0902580ce98800fd">INSTRUCTION</a>(NAME, NARG, ROUND_MODE, INTRINSIC)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af03a9549e7632dcca1a384646da10642">FUNCTION</a>(NAME, NARG, ROUND_MODE, INTRINSIC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21d38d06e4cf1a698c0a1d0d60811d34">CMP_INSTRUCTION</a>(NAME, NARG, ROUND_MODE, INTRINSIC, DAGN)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad383934ba665f875dec52d4066a8b587">FUNCTION</a>(NAME, NARG, ROUND_MODE, INTRINSIC)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac76c80c50f8ec1335d0a5a5ae26ab3da">INSTRUCTION</a>(NAME, NARG, ROUND_MODE, INTRINSIC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78000d72d57a644d003d08015b8a6c5b">CMP_INSTRUCTION</a>(NAME, NARG, ROUND_MODE, INTRINSIC, DAGN)</td>
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

<p>This file contains the implementations of entities that describe floating point environment.</p>

<div class="doxySectionDef">

## Macro Definitions

### CMP\_INSTRUCTION {#a21d38d06e4cf1a698c0a1d0d60811d34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CMP_INSTRUCTION(NAME, NARG, ROUND_MODE, INTRINSIC, DAGN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/fpenv-cpp">FPEnv.cpp</a>.</p>

</div>
</div>

### CMP\_INSTRUCTION {#a78000d72d57a644d003d08015b8a6c5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CMP_INSTRUCTION(NAME, NARG, ROUND_MODE, INTRINSIC, DAGN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/fpenv-cpp">FPEnv.cpp</a>.</p>

</div>
</div>

### FUNCTION {#af03a9549e7632dcca1a384646da10642}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION(NAME, NARG, ROUND_MODE, INTRINSIC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/fpenv-cpp">FPEnv.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-811ae43c28cafd3ad6d10512390e7b83/#a7ee6b18ce8af89b20d73a648baee5090">llvm::yaml::ScalarEnumerationTraits&lt; WasmYAML::ComdatKind &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-31797686350f02d80165f80902559b21/#ac5b8f6d035149c16326319fc0d5d3504">llvm::yaml::ScalarEnumerationTraits&lt; WasmYAML::ExportKind &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-4d3b57d02aa31561a81549422cec002a/#a0c1f18fc9fdd6562607eb852adf9aa9e">llvm::yaml::ScalarEnumerationTraits&lt; WasmYAML::SectionType &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-69628323fc5d4466075199eb0e0fa69d/#a70de3432b4436060c4192ad81a5df3db">llvm::yaml::ScalarEnumerationTraits&lt; WasmYAML::SymbolKind &gt;::enumeration</a> and <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp/#ad0ea28d901a2351fedec9ef3deec2663">GetCodeName</a>.</p>

</div>
</div>

### FUNCTION {#ad383934ba665f875dec52d4066a8b587}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION(NAME, NARG, ROUND_MODE, INTRINSIC)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case Intrinsic::NAME:                                                        \
    IID = Intrinsic::INTRINSIC;                                                \
    break;
</div>
</dd>
</dl>

<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/fpenv-cpp">FPEnv.cpp</a>.</p>

</div>
</div>

### INSTRUCTION {#acb1562b4fc2af28e0902580ce98800fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTRUCTION(NAME, NARG, ROUND_MODE, INTRINSIC)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case Instruction::NAME:                                                      \
    IID = Intrinsic::INTRINSIC;                                                \
    break;
</div>
</dd>
</dl>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/fpenv-cpp">FPEnv.cpp</a>.</p>

</div>
</div>

### INSTRUCTION {#ac76c80c50f8ec1335d0a5a5ae26ab3da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTRUCTION(NAME, NARG, ROUND_MODE, INTRINSIC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/fpenv-cpp">FPEnv.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
