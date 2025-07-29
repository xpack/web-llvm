---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/locationsize
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LocationSize` Class



## Declaration

<div class="doxyDeclaration">
class llvm::LocationSize { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">llvm/Analysis/MemoryLocation.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : uint64_t { <a href="#aba5fb73504d834a78f9d50d353398156">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">DirectConstruction { <a href="#a46d61827f2642558d9a1c8c7e2b27dcb">...</a> }</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae16137b885e5f7ee982f3ccb51b3fb81">LocationSize</a> (uint64_t Raw)</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d4cbdf5a1dd49ab9f2794f7d363a45f">LocationSize</a> (uint64_t Raw, DirectConstruction)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac2e5a30a2f5dfb5ff6a873e8acdd2d0">LocationSize</a> (uint64_t Raw, bool Scalable)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0949875354a95e7f895f3f87c0069bd">operator==</a> (const LocationSize &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a5e6f096143f4eca061f95f799dfeed">operator==</a> (const TypeSize &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaf0d80c1a93c63cc754660cf1c19d5f">operator!=</a> (const LocationSize &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fd108dacea905cc454e12e068d76175">operator!=</a> (const TypeSize &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accca9053ed30001b2ecd8347185d5d15">unionWith</a> (LocationSize Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b0401973fc9567440717a5d32a8eb8d">hasValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a900ef826f2fe747a00dc0bdb6b8ede87">isScalable</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a935a116f6c8690449f4eddd56a99504b">getValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9addaa6f7dd437922a57401cb192031">isPrecise</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a537a836fd9ef45c214308647907c69">isZero</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63bfde5a87e5175ab0a7844f2e5f5b6e">mayBeBeforePointer</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether accesses before the base pointer are possible. <a href="#a63bfde5a87e5175ab0a7844f2e5f5b6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b1d91a833a8210d4caf546e162ac627">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac69af0ff907e2fce2761442c786e5826">toRaw</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02efbc73bc5ad30fde12b7c56a87a756">Value</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a131715ceeb92fb803a329d6b76d14e0d">precise</a> (uint64_t Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afad081db71105d49ad801cd59bf99fb6">precise</a> (TypeSize Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7198c4852982f1005eb076b6ab126de">upperBound</a> (uint64_t Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56dd523202cf281642d8b54ecfaa2a39">upperBound</a> (TypeSize Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac01c1aa625e97bf21d27474544c463e5">afterPointer</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> location after the base pointer (but still within the underlying object). <a href="#ac01c1aa625e97bf21d27474544c463e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a837cf7f4d88580c0adb92afc6a3b08b0">beforeOrAfterPointer</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> location before or after the base pointer (but still within the underlying object). <a href="#a837cf7f4d88580c0adb92afc6a3b08b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae61749c787fd24d5402cb9fc9c6abe18">mapTombstone</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4758816718d91b0bb3a208a49039adf4">mapEmpty</a> ()</td>
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


<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#aba5fb73504d834a78f9d50d353398156}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : uint64_t</td>
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
<td class="doxyEnumItemName">BeforeOrAfterPointer<a id="aba5fb73504d834a78f9d50d353398156a7a545983adac7b733c6b1ee961c0122d"></a></td>
<td class="doxyEnumItemDescription"> (= ~uint64_t(0))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ScalableBit<a id="aba5fb73504d834a78f9d50d353398156a5c3be5908c0e527ac7868af8c6c0c704"></a></td>
<td class="doxyEnumItemDescription"> (= uint64_t(1) &lt;&lt; 62)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AfterPointer<a id="aba5fb73504d834a78f9d50d353398156ac8a0854b19ffa58bf4ac2614e59bb66a"></a></td>
<td class="doxyEnumItemDescription"> (= (BeforeOrAfterPointer - 1) &amp; ~ScalableBit)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MapEmpty<a id="aba5fb73504d834a78f9d50d353398156ae385ff8db4006b534dde63c04cfc7aae"></a></td>
<td class="doxyEnumItemDescription"> (= BeforeOrAfterPointer - 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MapTombstone<a id="aba5fb73504d834a78f9d50d353398156a44e37c06f8c9fb66482954cb47080453"></a></td>
<td class="doxyEnumItemDescription"> (= BeforeOrAfterPointer - 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImpreciseBit<a id="aba5fb73504d834a78f9d50d353398156a906e7142cf965e91f856114ec33e9e13"></a></td>
<td class="doxyEnumItemDescription"> (= uint64_t(1) &lt;&lt; 63)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MaxValue<a id="aba5fb73504d834a78f9d50d353398156ae1b64ce42673dedabb9bd40ba2f16a95"></a></td>
<td class="doxyEnumItemDescription"> (= (MapTombstone - 1) &amp; ~(ImpreciseBit | ScalableBit))</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>

</div>
</div>

### DirectConstruction {#a46d61827f2642558d9a1c8c7e2b27dcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::LocationSize::DirectConstruction </td>
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
<td class="doxyEnumItemName">Direct<a id="a46d61827f2642558d9a1c8c7e2b27dcba0327ffa3e50deaa5924aeea7ceeaefba"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LocationSize() {#ae16137b885e5f7ee982f3ccb51b3fb81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LocationSize::LocationSize (uint64_t Raw)</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### LocationSize() {#a0d4cbdf5a1dd49ab9f2794f7d363a45f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LocationSize::LocationSize (uint64_t Raw, DirectConstruction)</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>

</div>
</div>

### LocationSize() {#aac2e5a30a2f5dfb5ff6a873e8acdd2d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LocationSize::LocationSize (uint64_t Raw, bool Scalable)</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#aaaf0d80c1a93c63cc754660cf1c19d5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LocationSize::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a> &amp; Other)</td>
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



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator!=() {#a9fd108dacea905cc454e12e068d76175}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LocationSize::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a> &amp; Other)</td>
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



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator==() {#af0949875354a95e7f895f3f87c0069bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LocationSize::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a> &amp; Other)</td>
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



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator==() {#a7a5e6f096143f4eca061f95f799dfeed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LocationSize::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a> &amp; Other)</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>References <a href="#a935a116f6c8690449f4eddd56a99504b">getValue</a>, <a href="#a0b0401973fc9567440717a5d32a8eb8d">hasValue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getValue() {#a935a116f6c8690449f4eddd56a99504b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeSize llvm::LocationSize::getValue ()</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0b0401973fc9567440717a5d32a8eb8d">hasValue</a> and <a href="#a900ef826f2fe747a00dc0bdb6b8ede87">isScalable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scevaaresult/#a688068ae24921ce2ed14ca5ff0b732e2">llvm::SCEVAAResult::alias</a>, <a href="/web-llvm/docs/api/namespaces/llvm/giseladdressing/#a140cb977d5598588fb9e0079cd1aabf9">llvm::GISelAddressing::aliasIsKnownForLoadStore</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonsubtarget/bankconflictmutation/#a336138bbbfacbbb4be8c56d41f08b0c2">llvm::HexagonSubtarget::BankConflictMutation::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a87ac3f636dddf683cf1f9b7f1a60b1ae">llvm::AMDGPURegisterBankInfo::applyMappingLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a00f254751a3efe88d446fe5fdba2d7c4">llvm::LanaiInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a878d28bcb9d1575d5f5e56c5b1bcf064">llvm::PPCInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#afc0ac4e187f1865c16f5dd0814e7fa5b">llvm::RISCVInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#ab357dab967cae539bb19a9aa0a101fed">llvm::SystemZInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp/#ac33670a87c023e6ae45daf3df0a4cd1e">canSkipClobberingStore</a>, <a href="/web-llvm/docs/api/classes/llvm/baseindexoffset/#abceb615c6b3c238ec35d098d6925bcea">llvm::BaseIndexOffset::computeAliasing</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a651adf8bbb2fece837c1ef70250e19ce">llvm::GISelKnownBits::computeNumSignBits</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6885e40448874565521daac98e11f50d">llvm::TargetInstrInfo::describeLoadedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armbankconflicthazardrecognizer/#a4a4c40e81d31e50617db9eb227bc1707">llvm::ARMBankConflictHazardRecognizer::EmitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/ppchazardrecognizer970/#afe71af95c1e795a56d13e488898d58f5">llvm::PPCHazardRecognizer970::EmitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a414d9dfa6f85f8ad371a510821713e61">llvm::PPCTargetLowering::expandVSXLoadForLE</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#abf2cd323dcdc4b2b0a4741c62b30d0ba">llvm::PPCTargetLowering::expandVSXStoreForLE</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/instrrefbasedldv/#a3c1165eb09769fbc90612ff41c1830b3">LiveDebugValues::InstrRefBasedLDV::findLocationForMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ppchazardrecognizer970/#a930f5688f2bff088096f72a68000c94e">llvm::PPCHazardRecognizer970::getHazardType</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a0c826f5192676a1dfa8468a38b9ce1c3">llvm::SIInstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a8f69c05b63d549b2e51069b6edaf73c6">getMinimalExtentFrom</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a7d8410ca3fc6fb227416067d3c2535d2">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::getNonAliasingPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#a213eed2958a020a3cb8a92627acd4577">getSpillSlotSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/giseladdressing/#ada859501cbde2153a4e7fd7a19a7f682">llvm::GISelAddressing::instMayAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a78e274f7aa81fdeddac470d645c3c6e8">llvm::SwingSchedulerDAG::isLoopCarriedDep</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#ad2005ee17b5b6cb575257dc12793a077">anonymous{DeadStoreElimination.cpp}::DSEState::isOverwrite</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#aa46849ad227581d0105b7c41b4f9377f">isPartialOverwrite</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a7ebf01237ea354d0baf26fae2f0a04a3">llvm::AMDGPURegisterBankInfo::isScalarLoadLegal</a>, <a href="#a9a537a836fd9ef45c214308647907c69">isZero</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a2324ad614c957fc91b34a00f32e89d60">llvm::AMDGPULegalizerInfo::legalizeBufferStore</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a5d600f23e7d301bfcf60b292eaba31ef">llvm::CombinerHelper::matchCombineLoadWithAndMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#a3d46b900827f1a36ca44ea87cfb18e1f">MemOperandsHaveAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6701d040466d73f3dc51481d3186c294">llvm::LegalizerHelper::narrowScalar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a4ba9a87e58860879f35c8d0a7b3ed5ad">offsetsDoNotOverlap</a>, <a href="#a7a5e6f096143f4eca061f95f799dfeed">operator==</a>, <a href="#a9b1d91a833a8210d4caf546e162ac627">print</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a8eb21f893b8039f4edcc3e3bce0c319e">llvm::LegalizerHelper::reduceLoadStoreWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/regbanklegalizerules/#a4b79850edbd4118074e95097dca45fa5">llvm::AMDGPU::RegBankLegalizeRules::RegBankLegalizeRules</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcinstructionselector-cpp-/ppcinstructionselector/#a051c8a2638fc5f95b9ccd5e82a7a8559">anonymous{PPCInstructionSelector.cpp}::PPCInstructionSelector::select</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#adef06ef7e91c27f8cca2b635c3f1a178">llvm::PPCInstrInfo::shouldClusterMemOps</a>, <a href="#accca9053ed30001b2ecd8347185d5d15">unionWith</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a>.</p>

</div>
</div>

### hasValue() {#a0b0401973fc9567440717a5d32a8eb8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LocationSize::hasValue ()</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scevaaresult/#a688068ae24921ce2ed14ca5ff0b732e2">llvm::SCEVAAResult::alias</a>, <a href="/web-llvm/docs/api/namespaces/llvm/giseladdressing/#a140cb977d5598588fb9e0079cd1aabf9">llvm::GISelAddressing::aliasIsKnownForLoadStore</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonsubtarget/bankconflictmutation/#a336138bbbfacbbb4be8c56d41f08b0c2">llvm::HexagonSubtarget::BankConflictMutation::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a00f254751a3efe88d446fe5fdba2d7c4">llvm::LanaiInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a878d28bcb9d1575d5f5e56c5b1bcf064">llvm::PPCInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#afc0ac4e187f1865c16f5dd0814e7fa5b">llvm::RISCVInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#ab357dab967cae539bb19a9aa0a101fed">llvm::SystemZInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp/#ac33670a87c023e6ae45daf3df0a4cd1e">canSkipClobberingStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/basememopclustermutation/#a97b8f22f6c8ebb59fe454ba80d407baa">anonymous{MachineScheduler.cpp}::BaseMemOpClusterMutation::collectMemOpRecords</a>, <a href="/web-llvm/docs/api/classes/llvm/baseindexoffset/#abceb615c6b3c238ec35d098d6925bcea">llvm::BaseIndexOffset::computeAliasing</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6885e40448874565521daac98e11f50d">llvm::TargetInstrInfo::describeLoadedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armbankconflicthazardrecognizer/#a4a4c40e81d31e50617db9eb227bc1707">llvm::ARMBankConflictHazardRecognizer::EmitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a414d9dfa6f85f8ad371a510821713e61">llvm::PPCTargetLowering::expandVSXLoadForLE</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#abf2cd323dcdc4b2b0a4741c62b30d0ba">llvm::PPCTargetLowering::expandVSXStoreForLE</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/instrrefbasedldv/#a3c1165eb09769fbc90612ff41c1830b3">LiveDebugValues::InstrRefBasedLDV::findLocationForMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ppchazardrecognizer970/#a930f5688f2bff088096f72a68000c94e">llvm::PPCHazardRecognizer970::getHazardType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#a213eed2958a020a3cb8a92627acd4577">getSpillSlotSize</a>, <a href="#a935a116f6c8690449f4eddd56a99504b">getValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/giseladdressing/#ada859501cbde2153a4e7fd7a19a7f682">llvm::GISelAddressing::instMayAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a78e274f7aa81fdeddac470d645c3c6e8">llvm::SwingSchedulerDAG::isLoopCarriedDep</a>, <a href="#a9a537a836fd9ef45c214308647907c69">isZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#a3d46b900827f1a36ca44ea87cfb18e1f">MemOperandsHaveAlias</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a4ba9a87e58860879f35c8d0a7b3ed5ad">offsetsDoNotOverlap</a>, <a href="#a7a5e6f096143f4eca061f95f799dfeed">operator==</a> and <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a6cf00cf755c1275eba246de7ebf7842d">llvm::MachineMemOperand::refineAlignment</a>.</p>

</div>
</div>

### isPrecise() {#aa9addaa6f7dd437922a57401cb192031}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LocationSize::isPrecise ()</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a8f69c05b63d549b2e51069b6edaf73c6">getMinimalExtentFrom</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#ad2005ee17b5b6cb575257dc12793a077">anonymous{DeadStoreElimination.cpp}::DSEState::isOverwrite</a> and <a href="#a9b1d91a833a8210d4caf546e162ac627">print</a>.</p>

</div>
</div>

### isScalable() {#a900ef826f2fe747a00dc0bdb6b8ede87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LocationSize::isScalable ()</td>
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



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/giseladdressing/#a140cb977d5598588fb9e0079cd1aabf9">llvm::GISelAddressing::aliasIsKnownForLoadStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp/#ac33670a87c023e6ae45daf3df0a4cd1e">canSkipClobberingStore</a>, <a href="/web-llvm/docs/api/classes/llvm/baseindexoffset/#abceb615c6b3c238ec35d098d6925bcea">llvm::BaseIndexOffset::computeAliasing</a>, <a href="#a935a116f6c8690449f4eddd56a99504b">getValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/giseladdressing/#ada859501cbde2153a4e7fd7a19a7f682">llvm::GISelAddressing::instMayAlias</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#ad2005ee17b5b6cb575257dc12793a077">anonymous{DeadStoreElimination.cpp}::DSEState::isOverwrite</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#a3d46b900827f1a36ca44ea87cfb18e1f">MemOperandsHaveAlias</a> and <a href="#accca9053ed30001b2ecd8347185d5d15">unionWith</a>.</p>

</div>
</div>

### isZero() {#a9a537a836fd9ef45c214308647907c69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LocationSize::isZero ()</td>
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



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="#a935a116f6c8690449f4eddd56a99504b">getValue</a> and <a href="#a0b0401973fc9567440717a5d32a8eb8d">hasValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scevaaresult/#a688068ae24921ce2ed14ca5ff0b732e2">llvm::SCEVAAResult::alias</a>.</p>

</div>
</div>

### mayBeBeforePointer() {#a63bfde5a87e5175ab0a7844f2e5f5b6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LocationSize::mayBeBeforePointer ()</td>
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

<p>Whether accesses before the base pointer are possible.</p>

<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>

</div>
</div>

### print() {#a9b1d91a833a8210d4caf546e162ac627}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LocationSize::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>, definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorylocation-cpp">MemoryLocation.cpp</a>.</p>


<p>References <a href="#ac01c1aa625e97bf21d27474544c463e5">afterPointer</a>, <a href="#a837cf7f4d88580c0adb92afc6a3b08b0">beforeOrAfterPointer</a>, <a href="#a935a116f6c8690449f4eddd56a99504b">getValue</a>, <a href="#aa9addaa6f7dd437922a57401cb192031">isPrecise</a>, <a href="#a4758816718d91b0bb3a208a49039adf4">mapEmpty</a> and <a href="#ae61749c787fd24d5402cb9fc9c6abe18">mapTombstone</a>.</p>

</div>
</div>

### toRaw() {#ac69af0ff907e2fce2761442c786e5826}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::LocationSize::toRaw ()</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-b3f02d53fe13cccf1ed6335c94eda135/#aefced0f3f3bbaf3384b29c02d7f653ce">llvm::DenseMapInfo&lt; LocationSize &gt;::getHashValue</a>.</p>

</div>
</div>

### unionWith() {#accca9053ed30001b2ecd8347185d5d15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocationSize llvm::LocationSize::unionWith (<a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a> Other)</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>References <a href="#ac01c1aa625e97bf21d27474544c463e5">afterPointer</a>, <a href="#a837cf7f4d88580c0adb92afc6a3b08b0">beforeOrAfterPointer</a>, <a href="#a935a116f6c8690449f4eddd56a99504b">getValue</a>, <a href="#a900ef826f2fe747a00dc0bdb6b8ede87">isScalable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#ad7198c4852982f1005eb076b6ab126de">upperBound</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Value {#a02efbc73bc5ad30fde12b7c56a87a756}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::LocationSize::Value</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### afterPointer() {#ac01c1aa625e97bf21d27474544c463e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr LocationSize llvm::LocationSize::afterPointer ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> location after the base pointer (but still within the underlying object).</p>

<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a7a7fb118760760e7530c5d6f5be6ce64">llvm::MemoryLocation::get</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a49f776e0940cc5d63d17d85ff6dac257">llvm::MemoryLocation::getAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#afc51de08aefeeaabc77fefacc869dbd4">llvm::MemoryLocation::getForArgument</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#ade6253c0c19609ec9c632e60e08896fb">mayLoopAccessLocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonloopidiomrecognition-cpp/#abeee69852204fbee049fd520bdedbaae">mayLoopAccessLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasset/#a402ffc8c32cbcbcf858f1188ce7a4c87">llvm::AliasSet::print</a>, <a href="#a9b1d91a833a8210d4caf546e162ac627">print</a>, <a href="#accca9053ed30001b2ecd8347185d5d15">unionWith</a>, <a href="#a56dd523202cf281642d8b54ecfaa2a39">upperBound</a> and <a href="#ad7198c4852982f1005eb076b6ab126de">upperBound</a>.</p>

</div>
</div>

### beforeOrAfterPointer() {#a837cf7f4d88580c0adb92afc6a3b08b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr LocationSize llvm::LocationSize::beforeOrAfterPointer ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> location before or after the base pointer (but still within the underlying object).</p>

<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scevaaresult/#a688068ae24921ce2ed14ca5ff0b732e2">llvm::SCEVAAResult::alias</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a46815b7f69bb96eddd2e1e01bec6120c">llvm::MemoryLocation::getBeforeOrAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a0ffa31699dee0349f9b9ae1d3ccb21f1">llvm::MachineMemOperand::getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#abcceb535a4bb1e23c320e7628476bd5d">llvm::MachineMemOperand::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#a213eed2958a020a3cb8a92627acd4577">getSpillSlotSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizedag-cpp/#a845c5871499188129bc91bba5e1f03bf">getStackAlignedMMO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/giseladdressing/#ada859501cbde2153a4e7fd7a19a7f682">llvm::GISelAddressing::instMayAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ab4a6a57aa863f068433ba056f15c61b1">llvm::RISCVInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a84a7819a9f36f529085ab85492b5a4d7">performVP_REVERSECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a90e158dcd9e3da205b3703145ed4cfcb">performVP_STORECombine</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasset/#a402ffc8c32cbcbcf858f1188ce7a4c87">llvm::AliasSet::print</a>, <a href="#a9b1d91a833a8210d4caf546e162ac627">print</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a23e6d76b3b763236213c20fdd08718ed">llvm::RISCVInstrInfo::storeRegToStackSlot</a> and <a href="#accca9053ed30001b2ecd8347185d5d15">unionWith</a>.</p>

</div>
</div>

### mapEmpty() {#a4758816718d91b0bb3a208a49039adf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr LocationSize llvm::LocationSize::mapEmpty ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-b3f02d53fe13cccf1ed6335c94eda135/#aff6cc6921ee3396efa9ffc9660c77103">llvm::DenseMapInfo&lt; LocationSize &gt;::getEmptyKey</a> and <a href="#a9b1d91a833a8210d4caf546e162ac627">print</a>.</p>

</div>
</div>

### mapTombstone() {#ae61749c787fd24d5402cb9fc9c6abe18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr LocationSize llvm::LocationSize::mapTombstone ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-b3f02d53fe13cccf1ed6335c94eda135/#a6ba30dbcafdf1e71ad24ddea1670a6c9">llvm::DenseMapInfo&lt; LocationSize &gt;::getTombstoneKey</a> and <a href="#a9b1d91a833a8210d4caf546e162ac627">print</a>.</p>

</div>
</div>

### precise() {#a131715ceeb92fb803a329d6b76d14e0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocationSize llvm::LocationSize::precise (uint64_t Value)</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/loads-cpp/#abae944a67cbc6299389596f63df4359a">areNonOverlapSameBaseLoadAndStore</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a6c1bd5fd8ec3eeb7320cd9d457b0f164">llvm::MemoryLocation::get</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a46d61c561714322cb42bd3db9f1609fa">llvm::MemoryLocation::get</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a18e5a3f1d71ba10a624f2a8e5121cf1f">llvm::MemoryLocation::get</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a4037bfe373761aedbe48f3010dbadfed">llvm::MemoryLocation::get</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#afc51de08aefeeaabc77fefacc869dbd4">llvm::MemoryLocation::getForArgument</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#ae58d526e759487737de52702abf2b7c5">anonymous{DeadStoreElimination.cpp}::DSEState::getInitializesArgMemLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a564ffef4d327c872fe912322813e6a2f">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a0f49cd7f0f28bd9b7aaed4b5a0df02d6">getLoadStackGuard</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab847f1d70cf17cd2250d78d4bb19ec4e">llvm::SelectionDAG::getLoadVP</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a9a24d61ebbaf960b10d22de71b388be3">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a697dec75b5e5a66bd8e0312542cd63b3">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#acf9d481ec021e4bbb5429f0f6d7fcba9">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae6cc63109335eefe2c5727d1e12fc820">llvm::SelectionDAG::getMemIntrinsicNode</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a512855a97cf9032c007ca232000a81ba">llvm::AArch64InstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a0ffa31699dee0349f9b9ae1d3ccb21f1">llvm::MachineMemOperand::getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#abcceb535a4bb1e23c320e7628476bd5d">llvm::MachineMemOperand::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizedag-cpp/#a845c5871499188129bc91bba5e1f03bf">getStackAlignedMMO</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a89ed6b26ee4f62aec32468329f828a2f">llvm::SelectionDAG::getStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8063c77c39146c0790e66f5e0679475c">llvm::SelectionDAG::getTruncStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abf715e866131db937a292ab35643ca0c">llvm::SelectionDAG::getTruncStoreVP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/giseladdressing/#ada859501cbde2153a4e7fd7a19a7f682">llvm::GISelAddressing::instMayAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#ae00965005028c567c9c8d860655218b4">llvm::AAResults::isMustAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/batchaaresults/#ad5fc7dbdc17cdbefcd19aaa4026796fb">llvm::BatchAAResults::isMustAlias</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#ade6253c0c19609ec9c632e60e08896fb">mayLoopAccessLocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonloopidiomrecognition-cpp/#abeee69852204fbee049fd520bdedbaae">mayLoopAccessLocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#a3d46b900827f1a36ca44ea87cfb18e1f">MemOperandsHaveAlias</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a528e38dffd58ba9e81a7a05fb7d44c11">narrowExtractedVectorLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#aaa3589bcd74d9f4a9131af14ccd5a430">anonymous{DeadStoreElimination.cpp}::DSEState::strengthenLocationSize</a> and <a href="#ad7198c4852982f1005eb076b6ab126de">upperBound</a>.</p>

</div>
</div>

### precise() {#afad081db71105d49ad801cd59bf99fb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocationSize llvm::LocationSize::precise (<a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a> Value)</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>

</div>
</div>

### upperBound() {#ad7198c4852982f1005eb076b6ab126de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocationSize llvm::LocationSize::upperBound (uint64_t Value)</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>References <a href="#ac01c1aa625e97bf21d27474544c463e5">afterPointer</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a104cae72182bec0ab951e3faea6ce509">LLVM_UNLIKELY</a> and <a href="#a131715ceeb92fb803a329d6b76d14e0d">precise</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#afc51de08aefeeaabc77fefacc869dbd4">llvm::MemoryLocation::getForArgument</a>, <a href="#accca9053ed30001b2ecd8347185d5d15">unionWith</a> and <a href="#a56dd523202cf281642d8b54ecfaa2a39">upperBound</a>.</p>

</div>
</div>

### upperBound() {#a56dd523202cf281642d8b54ecfaa2a39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocationSize llvm::LocationSize::upperBound (<a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a> Value)</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a>.</p>


<p>References <a href="#ac01c1aa625e97bf21d27474544c463e5">afterPointer</a> and <a href="#ad7198c4852982f1005eb076b6ab126de">upperBound</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">MemoryLocation.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/memorylocation-cpp">MemoryLocation.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
