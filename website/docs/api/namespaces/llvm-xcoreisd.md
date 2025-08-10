---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/xcoreisd
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `XCoreISD` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::XCoreISD { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">NodeType : unsigned { <a href="#a34e7964aa899176244e03cb7b1fc5985">...</a> }</td>
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

### NodeType {#a34e7964aa899176244e03cb7b1fc5985}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::XCoreISD::NodeType : unsigned</td>
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
<td class="doxyEnumItemName">FIRST_NUMBER<a id="a34e7964aa899176244e03cb7b1fc5985ab47b45386702914e9f362ae41e53c850"></a></td>
<td class="doxyEnumItemDescription"> (= ISD::BUILTIN_OP_END)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BL<a id="a34e7964aa899176244e03cb7b1fc5985adba71479b3d85460f040da54d76bd319"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PCRelativeWrapper<a id="a34e7964aa899176244e03cb7b1fc5985a064d387ad671dc9febb3606af201b284"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPRelativeWrapper<a id="a34e7964aa899176244e03cb7b1fc5985a600bb16cd5b3bce7880b112db5f2281b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CPRelativeWrapper<a id="a34e7964aa899176244e03cb7b1fc5985ab652887aa45d664a05d8783b1d6a8899"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LDWSP<a id="a34e7964aa899176244e03cb7b1fc5985afdbb5096b83ea5b8c045d746893e5fba"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STWSP<a id="a34e7964aa899176244e03cb7b1fc5985a5166f934fd43404e8042c1c395146e67"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RETSP<a id="a34e7964aa899176244e03cb7b1fc5985a14111134be2528cea05a13485b1df354"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LADD<a id="a34e7964aa899176244e03cb7b1fc5985a648c09af7617f04ce222bc70fb7f88e3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LSUB<a id="a34e7964aa899176244e03cb7b1fc5985a5c8b4055734ba0678315de2f20d0c5ba"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LMUL<a id="a34e7964aa899176244e03cb7b1fc5985a5f16d1c5f09829a27d169eeda4d60a5f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MACCU<a id="a34e7964aa899176244e03cb7b1fc5985ad197e99fb70e216ac886cf13252f0359"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MACCS<a id="a34e7964aa899176244e03cb7b1fc5985a608a7298a93e2c2a30f636c1b2736800"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CRC8<a id="a34e7964aa899176244e03cb7b1fc5985a9ff212f229aa7157bdbdb9de3ce5f1b1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BR_JT<a id="a34e7964aa899176244e03cb7b1fc5985a94fbede2594ef25aa1e60639e18bf630"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BR_JT32<a id="a34e7964aa899176244e03cb7b1fc5985a6b16706166ed5e9a0d9dff292f4c0c3a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FRAME_TO_ARGS_OFFSET<a id="a34e7964aa899176244e03cb7b1fc5985a28b88acb09d6fb90465c65b920418a86"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EH_RETURN<a id="a34e7964aa899176244e03cb7b1fc5985a6bf8b999c017694fbb550294905d45a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreisellowering-h">XCoreISelLowering.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreisellowering-h">XCoreISelLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
