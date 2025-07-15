---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dwarf-linker/parallel/arraylist/itemsgroup
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ItemsGroup` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::dwarf_linker::parallel::ArrayList::ItemsGroup { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/arraylist-h">DWARFLinker/Parallel/ArrayList.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29800b02a2baf858a5fe15c90c714f2f">ArrayTy</a> = std::array&lt; T, ItemsGroupSize &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9e89ae010ebb7816972b1ef17e1a6a9">getItemsCount</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">ArrayTy::iterator</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace40d57733365050bf57d1bfbe839f1a">begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">ArrayTy::iterator</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6db0d5ef5dbd748ee9042a0f336ce77">end</a> ()</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a29800b02a2baf858a5fe15c90c714f2f">ArrayTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26c1fa2bf8cac04ab8ef503edf349c03">Items</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::atomic&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/arraylist/itemsgroup">ItemsGroup</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2b097065cbd9e8fe9695ded1c5a8e1f">Next</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::atomic&lt; size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6274095c04d4e37093643dd5df6945e6">ItemsCount</a> = 0</td>
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


<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/arraylist-h">ArrayList.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ArrayTy {#a29800b02a2baf858a5fe15c90c714f2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::ItemsGroup::ArrayTy =  std::array&lt;T, ItemsGroupSize&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/arraylist-h">ArrayList.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#ace40d57733365050bf57d1bfbe839f1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayTy::iterator llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::ItemsGroup::begin ()</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/arraylist-h">ArrayList.h</a>.</p>


<p>Reference <a href="#a26c1fa2bf8cac04ab8ef503edf349c03">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::ItemsGroup::Items</a>.</p>

</div>
</div>

### end() {#ac6db0d5ef5dbd748ee9042a0f336ce77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayTy::iterator llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::ItemsGroup::end ()</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/arraylist-h">ArrayList.h</a>.</p>


<p>References <a href="#ad9e89ae010ebb7816972b1ef17e1a6a9">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::ItemsGroup::getItemsCount</a> and <a href="#a26c1fa2bf8cac04ab8ef503edf349c03">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::ItemsGroup::Items</a>.</p>

</div>
</div>

### getItemsCount() {#ad9e89ae010ebb7816972b1ef17e1a6a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::ItemsGroup::getItemsCount ()</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/arraylist-h">ArrayList.h</a>.</p>


<p>Reference <a href="#a6274095c04d4e37093643dd5df6945e6">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::ItemsGroup::ItemsCount</a>.</p>


<p>Referenced by <a href="#ac6db0d5ef5dbd748ee9042a0f336ce77">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::ItemsGroup::end</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Items {#a26c1fa2bf8cac04ab8ef503edf349c03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayTy llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::ItemsGroup::Items</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/arraylist-h">ArrayList.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/arraylist/#a3055e7b57c17c6988622279667b77088">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::add</a>, <a href="#ace40d57733365050bf57d1bfbe839f1a">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::ItemsGroup::begin</a> and <a href="#ac6db0d5ef5dbd748ee9042a0f336ce77">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::ItemsGroup::end</a>.</p>

</div>
</div>

### ItemsCount {#a6274095c04d4e37093643dd5df6945e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::atomic&lt;size_t&gt; llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::ItemsGroup::ItemsCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/arraylist-h">ArrayList.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/arraylist/#a3055e7b57c17c6988622279667b77088">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::add</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/arraylist/#a5884ad133d07d8bd3f0f24d37a93bff8">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::allocateNewGroup</a> and <a href="#ad9e89ae010ebb7816972b1ef17e1a6a9">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::ItemsGroup::getItemsCount</a>.</p>

</div>
</div>

### Next {#aa2b097065cbd9e8fe9695ded1c5a8e1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::atomic&lt;ItemsGroup *&gt; llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::ItemsGroup::Next = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/arraylist-h">ArrayList.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/arraylist/#a3055e7b57c17c6988622279667b77088">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::add</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/arraylist/#a5884ad133d07d8bd3f0f24d37a93bff8">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::allocateNewGroup</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/arraylist-h">ArrayList.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
