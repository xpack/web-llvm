---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/executorprocesscontrol/runastask
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RunAsTask` Class

<p>Constructs an <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/incomingwfrhandler">IncomingWFRHandler</a> from a function object by creating a new function object that dispatches the original using a <a href="/web-llvm/docs/api/classes/llvm/orc/taskdispatcher">TaskDispatcher</a>, wrapping the original as a <a href="/web-llvm/docs/api/classes/llvm/orc/genericnamedtask">GenericNamedTask</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::ExecutorProcessControl::RunAsTask { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">llvm/ExecutionEngine/Orc/ExecutorProcessControl.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2eb74640ad52a1cfcab99fff9687b9f">RunAsTask</a> (TaskDispatcher &amp;D)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FnT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/incomingwfrhandler">IncomingWFRHandler</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5e3d1d6e5a2075158f91a369094b0322">operator()</a> (FnT &amp;&amp;Fn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/taskdispatcher">TaskDispatcher</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e63a531765159159d5953c53977f30b">D</a></td>
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

<p>Constructs an <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol/incomingwfrhandler">IncomingWFRHandler</a> from a function object by creating a new function object that dispatches the original using a <a href="/web-llvm/docs/api/classes/llvm/orc/taskdispatcher">TaskDispatcher</a>, wrapping the original as a <a href="/web-llvm/docs/api/classes/llvm/orc/genericnamedtask">GenericNamedTask</a>.</p>


<p>This is the default approach for running WFR handlers.</p>


<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RunAsTask() {#ad2eb74640ad52a1cfcab99fff9687b9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::ExecutorProcessControl::RunAsTask::RunAsTask (<a href="/web-llvm/docs/api/classes/llvm/orc/taskdispatcher">TaskDispatcher</a> &amp; D)</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator()() {#a5e3d1d6e5a2075158f91a369094b0322}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FnT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IncomingWFRHandler llvm::orc::ExecutorProcessControl::RunAsTask::operator() (FnT &amp;&amp; Fn)</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a4a64da92b7660d6aceacef12dd6dd78e">llvm::orc::makeGenericNamedTask</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### D {#a2e63a531765159159d5953c53977f30b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TaskDispatcher&amp; llvm::orc::ExecutorProcessControl::RunAsTask::D</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/executorprocesscontrol-h">ExecutorProcessControl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
