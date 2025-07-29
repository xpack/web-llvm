---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/machinetracemetrics/instrcycles
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `InstrCycles` Struct

<p><a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/instrcycles">InstrCycles</a> represents the cycle height and depth of an instruction in a trace. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::MachineTraceMetrics::InstrCycles { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">llvm/CodeGen/MachineTraceMetrics.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecec30fb7bb36797ee2c01f1c977a4b9">Depth</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Earliest issue cycle as determined by data dependencies and instruction latencies from the beginning of the trace. <a href="#aecec30fb7bb36797ee2c01f1c977a4b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71f86c7e329271a09b14d04a1153cb46">Height</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Minimum number of cycles from this instruction is issued to the of the trace, as determined by data dependencies and instruction latencies. <a href="#a71f86c7e329271a09b14d04a1153cb46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/instrcycles">InstrCycles</a> represents the cycle height and depth of an instruction in a trace.</p>

<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Depth {#aecec30fb7bb36797ee2c01f1c977a4b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineTraceMetrics::InstrCycles::Depth</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Earliest issue cycle as determined by data dependencies and instruction latencies from the beginning of the trace.</p>


<p>Data dependencies from before the trace are not included.</p>


<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/trace/#a4c28dd8965fc19e15f0ed6c7be60acec">llvm::MachineTraceMetrics::Trace::getInstrSlack</a> and <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#a3118fc82938c92f70453a0ccf9e7fc70">llvm::MachineTraceMetrics::Ensemble::updateDepth</a>.</p>

</div>
</div>

### Height {#a71f86c7e329271a09b14d04a1153cb46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineTraceMetrics::InstrCycles::Height</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Minimum number of cycles from this instruction is issued to the of the trace, as determined by data dependencies and instruction latencies.</p>

<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/trace/#a4c28dd8965fc19e15f0ed6c7be60acec">llvm::MachineTraceMetrics::Trace::getInstrSlack</a> and <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#a3118fc82938c92f70453a0ccf9e7fc70">llvm::MachineTraceMetrics::Ensemble::updateDepth</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
