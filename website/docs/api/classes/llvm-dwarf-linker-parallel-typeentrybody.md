---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf-linker/parallel/typeentrybody
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `TypeEntryBody` Class

<p>Keeps cloned data for the type <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::dwarf_linker::parallel::TypeEntryBody { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/typepool-h">DWARFLinker/Parallel/TypePool.h</a>"
</div>

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81e492d82a64eccb8c34be2d5bb0d8eb">TypeEntryBody</a> ()=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9489b19ef651ed38dcad92b89dc6011c">TypeEntryBody</a> (const TypeEntryBody &amp;RHS)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61b7fae509d6b4cb50eb399c7c65d97c">TypeEntryBody</a> (TypeEntryBody &amp;&amp;RHS)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95c255d41a30a621f1339a9736b2b501">TypeEntryBody</a> (llvm::parallel::PerThreadBumpPtrAllocator &amp;Allocator)</td>
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

## Protected Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeentrybody">TypeEntryBody</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e68b5beb8a7663af4e567f9485faa91">operator=</a> (const TypeEntryBody &amp;RHS)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeentrybody">TypeEntryBody</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae591dc1557d57740743c603b6149bd34">operator=</a> (const TypeEntryBody &amp;&amp;RHS)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30a134da38e368dc2cf1d981aec2bcf8">getFinalDie</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns copy of type <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> which should be emitted into resulting file. <a href="#a30a134da38e368dc2cf1d981aec2bcf8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8947c1e9fa7a7bc9f33f2d536f96478c">hasOnlyDeclaration</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if type die entry has only declaration die. <a href="#a8947c1e9fa7a7bc9f33f2d536f96478c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::atomic&lt; <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbaa4a80bd8f05f262dcffa77f30796f">Die</a> = {nullptr}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeentrybody">TypeEntryBody</a> keeps partially cloned DIEs corresponding to this type. <a href="#acbaa4a80bd8f05f262dcffa77f30796f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::atomic&lt; <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac02d9e01f4bca35bfab0164d4b6b5d43">DeclarationDie</a> = {nullptr}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::atomic&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f0854e618bc5868187f0b2d7340fe31">ParentIsDeclaration</a> = {<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/arraylist">ArrayList</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#ae00955922b792a539fb6b19062e0a1af">TypeEntry</a> *, 5 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2df5b34ee3df71e2d9d528a7708e72dd">Children</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Children for current type. <a href="#a2df5b34ee3df71e2d9d528a7708e72dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeentrybody">TypeEntryBody</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5911f089676e212db39133a0bba14e8">create</a> (llvm::parallel::PerThreadBumpPtrAllocator &amp;Allocator)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates type <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for the specified name. <a href="#ad5911f089676e212db39133a0bba14e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Keeps cloned data for the type <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/typepool-h">TypePool.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### TypeEntryBody() {#a81e492d82a64eccb8c34be2d5bb0d8eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::TypeEntryBody::TypeEntryBody ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/typepool-h">TypePool.h</a>.</p>


<p>Referenced by <a href="#ad5911f089676e212db39133a0bba14e8">create</a>, <a href="#ae591dc1557d57740743c603b6149bd34">operator=</a>, <a href="#a9e68b5beb8a7663af4e567f9485faa91">operator=</a>, <a href="#a9489b19ef651ed38dcad92b89dc6011c">TypeEntryBody</a> and <a href="#a61b7fae509d6b4cb50eb399c7c65d97c">TypeEntryBody</a>.</p>

</div>
</div>

### TypeEntryBody() {#a9489b19ef651ed38dcad92b89dc6011c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::TypeEntryBody::TypeEntryBody (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeentrybody">TypeEntryBody</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/typepool-h">TypePool.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a81e492d82a64eccb8c34be2d5bb0d8eb">TypeEntryBody</a>.</p>

</div>
</div>

### TypeEntryBody() {#a61b7fae509d6b4cb50eb399c7c65d97c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::TypeEntryBody::TypeEntryBody (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeentrybody">TypeEntryBody</a> &amp;&amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/typepool-h">TypePool.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a81e492d82a64eccb8c34be2d5bb0d8eb">TypeEntryBody</a>.</p>

</div>
</div>

### TypeEntryBody() {#a95c255d41a30a621f1339a9736b2b501}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::TypeEntryBody::TypeEntryBody (<a href="/web-llvm/docs/api/namespaces/llvm/parallel/#a4e82d98d22361038741bca9bd34bca85">llvm::parallel::PerThreadBumpPtrAllocator</a> &amp; Allocator)</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/typepool-h">TypePool.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbasic-cpp/#ad5d00e1d77644d95847b9bf8da12b759">Allocator</a> and <a href="#a2df5b34ee3df71e2d9d528a7708e72dd">Children</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Operators

### operator=() {#a9e68b5beb8a7663af4e567f9485faa91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeEntryBody &amp; llvm::dwarf_linker::parallel::TypeEntryBody::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeentrybody">TypeEntryBody</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/typepool-h">TypePool.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a81e492d82a64eccb8c34be2d5bb0d8eb">TypeEntryBody</a>.</p>

</div>
</div>

### operator=() {#ae591dc1557d57740743c603b6149bd34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeEntryBody &amp; llvm::dwarf_linker::parallel::TypeEntryBody::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeentrybody">TypeEntryBody</a> &amp;&amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/typepool-h">TypePool.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a81e492d82a64eccb8c34be2d5bb0d8eb">TypeEntryBody</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getFinalDie() {#a30a134da38e368dc2cf1d981aec2bcf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE &amp; llvm::dwarf_linker::parallel::TypeEntryBody::getFinalDie ()</td>
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

<p>Returns copy of type <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> which should be emitted into resulting file.</p>

<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/typepool-h">TypePool.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac02d9e01f4bca35bfab0164d4b6b5d43">DeclarationDie</a> and <a href="#acbaa4a80bd8f05f262dcffa77f30796f">Die</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a09b5d1027676907c7bc194a865ffe0df">llvm::dwarf_linker::parallel::OutputSections::applyPatches</a>.</p>

</div>
</div>

### hasOnlyDeclaration() {#a8947c1e9fa7a7bc9f33f2d536f96478c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::parallel::TypeEntryBody::hasOnlyDeclaration ()</td>
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

<p>Returns true if type die entry has only declaration die.</p>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/typepool-h">TypePool.h</a>.</p>


<p>Reference <a href="#acbaa4a80bd8f05f262dcffa77f30796f">Die</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Children {#a2df5b34ee3df71e2d9d528a7708e72dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayList&lt;TypeEntry *, 5&gt; llvm::dwarf_linker::parallel::TypeEntryBody::Children</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Children for current type.</p>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/typepool-h">TypePool.h</a>.</p>


<p>Referenced by <a href="#a95c255d41a30a621f1339a9736b2b501">TypeEntryBody</a>.</p>

</div>
</div>

### DeclarationDie {#ac02d9e01f4bca35bfab0164d4b6b5d43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::atomic&lt;DIE *&gt; llvm::dwarf_linker::parallel::TypeEntryBody::DeclarationDie = {nullptr}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/typepool-h">TypePool.h</a>.</p>


<p>Referenced by <a href="#a30a134da38e368dc2cf1d981aec2bcf8">getFinalDie</a>.</p>

</div>
</div>

### Die {#acbaa4a80bd8f05f262dcffa77f30796f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::atomic&lt;DIE *&gt; llvm::dwarf_linker::parallel::TypeEntryBody::Die = {nullptr}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeentrybody">TypeEntryBody</a> keeps partially cloned DIEs corresponding to this type.</p>


<p>The two kinds of <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> can be kept: declaration and definition. If definition <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> was met while parsing input DWARF then this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> would be used as a final <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for this type. If definition <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> is not met then declaration <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> would be used as a final <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>


<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/typepool-h">TypePool.h</a>.</p>


<p>Referenced by <a href="#a30a134da38e368dc2cf1d981aec2bcf8">getFinalDie</a> and <a href="#a8947c1e9fa7a7bc9f33f2d536f96478c">hasOnlyDeclaration</a>.</p>

</div>
</div>

### ParentIsDeclaration {#a9f0854e618bc5868187f0b2d7340fe31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::atomic&lt;bool&gt; llvm::dwarf_linker::parallel::TypeEntryBody::ParentIsDeclaration = {<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/typepool-h">TypePool.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#ad5911f089676e212db39133a0bba14e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeEntryBody * llvm::dwarf_linker::parallel::TypeEntryBody::create (<a href="/web-llvm/docs/api/namespaces/llvm/parallel/#a4e82d98d22361038741bca9bd34bca85">llvm::parallel::PerThreadBumpPtrAllocator</a> &amp; Allocator)</td>
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

<p>Creates type <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for the specified name.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/typepool-h">TypePool.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbasic-cpp/#ad5d00e1d77644d95847b9bf8da12b759">Allocator</a> and <a href="#a81e492d82a64eccb8c34be2d5bb0d8eb">TypeEntryBody</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typepool/#a4001c0dc6e6990fa6a0a2919e5db9068">llvm::dwarf_linker::parallel::TypePool::getOrCreateTypeEntryBody</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typepool/#a6839d6a080e53655c5952f319ca64256">llvm::dwarf_linker::parallel::TypePool::TypePool</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/typepool-h">TypePool.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
