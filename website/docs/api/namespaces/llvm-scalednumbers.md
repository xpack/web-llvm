---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/scalednumbers
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `ScaledNumbers` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::ScaledNumbers { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class DigitsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad2999ce6de7049e734c541cd6a868480">getWidth</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the width of a number. <a href="#ad2999ce6de7049e734c541cd6a868480">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class DigitsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8cfbb3bd6b2b9dbaee4f30a5b5fa5968">getRounded</a> (DigitsT Digits, int16_t Scale, bool ShouldRound) -&gt; std::pair&lt; DigitsT, int16_t &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Conditionally round up a scaled number. <a href="#a8cfbb3bd6b2b9dbaee4f30a5b5fa5968">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; uint32_t, int16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96588e2ec682fb6766a2ee7425242fe1">getRounded32</a> (uint32_t Digits, int16_t Scale, bool ShouldRound)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience helper for 32-bit rounding. <a href="#a96588e2ec682fb6766a2ee7425242fe1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; uint64_t, int16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef3ad1a75d5d27c4eed752fb4d8436c3">getRounded64</a> (uint64_t Digits, int16_t Scale, bool ShouldRound)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience helper for 64-bit rounding. <a href="#aef3ad1a75d5d27c4eed752fb4d8436c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class DigitsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a577d9fbdf827eebebf03e40b1d271f51">getAdjusted</a> (uint64_t Digits, int16_t Scale=0) -&gt; std::pair&lt; DigitsT, int16_t &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adjust a 64-bit scaled number down to the appropriate width. <a href="#a577d9fbdf827eebebf03e40b1d271f51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; uint32_t, int16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33d67c98f8d4325109084ae55008670c">getAdjusted32</a> (uint64_t Digits, int16_t Scale=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience helper for adjusting to 32 bits. <a href="#a33d67c98f8d4325109084ae55008670c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; uint64_t, int16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a20b371a385301acbe7b5940bc201d0">getAdjusted64</a> (uint64_t Digits, int16_t Scale=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience helper for adjusting to 64 bits. <a href="#a6a20b371a385301acbe7b5940bc201d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; uint64_t, int16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22a8258f778d9c8d3069d89a611e0abd">multiply64</a> (uint64_t LHS, uint64_t RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Multiply two 64-bit integers to create a 64-bit scaled number. <a href="#a22a8258f778d9c8d3069d89a611e0abd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class DigitsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8338a5002797a6c763182cf7526a09c0">getProduct</a> (DigitsT LHS, DigitsT RHS) -&gt; std::pair&lt; DigitsT, int16_t &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Multiply two 32-bit integers to create a 32-bit scaled number. <a href="#a8338a5002797a6c763182cf7526a09c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; uint32_t, int16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab297d80cc79a66648feeb41c8e070afa">getProduct32</a> (uint32_t LHS, uint32_t RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience helper for 32-bit product. <a href="#ab297d80cc79a66648feeb41c8e070afa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; uint64_t, int16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af393553ae9d345b2555e4fec38b4a8bc">getProduct64</a> (uint64_t LHS, uint64_t RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience helper for 64-bit product. <a href="#af393553ae9d345b2555e4fec38b4a8bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; uint64_t, int16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a6b36937186eb47bc6004f2eb0a7eee">divide64</a> (uint64_t Dividend, uint64_t Divisor)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Divide two 64-bit integers to create a 64-bit scaled number. <a href="#a0a6b36937186eb47bc6004f2eb0a7eee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; uint32_t, int16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa14759185c83674952abadab760c2028">divide32</a> (uint32_t Dividend, uint32_t Divisor)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Divide two 32-bit integers to create a 32-bit scaled number. <a href="#aa14759185c83674952abadab760c2028">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class DigitsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abe3c7dc3f454ec817ac2d56c8be27823">getQuotient</a> (DigitsT Dividend, DigitsT Divisor) -&gt; std::pair&lt; DigitsT, int16_t &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Divide two 32-bit numbers to create a 32-bit scaled number. <a href="#abe3c7dc3f454ec817ac2d56c8be27823">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; uint32_t, int16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ccad2b9795edca3a0185cdcde0f9119">getQuotient32</a> (uint32_t Dividend, uint32_t Divisor)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience helper for 32-bit quotient. <a href="#a6ccad2b9795edca3a0185cdcde0f9119">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; uint64_t, int16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92a467e68e9a45ee6bb19d320b095cd6">getQuotient64</a> (uint64_t Dividend, uint64_t Divisor)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience helper for 64-bit quotient. <a href="#a92a467e68e9a45ee6bb19d320b095cd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class DigitsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a702c858977d4ae7925fc8adca73af8cd">getLgImpl</a> (DigitsT Digits, int16_t Scale) -&gt; std::pair&lt; int32_t, int &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implementation of <a href="#ab63347a46b40b723f19ea7e153024a5e">getLg()</a> and friends. <a href="#a702c858977d4ae7925fc8adca73af8cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class DigitsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">int32_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab63347a46b40b723f19ea7e153024a5e">getLg</a> (DigitsT Digits, int16_t Scale)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the lg (rounded) of a scaled number. <a href="#ab63347a46b40b723f19ea7e153024a5e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class DigitsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">int32_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0c36a1c641beec6d22d4e371786cfce1">getLgFloor</a> (DigitsT Digits, int16_t Scale)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the lg floor of a scaled number. <a href="#a0c36a1c641beec6d22d4e371786cfce1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class DigitsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">int32_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adcdfc7209364d72aac80aee58254acc4">getLgCeiling</a> (DigitsT Digits, int16_t Scale)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the lg ceiling of a scaled number. <a href="#adcdfc7209364d72aac80aee58254acc4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4653521234cb7bc516c08e898036a42">compareImpl</a> (uint64_t L, uint64_t R, int ScaleDiff)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implementation for comparing scaled numbers. <a href="#ac4653521234cb7bc516c08e898036a42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class DigitsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0651aa0a52c69c4fe12cf730e7ed65ab">compare</a> (DigitsT LDigits, int16_t LScale, DigitsT RDigits, int16_t RScale)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare two scaled numbers. <a href="#a0651aa0a52c69c4fe12cf730e7ed65ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class DigitsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">int16_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9a4a7b9b4d6238cae16ec640dfd5d980">matchScales</a> (DigitsT &amp;LDigits, int16_t &amp;LScale, DigitsT &amp;RDigits, int16_t &amp;RScale)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Match scales of two numbers. <a href="#a9a4a7b9b4d6238cae16ec640dfd5d980">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class DigitsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2ea304f89cf0f32d2eb977dbf1154b9e">getSum</a> (DigitsT LDigits, int16_t LScale, DigitsT RDigits, int16_t RScale) -&gt; std::pair&lt; DigitsT, int16_t &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the sum of two scaled numbers. <a href="#a2ea304f89cf0f32d2eb977dbf1154b9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; uint32_t, int16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79f6ac2c63e1e6cd0e8e9487e538cfbe">getSum32</a> (uint32_t LDigits, int16_t LScale, uint32_t RDigits, int16_t RScale)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience helper for 32-bit sum. <a href="#a79f6ac2c63e1e6cd0e8e9487e538cfbe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; uint64_t, int16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab975f361f73a7b92cc260f035577608b">getSum64</a> (uint64_t LDigits, int16_t LScale, uint64_t RDigits, int16_t RScale)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience helper for 64-bit sum. <a href="#ab975f361f73a7b92cc260f035577608b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class DigitsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab9b560559be7a6630fbee210b5b46f39">getDifference</a> (DigitsT LDigits, int16_t LScale, DigitsT RDigits, int16_t RScale) -&gt; std::pair&lt; DigitsT, int16_t &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the difference of two scaled numbers. <a href="#ab9b560559be7a6630fbee210b5b46f39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; uint32_t, int16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d13d936e9200fe2b879345d3da77469">getDifference32</a> (uint32_t LDigits, int16_t LScale, uint32_t RDigits, int16_t RScale)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience helper for 32-bit difference. <a href="#a8d13d936e9200fe2b879345d3da77469">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; uint64_t, int16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad988756d495382cf8808ebe430f3d344">getDifference64</a> (uint64_t LDigits, int16_t LScale, uint64_t RDigits, int16_t RScale)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience helper for 64-bit difference. <a href="#ad988756d495382cf8808ebe430f3d344">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8aa6fe9d8188e55bf93404e0e19a7d9">MaxScale</a> = 16383</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maximum scale; same as <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> for easy debug printing. <a href="#aa8aa6fe9d8188e55bf93404e0e19a7d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a531ff53704c3545c63189ddea8e9b39b">MinScale</a> = -16382</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maximum scale; same as <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> for easy debug printing. <a href="#a531ff53704c3545c63189ddea8e9b39b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### compare() {#a0651aa0a52c69c4fe12cf730e7ed65ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class DigitsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ScaledNumbers::compare (DigitsT LDigits, int16_t LScale, DigitsT RDigits, int16_t RScale)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compare two scaled numbers.</p>


<p>Compare two scaled numbers. Returns 0 for equal, -1 for less than, and 1 for greater than.</p>


<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>References <a href="#ac4653521234cb7bc516c08e898036a42">compareImpl</a> and <a href="#a0c36a1c641beec6d22d4e371786cfce1">getLgFloor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#a58f5340edbc3475d613c9c67ae650c69">llvm::ScaledNumber&lt; uint64_t &gt;::compare</a>, <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#ad0993b94a7bf7bd7d1f23f6a0361210f">llvm::ScaledNumber&lt; uint64_t &gt;::compareTo</a> and <a href="#ab9b560559be7a6630fbee210b5b46f39">getDifference</a>.</p>

</div>
</div>

### compareImpl() {#ac4653521234cb7bc516c08e898036a42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ScaledNumbers::compareImpl (uint64_t L, uint64_t R, int ScaleDiff)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implementation for comparing scaled numbers.</p>


<p>Compare two 64-bit numbers with different scales. Given that the scale of <span class="doxyComputerOutput">L</span> is higher than that of <span class="doxyComputerOutput">R</span> by <span class="doxyComputerOutput">ScaleDiff</span>, compare them. Return -1, 1, and 0 for less than, greater than, and equal, respectively.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>0 &lt;= ScaleDiff &lt; 64.</p></dd>
</dl>


<p>Declaration at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>, definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/support/scalednumber-cpp">ScaledNumber.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a0651aa0a52c69c4fe12cf730e7ed65ab">compare</a>.</p>

</div>
</div>

### divide32() {#aa14759185c83674952abadab760c2028}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; uint32_t, int16_t &gt; llvm::ScaledNumbers::divide32 (uint32_t Dividend, uint32_t Divisor)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Divide two 32-bit integers to create a 32-bit scaled number.</p>


<p>Implemented with one 64-bit integer divide/remainder pair.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Dividend</span> and <span class="doxyComputerOutput">Divisor</span> are non-zero.</p></dd>
</dl>


<p>Declaration at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/support/scalednumber-cpp">ScaledNumber.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66191f0bcc8c62b784819e9e96ceeba2">llvm::countl_zero</a>, <a href="#a577d9fbdf827eebebf03e40b1d271f51">getAdjusted</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/scalednumber-cpp/#a96a8305eca90ffb97ef1ad6cbfa5c2c6">getHalf</a> and <a href="#a8cfbb3bd6b2b9dbaee4f30a5b5fa5968">getRounded</a>.</p>


<p>Referenced by <a href="#abe3c7dc3f454ec817ac2d56c8be27823">getQuotient</a>.</p>

</div>
</div>

### divide64() {#a0a6b36937186eb47bc6004f2eb0a7eee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; uint64_t, int16_t &gt; llvm::ScaledNumbers::divide64 (uint64_t Dividend, uint64_t Divisor)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Divide two 64-bit integers to create a 64-bit scaled number.</p>


<p>Implemented with long division.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Dividend</span> and <span class="doxyComputerOutput">Divisor</span> are non-zero.</p></dd>
</dl>


<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>, definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/support/scalednumber-cpp">ScaledNumber.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66191f0bcc8c62b784819e9e96ceeba2">llvm::countl_zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/scalednumber-cpp/#a96a8305eca90ffb97ef1ad6cbfa5c2c6">getHalf</a> and <a href="#a8cfbb3bd6b2b9dbaee4f30a5b5fa5968">getRounded</a>.</p>


<p>Referenced by <a href="#abe3c7dc3f454ec817ac2d56c8be27823">getQuotient</a>.</p>

</div>
</div>

### getAdjusted() {#a577d9fbdf827eebebf03e40b1d271f51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class DigitsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; DigitsT, int16_t &gt; llvm::ScaledNumbers::getAdjusted (uint64_t Digits, int16_t Scale=0)</td>
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

<p>Adjust a 64-bit scaled number down to the appropriate width.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>Adding 64 to <span class="doxyComputerOutput">Scale</span> will not overflow INT16_MAX.</p></dd>
</dl>


<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a37c1fdede126353d80c3753dfe06f3c7">llvm::bit_width</a>, <a href="#a8cfbb3bd6b2b9dbaee4f30a5b5fa5968">getRounded</a> and <a href="#ad2999ce6de7049e734c541cd6a868480">getWidth</a>.</p>


<p>Referenced by <a href="#aa14759185c83674952abadab760c2028">divide32</a>, <a href="#a33d67c98f8d4325109084ae55008670c">getAdjusted32</a>, <a href="#a6a20b371a385301acbe7b5940bc201d0">getAdjusted64</a> and <a href="#a8338a5002797a6c763182cf7526a09c0">getProduct</a>.</p>

</div>
</div>

### getAdjusted32() {#a33d67c98f8d4325109084ae55008670c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; uint32_t, int16_t &gt; llvm::ScaledNumbers::getAdjusted32 (uint64_t Digits, int16_t Scale=0)</td>
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

<p>Convenience helper for adjusting to 32 bits.</p>

<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>Reference <a href="#a577d9fbdf827eebebf03e40b1d271f51">getAdjusted</a>.</p>

</div>
</div>

### getAdjusted64() {#a6a20b371a385301acbe7b5940bc201d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; uint64_t, int16_t &gt; llvm::ScaledNumbers::getAdjusted64 (uint64_t Digits, int16_t Scale=0)</td>
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

<p>Convenience helper for adjusting to 64 bits.</p>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>Reference <a href="#a577d9fbdf827eebebf03e40b1d271f51">getAdjusted</a>.</p>

</div>
</div>

### getDifference() {#ab9b560559be7a6630fbee210b5b46f39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class DigitsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; DigitsT, int16_t &gt; llvm::ScaledNumbers::getDifference (DigitsT LDigits, int16_t LScale, DigitsT RDigits, int16_t RScale)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the difference of two scaled numbers.</p>


<p>Get LHS minus RHS with as much precision as possible.</p>


<p>Returns <span class="doxyComputerOutput"></span>(0, 0) if the RHS is larger than the LHS.</p>


<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>References <a href="#a0651aa0a52c69c4fe12cf730e7ed65ab">compare</a>, <a href="#a0c36a1c641beec6d22d4e371786cfce1">getLgFloor</a>, <a href="#ad2999ce6de7049e734c541cd6a868480">getWidth</a> and <a href="#a9a4a7b9b4d6238cae16ec640dfd5d980">matchScales</a>.</p>


<p>Referenced by <a href="#a8d13d936e9200fe2b879345d3da77469">getDifference32</a>, <a href="#ad988756d495382cf8808ebe430f3d344">getDifference64</a> and <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#af36979a0842013af6bf1cf9da73107c7">llvm::ScaledNumber&lt; uint64_t &gt;::operator-=</a>.</p>

</div>
</div>

### getDifference32() {#a8d13d936e9200fe2b879345d3da77469}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; uint32_t, int16_t &gt; llvm::ScaledNumbers::getDifference32 (uint32_t LDigits, int16_t LScale, uint32_t RDigits, int16_t RScale)</td>
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

<p>Convenience helper for 32-bit difference.</p>

<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>Reference <a href="#ab9b560559be7a6630fbee210b5b46f39">getDifference</a>.</p>

</div>
</div>

### getDifference64() {#ad988756d495382cf8808ebe430f3d344}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; uint64_t, int16_t &gt; llvm::ScaledNumbers::getDifference64 (uint64_t LDigits, int16_t LScale, uint64_t RDigits, int16_t RScale)</td>
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

<p>Convenience helper for 64-bit difference.</p>

<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>Reference <a href="#ab9b560559be7a6630fbee210b5b46f39">getDifference</a>.</p>

</div>
</div>

### getLg() {#ab63347a46b40b723f19ea7e153024a5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class DigitsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t llvm::ScaledNumbers::getLg (DigitsT Digits, int16_t Scale)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the lg (rounded) of a scaled number.</p>


<p>Get the lg of <span class="doxyComputerOutput">Digits*2^Scale</span>.</p>


<p>Returns <span class="doxyComputerOutput">INT32_MIN</span> when <span class="doxyComputerOutput">Digits</span> is zero.</p>


<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>Reference <a href="#a702c858977d4ae7925fc8adca73af8cd">getLgImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#ace4debe4ed7a99d12c9960035d723392">llvm::ScaledNumber&lt; uint64_t &gt;::lg</a>.</p>

</div>
</div>

### getLgCeiling() {#adcdfc7209364d72aac80aee58254acc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class DigitsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t llvm::ScaledNumbers::getLgCeiling (DigitsT Digits, int16_t Scale)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the lg ceiling of a scaled number.</p>


<p>Get the ceiling of the lg of <span class="doxyComputerOutput">Digits*2^Scale</span>.</p>


<p>Returns <span class="doxyComputerOutput">INT32_MIN</span> when <span class="doxyComputerOutput">Digits</span> is zero.</p>


<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>Reference <a href="#a702c858977d4ae7925fc8adca73af8cd">getLgImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#ab9f1ca77e0e4f907f0bd20ad556ea5c0">llvm::ScaledNumber&lt; uint64_t &gt;::lgCeiling</a>.</p>

</div>
</div>

### getLgFloor() {#a0c36a1c641beec6d22d4e371786cfce1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class DigitsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t llvm::ScaledNumbers::getLgFloor (DigitsT Digits, int16_t Scale)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the lg floor of a scaled number.</p>


<p>Get the floor of the lg of <span class="doxyComputerOutput">Digits*2^Scale</span>.</p>


<p>Returns <span class="doxyComputerOutput">INT32_MIN</span> when <span class="doxyComputerOutput">Digits</span> is zero.</p>


<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>Reference <a href="#a702c858977d4ae7925fc8adca73af8cd">getLgImpl</a>.</p>


<p>Referenced by <a href="#a0651aa0a52c69c4fe12cf730e7ed65ab">compare</a>, <a href="#ab9b560559be7a6630fbee210b5b46f39">getDifference</a> and <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#a3a83830eba487610e76cf51771ba4978">llvm::ScaledNumber&lt; uint64_t &gt;::lgFloor</a>.</p>

</div>
</div>

### getLgImpl() {#a702c858977d4ae7925fc8adca73af8cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class DigitsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; int32_t, int &gt; llvm::ScaledNumbers::getLgImpl (DigitsT Digits, int16_t Scale)</td>
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

<p>Implementation of <a href="#ab63347a46b40b723f19ea7e153024a5e">getLg()</a> and friends.</p>


<p>Returns the rounded lg of <span class="doxyComputerOutput">Digits*2^Scale</span> and an int specifying whether this was rounded up (1), down (-1), or exact (0).</p>


<p>Returns <span class="doxyComputerOutput">INT32_MIN</span> when <span class="doxyComputerOutput">Digits</span> is zero.</p>


<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4f42ed6fd2569fa43f03814a17f9d94a">llvm::Log2_64</a>.</p>


<p>Referenced by <a href="#ab63347a46b40b723f19ea7e153024a5e">getLg</a>, <a href="#adcdfc7209364d72aac80aee58254acc4">getLgCeiling</a> and <a href="#a0c36a1c641beec6d22d4e371786cfce1">getLgFloor</a>.</p>

</div>
</div>

### getProduct() {#a8338a5002797a6c763182cf7526a09c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class DigitsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; DigitsT, int16_t &gt; llvm::ScaledNumbers::getProduct (DigitsT LHS, DigitsT RHS)</td>
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

<p>Multiply two 32-bit integers to create a 32-bit scaled number.</p>


<p>Implemented with one 64-bit integer multiply.</p>


<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>References <a href="#a577d9fbdf827eebebf03e40b1d271f51">getAdjusted</a>, <a href="#ad2999ce6de7049e734c541cd6a868480">getWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="#a22a8258f778d9c8d3069d89a611e0abd">multiply64</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="#ab297d80cc79a66648feeb41c8e070afa">getProduct32</a> and <a href="#af393553ae9d345b2555e4fec38b4a8bc">getProduct64</a>.</p>

</div>
</div>

### getProduct32() {#ab297d80cc79a66648feeb41c8e070afa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; uint32_t, int16_t &gt; llvm::ScaledNumbers::getProduct32 (uint32_t LHS, uint32_t RHS)</td>
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

<p>Convenience helper for 32-bit product.</p>

<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>References <a href="#a8338a5002797a6c763182cf7526a09c0">getProduct</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### getProduct64() {#af393553ae9d345b2555e4fec38b4a8bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; uint64_t, int16_t &gt; llvm::ScaledNumbers::getProduct64 (uint64_t LHS, uint64_t RHS)</td>
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

<p>Convenience helper for 64-bit product.</p>

<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>References <a href="#a8338a5002797a6c763182cf7526a09c0">getProduct</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### getQuotient() {#abe3c7dc3f454ec817ac2d56c8be27823}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class DigitsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; DigitsT, int16_t &gt; llvm::ScaledNumbers::getQuotient (DigitsT Dividend, DigitsT Divisor)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Divide two 32-bit numbers to create a 32-bit scaled number.</p>


<p>Implemented with one 64-bit integer divide/remainder pair.</p>


<p>Returns <span class="doxyComputerOutput"></span>(DigitsT_MAX, MaxScale) for divide-by-zero (0 for 0/0).</p>


<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>References <a href="#aa14759185c83674952abadab760c2028">divide32</a>, <a href="#a0a6b36937186eb47bc6004f2eb0a7eee">divide64</a>, <a href="#ad2999ce6de7049e734c541cd6a868480">getWidth</a> and <a href="#aa8aa6fe9d8188e55bf93404e0e19a7d9">MaxScale</a>.</p>


<p>Referenced by <a href="#a6ccad2b9795edca3a0185cdcde0f9119">getQuotient32</a> and <a href="#a92a467e68e9a45ee6bb19d320b095cd6">getQuotient64</a>.</p>

</div>
</div>

### getQuotient32() {#a6ccad2b9795edca3a0185cdcde0f9119}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; uint32_t, int16_t &gt; llvm::ScaledNumbers::getQuotient32 (uint32_t Dividend, uint32_t Divisor)</td>
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

<p>Convenience helper for 32-bit quotient.</p>

<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>Reference <a href="#abe3c7dc3f454ec817ac2d56c8be27823">getQuotient</a>.</p>

</div>
</div>

### getQuotient64() {#a92a467e68e9a45ee6bb19d320b095cd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; uint64_t, int16_t &gt; llvm::ScaledNumbers::getQuotient64 (uint64_t Dividend, uint64_t Divisor)</td>
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

<p>Convenience helper for 64-bit quotient.</p>

<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>Reference <a href="#abe3c7dc3f454ec817ac2d56c8be27823">getQuotient</a>.</p>

</div>
</div>

### getRounded() {#a8cfbb3bd6b2b9dbaee4f30a5b5fa5968}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class DigitsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; DigitsT, int16_t &gt; llvm::ScaledNumbers::getRounded (DigitsT Digits, int16_t Scale, bool ShouldRound)</td>
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

<p>Conditionally round up a scaled number.</p>


<p>Given <span class="doxyComputerOutput">Digits</span> and <span class="doxyComputerOutput">Scale</span>, round up iff <span class="doxyComputerOutput">ShouldRound</span> is <span class="doxyComputerOutput">true</span>. Always returns <span class="doxyComputerOutput">Scale</span> unless there's an overflow, in which case it returns <span class="doxyComputerOutput">1+Scale</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>adding 1 to <span class="doxyComputerOutput">Scale</span> will not overflow INT16_MAX.</p></dd>
</dl>


<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>Reference <a href="#ad2999ce6de7049e734c541cd6a868480">getWidth</a>.</p>


<p>Referenced by <a href="#aa14759185c83674952abadab760c2028">divide32</a>, <a href="#a0a6b36937186eb47bc6004f2eb0a7eee">divide64</a>, <a href="#a577d9fbdf827eebebf03e40b1d271f51">getAdjusted</a>, <a href="#a96588e2ec682fb6766a2ee7425242fe1">getRounded32</a>, <a href="#aef3ad1a75d5d27c4eed752fb4d8436c3">getRounded64</a> and <a href="#a22a8258f778d9c8d3069d89a611e0abd">multiply64</a>.</p>

</div>
</div>

### getRounded32() {#a96588e2ec682fb6766a2ee7425242fe1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; uint32_t, int16_t &gt; llvm::ScaledNumbers::getRounded32 (uint32_t Digits, int16_t Scale, bool ShouldRound)</td>
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

<p>Convenience helper for 32-bit rounding.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>Reference <a href="#a8cfbb3bd6b2b9dbaee4f30a5b5fa5968">getRounded</a>.</p>

</div>
</div>

### getRounded64() {#aef3ad1a75d5d27c4eed752fb4d8436c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; uint64_t, int16_t &gt; llvm::ScaledNumbers::getRounded64 (uint64_t Digits, int16_t Scale, bool ShouldRound)</td>
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

<p>Convenience helper for 64-bit rounding.</p>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>Reference <a href="#a8cfbb3bd6b2b9dbaee4f30a5b5fa5968">getRounded</a>.</p>

</div>
</div>

### getSum() {#a2ea304f89cf0f32d2eb977dbf1154b9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class DigitsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; DigitsT, int16_t &gt; llvm::ScaledNumbers::getSum (DigitsT LDigits, int16_t LScale, DigitsT RDigits, int16_t RScale)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the sum of two scaled numbers.</p>


<p>Get the sum of two scaled numbers with as much precision as possible.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>Adding 1 to <span class="doxyComputerOutput">LScale</span> (or <span class="doxyComputerOutput">RScale</span>) will not overflow INT16_MAX.</p></dd>
</dl>


<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad2999ce6de7049e734c541cd6a868480">getWidth</a> and <a href="#a9a4a7b9b4d6238cae16ec640dfd5d980">matchScales</a>.</p>


<p>Referenced by <a href="#a79f6ac2c63e1e6cd0e8e9487e538cfbe">getSum32</a>, <a href="#ab975f361f73a7b92cc260f035577608b">getSum64</a> and <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#a50c31e20b8d6f9fcd42e616dff8303a2">llvm::ScaledNumber&lt; uint64_t &gt;::operator+=</a>.</p>

</div>
</div>

### getSum32() {#a79f6ac2c63e1e6cd0e8e9487e538cfbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; uint32_t, int16_t &gt; llvm::ScaledNumbers::getSum32 (uint32_t LDigits, int16_t LScale, uint32_t RDigits, int16_t RScale)</td>
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

<p>Convenience helper for 32-bit sum.</p>

<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>Reference <a href="#a2ea304f89cf0f32d2eb977dbf1154b9e">getSum</a>.</p>

</div>
</div>

### getSum64() {#ab975f361f73a7b92cc260f035577608b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; uint64_t, int16_t &gt; llvm::ScaledNumbers::getSum64 (uint64_t LDigits, int16_t LScale, uint64_t RDigits, int16_t RScale)</td>
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

<p>Convenience helper for 64-bit sum.</p>

<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>Reference <a href="#a2ea304f89cf0f32d2eb977dbf1154b9e">getSum</a>.</p>

</div>
</div>

### getWidth() {#ad2999ce6de7049e734c541cd6a868480}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class DigitsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ScaledNumbers::getWidth ()</td>
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

<p>Get the width of a number.</p>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>Referenced by <a href="#a577d9fbdf827eebebf03e40b1d271f51">getAdjusted</a>, <a href="#ab9b560559be7a6630fbee210b5b46f39">getDifference</a>, <a href="#a8338a5002797a6c763182cf7526a09c0">getProduct</a>, <a href="#abe3c7dc3f454ec817ac2d56c8be27823">getQuotient</a>, <a href="#a8cfbb3bd6b2b9dbaee4f30a5b5fa5968">getRounded</a>, <a href="#a2ea304f89cf0f32d2eb977dbf1154b9e">getSum</a> and <a href="#a9a4a7b9b4d6238cae16ec640dfd5d980">matchScales</a>.</p>

</div>
</div>

### matchScales() {#a9a4a7b9b4d6238cae16ec640dfd5d980}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class DigitsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int16_t llvm::ScaledNumbers::matchScales (DigitsT &amp; LDigits, int16_t &amp; LScale, DigitsT &amp; RDigits, int16_t &amp; RScale)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Match scales of two numbers.</p>


<p>Given two scaled numbers, match up their scales. Change the digits and scales in place. Shift the digits as necessary to form equivalent numbers, losing precision only when necessary.</p>


<p>If the output value of <span class="doxyComputerOutput">LDigits</span> (<span class="doxyComputerOutput">RDigits</span>) is <span class="doxyComputerOutput">0</span>, the output value of <span class="doxyComputerOutput">LScale</span> (<span class="doxyComputerOutput">RScale</span>) is unspecified.</p>


<p>As a convenience, returns the matching scale. If the output value of one number is zero, returns the scale of the other. If both are zero, which scale is returned is unspecified.</p>


<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66191f0bcc8c62b784819e9e96ceeba2">llvm::countl_zero</a>, <a href="#ad2999ce6de7049e734c541cd6a868480">getWidth</a> and <a href="#a9a4a7b9b4d6238cae16ec640dfd5d980">matchScales</a>.</p>


<p>Referenced by <a href="#ab9b560559be7a6630fbee210b5b46f39">getDifference</a>, <a href="#a2ea304f89cf0f32d2eb977dbf1154b9e">getSum</a> and <a href="#a9a4a7b9b4d6238cae16ec640dfd5d980">matchScales</a>.</p>

</div>
</div>

### multiply64() {#a22a8258f778d9c8d3069d89a611e0abd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; uint64_t, int16_t &gt; llvm::ScaledNumbers::multiply64 (uint64_t LHS, uint64_t RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Multiply two 64-bit integers to create a 64-bit scaled number.</p>


<p>Implemented with four 64-bit integer multiplies.</p>


<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>, definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/support/scalednumber-cpp">ScaledNumber.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a66191f0bcc8c62b784819e9e96ceeba2">llvm::countl_zero</a>, <a href="#a8cfbb3bd6b2b9dbaee4f30a5b5fa5968">getRounded</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0ab75fcdd2d72d9e000beab48622402d93">llvm::Lower</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0a19de5b94f7b83900d4b296d9fa491aec">llvm::Upper</a>.</p>


<p>Referenced by <a href="#a8338a5002797a6c763182cf7526a09c0">getProduct</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### MaxScale {#aa8aa6fe9d8188e55bf93404e0e19a7d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int32_t llvm::ScaledNumbers::MaxScale = 16383</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maximum scale; same as <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> for easy debug printing.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#a2fd49141f0fc36006080677630d0b1dc">llvm::ScaledNumber&lt; uint64_t &gt;::getLargest</a>, <a href="#abe3c7dc3f454ec817ac2d56c8be27823">getQuotient</a>, <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#a50c31e20b8d6f9fcd42e616dff8303a2">llvm::ScaledNumber&lt; uint64_t &gt;::operator+=</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/scalednumber-cpp/#abbfb15ef66003a1f34d28fa4fb90ac93">toStringAPFloat</a>.</p>

</div>
</div>

### MinScale {#a531ff53704c3545c63189ddea8e9b39b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int32_t llvm::ScaledNumbers::MinScale = -16382</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maximum scale; same as <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> for easy debug printing.</p>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/scalednumber-cpp/#abbfb15ef66003a1f34d28fa4fb90ac93">toStringAPFloat</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scalednumber-h">ScaledNumber.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/scalednumber-cpp">ScaledNumber.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
