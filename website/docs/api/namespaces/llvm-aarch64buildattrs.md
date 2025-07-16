---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/aarch64buildattrs
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `AArch64BuildAttrs` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::AArch64BuildAttrs { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">VendorID : unsigned { <a href="#ad2f2d095653918c60172f948524442a0">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> build attributes vendors IDs (a.k.a subsection name) <a href="#ad2f2d095653918c60172f948524442a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">SubsectionOptional : unsigned { <a href="#aed8b1a71c71c0448f7abc8a6ee32c95c">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">SubsectionType : unsigned { <a href="#ad81567845cc9fba4339ba1a69712f211">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">PauthABITags : unsigned { <a href="#ac35783f29186ae9f470ec2969c9cb952">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">FeatureAndBitsTags : unsigned { <a href="#a898116664a716f1ccf6c58afc7718863">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">FeatureAndBitsFlag : unsigned { <a href="#a02cbf821981385925f75eba32badbe8e">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26559a9763f5d95c22f17698ec2c8c06">getVendorName</a> (unsigned const Vendor)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad2f2d095653918c60172f948524442a0">VendorID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad766d3db5e5dbd0ab264d5b85814fbf7">getVendorID</a> (StringRef const Vendor)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87b8d785c73057cd4875629af50a29eb">getOptionalStr</a> (unsigned Optional)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aed8b1a71c71c0448f7abc8a6ee32c95c">SubsectionOptional</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1552d70a70e16a1b000424999a0ba957">getOptionalID</a> (StringRef Optional)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2535e04d77be56cc14953ac1f7feff1">getSubsectionOptionalUnknownError</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada0cf263c4a3d8d60d8b72035000f62b">getTypeStr</a> (unsigned Type)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad81567845cc9fba4339ba1a69712f211">SubsectionType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afec13a4bcd08acad2ef55c7c35fc4878">getTypeID</a> (StringRef Type)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8d246c271c3898f3d15e8154af67399">getSubsectionTypeUnknownError</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d9dd1125a78dedbde2f8c4d62a36acb">getPauthABITagsStr</a> (unsigned PauthABITag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac35783f29186ae9f470ec2969c9cb952">PauthABITags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae26d0ec0ccb5ee8ea72e0f296ea75a3">getPauthABITagsID</a> (StringRef PauthABITag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0653bcbdb0a613f9386d3a52909f7d3e">getFeatureAndBitsTagsStr</a> (unsigned FeatureAndBitsTag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a898116664a716f1ccf6c58afc7718863">FeatureAndBitsTags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74a62fe438b3f361417141dd25db3199">getFeatureAndBitsTagsID</a> (StringRef FeatureAndBitsTag)</td>
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

### FeatureAndBitsFlag {#a02cbf821981385925f75eba32badbe8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AArch64BuildAttrs::FeatureAndBitsFlag : unsigned</td>
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
<td class="doxyEnumItemName">Feature_BTI_Flag<a id="a02cbf821981385925f75eba32badbe8eab816b190d63b3b96519a82af9b9a125f"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Feature_PAC_Flag<a id="a02cbf821981385925f75eba32badbe8ea34cd5242b7d08fc2fbab8c9198e5548a"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Feature_GCS_Flag<a id="a02cbf821981385925f75eba32badbe8ea58cb58cf47368adad995c77f76dd6e92"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 2)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/aarch64buildattributes-h">AArch64BuildAttributes.h</a>.</p>

</div>
</div>

### FeatureAndBitsTags {#a898116664a716f1ccf6c58afc7718863}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AArch64BuildAttrs::FeatureAndBitsTags : unsigned</td>
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
<td class="doxyEnumItemName">TAG_FEATURE_BTI<a id="a898116664a716f1ccf6c58afc7718863a18ca061e3f2810477c52f9de8801f975"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TAG_FEATURE_PAC<a id="a898116664a716f1ccf6c58afc7718863a0ce80b04d6976789fedea754ab2061bc"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TAG_FEATURE_GCS<a id="a898116664a716f1ccf6c58afc7718863aa310972cb7b9330a266fbde0acaca074"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FEATURE_AND_BITS_TAG_NOT_FOUND<a id="a898116664a716f1ccf6c58afc7718863a9b33eaf2e3dfeb2b8965cae195a5a474"></a></td>
<td class="doxyEnumItemDescription"> (= 404)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/aarch64buildattributes-h">AArch64BuildAttributes.h</a>.</p>

</div>
</div>

### PauthABITags {#ac35783f29186ae9f470ec2969c9cb952}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AArch64BuildAttrs::PauthABITags : unsigned</td>
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
<td class="doxyEnumItemName">TAG_PAUTH_PLATFORM<a id="ac35783f29186ae9f470ec2969c9cb952a293cacaac39b4f7083fd3a9ddea61791"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TAG_PAUTH_SCHEMA<a id="ac35783f29186ae9f470ec2969c9cb952a399da32a3e92753a305b2bbe05dc77af"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PAUTHABI_TAG_NOT_FOUND<a id="ac35783f29186ae9f470ec2969c9cb952af3d63b0bfc1de14726c72dd6501dbf55"></a></td>
<td class="doxyEnumItemDescription"> (= 404)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/aarch64buildattributes-h">AArch64BuildAttributes.h</a>.</p>

</div>
</div>

### SubsectionOptional {#aed8b1a71c71c0448f7abc8a6ee32c95c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AArch64BuildAttrs::SubsectionOptional : unsigned</td>
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
<td class="doxyEnumItemName">REQUIRED<a id="aed8b1a71c71c0448f7abc8a6ee32c95ca1be39cb5280290892398ab312e199b8a"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPTIONAL<a id="aed8b1a71c71c0448f7abc8a6ee32c95ca177d5447cb7a2b6e6c8b13397fdecab0"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPTIONAL_NOT_FOUND<a id="aed8b1a71c71c0448f7abc8a6ee32c95ca18da5995f5c05300400d579821fd6c0e"></a></td>
<td class="doxyEnumItemDescription"> (= 404)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/aarch64buildattributes-h">AArch64BuildAttributes.h</a>.</p>

</div>
</div>

### SubsectionType {#ad81567845cc9fba4339ba1a69712f211}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AArch64BuildAttrs::SubsectionType : unsigned</td>
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
<td class="doxyEnumItemName">ULEB128<a id="ad81567845cc9fba4339ba1a69712f211a8032b483a40e2c705a7e6cafecf8c1a7"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NTBS<a id="ad81567845cc9fba4339ba1a69712f211aabd6b9a714ef361392b5fbafdec24656"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_NOT_FOUND<a id="ad81567845cc9fba4339ba1a69712f211a757bdab328b651b0830c6a49a50a550a"></a></td>
<td class="doxyEnumItemDescription"> (= 404)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/aarch64buildattributes-h">AArch64BuildAttributes.h</a>.</p>

</div>
</div>

### VendorID {#ad2f2d095653918c60172f948524442a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AArch64BuildAttrs::VendorID : unsigned</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> build attributes vendors IDs (a.k.a subsection name)</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AEABI_FEATURE_AND_BITS<a id="ad2f2d095653918c60172f948524442a0a8040351a645af569f250de2e02b541d4"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AEABI_PAUTHABI<a id="ad2f2d095653918c60172f948524442a0a1d86e09f81241e3af64dbee7469869e0"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VENDOR_UNKNOWN<a id="ad2f2d095653918c60172f948524442a0aa269fdc647bd0b35b3499399b62693f0"></a></td>
<td class="doxyEnumItemDescription"> (= 404)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/aarch64buildattributes-h">AArch64BuildAttributes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### getFeatureAndBitsTagsID() {#a74a62fe438b3f361417141dd25db3199}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FeatureAndBitsTags llvm::AArch64BuildAttrs::getFeatureAndBitsTagsID (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FeatureAndBitsTag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/aarch64buildattributes-h">AArch64BuildAttributes.h</a>, definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/support/aarch64buildattributes-cpp">AArch64BuildAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="#a898116664a716f1ccf6c58afc7718863a9b33eaf2e3dfeb2b8965cae195a5a474">FEATURE_AND_BITS_TAG_NOT_FOUND</a>, <a href="#a898116664a716f1ccf6c58afc7718863a18ca061e3f2810477c52f9de8801f975">TAG_FEATURE_BTI</a>, <a href="#a898116664a716f1ccf6c58afc7718863aa310972cb7b9330a266fbde0acaca074">TAG_FEATURE_GCS</a> and <a href="#a898116664a716f1ccf6c58afc7718863a0ce80b04d6976789fedea754ab2061bc">TAG_FEATURE_PAC</a>.</p>

</div>
</div>

### getFeatureAndBitsTagsStr() {#a0653bcbdb0a613f9386d3a52909f7d3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::AArch64BuildAttrs::getFeatureAndBitsTagsStr (unsigned FeatureAndBitsTag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/aarch64buildattributes-h">AArch64BuildAttributes.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/support/aarch64buildattributes-cpp">AArch64BuildAttributes.cpp</a>.</p>


<p>References <a href="#a898116664a716f1ccf6c58afc7718863a9b33eaf2e3dfeb2b8965cae195a5a474">FEATURE_AND_BITS_TAG_NOT_FOUND</a>, <a href="#a898116664a716f1ccf6c58afc7718863a18ca061e3f2810477c52f9de8801f975">TAG_FEATURE_BTI</a>, <a href="#a898116664a716f1ccf6c58afc7718863aa310972cb7b9330a266fbde0acaca074">TAG_FEATURE_GCS</a> and <a href="#a898116664a716f1ccf6c58afc7718863a0ce80b04d6976789fedea754ab2061bc">TAG_FEATURE_PAC</a>.</p>

</div>
</div>

### getOptionalID() {#a1552d70a70e16a1b000424999a0ba957}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SubsectionOptional llvm::AArch64BuildAttrs::getOptionalID (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Optional)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/aarch64buildattributes-h">AArch64BuildAttributes.h</a>, definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/support/aarch64buildattributes-cpp">AArch64BuildAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="#aed8b1a71c71c0448f7abc8a6ee32c95ca177d5447cb7a2b6e6c8b13397fdecab0">OPTIONAL</a>, <a href="#aed8b1a71c71c0448f7abc8a6ee32c95ca18da5995f5c05300400d579821fd6c0e">OPTIONAL_NOT_FOUND</a> and <a href="#aed8b1a71c71c0448f7abc8a6ee32c95ca1be39cb5280290892398ab312e199b8a">REQUIRED</a>.</p>

</div>
</div>

### getOptionalStr() {#a87b8d785c73057cd4875629af50a29eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::AArch64BuildAttrs::getOptionalStr (unsigned Optional)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/aarch64buildattributes-h">AArch64BuildAttributes.h</a>, definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/support/aarch64buildattributes-cpp">AArch64BuildAttributes.cpp</a>.</p>


<p>References <a href="#aed8b1a71c71c0448f7abc8a6ee32c95ca177d5447cb7a2b6e6c8b13397fdecab0">OPTIONAL</a>, <a href="#aed8b1a71c71c0448f7abc8a6ee32c95ca18da5995f5c05300400d579821fd6c0e">OPTIONAL_NOT_FOUND</a> and <a href="#aed8b1a71c71c0448f7abc8a6ee32c95ca1be39cb5280290892398ab312e199b8a">REQUIRED</a>.</p>

</div>
</div>

### getPauthABITagsID() {#aae26d0ec0ccb5ee8ea72e0f296ea75a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PauthABITags llvm::AArch64BuildAttrs::getPauthABITagsID (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PauthABITag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/aarch64buildattributes-h">AArch64BuildAttributes.h</a>, definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/support/aarch64buildattributes-cpp">AArch64BuildAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="#ac35783f29186ae9f470ec2969c9cb952af3d63b0bfc1de14726c72dd6501dbf55">PAUTHABI_TAG_NOT_FOUND</a>, <a href="#ac35783f29186ae9f470ec2969c9cb952a293cacaac39b4f7083fd3a9ddea61791">TAG_PAUTH_PLATFORM</a> and <a href="#ac35783f29186ae9f470ec2969c9cb952a399da32a3e92753a305b2bbe05dc77af">TAG_PAUTH_SCHEMA</a>.</p>

</div>
</div>

### getPauthABITagsStr() {#a2d9dd1125a78dedbde2f8c4d62a36acb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::AArch64BuildAttrs::getPauthABITagsStr (unsigned PauthABITag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/aarch64buildattributes-h">AArch64BuildAttributes.h</a>, definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/support/aarch64buildattributes-cpp">AArch64BuildAttributes.cpp</a>.</p>


<p>References <a href="#ac35783f29186ae9f470ec2969c9cb952af3d63b0bfc1de14726c72dd6501dbf55">PAUTHABI_TAG_NOT_FOUND</a>, <a href="#ac35783f29186ae9f470ec2969c9cb952a293cacaac39b4f7083fd3a9ddea61791">TAG_PAUTH_PLATFORM</a> and <a href="#ac35783f29186ae9f470ec2969c9cb952a399da32a3e92753a305b2bbe05dc77af">TAG_PAUTH_SCHEMA</a>.</p>

</div>
</div>

### getSubsectionOptionalUnknownError() {#ac2535e04d77be56cc14953ac1f7feff1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::AArch64BuildAttrs::getSubsectionOptionalUnknownError ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/aarch64buildattributes-h">AArch64BuildAttributes.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/support/aarch64buildattributes-cpp">AArch64BuildAttributes.cpp</a>.</p>

</div>
</div>

### getSubsectionTypeUnknownError() {#ae8d246c271c3898f3d15e8154af67399}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::AArch64BuildAttrs::getSubsectionTypeUnknownError ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/aarch64buildattributes-h">AArch64BuildAttributes.h</a>, definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/support/aarch64buildattributes-cpp">AArch64BuildAttributes.cpp</a>.</p>

</div>
</div>

### getTypeID() {#afec13a4bcd08acad2ef55c7c35fc4878}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SubsectionType llvm::AArch64BuildAttrs::getTypeID (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/aarch64buildattributes-h">AArch64BuildAttributes.h</a>, definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/support/aarch64buildattributes-cpp">AArch64BuildAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#aa13f802513b39e1e2a7650011e5651d7">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="#ad81567845cc9fba4339ba1a69712f211aabd6b9a714ef361392b5fbafdec24656">NTBS</a>, <a href="#ad81567845cc9fba4339ba1a69712f211a757bdab328b651b0830c6a49a50a550a">TYPE_NOT_FOUND</a> and <a href="#ad81567845cc9fba4339ba1a69712f211a8032b483a40e2c705a7e6cafecf8c1a7">ULEB128</a>.</p>

</div>
</div>

### getTypeStr() {#ada0cf263c4a3d8d60d8b72035000f62b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::AArch64BuildAttrs::getTypeStr (unsigned Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/aarch64buildattributes-h">AArch64BuildAttributes.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/support/aarch64buildattributes-cpp">AArch64BuildAttributes.cpp</a>.</p>


<p>References <a href="#ad81567845cc9fba4339ba1a69712f211aabd6b9a714ef361392b5fbafdec24656">NTBS</a>, <a href="#ad81567845cc9fba4339ba1a69712f211a757bdab328b651b0830c6a49a50a550a">TYPE_NOT_FOUND</a> and <a href="#ad81567845cc9fba4339ba1a69712f211a8032b483a40e2c705a7e6cafecf8c1a7">ULEB128</a>.</p>

</div>
</div>

### getVendorID() {#ad766d3db5e5dbd0ab264d5b85814fbf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VendorID llvm::AArch64BuildAttrs::getVendorID (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Vendor)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/aarch64buildattributes-h">AArch64BuildAttributes.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/support/aarch64buildattributes-cpp">AArch64BuildAttributes.cpp</a>.</p>


<p>References <a href="#ad2f2d095653918c60172f948524442a0a8040351a645af569f250de2e02b541d4">AEABI_FEATURE_AND_BITS</a>, <a href="#ad2f2d095653918c60172f948524442a0a1d86e09f81241e3af64dbee7469869e0">AEABI_PAUTHABI</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a> and <a href="#ad2f2d095653918c60172f948524442a0aa269fdc647bd0b35b3499399b62693f0">VENDOR_UNKNOWN</a>.</p>

</div>
</div>

### getVendorName() {#a26559a9763f5d95c22f17698ec2c8c06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::AArch64BuildAttrs::getVendorName (unsigned <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Vendor)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/aarch64buildattributes-h">AArch64BuildAttributes.h</a>, definition at line 15 of file <a href="/web-llvm/docs/api/files/lib/lib/support/aarch64buildattributes-cpp">AArch64BuildAttributes.cpp</a>.</p>


<p>References <a href="#ad2f2d095653918c60172f948524442a0a8040351a645af569f250de2e02b541d4">AEABI_FEATURE_AND_BITS</a>, <a href="#ad2f2d095653918c60172f948524442a0a1d86e09f81241e3af64dbee7469869e0">AEABI_PAUTHABI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ad2f2d095653918c60172f948524442a0aa269fdc647bd0b35b3499399b62693f0">VENDOR_UNKNOWN</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a9f2d85b2edc88b7eef2b10f54506ed77">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::emitAttributes</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/aarch64buildattributes-h">AArch64BuildAttributes.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/aarch64buildattributes-cpp">AArch64BuildAttributes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
