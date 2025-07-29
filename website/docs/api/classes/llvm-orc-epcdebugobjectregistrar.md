---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/epcdebugobjectregistrar
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `EPCDebugObjectRegistrar` Class

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> to register debug objects locally or in a remote executor process. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::EPCDebugObjectRegistrar { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcdebugobjectregistrar-h">llvm/ExecutionEngine/Orc/EPCDebugObjectRegistrar.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/debugobjectregistrar">DebugObjectRegistrar</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract interface for registering debug objects in the executor process. <a href="/web-llvm/docs/api/classes/llvm/orc/debugobjectregistrar/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78939a94ba5bb5f99a6ef422298cbb82">EPCDebugObjectRegistrar</a> (ExecutionSession &amp;ES, ExecutorAddr RegisterFn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8faf2a000ebf15bd95b35631ee1dcf7a">registerDebugObject</a> (ExecutorAddrRange TargetMem, bool AutoRegisterCode) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38309053f2caa480d5f63970c2e9c441">ES</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a93279e341d5a03bf4e82735b1896c5">RegisterFn</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> to register debug objects locally or in a remote executor process.</p>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcdebugobjectregistrar-h">EPCDebugObjectRegistrar.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### EPCDebugObjectRegistrar() {#a78939a94ba5bb5f99a6ef422298cbb82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::EPCDebugObjectRegistrar::EPCDebugObjectRegistrar (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> RegisterFn)</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcdebugobjectregistrar-h">EPCDebugObjectRegistrar.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### registerDebugObject() {#a8faf2a000ebf15bd95b35631ee1dcf7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::EPCDebugObjectRegistrar::registerDebugObject (<a href="/web-llvm/docs/api/structs/llvm/orc/executoraddrrange">ExecutorAddrRange</a> TargetMem, bool AutoRegisterCode)</td>
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



<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcdebugobjectregistrar-h">EPCDebugObjectRegistrar.h</a>, definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcdebugobjectregistrar-cpp">EPCDebugObjectRegistrar.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ES {#a38309053f2caa480d5f63970c2e9c441}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionSession&amp; llvm::orc::EPCDebugObjectRegistrar::ES</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcdebugobjectregistrar-h">EPCDebugObjectRegistrar.h</a>.</p>

</div>
</div>

### RegisterFn {#a4a93279e341d5a03bf4e82735b1896c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorAddr llvm::orc::EPCDebugObjectRegistrar::RegisterFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcdebugobjectregistrar-h">EPCDebugObjectRegistrar.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcdebugobjectregistrar-h">EPCDebugObjectRegistrar.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcdebugobjectregistrar-cpp">EPCDebugObjectRegistrar.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
