---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `DependencyTracker.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-h">DependencyTracker.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">llvm/Support/FormatVariadic.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/brokenlink">BrokenLink</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A broken link in the keep chain. <a href="/web-llvm/docs/api/structs/brokenlink/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91c41524c7d7cc02fcab2f1e49873359">isNamespaceLikeEntry</a> (const DWARFDebugInfoEntry *Entry)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bd005c8437f95e31592128ee5c97e99">isAlreadyMarked</a> (const CompileUnit::DIEInfo &amp;Info, CompileUnit::DieOutputPlacement NewPlacement)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad81fbcf409c2eb9c79edb47669b5a576">isAlreadyMarked</a> (const UnitEntryPairTy &amp;Entry, CompileUnit::DieOutputPlacement NewPlacement)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5270021419d157f502aba678e1ee8549">CompileUnit::DieOutputPlacement</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa791c4b3d0582a90ae8059dfa4598a9c">getFinalPlacementForEntry</a> (const UnitEntryPairTy &amp;Entry, CompileUnit::DieOutputPlacement Placement)</td>
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


<div class="doxySectionDef">

## Functions

### getFinalPlacementForEntry() {#aa791c4b3d0582a90ae8059dfa4598a9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CompileUnit::DieOutputPlacement getFinalPlacementForEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> &amp; Entry, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5270021419d157f502aba678e1ee8549">CompileUnit::DieOutputPlacement</a> Placement)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-cpp">DependencyTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5270021419d157f502aba678e1ee8549a5d59de2bbf0cc536bfb1d56049d26d68">llvm::dwarf_linker::parallel::CompileUnit::Both</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5270021419d157f502aba678e1ee8549ae9311639cca717631f1dc39e18b1f62d">llvm::dwarf_linker::parallel::CompileUnit::NotSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#a10783a549bfb83fd142ae4e645a283ef">Placement</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5270021419d157f502aba678e1ee8549aecc6950928c245961306947efbae3db7">llvm::dwarf_linker::parallel::CompileUnit::PlainDwarf</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5270021419d157f502aba678e1ee8549ae4e2eb6616a94c80f428778e4b1bb3bf">llvm::dwarf_linker::parallel::CompileUnit::TypeTable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#a99ca361384a0bc6e5fe805b3050ced95">llvm::dwarf_linker::parallel::DependencyTracker::markDIEEntryAsKeptRec</a>.</p>

</div>
</div>

### isAlreadyMarked() {#a0bd005c8437f95e31592128ee5c97e99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isAlreadyMarked (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/compileunit/dieinfo">CompileUnit::DIEInfo</a> &amp; Info, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5270021419d157f502aba678e1ee8549">CompileUnit::DieOutputPlacement</a> NewPlacement)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-cpp">DependencyTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5270021419d157f502aba678e1ee8549a5d59de2bbf0cc536bfb1d56049d26d68">llvm::dwarf_linker::parallel::CompileUnit::Both</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5270021419d157f502aba678e1ee8549ae9311639cca717631f1dc39e18b1f62d">llvm::dwarf_linker::parallel::CompileUnit::NotSet</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5270021419d157f502aba678e1ee8549aecc6950928c245961306947efbae3db7">llvm::dwarf_linker::parallel::CompileUnit::PlainDwarf</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5270021419d157f502aba678e1ee8549ae4e2eb6616a94c80f428778e4b1bb3bf">llvm::dwarf_linker::parallel::CompileUnit::TypeTable</a>.</p>


<p>Referenced by <a href="#ad81fbcf409c2eb9c79edb47669b5a576">isAlreadyMarked</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#a99ca361384a0bc6e5fe805b3050ced95">llvm::dwarf_linker::parallel::DependencyTracker::markDIEEntryAsKeptRec</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#a137ba2e95278852dbeb5d4b7a372b3a3">llvm::dwarf_linker::parallel::DependencyTracker::markParentsAsKeepingChildren</a>.</p>

</div>
</div>

### isAlreadyMarked() {#ad81fbcf409c2eb9c79edb47669b5a576}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isAlreadyMarked (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> &amp; Entry, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5270021419d157f502aba678e1ee8549">CompileUnit::DieOutputPlacement</a> NewPlacement)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-cpp">DependencyTracker.cpp</a>.</p>


<p>Reference <a href="#a0bd005c8437f95e31592128ee5c97e99">isAlreadyMarked</a>.</p>

</div>
</div>

### isNamespaceLikeEntry() {#a91c41524c7d7cc02fcab2f1e49873359}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isNamespaceLikeEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * Entry)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-cpp">DependencyTracker.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#a18df788a6ff9a2938e7ce3353609dba8">llvm::dwarf_linker::parallel::DependencyTracker::getRootForSpecifiedEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#a137ba2e95278852dbeb5d4b7a372b3a3">llvm::dwarf_linker::parallel::DependencyTracker::markParentsAsKeepingChildren</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#a42ebac4ef7af0fc75e5f1a36dccd169a">llvm::dwarf_linker::parallel::DependencyTracker::maybeAddReferencedRoots</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
