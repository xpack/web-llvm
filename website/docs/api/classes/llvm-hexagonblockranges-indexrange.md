---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/hexagonblockranges/indexrange
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `IndexRange` Class



## Declaration

<div class="doxyDeclaration">
class llvm::HexagonBlockRanges::IndexRange { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-h">Target/Hexagon/HexagonBlockRanges.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::pair&lt; IndexType, IndexType &gt;</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a896da44ea93b1652fe22b18402cb6862">IndexRange</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c5fc1bacd1e895d5e4b30cdf7e8e0f9">IndexRange</a> (IndexType Start, IndexType End, bool F=false, bool T=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76cf0a0c219b8e32dd0e536e29e18230">operator&lt;</a> (const IndexRange &amp;A) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/indextype">IndexType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d3eefbe3c5753f56041805c343b094e">start</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/indextype">IndexType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca59ba8f0683a6ab7f08ade1f4658bba">end</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c68ec020f9529a22c70a6528950da1d">overlaps</a> (const IndexRange &amp;A) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0966222cb0d2b18634eb3aa9c412f49">contains</a> (const IndexRange &amp;A) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a130d144a312addfffe2600000ddef06d">merge</a> (const IndexRange &amp;A)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a507654af7e68978931f217b021e17377">setStart</a> (const IndexType &amp;S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd3748c522dd9cd7b25eca791e23eeb3">setEnd</a> (const IndexType &amp;E)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4f32d7f0cfe00ffef0085a350d2b1b1">Fixed</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa171f135bca180deea52a78722ca1a2e">TiedEnd</a> = false</td>
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


<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-h">HexagonBlockRanges.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### IndexRange() {#a896da44ea93b1652fe22b18402cb6862}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::HexagonBlockRanges::IndexRange::IndexRange ()</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-h">HexagonBlockRanges.h</a>.</p>


<p>Referenced by <a href="#ab0966222cb0d2b18634eb3aa9c412f49">contains</a>, <a href="#a130d144a312addfffe2600000ddef06d">merge</a>, <a href="#a76cf0a0c219b8e32dd0e536e29e18230">operator&lt;</a> and <a href="#a7c68ec020f9529a22c70a6528950da1d">overlaps</a>.</p>

</div>
</div>

### IndexRange() {#a4c5fc1bacd1e895d5e4b30cdf7e8e0f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::HexagonBlockRanges::IndexRange::IndexRange (<a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/indextype">IndexType</a> Start, <a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/indextype">IndexType</a> End, bool F=false, bool T=false)</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-h">HexagonBlockRanges.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#ad4f32d7f0cfe00ffef0085a350d2b1b1">Fixed</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="#aa171f135bca180deea52a78722ca1a2e">TiedEnd</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator&lt;() {#a76cf0a0c219b8e32dd0e536e29e18230}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonBlockRanges::IndexRange::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/indexrange">IndexRange</a> &amp; A)</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-h">HexagonBlockRanges.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a896da44ea93b1652fe22b18402cb6862">IndexRange</a> and <a href="#a0d3eefbe3c5753f56041805c343b094e">start</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### contains() {#ab0966222cb0d2b18634eb3aa9c412f49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonBlockRanges::IndexRange::contains (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/indexrange">IndexRange</a> &amp; A)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-h">HexagonBlockRanges.h</a>, definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-cpp">HexagonBlockRanges.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#aca59ba8f0683a6ab7f08ade1f4658bba">end</a>, <a href="#a896da44ea93b1652fe22b18402cb6862">IndexRange</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/indextype/#a5b92ed17598d95ff52cb6c9a33f5dd76af51a19e2bdd0598f566d27e90b554c22">llvm::HexagonBlockRanges::IndexType::None</a> and <a href="#a0d3eefbe3c5753f56041805c343b094e">start</a>.</p>

</div>
</div>

### end() {#aca59ba8f0683a6ab7f08ade1f4658bba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndexType llvm::HexagonBlockRanges::IndexRange::end ()</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-h">HexagonBlockRanges.h</a>.</p>


<p>Referenced by <a href="#ab0966222cb0d2b18634eb3aa9c412f49">contains</a>, <a href="#a130d144a312addfffe2600000ddef06d">merge</a> and <a href="#a7c68ec020f9529a22c70a6528950da1d">overlaps</a>.</p>

</div>
</div>

### merge() {#a130d144a312addfffe2600000ddef06d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonBlockRanges::IndexRange::merge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/indexrange">IndexRange</a> &amp; A)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-h">HexagonBlockRanges.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-cpp">HexagonBlockRanges.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aca59ba8f0683a6ab7f08ade1f4658bba">end</a>, <a href="#ad4f32d7f0cfe00ffef0085a350d2b1b1">Fixed</a>, <a href="#a896da44ea93b1652fe22b18402cb6862">IndexRange</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/indextype/#a5b92ed17598d95ff52cb6c9a33f5dd76af51a19e2bdd0598f566d27e90b554c22">llvm::HexagonBlockRanges::IndexType::None</a>, <a href="#a7c68ec020f9529a22c70a6528950da1d">overlaps</a>, <a href="#a0d3eefbe3c5753f56041805c343b094e">start</a> and <a href="#aa171f135bca180deea52a78722ca1a2e">TiedEnd</a>.</p>

</div>
</div>

### overlaps() {#a7c68ec020f9529a22c70a6528950da1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonBlockRanges::IndexRange::overlaps (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/indexrange">IndexRange</a> &amp; A)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-h">HexagonBlockRanges.h</a>, definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-cpp">HexagonBlockRanges.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#aca59ba8f0683a6ab7f08ade1f4658bba">end</a>, <a href="#a896da44ea93b1652fe22b18402cb6862">IndexRange</a>, <a href="#a0d3eefbe3c5753f56041805c343b094e">start</a> and <a href="#aa171f135bca180deea52a78722ca1a2e">TiedEnd</a>.</p>


<p>Referenced by <a href="#a130d144a312addfffe2600000ddef06d">merge</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/rangelist/#a1e39247090c4a34534af7e360eb6b13f">llvm::HexagonBlockRanges::RangeList::subtract</a>.</p>

</div>
</div>

### start() {#a0d3eefbe3c5753f56041805c343b094e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndexType llvm::HexagonBlockRanges::IndexRange::start ()</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-h">HexagonBlockRanges.h</a>.</p>


<p>Referenced by <a href="#ab0966222cb0d2b18634eb3aa9c412f49">contains</a>, <a href="#a130d144a312addfffe2600000ddef06d">merge</a>, <a href="#a76cf0a0c219b8e32dd0e536e29e18230">operator&lt;</a> and <a href="#a7c68ec020f9529a22c70a6528950da1d">overlaps</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### setEnd() {#abd3748c522dd9cd7b25eca791e23eeb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::HexagonBlockRanges::IndexRange::setEnd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/indextype">IndexType</a> &amp; E)</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-h">HexagonBlockRanges.h</a>.</p>

</div>
</div>

### setStart() {#a507654af7e68978931f217b021e17377}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::HexagonBlockRanges::IndexRange::setStart (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/hexagonblockranges/indextype">IndexType</a> &amp; S)</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-h">HexagonBlockRanges.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Fixed {#ad4f32d7f0cfe00ffef0085a350d2b1b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonBlockRanges::IndexRange::Fixed = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-h">HexagonBlockRanges.h</a>.</p>


<p>Referenced by <a href="#a4c5fc1bacd1e895d5e4b30cdf7e8e0f9">IndexRange</a> and <a href="#a130d144a312addfffe2600000ddef06d">merge</a>.</p>

</div>
</div>

### TiedEnd {#aa171f135bca180deea52a78722ca1a2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonBlockRanges::IndexRange::TiedEnd = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-h">HexagonBlockRanges.h</a>.</p>


<p>Referenced by <a href="#a4c5fc1bacd1e895d5e4b30cdf7e8e0f9">IndexRange</a>, <a href="#a130d144a312addfffe2600000ddef06d">merge</a> and <a href="#a7c68ec020f9529a22c70a6528950da1d">overlaps</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-cpp">HexagonBlockRanges.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonblockranges-h">HexagonBlockRanges.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
