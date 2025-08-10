---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pdb/nativetypeudt
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `NativeTypeUDT` Class



## Declaration

<div class="doxyDeclaration">
class llvm::pdb::NativeTypeUDT { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">llvm/DebugInfo/PDB/Native/NativeTypeUDT.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol">NativeRawSymbol</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70b8e95461b0c5d87554a6a5c0364f48">NativeTypeUDT</a> (NativeSession &amp;Session, SymIndexId Id, codeview::TypeIndex TI, codeview::ClassRecord Class)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a758cb06187bc94241839ebde24aa2b70">NativeTypeUDT</a> (NativeSession &amp;Session, SymIndexId Id, codeview::TypeIndex TI, codeview::UnionRecord Union)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2573918bc53ebf30182e8d6e7b18c66">NativeTypeUDT</a> (NativeSession &amp;Session, SymIndexId Id, NativeTypeUDT &amp;UnmodifiedType, codeview::ModifierRecord Modifier)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6aa3892bd16b9ef3a2748c0166939517">~NativeTypeUDT</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a429795332975aa69787a933301471127">dump</a> (raw_ostream &amp;OS, int Indent, PdbSymbolIdField ShowIdFields, PdbSymbolIdField RecurseIdFields) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad026ccdc0ef3b2052f21dff0ca7d0061">getName</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a0d95a0af7fff523a0a4bfb7f6b578d12">SymIndexId</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a726423ee22916c3fb5b3ce9d66bf267f">getLexicalParentId</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a0d95a0af7fff523a0a4bfb7f6b578d12">SymIndexId</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c6d4091dec2d51e6073d91af7cb71bd">getUnmodifiedTypeId</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a0d95a0af7fff523a0a4bfb7f6b578d12">SymIndexId</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a069eef6f773300955e9b7c702e1bc868">getVirtualTableShapeId</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e67153fbcf7ef72347b7ddf3727236d">getLength</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a2ffaff61a965c84730991ba39b8fde85">PDB_UdtType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a024a1c90af860f1a90a54bce1fd02667">getUdtKind</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace7e8cb4ccde56f424f92bb9c705768c">hasConstructor</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae06c1ccaebbaa7df54fcc3966ca8c74b">isConstType</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaac5b7e5be2d46dce7f2b51e194abc23">hasAssignmentOperator</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb5389bc080c09e45b98adecfeee7e03">hasCastOperator</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08b9a5bf50e86833b595b2874240b741">hasNestedTypes</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1add428adad068e93d9f69380ddab02">hasOverloadedOperator</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb4f33d931fa6642c6a0fc5299bbedde">isInterfaceUdt</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af933dc10615f6df2d1b2b9c08ef8690d">isIntrinsic</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4247ae1f2a25ed7a53087a56e9683bc">isNested</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a82f8fefd8409bbd5cd01ac0690a2fd">isPacked</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18bc96420917b3183994fae206497a5f">isRefUdt</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42b6d97c601f2234c7e63b4aaad42912">isScoped</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a23b5d57e54e1bc994deaf310153352">isValueUdt</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d9bc59b7a30c2db04a3a052150a2ac5">isUnalignedType</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33d6eb9f715985d8cd3debb7fe2aede1">isVolatileType</a> () const override</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbf79f48453aaa16aedb10af8052118a">Index</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/codeview/classrecord">codeview::ClassRecord</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2b5aad1b0bdd180db46c60607f87de9">Class</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/unionrecord">codeview::UnionRecord</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fd173a79a20ad9822fcf941eb3045b3">Union</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pdb/nativetypeudt">NativeTypeUDT</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5178af4ec22ff6ac6a961d069593ded4">UnmodifiedType</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/tagrecord">codeview::TagRecord</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaa2d5ce718474310d3bdfd20fbab992">Tag</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/codeview/modifierrecord">codeview::ModifierRecord</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac68a7b7d77bf47f6dc92342763be88ca">Modifiers</a></td>
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


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### NativeTypeUDT() {#a70b8e95461b0c5d87554a6a5c0364f48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NativeTypeUDT::NativeTypeUDT (<a href="/web-llvm/docs/api/classes/llvm/pdb/nativesession">NativeSession</a> &amp; Session, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a0d95a0af7fff523a0a4bfb7f6b578d12">SymIndexId</a> Id, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/codeview/classrecord">codeview::ClassRecord</a> Class)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>, definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeudt-cpp">NativeTypeUDT.cpp</a>.</p>


<p>References <a href="#aa2b5aad1b0bdd180db46c60607f87de9">Class</a>, <a href="#adbf79f48453aaa16aedb10af8052118a">Index</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#a4cbeed8a0b429b5aea245873a199f97b">llvm::pdb::NativeRawSymbol::NativeRawSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#ae264b7462dfb57a16a94b8f871f52920">llvm::pdb::NativeRawSymbol::Session</a>, <a href="#acaa2d5ce718474310d3bdfd20fbab992">Tag</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30ba37c9ef439007788bd633ea027a36e87e">llvm::pdb::UDT</a>.</p>


<p>Referenced by <a href="#ad2573918bc53ebf30182e8d6e7b18c66">NativeTypeUDT</a>.</p>

</div>
</div>

### NativeTypeUDT() {#a758cb06187bc94241839ebde24aa2b70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NativeTypeUDT::NativeTypeUDT (<a href="/web-llvm/docs/api/classes/llvm/pdb/nativesession">NativeSession</a> &amp; Session, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a0d95a0af7fff523a0a4bfb7f6b578d12">SymIndexId</a> Id, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a> TI, <a href="/web-llvm/docs/api/structs/llvm/codeview/unionrecord">codeview::UnionRecord</a> Union)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeudt-cpp">NativeTypeUDT.cpp</a>.</p>


<p>References <a href="#adbf79f48453aaa16aedb10af8052118a">Index</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#a4cbeed8a0b429b5aea245873a199f97b">llvm::pdb::NativeRawSymbol::NativeRawSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#ae264b7462dfb57a16a94b8f871f52920">llvm::pdb::NativeRawSymbol::Session</a>, <a href="#acaa2d5ce718474310d3bdfd20fbab992">Tag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30ba37c9ef439007788bd633ea027a36e87e">llvm::pdb::UDT</a> and <a href="#a7fd173a79a20ad9822fcf941eb3045b3">Union</a>.</p>

</div>
</div>

### NativeTypeUDT() {#ad2573918bc53ebf30182e8d6e7b18c66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NativeTypeUDT::NativeTypeUDT (<a href="/web-llvm/docs/api/classes/llvm/pdb/nativesession">NativeSession</a> &amp; Session, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a0d95a0af7fff523a0a4bfb7f6b578d12">SymIndexId</a> Id, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativetypeudt">NativeTypeUDT</a> &amp; UnmodifiedType, <a href="/web-llvm/docs/api/classes/llvm/codeview/modifierrecord">codeview::ModifierRecord</a> Modifier)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>, definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeudt-cpp">NativeTypeUDT.cpp</a>.</p>


<p>References <a href="#ac68a7b7d77bf47f6dc92342763be88ca">Modifiers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#a4cbeed8a0b429b5aea245873a199f97b">llvm::pdb::NativeRawSymbol::NativeRawSymbol</a>, <a href="#a70b8e95461b0c5d87554a6a5c0364f48">NativeTypeUDT</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#ae264b7462dfb57a16a94b8f871f52920">llvm::pdb::NativeRawSymbol::Session</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30ba37c9ef439007788bd633ea027a36e87e">llvm::pdb::UDT</a> and <a href="#a5178af4ec22ff6ac6a961d069593ded4">UnmodifiedType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~NativeTypeUDT() {#a6aa3892bd16b9ef3a2748c0166939517}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NativeTypeUDT::~NativeTypeUDT ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a429795332975aa69787a933301471127}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NativeTypeUDT::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, int Indent, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2c">PdbSymbolIdField</a> ShowIdFields, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2c">PdbSymbolIdField</a> RecurseIdFields)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeudt-cpp">NativeTypeUDT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#aeeda1eb1da6fda8318d0a3093caa3ea2">llvm::pdb::NativeRawSymbol::dump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a28e0e7c7f7920e3608fea13ec3e4394e">llvm::pdb::dumpSymbolField</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#aebe60f61f4fe8956834c561bfb8a75e8">llvm::pdb::dumpSymbolIdField</a>, <a href="#a2e67153fbcf7ef72347b7ddf3727236d">getLength</a>, <a href="#ad026ccdc0ef3b2052f21dff0ca7d0061">getName</a>, <a href="#a024a1c90af860f1a90a54bce1fd02667">getUdtKind</a>, <a href="#a6c6d4091dec2d51e6073d91af7cb71bd">getUnmodifiedTypeId</a>, <a href="#a069eef6f773300955e9b7c702e1bc868">getVirtualTableShapeId</a>, <a href="#aaac5b7e5be2d46dce7f2b51e194abc23">hasAssignmentOperator</a>, <a href="#abb5389bc080c09e45b98adecfeee7e03">hasCastOperator</a>, <a href="#ace7e8cb4ccde56f424f92bb9c705768c">hasConstructor</a>, <a href="#a08b9a5bf50e86833b595b2874240b741">hasNestedTypes</a>, <a href="#af1add428adad068e93d9f69380ddab02">hasOverloadedOperator</a>, <a href="#ae06c1ccaebbaa7df54fcc3966ca8c74b">isConstType</a>, <a href="#afb4f33d931fa6642c6a0fc5299bbedde">isInterfaceUdt</a>, <a href="#af933dc10615f6df2d1b2b9c08ef8690d">isIntrinsic</a>, <a href="#af4247ae1f2a25ed7a53087a56e9683bc">isNested</a>, <a href="#a0a82f8fefd8409bbd5cd01ac0690a2fd">isPacked</a>, <a href="#a18bc96420917b3183994fae206497a5f">isRefUdt</a>, <a href="#a42b6d97c601f2234c7e63b4aaad42912">isScoped</a>, <a href="#a2d9bc59b7a30c2db04a3a052150a2ac5">isUnalignedType</a>, <a href="#a3a23b5d57e54e1bc994deaf310153352">isValueUdt</a>, <a href="#a33d6eb9f715985d8cd3debb7fe2aede1">isVolatileType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2ca0a31053bfd7ad7db33f78a8c31f4c99a">llvm::pdb::LexicalParent</a>, <a href="#ac68a7b7d77bf47f6dc92342763be88ca">Modifiers</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#ae264b7462dfb57a16a94b8f871f52920">llvm::pdb::NativeRawSymbol::Session</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a2ffaff61a965c84730991ba39b8fde85aaef12e903e606a4895a16b393bfdec8c">llvm::pdb::Union</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2ca233fe8dc2f7e028d63c719394a3b1f8a">llvm::pdb::UnmodifiedType</a>.</p>

</div>
</div>

### getLength() {#a2e67153fbcf7ef72347b7ddf3727236d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t NativeTypeUDT::getLength ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>, definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeudt-cpp">NativeTypeUDT.cpp</a>.</p>


<p>References <a href="#aa2b5aad1b0bdd180db46c60607f87de9">Class</a>, <a href="#a7fd173a79a20ad9822fcf941eb3045b3">Union</a> and <a href="#a5178af4ec22ff6ac6a961d069593ded4">UnmodifiedType</a>.</p>


<p>Referenced by <a href="#a429795332975aa69787a933301471127">dump</a>.</p>

</div>
</div>

### getLexicalParentId() {#a726423ee22916c3fb5b3ce9d66bf267f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymIndexId NativeTypeUDT::getLexicalParentId ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>, definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeudt-cpp">NativeTypeUDT.cpp</a>.</p>

</div>
</div>

### getName() {#ad026ccdc0ef3b2052f21dff0ca7d0061}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string NativeTypeUDT::getName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>, definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeudt-cpp">NativeTypeUDT.cpp</a>.</p>


<p>References <a href="#acaa2d5ce718474310d3bdfd20fbab992">Tag</a> and <a href="#a5178af4ec22ff6ac6a961d069593ded4">UnmodifiedType</a>.</p>


<p>Referenced by <a href="#a429795332975aa69787a933301471127">dump</a>.</p>

</div>
</div>

### getUdtKind() {#a024a1c90af860f1a90a54bce1fd02667}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PDB_UdtType NativeTypeUDT::getUdtKind ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>, definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeudt-cpp">NativeTypeUDT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a2ffaff61a965c84730991ba39b8fde85a9bd81329febf6efe22788e03ddeaf0af">llvm::pdb::Class</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a2ffaff61a965c84730991ba39b8fde85a3c1aac82863ed9e5a9aca8ce687f711d">llvm::pdb::Interface</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a2ffaff61a965c84730991ba39b8fde85a886ef5dbd655a6c97726d7091c6b173e">llvm::pdb::Struct</a>, <a href="#acaa2d5ce718474310d3bdfd20fbab992">Tag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a2ffaff61a965c84730991ba39b8fde85aaef12e903e606a4895a16b393bfdec8c">llvm::pdb::Union</a> and <a href="#a5178af4ec22ff6ac6a961d069593ded4">UnmodifiedType</a>.</p>


<p>Referenced by <a href="#a429795332975aa69787a933301471127">dump</a>.</p>

</div>
</div>

### getUnmodifiedTypeId() {#a6c6d4091dec2d51e6073d91af7cb71bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymIndexId NativeTypeUDT::getUnmodifiedTypeId ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>, definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeudt-cpp">NativeTypeUDT.cpp</a>.</p>


<p>Reference <a href="#a5178af4ec22ff6ac6a961d069593ded4">UnmodifiedType</a>.</p>


<p>Referenced by <a href="#a429795332975aa69787a933301471127">dump</a>.</p>

</div>
</div>

### getVirtualTableShapeId() {#a069eef6f773300955e9b7c702e1bc868}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymIndexId NativeTypeUDT::getVirtualTableShapeId ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>, definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeudt-cpp">NativeTypeUDT.cpp</a>.</p>


<p>References <a href="#aa2b5aad1b0bdd180db46c60607f87de9">Class</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#ae264b7462dfb57a16a94b8f871f52920">llvm::pdb::NativeRawSymbol::Session</a> and <a href="#a5178af4ec22ff6ac6a961d069593ded4">UnmodifiedType</a>.</p>


<p>Referenced by <a href="#a429795332975aa69787a933301471127">dump</a>.</p>

</div>
</div>

### hasAssignmentOperator() {#aaac5b7e5be2d46dce7f2b51e194abc23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeUDT::hasAssignmentOperator ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>, definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeudt-cpp">NativeTypeUDT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa8c104df916cac8868cd4e82cccb8adb2">llvm::codeview::HasOverloadedAssignmentOperator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa6adf97f83acf6453d4a6a4b1070f3754">llvm::codeview::None</a>, <a href="#acaa2d5ce718474310d3bdfd20fbab992">Tag</a> and <a href="#a5178af4ec22ff6ac6a961d069593ded4">UnmodifiedType</a>.</p>


<p>Referenced by <a href="#a429795332975aa69787a933301471127">dump</a>.</p>

</div>
</div>

### hasCastOperator() {#abb5389bc080c09e45b98adecfeee7e03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeUDT::hasCastOperator ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>, definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeudt-cpp">NativeTypeUDT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aadb77a6e068212caaabc47dbf4cab280f">llvm::codeview::HasConversionOperator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa6adf97f83acf6453d4a6a4b1070f3754">llvm::codeview::None</a>, <a href="#acaa2d5ce718474310d3bdfd20fbab992">Tag</a> and <a href="#a5178af4ec22ff6ac6a961d069593ded4">UnmodifiedType</a>.</p>


<p>Referenced by <a href="#a429795332975aa69787a933301471127">dump</a>.</p>

</div>
</div>

### hasConstructor() {#ace7e8cb4ccde56f424f92bb9c705768c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeUDT::hasConstructor ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>, definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeudt-cpp">NativeTypeUDT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa6df427d10ced170429c407317356800c">llvm::codeview::HasConstructorOrDestructor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa6adf97f83acf6453d4a6a4b1070f3754">llvm::codeview::None</a>, <a href="#acaa2d5ce718474310d3bdfd20fbab992">Tag</a> and <a href="#a5178af4ec22ff6ac6a961d069593ded4">UnmodifiedType</a>.</p>


<p>Referenced by <a href="#a429795332975aa69787a933301471127">dump</a>.</p>

</div>
</div>

### hasNestedTypes() {#a08b9a5bf50e86833b595b2874240b741}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeUDT::hasNestedTypes ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeudt-cpp">NativeTypeUDT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa7f67a4011b21d9ae7471351c38db2597">llvm::codeview::ContainsNestedClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa6adf97f83acf6453d4a6a4b1070f3754">llvm::codeview::None</a>, <a href="#acaa2d5ce718474310d3bdfd20fbab992">Tag</a> and <a href="#a5178af4ec22ff6ac6a961d069593ded4">UnmodifiedType</a>.</p>


<p>Referenced by <a href="#a429795332975aa69787a933301471127">dump</a>.</p>

</div>
</div>

### hasOverloadedOperator() {#af1add428adad068e93d9f69380ddab02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeUDT::hasOverloadedOperator ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>, definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeudt-cpp">NativeTypeUDT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa6c7813302cb4e344823952999dd52859">llvm::codeview::HasOverloadedOperator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa6adf97f83acf6453d4a6a4b1070f3754">llvm::codeview::None</a>, <a href="#acaa2d5ce718474310d3bdfd20fbab992">Tag</a> and <a href="#a5178af4ec22ff6ac6a961d069593ded4">UnmodifiedType</a>.</p>


<p>Referenced by <a href="#a429795332975aa69787a933301471127">dump</a>.</p>

</div>
</div>

### isConstType() {#ae06c1ccaebbaa7df54fcc3966ca8c74b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeUDT::isConstType ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>, definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeudt-cpp">NativeTypeUDT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#acf5c2920c8a10eeb1d8c5d3a9c2adfb6a79ceee9f8e3c1f0cc74223e05d2448bf">llvm::codeview::Const</a>, <a href="#ac68a7b7d77bf47f6dc92342763be88ca">Modifiers</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#acf5c2920c8a10eeb1d8c5d3a9c2adfb6a6adf97f83acf6453d4a6a4b1070f3754">llvm::codeview::None</a>.</p>


<p>Referenced by <a href="#a429795332975aa69787a933301471127">dump</a>.</p>

</div>
</div>

### isInterfaceUdt() {#afb4f33d931fa6642c6a0fc5299bbedde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeUDT::isInterfaceUdt ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>, definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeudt-cpp">NativeTypeUDT.cpp</a>.</p>


<p>Referenced by <a href="#a429795332975aa69787a933301471127">dump</a>.</p>

</div>
</div>

### isIntrinsic() {#af933dc10615f6df2d1b2b9c08ef8690d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeUDT::isIntrinsic ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>, definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeudt-cpp">NativeTypeUDT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa8b0f368e62695dc13b998050ea15a2c5">llvm::codeview::Intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa6adf97f83acf6453d4a6a4b1070f3754">llvm::codeview::None</a>, <a href="#acaa2d5ce718474310d3bdfd20fbab992">Tag</a> and <a href="#a5178af4ec22ff6ac6a961d069593ded4">UnmodifiedType</a>.</p>


<p>Referenced by <a href="#a429795332975aa69787a933301471127">dump</a>.</p>

</div>
</div>

### isNested() {#af4247ae1f2a25ed7a53087a56e9683bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeUDT::isNested ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>, definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeudt-cpp">NativeTypeUDT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa13c479c348969ab459513a4bfd559bb9">llvm::codeview::Nested</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa6adf97f83acf6453d4a6a4b1070f3754">llvm::codeview::None</a>, <a href="#acaa2d5ce718474310d3bdfd20fbab992">Tag</a> and <a href="#a5178af4ec22ff6ac6a961d069593ded4">UnmodifiedType</a>.</p>


<p>Referenced by <a href="#a429795332975aa69787a933301471127">dump</a>.</p>

</div>
</div>

### isPacked() {#a0a82f8fefd8409bbd5cd01ac0690a2fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeUDT::isPacked ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>, definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeudt-cpp">NativeTypeUDT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa6adf97f83acf6453d4a6a4b1070f3754">llvm::codeview::None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aaa1977c3f68d4d3bbfe14d0e51a575482">llvm::codeview::Packed</a>, <a href="#acaa2d5ce718474310d3bdfd20fbab992">Tag</a> and <a href="#a5178af4ec22ff6ac6a961d069593ded4">UnmodifiedType</a>.</p>


<p>Referenced by <a href="#a429795332975aa69787a933301471127">dump</a>.</p>

</div>
</div>

### isRefUdt() {#a18bc96420917b3183994fae206497a5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeUDT::isRefUdt ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>, definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeudt-cpp">NativeTypeUDT.cpp</a>.</p>


<p>Referenced by <a href="#a429795332975aa69787a933301471127">dump</a>.</p>

</div>
</div>

### isScoped() {#a42b6d97c601f2234c7e63b4aaad42912}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeUDT::isScoped ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>, definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeudt-cpp">NativeTypeUDT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa6adf97f83acf6453d4a6a4b1070f3754">llvm::codeview::None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa423f62fd0413b98ab4dd487ec060e628">llvm::codeview::Scoped</a>, <a href="#acaa2d5ce718474310d3bdfd20fbab992">Tag</a> and <a href="#a5178af4ec22ff6ac6a961d069593ded4">UnmodifiedType</a>.</p>


<p>Referenced by <a href="#a429795332975aa69787a933301471127">dump</a>.</p>

</div>
</div>

### isUnalignedType() {#a2d9bc59b7a30c2db04a3a052150a2ac5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeUDT::isUnalignedType ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>, definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeudt-cpp">NativeTypeUDT.cpp</a>.</p>


<p>References <a href="#ac68a7b7d77bf47f6dc92342763be88ca">Modifiers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#acf5c2920c8a10eeb1d8c5d3a9c2adfb6a6adf97f83acf6453d4a6a4b1070f3754">llvm::codeview::None</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#acf5c2920c8a10eeb1d8c5d3a9c2adfb6a9f19679888db198f8dd45606487e6cd6">llvm::codeview::Unaligned</a>.</p>


<p>Referenced by <a href="#a429795332975aa69787a933301471127">dump</a>.</p>

</div>
</div>

### isValueUdt() {#a3a23b5d57e54e1bc994deaf310153352}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeUDT::isValueUdt ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>, definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeudt-cpp">NativeTypeUDT.cpp</a>.</p>


<p>Referenced by <a href="#a429795332975aa69787a933301471127">dump</a>.</p>

</div>
</div>

### isVolatileType() {#a33d6eb9f715985d8cd3debb7fe2aede1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeUDT::isVolatileType ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>, definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeudt-cpp">NativeTypeUDT.cpp</a>.</p>


<p>References <a href="#ac68a7b7d77bf47f6dc92342763be88ca">Modifiers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#acf5c2920c8a10eeb1d8c5d3a9c2adfb6a6adf97f83acf6453d4a6a4b1070f3754">llvm::codeview::None</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#acf5c2920c8a10eeb1d8c5d3a9c2adfb6a3e3af98b6b48c7e593d8d18863e3333b">llvm::codeview::Volatile</a>.</p>


<p>Referenced by <a href="#a429795332975aa69787a933301471127">dump</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Class {#aa2b5aad1b0bdd180db46c60607f87de9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;codeview::ClassRecord&gt; llvm::pdb::NativeTypeUDT::Class</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>.</p>


<p>Referenced by <a href="#a2e67153fbcf7ef72347b7ddf3727236d">getLength</a>, <a href="#a069eef6f773300955e9b7c702e1bc868">getVirtualTableShapeId</a> and <a href="#a70b8e95461b0c5d87554a6a5c0364f48">NativeTypeUDT</a>.</p>

</div>
</div>

### Index {#adbf79f48453aaa16aedb10af8052118a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">codeview::TypeIndex llvm::pdb::NativeTypeUDT::Index</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>.</p>


<p>Referenced by <a href="#a70b8e95461b0c5d87554a6a5c0364f48">NativeTypeUDT</a> and <a href="#a758cb06187bc94241839ebde24aa2b70">NativeTypeUDT</a>.</p>

</div>
</div>

### Modifiers {#ac68a7b7d77bf47f6dc92342763be88ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;codeview::ModifierRecord&gt; llvm::pdb::NativeTypeUDT::Modifiers</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>.</p>


<p>Referenced by <a href="#a429795332975aa69787a933301471127">dump</a>, <a href="#ae06c1ccaebbaa7df54fcc3966ca8c74b">isConstType</a>, <a href="#a2d9bc59b7a30c2db04a3a052150a2ac5">isUnalignedType</a>, <a href="#a33d6eb9f715985d8cd3debb7fe2aede1">isVolatileType</a> and <a href="#ad2573918bc53ebf30182e8d6e7b18c66">NativeTypeUDT</a>.</p>

</div>
</div>

### Tag {#acaa2d5ce718474310d3bdfd20fbab992}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">codeview::TagRecord* llvm::pdb::NativeTypeUDT::Tag = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>.</p>


<p>Referenced by <a href="#ad026ccdc0ef3b2052f21dff0ca7d0061">getName</a>, <a href="#a024a1c90af860f1a90a54bce1fd02667">getUdtKind</a>, <a href="#aaac5b7e5be2d46dce7f2b51e194abc23">hasAssignmentOperator</a>, <a href="#abb5389bc080c09e45b98adecfeee7e03">hasCastOperator</a>, <a href="#ace7e8cb4ccde56f424f92bb9c705768c">hasConstructor</a>, <a href="#a08b9a5bf50e86833b595b2874240b741">hasNestedTypes</a>, <a href="#af1add428adad068e93d9f69380ddab02">hasOverloadedOperator</a>, <a href="#af933dc10615f6df2d1b2b9c08ef8690d">isIntrinsic</a>, <a href="#af4247ae1f2a25ed7a53087a56e9683bc">isNested</a>, <a href="#a0a82f8fefd8409bbd5cd01ac0690a2fd">isPacked</a>, <a href="#a42b6d97c601f2234c7e63b4aaad42912">isScoped</a>, <a href="#a70b8e95461b0c5d87554a6a5c0364f48">NativeTypeUDT</a> and <a href="#a758cb06187bc94241839ebde24aa2b70">NativeTypeUDT</a>.</p>

</div>
</div>

### Union {#a7fd173a79a20ad9822fcf941eb3045b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;codeview::UnionRecord&gt; llvm::pdb::NativeTypeUDT::Union</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>.</p>


<p>Referenced by <a href="#a2e67153fbcf7ef72347b7ddf3727236d">getLength</a> and <a href="#a758cb06187bc94241839ebde24aa2b70">NativeTypeUDT</a>.</p>

</div>
</div>

### UnmodifiedType {#a5178af4ec22ff6ac6a961d069593ded4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NativeTypeUDT* llvm::pdb::NativeTypeUDT::UnmodifiedType = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a>.</p>


<p>Referenced by <a href="#a2e67153fbcf7ef72347b7ddf3727236d">getLength</a>, <a href="#ad026ccdc0ef3b2052f21dff0ca7d0061">getName</a>, <a href="#a024a1c90af860f1a90a54bce1fd02667">getUdtKind</a>, <a href="#a6c6d4091dec2d51e6073d91af7cb71bd">getUnmodifiedTypeId</a>, <a href="#a069eef6f773300955e9b7c702e1bc868">getVirtualTableShapeId</a>, <a href="#aaac5b7e5be2d46dce7f2b51e194abc23">hasAssignmentOperator</a>, <a href="#abb5389bc080c09e45b98adecfeee7e03">hasCastOperator</a>, <a href="#ace7e8cb4ccde56f424f92bb9c705768c">hasConstructor</a>, <a href="#a08b9a5bf50e86833b595b2874240b741">hasNestedTypes</a>, <a href="#af1add428adad068e93d9f69380ddab02">hasOverloadedOperator</a>, <a href="#af933dc10615f6df2d1b2b9c08ef8690d">isIntrinsic</a>, <a href="#af4247ae1f2a25ed7a53087a56e9683bc">isNested</a>, <a href="#a0a82f8fefd8409bbd5cd01ac0690a2fd">isPacked</a>, <a href="#a42b6d97c601f2234c7e63b4aaad42912">isScoped</a> and <a href="#ad2573918bc53ebf30182e8d6e7b18c66">NativeTypeUDT</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">NativeTypeUDT.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeudt-cpp">NativeTypeUDT.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
