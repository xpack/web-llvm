---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pdb/nativetypeenum
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `NativeTypeEnum` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::pdb::NativeTypeEnum { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">llvm/DebugInfo/PDB/Native/NativeTypeEnum.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeecd54c516a16990d6a08d1dd5675305">NativeTypeEnum</a> (NativeSession &amp;Session, SymIndexId Id, codeview::TypeIndex TI, codeview::EnumRecord Record)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a314f3fab5f60ce72b855e5d138e8a1bf">NativeTypeEnum</a> (NativeSession &amp;Session, SymIndexId Id, NativeTypeEnum &amp;UnmodifiedType, codeview::ModifierRecord Modifier)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8e77b42844ee2b7ccd2b67cf1f155a9">~NativeTypeEnum</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39e505f7c57048ad10d23dc4f17ae413">dump</a> (raw_ostream &amp;OS, int Indent, PdbSymbolIdField ShowIdFields, PdbSymbolIdField RecurseIdFields) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a998b8b6d4749134e27e473e313ece092">IPDBEnumSymbols</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a616dd528c581972135480eb7b13dceca">findChildren</a> (PDB_SymType Type) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a29a5bdf367e3f74df9228dfce2c93a6f">PDB_BuiltinType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6740b5cf37d9355b1f920da35c666d96">getBuiltinType</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30b">PDB_SymType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9cd11b93297fb4fb411bfab0d5b4328">getSymTag</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfc600899131b1858375398069d2f604">getUnmodifiedTypeId</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a703661603296b069f5589b14383d8296">hasConstructor</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44aaba2293cab5d22146b49c596721c6">hasAssignmentOperator</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a624f209ee7f18171bad690f32b13b977">hasCastOperator</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae17a24ecd19908de92b5a124a8cc57e6">getLength</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a202da4841ffeab82ffdd34d5d7d2e437">getName</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82a0ade551d4350577ccc04bdc68e65b">isConstType</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a029aa26195d123c47100fd564a850d03">isVolatileType</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a4979af44394e318626ee259916b797">isUnalignedType</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a523b10b95d962cd80d62711789582a97">isNested</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c9dab0e0959f1f91aa7e18713e3058e">hasOverloadedOperator</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8e421cd983eff100ffa5f614534476d">hasNestedTypes</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a107b373b7b70ab47c03b52193867beac">isIntrinsic</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d1b8bde8a25d7083e4192ff905050e2">isPacked</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02e4ff01cce049ff9ec4eb0fc47514e9">isScoped</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7745bb6af8fabffdc34df8866af3f5ea">getTypeId</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee6102ad51e6b3f3771759a377a51863">isRefUdt</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58ef4452d1fcca9848c6e7a66421e364">isValueUdt</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60328cfef7d687f69c4e5e4a1bc65209">isInterfaceUdt</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pdb/nativetypebuiltin">NativeTypeBuiltin</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae2a46e82210ad08b02e14c261089988">getUnderlyingBuiltinType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeview/enumrecord">codeview::EnumRecord</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88121fdf4b0993d40f77a6a17eca0f1d">getEnumRecord</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0006e4521304048708c8e8085882725a">Index</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/codeview/enumrecord">codeview::EnumRecord</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9b2009770f84bad6cb26a7435e84ee0">Record</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pdb/nativetypeenum">NativeTypeEnum</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb4469b960bd11e184cb2cefb91a36e7">UnmodifiedType</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2073dc499f56b3a7bbb977f3af13ec0">Modifiers</a></td>
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


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### NativeTypeEnum() {#aeecd54c516a16990d6a08d1dd5675305}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NativeTypeEnum::NativeTypeEnum (<a href="/web-llvm/docs/api/classes/llvm/pdb/nativesession">NativeSession</a> &amp; Session, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a0d95a0af7fff523a0a4bfb7f6b578d12">SymIndexId</a> Id, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/codeview/enumrecord">codeview::EnumRecord</a> Record)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>, definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeenum-cpp">NativeTypeEnum.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30bacf20423ed48998082c20099488a0917c">llvm::pdb::Enum</a>, <a href="#a0006e4521304048708c8e8085882725a">Index</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#a4cbeed8a0b429b5aea245873a199f97b">llvm::pdb::NativeRawSymbol::NativeRawSymbol</a>, <a href="#ae9b2009770f84bad6cb26a7435e84ee0">Record</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#ae264b7462dfb57a16a94b8f871f52920">llvm::pdb::NativeRawSymbol::Session</a>.</p>


<p>Referenced by <a href="#a616dd528c581972135480eb7b13dceca">findChildren</a> and <a href="#a314f3fab5f60ce72b855e5d138e8a1bf">NativeTypeEnum</a>.</p>

</div>
</div>

### NativeTypeEnum() {#a314f3fab5f60ce72b855e5d138e8a1bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NativeTypeEnum::NativeTypeEnum (<a href="/web-llvm/docs/api/classes/llvm/pdb/nativesession">NativeSession</a> &amp; Session, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a0d95a0af7fff523a0a4bfb7f6b578d12">SymIndexId</a> Id, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativetypeenum">NativeTypeEnum</a> &amp; UnmodifiedType, <a href="/web-llvm/docs/api/classes/llvm/codeview/modifierrecord">codeview::ModifierRecord</a> Modifier)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>, definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeenum-cpp">NativeTypeEnum.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30bacf20423ed48998082c20099488a0917c">llvm::pdb::Enum</a>, <a href="#ac2073dc499f56b3a7bbb977f3af13ec0">Modifiers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#a4cbeed8a0b429b5aea245873a199f97b">llvm::pdb::NativeRawSymbol::NativeRawSymbol</a>, <a href="#aeecd54c516a16990d6a08d1dd5675305">NativeTypeEnum</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#ae264b7462dfb57a16a94b8f871f52920">llvm::pdb::NativeRawSymbol::Session</a> and <a href="#adb4469b960bd11e184cb2cefb91a36e7">UnmodifiedType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~NativeTypeEnum() {#ac8e77b42844ee2b7ccd2b67cf1f155a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NativeTypeEnum::~NativeTypeEnum ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2caa1fa27779242b4902f7ae3bdd5c6d508">llvm::pdb::Type</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a39e505f7c57048ad10d23dc4f17ae413}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NativeTypeEnum::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, int Indent, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2c">PdbSymbolIdField</a> ShowIdFields, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2c">PdbSymbolIdField</a> RecurseIdFields)</td>
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



<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>, definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeenum-cpp">NativeTypeEnum.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#aeeda1eb1da6fda8318d0a3093caa3ea2">llvm::pdb::NativeRawSymbol::dump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a28e0e7c7f7920e3608fea13ec3e4394e">llvm::pdb::dumpSymbolField</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#aebe60f61f4fe8956834c561bfb8a75e8">llvm::pdb::dumpSymbolIdField</a>, <a href="#a6740b5cf37d9355b1f920da35c666d96">getBuiltinType</a>, <a href="#ae17a24ecd19908de92b5a124a8cc57e6">getLength</a>, <a href="#a202da4841ffeab82ffdd34d5d7d2e437">getName</a>, <a href="#a7745bb6af8fabffdc34df8866af3f5ea">getTypeId</a>, <a href="#abfc600899131b1858375398069d2f604">getUnmodifiedTypeId</a>, <a href="#a44aaba2293cab5d22146b49c596721c6">hasAssignmentOperator</a>, <a href="#a624f209ee7f18171bad690f32b13b977">hasCastOperator</a>, <a href="#a703661603296b069f5589b14383d8296">hasConstructor</a>, <a href="#ab8e421cd983eff100ffa5f614534476d">hasNestedTypes</a>, <a href="#a0c9dab0e0959f1f91aa7e18713e3058e">hasOverloadedOperator</a>, <a href="#a82a0ade551d4350577ccc04bdc68e65b">isConstType</a>, <a href="#a60328cfef7d687f69c4e5e4a1bc65209">isInterfaceUdt</a>, <a href="#a107b373b7b70ab47c03b52193867beac">isIntrinsic</a>, <a href="#a523b10b95d962cd80d62711789582a97">isNested</a>, <a href="#a1d1b8bde8a25d7083e4192ff905050e2">isPacked</a>, <a href="#aee6102ad51e6b3f3771759a377a51863">isRefUdt</a>, <a href="#a02e4ff01cce049ff9ec4eb0fc47514e9">isScoped</a>, <a href="#a5a4979af44394e318626ee259916b797">isUnalignedType</a>, <a href="#a58ef4452d1fcca9848c6e7a66421e364">isValueUdt</a>, <a href="#a029aa26195d123c47100fd564a850d03">isVolatileType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2ca0a31053bfd7ad7db33f78a8c31f4c99a">llvm::pdb::LexicalParent</a>, <a href="#ac2073dc499f56b3a7bbb977f3af13ec0">Modifiers</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#ae264b7462dfb57a16a94b8f871f52920">llvm::pdb::NativeRawSymbol::Session</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2caa1fa27779242b4902f7ae3bdd5c6d508">llvm::pdb::Type</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2ca233fe8dc2f7e028d63c719394a3b1f8a">llvm::pdb::UnmodifiedType</a>.</p>

</div>
</div>

### findChildren() {#a616dd528c581972135480eb7b13dceca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; IPDBEnumSymbols &gt; NativeTypeEnum::findChildren (<a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30b">PDB_SymType</a> Type)</td>
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



<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>, definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeenum-cpp">NativeTypeEnum.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2ca5ec2b91b4f21888ae4a157c15d806941">llvm::pdb::ClassParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30baf6068daa29dbb05a7ead1e3b5a48bbee">llvm::pdb::Data</a>, <a href="#ac2073dc499f56b3a7bbb977f3af13ec0">Modifiers</a>, <a href="#aeecd54c516a16990d6a08d1dd5675305">NativeTypeEnum</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#ae264b7462dfb57a16a94b8f871f52920">llvm::pdb::NativeRawSymbol::Session</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2caa1fa27779242b4902f7ae3bdd5c6d508">llvm::pdb::Type</a> and <a href="#adb4469b960bd11e184cb2cefb91a36e7">UnmodifiedType</a>.</p>

</div>
</div>

### getBuiltinType() {#a6740b5cf37d9355b1f920da35c666d96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PDB_BuiltinType NativeTypeEnum::getBuiltinType ()</td>
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



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>, definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeenum-cpp">NativeTypeEnum.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a29a5bdf367e3f74df9228dfce2c93a6fac26f15e86e3de4c398a8273272aba034">llvm::pdb::Bool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0ab9962d18e5a75035a15ffa4016aebe32">llvm::codeview::Boolean128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0a0579b7f631dc5f934bae30d05c13564b">llvm::codeview::Boolean16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0abd8465c30924b33fa34ee6f14d69fef9">llvm::codeview::Boolean32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0ad046ecdb5d8369142de0e5662bcb87a3">llvm::codeview::Boolean64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0a1765d6985f810a03b9fe55f88a229806">llvm::codeview::Boolean8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a29a5bdf367e3f74df9228dfce2c93a6fa8e95e84813830072b7516cfaa7dbc1a9">llvm::pdb::Char</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a29a5bdf367e3f74df9228dfce2c93a6fa94c7a25562cb140db514fd2458aa6e38">llvm::pdb::Char16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a29a5bdf367e3f74df9228dfce2c93a6fa221653b38aed9471349e9b5449b309f9">llvm::pdb::Char32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a29a5bdf367e3f74df9228dfce2c93a6fae73841b97be8701f8d5b8b6147f55b11">llvm::pdb::Char8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0a1a8fd919b3ff75cf175311d6553ad5ac">llvm::codeview::Character16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0ae44c543adf64f1d4b6814f5e01ffb4bf">llvm::codeview::Character32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0a8eab47c1eb392aa028ad0beadc778f4a">llvm::codeview::Character8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a29a5bdf367e3f74df9228dfce2c93a6fa10b4eb76294b70d7fd6df997ff06edb1">llvm::pdb::Complex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0aee63a91375f038924d9671f9fec7059b">llvm::codeview::Complex128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0a52620ebbb998bb6f0aeaa5b126e391aa">llvm::codeview::Complex16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0a2ef2a9d5fdeebb762c9b0bc85c533ba1">llvm::codeview::Complex32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0a81d9ca073e6149fa6d82d8104224cbff">llvm::codeview::Complex32PartialPrecision</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0ad966dd0f6dc22b834b636fb9df4b756a">llvm::codeview::Complex64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0af7112bb4654b1382acbc2a727b2e16a5">llvm::codeview::Complex80</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9a5c54ae452fcc89ddc0c8d9b7b46caaafd1dd0c603be8170f9eae0be9f2f6afb">llvm::codeview::Direct</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a29a5bdf367e3f74df9228dfce2c93a6fa22ae0e2b89e5e3d477f988cc36d3272b">llvm::pdb::Float</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0ae74f68ddb36c1ed379de92ae3b589d34">llvm::codeview::Float128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0a26e6ed77470c6f2f830ecf874e6c0d55">llvm::codeview::Float16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0a166495adc0d0f53bee6baecc577f5204">llvm::codeview::Float32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0a24049be2051cb0db22f6fd0d05335d98">llvm::codeview::Float32PartialPrecision</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0a93c13843a0587f0cc89e30b1975dd815">llvm::codeview::Float48</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0ad2b556d8a8f5c8ac323f51a4b82e79a0">llvm::codeview::Float64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0a79be58cb7c8c7d476b945d17da96b579">llvm::codeview::Float80</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0ad861e22088ac2204369274eb062f34ed">llvm::codeview::HResult</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a29a5bdf367e3f74df9228dfce2c93a6fad861e22088ac2204369274eb062f34ed">llvm::pdb::HResult</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a29a5bdf367e3f74df9228dfce2c93a6fa1686a6c336b71b36d77354cea19a8b52">llvm::pdb::Int</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0a2af2c985007d8168454cefe7838798a7">llvm::codeview::Int128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0a0f35e518dfdd0896ba935e5157f4f872">llvm::codeview::Int128Oct</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0a39bc2ae44b184207f560ff8619823208">llvm::codeview::Int16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0a3df1f370f51c6d2de3a2c57f5604a514">llvm::codeview::Int16Short</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0ac06129f6e6e15c09328365e553f1dc31">llvm::codeview::Int32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0aa6bb6b57ff24796e4000d4d338387868">llvm::codeview::Int32Long</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0afbde23b11d7e59af7828e81144c8b487">llvm::codeview::Int64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0a1b4399198f4424ef17518b80aa61e3bf">llvm::codeview::Int64Quad</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0ab14654427bdd2fb8bffc9176c9cf307d">llvm::codeview::NarrowCharacter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a29a5bdf367e3f74df9228dfce2c93a6fa6adf97f83acf6453d4a6a4b1070f3754">llvm::pdb::None</a>, <a href="#ae9b2009770f84bad6cb26a7435e84ee0">Record</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#ae264b7462dfb57a16a94b8f871f52920">llvm::pdb::NativeRawSymbol::Session</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0a067e7e972da1751ac8a699cb28abf73f">llvm::codeview::SignedCharacter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a29a5bdf367e3f74df9228dfce2c93a6fa0b1291eded63143ac04709711274785a">llvm::pdb::UInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0a577b8e649cdc5d5e8cbb2a7accde778c">llvm::codeview::UInt128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0aa25048391b45f2ba9c092d4e7419815e">llvm::codeview::UInt128Oct</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0a8bd950a9d7779b83f5c30046c9aaf1cf">llvm::codeview::UInt16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0a59dc9f788c9559d4c8cea60d84002c60">llvm::codeview::UInt16Short</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0ae7956ed7be1c5025a27ed3cb42a396bd">llvm::codeview::UInt32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0ad431840316a4aecfe64d579cea683a15">llvm::codeview::UInt32Long</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0aaf71234725f0470ccf993e263a8b820a">llvm::codeview::UInt64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0af822fdbae327bd6afb6b20bd212db06f">llvm::codeview::UInt64Quad</a>, <a href="#adb4469b960bd11e184cb2cefb91a36e7">UnmodifiedType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0a67bd2dd7142f89c9c679185f8ec100dc">llvm::codeview::UnsignedCharacter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a29a5bdf367e3f74df9228dfce2c93a6fa540cf2133f8c90208ffc2712ee161213">llvm::pdb::WCharT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9cf141c9194799e2fa2d92de4c6e8ff0a615eb16f961ec5095ff1c6ef68564431">llvm::codeview::WideCharacter</a>.</p>


<p>Referenced by <a href="#a39e505f7c57048ad10d23dc4f17ae413">dump</a>.</p>

</div>
</div>

### getEnumRecord() {#a88121fdf4b0993d40f77a6a17eca0f1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const codeview::EnumRecord &amp; llvm::pdb::NativeTypeEnum::getEnumRecord ()</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>.</p>


<p>Reference <a href="#ae9b2009770f84bad6cb26a7435e84ee0">Record</a>.</p>

</div>
</div>

### getLength() {#ae17a24ecd19908de92b5a124a8cc57e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t NativeTypeEnum::getLength ()</td>
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



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>, definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeenum-cpp">NativeTypeEnum.cpp</a>.</p>


<p>References <a href="#ae9b2009770f84bad6cb26a7435e84ee0">Record</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#ae264b7462dfb57a16a94b8f871f52920">llvm::pdb::NativeRawSymbol::Session</a> and <a href="#adb4469b960bd11e184cb2cefb91a36e7">UnmodifiedType</a>.</p>


<p>Referenced by <a href="#a39e505f7c57048ad10d23dc4f17ae413">dump</a>.</p>

</div>
</div>

### getName() {#a202da4841ffeab82ffdd34d5d7d2e437}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string NativeTypeEnum::getName ()</td>
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



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>, definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeenum-cpp">NativeTypeEnum.cpp</a>.</p>


<p>References <a href="#ae9b2009770f84bad6cb26a7435e84ee0">Record</a> and <a href="#adb4469b960bd11e184cb2cefb91a36e7">UnmodifiedType</a>.</p>


<p>Referenced by <a href="#a39e505f7c57048ad10d23dc4f17ae413">dump</a>.</p>

</div>
</div>

### getSymTag() {#ab9cd11b93297fb4fb411bfab0d5b4328}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PDB_SymType NativeTypeEnum::getSymTag ()</td>
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



<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>, definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeenum-cpp">NativeTypeEnum.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30bacf20423ed48998082c20099488a0917c">llvm::pdb::Enum</a>.</p>

</div>
</div>

### getTypeId() {#a7745bb6af8fabffdc34df8866af3f5ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymIndexId NativeTypeEnum::getTypeId ()</td>
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



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>, definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeenum-cpp">NativeTypeEnum.cpp</a>.</p>


<p>References <a href="#ae9b2009770f84bad6cb26a7435e84ee0">Record</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#ae264b7462dfb57a16a94b8f871f52920">llvm::pdb::NativeRawSymbol::Session</a> and <a href="#adb4469b960bd11e184cb2cefb91a36e7">UnmodifiedType</a>.</p>


<p>Referenced by <a href="#a39e505f7c57048ad10d23dc4f17ae413">dump</a> and <a href="#aae2a46e82210ad08b02e14c261089988">getUnderlyingBuiltinType</a>.</p>

</div>
</div>

### getUnderlyingBuiltinType() {#aae2a46e82210ad08b02e14c261089988}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const NativeTypeBuiltin &amp; NativeTypeEnum::getUnderlyingBuiltinType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>, definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeenum-cpp">NativeTypeEnum.cpp</a>.</p>


<p>References <a href="#a7745bb6af8fabffdc34df8866af3f5ea">getTypeId</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#ae264b7462dfb57a16a94b8f871f52920">llvm::pdb::NativeRawSymbol::Session</a> and <a href="#adb4469b960bd11e184cb2cefb91a36e7">UnmodifiedType</a>.</p>

</div>
</div>

### getUnmodifiedTypeId() {#abfc600899131b1858375398069d2f604}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymIndexId NativeTypeEnum::getUnmodifiedTypeId ()</td>
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



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>, definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeenum-cpp">NativeTypeEnum.cpp</a>.</p>


<p>Reference <a href="#adb4469b960bd11e184cb2cefb91a36e7">UnmodifiedType</a>.</p>


<p>Referenced by <a href="#a39e505f7c57048ad10d23dc4f17ae413">dump</a>.</p>

</div>
</div>

### hasAssignmentOperator() {#a44aaba2293cab5d22146b49c596721c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeEnum::hasAssignmentOperator ()</td>
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



<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>, definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeenum-cpp">NativeTypeEnum.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa8c104df916cac8868cd4e82cccb8adb2">llvm::codeview::HasOverloadedAssignmentOperator</a>, <a href="#ae9b2009770f84bad6cb26a7435e84ee0">Record</a> and <a href="#adb4469b960bd11e184cb2cefb91a36e7">UnmodifiedType</a>.</p>


<p>Referenced by <a href="#a39e505f7c57048ad10d23dc4f17ae413">dump</a>.</p>

</div>
</div>

### hasCastOperator() {#a624f209ee7f18171bad690f32b13b977}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeEnum::hasCastOperator ()</td>
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



<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>, definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeenum-cpp">NativeTypeEnum.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aadb77a6e068212caaabc47dbf4cab280f">llvm::codeview::HasConversionOperator</a>, <a href="#ae9b2009770f84bad6cb26a7435e84ee0">Record</a> and <a href="#adb4469b960bd11e184cb2cefb91a36e7">UnmodifiedType</a>.</p>


<p>Referenced by <a href="#a39e505f7c57048ad10d23dc4f17ae413">dump</a>.</p>

</div>
</div>

### hasConstructor() {#a703661603296b069f5589b14383d8296}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeEnum::hasConstructor ()</td>
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



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>, definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeenum-cpp">NativeTypeEnum.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa6df427d10ced170429c407317356800c">llvm::codeview::HasConstructorOrDestructor</a>, <a href="#ae9b2009770f84bad6cb26a7435e84ee0">Record</a> and <a href="#adb4469b960bd11e184cb2cefb91a36e7">UnmodifiedType</a>.</p>


<p>Referenced by <a href="#a39e505f7c57048ad10d23dc4f17ae413">dump</a>.</p>

</div>
</div>

### hasNestedTypes() {#ab8e421cd983eff100ffa5f614534476d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeEnum::hasNestedTypes ()</td>
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



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>, definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeenum-cpp">NativeTypeEnum.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa7f67a4011b21d9ae7471351c38db2597">llvm::codeview::ContainsNestedClass</a>, <a href="#ae9b2009770f84bad6cb26a7435e84ee0">Record</a> and <a href="#adb4469b960bd11e184cb2cefb91a36e7">UnmodifiedType</a>.</p>


<p>Referenced by <a href="#a39e505f7c57048ad10d23dc4f17ae413">dump</a>.</p>

</div>
</div>

### hasOverloadedOperator() {#a0c9dab0e0959f1f91aa7e18713e3058e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeEnum::hasOverloadedOperator ()</td>
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



<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>, definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeenum-cpp">NativeTypeEnum.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa6c7813302cb4e344823952999dd52859">llvm::codeview::HasOverloadedOperator</a>, <a href="#ae9b2009770f84bad6cb26a7435e84ee0">Record</a> and <a href="#adb4469b960bd11e184cb2cefb91a36e7">UnmodifiedType</a>.</p>


<p>Referenced by <a href="#a39e505f7c57048ad10d23dc4f17ae413">dump</a>.</p>

</div>
</div>

### isConstType() {#a82a0ade551d4350577ccc04bdc68e65b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeEnum::isConstType ()</td>
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



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>, definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeenum-cpp">NativeTypeEnum.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#acf5c2920c8a10eeb1d8c5d3a9c2adfb6a79ceee9f8e3c1f0cc74223e05d2448bf">llvm::codeview::Const</a>, <a href="#ac2073dc499f56b3a7bbb977f3af13ec0">Modifiers</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#acf5c2920c8a10eeb1d8c5d3a9c2adfb6a6adf97f83acf6453d4a6a4b1070f3754">llvm::codeview::None</a>.</p>


<p>Referenced by <a href="#a39e505f7c57048ad10d23dc4f17ae413">dump</a>.</p>

</div>
</div>

### isInterfaceUdt() {#a60328cfef7d687f69c4e5e4a1bc65209}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeEnum::isInterfaceUdt ()</td>
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



<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>, definition at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeenum-cpp">NativeTypeEnum.cpp</a>.</p>


<p>Referenced by <a href="#a39e505f7c57048ad10d23dc4f17ae413">dump</a>.</p>

</div>
</div>

### isIntrinsic() {#a107b373b7b70ab47c03b52193867beac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeEnum::isIntrinsic ()</td>
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



<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>, definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeenum-cpp">NativeTypeEnum.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa8b0f368e62695dc13b998050ea15a2c5">llvm::codeview::Intrinsic</a>, <a href="#ae9b2009770f84bad6cb26a7435e84ee0">Record</a> and <a href="#adb4469b960bd11e184cb2cefb91a36e7">UnmodifiedType</a>.</p>


<p>Referenced by <a href="#a39e505f7c57048ad10d23dc4f17ae413">dump</a>.</p>

</div>
</div>

### isNested() {#a523b10b95d962cd80d62711789582a97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeEnum::isNested ()</td>
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



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>, definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeenum-cpp">NativeTypeEnum.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa13c479c348969ab459513a4bfd559bb9">llvm::codeview::Nested</a>, <a href="#ae9b2009770f84bad6cb26a7435e84ee0">Record</a> and <a href="#adb4469b960bd11e184cb2cefb91a36e7">UnmodifiedType</a>.</p>


<p>Referenced by <a href="#a39e505f7c57048ad10d23dc4f17ae413">dump</a>.</p>

</div>
</div>

### isPacked() {#a1d1b8bde8a25d7083e4192ff905050e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeEnum::isPacked ()</td>
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



<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>, definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeenum-cpp">NativeTypeEnum.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aaa1977c3f68d4d3bbfe14d0e51a575482">llvm::codeview::Packed</a>, <a href="#ae9b2009770f84bad6cb26a7435e84ee0">Record</a> and <a href="#adb4469b960bd11e184cb2cefb91a36e7">UnmodifiedType</a>.</p>


<p>Referenced by <a href="#a39e505f7c57048ad10d23dc4f17ae413">dump</a>.</p>

</div>
</div>

### isRefUdt() {#aee6102ad51e6b3f3771759a377a51863}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeEnum::isRefUdt ()</td>
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



<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>, definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeenum-cpp">NativeTypeEnum.cpp</a>.</p>


<p>Referenced by <a href="#a39e505f7c57048ad10d23dc4f17ae413">dump</a>.</p>

</div>
</div>

### isScoped() {#a02e4ff01cce049ff9ec4eb0fc47514e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeEnum::isScoped ()</td>
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



<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>, definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeenum-cpp">NativeTypeEnum.cpp</a>.</p>


<p>References <a href="#ae9b2009770f84bad6cb26a7435e84ee0">Record</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa423f62fd0413b98ab4dd487ec060e628">llvm::codeview::Scoped</a> and <a href="#adb4469b960bd11e184cb2cefb91a36e7">UnmodifiedType</a>.</p>


<p>Referenced by <a href="#a39e505f7c57048ad10d23dc4f17ae413">dump</a>.</p>

</div>
</div>

### isUnalignedType() {#a5a4979af44394e318626ee259916b797}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeEnum::isUnalignedType ()</td>
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



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>, definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeenum-cpp">NativeTypeEnum.cpp</a>.</p>


<p>References <a href="#ac2073dc499f56b3a7bbb977f3af13ec0">Modifiers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#acf5c2920c8a10eeb1d8c5d3a9c2adfb6a6adf97f83acf6453d4a6a4b1070f3754">llvm::codeview::None</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#acf5c2920c8a10eeb1d8c5d3a9c2adfb6a9f19679888db198f8dd45606487e6cd6">llvm::codeview::Unaligned</a>.</p>


<p>Referenced by <a href="#a39e505f7c57048ad10d23dc4f17ae413">dump</a>.</p>

</div>
</div>

### isValueUdt() {#a58ef4452d1fcca9848c6e7a66421e364}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeEnum::isValueUdt ()</td>
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



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>, definition at line 355 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeenum-cpp">NativeTypeEnum.cpp</a>.</p>


<p>Referenced by <a href="#a39e505f7c57048ad10d23dc4f17ae413">dump</a>.</p>

</div>
</div>

### isVolatileType() {#a029aa26195d123c47100fd564a850d03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeEnum::isVolatileType ()</td>
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



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>, definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeenum-cpp">NativeTypeEnum.cpp</a>.</p>


<p>References <a href="#ac2073dc499f56b3a7bbb977f3af13ec0">Modifiers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#acf5c2920c8a10eeb1d8c5d3a9c2adfb6a6adf97f83acf6453d4a6a4b1070f3754">llvm::codeview::None</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#acf5c2920c8a10eeb1d8c5d3a9c2adfb6a3e3af98b6b48c7e593d8d18863e3333b">llvm::codeview::Volatile</a>.</p>


<p>Referenced by <a href="#a39e505f7c57048ad10d23dc4f17ae413">dump</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Index {#a0006e4521304048708c8e8085882725a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">codeview::TypeIndex llvm::pdb::NativeTypeEnum::Index</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>.</p>


<p>Referenced by <a href="#aeecd54c516a16990d6a08d1dd5675305">NativeTypeEnum</a>.</p>

</div>
</div>

### Modifiers {#ac2073dc499f56b3a7bbb977f3af13ec0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;codeview::ModifierRecord&gt; llvm::pdb::NativeTypeEnum::Modifiers</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>.</p>


<p>Referenced by <a href="#a39e505f7c57048ad10d23dc4f17ae413">dump</a>, <a href="#a616dd528c581972135480eb7b13dceca">findChildren</a>, <a href="#a82a0ade551d4350577ccc04bdc68e65b">isConstType</a>, <a href="#a5a4979af44394e318626ee259916b797">isUnalignedType</a>, <a href="#a029aa26195d123c47100fd564a850d03">isVolatileType</a> and <a href="#a314f3fab5f60ce72b855e5d138e8a1bf">NativeTypeEnum</a>.</p>

</div>
</div>

### Record {#ae9b2009770f84bad6cb26a7435e84ee0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;codeview::EnumRecord&gt; llvm::pdb::NativeTypeEnum::Record</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>.</p>


<p>Referenced by <a href="#a6740b5cf37d9355b1f920da35c666d96">getBuiltinType</a>, <a href="#a88121fdf4b0993d40f77a6a17eca0f1d">getEnumRecord</a>, <a href="#ae17a24ecd19908de92b5a124a8cc57e6">getLength</a>, <a href="#a202da4841ffeab82ffdd34d5d7d2e437">getName</a>, <a href="#a7745bb6af8fabffdc34df8866af3f5ea">getTypeId</a>, <a href="#a44aaba2293cab5d22146b49c596721c6">hasAssignmentOperator</a>, <a href="#a624f209ee7f18171bad690f32b13b977">hasCastOperator</a>, <a href="#a703661603296b069f5589b14383d8296">hasConstructor</a>, <a href="#ab8e421cd983eff100ffa5f614534476d">hasNestedTypes</a>, <a href="#a0c9dab0e0959f1f91aa7e18713e3058e">hasOverloadedOperator</a>, <a href="#a107b373b7b70ab47c03b52193867beac">isIntrinsic</a>, <a href="#a523b10b95d962cd80d62711789582a97">isNested</a>, <a href="#a1d1b8bde8a25d7083e4192ff905050e2">isPacked</a>, <a href="#a02e4ff01cce049ff9ec4eb0fc47514e9">isScoped</a> and <a href="#aeecd54c516a16990d6a08d1dd5675305">NativeTypeEnum</a>.</p>

</div>
</div>

### UnmodifiedType {#adb4469b960bd11e184cb2cefb91a36e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NativeTypeEnum* llvm::pdb::NativeTypeEnum::UnmodifiedType = nullptr</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a>.</p>


<p>Referenced by <a href="#a616dd528c581972135480eb7b13dceca">findChildren</a>, <a href="#a6740b5cf37d9355b1f920da35c666d96">getBuiltinType</a>, <a href="#ae17a24ecd19908de92b5a124a8cc57e6">getLength</a>, <a href="#a202da4841ffeab82ffdd34d5d7d2e437">getName</a>, <a href="#a7745bb6af8fabffdc34df8866af3f5ea">getTypeId</a>, <a href="#aae2a46e82210ad08b02e14c261089988">getUnderlyingBuiltinType</a>, <a href="#abfc600899131b1858375398069d2f604">getUnmodifiedTypeId</a>, <a href="#a44aaba2293cab5d22146b49c596721c6">hasAssignmentOperator</a>, <a href="#a624f209ee7f18171bad690f32b13b977">hasCastOperator</a>, <a href="#a703661603296b069f5589b14383d8296">hasConstructor</a>, <a href="#ab8e421cd983eff100ffa5f614534476d">hasNestedTypes</a>, <a href="#a0c9dab0e0959f1f91aa7e18713e3058e">hasOverloadedOperator</a>, <a href="#a107b373b7b70ab47c03b52193867beac">isIntrinsic</a>, <a href="#a523b10b95d962cd80d62711789582a97">isNested</a>, <a href="#a1d1b8bde8a25d7083e4192ff905050e2">isPacked</a>, <a href="#a02e4ff01cce049ff9ec4eb0fc47514e9">isScoped</a> and <a href="#a314f3fab5f60ce72b855e5d138e8a1bf">NativeTypeEnum</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">NativeTypeEnum.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypeenum-cpp">NativeTypeEnum.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
