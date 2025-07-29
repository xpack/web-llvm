---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/droppedvariablestats/debugvariables
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `DebugVariables` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::DroppedVariableStats::DebugVariables { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestats-h">llvm/Passes/DroppedVariableStats.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a07ea053ea2cdbee8e68ebd607c26dc8a">VarID</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0035704c71ffaf5c1e72109a3209140">DebugVariablesBefore</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a> of VarIDs before an optimization pass has run. <a href="#ae0035704c71ffaf5c1e72109a3209140">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a07ea053ea2cdbee8e68ebd607c26dc8a">VarID</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e4d16731206131193654cbea6408074">DebugVariablesAfter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a> of VarIDs after an optimization pass has run. <a href="#a5e4d16731206131193654cbea6408074">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestats-h">DroppedVariableStats.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### DebugVariablesAfter {#a5e4d16731206131193654cbea6408074}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;VarID&gt; llvm::DroppedVariableStats::DebugVariables::DebugVariablesAfter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a> of VarIDs after an optimization pass has run.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestats-h">DroppedVariableStats.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/droppedvariablestats/#a039613c35cae74dbc1b9f2bcdc793f9e">llvm::DroppedVariableStats::calculateDroppedStatsAndPrint</a> and <a href="/web-llvm/docs/api/classes/llvm/droppedvariablestats/#a848e174c81c6209939940cb31f1353cf">llvm::DroppedVariableStats::run</a>.</p>

</div>
</div>

### DebugVariablesBefore {#ae0035704c71ffaf5c1e72109a3209140}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;VarID&gt; llvm::DroppedVariableStats::DebugVariables::DebugVariablesBefore</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a> of VarIDs before an optimization pass has run.</p>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestats-h">DroppedVariableStats.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/droppedvariablestats/#a039613c35cae74dbc1b9f2bcdc793f9e">llvm::DroppedVariableStats::calculateDroppedStatsAndPrint</a> and <a href="/web-llvm/docs/api/classes/llvm/droppedvariablestats/#a848e174c81c6209939940cb31f1353cf">llvm::DroppedVariableStats::run</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/droppedvariablestats-h">DroppedVariableStats.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
