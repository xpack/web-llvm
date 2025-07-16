---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf-linker/parallel/arraylist
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ArrayList` Class Template Reference

<p>This class is a simple list of T structures. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T, size_t ItemsGroupSize = 512&gt;
class llvm::dwarf_linker::parallel::ArrayList&lt;T, ItemsGroupSize&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/arraylist-h">DWARFLinker/Parallel/ArrayList.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t ItemsGroupSize = 512&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abd09d7947f142df414403edcfd31b2da">ItemHandlerTy</a> = <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(T &amp;)&gt;</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t ItemsGroupSize = 512&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#af31e0560a91550cb768460ab6231d32b">ArrayList</a> (llvm::parallel::PerThreadBumpPtrAllocator *Allocator)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t ItemsGroupSize = 512&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3055e7b57c17c6988622279667b77088">add</a> (const T &amp;Item)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add specified <span class="doxyComputerOutput">Item</span> to the list. <a href="#a3055e7b57c17c6988622279667b77088">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t ItemsGroupSize = 512&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aae25e913e6fa0953f3f6e4762e1f5ca2">forEach</a> (ItemHandlerTy Handler)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enumerate all items and apply specified <span class="doxyComputerOutput">Handler</span> to each. <a href="#aae25e913e6fa0953f3f6e4762e1f5ca2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t ItemsGroupSize = 512&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a501d4c15d3dac67bf3aa530a4716a4a6">empty</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether list is empty. <a href="#a501d4c15d3dac67bf3aa530a4716a4a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t ItemsGroupSize = 512&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab0b773c5dad2509b3ae2eb522ccbc755">erase</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erase list. <a href="#ab0b773c5dad2509b3ae2eb522ccbc755">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t ItemsGroupSize = 512&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adf19460a3c702d261e7ffe25d77cabbb">sort</a> (function_ref&lt; bool(const T &amp;LHS, const T &amp;RHS)&gt; Comparator)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t ItemsGroupSize = 512&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6d8c5fe252f23cfda8d77eb957fe1fe2">size</a> ()</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t ItemsGroupSize = 512&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5884ad133d07d8bd3f0f24d37a93bff8">allocateNewGroup</a> (std::atomic&lt; ItemsGroup * &gt; &amp;AtomicGroup)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t ItemsGroupSize = 512&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::atomic&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/arraylist/itemsgroup">ItemsGroup</a> * &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aae9e6806da513c25ccd7e7c4cf4c2da2">GroupsHead</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t ItemsGroupSize = 512&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::atomic&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/arraylist/itemsgroup">ItemsGroup</a> * &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a44b37ce26c8d59ffa58ba554bf4a4cfc">LastGroup</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, size_t ItemsGroupSize = 512&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/parallel/#a4e82d98d22361038741bca9bd34bca85">llvm::parallel::PerThreadBumpPtrAllocator</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a52bf80f6ad1dd26e853dc0fef4c10cc2">Allocator</a> = nullptr</td>
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

<p>This class is a simple list of T structures.</p>


<p>It keeps elements as pre-allocated groups to save memory for each element's next pointer. It allocates internal data using specified per-thread <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a>. Method <a href="#a3055e7b57c17c6988622279667b77088">add()</a> can be called asynchronously.</p>


<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/arraylist-h">ArrayList.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ItemHandlerTy {#abd09d7947f142df414403edcfd31b2da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t ItemsGroupSize = 512&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::ItemHandlerTy =  function_ref&lt;void(T &amp;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/arraylist-h">ArrayList.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ArrayList() {#af31e0560a91550cb768460ab6231d32b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t ItemsGroupSize = 512&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::ArrayList (<a href="/web-llvm/docs/api/namespaces/llvm/parallel/#a4e82d98d22361038741bca9bd34bca85">llvm::parallel::PerThreadBumpPtrAllocator</a> * Allocator)</td>
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



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/arraylist-h">ArrayList.h</a>.</p>


<p>Reference <a href="#a52bf80f6ad1dd26e853dc0fef4c10cc2">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::Allocator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#a3055e7b57c17c6988622279667b77088}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t ItemsGroupSize = 512&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T &amp; llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::add (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; Item)</td>
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

<p>Add specified <span class="doxyComputerOutput">Item</span> to the list.</p>

<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/arraylist-h">ArrayList.h</a>.</p>


<p>References <a href="#a5884ad133d07d8bd3f0f24d37a93bff8">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::allocateNewGroup</a>, <a href="#a52bf80f6ad1dd26e853dc0fef4c10cc2">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::Allocator</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aae9e6806da513c25ccd7e7c4cf4c2da2">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::GroupsHead</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/arraylist/itemsgroup/#a26c1fa2bf8cac04ab8ef503edf349c03">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::ItemsGroup::Items</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/arraylist/itemsgroup/#a6274095c04d4e37093643dd5df6945e6">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::ItemsGroup::ItemsCount</a>, <a href="#a44b37ce26c8d59ffa58ba554bf4a4cfc">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::LastGroup</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/arraylist/itemsgroup/#aa2b097065cbd9e8fe9695ded1c5a8e1f">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::ItemsGroup::Next</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### empty() {#a501d4c15d3dac67bf3aa530a4716a4a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t ItemsGroupSize = 512&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::empty ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether list is empty.</p>

<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/arraylist-h">ArrayList.h</a>.</p>


<p>Reference <a href="#aae9e6806da513c25ccd7e7c4cf4c2da2">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::GroupsHead</a>.</p>

</div>
</div>

### erase() {#ab0b773c5dad2509b3ae2eb522ccbc755}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t ItemsGroupSize = 512&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::erase ()</td>
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

<p>Erase list.</p>

<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/arraylist-h">ArrayList.h</a>.</p>


<p>References <a href="#aae9e6806da513c25ccd7e7c4cf4c2da2">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::GroupsHead</a> and <a href="#a44b37ce26c8d59ffa58ba554bf4a4cfc">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::LastGroup</a>.</p>

</div>
</div>

### forEach() {#aae25e913e6fa0953f3f6e4762e1f5ca2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t ItemsGroupSize = 512&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::forEach (<a href="#abd09d7947f142df414403edcfd31b2da">ItemHandlerTy</a> Handler)</td>
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

<p>Enumerate all items and apply specified <span class="doxyComputerOutput">Handler</span> to each.</p>

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/arraylist-h">ArrayList.h</a>.</p>


<p>References <a href="#aae9e6806da513c25ccd7e7c4cf4c2da2">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::GroupsHead</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#adf19460a3c702d261e7ffe25d77cabbb">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::sort</a>.</p>

</div>
</div>

### size() {#a6d8c5fe252f23cfda8d77eb957fe1fe2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t ItemsGroupSize = 512&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::size ()</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/arraylist-h">ArrayList.h</a>.</p>


<p>Reference <a href="#aae9e6806da513c25ccd7e7c4cf4c2da2">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::GroupsHead</a>.</p>

</div>
</div>

### sort() {#adf19460a3c702d261e7ffe25d77cabbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t ItemsGroupSize = 512&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::sort (<a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>)&gt; Comparator)</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/arraylist-h">ArrayList.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="#aae25e913e6fa0953f3f6e4762e1f5ca2">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::forEach</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### allocateNewGroup() {#a5884ad133d07d8bd3f0f24d37a93bff8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t ItemsGroupSize = 512&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::allocateNewGroup (std::atomic&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/arraylist/itemsgroup">ItemsGroup</a> * &gt; &amp; AtomicGroup)</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/arraylist-h">ArrayList.h</a>.</p>


<p>References <a href="#a52bf80f6ad1dd26e853dc0fef4c10cc2">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::Allocator</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/arraylist/itemsgroup/#a6274095c04d4e37093643dd5df6945e6">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::ItemsGroup::ItemsCount</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/arraylist/itemsgroup/#aa2b097065cbd9e8fe9695ded1c5a8e1f">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::ItemsGroup::Next</a>.</p>


<p>Referenced by <a href="#a3055e7b57c17c6988622279667b77088">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::add</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Allocator {#a52bf80f6ad1dd26e853dc0fef4c10cc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t ItemsGroupSize = 512&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::parallel::PerThreadBumpPtrAllocator* llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::Allocator = nullptr</td>
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



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/arraylist-h">ArrayList.h</a>.</p>


<p>Referenced by <a href="#a3055e7b57c17c6988622279667b77088">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::add</a>, <a href="#a5884ad133d07d8bd3f0f24d37a93bff8">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::allocateNewGroup</a> and <a href="#af31e0560a91550cb768460ab6231d32b">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::ArrayList</a>.</p>

</div>
</div>

### GroupsHead {#aae9e6806da513c25ccd7e7c4cf4c2da2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t ItemsGroupSize = 512&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::atomic&lt;ItemsGroup *&gt; llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::GroupsHead = nullptr</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/arraylist-h">ArrayList.h</a>.</p>


<p>Referenced by <a href="#a3055e7b57c17c6988622279667b77088">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::add</a>, <a href="#a501d4c15d3dac67bf3aa530a4716a4a6">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::empty</a>, <a href="#ab0b773c5dad2509b3ae2eb522ccbc755">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::erase</a>, <a href="#aae25e913e6fa0953f3f6e4762e1f5ca2">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::forEach</a> and <a href="#a6d8c5fe252f23cfda8d77eb957fe1fe2">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::size</a>.</p>

</div>
</div>

### LastGroup {#a44b37ce26c8d59ffa58ba554bf4a4cfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, size_t ItemsGroupSize = 512&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::atomic&lt;ItemsGroup *&gt; llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::LastGroup = nullptr</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/arraylist-h">ArrayList.h</a>.</p>


<p>Referenced by <a href="#a3055e7b57c17c6988622279667b77088">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::add</a> and <a href="#ab0b773c5dad2509b3ae2eb522ccbc755">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::erase</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/arraylist-h">ArrayList.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
