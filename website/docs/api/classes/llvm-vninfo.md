---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vninfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `VNInfo` Class

<p><a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> - <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> Number Information. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::VNInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">llvm/CodeGen/LiveInterval.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa750a7f159760b9c378d930deb6a9837">Allocator</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a12b509ba1b5967f2beec884eb17da9">VNInfo</a> (unsigned i, SlotIndex d)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> constructor. <a href="#a4a12b509ba1b5967f2beec884eb17da9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cdbcb31845858ea86bc50de705378c1">VNInfo</a> (unsigned i, const VNInfo &amp;orig)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> constructor, copies values from orig, except for the value number. <a href="#a5cdbcb31845858ea86bc50de705378c1">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a075960d0135f97b5df867eeaf30215f2">copyFrom</a> (VNInfo &amp;src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy from the parameter into this <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a>. <a href="#a075960d0135f97b5df867eeaf30215f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae72fbcf51be7574c84817cde814df07e">isPHIDef</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this value is defined by a PHI instruction (or was, PHI instructions may have been eliminated). <a href="#ae72fbcf51be7574c84817cde814df07e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab72366fd538f240cbb53dac39368cdfc">isUnused</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this value is unused. <a href="#ab72366fd538f240cbb53dac39368cdfc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81775e4a3dbcbc42d828c3e4becd9190">markUnused</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark this value as unused. <a href="#a81775e4a3dbcbc42d828c3e4becd9190">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad989a0c1b26066308798f4d11a0e69df">id</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> number of this value. <a href="#ad989a0c1b26066308798f4d11a0e69df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae623a0f1ab59da851f2ebf1674d1fddb">def</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The index of the defining instruction. <a href="#ae623a0f1ab59da851f2ebf1674d1fddb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> - <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> Number Information.</p>


<p>This class holds information about a machine level values, including definition and use points.</p>


<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### Allocator {#aa750a7f159760b9c378d930deb6a9837}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::VNInfo::Allocator =  BumpPtrAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### VNInfo() {#a4a12b509ba1b5967f2beec884eb17da9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VNInfo::VNInfo (unsigned i, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> d)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> constructor.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="#ae623a0f1ab59da851f2ebf1674d1fddb">def</a> and <a href="#ad989a0c1b26066308798f4d11a0e69df">id</a>.</p>


<p>Referenced by <a href="#a075960d0135f97b5df867eeaf30215f2">copyFrom</a> and <a href="#a5cdbcb31845858ea86bc50de705378c1">VNInfo</a>.</p>

</div>
</div>

### VNInfo() {#a5cdbcb31845858ea86bc50de705378c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VNInfo::VNInfo (unsigned i, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> &amp; orig)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> constructor, copies values from orig, except for the value number.</p>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="#ae623a0f1ab59da851f2ebf1674d1fddb">def</a>, <a href="#ad989a0c1b26066308798f4d11a0e69df">id</a> and <a href="#a4a12b509ba1b5967f2beec884eb17da9">VNInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### copyFrom() {#a075960d0135f97b5df867eeaf30215f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VNInfo::copyFrom (<a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> &amp; src)</td>
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

<p>Copy from the parameter into this <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a>.</p>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="#ae623a0f1ab59da851f2ebf1674d1fddb">def</a> and <a href="#a4a12b509ba1b5967f2beec884eb17da9">VNInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liverange/#a92e17326c2170e889ae4390c56878b77">llvm::LiveRange::MergeValueNumberInto</a>.</p>

</div>
</div>

### isPHIDef() {#ae72fbcf51be7574c84817cde814df07e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VNInfo::isPHIDef ()</td>
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

<p>Returns true if this value is defined by a PHI instruction (or was, PHI instructions may have been eliminated).</p>


<p>PHI-defs begin at a block boundary, all other defs begin at register or EC slots.</p>


<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Reference <a href="#ae623a0f1ab59da851f2ebf1674d1fddb">def</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/connectedvninfoeqclasses/#ab075ccec6878e16419fca5e423c7ddad">llvm::ConnectedVNInfoEqClasses::Classify</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a7bb19d3e5b68421bc97c3c4b524e7888">llvm::ScheduleDAGMILive::computeCyclicCriticalPath</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc/#af5198110c0058e3d60524eecf500ee51">llvm::LiveIntervalCalc::constructMainRangeFromSubranges</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp/#a643bfbd7372690fe71cc63171a3219bf">isLiveThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#a9e4d1b2ff6c306576d8ffa9922fa8ba3">llvm::VirtRegAuxInfo::isRematerializable</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#af62a3dfb9ce9b78c94e7b910a02b28cf">llvm::LiveRange::print</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#a1b3c2e77ef89dfcb6bc2129edc827264">anonymous{RegisterCoalescer.cpp}::JoinVals::pruneMainSegments</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#a3730642a8860945b6ca5ca954a238592">anonymous{RegisterCoalescer.cpp}::JoinVals::pruneSubRegValues</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#add7c3bdd8428904f63f53569807b8df6">anonymous{RegisterCoalescer.cpp}::JoinVals::resolveConflicts</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a42083019e0bdb164e55da49ab9f4d717">llvm::LiveIntervals::shrinkToUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp/#aeb309e71b02f8298a437ec465645fe99">stripValuesNotDefiningMask</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abc440c9fad640641c26ddae8c08dce82">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveRangeSegment</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a38cfbca05868eacdc315641e8ed182d4">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveRangeValue</a>.</p>

</div>
</div>

### isUnused() {#ab72366fd538f240cbb53dac39368cdfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VNInfo::isUnused ()</td>
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

<p>Returns true if this value is unused.</p>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Reference <a href="#ae623a0f1ab59da851f2ebf1674d1fddb">def</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/connectedvninfoeqclasses/#ab075ccec6878e16419fca5e423c7ddad">llvm::ConnectedVNInfoEqClasses::Classify</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc/#af5198110c0058e3d60524eecf500ee51">llvm::LiveIntervalCalc::constructMainRangeFromSubranges</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp/#ac46976013d5526a5d1430256b4007b6b">createSegmentsForValues</a>, <a href="/web-llvm/docs/api/classes/llvm/connectedvninfoeqclasses/#a5d79e4d110e15056182588d168ac6b2f">llvm::ConnectedVNInfoEqClasses::Distribute</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a98fa413da7a0053bf635119e74970219">llvm::SplitEditor::finish</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#a9e4d1b2ff6c306576d8ffa9922fa8ba3">llvm::VirtRegAuxInfo::isRematerializable</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#af62a3dfb9ce9b78c94e7b910a02b28cf">llvm::LiveRange::print</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#a1b3c2e77ef89dfcb6bc2129edc827264">anonymous{RegisterCoalescer.cpp}::JoinVals::pruneMainSegments</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a687cab1756967efc8f0ce66105531755">llvm::LiveRange::RenumberValues</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a42083019e0bdb164e55da49ab9f4d717">llvm::LiveIntervals::shrinkToUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp/#aeb309e71b02f8298a437ec465645fe99">stripValuesNotDefiningMask</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abc440c9fad640641c26ddae8c08dce82">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveRangeSegment</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a38cfbca05868eacdc315641e8ed182d4">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveRangeValue</a>.</p>

</div>
</div>

### markUnused() {#a81775e4a3dbcbc42d828c3e4becd9190}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VNInfo::markUnused ()</td>
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

<p>Mark this value as unused.</p>

<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Reference <a href="#ae623a0f1ab59da851f2ebf1674d1fddb">def</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#a1659a196eabbdd653b9a5d529ccfcb6e">anonymous{RegisterCoalescer.cpp}::JoinVals::eraseInstrs</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#a3730642a8860945b6ca5ca954a238592">anonymous{RegisterCoalescer.cpp}::JoinVals::pruneSubRegValues</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#a8546f9a7fa0a18cfe46dc20582dcbed2">anonymous{RegisterCoalescer.cpp}::JoinVals::removeImplicitDefs</a> and <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a42083019e0bdb164e55da49ab9f4d717">llvm::LiveIntervals::shrinkToUses</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### def {#ae623a0f1ab59da851f2ebf1674d1fddb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::VNInfo::def</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The index of the defining instruction.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#ac0a0c1bb8dc69992e326ead7f5faf286">anonymous{LiveDebugVariables.cpp}::UserValue::addDefsFromCopies</a>, <a href="/web-llvm/docs/api/classes/llvm/connectedvninfoeqclasses/#ab075ccec6878e16419fca5e423c7ddad">llvm::ConnectedVNInfoEqClasses::Classify</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a7bb19d3e5b68421bc97c3c4b524e7888">llvm::ScheduleDAGMILive::computeCyclicCriticalPath</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#aee8fb987217bee89c0f2059168e834ec">anonymous{MachineScheduler.cpp}::CopyConstrain::constrainLocalCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc/#af5198110c0058e3d60524eecf500ee51">llvm::LiveIntervalCalc::constructMainRangeFromSubranges</a>, <a href="#a075960d0135f97b5df867eeaf30215f2">copyFrom</a>, <a href="/web-llvm/docs/api/classes/anonymous-liveinterval-cpp-/calcliverangeutilbase/#acc30e10385342c3caf14a3bf391bc72b">anonymous{LiveInterval.cpp}::CalcLiveRangeUtilBase&lt; CalcLiveRangeUtilVector, LiveRange::iterator, LiveRange::Segments &gt;::createDeadDef</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#adbfe0544c5d2588941c44827f801e64b">llvm::LiveRange::createDeadDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp/#ac46976013d5526a5d1430256b4007b6b">createSegmentsForValues</a>, <a href="/web-llvm/docs/api/classes/llvm/connectedvninfoeqclasses/#a5d79e4d110e15056182588d168ac6b2f">llvm::ConnectedVNInfoEqClasses::Distribute</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a8808112c59febd729a9964ac6509d7d4">llvm::SplitEditor::enterIntvAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a94fd41d857393a092523f88b19d1bef3">llvm::SplitEditor::enterIntvAtEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a88924909b2d83abe8eb4ba2ac84eec6c">llvm::SplitEditor::enterIntvBefore</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#a1659a196eabbdd653b9a5d529ccfcb6e">anonymous{RegisterCoalescer.cpp}::JoinVals::eraseInstrs</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a98fa413da7a0053bf635119e74970219">llvm::SplitEditor::finish</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp/#a557a8b6ef8191908ae0c534f76b9f782">isDefInSubRange</a>, <a href="#ae72fbcf51be7574c84817cde814df07e">isPHIDef</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#a9e4d1b2ff6c306576d8ffa9922fa8ba3">llvm::VirtRegAuxInfo::isRematerializable</a>, <a href="#ab72366fd538f240cbb53dac39368cdfc">isUnused</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a8ab989120222d67308b4e03b2772fb6a">llvm::SplitEditor::leaveIntvAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a98785a9cb443380b8f700cb764a6fd84">llvm::SplitEditor::leaveIntvAtTop</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a9899a3945a73e70c7bb2800ef3865017">llvm::SplitEditor::leaveIntvBefore</a>, <a href="#a81775e4a3dbcbc42d828c3e4becd9190">markUnused</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#ad7ed3a1e19bd5b3c4ea5a74413371900">moveAndTeeForMultiUse</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#af62a3dfb9ce9b78c94e7b910a02b28cf">llvm::LiveRange::print</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxfmamutate-cpp-/ppcvsxfmamutate/#acd5cf076b2f9e98086a68b9d7e0f8710">anonymous{PPCVSXFMAMutate.cpp}::PPCVSXFMAMutate::processBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#a1b3c2e77ef89dfcb6bc2129edc827264">anonymous{RegisterCoalescer.cpp}::JoinVals::pruneMainSegments</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#a3730642a8860945b6ca5ca954a238592">anonymous{RegisterCoalescer.cpp}::JoinVals::pruneSubRegValues</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a6eb0e49d283729a5f8b99d4efa1be7c1">llvm::LiveRange::Query</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#ac332ca27d85adc8d21edd708be55dfe3">llvm::LiveIntervals::removeVRegDefAt</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#ad02cdb6766947f5b6254789d07cfb88e">anonymous{MachineVerifier.cpp}::MachineVerifier::report_context</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#add7c3bdd8428904f63f53569807b8df6">anonymous{RegisterCoalescer.cpp}::JoinVals::resolveConflicts</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a42083019e0bdb164e55da49ab9f4d717">llvm::LiveIntervals::shrinkToUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp/#aeb309e71b02f8298a437ec465645fe99">stripValuesNotDefiningMask</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abc440c9fad640641c26ddae8c08dce82">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveRangeSegment</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a38cfbca05868eacdc315641e8ed182d4">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveRangeValue</a>, <a href="#a5cdbcb31845858ea86bc50de705378c1">VNInfo</a> and <a href="#a4a12b509ba1b5967f2beec884eb17da9">VNInfo</a>.</p>

</div>
</div>

### id {#ad989a0c1b26066308798f4d11a0e69df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::VNInfo::id</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> number of this value.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#ac0a0c1bb8dc69992e326ead7f5faf286">anonymous{LiveDebugVariables.cpp}::UserValue::addDefsFromCopies</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#ae7eb95d6c78b269fe03ed9c78cf2c33f">llvm::LiveRange::assign</a>, <a href="/web-llvm/docs/api/classes/llvm/connectedvninfoeqclasses/#ab075ccec6878e16419fca5e423c7ddad">llvm::ConnectedVNInfoEqClasses::Classify</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a5c036680263adf0032709cd2e7c3c9c3">llvm::LiveRange::containsValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a78118d64746879fbc29e499228182853">llvm::DistributeRange</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a8808112c59febd729a9964ac6509d7d4">llvm::SplitEditor::enterIntvAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a94fd41d857393a092523f88b19d1bef3">llvm::SplitEditor::enterIntvAtEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a88924909b2d83abe8eb4ba2ac84eec6c">llvm::SplitEditor::enterIntvBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/connectedvninfoeqclasses/#ae72973e4a97d936d5d4805a89a3cc2ec">llvm::ConnectedVNInfoEqClasses::getEqClass</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinespiller-cpp-/hoistspillhelper/#a597bb5d7ef9a22f44dbe867d8eaa7fd6">anonymous{InlineSpiller.cpp}::HoistSpillHelper::hoistAllSpills</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a2b10543d5f749956dd408fd7ebb3c552">llvm::LiveRange::join</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a8ab989120222d67308b4e03b2772fb6a">llvm::SplitEditor::leaveIntvAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a9899a3945a73e70c7bb2800ef3865017">llvm::SplitEditor::leaveIntvBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a92e17326c2170e889ae4390c56878b77">llvm::LiveRange::MergeValueNumberInto</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a825d7d6de0a8dc551a2845f353036b6a">llvm::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a687cab1756967efc8f0ce66105531755">llvm::LiveRange::RenumberValues</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#ad02cdb6766947f5b6254789d07cfb88e">anonymous{MachineVerifier.cpp}::MachineVerifier::report_context</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abc440c9fad640641c26ddae8c08dce82">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveRangeSegment</a>, <a href="#a5cdbcb31845858ea86bc50de705378c1">VNInfo</a> and <a href="#a4a12b509ba1b5967f2beec884eb17da9">VNInfo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
