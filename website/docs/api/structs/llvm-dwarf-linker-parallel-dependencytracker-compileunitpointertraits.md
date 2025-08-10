---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dwarf-linker/parallel/dependencytracker/compileunitpointertraits
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `CompileUnitPointerTraits` Struct

<p>Pointer traits for <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::dwarf_linker::parallel::DependencyTracker::CompileUnitPointerTraits { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DWARFLinker/Parallel/DependencyTracker.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d548ea7f0fe6f6f3363a5d19593298a">getAsVoidPointer</a> (CompileUnit *P)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a327c02fc1ad75a54d17615c6b58590b9">getFromVoidPointer</a> (void *P)</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae39ecf317e218a769add75bb8c3c66c1">NumLowBitsAvailable</a> = 3</td>
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

<p>Pointer traits for <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the specified action affects only Root entry itself and does not affect it`s children. */ bool isSingleAction(LiveRootWorklistActionTy Action) { switch (Action) { default: return false;</p></dd>
</dl>


<p>case <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#acb3226f07be871308b3ebc1fe2e22ad8a5f0d4ecd2ea6dda3c5bc99cf667fedfa">LiveRootWorklistActionTy::MarkSingleLiveEntry</a>: case <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#acb3226f07be871308b3ebc1fe2e22ad8a4b0413e0a4858e280698bd82ada3d3f0">LiveRootWorklistActionTy::MarkSingleTypeEntry</a>: return true; } }</p>


<p>/**</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the specified action affects only Root entry itself and does not affect it`s children. */ bool isChildrenAction(LiveRootWorklistActionTy Action) { switch (Action) { default: return false;</p></dd>
</dl>


<p>case <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#acb3226f07be871308b3ebc1fe2e22ad8a76f7c22e7afa4d9203192b924b1d2447">LiveRootWorklistActionTy::MarkLiveChildrenRec</a>: case <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#acb3226f07be871308b3ebc1fe2e22ad8a8cdcce5d067ca8d256189c00ccf279cd">LiveRootWorklistActionTy::MarkTypeChildrenRec</a>: return true; } }</p>


<p>/ Class keeping live worklist item data. class LiveRootWorklistItemTy { public: LiveRootWorklistItemTy() = default; LiveRootWorklistItemTy(const LiveRootWorklistItemTy &amp;) = default; LiveRootWorklistItemTy(LiveRootWorklistActionTy Action,
                           UnitEntryPairTy RootEntry) { RootCU.setInt(Action); RootCU.setPointer(RootEntry.CU);</p>


<p>RootDieEntry = RootEntry.DieEntry; } LiveRootWorklistItemTy(LiveRootWorklistActionTy Action,
                           UnitEntryPairTy RootEntry,
                           UnitEntryPairTy ReferencedBy) { RootCU.setPointer(RootEntry.CU); RootCU.setInt(Action); RootDieEntry = RootEntry.DieEntry;</p>


<p>ReferencedByCU = ReferencedBy.CU; ReferencedByDieEntry = ReferencedBy.DieEntry; }</p>


<p><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> getRootEntry() const { return <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a>{RootCU.getPointer(), RootDieEntry}; }</p>


<p><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5270021419d157f502aba678e1ee8549">CompileUnit::DieOutputPlacement</a> getPlacement() const { return static_cast&lt;CompileUnit::DieOutputPlacement&gt;(RootCU.getInt()); }</p>


<p>bool hasReferencedByOtherEntry() const { return ReferencedByCU != nullptr; }</p>


<p><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> getReferencedByEntry() const { assert(ReferencedByCU); assert(ReferencedByDieEntry); return <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a>{ReferencedByCU, ReferencedByDieEntry}; }</p>


<p><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#acb3226f07be871308b3ebc1fe2e22ad8">LiveRootWorklistActionTy</a> getAction() const { return static_cast&lt;LiveRootWorklistActionTy&gt;(RootCU.getInt()); }</p>


<p>protected: /** Root entry. ASSUMPTION: 3 bits are used to store <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#acb3226f07be871308b3ebc1fe2e22ad8">LiveRootWorklistActionTy</a> value. Thus <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#acb3226f07be871308b3ebc1fe2e22ad8">LiveRootWorklistActionTy</a> should have no more eight elements.</p>


<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### getAsVoidPointer() {#a3d548ea7f0fe6f6f3363a5d19593298a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::dwarf_linker::parallel::DependencyTracker::CompileUnitPointerTraits::getAsVoidPointer (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> * P)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### getFromVoidPointer() {#a327c02fc1ad75a54d17615c6b58590b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CompileUnit * llvm::dwarf_linker::parallel::DependencyTracker::CompileUnitPointerTraits::getFromVoidPointer (void * P)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### NumLowBitsAvailable {#ae39ecf317e218a769add75bb8c3c66c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::dwarf_linker::parallel::DependencyTracker::CompileUnitPointerTraits::NumLowBitsAvailable = 3</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
