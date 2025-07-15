---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/targetschedmodel
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TargetSchedModel` Class Reference

<p>Provide an instruction scheduling machine model to CodeGen passes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::TargetSchedModel { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">llvm/CodeGen/TargetSchedule.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b653a507e8307775b33e01655d3b8d8">ProcResIter</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcwriteprocresentry">MCWriteProcResEntry</a> *</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93036cf35721ff24a7b09b33f5b368de">TargetSchedModel</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab357b39c47df52a19882a831feda1b6f">init</a> (const TargetSubtargetInfo *TSInfo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the machine model for instruction scheduling. <a href="#ab357b39c47df52a19882a831feda1b6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad3a46af0e50906ff7193aa923b80c65">resolveSchedClass</a> (const MachineInstr *MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> for this instruction. <a href="#aad3a46af0e50906ff7193aa923b80c65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af25644330a6584380b762e4c65482236">getSubtargetInfo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> getter. <a href="#af25644330a6584380b762e4c65482236">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bc8094c82bd7861466b876796ce3a56">getInstrInfo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> getter. <a href="#a1bc8094c82bd7861466b876796ce3a56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a572a0c9d17306d9414106ad1cf4c8052">hasInstrSchedModel</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this machine model includes an instruction-level scheduling model. <a href="#a572a0c9d17306d9414106ad1cf4c8052">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel">MCSchedModel</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11045ef5588d8e92398df194fbb667da">getMCSchedModel</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbb7dc7a2944d22184b4b57a56a167d6">hasInstrItineraries</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this machine model includes cycle-to-cycle itinerary data. <a href="#afbb7dc7a2944d22184b4b57a56a167d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1cd45c8a7d602373b7da7b5e00527d1">getInstrItineraries</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac870e1850c5ff410c0dea3600da980c2">hasInstrSchedModelOrItineraries</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this machine model includes an instruction-level scheduling model or cycle-to-cycle itinerary data. <a href="#ac870e1850c5ff410c0dea3600da980c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af463f6196bddedc736d9599780cfcc70">enableIntervals</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af18042a0439c06f5e5d0ccf53e8b312f">getProcessorID</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identify the processor corresponding to the current subtarget. <a href="#af18042a0439c06f5e5d0ccf53e8b312f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fdb857df4be03c47fa40a69110b84a8">getIssueWidth</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maximum number of micro-ops that may be scheduled per cycle. <a href="#a2fdb857df4be03c47fa40a69110b84a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a731c9c6fb702cf7ea6ae592e2d30126b">mustBeginGroup</a> (const MachineInstr *MI, const MCSchedClassDesc *SC=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if new group must begin. <a href="#a731c9c6fb702cf7ea6ae592e2d30126b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1de64b19d5863e1dbbdd3c0ae81ecdb3">mustEndGroup</a> (const MachineInstr *MI, const MCSchedClassDesc *SC=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if current group must end. <a href="#a1de64b19d5863e1dbbdd3c0ae81ecdb3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc6870d8a702ca4f480785afd7a1eba7">getNumMicroOps</a> (const MachineInstr *MI, const MCSchedClassDesc *SC=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of issue slots required for this MI. <a href="#adc6870d8a702ca4f480785afd7a1eba7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefe560ffcce905bc34e2d46becb54e84">getNumProcResourceKinds</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of kinds of resources for this target. <a href="#aefe560ffcce905bc34e2d46becb54e84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcprocresourcedesc">MCProcResourceDesc</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea6b86c09906bafae5cdf3393ba05f9a">getProcResource</a> (unsigned PIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a processor resource by <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for convenience. <a href="#aea6b86c09906bafae5cdf3393ba05f9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c4f7c8efe6089fc458df3df0acbd9be">getResourceName</a> (unsigned PIdx) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7b653a507e8307775b33e01655d3b8d8">ProcResIter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7c94f0b04c1a466ee77ca749cd8dc50">getWriteProcResBegin</a> (const MCSchedClassDesc *SC) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7b653a507e8307775b33e01655d3b8d8">ProcResIter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e53e3e37d8a810d38ffb83268103b23">getWriteProcResEnd</a> (const MCSchedClassDesc *SC) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c30a0cd9c2311a92add146b8def5eea">getResourceFactor</a> (unsigned ResIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Multiply the number of units consumed for a resource by this factor to normalize it relative to other resources. <a href="#a9c30a0cd9c2311a92add146b8def5eea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3803fd752ed113c37d71580a50888f26">getMicroOpFactor</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Multiply number of micro-ops by this factor to normalize it relative to other resources. <a href="#a3803fd752ed113c37d71580a50888f26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d3d8b3123f4f5060b648a5e15961630">getLatencyFactor</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Multiply cycle count by this factor to normalize it relative to other resources. <a href="#a7d3d8b3123f4f5060b648a5e15961630">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace32bee19ef48cedd4a647706f35b609">getMicroOpBufferSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of micro-ops that may be buffered for OOO execution. <a href="#ace32bee19ef48cedd4a647706f35b609">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55b9ff225b786fc187522aa94befc0b8">getResourceBufferSize</a> (unsigned PIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of resource units that may be buffered for OOO execution. <a href="#a55b9ff225b786fc187522aa94befc0b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe764852febe90b22412f1acf299fb9e">computeOperandLatency</a> (const MachineInstr *DefMI, unsigned DefOperIdx, const MachineInstr *UseMI, unsigned UseOperIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute operand latency based on the available machine model. <a href="#abe764852febe90b22412f1acf299fb9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a486f9d8524dbb66766ea27c02709d3c7">computeInstrLatency</a> (const MachineInstr *MI, bool UseDefaultDefLatency=true) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the instruction latency based on the available machine model. <a href="#a486f9d8524dbb66766ea27c02709d3c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb6e223c45e270c5b14fbdc934d059c4">computeInstrLatency</a> (const MCInst &amp;Inst) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af994c9d46caf44087197e86bb1be0f31">computeInstrLatency</a> (unsigned Opcode) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a00ff1e3eb19fe4001d742d93f8fade">computeOutputLatency</a> (const MachineInstr *DefMI, unsigned DefOperIdx, const MachineInstr *DepMI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Output dependency latency of a pair of defs of the same register. <a href="#a5a00ff1e3eb19fe4001d742d93f8fade">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace4f0c2aacc5c769605f6af20cbb91f3">computeReciprocalThroughput</a> (const MachineInstr *MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the reciprocal throughput of the given instruction. <a href="#ace4f0c2aacc5c769605f6af20cbb91f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed578032bbe3df337204c7557ec687f1">computeReciprocalThroughput</a> (const MCInst &amp;MI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b043aa01b559cc6f27b63a85332884b">computeReciprocalThroughput</a> (unsigned Opcode) const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a794e9f29c6de7d94715b084b84edbf86">computeInstrLatency</a> (const MCSchedClassDesc &amp;SCDesc) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mcschedmodel">MCSchedModel</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a637503b02842800c7f94ee044852c016">SchedModel</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43c8546aa2fd2788a61c045dbfa6c1d6">InstrItins</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a806c8726bf1a87c55ff2d94da3685672">STI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b788ee7b935cf3d29f82d3949a4b9da">TII</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a482a7fc8de13890a743713b8bb59595a">ResourceFactors</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6bcbf26cfbccc76d7c225e8e3a3c12c">MicroOpFactor</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e0d4918d276b89c1766db176486843e">ResourceLCM</a> = 0</td>
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

<p>Provide an instruction scheduling machine model to CodeGen passes.</p>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ProcResIter {#a7b653a507e8307775b33e01655d3b8d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::TargetSchedModel::ProcResIter =  const MCWriteProcResEntry *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### TargetSchedModel() {#a93036cf35721ff24a7b09b33f5b368de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TargetSchedModel::TargetSchedModel ()</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### computeInstrLatency() {#a486f9d8524dbb66766ea27c02709d3c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetSchedModel::computeInstrLatency (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, bool UseDefaultDefLatency=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the instruction latency based on the available machine model.</p>


<p>Compute and return the expected latency of this instruction independent of a particular use. computeOperandLatency is the preferred API, but this is occasionally useful to help estimate instruction cost.</p>


<p>If UseDefaultDefLatency is false and no new machine sched model is present this method falls back to TII-&gt;getInstrLatency with an empty instruction itinerary (this is so we preserve the previous behavior of the if converter after moving it to <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel">TargetSchedModel</a>).</p>


<p>Declaration at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>, definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetschedule-cpp">TargetSchedule.cpp</a>.</p>


<p>References <a href="#afbb7dc7a2944d22184b4b57a56a167d6">hasInstrItineraries</a>, <a href="#a572a0c9d17306d9414106ad1cf4c8052">hasInstrSchedModel</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc/#a03f7e8be243cde4843e2854d91bfa082">llvm::MCSchedClassDesc::isValid</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#aad3a46af0e50906ff7193aa923b80c65">resolveSchedClass</a>.</p>

</div>
</div>

### computeInstrLatency() {#adb6e223c45e270c5b14fbdc934d059c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetSchedModel::computeInstrLatency (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>, definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetschedule-cpp">TargetSchedule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetschedule-cpp/#a53077df79c9287854b0082944955b854">capLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a> and <a href="#a572a0c9d17306d9414106ad1cf4c8052">hasInstrSchedModel</a>.</p>

</div>
</div>

### computeInstrLatency() {#af994c9d46caf44087197e86bb1be0f31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetSchedModel::computeInstrLatency (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>, definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetschedule-cpp">TargetSchedule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetschedule-cpp/#a53077df79c9287854b0082944955b854">capLatency</a> and <a href="#a572a0c9d17306d9414106ad1cf4c8052">hasInstrSchedModel</a>.</p>

</div>
</div>

### computeOperandLatency() {#abe764852febe90b22412f1acf299fb9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetSchedModel::computeOperandLatency (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * DefMI, unsigned DefOperIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * UseMI, unsigned UseOperIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute operand latency based on the available machine model.</p>


<p>Compute and return the latency of the given data dependent def and use when the operand indices are already known. UseMI may be NULL for an unknown user.</p>


<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>, definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetschedule-cpp">TargetSchedule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetschedule-cpp/#a53077df79c9287854b0082944955b854">capLatency</a>, <a href="/web-llvm/docs/api/structs/llvm/mcwritelatencyentry/#acb109cb600fa4c75a40124a9dafd85cc">llvm::MCWriteLatencyEntry::Cycles</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetschedule-cpp/#a7ee47bba7fdfe2b4de0b767f6d493c26">findDefIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetschedule-cpp/#a0402c8e75bccfb666de451d465cd0ac5">findUseIdx</a>, <a href="#afbb7dc7a2944d22184b4b57a56a167d6">hasInstrItineraries</a>, <a href="#a572a0c9d17306d9414106ad1cf4c8052">hasInstrSchedModel</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc/#a03f7e8be243cde4843e2854d91bfa082">llvm::MCSchedClassDesc::isValid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06a2d68d32ff95cd10b4899c2823ec28e97">llvm::Latency</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc/#aaf852a03b56b36b08ed6b0d0bd221f1c">llvm::MCSchedClassDesc::NumReadAdvanceEntries</a>, <a href="#aad3a46af0e50906ff7193aa923b80c65">resolveSchedClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a> and <a href="/web-llvm/docs/api/structs/llvm/mcwritelatencyentry/#a1f528c20ab89b1480b820d3001a10a8f">llvm::MCWriteLatencyEntry::WriteResourceID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a9027a59d16b066e9f8549b9a9c50b60b">llvm::AArch64Subtarget::adjustSchedDependency</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp/#a0440a06c400cd0c68710d37b74cb8c67">pushDepHeight</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp/#a79107186b863ddb50f8bfdb721aa41d8">updatePhysDepsUpwards</a>.</p>

</div>
</div>

### computeOutputLatency() {#a5a00ff1e3eb19fe4001d742d93f8fade}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetSchedModel::computeOutputLatency (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * DefMI, unsigned DefOperIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * DepMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Output dependency latency of a pair of defs of the same register.</p>


<p>This is typically one cycle.</p>


<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>, definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetschedule-cpp">TargetSchedule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="#a572a0c9d17306d9414106ad1cf4c8052">hasInstrSchedModel</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc/#a03f7e8be243cde4843e2854d91bfa082">llvm::MCSchedClassDesc::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a2380c209ae5339835b5e6ea6d5c197ad">llvm::MachineInstr::readsRegister</a>, <a href="#aad3a46af0e50906ff7193aa923b80c65">resolveSchedClass</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### computeReciprocalThroughput() {#ace4f0c2aacc5c769605f6af20cbb91f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double TargetSchedModel::computeReciprocalThroughput (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the reciprocal throughput of the given instruction.</p>

<p>Declaration at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>, definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetschedule-cpp">TargetSchedule.cpp</a>.</p>


<p>References <a href="#af1cd45c8a7d602373b7da7b5e00527d1">getInstrItineraries</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#ae119a8f604442c5d6b0abb586d6aa03e">llvm::MCSchedModel::getReciprocalThroughput</a>, <a href="#afbb7dc7a2944d22184b4b57a56a167d6">hasInstrItineraries</a>, <a href="#a572a0c9d17306d9414106ad1cf4c8052">hasInstrSchedModel</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#aad3a46af0e50906ff7193aa923b80c65">resolveSchedClass</a>.</p>


<p>Referenced by <a href="#aed578032bbe3df337204c7557ec687f1">computeReciprocalThroughput</a>.</p>

</div>
</div>

### computeReciprocalThroughput() {#aed578032bbe3df337204c7557ec687f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double TargetSchedModel::computeReciprocalThroughput (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>, definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetschedule-cpp">TargetSchedule.cpp</a>.</p>


<p>References <a href="#ace4f0c2aacc5c769605f6af20cbb91f3">computeReciprocalThroughput</a>, <a href="#a572a0c9d17306d9414106ad1cf4c8052">hasInstrSchedModel</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### computeReciprocalThroughput() {#a1b043aa01b559cc6f27b63a85332884b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double TargetSchedModel::computeReciprocalThroughput (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>, definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetschedule-cpp">TargetSchedule.cpp</a>.</p>


<p>References <a href="#af1cd45c8a7d602373b7da7b5e00527d1">getInstrItineraries</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#ae119a8f604442c5d6b0abb586d6aa03e">llvm::MCSchedModel::getReciprocalThroughput</a>, <a href="#afbb7dc7a2944d22184b4b57a56a167d6">hasInstrItineraries</a>, <a href="#a572a0c9d17306d9414106ad1cf4c8052">hasInstrSchedModel</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc/#a03f7e8be243cde4843e2854d91bfa082">llvm::MCSchedClassDesc::isValid</a> and <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc/#a4a9a1303240e655d7c3efb1057b8e7a6">llvm::MCSchedClassDesc::isVariant</a>.</p>

</div>
</div>

### enableIntervals() {#af463f6196bddedc736d9599780cfcc70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetSchedModel::enableIntervals ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>, definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetschedule-cpp">TargetSchedule.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetschedule-cpp/#a9581a7728222e6249652bc489cfb4499">ForceEnableIntervals</a>.</p>

</div>
</div>

### getInstrInfo() {#a1bc8094c82bd7861466b876796ce3a56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo * llvm::TargetSchedModel::getInstrInfo ()</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> getter.</p>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>.</p>

</div>
</div>

### getInstrItineraries() {#af1cd45c8a7d602373b7da7b5e00527d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InstrItineraryData * llvm::TargetSchedModel::getInstrItineraries ()</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>.</p>


<p>Reference <a href="#afbb7dc7a2944d22184b4b57a56a167d6">hasInstrItineraries</a>.</p>


<p>Referenced by <a href="#ace4f0c2aacc5c769605f6af20cbb91f3">computeReciprocalThroughput</a>, <a href="#a1b043aa01b559cc6f27b63a85332884b">computeReciprocalThroughput</a> and <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a0aa73253579dd1c4acde85953454e838">llvm::TargetInstrInfo::hasLowDefLatency</a>.</p>

</div>
</div>

### getIssueWidth() {#a2fdb857df4be03c47fa40a69110b84a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetSchedModel::getIssueWidth ()</td>
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

<p>Maximum number of micro-ops that may be scheduled per cycle.</p>

<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#ae46906a076a2ec35cf6a38e433b48219">llvm::PPCTTIImpl::isHardwareLoopProfitable</a>.</p>

</div>
</div>

### getLatencyFactor() {#a7d3d8b3123f4f5060b648a5e15961630}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetSchedModel::getLatencyFactor ()</td>
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

<p>Multiply cycle count by this factor to normalize it relative to other resources.</p>


<p>This is the number of resource units per cycle.</p>


<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>.</p>

</div>
</div>

### getMCSchedModel() {#a11045ef5588d8e92398df194fbb667da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSchedModel * llvm::TargetSchedModel::getMCSchedModel ()</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>.</p>

</div>
</div>

### getMicroOpBufferSize() {#ace32bee19ef48cedd4a647706f35b609}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetSchedModel::getMicroOpBufferSize ()</td>
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

<p>Number of micro-ops that may be buffered for OOO execution.</p>

<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>.</p>

</div>
</div>

### getMicroOpFactor() {#a3803fd752ed113c37d71580a50888f26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetSchedModel::getMicroOpFactor ()</td>
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

<p>Multiply number of micro-ops by this factor to normalize it relative to other resources.</p>

<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/schedremainder/#a55cad625d59b0f4452d893b4a25c66b6">llvm::SchedRemainder::init</a>.</p>

</div>
</div>

### getNumMicroOps() {#adc6870d8a702ca4f480785afd7a1eba7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetSchedModel::getNumMicroOps (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> * SC=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the number of issue slots required for this MI.</p>

<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>, definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetschedule-cpp">TargetSchedule.cpp</a>.</p>


<p>References <a href="#afbb7dc7a2944d22184b4b57a56a167d6">hasInstrItineraries</a>, <a href="#a572a0c9d17306d9414106ad1cf4c8052">hasInstrSchedModel</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#aad3a46af0e50906ff7193aa923b80c65">resolveSchedClass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/schedremainder/#a55cad625d59b0f4452d893b4a25c66b6">llvm::SchedRemainder::init</a>.</p>

</div>
</div>

### getNumProcResourceKinds() {#aefe560ffcce905bc34e2d46becb54e84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetSchedModel::getNumProcResourceKinds ()</td>
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

<p>Get the number of kinds of resources for this target.</p>

<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/schedremainder/#a55cad625d59b0f4452d893b4a25c66b6">llvm::SchedRemainder::init</a>.</p>

</div>
</div>

### getProcessorID() {#af18042a0439c06f5e5d0ccf53e8b312f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetSchedModel::getProcessorID ()</td>
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

<p>Identify the processor corresponding to the current subtarget.</p>

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>.</p>

</div>
</div>

### getProcResource() {#aea6b86c09906bafae5cdf3393ba05f9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCProcResourceDesc * llvm::TargetSchedModel::getProcResource (unsigned PIdx)</td>
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

<p>Get a processor resource by <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for convenience.</p>

<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>.</p>

</div>
</div>

### getResourceBufferSize() {#a55b9ff225b786fc187522aa94befc0b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::TargetSchedModel::getResourceBufferSize (unsigned PIdx)</td>
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

<p>Number of resource units that may be buffered for OOO execution.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The buffer size in resource units or -1 for unlimited.</p></dd>
</dl>


<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>.</p>

</div>
</div>

### getResourceFactor() {#a9c30a0cd9c2311a92add146b8def5eea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetSchedModel::getResourceFactor (unsigned ResIdx)</td>
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

<p>Multiply the number of units consumed for a resource by this factor to normalize it relative to other resources.</p>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/schedremainder/#a55cad625d59b0f4452d893b4a25c66b6">llvm::SchedRemainder::init</a>.</p>

</div>
</div>

### getResourceName() {#a0c4f7c8efe6089fc458df3df0acbd9be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::TargetSchedModel::getResourceName (unsigned PIdx)</td>
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



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>.</p>

</div>
</div>

### getSubtargetInfo() {#af25644330a6584380b762e4c65482236}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetSubtargetInfo * llvm::TargetSchedModel::getSubtargetInfo ()</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> getter.</p>

<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>.</p>

</div>
</div>

### getWriteProcResBegin() {#af7c94f0b04c1a466ee77ca749cd8dc50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ProcResIter llvm::TargetSchedModel::getWriteProcResBegin (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> * SC)</td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/schedremainder/#a55cad625d59b0f4452d893b4a25c66b6">llvm::SchedRemainder::init</a>.</p>

</div>
</div>

### getWriteProcResEnd() {#a3e53e3e37d8a810d38ffb83268103b23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ProcResIter llvm::TargetSchedModel::getWriteProcResEnd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> * SC)</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/schedremainder/#a55cad625d59b0f4452d893b4a25c66b6">llvm::SchedRemainder::init</a>.</p>

</div>
</div>

### hasInstrItineraries() {#afbb7dc7a2944d22184b4b57a56a167d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetSchedModel::hasInstrItineraries ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this machine model includes cycle-to-cycle itinerary data.</p>


<p>This models scheduling at each stage in the processor pipeline.</p>


<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>, definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetschedule-cpp">TargetSchedule.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetschedule-cpp/#ad34cc79b63d7e8cf5d89e49d31609913">EnableSchedItins</a>.</p>


<p>Referenced by <a href="#a486f9d8524dbb66766ea27c02709d3c7">computeInstrLatency</a>, <a href="#abe764852febe90b22412f1acf299fb9e">computeOperandLatency</a>, <a href="#ace4f0c2aacc5c769605f6af20cbb91f3">computeReciprocalThroughput</a>, <a href="#a1b043aa01b559cc6f27b63a85332884b">computeReciprocalThroughput</a>, <a href="#af1cd45c8a7d602373b7da7b5e00527d1">getInstrItineraries</a>, <a href="#adc6870d8a702ca4f480785afd7a1eba7">getNumMicroOps</a> and <a href="#ac870e1850c5ff410c0dea3600da980c2">hasInstrSchedModelOrItineraries</a>.</p>

</div>
</div>

### hasInstrSchedModel() {#a572a0c9d17306d9414106ad1cf4c8052}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetSchedModel::hasInstrSchedModel ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this machine model includes an instruction-level scheduling model.</p>


<p>This is more detailed than the course grain IssueWidth and default latency properties, but separate from the per-cycle itinerary data.</p>


<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetschedule-cpp">TargetSchedule.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetschedule-cpp/#a55c6dc9a8968eb907f6fa1310c968bea">EnableSchedModel</a>.</p>


<p>Referenced by <a href="#a486f9d8524dbb66766ea27c02709d3c7">computeInstrLatency</a>, <a href="#adb6e223c45e270c5b14fbdc934d059c4">computeInstrLatency</a>, <a href="#af994c9d46caf44087197e86bb1be0f31">computeInstrLatency</a>, <a href="#abe764852febe90b22412f1acf299fb9e">computeOperandLatency</a>, <a href="#a5a00ff1e3eb19fe4001d742d93f8fade">computeOutputLatency</a>, <a href="#ace4f0c2aacc5c769605f6af20cbb91f3">computeReciprocalThroughput</a>, <a href="#aed578032bbe3df337204c7557ec687f1">computeReciprocalThroughput</a>, <a href="#a1b043aa01b559cc6f27b63a85332884b">computeReciprocalThroughput</a>, <a href="#adc6870d8a702ca4f480785afd7a1eba7">getNumMicroOps</a>, <a href="#ac870e1850c5ff410c0dea3600da980c2">hasInstrSchedModelOrItineraries</a>, <a href="/web-llvm/docs/api/structs/llvm/schedremainder/#a55cad625d59b0f4452d893b4a25c66b6">llvm::SchedRemainder::init</a>, <a href="#a731c9c6fb702cf7ea6ae592e2d30126b">mustBeginGroup</a> and <a href="#a1de64b19d5863e1dbbdd3c0ae81ecdb3">mustEndGroup</a>.</p>

</div>
</div>

### hasInstrSchedModelOrItineraries() {#ac870e1850c5ff410c0dea3600da980c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetSchedModel::hasInstrSchedModelOrItineraries ()</td>
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

<p>Return true if this machine model includes an instruction-level scheduling model or cycle-to-cycle itinerary data.</p>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>.</p>


<p>References <a href="#afbb7dc7a2944d22184b4b57a56a167d6">hasInstrItineraries</a> and <a href="#a572a0c9d17306d9414106ad1cf4c8052">hasInstrSchedModel</a>.</p>

</div>
</div>

### init() {#ab357b39c47df52a19882a831feda1b6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TargetSchedModel::init (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> * TSInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize the machine model for instruction scheduling.</p>


<p>The machine model API keeps a copy of the top-level <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel">MCSchedModel</a> table indices and may query <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> to resolve dynamic properties.</p>


<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>, definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetschedule-cpp">TargetSchedule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#af907ecc18c1f4f0bce8a9e2eb449ffb8">llvm::MCSubtargetInfo::getSchedModel</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#ae46906a076a2ec35cf6a38e433b48219">llvm::PPCTTIImpl::isHardwareLoopProfitable</a>.</p>

</div>
</div>

### mustBeginGroup() {#a731c9c6fb702cf7ea6ae592e2d30126b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetSchedModel::mustBeginGroup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> * SC=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if new group must begin.</p>


<p>Returns true only if instruction is specified as single issue.</p>


<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>, definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetschedule-cpp">TargetSchedule.cpp</a>.</p>


<p>References <a href="#a572a0c9d17306d9414106ad1cf4c8052">hasInstrSchedModel</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#aad3a46af0e50906ff7193aa923b80c65">resolveSchedClass</a>.</p>

</div>
</div>

### mustEndGroup() {#a1de64b19d5863e1dbbdd3c0ae81ecdb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetSchedModel::mustEndGroup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> * SC=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if current group must end.</p>

<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>, definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetschedule-cpp">TargetSchedule.cpp</a>.</p>


<p>References <a href="#a572a0c9d17306d9414106ad1cf4c8052">hasInstrSchedModel</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#aad3a46af0e50906ff7193aa923b80c65">resolveSchedClass</a>.</p>

</div>
</div>

### resolveSchedClass() {#aad3a46af0e50906ff7193aa923b80c65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSchedClassDesc * TargetSchedModel::resolveSchedClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> for this instruction.</p>


<p>Some SchedClasses require evaluation of predicates that depend on instruction operands or flags.</p>


<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>, definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetschedule-cpp">TargetSchedule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc/#a03f7e8be243cde4843e2854d91bfa082">llvm::MCSchedClassDesc::isValid</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc/#a4a9a1303240e655d7c3efb1057b8e7a6">llvm::MCSchedClassDesc::isVariant</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a486f9d8524dbb66766ea27c02709d3c7">computeInstrLatency</a>, <a href="#abe764852febe90b22412f1acf299fb9e">computeOperandLatency</a>, <a href="#a5a00ff1e3eb19fe4001d742d93f8fade">computeOutputLatency</a>, <a href="#ace4f0c2aacc5c769605f6af20cbb91f3">computeReciprocalThroughput</a>, <a href="#adc6870d8a702ca4f480785afd7a1eba7">getNumMicroOps</a>, <a href="#a731c9c6fb702cf7ea6ae592e2d30126b">mustBeginGroup</a> and <a href="#a1de64b19d5863e1dbbdd3c0ae81ecdb3">mustEndGroup</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### computeInstrLatency() {#a794e9f29c6de7d94715b084b84edbf86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TargetSchedModel::computeInstrLatency (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> &amp; SCDesc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>, definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetschedule-cpp">TargetSchedule.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### InstrItins {#a43c8546aa2fd2788a61c045dbfa6c1d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrItineraryData llvm::TargetSchedModel::InstrItins</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>.</p>

</div>
</div>

### MicroOpFactor {#aa6bcbf26cfbccc76d7c225e8e3a3c12c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetSchedModel::MicroOpFactor = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>.</p>

</div>
</div>

### ResourceFactors {#a482a7fc8de13890a743713b8bb59595a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;unsigned, 16&gt; llvm::TargetSchedModel::ResourceFactors</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>.</p>

</div>
</div>

### ResourceLCM {#a0e0d4918d276b89c1766db176486843e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetSchedModel::ResourceLCM = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>.</p>

</div>
</div>

### SchedModel {#a637503b02842800c7f94ee044852c016}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSchedModel llvm::TargetSchedModel::SchedModel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>.</p>

</div>
</div>

### STI {#a806c8726bf1a87c55ff2d94da3685672}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetSubtargetInfo* llvm::TargetSchedModel::STI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>.</p>

</div>
</div>

### TII {#a1b788ee7b935cf3d29f82d3949a4b9da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* llvm::TargetSchedModel::TII = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">TargetSchedule.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/targetschedule-cpp">TargetSchedule.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
