---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gcnusersgprusageinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GCNUserSGPRUsageInfo` Class



## Declaration

<div class="doxyDeclaration">
class llvm::GCNUserSGPRUsageInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">Target/AMDGPU/GCNSubtarget.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">UserSGPRID : unsigned { <a href="#a4fea12adb46cf8fc647c6e3a2a473467">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefc8f0b6a7216b0b236399cd3235471c">GCNUserSGPRUsageInfo</a> (const Function &amp;F, const GCNSubtarget &amp;ST)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a943f2258186cb3bd41d1f7811f7c42e2">hasImplicitBufferPtr</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a653036239bdfb1fdfbeea8dc682ccf33">hasPrivateSegmentBuffer</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad412b3a7ec02a4570a432c61893b825e">hasDispatchPtr</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18d715c9639346fd0894c867309cdea6">hasQueuePtr</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b002bef17a1750dad84568c253872a4">hasKernargSegmentPtr</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4557feb6ad664501fa2697164259963e">hasDispatchID</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af46f82034f9728539337d5c45e668642">hasFlatScratchInit</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3d8257393542792d4fb8644519f2f59">hasPrivateSegmentSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9463ec44e112fddbadd933843f46d1ee">getNumKernargPreloadSGPRs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1a555a6b9f16a61953f426298c814d7">getNumUsedUserSGPRs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cb6ff5b4d97ee4b7d8a03c3cd11d644">getNumFreeUserSGPRs</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28c5f19d7b897a0141bbc82d3d598825">allocKernargPreloadSGPRs</a> (unsigned NumSGPRs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14d20597726c8938dd70ded55f9344bd">ST</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e74c55683afb4089184175fd9494d13">ImplicitBufferPtr</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b6bbe03ead3de15a88d193054b5ea44">PrivateSegmentBuffer</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabe72ef90376744cda2850bf0f965ec9">DispatchPtr</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b4418ab055bc4d07672d1cad227ef6c">QueuePtr</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9787fc71036b080a4070349ab7ede4f7">KernargSegmentPtr</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e06fce88e99d8d4ee6aed81e73134d7">DispatchID</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8ae08715d1f8639a893d268d539b404">FlatScratchInit</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69b3195a9fd2c354f164954c9e31308e">PrivateSegmentSize</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3ce488bce3066ba6ae6c6cca26878e4">NumKernargPreloadSGPRs</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3d5dccddb0f19a0ecace7bc07f87a75">NumUsedUserSGPRs</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bb1f4b2f5fc9a8c2d46203805fdf696">getNumUserSGPRForField</a> (UserSGPRID ID)</td>
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


<p>Definition at line 1660 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### UserSGPRID {#a4fea12adb46cf8fc647c6e3a2a473467}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::GCNUserSGPRUsageInfo::UserSGPRID : unsigned</td>
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
<td class="doxyEnumItemName">ImplicitBufferPtrID<a id="a4fea12adb46cf8fc647c6e3a2a473467a50b339bf4fc352f5dacb4133cddd13e8"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PrivateSegmentBufferID<a id="a4fea12adb46cf8fc647c6e3a2a473467a842e64b828b6bcaa7917538e758524fa"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DispatchPtrID<a id="a4fea12adb46cf8fc647c6e3a2a473467a7cb9375ced6c5f6b4d1f67dd8b0c3774"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">QueuePtrID<a id="a4fea12adb46cf8fc647c6e3a2a473467a6d3e9448f5322fb4143ce26e847b46da"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">KernargSegmentPtrID<a id="a4fea12adb46cf8fc647c6e3a2a473467adaeda53c484fb01e239186610cddc35c"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DispatchIdID<a id="a4fea12adb46cf8fc647c6e3a2a473467a62016ea34379a5c44fee9904c42b0058"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FlatScratchInitID<a id="a4fea12adb46cf8fc647c6e3a2a473467a7fb4dbb782406e2d50accf79fb8a85ff"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PrivateSegmentSizeID<a id="a4fea12adb46cf8fc647c6e3a2a473467a848266ed3655b3fafe161ca68485ec64"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1686 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### GCNUserSGPRUsageInfo() {#aefc8f0b6a7216b0b236399cd3235471c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNUserSGPRUsageInfo::GCNUserSGPRUsageInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; ST)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1720 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>, definition at line 599 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp">GCNSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca27a385675142c462571165c839e41aa0">llvm::CallingConv::AMDGPU_KERNEL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="#a4fea12adb46cf8fc647c6e3a2a473467a62016ea34379a5c44fee9904c42b0058">DispatchIdID</a>, <a href="#a4fea12adb46cf8fc647c6e3a2a473467a7cb9375ced6c5f6b4d1f67dd8b0c3774">DispatchPtrID</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a4fea12adb46cf8fc647c6e3a2a473467a7fb4dbb782406e2d50accf79fb8a85ff">FlatScratchInitID</a>, <a href="#a0bb1f4b2f5fc9a8c2d46203805fdf696">getNumUserSGPRForField</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ab0b0a572164f8fccd5474cb6babed129a4f2a846b62b36aa105ec3ddfd151a482">HasCalls</a>, <a href="#a4557feb6ad664501fa2697164259963e">hasDispatchID</a>, <a href="#ad412b3a7ec02a4570a432c61893b825e">hasDispatchPtr</a>, <a href="#af46f82034f9728539337d5c45e668642">hasFlatScratchInit</a>, <a href="#a943f2258186cb3bd41d1f7811f7c42e2">hasImplicitBufferPtr</a>, <a href="#a1b002bef17a1750dad84568c253872a4">hasKernargSegmentPtr</a>, <a href="#a653036239bdfb1fdfbeea8dc682ccf33">hasPrivateSegmentBuffer</a>, <a href="#aa3d8257393542792d4fb8644519f2f59">hasPrivateSegmentSize</a>, <a href="#a18d715c9639346fd0894c867309cdea6">hasQueuePtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a>, <a href="#a4fea12adb46cf8fc647c6e3a2a473467a50b339bf4fc352f5dacb4133cddd13e8">ImplicitBufferPtrID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a3c65c76a817d60e322ff750366674a92">llvm::AMDGPU::isEntryFunctionCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af9f05d3701d61f10054f263eec92da45">llvm::AMDGPU::isGraphics</a>, <a href="#a4fea12adb46cf8fc647c6e3a2a473467adaeda53c484fb01e239186610cddc35c">KernargSegmentPtrID</a>, <a href="#a4fea12adb46cf8fc647c6e3a2a473467a842e64b828b6bcaa7917538e758524fa">PrivateSegmentBufferID</a>, <a href="#a4fea12adb46cf8fc647c6e3a2a473467a848266ed3655b3fafe161ca68485ec64">PrivateSegmentSizeID</a>, <a href="#a4fea12adb46cf8fc647c6e3a2a473467a6d3e9448f5322fb4143ce26e847b46da">QueuePtrID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca9b5e79699935bf721647d44339701860">llvm::CallingConv::SPIR_KERNEL</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### allocKernargPreloadSGPRs() {#a28c5f19d7b897a0141bbc82d3d598825}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNUserSGPRUsageInfo::allocKernargPreloadSGPRs (unsigned NumSGPRs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1684 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>, definition at line 668 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp">GCNSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a2b981a267feb0c817f91ab394b62699a">llvm::AMDGPU::getMaxNumUserSGPRs</a>.</p>

</div>
</div>

### getNumFreeUserSGPRs() {#a8cb6ff5b4d97ee4b7d8a03c3cd11d644}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GCNUserSGPRUsageInfo::getNumFreeUserSGPRs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1682 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>, definition at line 674 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp">GCNSubtarget.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a2b981a267feb0c817f91ab394b62699a">llvm::AMDGPU::getMaxNumUserSGPRs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ade385868ff059bef6446f70208541043">llvm::SITargetLowering::allocatePreloadKernArgSGPRs</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerkernelarguments-cpp-/preloadkernelarginfo/#a49308385cf90a25d63f1879307c7daa8">anonymous{AMDGPULowerKernelArguments.cpp}::PreloadKernelArgInfo::setInitialFreeUserSGPRsCount</a>.</p>

</div>
</div>

### getNumKernargPreloadSGPRs() {#a9463ec44e112fddbadd933843f46d1ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNUserSGPRUsageInfo::getNumKernargPreloadSGPRs ()</td>
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



<p>Definition at line 1678 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### getNumUsedUserSGPRs() {#ab1a555a6b9f16a61953f426298c814d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNUserSGPRUsageInfo::getNumUsedUserSGPRs ()</td>
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



<p>Definition at line 1680 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### hasDispatchID() {#a4557feb6ad664501fa2697164259963e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNUserSGPRUsageInfo::hasDispatchID ()</td>
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



<p>Definition at line 1672 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucalllowering-cpp/#a3986e436467855478f909c9b2226a066">allocateHSAUserSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a4678f677f6c3bd2a4c2d4b64549017d0">llvm::SITargetLowering::allocateHSAUserSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a3ef0dde77e91309be534394dc420d4a5">llvm::SITargetLowering::allocateSpecialInputSGPRs</a> and <a href="#aefc8f0b6a7216b0b236399cd3235471c">GCNUserSGPRUsageInfo</a>.</p>

</div>
</div>

### hasDispatchPtr() {#ad412b3a7ec02a4570a432c61893b825e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNUserSGPRUsageInfo::hasDispatchPtr ()</td>
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



<p>Definition at line 1666 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucalllowering-cpp/#a3986e436467855478f909c9b2226a066">allocateHSAUserSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a4678f677f6c3bd2a4c2d4b64549017d0">llvm::SITargetLowering::allocateHSAUserSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a3ef0dde77e91309be534394dc420d4a5">llvm::SITargetLowering::allocateSpecialInputSGPRs</a>, <a href="#aefc8f0b6a7216b0b236399cd3235471c">GCNUserSGPRUsageInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9854eddb8a07891be9aa4af0da56f198">llvm::SITargetLowering::LowerFormalArguments</a>.</p>

</div>
</div>

### hasFlatScratchInit() {#af46f82034f9728539337d5c45e668642}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNUserSGPRUsageInfo::hasFlatScratchInit ()</td>
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



<p>Definition at line 1674 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucalllowering-cpp/#a3986e436467855478f909c9b2226a066">allocateHSAUserSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a4678f677f6c3bd2a4c2d4b64549017d0">llvm::SITargetLowering::allocateHSAUserSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a702408ee868bae14b0de2b8a28c8058d">llvm::SIFrameLowering::emitEntryFunctionPrologue</a>, <a href="#aefc8f0b6a7216b0b236399cd3235471c">GCNUserSGPRUsageInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a988c4c0176e7554762642cd4f0fa1b8a">llvm::GCNSubtarget::getReservedNumSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9854eddb8a07891be9aa4af0da56f198">llvm::SITargetLowering::LowerFormalArguments</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#acf79ac9988d00b2ded8a68907a1569e4">llvm::AMDGPUCallLowering::lowerFormalArguments</a>.</p>

</div>
</div>

### hasImplicitBufferPtr() {#a943f2258186cb3bd41d1f7811f7c42e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNUserSGPRUsageInfo::hasImplicitBufferPtr ()</td>
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



<p>Definition at line 1662 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a4678f677f6c3bd2a4c2d4b64549017d0">llvm::SITargetLowering::allocateHSAUserSGPRs</a>, <a href="#aefc8f0b6a7216b0b236399cd3235471c">GCNUserSGPRUsageInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#acf79ac9988d00b2ded8a68907a1569e4">llvm::AMDGPUCallLowering::lowerFormalArguments</a>.</p>

</div>
</div>

### hasKernargSegmentPtr() {#a1b002bef17a1750dad84568c253872a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNUserSGPRUsageInfo::hasKernargSegmentPtr ()</td>
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



<p>Definition at line 1670 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucalllowering-cpp/#a3986e436467855478f909c9b2226a066">allocateHSAUserSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a4678f677f6c3bd2a4c2d4b64549017d0">llvm::SITargetLowering::allocateHSAUserSGPRs</a>, <a href="#aefc8f0b6a7216b0b236399cd3235471c">GCNUserSGPRUsageInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9854eddb8a07891be9aa4af0da56f198">llvm::SITargetLowering::LowerFormalArguments</a>.</p>

</div>
</div>

### hasPrivateSegmentBuffer() {#a653036239bdfb1fdfbeea8dc682ccf33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNUserSGPRUsageInfo::hasPrivateSegmentBuffer ()</td>
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



<p>Definition at line 1664 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucalllowering-cpp/#a3986e436467855478f909c9b2226a066">allocateHSAUserSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a4678f677f6c3bd2a4c2d4b64549017d0">llvm::SITargetLowering::allocateHSAUserSGPRs</a> and <a href="#aefc8f0b6a7216b0b236399cd3235471c">GCNUserSGPRUsageInfo</a>.</p>

</div>
</div>

### hasPrivateSegmentSize() {#aa3d8257393542792d4fb8644519f2f59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNUserSGPRUsageInfo::hasPrivateSegmentSize ()</td>
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



<p>Definition at line 1676 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a4678f677f6c3bd2a4c2d4b64549017d0">llvm::SITargetLowering::allocateHSAUserSGPRs</a> and <a href="#aefc8f0b6a7216b0b236399cd3235471c">GCNUserSGPRUsageInfo</a>.</p>

</div>
</div>

### hasQueuePtr() {#a18d715c9639346fd0894c867309cdea6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNUserSGPRUsageInfo::hasQueuePtr ()</td>
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



<p>Definition at line 1668 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucalllowering-cpp/#a3986e436467855478f909c9b2226a066">allocateHSAUserSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a4678f677f6c3bd2a4c2d4b64549017d0">llvm::SITargetLowering::allocateHSAUserSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a3ef0dde77e91309be534394dc420d4a5">llvm::SITargetLowering::allocateSpecialInputSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv5/#a00df0d04b86c6d3d0d027c912afb7282">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV5::emitHiddenKernelArgs</a> and <a href="#aefc8f0b6a7216b0b236399cd3235471c">GCNUserSGPRUsageInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DispatchID {#a2e06fce88e99d8d4ee6aed81e73134d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNUserSGPRUsageInfo::DispatchID = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1738 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### DispatchPtr {#aabe72ef90376744cda2850bf0f965ec9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNUserSGPRUsageInfo::DispatchPtr = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1732 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### FlatScratchInit {#ab8ae08715d1f8639a893d268d539b404}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNUserSGPRUsageInfo::FlatScratchInit = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1740 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### ImplicitBufferPtr {#a8e74c55683afb4089184175fd9494d13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNUserSGPRUsageInfo::ImplicitBufferPtr = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1728 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### KernargSegmentPtr {#a9787fc71036b080a4070349ab7ede4f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNUserSGPRUsageInfo::KernargSegmentPtr = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1736 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### NumKernargPreloadSGPRs {#aa3ce488bce3066ba6ae6c6cca26878e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNUserSGPRUsageInfo::NumKernargPreloadSGPRs = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1744 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### NumUsedUserSGPRs {#ac3d5dccddb0f19a0ecace7bc07f87a75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNUserSGPRUsageInfo::NumUsedUserSGPRs = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1746 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### PrivateSegmentBuffer {#a4b6bbe03ead3de15a88d193054b5ea44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNUserSGPRUsageInfo::PrivateSegmentBuffer = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1730 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### PrivateSegmentSize {#a69b3195a9fd2c354f164954c9e31308e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNUserSGPRUsageInfo::PrivateSegmentSize = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1742 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### QueuePtr {#a1b4418ab055bc4d07672d1cad227ef6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNUserSGPRUsageInfo::QueuePtr = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1734 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

### ST {#a14d20597726c8938dd70ded55f9344bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GCNSubtarget&amp; llvm::GCNUserSGPRUsageInfo::ST</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1723 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getNumUserSGPRForField() {#a0bb1f4b2f5fc9a8c2d46203805fdf696}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNUserSGPRUsageInfo::getNumUserSGPRForField (<a href="#a4fea12adb46cf8fc647c6e3a2a473467">UserSGPRID</a> ID)</td>
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



<p>Definition at line 1698 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>.</p>


<p>References <a href="#a4fea12adb46cf8fc647c6e3a2a473467a62016ea34379a5c44fee9904c42b0058">DispatchIdID</a>, <a href="#a4fea12adb46cf8fc647c6e3a2a473467a7cb9375ced6c5f6b4d1f67dd8b0c3774">DispatchPtrID</a>, <a href="#a4fea12adb46cf8fc647c6e3a2a473467a7fb4dbb782406e2d50accf79fb8a85ff">FlatScratchInitID</a>, <a href="#a4fea12adb46cf8fc647c6e3a2a473467a50b339bf4fc352f5dacb4133cddd13e8">ImplicitBufferPtrID</a>, <a href="#a4fea12adb46cf8fc647c6e3a2a473467adaeda53c484fb01e239186610cddc35c">KernargSegmentPtrID</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a4fea12adb46cf8fc647c6e3a2a473467a842e64b828b6bcaa7917538e758524fa">PrivateSegmentBufferID</a>, <a href="#a4fea12adb46cf8fc647c6e3a2a473467a848266ed3655b3fafe161ca68485ec64">PrivateSegmentSizeID</a> and <a href="#a4fea12adb46cf8fc647c6e3a2a473467a6d3e9448f5322fb4143ce26e847b46da">QueuePtrID</a>.</p>


<p>Referenced by <a href="#aefc8f0b6a7216b0b236399cd3235471c">GCNUserSGPRUsageInfo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-cpp">GCNSubtarget.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
