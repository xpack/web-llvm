---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pdb/nativetypepointer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `NativeTypePointer` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::pdb::NativeTypePointer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypepointer-h">llvm/DebugInfo/PDB/Native/NativeTypePointer.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab505cfbd671a4ca4db53adda746f04ad">NativeTypePointer</a> (NativeSession &amp;Session, SymIndexId Id, codeview::TypeIndex TI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c55b42ed0eae4232518eb7911e4527b">NativeTypePointer</a> (NativeSession &amp;Session, SymIndexId Id, codeview::TypeIndex TI, codeview::PointerRecord PR)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5429597efbdd652c1552340981ea852d">~NativeTypePointer</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a345422190d7931ba8f40e98dcf8e75b0">dump</a> (raw_ostream &amp;OS, int Indent, PdbSymbolIdField ShowIdFields, PdbSymbolIdField RecurseIdFields) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4805d5612b80e0d248c3ddc1a2997a95">getClassParentId</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65827bd953d4215dd6c5635cd9577a13">isConstType</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac94623caedbca7f9d08757406113097e">getLength</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5491839bc80efcb86c57f2d102432f18">isReference</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaad1bb64a5fe6dfe831822aa51d119a8">isRValueReference</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f75e0676f94c37de3f6d8682a77c5d6">isPointerToDataMember</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a424b3b1c390e74a8177b087699bcd22c">isPointerToMemberFunction</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a0e930306877fcde9ec2d6b9e9abd15">getTypeId</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb1f0b3a5fc18615a2e91380fc58ba1b">isRestrictedType</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac78738977ee6d3500698798e7ee69b64">isVolatileType</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5d9e48c7b104c0bd45fe643a8e12891">isUnalignedType</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dcf96a969eb7a017c7ee193e226ce3c">isSingleInheritance</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7253f2536c2db48120492b1b078ca0f4">isMultipleInheritance</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e925cb23beb9c7f21317f0905151a49">isVirtualInheritance</a> () const override</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7e4a7228eb6759f0a31c4befccf8019">isMemberPointer</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90bb92a5920a90c1263efc52a320a130">TI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/codeview/pointerrecord">codeview::PointerRecord</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeab0af506bd57a8fb15cae29a3309ed7">Record</a></td>
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


<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypepointer-h">NativeTypePointer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### NativeTypePointer() {#ab505cfbd671a4ca4db53adda746f04ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NativeTypePointer::NativeTypePointer (<a href="/web-llvm/docs/api/classes/llvm/pdb/nativesession">NativeSession</a> &amp; Session, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a0d95a0af7fff523a0a4bfb7f6b578d12">SymIndexId</a> Id, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a> TI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypepointer-h">NativeTypePointer.h</a>, definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypepointer-cpp">NativeTypePointer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9a5c54ae452fcc89ddc0c8d9b7b46caaafd1dd0c603be8170f9eae0be9f2f6afb">llvm::codeview::Direct</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#a4cbeed8a0b429b5aea245873a199f97b">llvm::pdb::NativeRawSymbol::NativeRawSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30bae385c38bb67ea909198e13ee23c21028">llvm::pdb::PointerType</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#ae264b7462dfb57a16a94b8f871f52920">llvm::pdb::NativeRawSymbol::Session</a> and <a href="#a90bb92a5920a90c1263efc52a320a130">TI</a>.</p>

</div>
</div>

### NativeTypePointer() {#a6c55b42ed0eae4232518eb7911e4527b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NativeTypePointer::NativeTypePointer (<a href="/web-llvm/docs/api/classes/llvm/pdb/nativesession">NativeSession</a> &amp; Session, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a0d95a0af7fff523a0a4bfb7f6b578d12">SymIndexId</a> Id, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">codeview::TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/codeview/pointerrecord">codeview::PointerRecord</a> PR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypepointer-h">NativeTypePointer.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypepointer-cpp">NativeTypePointer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#a4cbeed8a0b429b5aea245873a199f97b">llvm::pdb::NativeRawSymbol::NativeRawSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30bae385c38bb67ea909198e13ee23c21028">llvm::pdb::PointerType</a>, <a href="#aeab0af506bd57a8fb15cae29a3309ed7">Record</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#ae264b7462dfb57a16a94b8f871f52920">llvm::pdb::NativeRawSymbol::Session</a> and <a href="#a90bb92a5920a90c1263efc52a320a130">TI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~NativeTypePointer() {#a5429597efbdd652c1552340981ea852d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NativeTypePointer::~NativeTypePointer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypepointer-h">NativeTypePointer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a345422190d7931ba8f40e98dcf8e75b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NativeTypePointer::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, int Indent, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2c">PdbSymbolIdField</a> ShowIdFields, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2c">PdbSymbolIdField</a> RecurseIdFields)</td>
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



<p>Declaration at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypepointer-h">NativeTypePointer.h</a>, definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypepointer-cpp">NativeTypePointer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2ca5ec2b91b4f21888ae4a157c15d806941">llvm::pdb::ClassParent</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#aeeda1eb1da6fda8318d0a3093caa3ea2">llvm::pdb::NativeRawSymbol::dump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a28e0e7c7f7920e3608fea13ec3e4394e">llvm::pdb::dumpSymbolField</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#aebe60f61f4fe8956834c561bfb8a75e8">llvm::pdb::dumpSymbolIdField</a>, <a href="#a4805d5612b80e0d248c3ddc1a2997a95">getClassParentId</a>, <a href="#ac94623caedbca7f9d08757406113097e">getLength</a>, <a href="#a0a0e930306877fcde9ec2d6b9e9abd15">getTypeId</a>, <a href="#a65827bd953d4215dd6c5635cd9577a13">isConstType</a>, <a href="#aa7e4a7228eb6759f0a31c4befccf8019">isMemberPointer</a>, <a href="#a7253f2536c2db48120492b1b078ca0f4">isMultipleInheritance</a>, <a href="#a1f75e0676f94c37de3f6d8682a77c5d6">isPointerToDataMember</a>, <a href="#a424b3b1c390e74a8177b087699bcd22c">isPointerToMemberFunction</a>, <a href="#a5491839bc80efcb86c57f2d102432f18">isReference</a>, <a href="#aeb1f0b3a5fc18615a2e91380fc58ba1b">isRestrictedType</a>, <a href="#aaad1bb64a5fe6dfe831822aa51d119a8">isRValueReference</a>, <a href="#a6dcf96a969eb7a017c7ee193e226ce3c">isSingleInheritance</a>, <a href="#ab5d9e48c7b104c0bd45fe643a8e12891">isUnalignedType</a>, <a href="#a5e925cb23beb9c7f21317f0905151a49">isVirtualInheritance</a>, <a href="#ac78738977ee6d3500698798e7ee69b64">isVolatileType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2ca0a31053bfd7ad7db33f78a8c31f4c99a">llvm::pdb::LexicalParent</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#ae264b7462dfb57a16a94b8f871f52920">llvm::pdb::NativeRawSymbol::Session</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2caa1fa27779242b4902f7ae3bdd5c6d508">llvm::pdb::Type</a>.</p>

</div>
</div>

### getClassParentId() {#a4805d5612b80e0d248c3ddc1a2997a95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymIndexId NativeTypePointer::getClassParentId ()</td>
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



<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypepointer-h">NativeTypePointer.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypepointer-cpp">NativeTypePointer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/memberpointerinfo/#aa62149c3c6a779f5fc77447390ccfc5f">llvm::codeview::MemberPointerInfo::ContainingType</a>, <a href="#aa7e4a7228eb6759f0a31c4befccf8019">isMemberPointer</a>, <a href="#aeab0af506bd57a8fb15cae29a3309ed7">Record</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#ae264b7462dfb57a16a94b8f871f52920">llvm::pdb::NativeRawSymbol::Session</a>.</p>


<p>Referenced by <a href="#a345422190d7931ba8f40e98dcf8e75b0">dump</a>.</p>

</div>
</div>

### getLength() {#ac94623caedbca7f9d08757406113097e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t NativeTypePointer::getLength ()</td>
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



<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypepointer-h">NativeTypePointer.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypepointer-cpp">NativeTypePointer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9a5c54ae452fcc89ddc0c8d9b7b46caaa50b45f9cd686e534d40ffce8247c33de">llvm::codeview::FarPointer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9a5c54ae452fcc89ddc0c8d9b7b46caaa88173e475c2c0f2897927bf66c470336">llvm::codeview::FarPointer32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9a5c54ae452fcc89ddc0c8d9b7b46caaaae71736521fce2dc51ce0fe09f468f3b">llvm::codeview::HugePointer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9a5c54ae452fcc89ddc0c8d9b7b46caaa02027bfdc30a94b3403f55272734cfa6">llvm::codeview::NearPointer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9a5c54ae452fcc89ddc0c8d9b7b46caaa9290f95435c323f951e081836e89f2e4">llvm::codeview::NearPointer128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9a5c54ae452fcc89ddc0c8d9b7b46caaadc6b5357b616d34a07d679a56ad90aba">llvm::codeview::NearPointer32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a9a5c54ae452fcc89ddc0c8d9b7b46caaa6b5cf2c011b307b6427f284c7423a769">llvm::codeview::NearPointer64</a>, <a href="#aeab0af506bd57a8fb15cae29a3309ed7">Record</a> and <a href="#a90bb92a5920a90c1263efc52a320a130">TI</a>.</p>


<p>Referenced by <a href="#a345422190d7931ba8f40e98dcf8e75b0">dump</a>.</p>

</div>
</div>

### getTypeId() {#a0a0e930306877fcde9ec2d6b9e9abd15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymIndexId NativeTypePointer::getTypeId ()</td>
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



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypepointer-h">NativeTypePointer.h</a>, definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypepointer-cpp">NativeTypePointer.cpp</a>.</p>


<p>References <a href="#aeab0af506bd57a8fb15cae29a3309ed7">Record</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#ae264b7462dfb57a16a94b8f871f52920">llvm::pdb::NativeRawSymbol::Session</a> and <a href="#a90bb92a5920a90c1263efc52a320a130">TI</a>.</p>


<p>Referenced by <a href="#a345422190d7931ba8f40e98dcf8e75b0">dump</a>.</p>

</div>
</div>

### isConstType() {#a65827bd953d4215dd6c5635cd9577a13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypePointer::isConstType ()</td>
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



<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypepointer-h">NativeTypePointer.h</a>, definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypepointer-cpp">NativeTypePointer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0d7ea7b04f6f732cebed0f7c6ea4609fa79ceee9f8e3c1f0cc74223e05d2448bf">llvm::codeview::Const</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0d7ea7b04f6f732cebed0f7c6ea4609fa6adf97f83acf6453d4a6a4b1070f3754">llvm::codeview::None</a> and <a href="#aeab0af506bd57a8fb15cae29a3309ed7">Record</a>.</p>


<p>Referenced by <a href="#a345422190d7931ba8f40e98dcf8e75b0">dump</a>.</p>

</div>
</div>

### isMultipleInheritance() {#a7253f2536c2db48120492b1b078ca0f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypePointer::isMultipleInheritance ()</td>
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



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypepointer-h">NativeTypePointer.h</a>, definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypepointer-cpp">NativeTypePointer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypepointer-cpp/#af995a520ba652927c52b4134ed4da88b">isInheritanceKind</a>, <a href="#aa7e4a7228eb6759f0a31c4befccf8019">isMemberPointer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a524c6566f0266fbbbe1c7ed25882c7dda0f5e1c8100349251b6d196f7a29b0315">llvm::codeview::MultipleInheritanceData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a524c6566f0266fbbbe1c7ed25882c7ddac89e9e73f5a2136281e232659e0dbeb8">llvm::codeview::MultipleInheritanceFunction</a> and <a href="#aeab0af506bd57a8fb15cae29a3309ed7">Record</a>.</p>


<p>Referenced by <a href="#a345422190d7931ba8f40e98dcf8e75b0">dump</a>.</p>

</div>
</div>

### isPointerToDataMember() {#a1f75e0676f94c37de3f6d8682a77c5d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypePointer::isPointerToDataMember ()</td>
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



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypepointer-h">NativeTypePointer.h</a>, definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypepointer-cpp">NativeTypePointer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0bfa8e65ecd85f3151f84bb53ad4bcbcaadf8be6fd2059290188a2c4b791edcd1">llvm::codeview::PointerToDataMember</a> and <a href="#aeab0af506bd57a8fb15cae29a3309ed7">Record</a>.</p>


<p>Referenced by <a href="#a345422190d7931ba8f40e98dcf8e75b0">dump</a> and <a href="#aa7e4a7228eb6759f0a31c4befccf8019">isMemberPointer</a>.</p>

</div>
</div>

### isPointerToMemberFunction() {#a424b3b1c390e74a8177b087699bcd22c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypePointer::isPointerToMemberFunction ()</td>
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



<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypepointer-h">NativeTypePointer.h</a>, definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypepointer-cpp">NativeTypePointer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0bfa8e65ecd85f3151f84bb53ad4bcbcada5a6fc5693ed8a5e467c414ca2589d3">llvm::codeview::PointerToMemberFunction</a> and <a href="#aeab0af506bd57a8fb15cae29a3309ed7">Record</a>.</p>


<p>Referenced by <a href="#a345422190d7931ba8f40e98dcf8e75b0">dump</a> and <a href="#aa7e4a7228eb6759f0a31c4befccf8019">isMemberPointer</a>.</p>

</div>
</div>

### isReference() {#a5491839bc80efcb86c57f2d102432f18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypePointer::isReference ()</td>
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



<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypepointer-h">NativeTypePointer.h</a>, definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypepointer-cpp">NativeTypePointer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0bfa8e65ecd85f3151f84bb53ad4bcbca3408011d07d71eb98afa178eae72faf6">llvm::codeview::LValueReference</a> and <a href="#aeab0af506bd57a8fb15cae29a3309ed7">Record</a>.</p>


<p>Referenced by <a href="#a345422190d7931ba8f40e98dcf8e75b0">dump</a>.</p>

</div>
</div>

### isRestrictedType() {#aeb1f0b3a5fc18615a2e91380fc58ba1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypePointer::isRestrictedType ()</td>
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



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypepointer-h">NativeTypePointer.h</a>, definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypepointer-cpp">NativeTypePointer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0d7ea7b04f6f732cebed0f7c6ea4609fa6adf97f83acf6453d4a6a4b1070f3754">llvm::codeview::None</a>, <a href="#aeab0af506bd57a8fb15cae29a3309ed7">Record</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0d7ea7b04f6f732cebed0f7c6ea4609fa034d70b46e41ec9d0306b0001e04cae7">llvm::codeview::Restrict</a>.</p>


<p>Referenced by <a href="#a345422190d7931ba8f40e98dcf8e75b0">dump</a>.</p>

</div>
</div>

### isRValueReference() {#aaad1bb64a5fe6dfe831822aa51d119a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypePointer::isRValueReference ()</td>
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



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypepointer-h">NativeTypePointer.h</a>, definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypepointer-cpp">NativeTypePointer.cpp</a>.</p>


<p>References <a href="#aeab0af506bd57a8fb15cae29a3309ed7">Record</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0bfa8e65ecd85f3151f84bb53ad4bcbcaa68a3262ced5b445f2a5a1953c279116">llvm::codeview::RValueReference</a>.</p>


<p>Referenced by <a href="#a345422190d7931ba8f40e98dcf8e75b0">dump</a>.</p>

</div>
</div>

### isSingleInheritance() {#a6dcf96a969eb7a017c7ee193e226ce3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypePointer::isSingleInheritance ()</td>
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



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypepointer-h">NativeTypePointer.h</a>, definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypepointer-cpp">NativeTypePointer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypepointer-cpp/#af995a520ba652927c52b4134ed4da88b">isInheritanceKind</a>, <a href="#aa7e4a7228eb6759f0a31c4befccf8019">isMemberPointer</a>, <a href="#aeab0af506bd57a8fb15cae29a3309ed7">Record</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a524c6566f0266fbbbe1c7ed25882c7dda5d5e503ea7e7e734efc707b38c164bb4">llvm::codeview::SingleInheritanceData</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a524c6566f0266fbbbe1c7ed25882c7dda9ab2da5a8aa252c06b75d66a98037c6b">llvm::codeview::SingleInheritanceFunction</a>.</p>


<p>Referenced by <a href="#a345422190d7931ba8f40e98dcf8e75b0">dump</a>.</p>

</div>
</div>

### isUnalignedType() {#ab5d9e48c7b104c0bd45fe643a8e12891}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypePointer::isUnalignedType ()</td>
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



<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypepointer-h">NativeTypePointer.h</a>, definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypepointer-cpp">NativeTypePointer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0d7ea7b04f6f732cebed0f7c6ea4609fa6adf97f83acf6453d4a6a4b1070f3754">llvm::codeview::None</a>, <a href="#aeab0af506bd57a8fb15cae29a3309ed7">Record</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0d7ea7b04f6f732cebed0f7c6ea4609fa9f19679888db198f8dd45606487e6cd6">llvm::codeview::Unaligned</a>.</p>


<p>Referenced by <a href="#a345422190d7931ba8f40e98dcf8e75b0">dump</a>.</p>

</div>
</div>

### isVirtualInheritance() {#a5e925cb23beb9c7f21317f0905151a49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypePointer::isVirtualInheritance ()</td>
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



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypepointer-h">NativeTypePointer.h</a>, definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypepointer-cpp">NativeTypePointer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypepointer-cpp/#af995a520ba652927c52b4134ed4da88b">isInheritanceKind</a>, <a href="#aa7e4a7228eb6759f0a31c4befccf8019">isMemberPointer</a>, <a href="#aeab0af506bd57a8fb15cae29a3309ed7">Record</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a524c6566f0266fbbbe1c7ed25882c7ddab1504b8da65a6f6504fa211e8e1bc4c6">llvm::codeview::VirtualInheritanceData</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a524c6566f0266fbbbe1c7ed25882c7ddac657f976c7aad6a49765e9e15d0e954a">llvm::codeview::VirtualInheritanceFunction</a>.</p>


<p>Referenced by <a href="#a345422190d7931ba8f40e98dcf8e75b0">dump</a>.</p>

</div>
</div>

### isVolatileType() {#ac78738977ee6d3500698798e7ee69b64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypePointer::isVolatileType ()</td>
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



<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypepointer-h">NativeTypePointer.h</a>, definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypepointer-cpp">NativeTypePointer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0d7ea7b04f6f732cebed0f7c6ea4609fa6adf97f83acf6453d4a6a4b1070f3754">llvm::codeview::None</a>, <a href="#aeab0af506bd57a8fb15cae29a3309ed7">Record</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0d7ea7b04f6f732cebed0f7c6ea4609fa3e3af98b6b48c7e593d8d18863e3333b">llvm::codeview::Volatile</a>.</p>


<p>Referenced by <a href="#a345422190d7931ba8f40e98dcf8e75b0">dump</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### isMemberPointer() {#aa7e4a7228eb6759f0a31c4befccf8019}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypePointer::isMemberPointer ()</td>
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



<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypepointer-h">NativeTypePointer.h</a>, definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypepointer-cpp">NativeTypePointer.cpp</a>.</p>


<p>References <a href="#a1f75e0676f94c37de3f6d8682a77c5d6">isPointerToDataMember</a> and <a href="#a424b3b1c390e74a8177b087699bcd22c">isPointerToMemberFunction</a>.</p>


<p>Referenced by <a href="#a345422190d7931ba8f40e98dcf8e75b0">dump</a>, <a href="#a4805d5612b80e0d248c3ddc1a2997a95">getClassParentId</a>, <a href="#a7253f2536c2db48120492b1b078ca0f4">isMultipleInheritance</a>, <a href="#a6dcf96a969eb7a017c7ee193e226ce3c">isSingleInheritance</a> and <a href="#a5e925cb23beb9c7f21317f0905151a49">isVirtualInheritance</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Record {#aeab0af506bd57a8fb15cae29a3309ed7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;codeview::PointerRecord&gt; llvm::pdb::NativeTypePointer::Record</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypepointer-h">NativeTypePointer.h</a>.</p>


<p>Referenced by <a href="#a4805d5612b80e0d248c3ddc1a2997a95">getClassParentId</a>, <a href="#ac94623caedbca7f9d08757406113097e">getLength</a>, <a href="#a0a0e930306877fcde9ec2d6b9e9abd15">getTypeId</a>, <a href="#a65827bd953d4215dd6c5635cd9577a13">isConstType</a>, <a href="#a7253f2536c2db48120492b1b078ca0f4">isMultipleInheritance</a>, <a href="#a1f75e0676f94c37de3f6d8682a77c5d6">isPointerToDataMember</a>, <a href="#a424b3b1c390e74a8177b087699bcd22c">isPointerToMemberFunction</a>, <a href="#a5491839bc80efcb86c57f2d102432f18">isReference</a>, <a href="#aeb1f0b3a5fc18615a2e91380fc58ba1b">isRestrictedType</a>, <a href="#aaad1bb64a5fe6dfe831822aa51d119a8">isRValueReference</a>, <a href="#a6dcf96a969eb7a017c7ee193e226ce3c">isSingleInheritance</a>, <a href="#ab5d9e48c7b104c0bd45fe643a8e12891">isUnalignedType</a>, <a href="#a5e925cb23beb9c7f21317f0905151a49">isVirtualInheritance</a>, <a href="#ac78738977ee6d3500698798e7ee69b64">isVolatileType</a> and <a href="#a6c55b42ed0eae4232518eb7911e4527b">NativeTypePointer</a>.</p>

</div>
</div>

### TI {#a90bb92a5920a90c1263efc52a320a130}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">codeview::TypeIndex llvm::pdb::NativeTypePointer::TI</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypepointer-h">NativeTypePointer.h</a>.</p>


<p>Referenced by <a href="#ac94623caedbca7f9d08757406113097e">getLength</a>, <a href="#a0a0e930306877fcde9ec2d6b9e9abd15">getTypeId</a>, <a href="#ab505cfbd671a4ca4db53adda746f04ad">NativeTypePointer</a> and <a href="#a6c55b42ed0eae4232518eb7911e4527b">NativeTypePointer</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypepointer-h">NativeTypePointer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypepointer-cpp">NativeTypePointer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
