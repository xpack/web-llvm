---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pdb/nativesymbolenumerator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `NativeSymbolEnumerator` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::pdb::NativeSymbolEnumerator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesymbolenumerator-h">llvm/DebugInfo/PDB/Native/NativeSymbolEnumerator.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a477775d1b0e1f16b7d3e71f51a2a115a">NativeSymbolEnumerator</a> (NativeSession &amp;Session, SymIndexId Id, const NativeTypeEnum &amp;Parent, codeview::EnumeratorRecord Record)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac36b131b004c64cbe585c1078fdd9007">~NativeSymbolEnumerator</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2706f212a1c6e926e3d4c442f1c5755">dump</a> (raw_ostream &amp;OS, int Indent, PdbSymbolIdField ShowIdFields, PdbSymbolIdField RecurseIdFields) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32ee4efdb3312ebb6d9c3e73ad048232">getClassParentId</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab74a6ef6a2693459bb8ce2acf39bd594">getLexicalParentId</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a634e2e792a0cfa1b5f4f7a56a31f88e4">getName</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba6ed673803a31625a6b047eeb291a5f">getTypeId</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a6bb7bf8c85135f7a1ff129776219989e">PDB_DataKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adeb110d1b57f75298ba0d2ed5bb3dbea">getDataKind</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a5dbb1abfb6d3c14555304f9c56703234">PDB_LocType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0944df14a8c62a0f535a8e0b257a9c69">getLocationType</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abefc34ce5d2bf36aae986c21e167cd8f">isConstType</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29f1272e9d34736f87b8a4c8689db0f3">isVolatileType</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39428d7e4b30bb418cecf24ed76871b2">isUnalignedType</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/pdb/variant">Variant</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92ce81a47b33b491fd017d85aabf2822">getValue</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pdb/nativetypeenum">NativeTypeEnum</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a351d5393f1b5dffe67fa7271be8f1be7">Parent</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/enumeratorrecord">codeview::EnumeratorRecord</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afec51ecb047664ecde8cd6b3b6034d9c">Record</a></td>
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


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesymbolenumerator-h">NativeSymbolEnumerator.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### NativeSymbolEnumerator() {#a477775d1b0e1f16b7d3e71f51a2a115a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NativeSymbolEnumerator::NativeSymbolEnumerator (<a href="/web-llvm/docs/api/classes/llvm/pdb/nativesession">NativeSession</a> &amp; Session, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a0d95a0af7fff523a0a4bfb7f6b578d12">SymIndexId</a> Id, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pdb/nativetypeenum">NativeTypeEnum</a> &amp; Parent, <a href="/web-llvm/docs/api/classes/llvm/codeview/enumeratorrecord">codeview::EnumeratorRecord</a> Record)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesymbolenumerator-h">NativeSymbolEnumerator.h</a>, definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesymbolenumerator-cpp">NativeSymbolEnumerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30baf6068daa29dbb05a7ead1e3b5a48bbee">llvm::pdb::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#a4cbeed8a0b429b5aea245873a199f97b">llvm::pdb::NativeRawSymbol::NativeRawSymbol</a>, <a href="#a351d5393f1b5dffe67fa7271be8f1be7">Parent</a>, <a href="#afec51ecb047664ecde8cd6b3b6034d9c">Record</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#ae264b7462dfb57a16a94b8f871f52920">llvm::pdb::NativeRawSymbol::Session</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~NativeSymbolEnumerator() {#ac36b131b004c64cbe585c1078fdd9007}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NativeSymbolEnumerator::~NativeSymbolEnumerator ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesymbolenumerator-h">NativeSymbolEnumerator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#af2706f212a1c6e926e3d4c442f1c5755}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NativeSymbolEnumerator::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, int Indent, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2c">PdbSymbolIdField</a> ShowIdFields, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2c">PdbSymbolIdField</a> RecurseIdFields)</td>
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



<p>Declaration at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesymbolenumerator-h">NativeSymbolEnumerator.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesymbolenumerator-cpp">NativeSymbolEnumerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2ca5ec2b91b4f21888ae4a157c15d806941">llvm::pdb::ClassParent</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#aeeda1eb1da6fda8318d0a3093caa3ea2">llvm::pdb::NativeRawSymbol::dump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a28e0e7c7f7920e3608fea13ec3e4394e">llvm::pdb::dumpSymbolField</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#aebe60f61f4fe8956834c561bfb8a75e8">llvm::pdb::dumpSymbolIdField</a>, <a href="#a32ee4efdb3312ebb6d9c3e73ad048232">getClassParentId</a>, <a href="#adeb110d1b57f75298ba0d2ed5bb3dbea">getDataKind</a>, <a href="#ab74a6ef6a2693459bb8ce2acf39bd594">getLexicalParentId</a>, <a href="#a0944df14a8c62a0f535a8e0b257a9c69">getLocationType</a>, <a href="#a634e2e792a0cfa1b5f4f7a56a31f88e4">getName</a>, <a href="#aba6ed673803a31625a6b047eeb291a5f">getTypeId</a>, <a href="#a92ce81a47b33b491fd017d85aabf2822">getValue</a>, <a href="#abefc34ce5d2bf36aae986c21e167cd8f">isConstType</a>, <a href="#a39428d7e4b30bb418cecf24ed76871b2">isUnalignedType</a>, <a href="#a29f1272e9d34736f87b8a4c8689db0f3">isVolatileType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2ca0a31053bfd7ad7db33f78a8c31f4c99a">llvm::pdb::LexicalParent</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#ae264b7462dfb57a16a94b8f871f52920">llvm::pdb::NativeRawSymbol::Session</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2caa1fa27779242b4902f7ae3bdd5c6d508">llvm::pdb::Type</a>.</p>

</div>
</div>

### getClassParentId() {#a32ee4efdb3312ebb6d9c3e73ad048232}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymIndexId NativeSymbolEnumerator::getClassParentId ()</td>
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



<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesymbolenumerator-h">NativeSymbolEnumerator.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesymbolenumerator-cpp">NativeSymbolEnumerator.cpp</a>.</p>


<p>Reference <a href="#a351d5393f1b5dffe67fa7271be8f1be7">Parent</a>.</p>


<p>Referenced by <a href="#af2706f212a1c6e926e3d4c442f1c5755">dump</a>.</p>

</div>
</div>

### getDataKind() {#adeb110d1b57f75298ba0d2ed5bb3dbea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PDB_DataKind NativeSymbolEnumerator::getDataKind ()</td>
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



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesymbolenumerator-h">NativeSymbolEnumerator.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesymbolenumerator-cpp">NativeSymbolEnumerator.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a6bb7bf8c85135f7a1ff129776219989eacb17869fe51048b5a5c4c6106551a255">llvm::pdb::Constant</a>.</p>


<p>Referenced by <a href="#af2706f212a1c6e926e3d4c442f1c5755">dump</a>.</p>

</div>
</div>

### getLexicalParentId() {#ab74a6ef6a2693459bb8ce2acf39bd594}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymIndexId NativeSymbolEnumerator::getLexicalParentId ()</td>
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



<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesymbolenumerator-h">NativeSymbolEnumerator.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesymbolenumerator-cpp">NativeSymbolEnumerator.cpp</a>.</p>


<p>Referenced by <a href="#af2706f212a1c6e926e3d4c442f1c5755">dump</a>.</p>

</div>
</div>

### getLocationType() {#a0944df14a8c62a0f535a8e0b257a9c69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PDB_LocType NativeSymbolEnumerator::getLocationType ()</td>
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



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesymbolenumerator-h">NativeSymbolEnumerator.h</a>, definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesymbolenumerator-cpp">NativeSymbolEnumerator.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a5dbb1abfb6d3c14555304f9c56703234acb17869fe51048b5a5c4c6106551a255">llvm::pdb::Constant</a>.</p>


<p>Referenced by <a href="#af2706f212a1c6e926e3d4c442f1c5755">dump</a>.</p>

</div>
</div>

### getName() {#a634e2e792a0cfa1b5f4f7a56a31f88e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string NativeSymbolEnumerator::getName ()</td>
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



<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesymbolenumerator-h">NativeSymbolEnumerator.h</a>, definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesymbolenumerator-cpp">NativeSymbolEnumerator.cpp</a>.</p>


<p>Reference <a href="#afec51ecb047664ecde8cd6b3b6034d9c">Record</a>.</p>


<p>Referenced by <a href="#af2706f212a1c6e926e3d4c442f1c5755">dump</a>.</p>

</div>
</div>

### getTypeId() {#aba6ed673803a31625a6b047eeb291a5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymIndexId NativeSymbolEnumerator::getTypeId ()</td>
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



<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesymbolenumerator-h">NativeSymbolEnumerator.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesymbolenumerator-cpp">NativeSymbolEnumerator.cpp</a>.</p>


<p>Reference <a href="#a351d5393f1b5dffe67fa7271be8f1be7">Parent</a>.</p>


<p>Referenced by <a href="#af2706f212a1c6e926e3d4c442f1c5755">dump</a>.</p>

</div>
</div>

### getValue() {#a92ce81a47b33b491fd017d85aabf2822}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Variant NativeSymbolEnumerator::getValue ()</td>
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



<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesymbolenumerator-h">NativeSymbolEnumerator.h</a>, definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesymbolenumerator-cpp">NativeSymbolEnumerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a29a5bdf367e3f74df9228dfce2c93a6fac26f15e86e3de4c398a8273272aba034">llvm::pdb::Bool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a29a5bdf367e3f74df9228dfce2c93a6fa8e95e84813830072b7516cfaa7dbc1a9">llvm::pdb::Char</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a29a5bdf367e3f74df9228dfce2c93a6fa1686a6c336b71b36d77354cea19a8b52">llvm::pdb::Int</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a29a5bdf367e3f74df9228dfce2c93a6fa8394f0347c184cf156ac5924dccb773b">llvm::pdb::Long</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a351d5393f1b5dffe67fa7271be8f1be7">Parent</a>, <a href="#afec51ecb047664ecde8cd6b3b6034d9c">Record</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a29a5bdf367e3f74df9228dfce2c93a6fa0b1291eded63143ac04709711274785a">llvm::pdb::UInt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a29a5bdf367e3f74df9228dfce2c93a6fa43963b8459ea654be36f373f1a036182">llvm::pdb::ULong</a>.</p>


<p>Referenced by <a href="#af2706f212a1c6e926e3d4c442f1c5755">dump</a>.</p>

</div>
</div>

### isConstType() {#abefc34ce5d2bf36aae986c21e167cd8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeSymbolEnumerator::isConstType ()</td>
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



<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesymbolenumerator-h">NativeSymbolEnumerator.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesymbolenumerator-cpp">NativeSymbolEnumerator.cpp</a>.</p>


<p>Referenced by <a href="#af2706f212a1c6e926e3d4c442f1c5755">dump</a>.</p>

</div>
</div>

### isUnalignedType() {#a39428d7e4b30bb418cecf24ed76871b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeSymbolEnumerator::isUnalignedType ()</td>
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



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesymbolenumerator-h">NativeSymbolEnumerator.h</a>, definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesymbolenumerator-cpp">NativeSymbolEnumerator.cpp</a>.</p>


<p>Referenced by <a href="#af2706f212a1c6e926e3d4c442f1c5755">dump</a>.</p>

</div>
</div>

### isVolatileType() {#a29f1272e9d34736f87b8a4c8689db0f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeSymbolEnumerator::isVolatileType ()</td>
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



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesymbolenumerator-h">NativeSymbolEnumerator.h</a>, definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesymbolenumerator-cpp">NativeSymbolEnumerator.cpp</a>.</p>


<p>Referenced by <a href="#af2706f212a1c6e926e3d4c442f1c5755">dump</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Parent {#a351d5393f1b5dffe67fa7271be8f1be7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const NativeTypeEnum&amp; llvm::pdb::NativeSymbolEnumerator::Parent</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesymbolenumerator-h">NativeSymbolEnumerator.h</a>.</p>


<p>Referenced by <a href="#a32ee4efdb3312ebb6d9c3e73ad048232">getClassParentId</a>, <a href="#aba6ed673803a31625a6b047eeb291a5f">getTypeId</a>, <a href="#a92ce81a47b33b491fd017d85aabf2822">getValue</a> and <a href="#a477775d1b0e1f16b7d3e71f51a2a115a">NativeSymbolEnumerator</a>.</p>

</div>
</div>

### Record {#afec51ecb047664ecde8cd6b3b6034d9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">codeview::EnumeratorRecord llvm::pdb::NativeSymbolEnumerator::Record</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesymbolenumerator-h">NativeSymbolEnumerator.h</a>.</p>


<p>Referenced by <a href="#a634e2e792a0cfa1b5f4f7a56a31f88e4">getName</a>, <a href="#a92ce81a47b33b491fd017d85aabf2822">getValue</a> and <a href="#a477775d1b0e1f16b7d3e71f51a2a115a">NativeSymbolEnumerator</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesymbolenumerator-h">NativeSymbolEnumerator.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesymbolenumerator-cpp">NativeSymbolEnumerator.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
