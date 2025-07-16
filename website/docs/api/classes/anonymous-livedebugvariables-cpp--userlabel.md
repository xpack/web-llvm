---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-livedebugvariables-cpp-/userlabel
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `UserLabel` Class Reference

<p>A user label is a part of a debug info user label. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{LiveDebugVariables.cpp}::UserLabel { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3aa6ddae9477a59b96fa6597cf3be219">UserLabel</a> (const DILabel *label, DebugLoc L, SlotIndex Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/userlabel">UserLabel</a>. <a href="#a3aa6ddae9477a59b96fa6597cf3be219">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aade3703bf81dfed161af8ff0ba94ea2c">matches</a> (const DILabel *L, const DILocation *IA, const SlotIndex Index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does this <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/userlabel">UserLabel</a> match the parameters? <a href="#aade3703bf81dfed161af8ff0ba94ea2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada0f64f2cd5510902725c8a47d5bf56d">emitDebugLabel</a> (LiveIntervals &amp;LIS, const TargetInstrInfo &amp;TII, BlockSkipInstsMap &amp;BBSkipInstsMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recreate DBG_LABEL instruction from data structures. <a href="#ada0f64f2cd5510902725c8a47d5bf56d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a54ff35f90f6530de8a7094d5e3a164">getDebugLoc</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> of this <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/userlabel">UserLabel</a>. <a href="#a8a54ff35f90f6530de8a7094d5e3a164">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa3befc37137ca1a55bd8a2e88ff00e0">print</a> (raw_ostream &amp;, const TargetRegisterInfo *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a181953e71a43263210c30e98e8f43abc">insertDebugLabel</a> (MachineBasicBlock *MBB, SlotIndex Idx, LiveIntervals &amp;LIS, const TargetInstrInfo &amp;TII, BlockSkipInstsMap &amp;BBSkipInstsMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a DBG_LABEL into MBB at Idx. <a href="#a181953e71a43263210c30e98e8f43abc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilabel">DILabel</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5098ad5e409358a301a52bd990188a6">Label</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The debug info label we are part of. <a href="#ab5098ad5e409358a301a52bd990188a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a682a898dd5e094dfb7f0a87e9abdde5d">dl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The debug location for the label. <a href="#a682a898dd5e094dfb7f0a87e9abdde5d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34efe9ee370fb1b7a94bbf822b967b5e">loc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Slot used by the debug label. <a href="#a34efe9ee370fb1b7a94bbf822b967b5e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A user label is a part of a debug info user label.</p>

<p>Definition at line 503 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### UserLabel() {#a3aa6ddae9477a59b96fa6597cf3be219}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LiveDebugVariables.cpp}::UserLabel::UserLabel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilabel">DILabel</a> * label, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> L, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Idx)</td>
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

<p>Create a new <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/userlabel">UserLabel</a>.</p>

<p>Definition at line 516 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitDebugLabel() {#ada0f64f2cd5510902725c8a47d5bf56d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void UserLabel::emitDebugLabel (<a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp; LIS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> &amp; TII, <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp/#ab17bc8e142c2f18a7576ea8276b0d124">BlockSkipInstsMap</a> &amp; BBSkipInstsMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recreate DBG_LABEL instruction from data structures.</p>

<p>Definition at line 526 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#af3fe68c1ef3d401833b3d37cc222ead2">llvm::LiveIntervals::getMBBFromIndex</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### getDebugLoc() {#a8a54ff35f90f6530de8a7094d5e3a164}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DebugLoc &amp; anonymous{LiveDebugVariables.cpp}::UserLabel::getDebugLoc ()</td>
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

<p>Return <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> of this <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/userlabel">UserLabel</a>.</p>

<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### matches() {#aade3703bf81dfed161af8ff0ba94ea2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LiveDebugVariables.cpp}::UserLabel::matches (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilabel">DILabel</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * IA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Index)</td>
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

<p>Does this <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/userlabel">UserLabel</a> match the parameters?</p>

<p>Definition at line 520 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### print() {#afa3befc37137ca1a55bd8a2e88ff00e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void UserLabel::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 532 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp/#a6bcdb97daefc7a1ed36de42e22be84b2">printExtendedName</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### insertDebugLabel() {#a181953e71a43263210c30e98e8f43abc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void UserLabel::insertDebugLabel (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Idx, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp; LIS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> &amp; TII, <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp/#ab17bc8e142c2f18a7576ea8276b0d124">BlockSkipInstsMap</a> &amp; BBSkipInstsMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a DBG_LABEL into MBB at Idx.</p>

<p>Definition at line 510 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### dl {#a682a898dd5e094dfb7f0a87e9abdde5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc anonymous{LiveDebugVariables.cpp}::UserLabel::dl</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The debug location for the label.</p>


<p>This is used by dwarf writer to find lexical scope.</p>


<p>Definition at line 505 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### Label {#ab5098ad5e409358a301a52bd990188a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DILabel* anonymous{LiveDebugVariables.cpp}::UserLabel::Label</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The debug info label we are part of.</p>

<p>Definition at line 504 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### loc {#a34efe9ee370fb1b7a94bbf822b967b5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex anonymous{LiveDebugVariables.cpp}::UserLabel::loc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Slot used by the debug label.</p>

<p>Definition at line 507 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
