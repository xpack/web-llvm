---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/machinetracemetrics/traceblockinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `TraceBlockInfo` Struct Reference

<p>Per-basic block information that relates to a specific trace through the block. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::MachineTraceMetrics::TraceBlockInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">llvm/CodeGen/MachineTraceMetrics.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa15568fb019e0aebba9ff16aeca2edbb">TraceBlockInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e39c65ba3a21fb041f682ab7b2be929">hasValidDepth</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the depth resources have been computed from the trace above this block. <a href="#a8e39c65ba3a21fb041f682ab7b2be929">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad636cb57c36fe3c776bb458c552435ac">hasValidHeight</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the height resources have been computed from the trace below this block. <a href="#ad636cb57c36fe3c776bb458c552435ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a145c87332fff3323e335d8f6152ccbcf">invalidateDepth</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Invalidate depth resources when some block above this one has changed. <a href="#a145c87332fff3323e335d8f6152ccbcf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad9695c85c7fa313de163b67ae910b85">invalidateHeight</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Invalidate height resources when a block below this one has changed. <a href="#aad9695c85c7fa313de163b67ae910b85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1cb1af6ccc2e3907a5c11eab0a850a3">isUsefulDominator</a> (const TraceBlockInfo &amp;TBI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assuming that this is a dominator of TBI, determine if it contains useful instruction depths. <a href="#aa1cb1af6ccc2e3907a5c11eab0a850a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac780f9f109c83bd4d8654a6394260030">print</a> (raw_ostream &amp;) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6175e738847e2a36fc7036ca50bee741">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cf611223ee0f84ce33371cef8151768">Pred</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/trace">Trace</a> predecessor, or NULL for the first block in the trace. <a href="#a1cf611223ee0f84ce33371cef8151768">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b72d33d71c887bc07bd9c1551477c4c">Succ</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/trace">Trace</a> successor, or NULL for the last block in the trace. <a href="#a5b72d33d71c887bc07bd9c1551477c4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1289df76629f404936fc8b2df1a6934">Head</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The block number of the head of the trace. (When <a href="#a8e39c65ba3a21fb041f682ab7b2be929">hasValidDepth()</a>). <a href="#ad1289df76629f404936fc8b2df1a6934">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef0722b576f40e57f91a2a53b2e97c64">Tail</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The block number of the tail of the trace. (When <a href="#ad636cb57c36fe3c776bb458c552435ac">hasValidHeight()</a>). <a href="#aef0722b576f40e57f91a2a53b2e97c64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05783617bfead544a66a41fb304756f2">InstrDepth</a> = ~0u</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Accumulated number of instructions in the trace above this block. <a href="#a05783617bfead544a66a41fb304756f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bee15b953c70ea17198d4d8b60aefed">InstrHeight</a> = ~0u</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Accumulated number of instructions in the trace below this block. <a href="#a2bee15b953c70ea17198d4d8b60aefed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5da517ffd94fcc2e20eb76b6abbac50">HasValidInstrDepths</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> depths have been computed. This implies <a href="#a8e39c65ba3a21fb041f682ab7b2be929">hasValidDepth()</a>. <a href="#ad5da517ffd94fcc2e20eb76b6abbac50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc720e9e0f5863604b694be0b991b7a8">HasValidInstrHeights</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> heights have been computed. This implies <a href="#ad636cb57c36fe3c776bb458c552435ac">hasValidHeight()</a>. <a href="#afc720e9e0f5863604b694be0b991b7a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac29f5e22ff084751af77306d30e2b437">CriticalPath</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Critical path length. <a href="#ac29f5e22ff084751af77306d30e2b437">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/liveinreg">LiveInReg</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31a27d3966568ca13e2248fe0faf4080">LiveIns</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Live-in registers. <a href="#a31a27d3966568ca13e2248fe0faf4080">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Per-basic block information that relates to a specific trace through the block.</p>


<p>Convergent traces means that only one of these is required per block in a trace ensemble.</p>


<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TraceBlockInfo() {#aa15568fb019e0aebba9ff16aeca2edbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineTraceMetrics::TraceBlockInfo::TraceBlockInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>


<p>Referenced by <a href="#aa1cb1af6ccc2e3907a5c11eab0a850a3">isUsefulDominator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a6175e738847e2a36fc7036ca50bee741}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineTraceMetrics::TraceBlockInfo::dump ()</td>
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



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="#ac780f9f109c83bd4d8654a6394260030">print</a>.</p>

</div>
</div>

### hasValidDepth() {#a8e39c65ba3a21fb041f682ab7b2be929}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineTraceMetrics::TraceBlockInfo::hasValidDepth ()</td>
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

<p>Returns true if the depth resources have been computed from the trace above this block.</p>

<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>


<p>Reference <a href="#a05783617bfead544a66a41fb304756f2">InstrDepth</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#a8653801cc578cc48ccbe3e63704b46c2">llvm::MachineTraceMetrics::Ensemble::getDepthResources</a>, <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#ae48d29e7657ecdb05f44195870226d9a">llvm::MachineTraceMetrics::Ensemble::getTrace</a>, <a href="/web-llvm/docs/api/classes/llvm/po-iterator-storage-3fc582f4b807835050bb72d4ed1f0e76/#a12289268ab155993fbbeef5ef8a2ffa4">llvm::po_iterator_storage&lt; LoopBounds, true &gt;::insertEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#a063217bcbb8b81adfdc88feb1a52ddcb">llvm::MachineTraceMetrics::Ensemble::invalidate</a>, <a href="#aa1cb1af6ccc2e3907a5c11eab0a850a3">isUsefulDominator</a>, <a href="#ac780f9f109c83bd4d8654a6394260030">print</a> and <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#a0a23768d13b961c25d4bb19c3f42824c">llvm::MachineTraceMetrics::Ensemble::verify</a>.</p>

</div>
</div>

### hasValidHeight() {#ad636cb57c36fe3c776bb458c552435ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineTraceMetrics::TraceBlockInfo::hasValidHeight ()</td>
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

<p>Returns true if the height resources have been computed from the trace below this block.</p>

<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>


<p>Reference <a href="#a2bee15b953c70ea17198d4d8b60aefed">InstrHeight</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#a77eb2f55afeb56b75868b912d924418e">llvm::MachineTraceMetrics::Ensemble::getHeightResources</a>, <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#ae48d29e7657ecdb05f44195870226d9a">llvm::MachineTraceMetrics::Ensemble::getTrace</a>, <a href="/web-llvm/docs/api/classes/llvm/po-iterator-storage-3fc582f4b807835050bb72d4ed1f0e76/#a12289268ab155993fbbeef5ef8a2ffa4">llvm::po_iterator_storage&lt; LoopBounds, true &gt;::insertEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#a063217bcbb8b81adfdc88feb1a52ddcb">llvm::MachineTraceMetrics::Ensemble::invalidate</a>, <a href="#ac780f9f109c83bd4d8654a6394260030">print</a> and <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#a0a23768d13b961c25d4bb19c3f42824c">llvm::MachineTraceMetrics::Ensemble::verify</a>.</p>

</div>
</div>

### invalidateDepth() {#a145c87332fff3323e335d8f6152ccbcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineTraceMetrics::TraceBlockInfo::invalidateDepth ()</td>
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

<p>Invalidate depth resources when some block above this one has changed.</p>

<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>


<p>References <a href="#ad5da517ffd94fcc2e20eb76b6abbac50">HasValidInstrDepths</a> and <a href="#a05783617bfead544a66a41fb304756f2">InstrDepth</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#a063217bcbb8b81adfdc88feb1a52ddcb">llvm::MachineTraceMetrics::Ensemble::invalidate</a>.</p>

</div>
</div>

### invalidateHeight() {#aad9695c85c7fa313de163b67ae910b85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineTraceMetrics::TraceBlockInfo::invalidateHeight ()</td>
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

<p>Invalidate height resources when a block below this one has changed.</p>

<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>


<p>References <a href="#afc720e9e0f5863604b694be0b991b7a8">HasValidInstrHeights</a> and <a href="#a2bee15b953c70ea17198d4d8b60aefed">InstrHeight</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#a063217bcbb8b81adfdc88feb1a52ddcb">llvm::MachineTraceMetrics::Ensemble::invalidate</a>.</p>

</div>
</div>

### isUsefulDominator() {#aa1cb1af6ccc2e3907a5c11eab0a850a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineTraceMetrics::TraceBlockInfo::isUsefulDominator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/traceblockinfo">TraceBlockInfo</a> &amp; TBI)</td>
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

<p>Assuming that this is a dominator of TBI, determine if it contains useful instruction depths.</p>


<p>A dominating block can be above the current trace head, and any dependencies from such a far away dominator are not expected to affect the critical path.</p>


<p>Also returns true when TBI == this.</p>


<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>


<p>References <a href="#a8e39c65ba3a21fb041f682ab7b2be929">hasValidDepth</a>, <a href="#ad5da517ffd94fcc2e20eb76b6abbac50">HasValidInstrDepths</a>, <a href="#ad1289df76629f404936fc8b2df1a6934">Head</a>, <a href="#a05783617bfead544a66a41fb304756f2">InstrDepth</a> and <a href="#aa15568fb019e0aebba9ff16aeca2edbb">TraceBlockInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/trace/#a5c87181311e69141665082e3fc53d801">llvm::MachineTraceMetrics::Trace::isDepInTrace</a> and <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#a3118fc82938c92f70453a0ccf9e7fc70">llvm::MachineTraceMetrics::Ensemble::updateDepth</a>.</p>

</div>
</div>

### print() {#ac780f9f109c83bd4d8654a6394260030}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineTraceMetrics::TraceBlockInfo::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>, definition at line 1330 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp">MachineTraceMetrics.cpp</a>.</p>


<p>References <a href="#ac29f5e22ff084751af77306d30e2b437">CriticalPath</a>, <a href="#a8e39c65ba3a21fb041f682ab7b2be929">hasValidDepth</a>, <a href="#ad636cb57c36fe3c776bb458c552435ac">hasValidHeight</a>, <a href="#ad5da517ffd94fcc2e20eb76b6abbac50">HasValidInstrDepths</a>, <a href="#afc720e9e0f5863604b694be0b991b7a8">HasValidInstrHeights</a>, <a href="#ad1289df76629f404936fc8b2df1a6934">Head</a>, <a href="#a05783617bfead544a66a41fb304756f2">InstrDepth</a>, <a href="#a2bee15b953c70ea17198d4d8b60aefed">InstrHeight</a>, <a href="#a1cf611223ee0f84ce33371cef8151768">Pred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="#a5b72d33d71c887bc07bd9c1551477c4c">Succ</a> and <a href="#aef0722b576f40e57f91a2a53b2e97c64">Tail</a>.</p>


<p>Referenced by <a href="#a6175e738847e2a36fc7036ca50bee741">dump</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CriticalPath {#ac29f5e22ff084751af77306d30e2b437}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineTraceMetrics::TraceBlockInfo::CriticalPath</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Critical path length.</p>


<p>This is the number of cycles in the longest data dependency chain through the trace. This is only valid when both HasValidInstrDepths and HasValidInstrHeights are set.</p>


<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>


<p>Referenced by <a href="#ac780f9f109c83bd4d8654a6394260030">print</a> and <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#a3118fc82938c92f70453a0ccf9e7fc70">llvm::MachineTraceMetrics::Ensemble::updateDepth</a>.</p>

</div>
</div>

### HasValidInstrDepths {#ad5da517ffd94fcc2e20eb76b6abbac50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineTraceMetrics::TraceBlockInfo::HasValidInstrDepths = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> depths have been computed. This implies <a href="#a8e39c65ba3a21fb041f682ab7b2be929">hasValidDepth()</a>.</p>

<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#ae48d29e7657ecdb05f44195870226d9a">llvm::MachineTraceMetrics::Ensemble::getTrace</a>, <a href="#a145c87332fff3323e335d8f6152ccbcf">invalidateDepth</a>, <a href="#aa1cb1af6ccc2e3907a5c11eab0a850a3">isUsefulDominator</a>, <a href="#ac780f9f109c83bd4d8654a6394260030">print</a> and <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#a3118fc82938c92f70453a0ccf9e7fc70">llvm::MachineTraceMetrics::Ensemble::updateDepth</a>.</p>

</div>
</div>

### HasValidInstrHeights {#afc720e9e0f5863604b694be0b991b7a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineTraceMetrics::TraceBlockInfo::HasValidInstrHeights = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> heights have been computed. This implies <a href="#ad636cb57c36fe3c776bb458c552435ac">hasValidHeight()</a>.</p>

<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#ae48d29e7657ecdb05f44195870226d9a">llvm::MachineTraceMetrics::Ensemble::getTrace</a>, <a href="#aad9695c85c7fa313de163b67ae910b85">invalidateHeight</a>, <a href="#ac780f9f109c83bd4d8654a6394260030">print</a> and <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#a3118fc82938c92f70453a0ccf9e7fc70">llvm::MachineTraceMetrics::Ensemble::updateDepth</a>.</p>

</div>
</div>

### Head {#ad1289df76629f404936fc8b2df1a6934}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineTraceMetrics::TraceBlockInfo::Head</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The block number of the head of the trace. (When <a href="#a8e39c65ba3a21fb041f682ab7b2be929">hasValidDepth()</a>).</p>

<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>


<p>Referenced by <a href="#aa1cb1af6ccc2e3907a5c11eab0a850a3">isUsefulDominator</a> and <a href="#ac780f9f109c83bd4d8654a6394260030">print</a>.</p>

</div>
</div>

### InstrDepth {#a05783617bfead544a66a41fb304756f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineTraceMetrics::TraceBlockInfo::InstrDepth = ~0u</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Accumulated number of instructions in the trace above this block.</p>


<p>Does not include instructions in this block.</p>


<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>


<p>Referenced by <a href="#a8e39c65ba3a21fb041f682ab7b2be929">hasValidDepth</a>, <a href="#a145c87332fff3323e335d8f6152ccbcf">invalidateDepth</a>, <a href="#aa1cb1af6ccc2e3907a5c11eab0a850a3">isUsefulDominator</a> and <a href="#ac780f9f109c83bd4d8654a6394260030">print</a>.</p>

</div>
</div>

### InstrHeight {#a2bee15b953c70ea17198d4d8b60aefed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineTraceMetrics::TraceBlockInfo::InstrHeight = ~0u</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Accumulated number of instructions in the trace below this block.</p>


<p>Includes instructions in this block.</p>


<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>


<p>Referenced by <a href="#ad636cb57c36fe3c776bb458c552435ac">hasValidHeight</a>, <a href="#aad9695c85c7fa313de163b67ae910b85">invalidateHeight</a> and <a href="#ac780f9f109c83bd4d8654a6394260030">print</a>.</p>

</div>
</div>

### LiveIns {#a31a27d3966568ca13e2248fe0faf4080}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;LiveInReg, 4&gt; llvm::MachineTraceMetrics::TraceBlockInfo::LiveIns</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Live-in registers.</p>


<p>These registers are defined above the current block and used by this block or a block below it. This does not include PHI uses in the current block, but it does include PHI uses in deeper blocks.</p>


<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>

</div>
</div>

### Pred {#a1cf611223ee0f84ce33371cef8151768}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineBasicBlock* llvm::MachineTraceMetrics::TraceBlockInfo::Pred = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/trace">Trace</a> predecessor, or NULL for the first block in the trace.</p>


<p>Valid when <a href="#a8e39c65ba3a21fb041f682ab7b2be929">hasValidDepth()</a>.</p>


<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#a063217bcbb8b81adfdc88feb1a52ddcb">llvm::MachineTraceMetrics::Ensemble::invalidate</a>, <a href="#ac780f9f109c83bd4d8654a6394260030">print</a>, <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#a3118fc82938c92f70453a0ccf9e7fc70">llvm::MachineTraceMetrics::Ensemble::updateDepth</a> and <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#a0a23768d13b961c25d4bb19c3f42824c">llvm::MachineTraceMetrics::Ensemble::verify</a>.</p>

</div>
</div>

### Succ {#a5b72d33d71c887bc07bd9c1551477c4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineBasicBlock* llvm::MachineTraceMetrics::TraceBlockInfo::Succ = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/trace">Trace</a> successor, or NULL for the last block in the trace.</p>


<p>Valid when <a href="#ad636cb57c36fe3c776bb458c552435ac">hasValidHeight()</a>.</p>


<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#a063217bcbb8b81adfdc88feb1a52ddcb">llvm::MachineTraceMetrics::Ensemble::invalidate</a>, <a href="#ac780f9f109c83bd4d8654a6394260030">print</a> and <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#a0a23768d13b961c25d4bb19c3f42824c">llvm::MachineTraceMetrics::Ensemble::verify</a>.</p>

</div>
</div>

### Tail {#aef0722b576f40e57f91a2a53b2e97c64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineTraceMetrics::TraceBlockInfo::Tail</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The block number of the tail of the trace. (When <a href="#ad636cb57c36fe3c776bb458c552435ac">hasValidHeight()</a>).</p>

<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>


<p>Referenced by <a href="#ac780f9f109c83bd4d8654a6394260030">print</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp">MachineTraceMetrics.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
