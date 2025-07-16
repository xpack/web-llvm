---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/arccc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `ARCCC` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::ARCCC { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CondCode { <a href="#a9a81d9a1b379cf08150b22e81d7dd006">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">BRCondCode { <a href="#ab2a5c94ee5074aa9f31e28eda349b514">...</a> }</td>
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


<div class="doxySectionDef">

## Enumerations

### BRCondCode {#ab2a5c94ee5074aa9f31e28eda349b514}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ARCCC::BRCondCode </td>
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
<td class="doxyEnumItemName">BREQ<a id="ab2a5c94ee5074aa9f31e28eda349b514a03c139be512230f487f62726e1b35ab6"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BRNE<a id="ab2a5c94ee5074aa9f31e28eda349b514a9ec00135d7244a871984916d30cc30d2"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BRLT<a id="ab2a5c94ee5074aa9f31e28eda349b514aa9cd1b80e294031e0f457decbacabbb8"></a></td>
<td class="doxyEnumItemDescription"> (= 0x2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BRGE<a id="ab2a5c94ee5074aa9f31e28eda349b514a8e5753127b5f0ebc0f897447a7400d72"></a></td>
<td class="doxyEnumItemDescription"> (= 0x3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BRLO<a id="ab2a5c94ee5074aa9f31e28eda349b514ab763925d9e680ff06a428384411b74c5"></a></td>
<td class="doxyEnumItemDescription"> (= 0x4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BRHS<a id="ab2a5c94ee5074aa9f31e28eda349b514a47a1b9aad95fdf10ec422d8e6432a8be"></a></td>
<td class="doxyEnumItemDescription"> (= 0x5)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/mctargetdesc/arcinfo-h">ARCInfo.h</a>.</p>

</div>
</div>

### CondCode {#a9a81d9a1b379cf08150b22e81d7dd006}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ARCCC::CondCode </td>
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
<td class="doxyEnumItemName">AL<a id="a9a81d9a1b379cf08150b22e81d7dd006a912a5b8c0856fad709590b5d47aae1c7"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EQ<a id="a9a81d9a1b379cf08150b22e81d7dd006a06424d16ad2a930de1f57d6b564cbc1b"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NE<a id="a9a81d9a1b379cf08150b22e81d7dd006a913770d7f2c3565cff9146efa0621b8d"></a></td>
<td class="doxyEnumItemDescription"> (= 0x2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">P<a id="a9a81d9a1b379cf08150b22e81d7dd006a99e83610e4f815aa0556a531f26b2572"></a></td>
<td class="doxyEnumItemDescription"> (= 0x3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">N<a id="a9a81d9a1b379cf08150b22e81d7dd006a4846867f356ee9f45a8c45853d5f7e7a"></a></td>
<td class="doxyEnumItemDescription"> (= 0x4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LO<a id="a9a81d9a1b379cf08150b22e81d7dd006a01b7f88b89f69e354f814793602b2256"></a></td>
<td class="doxyEnumItemDescription"> (= 0x5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HS<a id="a9a81d9a1b379cf08150b22e81d7dd006a4c1cec33829d627ebeeb767b3d2b2c36"></a></td>
<td class="doxyEnumItemDescription"> (= 0x6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VS<a id="a9a81d9a1b379cf08150b22e81d7dd006a8172a107e0d48ee61e1f7631ad071c37"></a></td>
<td class="doxyEnumItemDescription"> (= 0x7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VC<a id="a9a81d9a1b379cf08150b22e81d7dd006a6a9fb8f59362e12960359e5a55f777c8"></a></td>
<td class="doxyEnumItemDescription"> (= 0x8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GT<a id="a9a81d9a1b379cf08150b22e81d7dd006ad55c9ceb8b27f401f5d82c0ebd20d6be"></a></td>
<td class="doxyEnumItemDescription"> (= 0x9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GE<a id="a9a81d9a1b379cf08150b22e81d7dd006a815eaffff57498d8c26b03fb3510dec6"></a></td>
<td class="doxyEnumItemDescription"> (= 0xa)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LT<a id="a9a81d9a1b379cf08150b22e81d7dd006a1695055effb07e0e8e69ff10aff4756b"></a></td>
<td class="doxyEnumItemDescription"> (= 0xb)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LE<a id="a9a81d9a1b379cf08150b22e81d7dd006aadc05bce3350700bee41e8525d23acc1"></a></td>
<td class="doxyEnumItemDescription"> (= 0xc)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HI<a id="a9a81d9a1b379cf08150b22e81d7dd006ad072d903ed389a04331251bbbc069524"></a></td>
<td class="doxyEnumItemDescription"> (= 0xd)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LS<a id="a9a81d9a1b379cf08150b22e81d7dd006ae0363d765d2cb82180e8db9332366d2b"></a></td>
<td class="doxyEnumItemDescription"> (= 0xe)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PNZ<a id="a9a81d9a1b379cf08150b22e81d7dd006a71fc36687f36bb6cc52543c8cc812b0c"></a></td>
<td class="doxyEnumItemDescription"> (= 0xf)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Z<a id="a9a81d9a1b379cf08150b22e81d7dd006aceb189306b941666e679bf556207c1e4"></a></td>
<td class="doxyEnumItemDescription"> (= 0x11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NZ<a id="a9a81d9a1b379cf08150b22e81d7dd006a799e707160aac5ed5107d38155b69d69"></a></td>
<td class="doxyEnumItemDescription"> (= 0x12)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/mctargetdesc/arcinfo-h">ARCInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/mctargetdesc/arcinfo-h">ARCInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
