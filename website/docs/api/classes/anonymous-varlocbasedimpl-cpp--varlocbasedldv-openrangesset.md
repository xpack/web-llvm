---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-varlocbasedimpl-cpp-/varlocbasedldv/openrangesset
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `OpenRangesSet` Class Reference

<p>This holds the working set of currently open ranges. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::OpenRangesSet { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dceaf6bf52f0ff59243f49e8aa87ca7">OpenRangesSet</a> (VarLocSet::Allocator &amp;Alloc, OverlapMap &amp;_OLapMap)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/anonymous-varlocbasedimpl-cpp-/#a0fcac79d5789c3482f72fdb2eb8d0a32">VarLocSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9e5820db43ad3529b087bdd793b8e65">getVarLocs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a78f2996c7ae1f3910c742a37d1cfcd">getUniqueVarLocs</a> (SmallVectorImpl&lt; VarLoc &gt; &amp;Collected, const VarLocMap &amp;VarLocIDs) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27b69a3b6f262b54e6c680f0d062b0e2">erase</a> (const VarLoc &amp;VL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Terminate all open ranges for VL.Var by removing it from the set. <a href="#a27b69a3b6f262b54e6c680f0d062b0e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2721244d3fd94f3f78b30fc987a4378">erase</a> (const VarLocsInRange &amp;KillSet, const VarLocMap &amp;VarLocIDs, LocIndex::u32_location_t Location)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Terminate all open ranges listed as indices in <span class="doxyComputerOutput">KillSet</span> with <span class="doxyComputerOutput">Location</span> by removing them from the set. <a href="#aa2721244d3fd94f3f78b30fc987a4378">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77875bf033ea52eec09c6bfe840cfe48">insert</a> (LocIndices VarLocIDs, const VarLoc &amp;VL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a new range into the set. <a href="#a77875bf033ea52eec09c6bfe840cfe48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dff86c7fb9ee02857e92f4762c8343d">insertFromLocSet</a> (const VarLocSet &amp;ToLoad, const VarLocMap &amp;Map)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a set of ranges. <a href="#a9dff86c7fb9ee02857e92f4762c8343d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-varlocbasedimpl-cpp-/#a1a71406009b70e55de914dc6374ce484">LocIndices</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c66a255f02fafbc4320d57459e8ed43">getEntryValueBackup</a> (DebugVariable Var)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a> <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of an entry value backup location, if it exists for the variable. <a href="#a8c66a255f02fafbc4320d57459e8ed43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae75ee6384188bdbb4a7b53d56c22c74e">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Empty the set. <a href="#ae75ee6384188bdbb4a7b53d56c22c74e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4a416fc1d2a6deaf3c56e35ae4da60d">empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether the set is empty or not. <a href="#ab4a416fc1d2a6deaf3c56e35ae4da60d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">auto</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b9d888d2754a53709924480be1ea64e">getEmptyVarLocRange</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an empty range of VarLoc IDs. <a href="#a6b9d888d2754a53709924480be1ea64e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">auto</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7c4250f50e1dc23a5db698a35e7d556">getRegisterVarLocs</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get all set IDs for VarLocs with MLs of kind RegisterKind in <span class="doxyComputerOutput">Reg</span>. <a href="#ae7c4250f50e1dc23a5db698a35e7d556">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">auto</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28f49319f5bd84152a82ccbbbe5b5942">getSpillVarLocs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get all set IDs for VarLocs with MLs of kind SpillLocKind. <a href="#a28f49319f5bd84152a82ccbbbe5b5942">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">auto</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a312f0f34b8346837346391e0d82c18a8">getEntryValueBackupVarLocs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get all set IDs for VarLocs of EVKind EntryValueBackupKind or EntryValueCopyBackupKind. <a href="#a312f0f34b8346837346391e0d82c18a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">auto</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab503328fee3bc3754ca1787a5109f8ec">getWasmVarLocs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get all set IDs for VarLocs with MLs of kind WasmLocKind. <a href="#ab503328fee3bc3754ca1787a5109f8ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/coalescingbitvector/#a56416744b3c83246a55d0890507b0654">VarLocSet::Allocator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1be744fa3f570ca658b22f749a166244">Alloc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-varlocbasedimpl-cpp-/#a0fcac79d5789c3482f72fdb2eb8d0a32">VarLocSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25d7a4383db3cc04bc8a772e79d6a6a2">VarLocs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-varlocbasedimpl-cpp-/#a1a71406009b70e55de914dc6374ce484">LocIndices</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a351e9cc3f27c8fda461aefb18bd1acb6">Vars</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-varlocbasedimpl-cpp-/#a1a71406009b70e55de914dc6374ce484">LocIndices</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab76af2058f50e2e673b62d8441fcb5fb">EntryValuesBackupVars</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">OverlapMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14f6d292fb22fc1a62b37573deb03b80">OverlappingFragments</a></td>
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

<p>This holds the working set of currently open ranges.</p>


<p>For fast access, this is done both as a set of VarLocIDs, and a map of <a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a> to recent VarLocID. Note that a DBG_VALUE ends all previous open ranges for the same variable. In addition, we keep two different maps (Vars/EntryValuesBackupVars), so erase/insert methods act differently depending on whether a VarLoc is primary location or backup one. In the case the VarLoc is backup location we will erase/insert from the EntryValuesBackupVars map, otherwise we perform the operation on the Vars.</p>


<p>Definition at line 897 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### OpenRangesSet() {#a1dceaf6bf52f0ff59243f49e8aa87ca7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::OpenRangesSet::OpenRangesSet (<a href="/web-llvm/docs/api/classes/llvm/coalescingbitvector/#a56416744b3c83246a55d0890507b0654">VarLocSet::Allocator</a> &amp; Alloc, <a href="/web-llvm/docs/api/classes/llvm/densemap">OverlapMap</a> &amp; _OLapMap)</td>
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



<p>Definition at line 907 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clear() {#ae75ee6384188bdbb4a7b53d56c22c74e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::OpenRangesSet::clear ()</td>
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

<p>Empty the set.</p>

<p>Definition at line 939 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### empty() {#ab4a416fc1d2a6deaf3c56e35ae4da60d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::OpenRangesSet::empty ()</td>
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

<p>Return whether the set is empty or not.</p>

<p>Definition at line 946 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### erase() {#a27b69a3b6f262b54e6c680f0d062b0e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VarLocBasedLDV::OpenRangesSet::erase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> VarLoc &amp; VL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Terminate all open ranges for VL.Var by removing it from the set.</p>


<p>Erase a variable from the set of open ranges, and additionally erase any fragments that may overlap it.</p>


<p>If the VarLoc is a backup location, erase the variable from the EntryValuesBackupVars set, indicating we should stop tracking its backup entry location. Otherwise, if the VarLoc is primary location, erase the variable from the Vars set.</p>


<p>Definition at line 923 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### erase() {#aa2721244d3fd94f3f78b30fc987a4378}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VarLocBasedLDV::OpenRangesSet::erase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/anonymous-varlocbasedimpl-cpp-/#ad2d1326e7d856e0dd89105bec90546b2">VarLocsInRange</a> &amp; KillSet, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> VarLocMap &amp; VarLocIDs, <a href="/web-llvm/docs/api/structs/anonymous-varlocbasedimpl-cpp-/locindex/#a626afd7de7fed611fa6307b8d3f40f6f">LocIndex::u32_location_t</a> Location)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Terminate all open ranges listed as indices in <span class="doxyComputerOutput">KillSet</span> with <span class="doxyComputerOutput">Location</span> by removing them from the set.</p>

<p>Definition at line 927 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### getEmptyVarLocRange() {#a6b9d888d2754a53709924480be1ea64e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::OpenRangesSet::getEmptyVarLocRange ()</td>
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

<p>Get an empty range of VarLoc IDs.</p>

<p>Definition at line 954 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### getEntryValueBackup() {#a8c66a255f02fafbc4320d57459e8ed43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; LocIndices &gt; VarLocBasedLDV::OpenRangesSet::getEntryValueBackup (<a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a> Var)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a> <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of an entry value backup location, if it exists for the variable.</p>

<p>Definition at line 936 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### getEntryValueBackupVarLocs() {#a312f0f34b8346837346391e0d82c18a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::OpenRangesSet::getEntryValueBackupVarLocs ()</td>
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

<p>Get all set IDs for VarLocs of EVKind EntryValueBackupKind or EntryValueCopyBackupKind.</p>

<p>Definition at line 972 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### getRegisterVarLocs() {#ae7c4250f50e1dc23a5db698a35e7d556}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::OpenRangesSet::getRegisterVarLocs (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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

<p>Get all set IDs for VarLocs with MLs of kind RegisterKind in <span class="doxyComputerOutput">Reg</span>.</p>

<p>Definition at line 960 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### getSpillVarLocs() {#a28f49319f5bd84152a82ccbbbe5b5942}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::OpenRangesSet::getSpillVarLocs ()</td>
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

<p>Get all set IDs for VarLocs with MLs of kind SpillLocKind.</p>

<p>Definition at line 965 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### getUniqueVarLocs() {#a2a78f2996c7ae1f3910c742a37d1cfcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::OpenRangesSet::getUniqueVarLocs (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; VarLoc &gt; &amp; Collected, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> VarLocMap &amp; VarLocIDs)</td>
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



<p>Definition at line 917 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### getVarLocs() {#ac9e5820db43ad3529b087bdd793b8e65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VarLocSet &amp; anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::OpenRangesSet::getVarLocs ()</td>
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



<p>Definition at line 910 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### getWasmVarLocs() {#ab503328fee3bc3754ca1787a5109f8ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::OpenRangesSet::getWasmVarLocs ()</td>
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

<p>Get all set IDs for VarLocs with MLs of kind WasmLocKind.</p>

<p>Definition at line 978 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### insert() {#a77875bf033ea52eec09c6bfe840cfe48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VarLocBasedLDV::OpenRangesSet::insert (<a href="/web-llvm/docs/api/namespaces/anonymous-varlocbasedimpl-cpp-/#a1a71406009b70e55de914dc6374ce484">LocIndices</a> VarLocIDs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> VarLoc &amp; VL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a new range into the set.</p>

<p>Definition at line 931 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### insertFromLocSet() {#a9dff86c7fb9ee02857e92f4762c8343d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VarLocBasedLDV::OpenRangesSet::insertFromLocSet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/anonymous-varlocbasedimpl-cpp-/#a0fcac79d5789c3482f72fdb2eb8d0a32">VarLocSet</a> &amp; ToLoad, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> VarLocMap &amp; Map)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a set of ranges.</p>

<p>Definition at line 934 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Alloc {#a1be744fa3f570ca658b22f749a166244}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VarLocSet::Allocator&amp; anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::OpenRangesSet::Alloc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 898 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### EntryValuesBackupVars {#ab76af2058f50e2e673b62d8441fcb5fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;DebugVariable, LocIndices, 8&gt; anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::OpenRangesSet::EntryValuesBackupVars</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 903 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### OverlappingFragments {#a14f6d292fb22fc1a62b37573deb03b80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OverlapMap&amp; anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::OpenRangesSet::OverlappingFragments</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 904 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### VarLocs {#a25d7a4383db3cc04bc8a772e79d6a6a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VarLocSet anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::OpenRangesSet::VarLocs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 899 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### Vars {#a351e9cc3f27c8fda461aefb18bd1acb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;DebugVariable, LocIndices, 8&gt; anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::OpenRangesSet::Vars</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 901 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
