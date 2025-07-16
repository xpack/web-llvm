---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/allocationinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AllocationInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::AllocationInfo { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#afb181099bc73e874960b3ec63602b77f">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The status wrt. a rewrite. <a href="#afb181099bc73e874960b3ec63602b77f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24bf70eedf04000106c884643a5ce192">CB</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The call that allocates the memory. <a href="#a24bf70eedf04000106c884643a5ce192">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b8550b9800fda71999125f6afb050e1">LibraryFunctionId</a> = NotLibFunc</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The library function id for the allocation. <a href="#a8b8550b9800fda71999125f6afb050e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum anonymous_namespace{AttributorAttributes.cpp}<a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/allocationinfo">::AAHeapToStackFunction::AllocationInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab82b4a048c11e2ed40ad1193fb0162e1">Status</a> = <a href="#afb181099bc73e874960b3ec63602b77fa86fb843d7c551262c52e0e1c592f700c">STACK_DUE_TO_USE</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The status wrt. a rewrite. <a href="#ab82b4a048c11e2ed40ad1193fb0162e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd00c4139cc326952b036e26e2607058">HasPotentiallyFreeingUnknownUses</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag to indicate if we encountered a use that might free this allocation but which is not in the deallocation infos. <a href="#abd00c4139cc326952b036e26e2607058">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff4ac5dd6ea7aefb83bfd761aa12e415">MoveAllocaIntoEntry</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag to indicate that we should place the new alloca in the function entry block rather than where the call site (CB) is. <a href="#aff4ac5dd6ea7aefb83bfd761aa12e415">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> *, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab841fd478384e7a0740d29fc331d625f">PotentialFreeCalls</a> {}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of free calls that use this allocation. <a href="#ab841fd478384e7a0740d29fc331d625f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 6596 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#afb181099bc73e874960b3ec63602b77f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The status wrt. a rewrite.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STACK_DUE_TO_USE<a id="afb181099bc73e874960b3ec63602b77fa86fb843d7c551262c52e0e1c592f700c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STACK_DUE_TO_FREE<a id="afb181099bc73e874960b3ec63602b77fa41f7f9fc63682d208fa59378ea476e82"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">INVALID<a id="afb181099bc73e874960b3ec63602b77fa27dbbde654b0c92569d019b830182778"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 6604 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CB {#a24bf70eedf04000106c884643a5ce192}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallBase* const anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::AllocationInfo::CB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The call that allocates the memory.</p>

<p>Definition at line 6598 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#aeda99db80deee5e043ee85bd09835da9">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::getSize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#a7d3aee2fc33ae5d5ffe0085711f601bf">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::manifest</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#abe94b0d36f169e52ede6a35d6ac41859">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::updateImpl</a>.</p>

</div>
</div>

### HasPotentiallyFreeingUnknownUses {#abd00c4139cc326952b036e26e2607058}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::AllocationInfo::HasPotentiallyFreeingUnknownUses = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag to indicate if we encountered a use that might free this allocation but which is not in the deallocation infos.</p>

<p>Definition at line 6612 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>

</div>
</div>

### LibraryFunctionId {#a8b8550b9800fda71999125f6afb050e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LibFunc anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::AllocationInfo::LibraryFunctionId = NotLibFunc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The library function id for the allocation.</p>

<p>Definition at line 6601 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#a424871cbef50e8414bb8bbed3a4068db">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#a7d3aee2fc33ae5d5ffe0085711f601bf">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::manifest</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#abe94b0d36f169e52ede6a35d6ac41859">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::updateImpl</a>.</p>

</div>
</div>

### MoveAllocaIntoEntry {#aff4ac5dd6ea7aefb83bfd761aa12e415}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::AllocationInfo::MoveAllocaIntoEntry = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag to indicate that we should place the new alloca in the function entry block rather than where the call site (CB) is.</p>

<p>Definition at line 6616 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#a7d3aee2fc33ae5d5ffe0085711f601bf">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::manifest</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#abe94b0d36f169e52ede6a35d6ac41859">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::updateImpl</a>.</p>

</div>
</div>

### PotentialFreeCalls {#ab841fd478384e7a0740d29fc331d625f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSetVector&lt;CallBase *, 1&gt; anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::AllocationInfo::PotentialFreeCalls {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of free calls that use this allocation.</p>

<p>Definition at line 6619 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#ace38ebf109b7e602677cb2e0ce4839fb">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::isAssumedHeapToStackRemovedFree</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#a7d3aee2fc33ae5d5ffe0085711f601bf">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::manifest</a>.</p>

</div>
</div>

### Status {#ab82b4a048c11e2ed40ad1193fb0162e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::AllocationInfo anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::AllocationInfo::Status = <a href="#afb181099bc73e874960b3ec63602b77fa86fb843d7c551262c52e0e1c592f700c">STACK_DUE_TO_USE</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The status wrt. a rewrite.</p>

<p>Definition at line 6608 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#ace38ebf109b7e602677cb2e0ce4839fb">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::isAssumedHeapToStackRemovedFree</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#a7d3aee2fc33ae5d5ffe0085711f601bf">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::manifest</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#abe94b0d36f169e52ede6a35d6ac41859">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::updateImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
