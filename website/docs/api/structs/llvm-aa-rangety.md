---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/aa/rangety
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `RangeTy` Struct

<p>Helper to represent an access offset and size, with logic to deal with uncertainty and check for overlapping accesses. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::AA::RangeTy { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">llvm/Transforms/IPO/Attributor.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace9f05921f46ee75df674bf4d0830e64">RangeTy</a> (int64_t Offset, int64_t Size)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f4d6ff3eb39e0064f044f8595c5ffc5">RangeTy</a> ()=default</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aa/rangety">RangeTy</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a8a17defa5969b353cd0a46a8d17c3c">operator&amp;=</a> (const RangeTy &amp;R)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5182e1587d800f1eb2ca55e0a260ad2d">offsetOrSizeAreUnknown</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if offset or size are unknown. <a href="#a5182e1587d800f1eb2ca55e0a260ad2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a114514451120f7aa9912d64a3b4a0b13">offsetAndSizeAreUnknown</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if offset and size are unknown, thus this is the default unknown object. <a href="#a114514451120f7aa9912d64a3b4a0b13">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4cf377e484d8cd4532d20a9207411a1">isUnassigned</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the offset and size are unassigned. <a href="#aa4cf377e484d8cd4532d20a9207411a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdeb096302d5c627eadefa472e141bcf">mayOverlap</a> (const RangeTy &amp;Range) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this offset and size pair might describe an address that overlaps with <span class="doxyComputerOutput">Range</span>. <a href="#abdeb096302d5c627eadefa472e141bcf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8b6601a2aaaa9968df053e679f85f58">Offset</a> = <a href="#a5960fe0f64e0af63e9cbddb4ab880b7f">Unassigned</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acee729b7583c1c81e9dd37ecf52b1940">Size</a> = <a href="#a5960fe0f64e0af63e9cbddb4ab880b7f">Unassigned</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/aa/rangety">RangeTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a2f37da6d4fb687896f10c0877386d5">getUnknown</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2e2c8f6c3c630eaf624e5b9589b8c9f">LessThan</a> (const RangeTy &amp;L, const RangeTy &amp;R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Comparison for sorting ranges. <a href="#ab2e2c8f6c3c630eaf624e5b9589b8c9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5960fe0f64e0af63e9cbddb4ab880b7f">Unassigned</a> = std::numeric_limits&lt;int32_t&gt;::min()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constants used to represent special offsets or sizes. <a href="#a5960fe0f64e0af63e9cbddb4ab880b7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a61943cb8a1b4b07da2b2edeb9cf51c">Unknown</a> = std::numeric_limits&lt;int32_t&gt;<a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">::max</a>()</td>
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

<p>Helper to represent an access offset and size, with logic to deal with uncertainty and check for overlapping accesses.</p>

<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RangeTy() {#ace9f05921f46ee75df674bf4d0830e64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AA::RangeTy::RangeTy (int64_t Offset, int64_t Size)</td>
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



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#ad8b6601a2aaaa9968df053e679f85f58">Offset</a> and <a href="#acee729b7583c1c81e9dd37ecf52b1940">Size</a>.</p>


<p>Referenced by <a href="#a7a2f37da6d4fb687896f10c0877386d5">getUnknown</a>, <a href="#ab2e2c8f6c3c630eaf624e5b9589b8c9f">LessThan</a>, <a href="#abdeb096302d5c627eadefa472e141bcf">mayOverlap</a> and <a href="#a5a8a17defa5969b353cd0a46a8d17c3c">operator&amp;=</a>.</p>

</div>
</div>

### RangeTy() {#a6f4d6ff3eb39e0064f044f8595c5ffc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AA::RangeTy::RangeTy ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator&amp;=() {#a5a8a17defa5969b353cd0a46a8d17c3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RangeTy &amp; llvm::AA::RangeTy::operator&amp;= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aa/rangety">RangeTy</a> &amp; R)</td>
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



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#aa4cf377e484d8cd4532d20a9207411a1">isUnassigned</a>, <a href="#ad8b6601a2aaaa9968df053e679f85f58">Offset</a>, <a href="#a114514451120f7aa9912d64a3b4a0b13">offsetAndSizeAreUnknown</a>, <a href="#ace9f05921f46ee75df674bf4d0830e64">RangeTy</a>, <a href="#acee729b7583c1c81e9dd37ecf52b1940">Size</a> and <a href="#a3a61943cb8a1b4b07da2b2edeb9cf51c">Unknown</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isUnassigned() {#aa4cf377e484d8cd4532d20a9207411a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AA::RangeTy::isUnassigned ()</td>
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

<p>Return true if the offset and size are unassigned.</p>

<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad8b6601a2aaaa9968df053e679f85f58">Offset</a>, <a href="#acee729b7583c1c81e9dd37ecf52b1940">Size</a> and <a href="#a5960fe0f64e0af63e9cbddb4ab880b7f">Unassigned</a>.</p>


<p>Referenced by <a href="#a5a8a17defa5969b353cd0a46a8d17c3c">operator&amp;=</a>.</p>

</div>
</div>

### mayOverlap() {#abdeb096302d5c627eadefa472e141bcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AA::RangeTy::mayOverlap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aa/rangety">RangeTy</a> &amp; Range)</td>
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

<p>Return true if this offset and size pair might describe an address that overlaps with <span class="doxyComputerOutput">Range</span>.</p>

<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#ad8b6601a2aaaa9968df053e679f85f58">Offset</a>, <a href="#a5182e1587d800f1eb2ca55e0a260ad2d">offsetOrSizeAreUnknown</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="#ace9f05921f46ee75df674bf4d0830e64">RangeTy</a> and <a href="#acee729b7583c1c81e9dd37ecf52b1940">Size</a>.</p>

</div>
</div>

### offsetAndSizeAreUnknown() {#a114514451120f7aa9912d64a3b4a0b13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AA::RangeTy::offsetAndSizeAreUnknown ()</td>
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

<p>Return true if offset and size are unknown, thus this is the default unknown object.</p>

<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#ad8b6601a2aaaa9968df053e679f85f58">Offset</a>, <a href="#acee729b7583c1c81e9dd37ecf52b1940">Size</a> and <a href="#a3a61943cb8a1b4b07da2b2edeb9cf51c">Unknown</a>.</p>


<p>Referenced by <a href="#a5a8a17defa5969b353cd0a46a8d17c3c">operator&amp;=</a>.</p>

</div>
</div>

### offsetOrSizeAreUnknown() {#a5182e1587d800f1eb2ca55e0a260ad2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AA::RangeTy::offsetOrSizeAreUnknown ()</td>
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

<p>Return true if offset or size are unknown.</p>

<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#ad8b6601a2aaaa9968df053e679f85f58">Offset</a>, <a href="#acee729b7583c1c81e9dd37ecf52b1940">Size</a> and <a href="#a3a61943cb8a1b4b07da2b2edeb9cf51c">Unknown</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/aa/#abdc024165477822f664fda55551f8a66">llvm::AA::getInitialValueForObj</a> and <a href="#abdeb096302d5c627eadefa472e141bcf">mayOverlap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Offset {#ad8b6601a2aaaa9968df053e679f85f58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::AA::RangeTy::Offset = <a href="#a5960fe0f64e0af63e9cbddb4ab880b7f">Unassigned</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/aa/#abdc024165477822f664fda55551f8a66">llvm::AA::getInitialValueForObj</a>, <a href="#aa4cf377e484d8cd4532d20a9207411a1">isUnassigned</a>, <a href="#abdeb096302d5c627eadefa472e141bcf">mayOverlap</a>, <a href="#a114514451120f7aa9912d64a3b4a0b13">offsetAndSizeAreUnknown</a>, <a href="#a5182e1587d800f1eb2ca55e0a260ad2d">offsetOrSizeAreUnknown</a>, <a href="#a5a8a17defa5969b353cd0a46a8d17c3c">operator&amp;=</a> and <a href="#ace9f05921f46ee75df674bf4d0830e64">RangeTy</a>.</p>

</div>
</div>

### Size {#acee729b7583c1c81e9dd37ecf52b1940}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::AA::RangeTy::Size = <a href="#a5960fe0f64e0af63e9cbddb4ab880b7f">Unassigned</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="#aa4cf377e484d8cd4532d20a9207411a1">isUnassigned</a>, <a href="#abdeb096302d5c627eadefa472e141bcf">mayOverlap</a>, <a href="#a114514451120f7aa9912d64a3b4a0b13">offsetAndSizeAreUnknown</a>, <a href="#a5182e1587d800f1eb2ca55e0a260ad2d">offsetOrSizeAreUnknown</a>, <a href="#a5a8a17defa5969b353cd0a46a8d17c3c">operator&amp;=</a> and <a href="#ace9f05921f46ee75df674bf4d0830e64">RangeTy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getUnknown() {#a7a2f37da6d4fb687896f10c0877386d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RangeTy llvm::AA::RangeTy::getUnknown ()</td>
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



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#ace9f05921f46ee75df674bf4d0830e64">RangeTy</a> and <a href="#a3a61943cb8a1b4b07da2b2edeb9cf51c">Unknown</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/rangelist/#ad31ac44d4ac99ee1ee463e3d37960788">llvm::AAPointerInfo::RangeList::setUnknown</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#afa9d4327193a1cc24ab70233ec67af82">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::translateAndAddState</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfocallsiteargument/#afd64f56df116f9c6c4763b55bf74897a">anonymous{AttributorAttributes.cpp}::AAPointerInfoCallSiteArgument::updateImpl</a>.</p>

</div>
</div>

### LessThan() {#ab2e2c8f6c3c630eaf624e5b9589b8c9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AA::RangeTy::LessThan (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aa/rangety">RangeTy</a> &amp; L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aa/rangety">RangeTy</a> &amp; R)</td>
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

<p>Comparison for sorting ranges.</p>


<p>Returns true if the offset of <span class="doxyComputerOutput">L</span> is less than that of <span class="doxyComputerOutput">R</span>. If the two offsets are same, compare the sizes instead.</p>


<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="#ace9f05921f46ee75df674bf4d0830e64">RangeTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/rangelist/#a52b05098bc5781643855cd42e1d5184c">llvm::AAPointerInfo::RangeList::insert</a>, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/rangelist/#ae31e931475cf0de72f221a29708d6314">llvm::AAPointerInfo::RangeList::push_back</a> and <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/rangelist/#ac1944e462953413d1cac710fc359c1cb">llvm::AAPointerInfo::RangeList::set_difference</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### Unassigned {#a5960fe0f64e0af63e9cbddb4ab880b7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::AA::RangeTy::Unassigned = std::numeric_limits&lt;int32_t&gt;::min()</td>
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

<p>Constants used to represent special offsets or sizes.</p>


<ul class="doxyList ">
<li>We cannot assume that Offsets and Size are non-negative.</li>
<li>The constants should not clash with <a href="/web-llvm/docs/api/structs/llvm/densemapinfo">DenseMapInfo</a>, such as EmptyKey (INT64_MAX) and TombstoneKey (INT64_MIN). We use values "in the middle" of the 64 bit range to represent these special cases.</li>
</ul>

<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="#aa4cf377e484d8cd4532d20a9207411a1">isUnassigned</a>.</p>

</div>
</div>

### Unknown {#a3a61943cb8a1b4b07da2b2edeb9cf51c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::AA::RangeTy::Unknown = std::numeric_limits&lt;int32_t&gt;<a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">::max</a>()</td>
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



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="#a7a2f37da6d4fb687896f10c0877386d5">getUnknown</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a272cd16957d147ad113779617eeabf77">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::handleAccess</a>, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/offsetinfo/#a84931776d6bfa263f9066657ec3ccc0e">llvm::AAPointerInfo::OffsetInfo::isUnknown</a>, <a href="#a114514451120f7aa9912d64a3b4a0b13">offsetAndSizeAreUnknown</a>, <a href="#a5182e1587d800f1eb2ca55e0a260ad2d">offsetOrSizeAreUnknown</a>, <a href="#a5a8a17defa5969b353cd0a46a8d17c3c">operator&amp;=</a>, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/offsetinfo/#a0ffc9e3ce7217e6b65ccb47a5acb0f02">llvm::AAPointerInfo::OffsetInfo::setUnknown</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#afa9d4327193a1cc24ab70233ec67af82">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::translateAndAddState</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfocallsiteargument/#afd64f56df116f9c6c4763b55bf74897a">anonymous{AttributorAttributes.cpp}::AAPointerInfoCallSiteArgument::updateImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
