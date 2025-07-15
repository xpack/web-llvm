---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/liverangeupdater
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LiveRangeUpdater` Class Reference

<p>Helper class for performant <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> bulk updates. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LiveRangeUpdater { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">llvm/CodeGen/LiveInterval.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f8850300c47772d8ae8a70aab6b1996">LiveRangeUpdater</a> (LiveRange *lr=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/liverangeupdater">LiveRangeUpdater</a> for adding segments to LR. <a href="#a7f8850300c47772d8ae8a70aab6b1996">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a3dc9d6e73e31dfbdb2db64f84d3375">~LiveRangeUpdater</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecdfedd0173a7d04cd7d06d4538dc7bc">add</a> (LiveRange::Segment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a segment to LR and coalesce when possible, just like LR.addSegment(). <a href="#aecdfedd0173a7d04cd7d06d4538dc7bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a974ca80102947b3f8400a70c2b36955b">add</a> (SlotIndex Start, SlotIndex End, VNInfo *VNI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf0968cd0258e86bc58fd76e50e57735">isDirty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the LR is currently in an invalid state, and <a href="#a3743aaad6337d6a4c483f6c19efa3894">flush()</a> needs to be called. <a href="#aaf0968cd0258e86bc58fd76e50e57735">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3743aaad6337d6a4c483f6c19efa3894">flush</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flush the updater state to LR so it is valid and contains all added segments. <a href="#a3743aaad6337d6a4c483f6c19efa3894">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dd8f1129a87977ed69082192cbf3d39">setDest</a> (LiveRange *lr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Select a different destination live range. <a href="#a2dd8f1129a87977ed69082192cbf3d39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab496f1c444abc230c42f2c6128ec0a8f">getDest</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the current destination live range. <a href="#ab496f1c444abc230c42f2c6128ec0a8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99dba5518021b799c8eb62367b225919">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a020de47777d0d24a6eecf4013ea95adf">print</a> (raw_ostream &amp;) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ce65cbe6ab5b9619c5d66080635fece">mergeSpills</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b12c9e10eaff08fe13d977e8558d3f0">LR</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee66c577bdd282ab25314c89f7bf2016">LastStart</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liverange/#a143c1fcb6066cb301f828ec4c18d79f4">LiveRange::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63fb6c30a9ee317d564f02827420b635">WriteI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liverange/#a143c1fcb6066cb301f828ec4c18d79f4">LiveRange::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44ebb869f95bdd54e3ce899bd2957810">ReadI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/liverange/segment">LiveRange::Segment</a>, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf233fa3e162169a7f81f13dbb905380">Spills</a></td>
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

<p>Helper class for performant <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> bulk updates.</p>


<p>Calling <a href="/web-llvm/docs/api/classes/llvm/liverange/#a0b73c8d5ae32ca13dd02ddde86ffd0a2">LiveRange::addSegment()</a> repeatedly can be expensive on large live ranges because segments after the insertion point may need to be shifted. The <a href="/web-llvm/docs/api/classes/llvm/liverangeupdater">LiveRangeUpdater</a> class can defer the shifting when adding many segments in order.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> will be in an invalid state until <a href="#a3743aaad6337d6a4c483f6c19efa3894">flush()</a> is called.</p>


<p>Definition at line 943 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LiveRangeUpdater() {#a7f8850300c47772d8ae8a70aab6b1996}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LiveRangeUpdater::LiveRangeUpdater (<a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> * lr=nullptr)</td>
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

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/liverangeupdater">LiveRangeUpdater</a> for adding segments to LR.</p>


<p>LR will temporarily be in an invalid state until <a href="#a3743aaad6337d6a4c483f6c19efa3894">flush()</a> is called.</p>


<p>Definition at line 954 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~LiveRangeUpdater() {#a4a3dc9d6e73e31dfbdb2db64f84d3375}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LiveRangeUpdater::~LiveRangeUpdater ()</td>
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



<p>Definition at line 956 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Reference <a href="#a3743aaad6337d6a4c483f6c19efa3894">flush</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#aecdfedd0173a7d04cd7d06d4538dc7bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRangeUpdater::add (<a href="/web-llvm/docs/api/structs/llvm/liverange/segment">LiveRange::Segment</a> Seg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a segment to LR and coalesce when possible, just like LR.addSegment().</p>


<p>Segments should be added in increasing start order for best performance.</p>


<p>Declaration at line 961 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 1190 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp/#aa4faced2370f119031286fae5b5f2a5c">coalescable</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a757fd6afba0f531db70e78e057d147c6">llvm::LiveRange::end</a>, <a href="/web-llvm/docs/api/structs/llvm/liverange/segment/#afe8e59ffc86cb1736116e4dc8b86e26f">llvm::LiveRange::Segment::end</a>, <a href="#a3743aaad6337d6a4c483f6c19efa3894">flush</a>, <a href="#aaf0968cd0258e86bc58fd76e50e57735">isDirty</a>, <a href="/web-llvm/docs/api/structs/llvm/liverange/segment/#a85f7bf79596d84273b5b3b9b490bc2ec">llvm::LiveRange::Segment::start</a> and <a href="/web-llvm/docs/api/structs/llvm/liverange/segment/#ac3d1b43d371bc68742232ec51d4a6321">llvm::LiveRange::Segment::valno</a>.</p>


<p>Referenced by <a href="#a974ca80102947b3f8400a70c2b36955b">add</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a2b10543d5f749956dd408fd7ebb3c552">llvm::LiveRange::join</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#aae51d91c7cb4dc1a4ffabbfd1b7be9a1">llvm::LiveRange::MergeSegmentsInAsValue</a> and <a href="/web-llvm/docs/api/classes/llvm/liverange/#a325a4ec9c33a3dead9ff01c9e70fd534">llvm::LiveRange::MergeValueInAsValue</a>.</p>

</div>
</div>

### add() {#a974ca80102947b3f8400a70c2b36955b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveRangeUpdater::add (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Start, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> End, <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * VNI)</td>
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



<p>Definition at line 963 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Reference <a href="#aecdfedd0173a7d04cd7d06d4538dc7bc">add</a>.</p>

</div>
</div>

### dump() {#a99dba5518021b799c8eb62367b225919}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void LiveRangeUpdater::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 985 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 1173 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="/web-llvm/docs/api/classes/llvm/liverange/#af62a3dfb9ce9b78c94e7b910a02b28cf">llvm::LiveRange::print</a>.</p>

</div>
</div>

### flush() {#a3743aaad6337d6a4c483f6c19efa3894}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRangeUpdater::flush ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flush the updater state to LR so it is valid and contains all added segments.</p>

<p>Declaration at line 973 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 1297 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aaf0968cd0258e86bc58fd76e50e57735">isDirty</a>.</p>


<p>Referenced by <a href="#aecdfedd0173a7d04cd7d06d4538dc7bc">add</a>, <a href="#a2dd8f1129a87977ed69082192cbf3d39">setDest</a> and <a href="#a4a3dc9d6e73e31dfbdb2db64f84d3375">~LiveRangeUpdater</a>.</p>

</div>
</div>

### getDest() {#ab496f1c444abc230c42f2c6128ec0a8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRange * llvm::LiveRangeUpdater::getDest ()</td>
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

<p>Get the current destination live range.</p>

<p>Definition at line 983 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

### isDirty() {#aaf0968cd0258e86bc58fd76e50e57735}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveRangeUpdater::isDirty ()</td>
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

<p>Return true if the LR is currently in an invalid state, and <a href="#a3743aaad6337d6a4c483f6c19efa3894">flush()</a> needs to be called.</p>

<p>Definition at line 969 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Referenced by <a href="#aecdfedd0173a7d04cd7d06d4538dc7bc">add</a>, <a href="#a3743aaad6337d6a4c483f6c19efa3894">flush</a>, <a href="#a020de47777d0d24a6eecf4013ea95adf">print</a> and <a href="#a2dd8f1129a87977ed69082192cbf3d39">setDest</a>.</p>

</div>
</div>

### print() {#a020de47777d0d24a6eecf4013ea95adf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRangeUpdater::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 986 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 1150 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#aaf0968cd0258e86bc58fd76e50e57735">isDirty</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### setDest() {#a2dd8f1129a87977ed69082192cbf3d39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveRangeUpdater::setDest (<a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> * lr)</td>
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

<p>Select a different destination live range.</p>

<p>Definition at line 976 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="#a3743aaad6337d6a4c483f6c19efa3894">flush</a> and <a href="#aaf0968cd0258e86bc58fd76e50e57735">isDirty</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### mergeSpills() {#a0ce65cbe6ab5b9619c5d66080635fece}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRangeUpdater::mergeSpills ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 949 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 1274 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LastStart {#aee66c577bdd282ab25314c89f7bf2016}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::LiveRangeUpdater::LastStart</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 945 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

### LR {#a0b12c9e10eaff08fe13d977e8558d3f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRange* llvm::LiveRangeUpdater::LR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 944 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

### ReadI {#a44ebb869f95bdd54e3ce899bd2957810}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRange::iterator llvm::LiveRangeUpdater::ReadI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 947 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

### Spills {#adf233fa3e162169a7f81f13dbb905380}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;LiveRange::Segment, 16&gt; llvm::LiveRangeUpdater::Spills</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 948 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

### WriteI {#a63fb6c30a9ee317d564f02827420b635}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRange::iterator llvm::LiveRangeUpdater::WriteI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 946 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
