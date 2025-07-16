---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/parsestatus
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ParseStatus` Class Reference

<p>Ternary parse status returned by various parse* methods. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ParseStatus { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mctargetasmparser-h">llvm/MC/MCParser/MCTargetAsmParser.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">StatusTy { <a href="#a75ac4d5e24dfeaa3277049bf8a189617">...</a> }</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3e47bccce7911654e817c1440fba0f9">ParseStatus</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f5013ca5b55be0d3eda7131d5e7d25d">ParseStatus</a> (StatusTy Status)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0de27281edb302b8d391af090680d289">ParseStatus</a> (bool Error)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a94688377f9aa9ab0461f294cf69156a9">ParseStatus</a> (T)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e9e0ca8400d7f2ddbf51b586704ffda">ParseStatus</a> (OperandMatchResultTy R)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0034ca76d6ee5ed3cf84940d2b5be65a">operator OperandMatchResultTy</a> () const</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60b6e83411b03e0c4dc4858bb5e9f912">isSuccess</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01a3be3f469c6f0a26bf9a5180b7b322">isFailure</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78a275295bb9a176cb9fcfa9bbc43db1">isNoMatch</a> () const</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum llvm::ParseStatus::StatusTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9c46649fc1dc82f3edba922f80b4a99">Status</a></td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr StatusTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66a81b1ff471ed3e871c93599118f34c">Success</a> = StatusTy::Success</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr StatusTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07e0e7c7dba79a89519092de57d17358">Failure</a> = StatusTy::Failure</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr StatusTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a670f6078c68c861b8ecaa1ec082fd736">NoMatch</a> = StatusTy::NoMatch</td>
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

<p>Ternary parse status returned by various parse* methods.</p>

<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mctargetasmparser-h">MCTargetAsmParser.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### StatusTy {#a75ac4d5e24dfeaa3277049bf8a189617}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::ParseStatus::StatusTy </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">Success<a id="a75ac4d5e24dfeaa3277049bf8a189617a505a83f220c02df2f85c3810cd9ceb38"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Failure<a id="a75ac4d5e24dfeaa3277049bf8a189617ae139a585510a502bbf1841cf589f5086"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoMatch<a id="a75ac4d5e24dfeaa3277049bf8a189617ac8b77721c677e0429241a9250972122d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mctargetasmparser-h">MCTargetAsmParser.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ParseStatus() {#ad3e47bccce7911654e817c1440fba0f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ParseStatus::ParseStatus ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mctargetasmparser-h">MCTargetAsmParser.h</a>.</p>


<p>Reference <a href="#a670f6078c68c861b8ecaa1ec082fd736">NoMatch</a>.</p>


<p>Referenced by <a href="#a5e9e0ca8400d7f2ddbf51b586704ffda">ParseStatus</a>.</p>

</div>
</div>

### ParseStatus() {#a0f5013ca5b55be0d3eda7131d5e7d25d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ParseStatus::ParseStatus (StatusTy Status)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mctargetasmparser-h">MCTargetAsmParser.h</a>.</p>

</div>
</div>

### ParseStatus() {#a0de27281edb302b8d391af090680d289}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ParseStatus::ParseStatus (bool Error)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mctargetasmparser-h">MCTargetAsmParser.h</a>.</p>


<p>References <a href="#a07e0e7c7dba79a89519092de57d17358">Failure</a> and <a href="#a66a81b1ff471ed3e871c93599118f34c">Success</a>.</p>

</div>
</div>

### ParseStatus() {#a94688377f9aa9ab0461f294cf69156a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ParseStatus::ParseStatus (T)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mctargetasmparser-h">MCTargetAsmParser.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### ParseStatus() {#a5e9e0ca8400d7f2ddbf51b586704ffda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ParseStatus::ParseStatus (<a href="/web-llvm/docs/api/namespaces/llvm/#a1fcdae651db3104b384cf4188a4f8c30">OperandMatchResultTy</a> R)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mctargetasmparser-h">MCTargetAsmParser.h</a>.</p>


<p>References <a href="#a07e0e7c7dba79a89519092de57d17358">Failure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1fcdae651db3104b384cf4188a4f8c30a41dde5dbf394e872c8b2cb70ea228e55">llvm::MatchOperand_ParseFail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1fcdae651db3104b384cf4188a4f8c30a87aee8d011a4f83d6e37db1cdbcb5a48">llvm::MatchOperand_Success</a>, <a href="#a670f6078c68c861b8ecaa1ec082fd736">NoMatch</a>, <a href="#ad3e47bccce7911654e817c1440fba0f9">ParseStatus</a> and <a href="#a66a81b1ff471ed3e871c93599118f34c">Success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator OperandMatchResultTy() {#a0034ca76d6ee5ed3cf84940d2b5be65a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ParseStatus::operator OperandMatchResultTy ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mctargetasmparser-h">MCTargetAsmParser.h</a>.</p>


<p>References <a href="#a01a3be3f469c6f0a26bf9a5180b7b322">isFailure</a>, <a href="#a60b6e83411b03e0c4dc4858bb5e9f912">isSuccess</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1fcdae651db3104b384cf4188a4f8c30a3c4d26bfcbee461bd1d50de51ade3ac0">llvm::MatchOperand_NoMatch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1fcdae651db3104b384cf4188a4f8c30a41dde5dbf394e872c8b2cb70ea228e55">llvm::MatchOperand_ParseFail</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1fcdae651db3104b384cf4188a4f8c30a87aee8d011a4f83d6e37db1cdbcb5a48">llvm::MatchOperand_Success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isFailure() {#a01a3be3f469c6f0a26bf9a5180b7b322}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ParseStatus::isFailure ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mctargetasmparser-h">MCTargetAsmParser.h</a>.</p>


<p>Referenced by <a href="#a0034ca76d6ee5ed3cf84940d2b5be65a">operator OperandMatchResultTy</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a905978e46c9c9a277645e938f41e1876">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseCPol</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#aae18974f031b21f7dd37b072a1cbe24d">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseFORMAT</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#af09dfe84acccdfc6a55c91388892da8e">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a2f6673e616e48f8b6505d19ef64eddab">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a034b546ea133319ab2244f9bfa28ecae">anonymous{AsmParser.cpp}::AsmParser::parseStatement</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#aedd4ddd3d36c07298e0d1c8ea2903593">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseSVEDataVector</a>.</p>

</div>
</div>

### isNoMatch() {#a78a275295bb9a176cb9fcfa9bbc43db1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ParseStatus::isNoMatch ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mctargetasmparser-h">MCTargetAsmParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a3ad635dcc304d17a852fa28adac99bb9">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseBLGP</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a905978e46c9c9a277645e938f41e1876">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseCPol</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#af9a4f566ce16209db2301b23edfe1573">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseFlatOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a16bbeaa5435876a2a30093aa9f7adc09">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseHwreg</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a2f6673e616e48f8b6505d19ef64eddab">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#aa73d0a8ecc958df50e46e59e1ad97478">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseR128A16</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a60728802d4e08feb0abc5cc75c3eefc9">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseRegOrImm</a>.</p>

</div>
</div>

### isSuccess() {#a60b6e83411b03e0c4dc4858bb5e9f912}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ParseStatus::isSuccess ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mctargetasmparser-h">MCTargetAsmParser.h</a>.</p>


<p>Referenced by <a href="#a0034ca76d6ee5ed3cf84940d2b5be65a">operator OperandMatchResultTy</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a905978e46c9c9a277645e938f41e1876">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseCPol</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#aae18974f031b21f7dd37b072a1cbe24d">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseFORMAT</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a16bbeaa5435876a2a30093aa9f7adc09">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseHwreg</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a62ccca1cd262d040e8aee057ab0d22d5">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#af09dfe84acccdfc6a55c91388892da8e">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmparser-cpp-/m68kasmparser/#a6ed1f4d7f56e05cf30cc258a8f248bf7">anonymous{M68kAsmParser.cpp}::M68kAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a4bbb3e5e0e2e2c935c2a911665fff611">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseIntWithPrefix</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a2f6673e616e48f8b6505d19ef64eddab">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a0970907190b315d94fa0f5bd315df87f">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::parseRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a74b6654d186e55d185e29c67ebd46cc6">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseRegOrImmWithFPInputMods</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a2d208597e9458f13c660462e0d3a4a6a">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseRegOrImmWithIntInputMods</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a1a55d776c65cd09db2546fb584a2de47">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseScope</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a034b546ea133319ab2244f9bfa28ecae">anonymous{AsmParser.cpp}::AsmParser::parseStatement</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a11669d3b022f7e99114faaf694659b89">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseStringOrIntWithPrefix</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a3a4cad862e9d4dda82fe89b5a2557e97">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseTH</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a72482e46711748fee7ce49e1d66002de">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseGPROperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#aedd4ddd3d36c07298e0d1c8ea2903593">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseSVEDataVector</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#aef98635d49b1c38ba8b291b28df6a62d">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseSVEPredicateVector</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Status {#ab9c46649fc1dc82f3edba922f80b4a99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ParseStatus::StatusTy llvm::ParseStatus::Status</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mctargetasmparser-h">MCTargetAsmParser.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### Failure {#a07e0e7c7dba79a89519092de57d17358}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StatusTy llvm::ParseStatus::Failure = StatusTy::Failure</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mctargetasmparser-h">MCTargetAsmParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#aa54525f0109858da308fa32559539255">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDepCtr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a157290e9f9aa7ff61c53d131b090e50a">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDfmtNfmt</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a4e07e3e64caa97fc5dbc73fe0b20d311">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a0478394229fb5470e1489709c8711643">llvm::MCTargetAsmParser::parseDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a59d9c798683c4a134a731c43840d62aa">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDPP8</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#af1e3005e43d45d207eb661fa024b1753">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDPPCtrl</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ad03402b69301c9df929a7ca211df947c">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseGPRIdxMode</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a16bbeaa5435876a2a30093aa9f7adc09">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseHwreg</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a62ccca1cd262d040e8aee057ab0d22d5">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ae93e542fa2b3eac118a87c97a47bc681">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseNumericFormat</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a2f6673e616e48f8b6505d19ef64eddab">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ac9d07a4881948a410fcba201eeb36480">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseOperandArrayWithPrefix</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ab2ca31c142db4eaa8c629f36d61339bf">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a74b6654d186e55d185e29c67ebd46cc6">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseRegOrImmWithFPInputMods</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a2d208597e9458f13c660462e0d3a4a6a">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseRegOrImmWithIntInputMods</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a493337bf1e3308881e03af9142a5bb5a">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSDelayALU</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a7e026648ec951bc9ce02a0e99e31f583">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSendMsg</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcasmparser/#a2a338087cbd108168ba920ad7906f6b8">anonymous{SparcAsmParser.cpp}::SparcAsmParser::parseShiftAmtImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a082f5bbf706dd5cd5bcb35d7bdf5564f">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSOPPBrTarget</a>, <a href="#a0de27281edb302b8d391af090680d289">ParseStatus</a>, <a href="#a5e9e0ca8400d7f2ddbf51b586704ffda">ParseStatus</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a066421d8538981830a93a7598a571e8f">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseStringOrIntWithPrefix</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a8dbdde33e6acd3e814ee9db9b8cfef68">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseStringWithPrefix</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ac3b25b92e123263ee61ca38bdee04828">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSWaitCnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a45d3320cf47a5c534c3e884ea6501728">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSwizzle</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ac75ca253bd4248bf1ab2b4d4695f0500">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSymbolicOrNumericFormat</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ad0ddd35516c856b2c41317d0c1febdea">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSymbolicSplitFormat</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcasmparser/#abdef83570b9c07195a0570f8744b2fc0">anonymous{SparcAsmParser.cpp}::SparcAsmParser::parseTailRelocSym</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a1125b7de6fb9f81f501a1988550e60d9">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseUfmt</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#aad55de4993c720c50d992a7cbda3d8d3">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseVReg32OrOff</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a3836dbcbb0e7b8207e5b1f40a85269af">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParsePrefetch</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a5e29118c0f500ee77e2601b120205f54">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::tryParseRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a13dd89de2b4ed943fa814913ba93b327">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::tryParseRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#a1a5f6fe20b3365323eedea54e79aa8c0">anonymous{X86AsmParser.cpp}::X86AsmParser::tryParseRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#aedd4ddd3d36c07298e0d1c8ea2903593">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseSVEDataVector</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#ac039137a2de44626abac897fe2382ef7">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseVectorList</a>.</p>

</div>
</div>

### NoMatch {#a670f6078c68c861b8ecaa1ec082fd736}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StatusTy llvm::ParseStatus::NoMatch = StatusTy::NoMatch</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mctargetasmparser-h">MCTargetAsmParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/asmparser/veasmparser-cpp/#a12e31c0c30a774b7e1a19becc5fa1890">MatchRegisterAltName</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a905978e46c9c9a277645e938f41e1876">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseCPol</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a157290e9f9aa7ff61c53d131b090e50a">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDfmtNfmt</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a4c31665501f9b711e245f1b4e201683b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDim</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a3390881f203f23dca9f40c151f89d581">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a4e07e3e64caa97fc5dbc73fe0b20d311">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a0478394229fb5470e1489709c8711643">llvm::MCTargetAsmParser::parseDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a59d9c798683c4a134a731c43840d62aa">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDPP8</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#af1e3005e43d45d207eb661fa024b1753">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDPPCtrl</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a26a8456ca91f0f85ed2f854837b0dc29">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseExpTgt</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a62ccca1cd262d040e8aee057ab0d22d5">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a5c3abd5a0df4ec19738884622846a92b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseInterpAttr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#abc5a32fe7c02fdcfc1484e926e376ce0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseInterpSlot</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ab2ff8b8fa2100a684cea688b74d329ab">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseNamedBit</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a9d5e44bae726c6d5f1d1af4aba4a48ff">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseOModSI</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ac9d07a4881948a410fcba201eeb36480">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseOperandArrayWithPrefix</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ab2ca31c142db4eaa8c629f36d61339bf">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a60728802d4e08feb0abc5cc75c3eefc9">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseRegOrImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcasmparser/#a2a338087cbd108168ba920ad7906f6b8">anonymous{SparcAsmParser.cpp}::SparcAsmParser::parseShiftAmtImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a082f5bbf706dd5cd5bcb35d7bdf5564f">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSOPPBrTarget</a>, <a href="#ad3e47bccce7911654e817c1440fba0f9">ParseStatus</a>, <a href="#a5e9e0ca8400d7f2ddbf51b586704ffda">ParseStatus</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a066421d8538981830a93a7598a571e8f">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseStringOrIntWithPrefix</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a8dbdde33e6acd3e814ee9db9b8cfef68">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseStringWithPrefix</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a45d3320cf47a5c534c3e884ea6501728">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSwizzle</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ac75ca253bd4248bf1ab2b4d4695f0500">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSymbolicOrNumericFormat</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a9cba0b00a0bcffcb413914db33553071">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSymbolicUnifiedFormat</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcasmparser/#abdef83570b9c07195a0570f8744b2fc0">anonymous{SparcAsmParser.cpp}::SparcAsmParser::parseTailRelocSym</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a40cae821d596ce5a10da36c3d1836dac">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseTokenOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a1125b7de6fb9f81f501a1988550e60d9">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseUfmt</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a4c71cb47a3f1bcc8147c44cc1395ed63">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseVOPD</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#aad55de4993c720c50d992a7cbda3d8d3">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseVReg32OrOff</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a246c8dfd4ca957b7da4d52cb7805650c">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseAdjImm0_63</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a0ff7af77f414b9796ed948a2723f6199">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseFPImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a5e29118c0f500ee77e2601b120205f54">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::tryParseRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#a0ba61fbe8e007cee20b7d18386276617">anonymous{ARMAsmParser.cpp}::ARMAsmParser::tryParseRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a13dd89de2b4ed943fa814913ba93b327">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::tryParseRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#a1a5f6fe20b3365323eedea54e79aa8c0">anonymous{X86AsmParser.cpp}::X86AsmParser::tryParseRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#aedd4ddd3d36c07298e0d1c8ea2903593">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseSVEDataVector</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#aef98635d49b1c38ba8b291b28df6a62d">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseSVEPredicateVector</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#ac039137a2de44626abac897fe2382ef7">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseVectorList</a>.</p>

</div>
</div>

### Success {#a66a81b1ff471ed3e871c93599118f34c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StatusTy llvm::ParseStatus::Success = StatusTy::Success</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mctargetasmparser-h">MCTargetAsmParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/asmparser/veasmparser-cpp/#a12e31c0c30a774b7e1a19becc5fa1890">MatchRegisterAltName</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a905978e46c9c9a277645e938f41e1876">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseCPol</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#aa54525f0109858da308fa32559539255">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDepCtr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a157290e9f9aa7ff61c53d131b090e50a">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDfmtNfmt</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a4c31665501f9b711e245f1b4e201683b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDim</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a0478394229fb5470e1489709c8711643">llvm::MCTargetAsmParser::parseDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a59d9c798683c4a134a731c43840d62aa">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDPP8</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#af1e3005e43d45d207eb661fa024b1753">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDPPCtrl</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a0b822486044ee842c7c868f39ff4830b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseEndpgm</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a26a8456ca91f0f85ed2f854837b0dc29">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseExpTgt</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#aae18974f031b21f7dd37b072a1cbe24d">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseFORMAT</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ad03402b69301c9df929a7ca211df947c">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseGPRIdxMode</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a16bbeaa5435876a2a30093aa9f7adc09">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseHwreg</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a62ccca1cd262d040e8aee057ab0d22d5">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a5c3abd5a0df4ec19738884622846a92b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseInterpAttr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#abc5a32fe7c02fdcfc1484e926e376ce0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseInterpSlot</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a4bbb3e5e0e2e2c935c2a911665fff611">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseIntWithPrefix</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ab2ff8b8fa2100a684cea688b74d329ab">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseNamedBit</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ae93e542fa2b3eac118a87c97a47bc681">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseNumericFormat</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a2f6673e616e48f8b6505d19ef64eddab">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ac9d07a4881948a410fcba201eeb36480">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseOperandArrayWithPrefix</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ab2ca31c142db4eaa8c629f36d61339bf">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a74b6654d186e55d185e29c67ebd46cc6">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseRegOrImmWithFPInputMods</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a2d208597e9458f13c660462e0d3a4a6a">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseRegOrImmWithIntInputMods</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a493337bf1e3308881e03af9142a5bb5a">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSDelayALU</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a7e026648ec951bc9ce02a0e99e31f583">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSendMsg</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcasmparser/#a2a338087cbd108168ba920ad7906f6b8">anonymous{SparcAsmParser.cpp}::SparcAsmParser::parseShiftAmtImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a082f5bbf706dd5cd5bcb35d7bdf5564f">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSOPPBrTarget</a>, <a href="#a0de27281edb302b8d391af090680d289">ParseStatus</a>, <a href="#a5e9e0ca8400d7f2ddbf51b586704ffda">ParseStatus</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a066421d8538981830a93a7598a571e8f">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseStringOrIntWithPrefix</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a8dbdde33e6acd3e814ee9db9b8cfef68">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseStringWithPrefix</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ac3b25b92e123263ee61ca38bdee04828">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSWaitCnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a45d3320cf47a5c534c3e884ea6501728">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSwizzle</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ac75ca253bd4248bf1ab2b4d4695f0500">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSymbolicOrNumericFormat</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ad0ddd35516c856b2c41317d0c1febdea">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSymbolicSplitFormat</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a9cba0b00a0bcffcb413914db33553071">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSymbolicUnifiedFormat</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcasmparser/#abdef83570b9c07195a0570f8744b2fc0">anonymous{SparcAsmParser.cpp}::SparcAsmParser::parseTailRelocSym</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a3a4cad862e9d4dda82fe89b5a2557e97">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseTH</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a40cae821d596ce5a10da36c3d1836dac">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseTokenOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a1125b7de6fb9f81f501a1988550e60d9">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseUfmt</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a4c71cb47a3f1bcc8147c44cc1395ed63">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseVOPD</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#aad55de4993c720c50d992a7cbda3d8d3">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseVReg32OrOff</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a246c8dfd4ca957b7da4d52cb7805650c">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseAdjImm0_63</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a0ff7af77f414b9796ed948a2723f6199">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseFPImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a72482e46711748fee7ce49e1d66002de">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseGPROperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a971176e60129a0824a8c1e2a193e6b62">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::tryParseIndexKey</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a3836dbcbb0e7b8207e5b1f40a85269af">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParsePrefetch</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a5e29118c0f500ee77e2601b120205f54">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::tryParseRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#a0ba61fbe8e007cee20b7d18386276617">anonymous{ARMAsmParser.cpp}::ARMAsmParser::tryParseRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a13dd89de2b4ed943fa814913ba93b327">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::tryParseRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#a1a5f6fe20b3365323eedea54e79aa8c0">anonymous{X86AsmParser.cpp}::X86AsmParser::tryParseRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#aedd4ddd3d36c07298e0d1c8ea2903593">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseSVEDataVector</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#aef98635d49b1c38ba8b291b28df6a62d">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseSVEPredicateVector</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#ac039137a2de44626abac897fe2382ef7">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseVectorList</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcparser/mctargetasmparser-h">MCTargetAsmParser.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
