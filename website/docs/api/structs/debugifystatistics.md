---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/debugifystatistics
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DebugifyStatistics` Struct Reference

<p>Track how much <span class="doxyComputerOutput">debugify</span> information (in the <span class="doxyComputerOutput">synthetic</span> mode only) has been lost. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct DebugifyStatistics { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h">llvm/Transforms/Utils/Debugify.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">float</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5cc6af53746ccf1571e63c9f13d5d67">getMissingValueRatio</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the ratio of missing/expected dbg.values. <a href="#ae5cc6af53746ccf1571e63c9f13d5d67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">float</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61603faaba6b4b074618fca8aebeed14">getEmptyLocationRatio</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the ratio of missing/expected instructions with locations. <a href="#a61603faaba6b4b074618fca8aebeed14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac033a5fcd15917385cb0fe2945a4d03d">NumDbgValuesMissing</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of missing dbg.values. <a href="#ac033a5fcd15917385cb0fe2945a4d03d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0642c2e50fac90de71f742c671aa5798">NumDbgValuesExpected</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of dbg.values expected. <a href="#a0642c2e50fac90de71f742c671aa5798">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc37eb02f46146e78d47b9a5d744b165">NumDbgLocsMissing</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of instructions with empty debug locations. <a href="#abc37eb02f46146e78d47b9a5d744b165">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a131b4cfba175e9ced29c4fc978700d6c">NumDbgLocsExpected</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of instructions expected to have debug locations. <a href="#a131b4cfba175e9ced29c4fc978700d6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Track how much <span class="doxyComputerOutput">debugify</span> information (in the <span class="doxyComputerOutput">synthetic</span> mode only) has been lost.</p>

<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h">Debugify.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getEmptyLocationRatio() {#a61603faaba6b4b074618fca8aebeed14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">float DebugifyStatistics::getEmptyLocationRatio ()</td>
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

<p>Get the ratio of missing/expected instructions with locations.</p>

<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h">Debugify.h</a>.</p>


<p>References <a href="#a131b4cfba175e9ced29c4fc978700d6c">NumDbgLocsExpected</a> and <a href="#abc37eb02f46146e78d47b9a5d744b165">NumDbgLocsMissing</a>.</p>

</div>
</div>

### getMissingValueRatio() {#ae5cc6af53746ccf1571e63c9f13d5d67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">float DebugifyStatistics::getMissingValueRatio ()</td>
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

<p>Get the ratio of missing/expected dbg.values.</p>

<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h">Debugify.h</a>.</p>


<p>References <a href="#a131b4cfba175e9ced29c4fc978700d6c">NumDbgLocsExpected</a> and <a href="#ac033a5fcd15917385cb0fe2945a4d03d">NumDbgValuesMissing</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### NumDbgLocsExpected {#a131b4cfba175e9ced29c4fc978700d6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DebugifyStatistics::NumDbgLocsExpected = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of instructions expected to have debug locations.</p>

<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h">Debugify.h</a>.</p>


<p>Referenced by <a href="#a61603faaba6b4b074618fca8aebeed14">getEmptyLocationRatio</a> and <a href="#ae5cc6af53746ccf1571e63c9f13d5d67">getMissingValueRatio</a>.</p>

</div>
</div>

### NumDbgLocsMissing {#abc37eb02f46146e78d47b9a5d744b165}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DebugifyStatistics::NumDbgLocsMissing = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of instructions with empty debug locations.</p>

<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h">Debugify.h</a>.</p>


<p>Referenced by <a href="#a61603faaba6b4b074618fca8aebeed14">getEmptyLocationRatio</a>.</p>

</div>
</div>

### NumDbgValuesExpected {#a0642c2e50fac90de71f742c671aa5798}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DebugifyStatistics::NumDbgValuesExpected = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of dbg.values expected.</p>

<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h">Debugify.h</a>.</p>

</div>
</div>

### NumDbgValuesMissing {#ac033a5fcd15917385cb0fe2945a4d03d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DebugifyStatistics::NumDbgValuesMissing = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of missing dbg.values.</p>

<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h">Debugify.h</a>.</p>


<p>Referenced by <a href="#ae5cc6af53746ccf1571e63c9f13d5d67">getMissingValueRatio</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h">Debugify.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
