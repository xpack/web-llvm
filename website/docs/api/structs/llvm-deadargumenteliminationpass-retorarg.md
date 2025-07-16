---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/deadargumenteliminationpass/retorarg
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `RetOrArg` Struct Reference

<p>Struct that represents (part of) either a return value or a function argument. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::DeadArgumentEliminationPass::RetOrArg { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">llvm/Transforms/IPO/DeadArgumentElimination.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc898f4d6a31df60d20c4af66e4f9883">RetOrArg</a> (const Function *F, unsigned Idx, bool IsArg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7534a8f94138b78738c9758b5157be80">operator&lt;</a> (const RetOrArg &amp;O) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make <a href="/web-llvm/docs/api/structs/llvm/deadargumenteliminationpass/retorarg">RetOrArg</a> comparable, so we can put it into a map. <a href="#a7534a8f94138b78738c9758b5157be80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a099414b91a76ae70d3011b6639b141fc">operator==</a> (const RetOrArg &amp;O) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make <a href="/web-llvm/docs/api/structs/llvm/deadargumenteliminationpass/retorarg">RetOrArg</a> comparable, so we can easily iterate the multimap. <a href="#a099414b91a76ae70d3011b6639b141fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5950eb0a10b8b78ba2fa237dca795f0">getDescription</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a163bb8216fa41dd887934a0b14bd6f2b">F</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a910f7a683ddbba1ef6b4dc568488e91c">Idx</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e0078db8ed89a9a43e5b13b58be458a">IsArg</a></td>
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

<p>Struct that represents (part of) either a return value or a function argument.</p>


<p>Used so that arguments and return values can be used interchangeably.</p>


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RetOrArg() {#afc898f4d6a31df60d20c4af66e4f9883}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DeadArgumentEliminationPass::RetOrArg::RetOrArg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, unsigned Idx, bool IsArg)</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>.</p>


<p>References <a href="#a163bb8216fa41dd887934a0b14bd6f2b">F</a>, <a href="#a910f7a683ddbba1ef6b4dc568488e91c">Idx</a> and <a href="#a2e0078db8ed89a9a43e5b13b58be458a">IsArg</a>.</p>


<p>Referenced by <a href="#a7534a8f94138b78738c9758b5157be80">operator&lt;</a> and <a href="#a099414b91a76ae70d3011b6639b141fc">operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator&lt;() {#a7534a8f94138b78738c9758b5157be80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DeadArgumentEliminationPass::RetOrArg::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/deadargumenteliminationpass/retorarg">RetOrArg</a> &amp; O)</td>
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

<p>Make <a href="/web-llvm/docs/api/structs/llvm/deadargumenteliminationpass/retorarg">RetOrArg</a> comparable, so we can put it into a map.</p>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>.</p>


<p>References <a href="#a163bb8216fa41dd887934a0b14bd6f2b">F</a>, <a href="#a910f7a683ddbba1ef6b4dc568488e91c">Idx</a>, <a href="#a2e0078db8ed89a9a43e5b13b58be458a">IsArg</a> and <a href="#afc898f4d6a31df60d20c4af66e4f9883">RetOrArg</a>.</p>

</div>
</div>

### operator==() {#a099414b91a76ae70d3011b6639b141fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DeadArgumentEliminationPass::RetOrArg::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/deadargumenteliminationpass/retorarg">RetOrArg</a> &amp; O)</td>
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

<p>Make <a href="/web-llvm/docs/api/structs/llvm/deadargumenteliminationpass/retorarg">RetOrArg</a> comparable, so we can easily iterate the multimap.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>.</p>


<p>References <a href="#a163bb8216fa41dd887934a0b14bd6f2b">F</a>, <a href="#a910f7a683ddbba1ef6b4dc568488e91c">Idx</a>, <a href="#a2e0078db8ed89a9a43e5b13b58be458a">IsArg</a> and <a href="#afc898f4d6a31df60d20c4af66e4f9883">RetOrArg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getDescription() {#af5950eb0a10b8b78ba2fa237dca795f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DeadArgumentEliminationPass::RetOrArg::getDescription ()</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>.</p>


<p>References <a href="#a163bb8216fa41dd887934a0b14bd6f2b">F</a>, <a href="#a910f7a683ddbba1ef6b4dc568488e91c">Idx</a> and <a href="#a2e0078db8ed89a9a43e5b13b58be458a">IsArg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### F {#a163bb8216fa41dd887934a0b14bd6f2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function* llvm::DeadArgumentEliminationPass::RetOrArg::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>.</p>


<p>Referenced by <a href="#af5950eb0a10b8b78ba2fa237dca795f0">getDescription</a>, <a href="#a7534a8f94138b78738c9758b5157be80">operator&lt;</a>, <a href="#a099414b91a76ae70d3011b6639b141fc">operator==</a> and <a href="#afc898f4d6a31df60d20c4af66e4f9883">RetOrArg</a>.</p>

</div>
</div>

### Idx {#a910f7a683ddbba1ef6b4dc568488e91c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DeadArgumentEliminationPass::RetOrArg::Idx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>.</p>


<p>Referenced by <a href="#af5950eb0a10b8b78ba2fa237dca795f0">getDescription</a>, <a href="#a7534a8f94138b78738c9758b5157be80">operator&lt;</a>, <a href="#a099414b91a76ae70d3011b6639b141fc">operator==</a> and <a href="#afc898f4d6a31df60d20c4af66e4f9883">RetOrArg</a>.</p>

</div>
</div>

### IsArg {#a2e0078db8ed89a9a43e5b13b58be458a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DeadArgumentEliminationPass::RetOrArg::IsArg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a>.</p>


<p>Referenced by <a href="#af5950eb0a10b8b78ba2fa237dca795f0">getDescription</a>, <a href="#a7534a8f94138b78738c9758b5157be80">operator&lt;</a>, <a href="#a099414b91a76ae70d3011b6639b141fc">operator==</a> and <a href="#afc898f4d6a31df60d20c4af66e4f9883">RetOrArg</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/deadargumentelimination-h">DeadArgumentElimination.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
