---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/featurebitset
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `FeatureBitset` Class

<p>Container class for subtarget features. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::FeatureBitset { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">llvm/TargetParser/SubtargetFeature.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/featurebitarray">FeatureBitArray</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class used to store the subtarget bits in the tables created by tablegen. <a href="/web-llvm/docs/api/classes/llvm/featurebitarray/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c5ae7d3a4707f06790b68ef0422a23d">FeatureBitset</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89c823aee257d38096846f2ec188a38a">FeatureBitset</a> (std::initializer_list&lt; unsigned &gt; Init)</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e07d5143362d63a8202333029b280e8">FeatureBitset</a> (const std::array&lt; uint64_t, MAX_SUBTARGET_WORDS &gt; &amp;B)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a252c6da0883abd4893ce1b1831401274">operator[]</a> (unsigned I) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30c6de56b09a8e08ecda9c0d34914ad8">operator^=</a> (const FeatureBitset &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af61fb4511c9b52023328d035c3f36ea0">operator^</a> (const FeatureBitset &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10d75044bbec3109319d5c4cc84e401e">operator&amp;=</a> (const FeatureBitset &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9221eae36e693fc83edc21a048222d31">operator&amp;</a> (const FeatureBitset &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bd450d4f2b0fe29de51f8a72c468faf">operator|=</a> (const FeatureBitset &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c45baf0e20aec37d596fff2aec88fc0">operator|</a> (const FeatureBitset &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebab5c6448dfac2b157f54cd975482ff">operator~</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acafe17b1f1ceb126a092483029c3e661">operator==</a> (const FeatureBitset &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e63c74e1e20e9c6cd8d499f4b609b0f">operator!=</a> (const FeatureBitset &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab060954a64e3cc74a090baf475007883">operator&lt;</a> (const FeatureBitset &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54e5f414a306634a73023a4ca94aa776">set</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a441d6d7b026c4de8b2c7f864cdf0efef">set</a> (unsigned I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20907c2cbc50e3cad93df4c7e49e2b3b">reset</a> (unsigned I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54ab816fd39422eb444d7d1e01b50dd0">flip</a> (unsigned I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fce0696a3465a5f24d788288f23f6bf">test</a> (unsigned I) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec33832bdf233909649a8632be33aa0c">size</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13ecaf937de861fc3149cea0da6b82b2">any</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfdb417afa4938d4f4208235ebc65c7c">none</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ce4789ee3e938b5f21eb532291e7ffa">count</a> () const</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::array&lt; uint64_t, <a href="/web-llvm/docs/api/namespaces/llvm/#aba72d8ae24eb61078096f50ae780bd30">MAX_SUBTARGET_WORDS</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca994873c8eb41c52ec7edf9825e4cda">Bits</a> {}</td>
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

<p>Container class for subtarget features.</p>


<p>This is a constexpr reimplementation of a subset of std::bitset. It would be nice to use std::bitset directly, but it doesn't support constant initialization.</p>


<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FeatureBitset() {#a5c5ae7d3a4707f06790b68ef0422a23d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FeatureBitset::FeatureBitset ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>

</div>
</div>

### FeatureBitset() {#a89c823aee257d38096846f2ec188a38a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FeatureBitset::FeatureBitset (std::initializer_list&lt; unsigned &gt; Init)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a54e5f414a306634a73023a4ca94aa776">set</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### FeatureBitset() {#a0e07d5143362d63a8202333029b280e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FeatureBitset::FeatureBitset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::array&lt; uint64_t, <a href="/web-llvm/docs/api/namespaces/llvm/#aba72d8ae24eb61078096f50ae780bd30">MAX_SUBTARGET_WORDS</a> &gt; &amp; B)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/featurebitarray/#affce0efa9230570ce4a0790c6555aa18">llvm::FeatureBitArray::FeatureBitArray</a>, <a href="#a54ab816fd39422eb444d7d1e01b50dd0">flip</a>, <a href="/web-llvm/docs/api/classes/llvm/featurebitarray/#ac4a0360586ccc1be7d8ec4e824778e1a">llvm::FeatureBitArray::getAsBitset</a>, <a href="#a3e63c74e1e20e9c6cd8d499f4b609b0f">operator!=</a>, <a href="#a9221eae36e693fc83edc21a048222d31">operator&amp;</a>, <a href="#a10d75044bbec3109319d5c4cc84e401e">operator&amp;=</a>, <a href="#ab060954a64e3cc74a090baf475007883">operator&lt;</a>, <a href="#acafe17b1f1ceb126a092483029c3e661">operator==</a>, <a href="#af61fb4511c9b52023328d035c3f36ea0">operator^</a>, <a href="#a30c6de56b09a8e08ecda9c0d34914ad8">operator^=</a>, <a href="#a7c45baf0e20aec37d596fff2aec88fc0">operator|</a>, <a href="#a1bd450d4f2b0fe29de51f8a72c468faf">operator|=</a>, <a href="#aebab5c6448dfac2b157f54cd975482ff">operator~</a>, <a href="#a20907c2cbc50e3cad93df4c7e49e2b3b">reset</a>, <a href="#a54e5f414a306634a73023a4ca94aa776">set</a> and <a href="#a441d6d7b026c4de8b2c7f864cdf0efef">set</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a3e63c74e1e20e9c6cd8d499f4b609b0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FeatureBitset::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp; RHS)</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>


<p>References <a href="#a0e07d5143362d63a8202333029b280e8">FeatureBitset</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator\[\]() {#a252c6da0883abd4893ce1b1831401274}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FeatureBitset::operator[] (unsigned I)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### operator&amp;() {#a9221eae36e693fc83edc21a048222d31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FeatureBitset llvm::FeatureBitset::operator&amp; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>


<p>References <a href="#a0e07d5143362d63a8202333029b280e8">FeatureBitset</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&amp;=() {#a10d75044bbec3109319d5c4cc84e401e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FeatureBitset &amp; llvm::FeatureBitset::operator&amp;= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a0e07d5143362d63a8202333029b280e8">FeatureBitset</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator^() {#af61fb4511c9b52023328d035c3f36ea0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FeatureBitset llvm::FeatureBitset::operator^ (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>


<p>References <a href="#a0e07d5143362d63a8202333029b280e8">FeatureBitset</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator^=() {#a30c6de56b09a8e08ecda9c0d34914ad8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FeatureBitset &amp; llvm::FeatureBitset::operator^= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a0e07d5143362d63a8202333029b280e8">FeatureBitset</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&lt;() {#ab060954a64e3cc74a090baf475007883}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FeatureBitset::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp; Other)</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a0e07d5143362d63a8202333029b280e8">FeatureBitset</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#aec33832bdf233909649a8632be33aa0c">size</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp/#a106e32122c569cdb42ddf61ecbb0aad1">test</a>.</p>

</div>
</div>

### operator==() {#acafe17b1f1ceb126a092483029c3e661}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FeatureBitset::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp; RHS)</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>


<p>References <a href="#a0e07d5143362d63a8202333029b280e8">FeatureBitset</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator|() {#a7c45baf0e20aec37d596fff2aec88fc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FeatureBitset llvm::FeatureBitset::operator| (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>


<p>References <a href="#a0e07d5143362d63a8202333029b280e8">FeatureBitset</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator|=() {#a1bd450d4f2b0fe29de51f8a72c468faf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FeatureBitset &amp; llvm::FeatureBitset::operator|= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a0e07d5143362d63a8202333029b280e8">FeatureBitset</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator\~() {#aebab5c6448dfac2b157f54cd975482ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FeatureBitset llvm::FeatureBitset::operator~ ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="#a0e07d5143362d63a8202333029b280e8">FeatureBitset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### any() {#a13ecaf937de861fc3149cea0da6b82b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FeatureBitset::any ()</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/targetparser/x86targetparser-cpp/#a8dae1243f4742fb2ffa555c4b220c4b4">getImpliedEnabledFeatures</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a0b228c0975660d76b206b2f9220b3cc3">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::matchAndEmitInstruction</a> and <a href="#abfdb417afa4938d4f4208235ebc65c7c">none</a>.</p>

</div>
</div>

### count() {#a6ce4789ee3e938b5f21eb532291e7ffa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::FeatureBitset::count ()</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0eea77e7bfa82e0219d2ec7b4efbc94f">llvm::popcount</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#a43ffe9d0de2c3fc1eb0c8bb0b6c7526d">anonymous{ARMAsmParser.cpp}::ARMAsmParser::FilterNearMisses</a> and <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#abeebd6c3e48c1d92d186d8ffafbf5e2b">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::matchAndEmitInstruction</a>.</p>

</div>
</div>

### flip() {#a54ab816fd39422eb444d7d1e01b50dd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FeatureBitset &amp; llvm::FeatureBitset::flip (unsigned I)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>


<p>References <a href="#a0e07d5143362d63a8202333029b280e8">FeatureBitset</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#acaa1de0987d9c003e41c92f310c45746">llvm::MCSubtargetInfo::ToggleFeature</a>.</p>

</div>
</div>

### none() {#abfdb417afa4938d4f4208235ebc65c7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FeatureBitset::none ()</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>


<p>Reference <a href="#a13ecaf937de861fc3149cea0da6b82b2">any</a>.</p>

</div>
</div>

### reset() {#a20907c2cbc50e3cad93df4c7e49e2b3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FeatureBitset &amp; llvm::FeatureBitset::reset (unsigned I)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>


<p>References <a href="#a0e07d5143362d63a8202333029b280e8">FeatureBitset</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#afb851cd69bea258a1020b268d3de3abd">llvm::Hexagon_MC::createHexagonMCSubtargetInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#ac33e274ca277cfe840f699acc1b8a814">llvm::HexagonSubtarget::initializeSubtargetDependencies</a>.</p>

</div>
</div>

### set() {#a54e5f414a306634a73023a4ca94aa776}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FeatureBitset &amp; llvm::FeatureBitset::set ()</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>


<p>Reference <a href="#a0e07d5143362d63a8202333029b280e8">FeatureBitset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#aee59f67f23fccbef39abc4ecd6092d54">llvm::Hexagon_MC::completeHVXFeatures</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#afb851cd69bea258a1020b268d3de3abd">llvm::Hexagon_MC::createHexagonMCSubtargetInfo</a>, <a href="#a89c823aee257d38096846f2ec188a38a">FeatureBitset</a> and <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a29ae6841bfae28e4dc7aa1db76fcca17">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::WebAssemblyAsmParser</a>.</p>

</div>
</div>

### set() {#a441d6d7b026c4de8b2c7f864cdf0efef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FeatureBitset &amp; llvm::FeatureBitset::set (unsigned I)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>


<p>References <a href="#a0e07d5143362d63a8202333029b280e8">FeatureBitset</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### size() {#aec33832bdf233909649a8632be33aa0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::FeatureBitset::size ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a01df264ee0f0b191e89311709c67f0dc">llvm::MAX_SUBTARGET_FEATURES</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#af4b8dd4ace194f4d2fd90bc1c7cc9e61">llvm::MCSubtargetInfo::ClearFeatureBitsTransitively</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#a43ffe9d0de2c3fc1eb0c8bb0b6c7526d">anonymous{ARMAsmParser.cpp}::ARMAsmParser::FilterNearMisses</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a0b228c0975660d76b206b2f9220b3cc3">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::matchAndEmitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#abeebd6c3e48c1d92d186d8ffafbf5e2b">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::matchAndEmitInstruction</a> and <a href="#ab060954a64e3cc74a090baf475007883">operator&lt;</a>.</p>

</div>
</div>

### test() {#a4fce0696a3465a5f24d788288f23f6bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FeatureBitset::test (unsigned I)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuremoveincompatiblefunctions-cpp-/amdgpuremoveincompatiblefunctions/#a9910118e4db5bb56e348017ba1460553">anonymous{AMDGPURemoveIncompatibleFunctions.cpp}::AMDGPURemoveIncompatibleFunctions::checkFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#aee59f67f23fccbef39abc4ecd6092d54">llvm::Hexagon_MC::completeHVXFeatures</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuremoveincompatiblefunctions-cpp-/#ad69a0ba53c1180dd66530af345bda9cb">anonymous{AMDGPURemoveIncompatibleFunctions.cpp}::expandImpliedFeatures</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#a43ffe9d0de2c3fc1eb0c8bb0b6c7526d">anonymous{ARMAsmParser.cpp}::ARMAsmParser::FilterNearMisses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a6f199c1f3d13e403d252d9b028b4c7a0">llvm::AMDGPU::IsaInfo::getAddressableLocalMemorySize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a7baaa91927748c04ac388e82788a973d">llvm::AMDGPU::IsaInfo::getAddressableNumSGPRs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a842a99d2928e264423f0ac73b0910ec9">llvm::AMDGPU::IsaInfo::getAddressableNumVGPRs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#a135e6f2cdc120b46545bd36075323a2a">llvm::Hexagon_MC::getArchVersion</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/mckerneldescriptor/#ae427ea6c3fad2449f851240892963b14">llvm::AMDGPU::MCKernelDescriptor::getDefaultAmdhsaKernelDescriptor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a705a7512f5b23ec9b3bb19f032040285">llvm::AMDGPU::IsaInfo::getEUsPerCU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#a2ddfa3e93456cffcbd3e4beff76d2d50">llvm::Hexagon_MC::getHVXVersion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a6a404dcfcc397b46c1658356bbae054f">llvm::AMDGPU::IsaInfo::getLocalMemorySize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a98803f3d3a9a7e50ad0f40bdf8cd8190">llvm::AMDGPU::IsaInfo::getMaxNumSGPRs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a2d0c61cd3e4d53626ffdb34031766f08">llvm::AMDGPU::IsaInfo::getMaxWorkGroupsPerCU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a8712096d79b8b76954f261f06351c34f">llvm::AMDGPU::IsaInfo::getMinNumSGPRs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#aae419e2ff2e3882dd0d8e99c97add6b1">llvm::AMDGPU::IsaInfo::getNumExtraSGPRs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a4f0de0c1180aa2d8965d9cdddfde84a5">llvm::AMDGPU::IsaInfo::getNumExtraSGPRs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a14accda22ecd133d48fa434165e690a0">llvm::AMDGPU::IsaInfo::getTotalNumVGPRs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#ae47a2723f63ec4e85b4228b56e5d759c">llvm::AMDGPU::IsaInfo::getVGPRAllocGranule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a00ddec6f625f5fdc41b2ee64b272b5b9">llvm::AMDGPU::IsaInfo::getVGPREncodingGranule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a20f21352639512a028b2297e3cba9094">llvm::AMDGPU::IsaInfo::getWavefrontSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab8a9a35e11965a5192429b791b2b25f5">llvm::AMDGPU::initDefaultAMDKernelCodeT</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcinstprinter-cpp/#aad70fb95e1855cf69dfefcf98e2d5e8b">matchAliasCondition</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#abeebd6c3e48c1d92d186d8ffafbf5e2b">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::matchAndEmitInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp/#a09e4ddb5c9eead1f368615b3bde65f92">SetImpliedBits</a> and <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a29ae6841bfae28e4dc7aa1db76fcca17">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::WebAssemblyAsmParser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Bits {#aca994873c8eb41c52ec7edf9825e4cda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array&lt;uint64_t, MAX_SUBTARGET_WORDS&gt; llvm::FeatureBitset::Bits {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">SubtargetFeature.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
