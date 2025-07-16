---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf-linker/parallel/dependencytracker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DependencyTracker` Class Reference

<p>This class discovers DIEs dependencies: marks "live" DIEs, marks <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> locations (whether <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> should be cloned as regular <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> or it should be put into the artificial type unit). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::dwarf_linker::parallel::DependencyTracker { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DWARFLinker/Parallel/DependencyTracker.h</a>"
</div>

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2ba7d664d32a10e2f1916898da07694">RootEntriesListTy</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; LiveRootWorklistItemTy &gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LiveRootWorklistActionTy : uint8_t { <a href="#acb3226f07be871308b3ebc1fe2e22ad8">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9da477812f655ba4a4e3f54921d8844e">DependencyTracker</a> (CompileUnit &amp;CU)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac29d7dd5c7ba980d5a368339b4fc03af">resolveDependenciesAndMarkLiveness</a> (bool InterCUProcessingStarted, std::atomic&lt; bool &gt; &amp;HasNewInterconnectedCUs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively walk the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a></span> tree and look for DIEs to keep. <a href="#ac29d7dd5c7ba980d5a368339b4fc03af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af28b850047c908b6602c0783a0c4688f">updateDependenciesCompleteness</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if dependencies have incompatible placement. <a href="#af28b850047c908b6602c0783a0c4688f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a066fd5533813e5df6d52cb59fc8afd4e">verifyKeepChain</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively walk the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a></span> tree and check "keepness" and "placement" information. <a href="#a066fd5533813e5df6d52cb59fc8afd4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b4a1d2b759deb0cb3917f4ad33c2ca1">isLiveAction</a> (LiveRootWorklistActionTy Action)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a713ff4f56c059b816949d50ba30e4fc6">isTypeAction</a> (LiveRootWorklistActionTy Action)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecab109879b9f476fec35ab74cfd690b">collectRootsToKeep</a> (const UnitEntryPairTy &amp;Entry, std::optional&lt; UnitEntryPairTy &gt; ReferencedBy, bool IsLiveParent)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function navigates DIEs tree starting from specified <span class="doxyComputerOutput">Entry</span>. <a href="#aecab109879b9f476fec35ab74cfd690b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29cd2bdde62b64762aa4c406eff8618f">markCollectedLiveRootsAsKept</a> (bool InterCUProcessingStarted, std::atomic&lt; bool &gt; &amp;HasNewInterconnectedCUs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Examine worklist and mark all 'root <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>'s as kept and set "Placement" property. <a href="#a29cd2bdde62b64762aa4c406eff8618f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99ca361384a0bc6e5fe805b3050ced95">markDIEEntryAsKeptRec</a> (LiveRootWorklistActionTy Action, const UnitEntryPairTy &amp;RootEntry, const UnitEntryPairTy &amp;Entry, bool InterCUProcessingStarted, std::atomic&lt; bool &gt; &amp;HasNewInterconnectedCUs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark whole <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> tree as kept recursively. <a href="#a99ca361384a0bc6e5fe805b3050ced95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a137ba2e95278852dbeb5d4b7a372b3a3">markParentsAsKeepingChildren</a> (const UnitEntryPairTy &amp;Entry)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark parents as keeping children. <a href="#a137ba2e95278852dbeb5d4b7a372b3a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa664f05184b8e7e5101de50bf18ccc99">setPlainDwarfPlacementRec</a> (const UnitEntryPairTy &amp;Entry)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark whole <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> tree as placed in "PlainDwarf". <a href="#aa664f05184b8e7e5101de50bf18ccc99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42ebac4ef7af0fc75e5f1a36dccd169a">maybeAddReferencedRoots</a> (LiveRootWorklistActionTy Action, const UnitEntryPairTy &amp;RootEntry, const UnitEntryPairTy &amp;Entry, bool InterCUProcessingStarted, std::atomic&lt; bool &gt; &amp;HasNewInterconnectedCUs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> referenced DIEs and add them into the worklist. <a href="#a42ebac4ef7af0fc75e5f1a36dccd169a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d4d1ef3bbae56f8ec7ac95bb5320146">isTypeTableCandidate</a> (const DWARFDebugInfoEntry *DIEEntry)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18df788a6ff9a2938e7ce3353609dba8">getRootForSpecifiedEntry</a> (UnitEntryPairTy Entry)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab611f3c12ccf9485de74c6bb78aedb81">addActionToRootEntriesWorkList</a> (LiveRootWorklistActionTy Action, const UnitEntryPairTy &amp;Entry, std::optional&lt; UnitEntryPairTy &gt; ReferencedBy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add action item to the work list. <a href="#ab611f3c12ccf9485de74c6bb78aedb81">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> *, 3, <a href="#acb3226f07be871308b3ebc1fe2e22ad8">LiveRootWorklistActionTy</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dependencytracker/compileunitpointertraits">CompileUnitPointerTraits</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa411def72116744e4a23ebda2b9b9250">RootCU</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a948ffc10c192b2502908ae6a0aa6a082">RootDieEntry</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3823523700ff25bf711096e0e22578de">ReferencedByCU</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Another root entry which references this RootDieEntry. <a href="#a3823523700ff25bf711096e0e22578de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf99246a5f6c50057f9725ad80bebcd5">ReferencedByDieEntry</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4df77906fd480828f5af41e52e738538">CU</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa2ba7d664d32a10e2f1916898da07694">RootEntriesListTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab2d7f8a06a89d372e4cf7da8d45d499">RootEntriesWorkList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of entries which are 'root <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>'s. <a href="#aab2d7f8a06a89d372e4cf7da8d45d499">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa2ba7d664d32a10e2f1916898da07694">RootEntriesListTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06bc651ada60f19beefe066cf9d314a8">Dependencies</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of entries dependencies. <a href="#a06bc651ada60f19beefe066cf9d314a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9a57660f0db8e2b356c3ebccd34b063">isLiveVariableEntry</a> (const UnitEntryPairTy &amp;Entry, bool IsLiveParent)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if specified variable references live code section. <a href="#ac9a57660f0db8e2b356c3ebccd34b063">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abab9675572d9fe6ef8cf9674b1bab8f7">isLiveSubprogramEntry</a> (const UnitEntryPairTy &amp;Entry)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if specified subprogram references live code section. <a href="#abab9675572d9fe6ef8cf9674b1bab8f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class discovers DIEs dependencies: marks "live" DIEs, marks <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> locations (whether <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> should be cloned as regular <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> or it should be put into the artificial type unit).</p>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>.</p>


<div class="doxySectionDef">

## Protected Member Typedefs

### RootEntriesListTy {#aa2ba7d664d32a10e2f1916898da07694}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::dwarf_linker::parallel::DependencyTracker::RootEntriesListTy =  SmallVector&lt;LiveRootWorklistItemTy&gt;</td>
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



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### LiveRootWorklistActionTy {#acb3226f07be871308b3ebc1fe2e22ad8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::dwarf_linker::parallel::DependencyTracker::LiveRootWorklistActionTy : uint8_t</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MarkSingleLiveEntry<a id="acb3226f07be871308b3ebc1fe2e22ad8a5f0d4ecd2ea6dda3c5bc99cf667fedfa"></a></td>
<td class="doxyEnumItemDescription">Mark current item as live entry (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MarkSingleTypeEntry<a id="acb3226f07be871308b3ebc1fe2e22ad8a4b0413e0a4858e280698bd82ada3d3f0"></a></td>
<td class="doxyEnumItemDescription">Mark current item as type entry</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MarkLiveEntryRec<a id="acb3226f07be871308b3ebc1fe2e22ad8a787e7b5f110b542056c9ca685eb4dcbc"></a></td>
<td class="doxyEnumItemDescription">Mark current item and all its children as live entry</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MarkTypeEntryRec<a id="acb3226f07be871308b3ebc1fe2e22ad8a6a6c345844bef74add0fbf8063cbef2b"></a></td>
<td class="doxyEnumItemDescription">Mark current item and all its children as type entry</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MarkLiveChildrenRec<a id="acb3226f07be871308b3ebc1fe2e22ad8a76f7c22e7afa4d9203192b924b1d2447"></a></td>
<td class="doxyEnumItemDescription">Mark all children of current item as live entry</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MarkTypeChildrenRec<a id="acb3226f07be871308b3ebc1fe2e22ad8a8cdcce5d067ca8d256189c00ccf279cd"></a></td>
<td class="doxyEnumItemDescription">Mark all children of current item as type entry</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DependencyTracker() {#a9da477812f655ba4a4e3f54921d8844e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::DependencyTracker::DependencyTracker (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> &amp; CU)</td>
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



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### resolveDependenciesAndMarkLiveness() {#ac29d7dd5c7ba980d5a368339b4fc03af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependencyTracker::resolveDependenciesAndMarkLiveness (bool InterCUProcessingStarted, std::atomic&lt; bool &gt; &amp; HasNewInterconnectedCUs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recursively walk the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a></span> tree and look for DIEs to keep.</p>


<p>Store that information in <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/cu">CU</a>'s</span> DIEInfo.</p>


<p>This function is the entry point of the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> selection algorithm. It is expected to walk the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> tree and(through the mediation of Context.File.Addresses) ask for relocation adjustment value on each <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> that might be a 'root <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>'(f.e. subprograms, variables).</p>


<p>Returns true if all dependencies are correctly discovered. Inter-CU dependencies cannot be discovered if referenced <a href="/web-llvm/docs/api/namespaces/cu">CU</a> is not analyzed yet. If that is the case this method returns false.</p>


<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>, definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-cpp">DependencyTracker.cpp</a>.</p>


<p>References <a href="#aecab109879b9f476fec35ab74cfd690b">collectRootsToKeep</a>, <a href="#a29cd2bdde62b64762aa4c406eff8618f">markCollectedLiveRootsAsKept</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5270021419d157f502aba678e1ee8549aecc6950928c245961306947efbae3db7">llvm::dwarf_linker::parallel::CompileUnit::PlainDwarf</a>, <a href="#aab2d7f8a06a89d372e4cf7da8d45d499">RootEntriesWorkList</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/compileunit/dieinfo/#a29d892081e6d10f999dcf96f7a1b4729">llvm::dwarf_linker::parallel::CompileUnit::DIEInfo::setPlacement</a>.</p>

</div>
</div>

### updateDependenciesCompleteness() {#af28b850047c908b6602c0783a0c4688f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependencyTracker::updateDependenciesCompleteness ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if dependencies have incompatible placement.</p>


<p>If that is the case modify placement to be compatible.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if any placement was updated, otherwise returns false. This method should be called as a followup processing after <a href="#ac29d7dd5c7ba980d5a368339b4fc03af">resolveDependenciesAndMarkLiveness()</a>.</p></dd>
</dl>


<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>, definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-cpp">DependencyTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty/#a52b782888847c9ffd3c67ff187783af0">llvm::dwarf_linker::parallel::UnitEntryPairTy::CU</a>, <a href="#a06bc651ada60f19beefe066cf9d314a8">Dependencies</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty/#af5c2b2cb0d8ba2bd1233b6482d15f36d">llvm::dwarf_linker::parallel::UnitEntryPairTy::DieEntry</a>, <a href="/web-llvm/docs/api/groups/group/#ga3cc183d3d4b3e914db2998f157d22e8a">llvm::dwarf_linker::parallel::CompileUnit::getDIEInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/compileunit/dieinfo/#a4fb9f942a186fdee7f8665c5d3363ee3">llvm::dwarf_linker::parallel::CompileUnit::DIEInfo::needToPlaceInTypeTable</a> and <a href="#aa664f05184b8e7e5101de50bf18ccc99">setPlainDwarfPlacementRec</a>.</p>

</div>
</div>

### verifyKeepChain() {#a066fd5533813e5df6d52cb59fc8afd4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DependencyTracker::verifyKeepChain ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recursively walk the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a></span> tree and check "keepness" and "placement" information.</p>


<p>Verify the keep chain by looking for DIEs that are kept but who's parent isn't.</p>


<p>It is an error if parent node does not have "keep" flag, while child has one. It is an error if parent node has "TypeTable" placement while child has "PlainDwarf" placement. This function dump error at stderr in that case.</p>


<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-cpp">DependencyTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a1fa7cbc55eb0808d9fc434ef3efb5bca">llvm::DWARFDie::children</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/withcolor/#a59d59f7f8aa89b08f44ad6a87e8ebb1a">llvm::WithColor::error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a41fc5e2ca3d059c98029728b2677be44">llvm::DWARFDie::getDebugInfoEntry</a>, <a href="#abab9675572d9fe6ef8cf9674b1bab8f7">isLiveSubprogramEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#ae970d60ab52d996448bb030b4a0b67bc">llvm::DWARFDie::isValid</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/compileunit/dieinfo/#a29e5611206ac6f6a6c6fc7f570a368c4">llvm::dwarf_linker::parallel::CompileUnit::DIEInfo::needToKeepInPlainDwarf</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/compileunit/dieinfo/#a4fb9f942a186fdee7f8665c5d3363ee3">llvm::dwarf_linker::parallel::CompileUnit::DIEInfo::needToPlaceInTypeTable</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#ad97688dfe9cd802e2a0691cbe620218a">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::pop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### addActionToRootEntriesWorkList() {#ab611f3c12ccf9485de74c6bb78aedb81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DependencyTracker::addActionToRootEntriesWorkList (<a href="#acb3226f07be871308b3ebc1fe2e22ad8">LiveRootWorklistActionTy</a> Action, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> &amp; Entry, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> &gt; ReferencedBy)</td>
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

<p>Add action item to the work list.</p>

<p>Declaration at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>, definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-cpp">DependencyTracker.cpp</a>.</p>


<p>Reference <a href="#aab2d7f8a06a89d372e4cf7da8d45d499">RootEntriesWorkList</a>.</p>


<p>Referenced by <a href="#aecab109879b9f476fec35ab74cfd690b">collectRootsToKeep</a>, <a href="#a137ba2e95278852dbeb5d4b7a372b3a3">markParentsAsKeepingChildren</a> and <a href="#a42ebac4ef7af0fc75e5f1a36dccd169a">maybeAddReferencedRoots</a>.</p>

</div>
</div>

### collectRootsToKeep() {#aecab109879b9f476fec35ab74cfd690b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DependencyTracker::collectRootsToKeep (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> &amp; Entry, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> &gt; ReferencedBy, bool IsLiveParent)</td>
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

<p>This function navigates DIEs tree starting from specified <span class="doxyComputerOutput">Entry</span>.</p>


<p>It puts found 'root <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>' into the worklist. The <span class="doxyComputerOutput">CollectLiveEntries</span> instructs to collect either live roots(like subprograms having live
DW_AT_low_pc) or otherwise roots which is not live(they need to be collected if they are imported f.e. by DW_TAG_imported_module).</p>


<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>, definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-cpp">DependencyTracker.cpp</a>.</p>


<p>References <a href="#ab611f3c12ccf9485de74c6bb78aedb81">addActionToRootEntriesWorkList</a>, <a href="#aecab109879b9f476fec35ab74cfd690b">collectRootsToKeep</a>, <a href="#abab9675572d9fe6ef8cf9674b1bab8f7">isLiveSubprogramEntry</a>, <a href="#ac9a57660f0db8e2b356c3ebccd34b063">isLiveVariableEntry</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#acb3226f07be871308b3ebc1fe2e22ad8a787e7b5f110b542056c9ca685eb4dcbc">MarkLiveEntryRec</a>, <a href="#acb3226f07be871308b3ebc1fe2e22ad8a5f0d4ecd2ea6dda3c5bc99cf667fedfa">MarkSingleLiveEntry</a>, <a href="#acb3226f07be871308b3ebc1fe2e22ad8a4b0413e0a4858e280698bd82ada3d3f0">MarkSingleTypeEntry</a> and <a href="#acb3226f07be871308b3ebc1fe2e22ad8a6a6c345844bef74add0fbf8063cbef2b">MarkTypeEntryRec</a>.</p>


<p>Referenced by <a href="#aecab109879b9f476fec35ab74cfd690b">collectRootsToKeep</a> and <a href="#ac29d7dd5c7ba980d5a368339b4fc03af">resolveDependenciesAndMarkLiveness</a>.</p>

</div>
</div>

### getRootForSpecifiedEntry() {#a18df788a6ff9a2938e7ce3353609dba8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UnitEntryPairTy DependencyTracker::getRootForSpecifiedEntry (<a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> Entry)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>root for the specified <span class="doxyComputerOutput">Entry</span>.</p></dd>
</dl>


<p>Declaration at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>, definition at line 694 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-cpp">DependencyTracker.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-cpp/#a91c41524c7d7cc02fcab2f1e49873359">isNamespaceLikeEntry</a>.</p>


<p>Referenced by <a href="#a42ebac4ef7af0fc75e5f1a36dccd169a">maybeAddReferencedRoots</a>.</p>

</div>
</div>

### isLiveAction() {#a4b4a1d2b759deb0cb3917f4ad33c2ca1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::parallel::DependencyTracker::isLiveAction (<a href="#acb3226f07be871308b3ebc1fe2e22ad8">LiveRootWorklistActionTy</a> Action)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the specified action is for the "PlainDwarf".</p></dd>
</dl>


<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>.</p>


<p>References <a href="#acb3226f07be871308b3ebc1fe2e22ad8a76f7c22e7afa4d9203192b924b1d2447">MarkLiveChildrenRec</a>, <a href="#acb3226f07be871308b3ebc1fe2e22ad8a787e7b5f110b542056c9ca685eb4dcbc">MarkLiveEntryRec</a> and <a href="#acb3226f07be871308b3ebc1fe2e22ad8a5f0d4ecd2ea6dda3c5bc99cf667fedfa">MarkSingleLiveEntry</a>.</p>


<p>Referenced by <a href="#a99ca361384a0bc6e5fe805b3050ced95">markDIEEntryAsKeptRec</a> and <a href="#a42ebac4ef7af0fc75e5f1a36dccd169a">maybeAddReferencedRoots</a>.</p>

</div>
</div>

### isTypeAction() {#a713ff4f56c059b816949d50ba30e4fc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::parallel::DependencyTracker::isTypeAction (<a href="#acb3226f07be871308b3ebc1fe2e22ad8">LiveRootWorklistActionTy</a> Action)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the specified action is for the "TypeTable".</p></dd>
</dl>


<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>.</p>


<p>References <a href="#acb3226f07be871308b3ebc1fe2e22ad8a4b0413e0a4858e280698bd82ada3d3f0">MarkSingleTypeEntry</a>, <a href="#acb3226f07be871308b3ebc1fe2e22ad8a8cdcce5d067ca8d256189c00ccf279cd">MarkTypeChildrenRec</a> and <a href="#acb3226f07be871308b3ebc1fe2e22ad8a6a6c345844bef74add0fbf8063cbef2b">MarkTypeEntryRec</a>.</p>


<p>Referenced by <a href="#a99ca361384a0bc6e5fe805b3050ced95">markDIEEntryAsKeptRec</a> and <a href="#a42ebac4ef7af0fc75e5f1a36dccd169a">maybeAddReferencedRoots</a>.</p>

</div>
</div>

### isTypeTableCandidate() {#a9d4d1ef3bbae56f8ec7ac95bb5320146}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependencyTracker::isTypeTableCandidate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * DIEEntry)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/dieentry">DIEEntry</a></span> can possibly be put into the artificial type unit.</p></dd>
</dl>


<p>Declaration at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>, definition at line 564 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-cpp">DependencyTracker.cpp</a>.</p>


<p>Referenced by <a href="#a99ca361384a0bc6e5fe805b3050ced95">markDIEEntryAsKeptRec</a>.</p>

</div>
</div>

### markCollectedLiveRootsAsKept() {#a29cd2bdde62b64762aa4c406eff8618f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependencyTracker::markCollectedLiveRootsAsKept (bool InterCUProcessingStarted, std::atomic&lt; bool &gt; &amp; HasNewInterconnectedCUs)</td>
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

<p>Examine worklist and mark all 'root <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>'s as kept and set "Placement" property.</p>

<p>Declaration at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>, definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-cpp">DependencyTracker.cpp</a>.</p>


<p>References <a href="#a06bc651ada60f19beefe066cf9d314a8">Dependencies</a>, <a href="#a99ca361384a0bc6e5fe805b3050ced95">markDIEEntryAsKeptRec</a> and <a href="#aab2d7f8a06a89d372e4cf7da8d45d499">RootEntriesWorkList</a>.</p>


<p>Referenced by <a href="#ac29d7dd5c7ba980d5a368339b4fc03af">resolveDependenciesAndMarkLiveness</a>.</p>

</div>
</div>

### markDIEEntryAsKeptRec() {#a99ca361384a0bc6e5fe805b3050ced95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependencyTracker::markDIEEntryAsKeptRec (<a href="#acb3226f07be871308b3ebc1fe2e22ad8">LiveRootWorklistActionTy</a> Action, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> &amp; RootEntry, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> &amp; Entry, bool InterCUProcessingStarted, std::atomic&lt; bool &gt; &amp; HasNewInterconnectedCUs)</td>
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

<p>Mark whole <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> tree as kept recursively.</p>

<p>Declaration at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>, definition at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-cpp">DependencyTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-cpp/#aa791c4b3d0582a90ae8059dfa4598a9c">getFinalPlacementForEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-cpp/#a0bd005c8437f95e31592128ee5c97e99">isAlreadyMarked</a>, <a href="#a4b4a1d2b759deb0cb3917f4ad33c2ca1">isLiveAction</a>, <a href="#a713ff4f56c059b816949d50ba30e4fc6">isTypeAction</a>, <a href="#a9d4d1ef3bbae56f8ec7ac95bb5320146">isTypeTableCandidate</a>, <a href="#a99ca361384a0bc6e5fe805b3050ced95">markDIEEntryAsKeptRec</a>, <a href="#a137ba2e95278852dbeb5d4b7a372b3a3">markParentsAsKeepingChildren</a>, <a href="#a42ebac4ef7af0fc75e5f1a36dccd169a">maybeAddReferencedRoots</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#a10783a549bfb83fd142ae4e645a283ef">Placement</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5270021419d157f502aba678e1ee8549aecc6950928c245961306947efbae3db7">llvm::dwarf_linker::parallel::CompileUnit::PlainDwarf</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5270021419d157f502aba678e1ee8549ae4e2eb6616a94c80f428778e4b1bb3bf">llvm::dwarf_linker::parallel::CompileUnit::TypeTable</a>.</p>


<p>Referenced by <a href="#a29cd2bdde62b64762aa4c406eff8618f">markCollectedLiveRootsAsKept</a> and <a href="#a99ca361384a0bc6e5fe805b3050ced95">markDIEEntryAsKeptRec</a>.</p>

</div>
</div>

### markParentsAsKeepingChildren() {#a137ba2e95278852dbeb5d4b7a372b3a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DependencyTracker::markParentsAsKeepingChildren (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> &amp; Entry)</td>
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

<p>Mark parents as keeping children.</p>

<p>Declaration at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>, definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-cpp">DependencyTracker.cpp</a>.</p>


<p>References <a href="#ab611f3c12ccf9485de74c6bb78aedb81">addActionToRootEntriesWorkList</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry/#ab9761bc1cfe0e7e41b91d4e590df92e4">llvm::DWARFDebugInfoEntry::getParentIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-cpp/#a0bd005c8437f95e31592128ee5c97e99">isAlreadyMarked</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-cpp/#a91c41524c7d7cc02fcab2f1e49873359">isNamespaceLikeEntry</a>, <a href="#acb3226f07be871308b3ebc1fe2e22ad8a76f7c22e7afa4d9203192b924b1d2447">MarkLiveChildrenRec</a>, <a href="#acb3226f07be871308b3ebc1fe2e22ad8a8cdcce5d067ca8d256189c00ccf279cd">MarkTypeChildrenRec</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5270021419d157f502aba678e1ee8549aecc6950928c245961306947efbae3db7">llvm::dwarf_linker::parallel::CompileUnit::PlainDwarf</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5270021419d157f502aba678e1ee8549ae4e2eb6616a94c80f428778e4b1bb3bf">llvm::dwarf_linker::parallel::CompileUnit::TypeTable</a>.</p>


<p>Referenced by <a href="#a99ca361384a0bc6e5fe805b3050ced95">markDIEEntryAsKeptRec</a> and <a href="#aa664f05184b8e7e5101de50bf18ccc99">setPlainDwarfPlacementRec</a>.</p>

</div>
</div>

### maybeAddReferencedRoots() {#a42ebac4ef7af0fc75e5f1a36dccd169a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependencyTracker::maybeAddReferencedRoots (<a href="#acb3226f07be871308b3ebc1fe2e22ad8">LiveRootWorklistActionTy</a> Action, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> &amp; RootEntry, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> &amp; Entry, bool InterCUProcessingStarted, std::atomic&lt; bool &gt; &amp; HasNewInterconnectedCUs)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> referenced DIEs and add them into the worklist.</p>

<p>Declaration at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>, definition at line 612 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-cpp">DependencyTracker.cpp</a>.</p>


<p>References <a href="#ab611f3c12ccf9485de74c6bb78aedb81">addActionToRootEntriesWorkList</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#afcf78d2889ce6c20ba9de57049ac479faab10e425f6c3ac968107b815f2a08814">llvm::dwarf_linker::parallel::AvoidResolving</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#aa146755e2500aea560c4417a30c0b96b">llvm::DWARFFormValue::extractValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a031683a2f97f9d8db3b493ada43e2228aecc352ab32050f10e6c1d07d39eca711">llvm::DWARFFormValue::FC_Reference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#afbe6a2dc0336fa85db3656856747ce1e">llvm::dwarf_linker::parallel::getODRAttributes</a>, <a href="#a18df788a6ff9a2938e7ce3353609dba8">getRootForSpecifiedEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa02a1d8fb0f561ab81f4a2570db7dc28">llvm::getULEB128Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a7f4acdd5d8a9b78623878262b10f8e4f">llvm::DWARFFormValue::isFormClass</a>, <a href="#a4b4a1d2b759deb0cb3917f4ad33c2ca1">isLiveAction</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-cpp/#a91c41524c7d7cc02fcab2f1e49873359">isNamespaceLikeEntry</a>, <a href="#a713ff4f56c059b816949d50ba30e4fc6">isTypeAction</a>, <a href="#acb3226f07be871308b3ebc1fe2e22ad8a787e7b5f110b542056c9ca685eb4dcbc">MarkLiveEntryRec</a>, <a href="#acb3226f07be871308b3ebc1fe2e22ad8a5f0d4ecd2ea6dda3c5bc99cf667fedfa">MarkSingleLiveEntry</a>, <a href="#acb3226f07be871308b3ebc1fe2e22ad8a4b0413e0a4858e280698bd82ada3d3f0">MarkSingleTypeEntry</a>, <a href="#acb3226f07be871308b3ebc1fe2e22ad8a6a6c345844bef74add0fbf8063cbef2b">MarkTypeEntryRec</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#afcf78d2889ce6c20ba9de57049ac479fad28670925b341cc0d43e6a0535646d38">llvm::dwarf_linker::parallel::Resolve</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#ad16686174287aeb36289484f271d5225">llvm::DWARFFormValue::skipValue</a>.</p>


<p>Referenced by <a href="#a99ca361384a0bc6e5fe805b3050ced95">markDIEEntryAsKeptRec</a>.</p>

</div>
</div>

### setPlainDwarfPlacementRec() {#aa664f05184b8e7e5101de50bf18ccc99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DependencyTracker::setPlainDwarfPlacementRec (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> &amp; Entry)</td>
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

<p>Mark whole <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> tree as placed in "PlainDwarf".</p>

<p>Declaration at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>, definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-cpp">DependencyTracker.cpp</a>.</p>


<p>References <a href="#a137ba2e95278852dbeb5d4b7a372b3a3">markParentsAsKeepingChildren</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5270021419d157f502aba678e1ee8549aecc6950928c245961306947efbae3db7">llvm::dwarf_linker::parallel::CompileUnit::PlainDwarf</a> and <a href="#aa664f05184b8e7e5101de50bf18ccc99">setPlainDwarfPlacementRec</a>.</p>


<p>Referenced by <a href="#aa664f05184b8e7e5101de50bf18ccc99">setPlainDwarfPlacementRec</a> and <a href="#af28b850047c908b6602c0783a0c4688f">updateDependenciesCompleteness</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### CU {#a4df77906fd480828f5af41e52e738538}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CompileUnit&amp; llvm::dwarf_linker::parallel::DependencyTracker::CU</td>
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



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>.</p>

</div>
</div>

### Dependencies {#a06bc651ada60f19beefe066cf9d314a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RootEntriesListTy llvm::dwarf_linker::parallel::DependencyTracker::Dependencies</td>
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

<p>List of entries dependencies.</p>

<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>.</p>


<p>Referenced by <a href="#a29cd2bdde62b64762aa4c406eff8618f">markCollectedLiveRootsAsKept</a> and <a href="#af28b850047c908b6602c0783a0c4688f">updateDependenciesCompleteness</a>.</p>

</div>
</div>

### ReferencedByCU {#a3823523700ff25bf711096e0e22578de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CompileUnit* llvm::dwarf_linker::parallel::DependencyTracker::ReferencedByCU = nullptr</td>
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

</div>
</div>

### ReferencedByDieEntry {#adf99246a5f6c50057f9725ad80bebcd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugInfoEntry* llvm::dwarf_linker::parallel::DependencyTracker::ReferencedByDieEntry = nullptr</td>
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

</div>
</div>

### RootCU {#aa411def72116744e4a23ebda2b9b9250}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerIntPair&lt;CompileUnit *, 3, LiveRootWorklistActionTy, CompileUnitPointerTraits&gt; llvm::dwarf_linker::parallel::DependencyTracker::RootCU</td>
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

</div>
</div>

### RootDieEntry {#a948ffc10c192b2502908ae6a0aa6a082}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugInfoEntry* llvm::dwarf_linker::parallel::DependencyTracker::RootDieEntry = nullptr</td>
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

</div>
</div>

### RootEntriesWorkList {#aab2d7f8a06a89d372e4cf7da8d45d499}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RootEntriesListTy llvm::dwarf_linker::parallel::DependencyTracker::RootEntriesWorkList</td>
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

<p>List of entries which are 'root <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>'s.</p>

<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>.</p>


<p>Referenced by <a href="#ab611f3c12ccf9485de74c6bb78aedb81">addActionToRootEntriesWorkList</a>, <a href="#a29cd2bdde62b64762aa4c406eff8618f">markCollectedLiveRootsAsKept</a> and <a href="#ac29d7dd5c7ba980d5a368339b4fc03af">resolveDependenciesAndMarkLiveness</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### isLiveSubprogramEntry() {#abab9675572d9fe6ef8cf9674b1bab8f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependencyTracker::isLiveSubprogramEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> &amp; Entry)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if specified subprogram references live code section.</p>

<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>, definition at line 770 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-cpp">DependencyTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#ae396b319b15cbecf51ec8dc4ee2719b0">llvm::DIDumpOptions::ChildRecurseDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#aeec7f1000c747324d45318321277b7b9">llvm::DIE::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#aeac16c22ec5a0c13658381144c7e3439">llvm::DIE::getTag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2d79a00fa7c56f57b87f2fe2a3f118c7">llvm::outs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a0ed489a15626cfc6a1dd642c012aeb74">llvm::dwarf::toAddress</a>, <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#a30654b4b67d97c42ca3f9b6052dda916">UINT64_MAX</a> and <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#add6a33649e764a95f041d7b8358a019e">llvm::DIDumpOptions::Verbose</a>.</p>


<p>Referenced by <a href="#aecab109879b9f476fec35ab74cfd690b">collectRootsToKeep</a> and <a href="#a066fd5533813e5df6d52cb59fc8afd4e">verifyKeepChain</a>.</p>

</div>
</div>

### isLiveVariableEntry() {#ac9a57660f0db8e2b356c3ebccd34b063}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DependencyTracker::isLiveVariableEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> &amp; Entry, bool IsLiveParent)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if specified variable references live code section.</p>

<p>Declaration at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>, definition at line 725 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-cpp">DependencyTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#ae396b319b15cbecf51ec8dc4ee2719b0">llvm::DIDumpOptions::ChildRecurseDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#aeec7f1000c747324d45318321277b7b9">llvm::DIE::dump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2d79a00fa7c56f57b87f2fe2a3f118c7">llvm::outs</a> and <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#add6a33649e764a95f041d7b8358a019e">llvm::DIDumpOptions::Verbose</a>.</p>


<p>Referenced by <a href="#aecab109879b9f476fec35ab74cfd690b">collectRootsToKeep</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-cpp">DependencyTracker.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
