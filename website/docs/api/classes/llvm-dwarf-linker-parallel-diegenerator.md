---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf-linker/parallel/diegenerator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DIEGenerator` Class Reference

<p>This class is a helper to create output <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> tree. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::dwarf_linker::parallel::DIEGenerator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/diegenerator-h">DWARFLinker/Parallel/DIEGenerator.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f9b8781d9d03294d1498f18806c9d4b">DIEGenerator</a> (BumpPtrAllocator &amp;Allocator, DwarfUnit &amp;CU)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a697095e1df1cb6b2421b8cd34e01cd95">DIEGenerator</a> (DIE *OutputDIE, BumpPtrAllocator &amp;Allocator, DwarfUnit &amp;CU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bcf59b48e896fea4f6661dffa7351da">createDIE</a> (dwarf::Tag DieTag, uint32_t OutOffset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> of specified tag <span class="doxyComputerOutput">DieTag</span> and <span class="doxyComputerOutput">OutOffset</span>. <a href="#a7bcf59b48e896fea4f6661dffa7351da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae83f8b1f70a7f9cab146f299626fae0d">getDIE</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18ef43d7a80b7abfe19ae9d6aae351e3">addChild</a> (DIE *Child)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a specified <span class="doxyComputerOutput">Child</span> to the current <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#a18ef43d7a80b7abfe19ae9d6aae351e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/dievalue">DIEValue</a> &amp;, size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af54f8f41713ea2fd258a3143440bda14">addScalarAttribute</a> (dwarf::Attribute Attr, dwarf::Form AttrForm, uint64_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds specified scalar attribute to the current <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#af54f8f41713ea2fd258a3143440bda14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/dievalue">DIEValue</a> &amp;, size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a2762a53f796809b0cc3f70b57024de">addLocationAttribute</a> (dwarf::Attribute Attr, dwarf::Form AttrForm, ArrayRef&lt; uint8_t &gt; Bytes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds specified location attribute to the current <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#a2a2762a53f796809b0cc3f70b57024de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/dievalue">DIEValue</a> &amp;, size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1f4ba74dc5112ee745cc214c2ae31b9">addBlockAttribute</a> (dwarf::Attribute Attr, dwarf::Form AttrForm, ArrayRef&lt; uint8_t &gt; Bytes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds specified block or exprloc attribute to the current <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#ac1f4ba74dc5112ee745cc214c2ae31b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/dievalue">DIEValue</a> &amp;, size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c2522c895b0dca9eda3f5f965dec438">addLocListAttribute</a> (dwarf::Attribute Attr, dwarf::Form AttrForm, uint64_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds specified location list attribute to the current <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#a3c2522c895b0dca9eda3f5f965dec438">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/dievalue">DIEValue</a> &amp;, size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab665f6c8b88a92c836ce9a99e7946c10">addIndexedStringAttribute</a> (dwarf::Attribute Attr, dwarf::Form AttrForm, uint64_t Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds indexed string attribute. <a href="#ab665f6c8b88a92c836ce9a99e7946c10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/dievalue">DIEValue</a> &amp;, size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e0b5008ca82c7f6a4b429d2ec441f7f">addStringPlaceholderAttribute</a> (dwarf::Attribute Attr, dwarf::Form AttrForm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds string attribute with dummy offset to the current <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#a4e0b5008ca82c7f6a4b429d2ec441f7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/dievalue">DIEValue</a> &amp;, size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb105b3b899c8d77d01daa58b6424cde">addInplaceString</a> (dwarf::Attribute Attr, StringRef String)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds inplace string attribute to the current <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#adb105b3b899c8d77d01daa58b6424cde">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af54251ec52387457926f12212d0364cb">finalizeAbbreviations</a> (bool CHILDREN_yes, OffsetsPtrVector *OffsetsList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates appreviations for the current <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#af54251ec52387457926f12212d0364cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa1658203b0434a19094e4ec4da85ecf8">addAttribute</a> (dwarf::Attribute Attr, dwarf::Form AttrForm, T &amp;&amp;Value) -&gt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/dievalue">DIEValue</a> &amp;, size_t &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46c47b22faf7b0baaa02f8cb903884db">Allocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit">DwarfUnit</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b5cc9a40cd529f34ad761803a21d2ca">CU</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbe5c7fb4ec782bb1f2891409995504d">OutputDIE</a> = nullptr</td>
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

<p>This class is a helper to create output <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> tree.</p>

<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/diegenerator-h">DIEGenerator.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DIEGenerator() {#a8f9b8781d9d03294d1498f18806c9d4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::DIEGenerator::DIEGenerator (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit">DwarfUnit</a> &amp; CU)</td>
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



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/diegenerator-h">DIEGenerator.h</a>.</p>


<p>Reference <a href="#a46c47b22faf7b0baaa02f8cb903884db">Allocator</a>.</p>

</div>
</div>

### DIEGenerator() {#a697095e1df1cb6b2421b8cd34e01cd95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::DIEGenerator::DIEGenerator (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * OutputDIE, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit">DwarfUnit</a> &amp; CU)</td>
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



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/diegenerator-h">DIEGenerator.h</a>.</p>


<p>References <a href="#a46c47b22faf7b0baaa02f8cb903884db">Allocator</a> and <a href="#acbe5c7fb4ec782bb1f2891409995504d">OutputDIE</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addBlockAttribute() {#ac1f4ba74dc5112ee745cc214c2ae31b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; DIEValue &amp;, size_t &gt; llvm::dwarf_linker::parallel::DIEGenerator::addBlockAttribute (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attr, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> AttrForm, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Bytes)</td>
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

<p>Adds specified block or exprloc attribute to the current <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/diegenerator-h">DIEGenerator.h</a>.</p>


<p>References <a href="#aa1658203b0434a19094e4ec4da85ecf8">addAttribute</a>, <a href="#a46c47b22faf7b0baaa02f8cb903884db">Allocator</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### addChild() {#a18ef43d7a80b7abfe19ae9d6aae351e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::DIEGenerator::addChild (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * Child)</td>
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

<p>Adds a specified <span class="doxyComputerOutput">Child</span> to the current <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/diegenerator-h">DIEGenerator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#acbe5c7fb4ec782bb1f2891409995504d">OutputDIE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a1df1c26e0a60f062547d6ba537e0021a">llvm::dwarf_linker::parallel::CompileUnit::cloneDIE</a>.</p>

</div>
</div>

### addIndexedStringAttribute() {#ab665f6c8b88a92c836ce9a99e7946c10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; DIEValue &amp;, size_t &gt; llvm::dwarf_linker::parallel::DIEGenerator::addIndexedStringAttribute (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attr, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> AttrForm, uint64_t Idx)</td>
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

<p>Adds indexed string attribute.</p>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/diegenerator-h">DIEGenerator.h</a>.</p>


<p>References <a href="#aa1658203b0434a19094e4ec4da85ecf8">addAttribute</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### addInplaceString() {#adb105b3b899c8d77d01daa58b6424cde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; DIEValue &amp;, size_t &gt; llvm::dwarf_linker::parallel::DIEGenerator::addInplaceString (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attr, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> String)</td>
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

<p>Adds inplace string attribute to the current <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/diegenerator-h">DIEGenerator.h</a>.</p>


<p>References <a href="#a46c47b22faf7b0baaa02f8cb903884db">Allocator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="#acbe5c7fb4ec782bb1f2891409995504d">OutputDIE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a>.</p>

</div>
</div>

### addLocationAttribute() {#a2a2762a53f796809b0cc3f70b57024de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; DIEValue &amp;, size_t &gt; llvm::dwarf_linker::parallel::DIEGenerator::addLocationAttribute (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attr, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> AttrForm, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Bytes)</td>
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

<p>Adds specified location attribute to the current <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/diegenerator-h">DIEGenerator.h</a>.</p>


<p>References <a href="#aa1658203b0434a19094e4ec4da85ecf8">addAttribute</a>, <a href="#a46c47b22faf7b0baaa02f8cb903884db">Allocator</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### addLocListAttribute() {#a3c2522c895b0dca9eda3f5f965dec438}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; DIEValue &amp;, size_t &gt; llvm::dwarf_linker::parallel::DIEGenerator::addLocListAttribute (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attr, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> AttrForm, uint64_t Value)</td>
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

<p>Adds specified location list attribute to the current <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/diegenerator-h">DIEGenerator.h</a>.</p>


<p>Reference <a href="#aa1658203b0434a19094e4ec4da85ecf8">addAttribute</a>.</p>

</div>
</div>

### addScalarAttribute() {#af54f8f41713ea2fd258a3143440bda14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; DIEValue &amp;, size_t &gt; llvm::dwarf_linker::parallel::DIEGenerator::addScalarAttribute (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attr, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> AttrForm, uint64_t Value)</td>
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

<p>Adds specified scalar attribute to the current <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/diegenerator-h">DIEGenerator.h</a>.</p>


<p>Reference <a href="#aa1658203b0434a19094e4ec4da85ecf8">addAttribute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#aafd0fac7574417fa923ca2bce4b9b85c">llvm::dwarf_linker::parallel::TypeUnit::createDIETree</a>.</p>

</div>
</div>

### addStringPlaceholderAttribute() {#a4e0b5008ca82c7f6a4b429d2ec441f7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; DIEValue &amp;, size_t &gt; llvm::dwarf_linker::parallel::DIEGenerator::addStringPlaceholderAttribute (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attr, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> AttrForm)</td>
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

<p>Adds string attribute with dummy offset to the current <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/diegenerator-h">DIEGenerator.h</a>.</p>


<p>References <a href="#aa1658203b0434a19094e4ec4da85ecf8">addAttribute</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#aafd0fac7574417fa923ca2bce4b9b85c">llvm::dwarf_linker::parallel::TypeUnit::createDIETree</a>.</p>

</div>
</div>

### createDIE() {#a7bcf59b48e896fea4f6661dffa7351da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * llvm::dwarf_linker::parallel::DIEGenerator::createDIE (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a> DieTag, uint32_t OutOffset)</td>
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

<p>Creates a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> of specified tag <span class="doxyComputerOutput">DieTag</span> and <span class="doxyComputerOutput">OutOffset</span>.</p>

<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/diegenerator-h">DIEGenerator.h</a>.</p>


<p>References <a href="#a46c47b22faf7b0baaa02f8cb903884db">Allocator</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#a75692ef0b9a881db75fc0e0a79db0d1d">llvm::DIE::get</a> and <a href="#acbe5c7fb4ec782bb1f2891409995504d">OutputDIE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#aafd0fac7574417fa923ca2bce4b9b85c">llvm::dwarf_linker::parallel::TypeUnit::createDIETree</a>.</p>

</div>
</div>

### finalizeAbbreviations() {#af54251ec52387457926f12212d0364cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::dwarf_linker::parallel::DIEGenerator::finalizeAbbreviations (bool CHILDREN_yes, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#ad2dde002b59709a633439269e84fb29c">OffsetsPtrVector</a> * OffsetsList)</td>
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

<p>Creates appreviations for the current <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>


<p>Returns value of abbreviation number. Updates offsets with the size of abbreviation number.</p>


<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/diegenerator-h">DIEGenerator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255a4b8a3f1fe8eed309f0b034064b508050">llvm::dwarf::DW_CHILDREN_yes</a>, <a href="/web-llvm/docs/api/classes/llvm/dieabbrev/#a2618aa0a10d4d37dfa2ac6b501f3d5a6">llvm::DIEAbbrev::getNumber</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa02a1d8fb0f561ab81f4a2570db7dc28">llvm::getULEB128Size</a>, <a href="#acbe5c7fb4ec782bb1f2891409995504d">OutputDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dieabbrev/#abca8271405f016128079b0f282f66b9e">llvm::DIEAbbrev::setChildrenFlag</a>.</p>

</div>
</div>

### getDIE() {#ae83f8b1f70a7f9cab146f299626fae0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * llvm::dwarf_linker::parallel::DIEGenerator::getDIE ()</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/diegenerator-h">DIEGenerator.h</a>.</p>


<p>Reference <a href="#acbe5c7fb4ec782bb1f2891409995504d">OutputDIE</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### addAttribute() {#aa1658203b0434a19094e4ec4da85ecf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; DIEValue &amp;, size_t &gt; llvm::dwarf_linker::parallel::DIEGenerator::addAttribute (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attr, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> AttrForm, T &amp;&amp; Value)</td>
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



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/diegenerator-h">DIEGenerator.h</a>.</p>


<p>References <a href="#a46c47b22faf7b0baaa02f8cb903884db">Allocator</a>, <a href="#acbe5c7fb4ec782bb1f2891409995504d">OutputDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dievalue/#a27eed3dd7fafd0c35e8ed73bbeac5514">llvm::DIEValue::sizeOf</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#ac1f4ba74dc5112ee745cc214c2ae31b9">addBlockAttribute</a>, <a href="#ab665f6c8b88a92c836ce9a99e7946c10">addIndexedStringAttribute</a>, <a href="#a2a2762a53f796809b0cc3f70b57024de">addLocationAttribute</a>, <a href="#a3c2522c895b0dca9eda3f5f965dec438">addLocListAttribute</a>, <a href="#af54f8f41713ea2fd258a3143440bda14">addScalarAttribute</a> and <a href="#a4e0b5008ca82c7f6a4b429d2ec441f7f">addStringPlaceholderAttribute</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Allocator {#a46c47b22faf7b0baaa02f8cb903884db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator&amp; llvm::dwarf_linker::parallel::DIEGenerator::Allocator</td>
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



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/diegenerator-h">DIEGenerator.h</a>.</p>


<p>Referenced by <a href="#aa1658203b0434a19094e4ec4da85ecf8">addAttribute</a>, <a href="#ac1f4ba74dc5112ee745cc214c2ae31b9">addBlockAttribute</a>, <a href="#adb105b3b899c8d77d01daa58b6424cde">addInplaceString</a>, <a href="#a2a2762a53f796809b0cc3f70b57024de">addLocationAttribute</a>, <a href="#a7bcf59b48e896fea4f6661dffa7351da">createDIE</a>, <a href="#a8f9b8781d9d03294d1498f18806c9d4b">DIEGenerator</a> and <a href="#a697095e1df1cb6b2421b8cd34e01cd95">DIEGenerator</a>.</p>

</div>
</div>

### CU {#a8b5cc9a40cd529f34ad761803a21d2ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfUnit&amp; llvm::dwarf_linker::parallel::DIEGenerator::CU</td>
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



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/diegenerator-h">DIEGenerator.h</a>.</p>

</div>
</div>

### OutputDIE {#acbe5c7fb4ec782bb1f2891409995504d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE* llvm::dwarf_linker::parallel::DIEGenerator::OutputDIE = nullptr</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/diegenerator-h">DIEGenerator.h</a>.</p>


<p>Referenced by <a href="#aa1658203b0434a19094e4ec4da85ecf8">addAttribute</a>, <a href="#a18ef43d7a80b7abfe19ae9d6aae351e3">addChild</a>, <a href="#adb105b3b899c8d77d01daa58b6424cde">addInplaceString</a>, <a href="#a7bcf59b48e896fea4f6661dffa7351da">createDIE</a>, <a href="#a697095e1df1cb6b2421b8cd34e01cd95">DIEGenerator</a>, <a href="#af54251ec52387457926f12212d0364cb">finalizeAbbreviations</a> and <a href="#ae83f8b1f70a7f9cab146f299626fae0d">getDIE</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/diegenerator-h">DIEGenerator.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
