---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/densemapinfo-a4d14e865a8adfcbd9b83f2242f1f515
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `DenseMapInfo` Struct Template



## Declaration

<div class="doxyDeclaration">
struct llvm::DenseMapInfo&lt;DivRemMapKey&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/bypassslowdivision-h">llvm/Transforms/Utils/BypassSlowDivision.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf0a7c65e10311f073d8c6f8dd0ef5bf">isEqual</a> (const DivRemMapKey &amp;Val1, const DivRemMapKey &amp;Val2)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/divremmapkey">DivRemMapKey</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a585df04b5e864523b0be2f764526ba23">getEmptyKey</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/divremmapkey">DivRemMapKey</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aced0f0587d5b722332270aca1569117b">getTombstoneKey</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa97b0fccb52a52ad74543f32ac05d8df">getHashValue</a> (const DivRemMapKey &amp;Val)</td>
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


<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/bypassslowdivision-h">BypassSlowDivision.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### getEmptyKey() {#a585df04b5e864523b0be2f764526ba23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DivRemMapKey llvm::DenseMapInfo&lt; DivRemMapKey &gt;::getEmptyKey ()</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/bypassslowdivision-h">BypassSlowDivision.h</a>.</p>

</div>
</div>

### getHashValue() {#aa97b0fccb52a52ad74543f32ac05d8df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DenseMapInfo&lt; DivRemMapKey &gt;::getHashValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/divremmapkey">DivRemMapKey</a> &amp; Val)</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/bypassslowdivision-h">BypassSlowDivision.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/divremmapkey/#af6c09e645fbad704df924a7fa0e16aec">llvm::DivRemMapKey::Dividend</a>, <a href="/web-llvm/docs/api/structs/llvm/divremmapkey/#a7abf4dfbd44a1d22e5db941bc89a35d4">llvm::DivRemMapKey::Divisor</a> and <a href="/web-llvm/docs/api/structs/llvm/divremmapkey/#a9e88c4c4d1b77ff28b1835f58cf56b91">llvm::DivRemMapKey::SignedOp</a>.</p>

</div>
</div>

### getTombstoneKey() {#aced0f0587d5b722332270aca1569117b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DivRemMapKey llvm::DenseMapInfo&lt; DivRemMapKey &gt;::getTombstoneKey ()</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/bypassslowdivision-h">BypassSlowDivision.h</a>.</p>

</div>
</div>

### isEqual() {#adf0a7c65e10311f073d8c6f8dd0ef5bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DenseMapInfo&lt; DivRemMapKey &gt;::isEqual (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/divremmapkey">DivRemMapKey</a> &amp; Val1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/divremmapkey">DivRemMapKey</a> &amp; Val2)</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/bypassslowdivision-h">BypassSlowDivision.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/divremmapkey/#af6c09e645fbad704df924a7fa0e16aec">llvm::DivRemMapKey::Dividend</a>, <a href="/web-llvm/docs/api/structs/llvm/divremmapkey/#a7abf4dfbd44a1d22e5db941bc89a35d4">llvm::DivRemMapKey::Divisor</a> and <a href="/web-llvm/docs/api/structs/llvm/divremmapkey/#a9e88c4c4d1b77ff28b1835f58cf56b91">llvm::DivRemMapKey::SignedOp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/bypassslowdivision-h">BypassSlowDivision.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
