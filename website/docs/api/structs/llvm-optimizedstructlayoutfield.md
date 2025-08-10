---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/optimizedstructlayoutfield
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `OptimizedStructLayoutField` Struct

<p>A field in a structure. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::OptimizedStructLayoutField { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/optimizedstructlayout-h">llvm/Support/OptimizedStructLayout.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add77194e307eeb1f4ac9099ea63ef922">OptimizedStructLayoutField</a> (const void *Id, uint64_t Size, Align Alignment, uint64_t FixedOffset=FlexibleOffset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf43399e1cbcadbb63dd9b33a3eac938">hasFixedOffset</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this field has been assigned a fixed offset. <a href="#acf43399e1cbcadbb63dd9b33a3eac938">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33aaa97d3e6098e4106d1fdecee2dc1d">getEndOffset</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given that this field has a fixed offset, return the offset of the first byte following it. <a href="#a33aaa97d3e6098e4106d1fdecee2dc1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adae4afc395aed3ab340d695de637dd11">Offset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The offset of this field in the final layout. <a href="#adae4afc395aed3ab340d695de637dd11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae472b245af5bd4a76bea7581ea772185">Size</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The required size of this field in bytes. <a href="#ae472b245af5bd4a76bea7581ea772185">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2950e642905cbcf7104abd58ab797e26">Id</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A opaque value which uniquely identifies this field. <a href="#a2950e642905cbcf7104abd58ab797e26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a432caecc9417394c69f599b6476febdb">Scratch</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Private scratch space for the algorithm. <a href="#a432caecc9417394c69f599b6476febdb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31b084098ebbf47988d1817a597b52d2">Alignment</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The required alignment of this field. <a href="#a31b084098ebbf47988d1817a597b52d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd2b6f2791d97f9d64eb5ad7972cd28b">FlexibleOffset</a> = ~(uint64_t)0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A special value for Offset indicating that the field can be moved anywhere. <a href="#afd2b6f2791d97f9d64eb5ad7972cd28b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A field in a structure.</p>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/optimizedstructlayout-h">OptimizedStructLayout.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### OptimizedStructLayoutField() {#add77194e307eeb1f4ac9099ea63ef922}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OptimizedStructLayoutField::OptimizedStructLayoutField (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * Id, uint64_t Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, uint64_t FixedOffset=<a href="#afd2b6f2791d97f9d64eb5ad7972cd28b">FlexibleOffset</a>)</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/optimizedstructlayout-h">OptimizedStructLayout.h</a>.</p>


<p>References <a href="#a31b084098ebbf47988d1817a597b52d2">Alignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afd2b6f2791d97f9d64eb5ad7972cd28b">FlexibleOffset</a>, <a href="#a2950e642905cbcf7104abd58ab797e26">Id</a>, <a href="#adae4afc395aed3ab340d695de637dd11">Offset</a> and <a href="#ae472b245af5bd4a76bea7581ea772185">Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getEndOffset() {#a33aaa97d3e6098e4106d1fdecee2dc1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::OptimizedStructLayoutField::getEndOffset ()</td>
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

<p>Given that this field has a fixed offset, return the offset of the first byte following it.</p>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/optimizedstructlayout-h">OptimizedStructLayout.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#acf43399e1cbcadbb63dd9b33a3eac938">hasFixedOffset</a>, <a href="#adae4afc395aed3ab340d695de637dd11">Offset</a> and <a href="#ae472b245af5bd4a76bea7581ea772185">Size</a>.</p>

</div>
</div>

### hasFixedOffset() {#acf43399e1cbcadbb63dd9b33a3eac938}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OptimizedStructLayoutField::hasFixedOffset ()</td>
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

<p>Return true if this field has been assigned a fixed offset.</p>


<p>After layout, this will be true of all the fields.</p>


<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/optimizedstructlayout-h">OptimizedStructLayout.h</a>.</p>


<p>References <a href="#afd2b6f2791d97f9d64eb5ad7972cd28b">FlexibleOffset</a> and <a href="#adae4afc395aed3ab340d695de637dd11">Offset</a>.</p>


<p>Referenced by <a href="#a33aaa97d3e6098e4106d1fdecee2dc1d">getEndOffset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Alignment {#a31b084098ebbf47988d1817a597b52d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::OptimizedStructLayoutField::Alignment</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The required alignment of this field.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/optimizedstructlayout-h">OptimizedStructLayout.h</a>.</p>


<p>Referenced by <a href="#add77194e307eeb1f4ac9099ea63ef922">OptimizedStructLayoutField</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aae35ec9b920ff3bb892cd872877a89fe">llvm::performOptimizedStructLayout</a>.</p>

</div>
</div>

### Id {#a2950e642905cbcf7104abd58ab797e26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const void* llvm::OptimizedStructLayoutField::Id</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A opaque value which uniquely identifies this field.</p>

<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/optimizedstructlayout-h">OptimizedStructLayout.h</a>.</p>


<p>Referenced by <a href="#add77194e307eeb1f4ac9099ea63ef922">OptimizedStructLayoutField</a>.</p>

</div>
</div>

### Offset {#adae4afc395aed3ab340d695de637dd11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::OptimizedStructLayoutField::Offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The offset of this field in the final layout.</p>


<p>If this is initialized to FlexibleOffset, layout will overwrite it with the assigned offset of the field.</p>


<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/optimizedstructlayout-h">OptimizedStructLayout.h</a>.</p>


<p>Referenced by <a href="#a33aaa97d3e6098e4106d1fdecee2dc1d">getEndOffset</a>, <a href="#acf43399e1cbcadbb63dd9b33a3eac938">hasFixedOffset</a> and <a href="#add77194e307eeb1f4ac9099ea63ef922">OptimizedStructLayoutField</a>.</p>

</div>
</div>

### Scratch {#a432caecc9417394c69f599b6476febdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* llvm::OptimizedStructLayoutField::Scratch</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Private scratch space for the algorithm.</p>


<p>The implementation must treat this as uninitialized memory on entry.</p>


<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/optimizedstructlayout-h">OptimizedStructLayout.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aae35ec9b920ff3bb892cd872877a89fe">llvm::performOptimizedStructLayout</a>.</p>

</div>
</div>

### Size {#ae472b245af5bd4a76bea7581ea772185}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::OptimizedStructLayoutField::Size</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The required size of this field in bytes.</p>


<p>Does not have to be a multiple of Alignment. Must be non-zero.</p>


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/optimizedstructlayout-h">OptimizedStructLayout.h</a>.</p>


<p>Referenced by <a href="#a33aaa97d3e6098e4106d1fdecee2dc1d">getEndOffset</a>, <a href="#add77194e307eeb1f4ac9099ea63ef922">OptimizedStructLayoutField</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aae35ec9b920ff3bb892cd872877a89fe">llvm::performOptimizedStructLayout</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### FlexibleOffset {#afd2b6f2791d97f9d64eb5ad7972cd28b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::OptimizedStructLayoutField::FlexibleOffset = ~(uint64_t)0</td>
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

<p>A special value for Offset indicating that the field can be moved anywhere.</p>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/optimizedstructlayout-h">OptimizedStructLayout.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-coroframe-cpp-/frametypebuilder/#a5c96118e25d97e97ae778fb8084e4154">anonymous{CoroFrame.cpp}::FrameTypeBuilder::addField</a>, <a href="#acf43399e1cbcadbb63dd9b33a3eac938">hasFixedOffset</a> and <a href="#add77194e307eeb1f4ac9099ea63ef922">OptimizedStructLayoutField</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/optimizedstructlayout-h">OptimizedStructLayout.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
