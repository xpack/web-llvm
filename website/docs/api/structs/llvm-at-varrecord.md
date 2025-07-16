---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/at/varrecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `VarRecord` Struct Reference

<p>Helper struct for trackAssignments, below. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::at::VarRecord { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">llvm/IR/DebugInfo.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e1aaf97264e1787bbe5c2ce2ed2cbb4">operator&lt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98223a6fa89ab8b6e6c5cbb502fbd3e1">operator==</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6df61be40030f54eda63e94d716b72bf">VarRecord</a> (DbgVariableIntrinsic *DVI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a070e5425cba551f0b7f65582a4b5b328">VarRecord</a> (DbgVariableRecord *DVR)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6a8092dbee5ce434dc52d2674f0ce66">VarRecord</a> (DILocalVariable *Var, DILocation *DL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa37ef81e1522bc8d78d702c59ad62b1">Var</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef07c6fc4c9df3199800ba5decf9c8e0">DL</a></td>
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

<p>Helper struct for trackAssignments, below.</p>


<p>We don't use the similar <a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a> class because trackAssignments doesn't (yet?) understand partial variables (fragment info) as input and want to make that clear and explicit using types. In addition, eventually we will want to understand expressions that modify the base address too, which a <a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a> doesn't capture.</p>


<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>


<div class="doxySectionDef">

## Friends

### operator&lt; {#a9e1aaf97264e1787bbe5c2ce2ed2cbb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/at/varrecord">VarRecord</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/at/varrecord">VarRecord</a> &amp; RHS</td>
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


<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a6df61be40030f54eda63e94d716b72bf">VarRecord</a>.</p>

</div>
</div>

### operator== {#a98223a6fa89ab8b6e6c5cbb502fbd3e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/at/varrecord">VarRecord</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/at/varrecord">VarRecord</a> &amp; RHS</td>
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


<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a6df61be40030f54eda63e94d716b72bf">VarRecord</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### VarRecord() {#a6df61be40030f54eda63e94d716b72bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::at::VarRecord::VarRecord (<a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic">DbgVariableIntrinsic</a> * DVI)</td>
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



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>


<p>References <a href="#aef07c6fc4c9df3199800ba5decf9c8e0">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87ef919ea907189c22b74f604a645b40">llvm::getDebugValueLoc</a> and <a href="#afa37ef81e1522bc8d78d702c59ad62b1">Var</a>.</p>


<p>Referenced by <a href="#a9e1aaf97264e1787bbe5c2ce2ed2cbb4">operator&lt;</a> and <a href="#a98223a6fa89ab8b6e6c5cbb502fbd3e1">operator==</a>.</p>

</div>
</div>

### VarRecord() {#a070e5425cba551f0b7f65582a4b5b328}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::at::VarRecord::VarRecord (<a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> * DVR)</td>
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



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>


<p>References <a href="#aef07c6fc4c9df3199800ba5decf9c8e0">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87ef919ea907189c22b74f604a645b40">llvm::getDebugValueLoc</a> and <a href="#afa37ef81e1522bc8d78d702c59ad62b1">Var</a>.</p>

</div>
</div>

### VarRecord() {#af6a8092dbee5ce434dc52d2674f0ce66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::at::VarRecord::VarRecord (<a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * Var, <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DL)</td>
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



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>


<p>References <a href="#aef07c6fc4c9df3199800ba5decf9c8e0">DL</a> and <a href="#afa37ef81e1522bc8d78d702c59ad62b1">Var</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DL {#aef07c6fc4c9df3199800ba5decf9c8e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DILocation* llvm::at::VarRecord::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#a9b051a25ba281897b4dc62df58312b7e">emitDbgAssign</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-339e92432108a12c437bc5c3804a88b0/#ad5f791c09e8ce96486adbc75adc54966">llvm::DenseMapInfo&lt; at::VarRecord &gt;::getHashValue</a>, <a href="#a6df61be40030f54eda63e94d716b72bf">VarRecord</a>, <a href="#a070e5425cba551f0b7f65582a4b5b328">VarRecord</a> and <a href="#af6a8092dbee5ce434dc52d2674f0ce66">VarRecord</a>.</p>

</div>
</div>

### Var {#afa37ef81e1522bc8d78d702c59ad62b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DILocalVariable* llvm::at::VarRecord::Var</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#a9b051a25ba281897b4dc62df58312b7e">emitDbgAssign</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-339e92432108a12c437bc5c3804a88b0/#ad5f791c09e8ce96486adbc75adc54966">llvm::DenseMapInfo&lt; at::VarRecord &gt;::getHashValue</a>, <a href="#a6df61be40030f54eda63e94d716b72bf">VarRecord</a>, <a href="#a070e5425cba551f0b7f65582a4b5b328">VarRecord</a> and <a href="#af6a8092dbee5ce434dc52d2674f0ce66">VarRecord</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
