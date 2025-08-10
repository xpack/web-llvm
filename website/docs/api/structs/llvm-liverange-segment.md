---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/liverange/segment
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `Segment` Struct

<p>This represents a simple continuous liveness interval for a value. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::LiveRange::Segment { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">llvm/CodeGen/LiveInterval.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ef182a28a281af98ce25c5142433413">Segment</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99cddbeb8e6c8377416302da7f84940e">Segment</a> (SlotIndex S, SlotIndex E, VNInfo *V)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6cefab57f3f0bca03f3204eb0220d60">operator&lt;</a> (const Segment &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f8fcd301d0551372c908462c7f1bcb4">operator==</a> (const Segment &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c220d7f045e4b402454f75c452d2c16">operator!=</a> (const Segment &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0b08f08ddd79f6469dd14f7923a2bb2">contains</a> (SlotIndex I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the index is covered by this segment. <a href="#aa0b08f08ddd79f6469dd14f7923a2bb2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a30a2c9da2d56ab16c71cd95617b64d">containsInterval</a> (SlotIndex S, SlotIndex E) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the given interval, [S, E), is covered by this segment. <a href="#a8a30a2c9da2d56ab16c71cd95617b64d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaefba2d8bca4f1f27e3ec5d2efe8c4f">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85f7bf79596d84273b5b3b9b490bc2ec">start</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe8e59ffc86cb1736116e4dc8b86e26f">end</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3d1b43d371bc68742232ec51d4a6321">valno</a> = nullptr</td>
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

<p>This represents a simple continuous liveness interval for a value.</p>


<p>The start point is inclusive, the end point exclusive. These intervals are rendered as [start,end).</p>


<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Segment() {#a8ef182a28a281af98ce25c5142433413}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LiveRange::Segment::Segment ()</td>
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



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Referenced by <a href="#a8c220d7f045e4b402454f75c452d2c16">operator!=</a>, <a href="#ae6cefab57f3f0bca03f3204eb0220d60">operator&lt;</a> and <a href="#a7f8fcd301d0551372c908462c7f1bcb4">operator==</a>.</p>

</div>
</div>

### Segment() {#a99cddbeb8e6c8377416302da7f84940e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LiveRange::Segment::Segment (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> S, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> E, <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * V)</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#afe8e59ffc86cb1736116e4dc8b86e26f">end</a>, <a href="#a85f7bf79596d84273b5b3b9b490bc2ec">start</a> and <a href="#ac3d1b43d371bc68742232ec51d4a6321">valno</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a8c220d7f045e4b402454f75c452d2c16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveRange::Segment::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/liverange/segment">Segment</a> &amp; Other)</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a8ef182a28a281af98ce25c5142433413">Segment</a>.</p>

</div>
</div>

### operator&lt;() {#ae6cefab57f3f0bca03f3204eb0220d60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveRange::Segment::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/liverange/segment">Segment</a> &amp; Other)</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="#afe8e59ffc86cb1736116e4dc8b86e26f">end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a8ef182a28a281af98ce25c5142433413">Segment</a> and <a href="#a85f7bf79596d84273b5b3b9b490bc2ec">start</a>.</p>

</div>
</div>

### operator==() {#a7f8fcd301d0551372c908462c7f1bcb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveRange::Segment::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/liverange/segment">Segment</a> &amp; Other)</td>
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



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="#afe8e59ffc86cb1736116e4dc8b86e26f">end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a8ef182a28a281af98ce25c5142433413">Segment</a> and <a href="#a85f7bf79596d84273b5b3b9b490bc2ec">start</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### contains() {#aa0b08f08ddd79f6469dd14f7923a2bb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveRange::Segment::contains (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> I)</td>
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

<p>Return true if the index is covered by this segment.</p>

<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="#afe8e59ffc86cb1736116e4dc8b86e26f">end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a85f7bf79596d84273b5b3b9b490bc2ec">start</a>.</p>

</div>
</div>

### containsInterval() {#a8a30a2c9da2d56ab16c71cd95617b64d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveRange::Segment::containsInterval (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> S, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> E)</td>
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

<p>Return true if the given interval, [S, E), is covered by this segment.</p>

<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#afe8e59ffc86cb1736116e4dc8b86e26f">end</a> and <a href="#a85f7bf79596d84273b5b3b9b490bc2ec">start</a>.</p>

</div>
</div>

### dump() {#acaefba2d8bca4f1f27e3ec5d2efe8c4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void LiveRange::Segment::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 994 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### end {#afe8e59ffc86cb1736116e4dc8b86e26f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::LiveRange::Segment::end</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liverangeupdater/#aecdfedd0173a7d04cd7d06d4538dc7bc">llvm::LiveRangeUpdater::add</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a6e3886e9084257e74b5db4a8951d36e0">llvm::LiveIntervals::addKillFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp/#a61eeba1f176225faf4761e4d9b25cc43">addSegmentsWithValNo</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#ae7eb95d6c78b269fe03ed9c78cf2c33f">llvm::LiveRange::assign</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#acf40b35a88eb365bc4f4047a03bb1ece">llvm::X86InstrInfo::classifyLEAReg</a>, <a href="#aa0b08f08ddd79f6469dd14f7923a2bb2">contains</a>, <a href="#a8a30a2c9da2d56ab16c71cd95617b64d">containsInterval</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a061f47e0bf17eed5f4fb190668a20858">llvm::RISCVInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#a1066c542d3ccd99d3e740ad91aed49de">anonymous{LiveDebugVariables.cpp}::UserValue::extendDef</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#ad8b14ec0777ac642d3403470e0753533">llvm::RegPressureTracker::getLiveThroughAt</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#aae51d91c7cb4dc1a4ffabbfd1b7be9a1">llvm::LiveRange::MergeSegmentsInAsValue</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a325a4ec9c33a3dead9ff01c9e70fd534">llvm::LiveRange::MergeValueInAsValue</a>, <a href="#ae6cefab57f3f0bca03f3204eb0220d60">operator&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a825d7d6de0a8dc551a2845f353036b6a">llvm::operator&lt;&lt;</a>, <a href="#a7f8fcd301d0551372c908462c7f1bcb4">operator==</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp/#a5d107951e5df0e107a1269647a484f2f">removeDeadSegment</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#aedd2a145f951aba2dc5ee491dfdbfceb">llvm::LiveRange::removeSegment</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpumarklastscratchload-cpp-/amdgpumarklastscratchload/#adb457e87e019538757ec91bec7a7e5f0">anonymous{AMDGPUMarkLastScratchLoad.cpp}::AMDGPUMarkLastScratchLoad::runOnMachineFunction</a>, <a href="#a99cddbeb8e6c8377416302da7f84940e">Segment</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a42083019e0bdb164e55da49ab9f4d717">llvm::LiveIntervals::shrinkToUses</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abc440c9fad640641c26ddae8c08dce82">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveRangeSegment</a>.</p>

</div>
</div>

### start {#a85f7bf79596d84273b5b3b9b490bc2ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::LiveRange::Segment::start</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liverangeupdater/#aecdfedd0173a7d04cd7d06d4538dc7bc">llvm::LiveRangeUpdater::add</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a6e3886e9084257e74b5db4a8951d36e0">llvm::LiveIntervals::addKillFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp/#a61eeba1f176225faf4761e4d9b25cc43">addSegmentsWithValNo</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a8fc86da696e49b67827c940045434c4b">llvm::LiveRange::append</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#ae7eb95d6c78b269fe03ed9c78cf2c33f">llvm::LiveRange::assign</a>, <a href="#aa0b08f08ddd79f6469dd14f7923a2bb2">contains</a>, <a href="#a8a30a2c9da2d56ab16c71cd95617b64d">containsInterval</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#ad8b14ec0777ac642d3403470e0753533">llvm::RegPressureTracker::getLiveThroughAt</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#aae51d91c7cb4dc1a4ffabbfd1b7be9a1">llvm::LiveRange::MergeSegmentsInAsValue</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a325a4ec9c33a3dead9ff01c9e70fd534">llvm::LiveRange::MergeValueInAsValue</a>, <a href="#ae6cefab57f3f0bca03f3204eb0220d60">operator&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e9d939eec3239b0f0485aa7be244b6c">llvm::operator&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d7b2eb09dd0680a69c9af535b9d53ec">llvm::operator&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a825d7d6de0a8dc551a2845f353036b6a">llvm::operator&lt;&lt;</a>, <a href="#a7f8fcd301d0551372c908462c7f1bcb4">operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#aedd2a145f951aba2dc5ee491dfdbfceb">llvm::LiveRange::removeSegment</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpumarklastscratchload-cpp-/amdgpumarklastscratchload/#adb457e87e019538757ec91bec7a7e5f0">anonymous{AMDGPUMarkLastScratchLoad.cpp}::AMDGPUMarkLastScratchLoad::runOnMachineFunction</a>, <a href="#a99cddbeb8e6c8377416302da7f84940e">Segment</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abc440c9fad640641c26ddae8c08dce82">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveRangeSegment</a>.</p>

</div>
</div>

### valno {#ac3d1b43d371bc68742232ec51d4a6321}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VNInfo* llvm::LiveRange::Segment::valno = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liverangeupdater/#aecdfedd0173a7d04cd7d06d4538dc7bc">llvm::LiveRangeUpdater::add</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp/#a61eeba1f176225faf4761e4d9b25cc43">addSegmentsWithValNo</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#ae7eb95d6c78b269fe03ed9c78cf2c33f">llvm::LiveRange::assign</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#a1066c542d3ccd99d3e740ad91aed49de">anonymous{LiveDebugVariables.cpp}::UserValue::extendDef</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a2b10543d5f749956dd408fd7ebb3c552">llvm::LiveRange::join</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a325a4ec9c33a3dead9ff01c9e70fd534">llvm::LiveRange::MergeValueInAsValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a825d7d6de0a8dc551a2845f353036b6a">llvm::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a63176e601338dbe403676b86e78c7203">llvm::LiveRange::removeValNo</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#aea1f4a9101ccc20faa0e67fdef1e5086">llvm::LiveRange::removeValNoIfDead</a>, <a href="#a99cddbeb8e6c8377416302da7f84940e">Segment</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abc440c9fad640641c26ddae8c08dce82">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveRangeSegment</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
