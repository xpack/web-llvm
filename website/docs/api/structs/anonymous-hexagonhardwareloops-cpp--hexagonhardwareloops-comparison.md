---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-hexagonhardwareloops-cpp-/hexagonhardwareloops/comparison
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `Comparison` Struct

<p>Kinds of comparisons in the compare instructions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{HexagonHardwareLoops.cpp}::HexagonHardwareLoops::Comparison { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Kind { <a href="#a289dfbdfd74ca2ab7179706fb32e6a80">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Kind</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8909e7ad2482fbd52d6a0d4b659f8784">getSwappedComparison</a> (Kind Cmp)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Kind</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13f4f34a4bac1ae1147f8a323ac16dbf">getNegatedComparison</a> (Kind Cmp)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fb055c609fa521173a179e8f6301056">isSigned</a> (Kind Cmp)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a51f710ea2fcafa9fb870fcb48c7ab4">isUnsigned</a> (Kind Cmp)</td>
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

<p>Kinds of comparisons in the compare instructions.</p>

<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Kind {#a289dfbdfd74ca2ab7179706fb32e6a80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{HexagonHardwareLoops.cpp}::HexagonHardwareLoops::Comparison::Kind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EQ<a id="a289dfbdfd74ca2ab7179706fb32e6a80a6940210807a211ff45560012fdf714c4"></a></td>
<td class="doxyEnumItemDescription"> (= 0x01)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NE<a id="a289dfbdfd74ca2ab7179706fb32e6a80a59f53a7e9fc9c1efc42f7000fe090b56"></a></td>
<td class="doxyEnumItemDescription"> (= 0x02)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">L<a id="a289dfbdfd74ca2ab7179706fb32e6a80aa5e4e22a5faa4b55a866a3e60615eed4"></a></td>
<td class="doxyEnumItemDescription"> (= 0x04)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">G<a id="a289dfbdfd74ca2ab7179706fb32e6a80ad990cfa0c8f655e59167a41abe5e29f1"></a></td>
<td class="doxyEnumItemDescription"> (= 0x08)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">U<a id="a289dfbdfd74ca2ab7179706fb32e6a80a07f6035852e9c11e6fb10151cd213b01"></a></td>
<td class="doxyEnumItemDescription"> (= 0x40)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTs<a id="a289dfbdfd74ca2ab7179706fb32e6a80a3d53a53fabee9772e5f092b1a33190b8"></a></td>
<td class="doxyEnumItemDescription"> (= L)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LEs<a id="a289dfbdfd74ca2ab7179706fb32e6a80a723f1c085e2640ad870cc08b831b3824"></a></td>
<td class="doxyEnumItemDescription"> (= L | EQ)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GTs<a id="a289dfbdfd74ca2ab7179706fb32e6a80a65be4c48d8ce3c502cd825e30618b68d"></a></td>
<td class="doxyEnumItemDescription"> (= G)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GEs<a id="a289dfbdfd74ca2ab7179706fb32e6a80a40cfda5c275c8ddbad530f1d0b78d659"></a></td>
<td class="doxyEnumItemDescription"> (= G | EQ)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTu<a id="a289dfbdfd74ca2ab7179706fb32e6a80aadc4933c9344796926fee767a3daeb94"></a></td>
<td class="doxyEnumItemDescription"> (= L      | U)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LEu<a id="a289dfbdfd74ca2ab7179706fb32e6a80aad32c1ef2822bccf37d18258b29305ef"></a></td>
<td class="doxyEnumItemDescription"> (= L | EQ | U)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GTu<a id="a289dfbdfd74ca2ab7179706fb32e6a80a93c0367d7b8f149123bf5607809158b5"></a></td>
<td class="doxyEnumItemDescription"> (= G      | U)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GEu<a id="a289dfbdfd74ca2ab7179706fb32e6a80ac48b9e99ada7fedf9933ee4b4442857c"></a></td>
<td class="doxyEnumItemDescription"> (= G | EQ | U)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getNegatedComparison() {#a13f4f34a4bac1ae1147f8a323ac16dbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Kind anonymous{HexagonHardwareLoops.cpp}::HexagonHardwareLoops::Comparison::getNegatedComparison (Kind Cmp)</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>

</div>
</div>

### getSwappedComparison() {#a8909e7ad2482fbd52d6a0d4b659f8784}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Kind anonymous{HexagonHardwareLoops.cpp}::HexagonHardwareLoops::Comparison::getSwappedComparison (Kind Cmp)</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>

</div>
</div>

### isSigned() {#a0fb055c609fa521173a179e8f6301056}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{HexagonHardwareLoops.cpp}::HexagonHardwareLoops::Comparison::isSigned (Kind Cmp)</td>
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



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>

</div>
</div>

### isUnsigned() {#a3a51f710ea2fcafa9fb870fcb48c7ab4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{HexagonHardwareLoops.cpp}::HexagonHardwareLoops::Comparison::isUnsigned (Kind Cmp)</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
