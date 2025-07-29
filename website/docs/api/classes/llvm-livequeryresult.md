---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/livequeryresult
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LiveQueryResult` Class

<p>Result of a <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> query. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LiveQueryResult { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">llvm/CodeGen/LiveInterval.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad06c2e2b6c92ebe70cfdde1e52a3ff46">LiveQueryResult</a> (VNInfo *EarlyVal, VNInfo *LateVal, SlotIndex EndPoint, bool Kill)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a527e4a21e13a8455c75eb0d811701066">valueIn</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the value that is live-in to the instruction. <a href="#a527e4a21e13a8455c75eb0d811701066">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af155aeaffc7607f4f27ab4cfcbb39a64">isKill</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the live-in value is killed by this instruction. <a href="#af155aeaffc7607f4f27ab4cfcbb39a64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a149e4cda329019551bbb27fe3159eca6">isDeadDef</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction has a dead def. <a href="#a149e4cda329019551bbb27fe3159eca6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c9627b7e8bbfa4fbd02f6644907147f">valueOut</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the value leaving the instruction, if any. <a href="#a8c9627b7e8bbfa4fbd02f6644907147f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a001d69b0b75e2841cc109cbe8729ba87">valueOutOrDead</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the value alive at the end of the instruction, if any. <a href="#a001d69b0b75e2841cc109cbe8729ba87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaae33cfd0a31e453deec40b2d5274e70">valueDefined</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the value defined by this instruction, if any. <a href="#aaae33cfd0a31e453deec40b2d5274e70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accf3c068536d27391a38eaec0db05eec">endPoint</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the end point of the last live range segment to interact with the instruction, if any. <a href="#accf3c068536d27391a38eaec0db05eec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a055e74eebb8d1269ebed386682953c16">EarlyVal</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6197d4d4921758d3fea0265505145d6a">LateVal</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af244d112bc391492483248f6f79dc2a9">EndPoint</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82e5529775778f004fe1c149ef2378ee">Kill</a></td>
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

<p>Result of a <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> query.</p>


<p>This class hides the implementation details of live ranges, and it should be used as the primary interface for examining live ranges around instructions.</p>


<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LiveQueryResult() {#ad06c2e2b6c92ebe70cfdde1e52a3ff46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LiveQueryResult::LiveQueryResult (<a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * EarlyVal, <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * LateVal, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> EndPoint, bool Kill)</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### endPoint() {#accf3c068536d27391a38eaec0db05eec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::LiveQueryResult::endPoint ()</td>
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

<p>Return the end point of the last live range segment to interact with the instruction, if any.</p>


<p>The end point is an invalid <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> only if the live range doesn't intersect the instruction at all.</p>


<p>The end point may be at or past the end of the instruction's basic block. That means the value was live out of the block.</p>


<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a94cf1c59ca73ea330872deb639013cb9">llvm::LiveIntervals::pruneValue</a>.</p>

</div>
</div>

### isDeadDef() {#a149e4cda329019551bbb27fe3159eca6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveQueryResult::isDeadDef ()</td>
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

<p>Return true if this instruction has a dead def.</p>

<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a4d40a357c884c36942205713e7bf3244">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLivenessAtDef</a>, <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#acee6dacd4d30da478f3ad67f7fc27142">llvm::RegisterOperands::detectDeadDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#aa1a6fbdf0a3311c7b9602dd67e46fef9">llvm::LiveIntervals::handleMoveIntoNewBundle</a> and <a href="#a8c9627b7e8bbfa4fbd02f6644907147f">valueOut</a>.</p>

</div>
</div>

### isKill() {#af155aeaffc7607f4f27ab4cfcbb39a64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveQueryResult::isKill ()</td>
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

<p>Return true if the live-in value is killed by this instruction.</p>


<p>This means that either the live range ends at the instruction, or it changes value.</p>


<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a185de6f70a894f044801931c4956150d">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLivenessAtUse</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp/#ab52ab15874c8fda9ecc6bae0bcd42444">isDefBetween</a>.</p>

</div>
</div>

### valueDefined() {#aaae33cfd0a31e453deec40b2d5274e70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VNInfo * llvm::LiveQueryResult::valueDefined ()</td>
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

<p>Return the value defined by this instruction, if any.</p>


<p>This includes dead defs, it is the value created by the instruction's def operands.</p>


<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/connectedvninfoeqclasses/#a5d79e4d110e15056182588d168ac6b2f">llvm::ConnectedVNInfoEqClasses::Distribute</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#ac7446b2819c44bf459763351b5bcc29b">llvm::LiveIntervals::shrinkToUses</a> and <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a42083019e0bdb164e55da49ab9f4d717">llvm::LiveIntervals::shrinkToUses</a>.</p>

</div>
</div>

### valueIn() {#a527e4a21e13a8455c75eb0d811701066}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VNInfo * llvm::LiveQueryResult::valueIn ()</td>
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

<p>Return the value that is live-in to the instruction.</p>


<p>This is the value that will be read by the instruction's use operands. Return NULL if no value is live-in.</p>


<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#aa2b8ab3df737c2492c7967447e7abac9">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLiveness</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a185de6f70a894f044801931c4956150d">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLivenessAtUse</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a7bb19d3e5b68421bc97c3c4b524e7888">llvm::ScheduleDAGMILive::computeCyclicCriticalPath</a>, <a href="/web-llvm/docs/api/classes/llvm/connectedvninfoeqclasses/#a5d79e4d110e15056182588d168ac6b2f">llvm::ConnectedVNInfoEqClasses::Distribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp/#ab52ab15874c8fda9ecc6bae0bcd42444">isDefBetween</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp/#a643bfbd7372690fe71cc63171a3219bf">isLiveThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#a9e4d1b2ff6c306576d8ffa9922fa8ba3">llvm::VirtRegAuxInfo::isRematerializable</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#a3730642a8860945b6ca5ca954a238592">anonymous{RegisterCoalescer.cpp}::JoinVals::pruneSubRegValues</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a94cf1c59ca73ea330872deb639013cb9">llvm::LiveIntervals::pruneValue</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#ac7446b2819c44bf459763351b5bcc29b">llvm::LiveIntervals::shrinkToUses</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a42083019e0bdb164e55da49ab9f4d717">llvm::LiveIntervals::shrinkToUses</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a91251ec06d557b21578095955b7b7fa7">llvm::ScheduleDAGMILive::updatePressureDiffs</a>.</p>

</div>
</div>

### valueOut() {#a8c9627b7e8bbfa4fbd02f6644907147f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VNInfo * llvm::LiveQueryResult::valueOut ()</td>
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

<p>Return the value leaving the instruction, if any.</p>


<p>This can be a live-through value, or a live def. A dead def returns NULL.</p>


<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Reference <a href="#a149e4cda329019551bbb27fe3159eca6">isDeadDef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#aa2b8ab3df737c2492c7967447e7abac9">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLiveness</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a185de6f70a894f044801931c4956150d">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLivenessAtUse</a>, <a href="/web-llvm/docs/api/classes/llvm/connectedvninfoeqclasses/#a5d79e4d110e15056182588d168ac6b2f">llvm::ConnectedVNInfoEqClasses::Distribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp/#ab52ab15874c8fda9ecc6bae0bcd42444">isDefBetween</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp/#a643bfbd7372690fe71cc63171a3219bf">isLiveThrough</a> and <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#a3730642a8860945b6ca5ca954a238592">anonymous{RegisterCoalescer.cpp}::JoinVals::pruneSubRegValues</a>.</p>

</div>
</div>

### valueOutOrDead() {#a001d69b0b75e2841cc109cbe8729ba87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VNInfo * llvm::LiveQueryResult::valueOutOrDead ()</td>
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

<p>Returns the value alive at the end of the instruction, if any.</p>


<p>This can be a live-through value, a live def or a dead def.</p>


<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp/#a557a8b6ef8191908ae0c534f76b9f782">isDefInSubRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#a3730642a8860945b6ca5ca954a238592">anonymous{RegisterCoalescer.cpp}::JoinVals::pruneSubRegValues</a> and <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a94cf1c59ca73ea330872deb639013cb9">llvm::LiveIntervals::pruneValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### EarlyVal {#a055e74eebb8d1269ebed386682953c16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VNInfo* const llvm::LiveQueryResult::EarlyVal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

### EndPoint {#af244d112bc391492483248f6f79dc2a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SlotIndex llvm::LiveQueryResult::EndPoint</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

### Kill {#a82e5529775778f004fe1c149ef2378ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::LiveQueryResult::Kill</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

### LateVal {#a6197d4d4921758d3fea0265505145d6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VNInfo* const llvm::LiveQueryResult::LateVal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
