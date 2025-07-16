---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/objcopy/elf/srecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SRecord` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::objcopy::elf::SRecord { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ObjCopy/ELF/ELFObject.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Type : uint8_t { <a href="#a742f40f4bf8902666799d9e85a4e76bb">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/objcopy/elf/#a9b6d42fb6e22ed2e5514e1ed333e4789">SRecLineData</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad1cb0897aed593c359266f009482c57">toString</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a907ddb9386934d9f9e75848e0cc7dc07">getCount</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6310bb27af9c4546fe123e3d550efc2c">getAddressSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f8b58c2001dca7186d4a97527a28063">getChecksum</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a304bafd2eb07a002fa5b59d6bcc400f0">getSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae47da2e4fcb90fb3a67870cd38c06861">Type</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c10ce793ef890474c025f588f981005">Address</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbf98665aaec658697904875d9c215a5">Data</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/srecord">SRecord</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a3e8a37182f3d235fba5f02768ce39a">getHeader</a> (StringRef FileName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5875f6e0e0f6d6113460b189e3af71b">getType</a> (uint32_t Address)</td>
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


<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Type {#a742f40f4bf8902666799d9e85a4e76bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::objcopy::elf::SRecord::Type : uint8_t</td>
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
<td class="doxyEnumItemName">S0<a id="a742f40f4bf8902666799d9e85a4e76bbaebe80369da4ef9f14bdad447174daf99"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S1<a id="a742f40f4bf8902666799d9e85a4e76bba19034685b9de7e2bb9f9043f1de551d4"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S2<a id="a742f40f4bf8902666799d9e85a4e76bba59a19ece47173697233af9eb09876fe1"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S3<a id="a742f40f4bf8902666799d9e85a4e76bbac4044e4d8abbe0ed4c3be8d1babda939"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S4<a id="a742f40f4bf8902666799d9e85a4e76bba9e59fee11618d44e972e8b0f6d23271b"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S5<a id="a742f40f4bf8902666799d9e85a4e76bba4d3a1ce5665ecab7eac2fd75fa177566"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S6<a id="a742f40f4bf8902666799d9e85a4e76bbaca8951e47f0151fd34a9d7d34dba7845"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S7<a id="a742f40f4bf8902666799d9e85a4e76bbaca85bf2727b1affb73bd2c22ceaa7c0f"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S8<a id="a742f40f4bf8902666799d9e85a4e76bba1346207ad1e41cfab512ac3fc9f03738"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S9<a id="a742f40f4bf8902666799d9e85a4e76bbaf017c1deeb36b45c4d3e914599796405"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAddressSize() {#a6310bb27af9c4546fe123e3d550efc2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t SRecord::getAddressSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>, definition at line 2977 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="#a742f40f4bf8902666799d9e85a4e76bba59a19ece47173697233af9eb09876fe1">S2</a>, <a href="#a742f40f4bf8902666799d9e85a4e76bbac4044e4d8abbe0ed4c3be8d1babda939">S3</a>, <a href="#a742f40f4bf8902666799d9e85a4e76bbaca85bf2727b1affb73bd2c22ceaa7c0f">S7</a> and <a href="#a742f40f4bf8902666799d9e85a4e76bba1346207ad1e41cfab512ac3fc9f03738">S8</a>.</p>


<p>Referenced by <a href="#a907ddb9386934d9f9e75848e0cc7dc07">getCount</a>, <a href="#a304bafd2eb07a002fa5b59d6bcc400f0">getSize</a> and <a href="#aad1cb0897aed593c359266f009482c57">toString</a>.</p>

</div>
</div>

### getChecksum() {#a8f8b58c2001dca7186d4a97527a28063}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t SRecord::getChecksum ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>, definition at line 2961 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="#a0c10ce793ef890474c025f588f981005">Address</a>, <a href="#afbf98665aaec658697904875d9c215a5">Data</a> and <a href="#a907ddb9386934d9f9e75848e0cc7dc07">getCount</a>.</p>


<p>Referenced by <a href="#aad1cb0897aed593c359266f009482c57">toString</a>.</p>

</div>
</div>

### getCount() {#a907ddb9386934d9f9e75848e0cc7dc07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t SRecord::getCount ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>, definition at line 2992 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="#afbf98665aaec658697904875d9c215a5">Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b9d675b34f20ba67f1f3213e63935d6">llvm::DataSize</a> and <a href="#a6310bb27af9c4546fe123e3d550efc2c">getAddressSize</a>.</p>


<p>Referenced by <a href="#a8f8b58c2001dca7186d4a97527a28063">getChecksum</a> and <a href="#aad1cb0897aed593c359266f009482c57">toString</a>.</p>

</div>
</div>

### getSize() {#a304bafd2eb07a002fa5b59d6bcc400f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t SRecord::getSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>, definition at line 2972 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="#afbf98665aaec658697904875d9c215a5">Data</a> and <a href="#a6310bb27af9c4546fe123e3d550efc2c">getAddressSize</a>.</p>


<p>Referenced by <a href="#aad1cb0897aed593c359266f009482c57">toString</a>.</p>

</div>
</div>

### toString() {#aad1cb0897aed593c359266f009482c57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SRecLineData SRecord::toString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>, definition at line 2941 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="#a0c10ce793ef890474c025f588f981005">Address</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afbf98665aaec658697904875d9c215a5">Data</a>, <a href="#a6310bb27af9c4546fe123e3d550efc2c">getAddressSize</a>, <a href="#a8f8b58c2001dca7186d4a97527a28063">getChecksum</a>, <a href="#a907ddb9386934d9f9e75848e0cc7dc07">getCount</a>, <a href="#a304bafd2eb07a002fa5b59d6bcc400f0">getSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp/#ace9ca57da9b4fcd62a7db7e96bd75a73">toHexStr</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Address {#a0c10ce793ef890474c025f588f981005}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::objcopy::elf::SRecord::Address</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>.</p>


<p>Referenced by <a href="#a8f8b58c2001dca7186d4a97527a28063">getChecksum</a>, <a href="#ab5875f6e0e0f6d6113460b189e3af71b">getType</a> and <a href="#aad1cb0897aed593c359266f009482c57">toString</a>.</p>

</div>
</div>

### Data {#afbf98665aaec658697904875d9c215a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;uint8_t&gt; llvm::objcopy::elf::SRecord::Data</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>.</p>


<p>Referenced by <a href="#a8f8b58c2001dca7186d4a97527a28063">getChecksum</a>, <a href="#a907ddb9386934d9f9e75848e0cc7dc07">getCount</a>, <a href="#a8a3e8a37182f3d235fba5f02768ce39a">getHeader</a>, <a href="#a304bafd2eb07a002fa5b59d6bcc400f0">getSize</a> and <a href="#aad1cb0897aed593c359266f009482c57">toString</a>.</p>

</div>
</div>

### Type {#ae47da2e4fcb90fb3a67870cd38c06861}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::objcopy::elf::SRecord::Type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getHeader() {#a8a3e8a37182f3d235fba5f02768ce39a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SRecord SRecord::getHeader (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileName)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 431 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>, definition at line 3006 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="#afbf98665aaec658697904875d9c215a5">Data</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="#a742f40f4bf8902666799d9e85a4e76bbaebe80369da4ef9f14bdad447174daf99">S0</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5d4c961b9b6f1da17df74b4496ecb30e">llvm::StringRef::slice</a>.</p>

</div>
</div>

### getType() {#ab5875f6e0e0f6d6113460b189e3af71b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t SRecord::getType (uint32_t Address)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>, definition at line 2998 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="#a0c10ce793ef890474c025f588f981005">Address</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="#a742f40f4bf8902666799d9e85a4e76bba19034685b9de7e2bb9f9043f1de551d4">S1</a>, <a href="#a742f40f4bf8902666799d9e85a4e76bba59a19ece47173697233af9eb09876fe1">S2</a> and <a href="#a742f40f4bf8902666799d9e85a4e76bbac4044e4d8abbe0ed4c3be8d1babda939">S3</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/srecsectionwriterbase/#abc7373c3b2afd5c375f9eae60795bda2">llvm::objcopy::elf::SRECSectionWriterBase::writeRecords</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/srecsectionwriterbase/#a6c620527600c3b7b2f5ef48b7646b0c4">llvm::objcopy::elf::SRECSectionWriterBase::writeSection</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
