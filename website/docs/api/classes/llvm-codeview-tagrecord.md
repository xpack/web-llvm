---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/codeview/tagrecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TagRecord` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::codeview::TagRecord { ... }
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/classrecord">ClassRecord</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/enumrecord">EnumRecord</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/codeview/unionrecord">UnionRecord</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af759981899827fb561806e39c9369f14">TagRecord</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2659a3cf5e042a5506f92bc334d55612">TagRecord</a> (TypeRecordKind Kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c00d1d1585b47541c01831ed6c6f8be">TagRecord</a> (TypeRecordKind Kind, uint16_t MemberCount, ClassOptions Options, TypeIndex FieldList, StringRef Name, StringRef UniqueName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec162f6cc543f9d9cea5c80164b721c7">hasUniqueName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab6453aee30af4ac315f22cb9a995228">isNested</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdd20673746f621d8d66eb99ea184db6">isForwardRef</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a235fa5ef1a5993850940f214e5cea8e6">containsNestedClass</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37edbd3c8727a30a60c94039bab9c1f3">isScoped</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a617caeb566ab0b62ed80122ec0dc391c">getMemberCount</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5a">ClassOptions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ae1be6e6d0d96125297733a3cfb222a">getOptions</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ce7692f6399c7ea2cdd3d84af0c912d">getFieldList</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70d494508697280429a70e6b54e90564">getName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3ecf47bdb500f15d02088ae17279b8b">getUniqueName</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a640158635770e1627bc985271458d606">MemberCount</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5a">ClassOptions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd08faf8aab0b59079ce629de126a952">Options</a> = <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa6adf97f83acf6453d4a6a4b1070f3754">ClassOptions::None</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e9fba1e80f2d1c13f9877b0d499ed2b">FieldList</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2babf3cfbef72c6758e02fde4f380370">Name</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa62f6a3634e2f0dfaf94a709751414af">UniqueName</a></td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2c8fff936dcf5ecd3d7e8ce9a73fce2">HfaKindShift</a> = 11</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79154e1b8650d54f9d32080e9fec7487">HfaKindMask</a> = 0x1800</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68169ea004d08c2d3cbc675d7445fcbb">WinRTKindShift</a> = 14</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54c72040065341ce4004a386fef4e426">WinRTKindMask</a> = 0xC000</td>
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


<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### TagRecord() {#af759981899827fb561806e39c9369f14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::codeview::TagRecord::TagRecord ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeview/classrecord/#a5d5838fd46303d07e42dd797aba73763">llvm::codeview::ClassRecord::ClassRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/classrecord/#a44215b067a96674eacbc9efd26a80987">llvm::codeview::ClassRecord::ClassRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/enumrecord/#a43c9ccb6269b742743b73b6799e9c867">llvm::codeview::EnumRecord::EnumRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/enumrecord/#a5feb9815c222d6714876d7be6a7168d5">llvm::codeview::EnumRecord::EnumRecord</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/unionrecord/#ad21d253fe1ff20d031e9a3dc5dcdb7a7">llvm::codeview::UnionRecord::UnionRecord</a> and <a href="/web-llvm/docs/api/structs/llvm/codeview/unionrecord/#a9dc7c5b6d04e2a89086da4a04daf3655">llvm::codeview::UnionRecord::UnionRecord</a>.</p>

</div>
</div>

### TagRecord() {#a2659a3cf5e042a5506f92bc334d55612}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::codeview::TagRecord::TagRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#abf3db0193e50769bab633545f88c383a">TypeRecordKind</a> Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codeview/typerecord/#a714d9d1981216f2af467fc81f53b8790">llvm::codeview::TypeRecord::Kind</a> and <a href="/web-llvm/docs/api/classes/llvm/codeview/typerecord/#a4259276eb9e9ab247c88103b93a20b5d">llvm::codeview::TypeRecord::TypeRecord</a>.</p>

</div>
</div>

### TagRecord() {#a9c00d1d1585b47541c01831ed6c6f8be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::codeview::TagRecord::TagRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#abf3db0193e50769bab633545f88c383a">TypeRecordKind</a> Kind, uint16_t MemberCount, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5a">ClassOptions</a> Options, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> FieldList, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> UniqueName)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>References <a href="#a3e9fba1e80f2d1c13f9877b0d499ed2b">FieldList</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typerecord/#a714d9d1981216f2af467fc81f53b8790">llvm::codeview::TypeRecord::Kind</a>, <a href="#a640158635770e1627bc985271458d606">MemberCount</a>, <a href="#a2babf3cfbef72c6758e02fde4f380370">Name</a>, <a href="#acd08faf8aab0b59079ce629de126a952">Options</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typerecord/#a4259276eb9e9ab247c88103b93a20b5d">llvm::codeview::TypeRecord::TypeRecord</a> and <a href="#aa62f6a3634e2f0dfaf94a709751414af">UniqueName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### containsNestedClass() {#a235fa5ef1a5993850940f214e5cea8e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codeview::TagRecord::containsNestedClass ()</td>
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



<p>Definition at line 443 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa7f67a4011b21d9ae7471351c38db2597">llvm::codeview::ContainsNestedClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa6adf97f83acf6453d4a6a4b1070f3754">llvm::codeview::None</a> and <a href="#acd08faf8aab0b59079ce629de126a952">Options</a>.</p>

</div>
</div>

### getFieldList() {#a6ce7692f6399c7ea2cdd3d84af0c912d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeIndex llvm::codeview::TagRecord::getFieldList ()</td>
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



<p>Definition at line 453 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>Reference <a href="#a3e9fba1e80f2d1c13f9877b0d499ed2b">FieldList</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#ade7088de2025cc1850af4e51e17c9255">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>.</p>

</div>
</div>

### getMemberCount() {#a617caeb566ab0b62ed80122ec0dc391c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::codeview::TagRecord::getMemberCount ()</td>
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



<p>Definition at line 451 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>Reference <a href="#a640158635770e1627bc985271458d606">MemberCount</a>.</p>

</div>
</div>

### getName() {#a70d494508697280429a70e6b54e90564}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::codeview::TagRecord::getName ()</td>
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



<p>Definition at line 454 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>Reference <a href="#a2babf3cfbef72c6758e02fde4f380370">Name</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/tpistream/#aab363a93f3751289108fdc859406dec4">llvm::pdb::TpiStream::findFullDeclForForwardRef</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/tpihashing-cpp/#af90a30ef58dfd685ecb7f85db1fc7ed0">getHashForUdt</a>.</p>

</div>
</div>

### getOptions() {#a1ae1be6e6d0d96125297733a3cfb222a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClassOptions llvm::codeview::TagRecord::getOptions ()</td>
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



<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>Reference <a href="#acd08faf8aab0b59079ce629de126a952">Options</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/tpihashing-cpp/#af90a30ef58dfd685ecb7f85db1fc7ed0">getHashForUdt</a>.</p>

</div>
</div>

### getUniqueName() {#ab3ecf47bdb500f15d02088ae17279b8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::codeview::TagRecord::getUniqueName ()</td>
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



<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>Reference <a href="#aa62f6a3634e2f0dfaf94a709751414af">UniqueName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/tpistream/#aab363a93f3751289108fdc859406dec4">llvm::pdb::TpiStream::findFullDeclForForwardRef</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/tpihashing-cpp/#af90a30ef58dfd685ecb7f85db1fc7ed0">getHashForUdt</a>.</p>

</div>
</div>

### hasUniqueName() {#aec162f6cc543f9d9cea5c80164b721c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codeview::TagRecord::hasUniqueName ()</td>
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



<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa1d847ff214177f9339928f7be873cd38">llvm::codeview::HasUniqueName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa6adf97f83acf6453d4a6a4b1070f3754">llvm::codeview::None</a> and <a href="#acd08faf8aab0b59079ce629de126a952">Options</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/tpistream/#aab363a93f3751289108fdc859406dec4">llvm::pdb::TpiStream::findFullDeclForForwardRef</a>.</p>

</div>
</div>

### isForwardRef() {#abdd20673746f621d8d66eb99ea184db6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codeview::TagRecord::isForwardRef ()</td>
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



<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa7e37f2aff533091462989c02c0cac8a1">llvm::codeview::ForwardReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa6adf97f83acf6453d4a6a4b1070f3754">llvm::codeview::None</a> and <a href="#acd08faf8aab0b59079ce629de126a952">Options</a>.</p>

</div>
</div>

### isNested() {#aab6453aee30af4ac315f22cb9a995228}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codeview::TagRecord::isNested ()</td>
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



<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa13c479c348969ab459513a4bfd559bb9">llvm::codeview::Nested</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa6adf97f83acf6453d4a6a4b1070f3754">llvm::codeview::None</a> and <a href="#acd08faf8aab0b59079ce629de126a952">Options</a>.</p>

</div>
</div>

### isScoped() {#a37edbd3c8727a30a60c94039bab9c1f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codeview::TagRecord::isScoped ()</td>
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



<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa6adf97f83acf6453d4a6a4b1070f3754">llvm::codeview::None</a>, <a href="#acd08faf8aab0b59079ce629de126a952">Options</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa423f62fd0413b98ab4dd487ec060e628">llvm::codeview::Scoped</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### FieldList {#a3e9fba1e80f2d1c13f9877b0d499ed2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeIndex llvm::codeview::TagRecord::FieldList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 459 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeview/classrecord/#a44215b067a96674eacbc9efd26a80987">llvm::codeview::ClassRecord::ClassRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/enumrecord/#a5feb9815c222d6714876d7be6a7168d5">llvm::codeview::EnumRecord::EnumRecord</a>, <a href="#a6ce7692f6399c7ea2cdd3d84af0c912d">getFieldList</a>, <a href="#a9c00d1d1585b47541c01831ed6c6f8be">TagRecord</a> and <a href="/web-llvm/docs/api/structs/llvm/codeview/unionrecord/#a9dc7c5b6d04e2a89086da4a04daf3655">llvm::codeview::UnionRecord::UnionRecord</a>.</p>

</div>
</div>

### MemberCount {#a640158635770e1627bc985271458d606}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::codeview::TagRecord::MemberCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 457 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeview/classrecord/#a44215b067a96674eacbc9efd26a80987">llvm::codeview::ClassRecord::ClassRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/enumrecord/#a5feb9815c222d6714876d7be6a7168d5">llvm::codeview::EnumRecord::EnumRecord</a>, <a href="#a617caeb566ab0b62ed80122ec0dc391c">getMemberCount</a>, <a href="#a9c00d1d1585b47541c01831ed6c6f8be">TagRecord</a> and <a href="/web-llvm/docs/api/structs/llvm/codeview/unionrecord/#a9dc7c5b6d04e2a89086da4a04daf3655">llvm::codeview::UnionRecord::UnionRecord</a>.</p>

</div>
</div>

### Name {#a2babf3cfbef72c6758e02fde4f380370}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::codeview::TagRecord::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeview/classrecord/#a44215b067a96674eacbc9efd26a80987">llvm::codeview::ClassRecord::ClassRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/enumrecord/#a5feb9815c222d6714876d7be6a7168d5">llvm::codeview::EnumRecord::EnumRecord</a>, <a href="#a70d494508697280429a70e6b54e90564">getName</a>, <a href="#a9c00d1d1585b47541c01831ed6c6f8be">TagRecord</a> and <a href="/web-llvm/docs/api/structs/llvm/codeview/unionrecord/#a9dc7c5b6d04e2a89086da4a04daf3655">llvm::codeview::UnionRecord::UnionRecord</a>.</p>

</div>
</div>

### Options {#acd08faf8aab0b59079ce629de126a952}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClassOptions llvm::codeview::TagRecord::Options = <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa6adf97f83acf6453d4a6a4b1070f3754">ClassOptions::None</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeview/classrecord/#a44215b067a96674eacbc9efd26a80987">llvm::codeview::ClassRecord::ClassRecord</a>, <a href="#a235fa5ef1a5993850940f214e5cea8e6">containsNestedClass</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/enumrecord/#a5feb9815c222d6714876d7be6a7168d5">llvm::codeview::EnumRecord::EnumRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/classrecord/#a5f5f136eae5ced747a0a295a38b7484c">llvm::codeview::ClassRecord::getHfa</a>, <a href="/web-llvm/docs/api/structs/llvm/codeview/unionrecord/#ae43e9785f43f3bce9cdd9154915ec28b">llvm::codeview::UnionRecord::getHfa</a>, <a href="#a1ae1be6e6d0d96125297733a3cfb222a">getOptions</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/classrecord/#a06d5aacdfe5b577af955c324a7476ccf">llvm::codeview::ClassRecord::getWinRTKind</a>, <a href="#aec162f6cc543f9d9cea5c80164b721c7">hasUniqueName</a>, <a href="#abdd20673746f621d8d66eb99ea184db6">isForwardRef</a>, <a href="#aab6453aee30af4ac315f22cb9a995228">isNested</a>, <a href="#a37edbd3c8727a30a60c94039bab9c1f3">isScoped</a>, <a href="#a9c00d1d1585b47541c01831ed6c6f8be">TagRecord</a> and <a href="/web-llvm/docs/api/structs/llvm/codeview/unionrecord/#a9dc7c5b6d04e2a89086da4a04daf3655">llvm::codeview::UnionRecord::UnionRecord</a>.</p>

</div>
</div>

### UniqueName {#aa62f6a3634e2f0dfaf94a709751414af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::codeview::TagRecord::UniqueName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 461 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeview/classrecord/#a44215b067a96674eacbc9efd26a80987">llvm::codeview::ClassRecord::ClassRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/enumrecord/#a5feb9815c222d6714876d7be6a7168d5">llvm::codeview::EnumRecord::EnumRecord</a>, <a href="#ab3ecf47bdb500f15d02088ae17279b8b">getUniqueName</a>, <a href="#a9c00d1d1585b47541c01831ed6c6f8be">TagRecord</a> and <a href="/web-llvm/docs/api/structs/llvm/codeview/unionrecord/#a9dc7c5b6d04e2a89086da4a04daf3655">llvm::codeview::UnionRecord::UnionRecord</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### HfaKindMask {#a79154e1b8650d54f9d32080e9fec7487}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int llvm::codeview::TagRecord::HfaKindMask = 0x1800</td>
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



<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeview/classrecord/#a5f5f136eae5ced747a0a295a38b7484c">llvm::codeview::ClassRecord::getHfa</a> and <a href="/web-llvm/docs/api/structs/llvm/codeview/unionrecord/#ae43e9785f43f3bce9cdd9154915ec28b">llvm::codeview::UnionRecord::getHfa</a>.</p>

</div>
</div>

### HfaKindShift {#ab2c8fff936dcf5ecd3d7e8ce9a73fce2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int llvm::codeview::TagRecord::HfaKindShift = 11</td>
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



<p>Definition at line 426 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeview/classrecord/#a5f5f136eae5ced747a0a295a38b7484c">llvm::codeview::ClassRecord::getHfa</a> and <a href="/web-llvm/docs/api/structs/llvm/codeview/unionrecord/#ae43e9785f43f3bce9cdd9154915ec28b">llvm::codeview::UnionRecord::getHfa</a>.</p>

</div>
</div>

### WinRTKindMask {#a54c72040065341ce4004a386fef4e426}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int llvm::codeview::TagRecord::WinRTKindMask = 0xC000</td>
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



<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeview/classrecord/#a06d5aacdfe5b577af955c324a7476ccf">llvm::codeview::ClassRecord::getWinRTKind</a>.</p>

</div>
</div>

### WinRTKindShift {#a68169ea004d08c2d3cbc675d7445fcbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int llvm::codeview::TagRecord::WinRTKindShift = 14</td>
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



<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeview/classrecord/#a06d5aacdfe5b577af955c324a7476ccf">llvm::codeview::ClassRecord::getWinRTKind</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">TypeRecord.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
