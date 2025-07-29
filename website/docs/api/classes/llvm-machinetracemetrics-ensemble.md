---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/machinetracemetrics/ensemble
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Ensemble` Class

<p>A trace ensemble is a collection of traces selected using the same strategy, for example 'minimum resource height'. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MachineTraceMetrics::Ensemble { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">llvm/CodeGen/MachineTraceMetrics.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-machinetracemetrics-cpp-/localensemble">LocalEnsemble</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pick only the current basic block for the trace and do not choose any predecessors/successors. <a href="/web-llvm/docs/api/classes/anonymous-machinetracemetrics-cpp-/localensemble/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-machinetracemetrics-cpp-/mininstrcountensemble">MinInstrCountEnsemble</a></td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a7aa541dbcfdac34b25b49217ec39d7">Trace</a></td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94c7f4353dd7cd3169ab1f8309a6ebbc">Ensemble</a> (MachineTraceMetrics *)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a375a21e590d51aec3ad8da2f2bbb895f">~Ensemble</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89fcf2278835c9221e4586b7f9698fed">getName</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7672297acdaf5409f8e9c116fb4b207">print</a> (raw_ostream &amp;) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3948a6d2974da9cf17fe8c6226f9b569">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a063217bcbb8b81adfdc88feb1a52ddcb">invalidate</a> (const MachineBasicBlock *MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Invalidate traces through BadMBB. <a href="#a063217bcbb8b81adfdc88feb1a52ddcb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a23768d13b961c25d4bb19c3f42824c">verify</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/trace">Trace</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae48d29e7657ecdb05f44195870226d9a">getTrace</a> (const MachineBasicBlock *MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the trace that passes through MBB. <a href="#ae48d29e7657ecdb05f44195870226d9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3118fc82938c92f70453a0ccf9e7fc70">updateDepth</a> (TraceBlockInfo &amp;TBI, const MachineInstr &amp;, SparseSet&lt; LiveRegUnit &gt; &amp;RegUnits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Updates the depth of an machine instruction, given RegUnits. <a href="#a3118fc82938c92f70453a0ccf9e7fc70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a804ccee98d777a9a0e3b342bd850688d">updateDepth</a> (const MachineBasicBlock *, const MachineInstr &amp;, SparseSet&lt; LiveRegUnit &gt; &amp;RegUnits)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a38150d8200741f700cac286154bab3">updateDepths</a> (MachineBasicBlock::iterator Start, MachineBasicBlock::iterator End, SparseSet&lt; LiveRegUnit &gt; &amp;RegUnits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Updates the depth of the instructions from Start to End. <a href="#a7a38150d8200741f700cac286154bab3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16fd3ddeca4f89318c9d449e0d9b8335">pickTracePred</a> (const MachineBasicBlock *)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8b8b17f58253fbeda5d2daa13c916a4">pickTraceSucc</a> (const MachineBasicBlock *)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5046473e61a645cfdec00f76cfc3df7c">getLoopFor</a> (const MachineBasicBlock *) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/traceblockinfo">TraceBlockInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8653801cc578cc48ccbe3e63704b46c2">getDepthResources</a> (const MachineBasicBlock *) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/traceblockinfo">TraceBlockInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77eb2f55afeb56b75868b912d924418e">getHeightResources</a> (const MachineBasicBlock *) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a2f482cc1f32a8cf3193f34f051064e">getProcResourceDepths</a> (unsigned MBBNum) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an array of processor resource depths for MBB. <a href="#a8a2f482cc1f32a8cf3193f34f051064e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ec4ed0a00f77f3225c7e200021c2da2">getProcResourceHeights</a> (unsigned MBBNum) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an array of processor resource heights for MBB. <a href="#a0ec4ed0a00f77f3225c7e200021c2da2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab075e868be7eb6b477441f21d34ea2b8">computeTrace</a> (const MachineBasicBlock *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the trace through MBB. <a href="#ab075e868be7eb6b477441f21d34ea2b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3998744046fbc495d9fc57d1e71ec82">computeDepthResources</a> (const MachineBasicBlock *)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fe8df9259772d1b40b4be970772d1d2">computeHeightResources</a> (const MachineBasicBlock *)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40c03f81eaf866eeb818cbf2ddeb1ad5">computeCrossBlockCriticalPath</a> (const TraceBlockInfo &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The length of the critical path through a trace is the maximum of two path lengths: <a href="#a40c03f81eaf866eeb818cbf2ddeb1ad5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bb52a15415430cd95c4da167a9d14b6">computeInstrDepths</a> (const MachineBasicBlock *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute instruction depths for all instructions above or in MBB in its trace. <a href="#a1bb52a15415430cd95c4da167a9d14b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad93e240b9069128294e6e38df21cf7d8">computeInstrHeights</a> (const MachineBasicBlock *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute instruction heights in the trace through MBB. <a href="#ad93e240b9069128294e6e38df21cf7d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bcbe8947ce0b352e843e2f201fc3338">addLiveIns</a> (const MachineInstr *DefMI, unsigned DefOp, ArrayRef&lt; const MachineBasicBlock * &gt; Trace)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assuming that the virtual register defined by DefMI:DefOp was used by Trace.back(), add it to the live-in lists of all the blocks in <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/trace">Trace</a>. <a href="#a3bcbe8947ce0b352e843e2f201fc3338">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics">MachineTraceMetrics</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa60016dad618cf77f24d57fdd3e33112">MTM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/traceblockinfo">TraceBlockInfo</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cd2bbd553ab66b2cab32b981cde5df7">BlockInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/instrcycles">InstrCycles</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa15ddfc64482e923393197cd39256676">Cycles</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44e089a094ba750d7a5742532937ddb5">ProcResourceDepths</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8b2e10feb5d6a59d9d5e614861035b9">ProcResourceHeights</a></td>
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

<p>A trace ensemble is a collection of traces selected using the same strategy, for example 'minimum resource height'.</p>


<p>There is one trace for every block in the function.</p>


<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>


<div class="doxySectionDef">

## Friends

### Trace {#a9a7aa541dbcfdac34b25b49217ec39d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/trace">Trace</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a> and <a href="#a9a7aa541dbcfdac34b25b49217ec39d7">Trace</a>.</p>


<p>Referenced by <a href="#ae48d29e7657ecdb05f44195870226d9a">getTrace</a> and <a href="#a9a7aa541dbcfdac34b25b49217ec39d7">Trace</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### Ensemble() {#a94c7f4353dd7cd3169ab1f8309a6ebbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineTraceMetrics::Ensemble::Ensemble (<a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics">MachineTraceMetrics</a> * ct)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>, definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp">MachineTraceMetrics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/#a56bc8774919d0422588d4b87222d6dc2">llvm::MachineTraceMetrics::MachineTraceMetrics</a> and <a href="#aa60016dad618cf77f24d57fdd3e33112">MTM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinetracemetrics-cpp-/localensemble/#ab0d2943c10ade05e11aabd4f9930f85b">anonymous{MachineTraceMetrics.cpp}::LocalEnsemble::LocalEnsemble</a> and <a href="/web-llvm/docs/api/classes/anonymous-machinetracemetrics-cpp-/mininstrcountensemble/#a02ee20450fbf488a7abc466f26f4182e">anonymous{MachineTraceMetrics.cpp}::MinInstrCountEnsemble::MinInstrCountEnsemble</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~Ensemble() {#a375a21e590d51aec3ad8da2f2bbb895f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineTraceMetrics::Ensemble::~Ensemble ()</td>
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



<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a3948a6d2974da9cf17fe8c6226f9b569}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineTraceMetrics::Ensemble::dump ()</td>
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



<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="#ac7672297acdaf5409f8e9c116fb4b207">print</a>.</p>

</div>
</div>

### getName() {#a89fcf2278835c9221e4586b7f9698fed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const char * llvm::MachineTraceMetrics::Ensemble::getName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>

</div>
</div>

### getTrace() {#ae48d29e7657ecdb05f44195870226d9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineTraceMetrics::Trace MachineTraceMetrics::Ensemble::getTrace (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the trace that passes through MBB.</p>


<p>The trace is computed on demand.</p>


<p>Declaration at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>, definition at line 1192 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp">MachineTraceMetrics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/traceblockinfo/#a8e39c65ba3a21fb041f682ab7b2be929">llvm::MachineTraceMetrics::TraceBlockInfo::hasValidDepth</a>, <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/traceblockinfo/#ad636cb57c36fe3c776bb458c552435ac">llvm::MachineTraceMetrics::TraceBlockInfo::hasValidHeight</a>, <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/traceblockinfo/#ad5da517ffd94fcc2e20eb76b6abbac50">llvm::MachineTraceMetrics::TraceBlockInfo::HasValidInstrDepths</a>, <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/traceblockinfo/#afc720e9e0f5863604b694be0b991b7a8">llvm::MachineTraceMetrics::TraceBlockInfo::HasValidInstrHeights</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="#a9a7aa541dbcfdac34b25b49217ec39d7">Trace</a>.</p>

</div>
</div>

### invalidate() {#a063217bcbb8b81adfdc88feb1a52ddcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineTraceMetrics::Ensemble::invalidate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Invalidate traces through BadMBB.</p>

<p>Declaration at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>, definition at line 570 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp">MachineTraceMetrics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp/#a2ee79648e8bce3ddbb26358ff10e3e82">getName</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/traceblockinfo/#a8e39c65ba3a21fb041f682ab7b2be929">llvm::MachineTraceMetrics::TraceBlockInfo::hasValidDepth</a>, <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/traceblockinfo/#ad636cb57c36fe3c776bb458c552435ac">llvm::MachineTraceMetrics::TraceBlockInfo::hasValidHeight</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/traceblockinfo/#a145c87332fff3323e335d8f6152ccbcf">llvm::MachineTraceMetrics::TraceBlockInfo::invalidateDepth</a>, <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/traceblockinfo/#aad9695c85c7fa313de163b67ae910b85">llvm::MachineTraceMetrics::TraceBlockInfo::invalidateHeight</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aaa71c733e5aa6113e60a3a806e01bb10">llvm::MachineBasicBlock::isPredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adc8f1be4a77ae671ac139d5f06b44deb">llvm::MachineBasicBlock::isSuccessor</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/traceblockinfo/#a1cf611223ee0f84ce33371cef8151768">llvm::MachineTraceMetrics::TraceBlockInfo::Pred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/traceblockinfo/#a5b72d33d71c887bc07bd9c1551477c4c">llvm::MachineTraceMetrics::TraceBlockInfo::Succ</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecombiner-cpp/#a009d1779a003a0d7f14fbc05073dc987">insertDeleteInstructions</a>.</p>

</div>
</div>

### print() {#ac7672297acdaf5409f8e9c116fb4b207}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineTraceMetrics::Ensemble::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>, definition at line 1321 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp">MachineTraceMetrics.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp/#a2ee79648e8bce3ddbb26358ff10e3e82">getName</a>.</p>


<p>Referenced by <a href="#a3948a6d2974da9cf17fe8c6226f9b569">dump</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9c09811b8bc14cc266b1cbc97295d52">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### updateDepth() {#a3118fc82938c92f70453a0ccf9e7fc70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineTraceMetrics::Ensemble::updateDepth (<a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/traceblockinfo">TraceBlockInfo</a> &amp; TBI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; UseMI, <a href="/web-llvm/docs/api/classes/llvm/sparseset">SparseSet</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/liveregunit">LiveRegUnit</a> &gt; &amp; RegUnits)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Updates the depth of an machine instruction, given RegUnits.</p>

<p>Declaration at line 383 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>, definition at line 823 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp">MachineTraceMetrics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/traceblockinfo/#ac29f5e22ff084751af77306d30e2b437">llvm::MachineTraceMetrics::TraceBlockInfo::CriticalPath</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/instrcycles/#aecec30fb7bb36797ee2c01f1c977a4b9">llvm::MachineTraceMetrics::InstrCycles::Depth</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp/#a59b9890650c2857c6688596e74fefef1">getDataDeps</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp/#a165430a83d0399a48d8983764c9e60b3">getPHIDeps</a>, <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/traceblockinfo/#ad5da517ffd94fcc2e20eb76b6abbac50">llvm::MachineTraceMetrics::TraceBlockInfo::HasValidInstrDepths</a>, <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/traceblockinfo/#afc720e9e0f5863604b694be0b991b7a8">llvm::MachineTraceMetrics::TraceBlockInfo::HasValidInstrHeights</a>, <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/instrcycles/#a71f86c7e329271a09b14d04a1153cb46">llvm::MachineTraceMetrics::InstrCycles::Height</a>, <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/traceblockinfo/#aa1cb1af6ccc2e3907a5c11eab0a850a3">llvm::MachineTraceMetrics::TraceBlockInfo::isUsefulDominator</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#aa60016dad618cf77f24d57fdd3e33112">MTM</a>, <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/traceblockinfo/#a1cf611223ee0f84ce33371cef8151768">llvm::MachineTraceMetrics::TraceBlockInfo::Pred</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp/#a6eb3ac91456a9880aecf25dc8e3cbaa5">updatePhysDepsDownwards</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecombiner-cpp/#a009d1779a003a0d7f14fbc05073dc987">insertDeleteInstructions</a>, <a href="#a804ccee98d777a9a0e3b342bd850688d">updateDepth</a> and <a href="#a7a38150d8200741f700cac286154bab3">updateDepths</a>.</p>

</div>
</div>

### updateDepth() {#a804ccee98d777a9a0e3b342bd850688d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineTraceMetrics::Ensemble::updateDepth (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; UseMI, <a href="/web-llvm/docs/api/classes/llvm/sparseset">SparseSet</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/liveregunit">LiveRegUnit</a> &gt; &amp; RegUnits)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>, definition at line 862 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp">MachineTraceMetrics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#a3118fc82938c92f70453a0ccf9e7fc70">updateDepth</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>.</p>

</div>
</div>

### updateDepths() {#a7a38150d8200741f700cac286154bab3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineTraceMetrics::Ensemble::updateDepths (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> Start, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> End, <a href="/web-llvm/docs/api/classes/llvm/sparseset">SparseSet</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/liveregunit">LiveRegUnit</a> &gt; &amp; RegUnits)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Updates the depth of the instructions from Start to End.</p>

<p>Declaration at line 389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>, definition at line 868 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp">MachineTraceMetrics.cpp</a>.</p>


<p>Reference <a href="#a3118fc82938c92f70453a0ccf9e7fc70">updateDepth</a>.</p>

</div>
</div>

### verify() {#a0a23768d13b961c25d4bb19c3f42824c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineTraceMetrics::Ensemble::verify ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>, definition at line 633 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp">MachineTraceMetrics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a>, <a href="#a5046473e61a645cfdec00f76cfc3df7c">getLoopFor</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/traceblockinfo/#a8e39c65ba3a21fb041f682ab7b2be929">llvm::MachineTraceMetrics::TraceBlockInfo::hasValidDepth</a>, <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/traceblockinfo/#ad636cb57c36fe3c776bb458c552435ac">llvm::MachineTraceMetrics::TraceBlockInfo::hasValidHeight</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#aa60016dad618cf77f24d57fdd3e33112">MTM</a>, <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/traceblockinfo/#a1cf611223ee0f84ce33371cef8151768">llvm::MachineTraceMetrics::TraceBlockInfo::Pred</a> and <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/traceblockinfo/#a5b72d33d71c887bc07bd9c1551477c4c">llvm::MachineTraceMetrics::TraceBlockInfo::Succ</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getDepthResources() {#a8653801cc578cc48ccbe3e63704b46c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineTraceMetrics::TraceBlockInfo * MachineTraceMetrics::Ensemble::getDepthResources (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>, definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp">MachineTraceMetrics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/traceblockinfo/#a8e39c65ba3a21fb041f682ab7b2be929">llvm::MachineTraceMetrics::TraceBlockInfo::hasValidDepth</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### getHeightResources() {#a77eb2f55afeb56b75868b912d924418e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineTraceMetrics::TraceBlockInfo * MachineTraceMetrics::Ensemble::getHeightResources (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>, definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp">MachineTraceMetrics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/traceblockinfo/#ad636cb57c36fe3c776bb458c552435ac">llvm::MachineTraceMetrics::TraceBlockInfo::hasValidHeight</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### getLoopFor() {#a5046473e61a645cfdec00f76cfc3df7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineLoop * MachineTraceMetrics::Ensemble::getLoopFor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>, definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp">MachineTraceMetrics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="#aa60016dad618cf77f24d57fdd3e33112">MTM</a>.</p>


<p>Referenced by <a href="#a0a23768d13b961c25d4bb19c3f42824c">verify</a>.</p>

</div>
</div>

### getProcResourceDepths() {#a8a2f482cc1f32a8cf3193f34f051064e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; unsigned &gt; MachineTraceMetrics::Ensemble::getProcResourceDepths (unsigned MBBNum)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get an array of processor resource depths for MBB.</p>


<p>Indexed by processor resource kind, this array contains the scaled processor resources consumed by all blocks preceding MBB in its trace. It does not include instructions in MBB.</p>


<p>Compare <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/traceblockinfo/#a05783617bfead544a66a41fb304756f2">TraceBlockInfo::InstrDepth</a>.</p>


<p>Declaration at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>, definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp">MachineTraceMetrics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aa60016dad618cf77f24d57fdd3e33112">MTM</a>.</p>

</div>
</div>

### getProcResourceHeights() {#a0ec4ed0a00f77f3225c7e200021c2da2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; unsigned &gt; MachineTraceMetrics::Ensemble::getProcResourceHeights (unsigned MBBNum)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get an array of processor resource heights for MBB.</p>


<p>Indexed by processor resource kind, this array contains the scaled processor resources consumed by this block and all blocks following it in its trace.</p>


<p>Compare <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/traceblockinfo/#a2bee15b953c70ea17198d4d8b60aefed">TraceBlockInfo::InstrHeight</a>.</p>


<p>Declaration at line 367 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>, definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp">MachineTraceMetrics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aa60016dad618cf77f24d57fdd3e33112">MTM</a>.</p>

</div>
</div>

### pickTracePred() {#a16fd3ddeca4f89318c9d449e0d9b8335}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const MachineBasicBlock * llvm::MachineTraceMetrics::Ensemble::pickTracePred (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>

</div>
</div>

### pickTraceSucc() {#aa8b8b17f58253fbeda5d2daa13c916a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const MachineBasicBlock * llvm::MachineTraceMetrics::Ensemble::pickTraceSucc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addLiveIns() {#a3bcbe8947ce0b352e843e2f201fc3338}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineTraceMetrics::Ensemble::addLiveIns (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * DefMI, unsigned DefOp, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; Trace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Assuming that the virtual register defined by DefMI:DefOp was used by Trace.back(), add it to the live-in lists of all the blocks in <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/trace">Trace</a>.</p>


<p>Stop when reaching the block that contains DefMI.</p>


<p>Declaration at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>, definition at line 1016 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp">MachineTraceMetrics.cpp</a>.</p>

</div>
</div>

### computeCrossBlockCriticalPath() {#a40c03f81eaf866eeb818cbf2ddeb1ad5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MachineTraceMetrics::Ensemble::computeCrossBlockCriticalPath (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/traceblockinfo">TraceBlockInfo</a> &amp; TBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The length of the critical path through a trace is the maximum of two path lengths:</p>


<ol class="doxyList" type="1">
<li>The maximum height+depth over all instructions in the trace center block.</li>
<li>The longest cross-block dependency chain. For small blocks, it is possible that the critical path through the trace doesn't include any instructions in the block.</li>
</ol>

<p>This function computes the second number from the live-in list of the center block.</p>


<p>Declaration at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>, definition at line 804 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp">MachineTraceMetrics.cpp</a>.</p>

</div>
</div>

### computeDepthResources() {#aa3998744046fbc495d9fc57d1e71ec82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineTraceMetrics::Ensemble::computeDepthResources (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>, definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp">MachineTraceMetrics.cpp</a>.</p>

</div>
</div>

### computeHeightResources() {#a9fe8df9259772d1b40b4be970772d1d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineTraceMetrics::Ensemble::computeHeightResources (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>, definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp">MachineTraceMetrics.cpp</a>.</p>

</div>
</div>

### computeInstrDepths() {#a1bb52a15415430cd95c4da167a9d14b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineTraceMetrics::Ensemble::computeInstrDepths (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute instruction depths for all instructions above or in MBB in its trace.</p>


<p>This assumes that the trace through MBB has already been computed.</p>


<p>Declaration at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>, definition at line 878 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp">MachineTraceMetrics.cpp</a>.</p>

</div>
</div>

### computeInstrHeights() {#ad93e240b9069128294e6e38df21cf7d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineTraceMetrics::Ensemble::computeInstrHeights (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute instruction heights in the trace through MBB.</p>


<p>This updates MBB and the blocks below it in the trace. It is assumed that the trace has already been computed.</p>


<p>Declaration at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>, definition at line 1037 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp">MachineTraceMetrics.cpp</a>.</p>

</div>
</div>

### computeTrace() {#ab075e868be7eb6b477441f21d34ea2b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineTraceMetrics::Ensemble::computeTrace (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the trace through MBB.</p>

<p>Declaration at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>, definition at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp">MachineTraceMetrics.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### MTM {#aa60016dad618cf77f24d57fdd3e33112}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineTraceMetrics&amp; llvm::MachineTraceMetrics::Ensemble::MTM</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>


<p>Referenced by <a href="#a94c7f4353dd7cd3169ab1f8309a6ebbc">Ensemble</a>, <a href="#a5046473e61a645cfdec00f76cfc3df7c">getLoopFor</a>, <a href="#a8a2f482cc1f32a8cf3193f34f051064e">getProcResourceDepths</a>, <a href="#a0ec4ed0a00f77f3225c7e200021c2da2">getProcResourceHeights</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinetracemetrics-cpp-/localensemble/#ab0d2943c10ade05e11aabd4f9930f85b">anonymous{MachineTraceMetrics.cpp}::LocalEnsemble::LocalEnsemble</a>, <a href="#a3118fc82938c92f70453a0ccf9e7fc70">updateDepth</a> and <a href="#a0a23768d13b961c25d4bb19c3f42824c">verify</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BlockInfo {#a3cd2bbd553ab66b2cab32b981cde5df7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;TraceBlockInfo, 4&gt; llvm::MachineTraceMetrics::Ensemble::BlockInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>

</div>
</div>

### Cycles {#aa15ddfc64482e923393197cd39256676}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MachineInstr*, InstrCycles&gt; llvm::MachineTraceMetrics::Ensemble::Cycles</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>

</div>
</div>

### ProcResourceDepths {#a44e089a094ba750d7a5742532937ddb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;unsigned, 0&gt; llvm::MachineTraceMetrics::Ensemble::ProcResourceDepths</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>

</div>
</div>

### ProcResourceHeights {#ae8b2e10feb5d6a59d9d5e614861035b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;unsigned, 0&gt; llvm::MachineTraceMetrics::Ensemble::ProcResourceHeights</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">MachineTraceMetrics.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp">MachineTraceMetrics.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
