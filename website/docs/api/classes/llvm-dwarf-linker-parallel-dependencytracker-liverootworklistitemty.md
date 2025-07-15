---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf-linker/parallel/dependencytracker/liverootworklistitemty
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LiveRootWorklistItemTy` Class Reference

<p>Class keeping live worklist item data. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::dwarf_linker::parallel::DependencyTracker::LiveRootWorklistItemTy { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DWARFLinker/Parallel/DependencyTracker.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b3905f0edc2524a3a1f085ba65f4384">LiveRootWorklistItemTy</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13929917503b39ea538309b36a24ac79">LiveRootWorklistItemTy</a> (const LiveRootWorklistItemTy &amp;)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a605e1f6e432a87442769291a182cff34">LiveRootWorklistItemTy</a> (LiveRootWorklistActionTy Action, UnitEntryPairTy RootEntry)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab27ce3d3d7b6ba054c4e09abdec45476">LiveRootWorklistItemTy</a> (LiveRootWorklistActionTy Action, UnitEntryPairTy RootEntry, UnitEntryPairTy ReferencedBy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6591460eefa46122282d50c68a82397b">getRootEntry</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5270021419d157f502aba678e1ee8549">CompileUnit::DieOutputPlacement</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef62a193fbeea10e3ec64ee56c31a2b3">getPlacement</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8de76b51e353f26b23bec4c2bddd357">hasReferencedByOtherEntry</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03f3665b37eb52ac2e0b99dc3a671fbf">getReferencedByEntry</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#acb3226f07be871308b3ebc1fe2e22ad8">LiveRootWorklistActionTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae96ecbe1f7161c18bab554e554654e08">getAction</a> () const</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> *, 3, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#acb3226f07be871308b3ebc1fe2e22ad8">LiveRootWorklistActionTy</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dependencytracker/liverootworklistitemty/compileunitpointertraits">CompileUnitPointerTraits</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a637e46c2326a3e5ab947419ffdf91a1c">RootCU</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7f6fbba27e7887118c893bc4246e915">RootDieEntry</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac36631a8d5183068ea83f82765333ccf">ReferencedByCU</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Another root entry which references this RootDieEntry. <a href="#ac36631a8d5183068ea83f82765333ccf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d32dab5d97f9ce61a5810b7e4fd4723">ReferencedByDieEntry</a> = nullptr</td>
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

<p>Class keeping live worklist item data.</p>

<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LiveRootWorklistItemTy() {#a3b3905f0edc2524a3a1f085ba65f4384}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::DependencyTracker::LiveRootWorklistItemTy::LiveRootWorklistItemTy ()</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>.</p>


<p>Referenced by <a href="#a13929917503b39ea538309b36a24ac79">LiveRootWorklistItemTy</a>.</p>

</div>
</div>

### LiveRootWorklistItemTy() {#a13929917503b39ea538309b36a24ac79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::DependencyTracker::LiveRootWorklistItemTy::LiveRootWorklistItemTy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/liverootworklistitemty">LiveRootWorklistItemTy</a> &amp;)</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>.</p>


<p>Reference <a href="#a3b3905f0edc2524a3a1f085ba65f4384">LiveRootWorklistItemTy</a>.</p>

</div>
</div>

### LiveRootWorklistItemTy() {#a605e1f6e432a87442769291a182cff34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::DependencyTracker::LiveRootWorklistItemTy::LiveRootWorklistItemTy (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#acb3226f07be871308b3ebc1fe2e22ad8">LiveRootWorklistActionTy</a> Action, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> RootEntry)</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty/#a52b782888847c9ffd3c67ff187783af0">llvm::dwarf_linker::parallel::UnitEntryPairTy::CU</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty/#af5c2b2cb0d8ba2bd1233b6482d15f36d">llvm::dwarf_linker::parallel::UnitEntryPairTy::DieEntry</a>, <a href="#a637e46c2326a3e5ab947419ffdf91a1c">RootCU</a> and <a href="#ad7f6fbba27e7887118c893bc4246e915">RootDieEntry</a>.</p>

</div>
</div>

### LiveRootWorklistItemTy() {#ab27ce3d3d7b6ba054c4e09abdec45476}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::DependencyTracker::LiveRootWorklistItemTy::LiveRootWorklistItemTy (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#acb3226f07be871308b3ebc1fe2e22ad8">LiveRootWorklistActionTy</a> Action, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> RootEntry, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> ReferencedBy)</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty/#a52b782888847c9ffd3c67ff187783af0">llvm::dwarf_linker::parallel::UnitEntryPairTy::CU</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty/#af5c2b2cb0d8ba2bd1233b6482d15f36d">llvm::dwarf_linker::parallel::UnitEntryPairTy::DieEntry</a>, <a href="#ac36631a8d5183068ea83f82765333ccf">ReferencedByCU</a>, <a href="#a7d32dab5d97f9ce61a5810b7e4fd4723">ReferencedByDieEntry</a>, <a href="#a637e46c2326a3e5ab947419ffdf91a1c">RootCU</a> and <a href="#ad7f6fbba27e7887118c893bc4246e915">RootDieEntry</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAction() {#ae96ecbe1f7161c18bab554e554654e08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRootWorklistActionTy llvm::dwarf_linker::parallel::DependencyTracker::LiveRootWorklistItemTy::getAction ()</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>.</p>


<p>Reference <a href="#a637e46c2326a3e5ab947419ffdf91a1c">RootCU</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#a29cd2bdde62b64762aa4c406eff8618f">llvm::dwarf_linker::parallel::DependencyTracker::markCollectedLiveRootsAsKept</a>.</p>

</div>
</div>

### getPlacement() {#aef62a193fbeea10e3ec64ee56c31a2b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CompileUnit::DieOutputPlacement llvm::dwarf_linker::parallel::DependencyTracker::LiveRootWorklistItemTy::getPlacement ()</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>.</p>


<p>Reference <a href="#a637e46c2326a3e5ab947419ffdf91a1c">RootCU</a>.</p>

</div>
</div>

### getReferencedByEntry() {#a03f3665b37eb52ac2e0b99dc3a671fbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UnitEntryPairTy llvm::dwarf_linker::parallel::DependencyTracker::LiveRootWorklistItemTy::getReferencedByEntry ()</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac36631a8d5183068ea83f82765333ccf">ReferencedByCU</a> and <a href="#a7d32dab5d97f9ce61a5810b7e4fd4723">ReferencedByDieEntry</a>.</p>

</div>
</div>

### getRootEntry() {#a6591460eefa46122282d50c68a82397b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UnitEntryPairTy llvm::dwarf_linker::parallel::DependencyTracker::LiveRootWorklistItemTy::getRootEntry ()</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>.</p>


<p>References <a href="#a637e46c2326a3e5ab947419ffdf91a1c">RootCU</a> and <a href="#ad7f6fbba27e7887118c893bc4246e915">RootDieEntry</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#a29cd2bdde62b64762aa4c406eff8618f">llvm::dwarf_linker::parallel::DependencyTracker::markCollectedLiveRootsAsKept</a>.</p>

</div>
</div>

### hasReferencedByOtherEntry() {#af8de76b51e353f26b23bec4c2bddd357}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::parallel::DependencyTracker::LiveRootWorklistItemTy::hasReferencedByOtherEntry ()</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>.</p>


<p>Reference <a href="#ac36631a8d5183068ea83f82765333ccf">ReferencedByCU</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#a29cd2bdde62b64762aa4c406eff8618f">llvm::dwarf_linker::parallel::DependencyTracker::markCollectedLiveRootsAsKept</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### ReferencedByCU {#ac36631a8d5183068ea83f82765333ccf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CompileUnit* llvm::dwarf_linker::parallel::DependencyTracker::LiveRootWorklistItemTy::ReferencedByCU = nullptr</td>
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

<p>Another root entry which references this RootDieEntry.</p>


<p>ReferencedByDieEntry is kept to update placement. if RootDieEntry has placement incompatible with placement of ReferencedByDieEntry then it should be updated.</p>


<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>.</p>


<p>Referenced by <a href="#a03f3665b37eb52ac2e0b99dc3a671fbf">getReferencedByEntry</a>, <a href="#af8de76b51e353f26b23bec4c2bddd357">hasReferencedByOtherEntry</a> and <a href="#ab27ce3d3d7b6ba054c4e09abdec45476">LiveRootWorklistItemTy</a>.</p>

</div>
</div>

### ReferencedByDieEntry {#a7d32dab5d97f9ce61a5810b7e4fd4723}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugInfoEntry* llvm::dwarf_linker::parallel::DependencyTracker::LiveRootWorklistItemTy::ReferencedByDieEntry = nullptr</td>
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



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>.</p>


<p>Referenced by <a href="#a03f3665b37eb52ac2e0b99dc3a671fbf">getReferencedByEntry</a> and <a href="#ab27ce3d3d7b6ba054c4e09abdec45476">LiveRootWorklistItemTy</a>.</p>

</div>
</div>

### RootCU {#a637e46c2326a3e5ab947419ffdf91a1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerIntPair&lt;CompileUnit *, 3, LiveRootWorklistActionTy, CompileUnitPointerTraits&gt; llvm::dwarf_linker::parallel::DependencyTracker::LiveRootWorklistItemTy::RootCU</td>
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



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>.</p>


<p>Referenced by <a href="#ae96ecbe1f7161c18bab554e554654e08">getAction</a>, <a href="#aef62a193fbeea10e3ec64ee56c31a2b3">getPlacement</a>, <a href="#a6591460eefa46122282d50c68a82397b">getRootEntry</a>, <a href="#a605e1f6e432a87442769291a182cff34">LiveRootWorklistItemTy</a> and <a href="#ab27ce3d3d7b6ba054c4e09abdec45476">LiveRootWorklistItemTy</a>.</p>

</div>
</div>

### RootDieEntry {#ad7f6fbba27e7887118c893bc4246e915}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugInfoEntry* llvm::dwarf_linker::parallel::DependencyTracker::LiveRootWorklistItemTy::RootDieEntry = nullptr</td>
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



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>.</p>


<p>Referenced by <a href="#a6591460eefa46122282d50c68a82397b">getRootEntry</a>, <a href="#a605e1f6e432a87442769291a182cff34">LiveRootWorklistItemTy</a> and <a href="#ab27ce3d3d7b6ba054c4e09abdec45476">LiveRootWorklistItemTy</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
