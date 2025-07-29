---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/codeview/onemethodrecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `OneMethodRecord` Class



## Declaration

<div class="doxyDeclaration">
class llvm::codeview::OneMethodRecord { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">llvm/DebugInfo/CodeView/TypeRecord.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typerecord">TypeRecord</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abff58080136c5a27984df99c287b0288">OneMethodRecord</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cb3e782702c95a35151a094e30228ac">OneMethodRecord</a> (TypeRecordKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae06373edc09f5ebb1d0f3af50cf07cde">OneMethodRecord</a> (TypeIndex Type, MemberAttributes Attrs, int32_t VFTableOffset, StringRef Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad88a5f32b30f32f997ecb970ba78447b">OneMethodRecord</a> (TypeIndex Type, MemberAccess Access, MethodKind MK, MethodOptions Options, int32_t VFTableOffset, StringRef Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41620ed344dcf14ecf5e645376ba5c32">getType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a168a6021abac4aa4ac613129e7fc38c7">MethodKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5995cb258a5e2e48cbd88eb9d55c248">getMethodKind</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a728fe3ed02de6938b9ae302f54d8626f">MethodOptions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4912ea70026c956728a2d2730bda6e9">getOptions</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a86888a0082bafa16b982170695ebb881">MemberAccess</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99cb8d9d0bb2afa112ef8d4239eb2f1e">getAccess</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fe5da86460c13bb2dce221d7abaf065">getVFTableOffset</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad90ae94cd1ece9ed03e400d768d001f9">getName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66952c25fab42f836c97333715a36239">isIntroducingVirtual</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a353d4483ddd2413bb0278ab13823f40b">Type</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/codeview/memberattributes">MemberAttributes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae64e42551b20dd850923628e968c61b2">Attrs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad90a90b166c420395bedf48b1ad24cea">VFTableOffset</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a442a2d9e12e944cb483f3a6435b84cb0">Name</a></td>
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


<p>Definition at line 719 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### OneMethodRecord() {#abff58080136c5a27984df99c287b0288}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::codeview::OneMethodRecord::OneMethodRecord ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 721 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>

</div>
</div>

### OneMethodRecord() {#a9cb3e782702c95a35151a094e30228ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::codeview::OneMethodRecord::OneMethodRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#abf3db0193e50769bab633545f88c383a">TypeRecordKind</a> Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 722 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codeview/typerecord/#a714d9d1981216f2af467fc81f53b8790">llvm::codeview::TypeRecord::Kind</a> and <a href="/web-llvm/docs/api/classes/llvm/codeview/typerecord/#a4259276eb9e9ab247c88103b93a20b5d">llvm::codeview::TypeRecord::TypeRecord</a>.</p>

</div>
</div>

### OneMethodRecord() {#ae06373edc09f5ebb1d0f3af50cf07cde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::codeview::OneMethodRecord::OneMethodRecord (<a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> Type, <a href="/web-llvm/docs/api/structs/llvm/codeview/memberattributes">MemberAttributes</a> Attrs, int32_t VFTableOffset, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 723 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>References <a href="#ae64e42551b20dd850923628e968c61b2">Attrs</a>, <a href="#a442a2d9e12e944cb483f3a6435b84cb0">Name</a>, <a href="#a353d4483ddd2413bb0278ab13823f40b">Type</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typerecord/#a4259276eb9e9ab247c88103b93a20b5d">llvm::codeview::TypeRecord::TypeRecord</a> and <a href="#ad90a90b166c420395bedf48b1ad24cea">VFTableOffset</a>.</p>

</div>
</div>

### OneMethodRecord() {#ad88a5f32b30f32f997ecb970ba78447b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::codeview::OneMethodRecord::OneMethodRecord (<a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> Type, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a86888a0082bafa16b982170695ebb881">MemberAccess</a> Access, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a168a6021abac4aa4ac613129e7fc38c7">MethodKind</a> MK, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a728fe3ed02de6938b9ae302f54d8626f">MethodOptions</a> Options, int32_t VFTableOffset, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 727 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#adb4fa2b9065093d32736f78ea43a8c8a">Access</a>, <a href="#ae64e42551b20dd850923628e968c61b2">Attrs</a>, <a href="#a442a2d9e12e944cb483f3a6435b84cb0">Name</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>, <a href="#a353d4483ddd2413bb0278ab13823f40b">Type</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typerecord/#a4259276eb9e9ab247c88103b93a20b5d">llvm::codeview::TypeRecord::TypeRecord</a> and <a href="#ad90a90b166c420395bedf48b1ad24cea">VFTableOffset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAccess() {#a99cb8d9d0bb2afa112ef8d4239eb2f1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemberAccess llvm::codeview::OneMethodRecord::getAccess ()</td>
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



<p>Definition at line 735 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>Reference <a href="#ae64e42551b20dd850923628e968c61b2">Attrs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-typerecordmapping-cpp-/maponemethodrecord/#a8512de7a16f0f4a4b44a94bd615e1c31">anonymous{TypeRecordMapping.cpp}::MapOneMethodRecord::operator()</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a9efe423cacffbe87239e1e0f556d6d86">llvm::logicalview::LVLogicalVisitor::visitKnownMember</a>.</p>

</div>
</div>

### getMethodKind() {#ac5995cb258a5e2e48cbd88eb9d55c248}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MethodKind llvm::codeview::OneMethodRecord::getMethodKind ()</td>
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



<p>Definition at line 733 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>Reference <a href="#ae64e42551b20dd850923628e968c61b2">Attrs</a>.</p>


<p>Referenced by <a href="#a66952c25fab42f836c97333715a36239">isIntroducingVirtual</a>, <a href="/web-llvm/docs/api/structs/anonymous-typerecordmapping-cpp-/maponemethodrecord/#a8512de7a16f0f4a4b44a94bd615e1c31">anonymous{TypeRecordMapping.cpp}::MapOneMethodRecord::operator()</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a9efe423cacffbe87239e1e0f556d6d86">llvm::logicalview::LVLogicalVisitor::visitKnownMember</a>.</p>

</div>
</div>

### getName() {#ad90ae94cd1ece9ed03e400d768d001f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::codeview::OneMethodRecord::getName ()</td>
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



<p>Definition at line 737 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>Reference <a href="#a442a2d9e12e944cb483f3a6435b84cb0">Name</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a9efe423cacffbe87239e1e0f556d6d86">llvm::logicalview::LVLogicalVisitor::visitKnownMember</a>.</p>

</div>
</div>

### getOptions() {#ac4912ea70026c956728a2d2730bda6e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MethodOptions llvm::codeview::OneMethodRecord::getOptions ()</td>
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



<p>Definition at line 734 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>Reference <a href="#ae64e42551b20dd850923628e968c61b2">Attrs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-typerecordmapping-cpp-/maponemethodrecord/#a8512de7a16f0f4a4b44a94bd615e1c31">anonymous{TypeRecordMapping.cpp}::MapOneMethodRecord::operator()</a>.</p>

</div>
</div>

### getType() {#a41620ed344dcf14ecf5e645376ba5c32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeIndex llvm::codeview::OneMethodRecord::getType ()</td>
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



<p>Definition at line 732 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>Reference <a href="#a353d4483ddd2413bb0278ab13823f40b">Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a9efe423cacffbe87239e1e0f556d6d86">llvm::logicalview::LVLogicalVisitor::visitKnownMember</a>.</p>

</div>
</div>

### getVFTableOffset() {#a0fe5da86460c13bb2dce221d7abaf065}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t llvm::codeview::OneMethodRecord::getVFTableOffset ()</td>
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



<p>Definition at line 736 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>Reference <a href="#ad90a90b166c420395bedf48b1ad24cea">VFTableOffset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a9efe423cacffbe87239e1e0f556d6d86">llvm::logicalview::LVLogicalVisitor::visitKnownMember</a>.</p>

</div>
</div>

### isIntroducingVirtual() {#a66952c25fab42f836c97333715a36239}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codeview::OneMethodRecord::isIntroducingVirtual ()</td>
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



<p>Definition at line 739 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>References <a href="#ac5995cb258a5e2e48cbd88eb9d55c248">getMethodKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a168a6021abac4aa4ac613129e7fc38c7ab195ef30e97fd79fc09350e5528d0ede">llvm::codeview::IntroducingVirtual</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a168a6021abac4aa4ac613129e7fc38c7af60013c9b6ecfec449aeace857155e4c">llvm::codeview::PureIntroducingVirtual</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-typerecordmapping-cpp-/maponemethodrecord/#a8512de7a16f0f4a4b44a94bd615e1c31">anonymous{TypeRecordMapping.cpp}::MapOneMethodRecord::operator()</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a9efe423cacffbe87239e1e0f556d6d86">llvm::logicalview::LVLogicalVisitor::visitKnownMember</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Attrs {#ae64e42551b20dd850923628e968c61b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemberAttributes llvm::codeview::OneMethodRecord::Attrs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 745 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>Referenced by <a href="#a99cb8d9d0bb2afa112ef8d4239eb2f1e">getAccess</a>, <a href="#ac5995cb258a5e2e48cbd88eb9d55c248">getMethodKind</a>, <a href="#ac4912ea70026c956728a2d2730bda6e9">getOptions</a>, <a href="#ad88a5f32b30f32f997ecb970ba78447b">OneMethodRecord</a>, <a href="#ae06373edc09f5ebb1d0f3af50cf07cde">OneMethodRecord</a>, <a href="/web-llvm/docs/api/structs/anonymous-typerecordmapping-cpp-/maponemethodrecord/#a8512de7a16f0f4a4b44a94bd615e1c31">anonymous{TypeRecordMapping.cpp}::MapOneMethodRecord::operator()</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a9efe423cacffbe87239e1e0f556d6d86">llvm::logicalview::LVLogicalVisitor::visitKnownMember</a>.</p>

</div>
</div>

### Name {#a442a2d9e12e944cb483f3a6435b84cb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::codeview::OneMethodRecord::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 747 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>Referenced by <a href="#ad90ae94cd1ece9ed03e400d768d001f9">getName</a>, <a href="#ad88a5f32b30f32f997ecb970ba78447b">OneMethodRecord</a>, <a href="#ae06373edc09f5ebb1d0f3af50cf07cde">OneMethodRecord</a>, <a href="/web-llvm/docs/api/structs/anonymous-typerecordmapping-cpp-/maponemethodrecord/#a8512de7a16f0f4a4b44a94bd615e1c31">anonymous{TypeRecordMapping.cpp}::MapOneMethodRecord::operator()</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#ac28d415acf28987bc11560889b9e76b1">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>.</p>

</div>
</div>

### Type {#a353d4483ddd2413bb0278ab13823f40b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeIndex llvm::codeview::OneMethodRecord::Type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 744 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>Referenced by <a href="#a41620ed344dcf14ecf5e645376ba5c32">getType</a>, <a href="#ad88a5f32b30f32f997ecb970ba78447b">OneMethodRecord</a>, <a href="#ae06373edc09f5ebb1d0f3af50cf07cde">OneMethodRecord</a> and <a href="/web-llvm/docs/api/structs/anonymous-typerecordmapping-cpp-/maponemethodrecord/#a8512de7a16f0f4a4b44a94bd615e1c31">anonymous{TypeRecordMapping.cpp}::MapOneMethodRecord::operator()</a>.</p>

</div>
</div>

### VFTableOffset {#ad90a90b166c420395bedf48b1ad24cea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t llvm::codeview::OneMethodRecord::VFTableOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 746 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>Referenced by <a href="#a0fe5da86460c13bb2dce221d7abaf065">getVFTableOffset</a>, <a href="#ad88a5f32b30f32f997ecb970ba78447b">OneMethodRecord</a>, <a href="#ae06373edc09f5ebb1d0f3af50cf07cde">OneMethodRecord</a> and <a href="/web-llvm/docs/api/structs/anonymous-typerecordmapping-cpp-/maponemethodrecord/#a8512de7a16f0f4a4b44a94bd615e1c31">anonymous{TypeRecordMapping.cpp}::MapOneMethodRecord::operator()</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
