---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/contextworklistitem
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ContextWorklistItem` Struct Reference

<p>This class represents an item in the work list. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::ContextWorklistItem { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79f599e8e764cfbb0fdd807f88fce7c8">ContextWorklistItem</a> (DWARFDie Die, ContextWorklistItemType T, CompileUnit::DIEInfo *OtherInfo=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a84ce93f65e459315ed3d92ed646d97">ContextWorklistItem</a> (DWARFDie Die, DeclContext *Context, unsigned ParentIdx, bool InImportedModule)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a862d854faaa0b2b0d27f44fdb785636a">Die</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a8673fef8926d6dc26b49ed727fd600">ParentIdx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/compileunit/dieinfo">CompileUnit::DIEInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bc9c63c9734c8c7d7822306b4c2beac">OtherInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/declcontext">DeclContext</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf54e3c115f6a44dcc026c893cd080f0">Context</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/structs/llvm/contextworklistitem">llvm::ContextWorklistItem</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a009cf74d50c58fc2b4c612542aae4aca"></a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ad5883fb838a32efa088e5cd355992fc1">ContextWorklistItemType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7678f2dc98b94e702a92baac0f3175fc">Type</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a508c1ba28bbae0cdb086a94f9c20c1de">InImportedModule</a></td>
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

<p>This class represents an item in the work list.</p>


<p>The type defines what kind of work needs to be performed when processing the current item. Everything but the <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> and Die fields are optional based on the type.</p>


<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ContextWorklistItem() {#a79f599e8e764cfbb0fdd807f88fce7c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ContextWorklistItem::ContextWorklistItem (<a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> Die, <a href="/web-llvm/docs/api/namespaces/llvm/#ad5883fb838a32efa088e5cd355992fc1">ContextWorklistItemType</a> T, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/compileunit/dieinfo">CompileUnit::DIEInfo</a> * OtherInfo=nullptr)</td>
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



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>


<p>References <a href="#a862d854faaa0b2b0d27f44fdb785636a">Die</a>, <a href="#a508c1ba28bbae0cdb086a94f9c20c1de">InImportedModule</a>, <a href="#a0bc9c63c9734c8c7d7822306b4c2beac">OtherInfo</a>, <a href="#a4a8673fef8926d6dc26b49ed727fd600">ParentIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="#a7678f2dc98b94e702a92baac0f3175fc">Type</a>.</p>

</div>
</div>

### ContextWorklistItem() {#a4a84ce93f65e459315ed3d92ed646d97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ContextWorklistItem::ContextWorklistItem (<a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> Die, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/declcontext">DeclContext</a> * Context, unsigned ParentIdx, bool InImportedModule)</td>
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



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad5883fb838a32efa088e5cd355992fc1a0f21fc12a5217183be792c5e6f3e00b5">llvm::AnalyzeContextInfo</a>, <a href="#abf54e3c115f6a44dcc026c893cd080f0">Context</a>, <a href="#a862d854faaa0b2b0d27f44fdb785636a">Die</a>, <a href="#a508c1ba28bbae0cdb086a94f9c20c1de">InImportedModule</a>, <a href="#a4a8673fef8926d6dc26b49ed727fd600">ParentIdx</a> and <a href="#a7678f2dc98b94e702a92baac0f3175fc">Type</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

###  {#a009cf74d50c58fc2b4c612542aae4aca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::ContextWorklistItem llvm::ContextWorklistItem</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### Context {#abf54e3c115f6a44dcc026c893cd080f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DeclContext* llvm::ContextWorklistItem::Context</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac7f4306c508478ca81791cbccef212fb">llvm::analyzeContextInfo</a> and <a href="#a4a84ce93f65e459315ed3d92ed646d97">ContextWorklistItem</a>.</p>

</div>
</div>

### Die {#a862d854faaa0b2b0d27f44fdb785636a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie llvm::ContextWorklistItem::Die</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac7f4306c508478ca81791cbccef212fb">llvm::analyzeContextInfo</a>, <a href="#a79f599e8e764cfbb0fdd807f88fce7c8">ContextWorklistItem</a> and <a href="#a4a84ce93f65e459315ed3d92ed646d97">ContextWorklistItem</a>.</p>

</div>
</div>

### InImportedModule {#a508c1ba28bbae0cdb086a94f9c20c1de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ContextWorklistItem::InImportedModule</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac7f4306c508478ca81791cbccef212fb">llvm::analyzeContextInfo</a>, <a href="#a79f599e8e764cfbb0fdd807f88fce7c8">ContextWorklistItem</a> and <a href="#a4a84ce93f65e459315ed3d92ed646d97">ContextWorklistItem</a>.</p>

</div>
</div>

### OtherInfo {#a0bc9c63c9734c8c7d7822306b4c2beac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CompileUnit::DIEInfo* llvm::ContextWorklistItem::OtherInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac7f4306c508478ca81791cbccef212fb">llvm::analyzeContextInfo</a> and <a href="#a79f599e8e764cfbb0fdd807f88fce7c8">ContextWorklistItem</a>.</p>

</div>
</div>

### ParentIdx {#a4a8673fef8926d6dc26b49ed727fd600}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ContextWorklistItem::ParentIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac7f4306c508478ca81791cbccef212fb">llvm::analyzeContextInfo</a>, <a href="#a79f599e8e764cfbb0fdd807f88fce7c8">ContextWorklistItem</a> and <a href="#a4a84ce93f65e459315ed3d92ed646d97">ContextWorklistItem</a>.</p>

</div>
</div>

### Type {#a7678f2dc98b94e702a92baac0f3175fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContextWorklistItemType llvm::ContextWorklistItem::Type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac7f4306c508478ca81791cbccef212fb">llvm::analyzeContextInfo</a>, <a href="#a79f599e8e764cfbb0fdd807f88fce7c8">ContextWorklistItem</a> and <a href="#a4a84ce93f65e459315ed3d92ed646d97">ContextWorklistItem</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
