---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pdb/nativetypebuiltin
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `NativeTypeBuiltin` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::pdb::NativeTypeBuiltin { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypebuiltin-h">llvm/DebugInfo/PDB/Native/NativeTypeBuiltin.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a9c8a66e690105eed603e7ca0b5d9a7">NativeTypeBuiltin</a> (NativeSession &amp;PDBSession, SymIndexId Id, codeview::ModifierOptions Mods, PDB_BuiltinType T, uint64_t L)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad317438c1cb77e99e42f3e8e57d9ff2d">~NativeTypeBuiltin</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2bd90ec10496f7396a818f9c3ab5f71">dump</a> (raw_ostream &amp;OS, int Indent, PdbSymbolIdField ShowIdFields, PdbSymbolIdField RecurseIdFields) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdff09d12522af7b345a5b910edc6389">getSymTag</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26a45f8ca4a45172797d48d1942ed38b">getBuiltinType</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accc7ab996f7047ffcb83efb1b2585062">isConstType</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e601ab708c4c5995710ff798d63096a">getLength</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66bbd30b0740cf33e2fc6a7bb77f852f">isUnalignedType</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d356536f70c283bb8b1a7a8017ad21d">isVolatileType</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pdb/nativesession">NativeSession</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacdef3860356750ef3cba14ff8d2ea69">Session</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#acf5c2920c8a10eeb1d8c5d3a9c2adfb6">codeview::ModifierOptions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae93920c7f4ef51034c238faef5493807">Mods</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a924e41756f472cb92448ad19fb78f1e0">Type</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acacf2730104f97f4e5aa317a613b166e">Length</a></td>
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


<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypebuiltin-h">NativeTypeBuiltin.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### NativeTypeBuiltin() {#a4a9c8a66e690105eed603e7ca0b5d9a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NativeTypeBuiltin::NativeTypeBuiltin (<a href="/web-llvm/docs/api/classes/llvm/pdb/nativesession">NativeSession</a> &amp; PDBSession, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a0d95a0af7fff523a0a4bfb7f6b578d12">SymIndexId</a> Id, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#acf5c2920c8a10eeb1d8c5d3a9c2adfb6">codeview::ModifierOptions</a> Mods, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a29a5bdf367e3f74df9228dfce2c93a6f">PDB_BuiltinType</a> T, uint64_t L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypebuiltin-h">NativeTypeBuiltin.h</a>, definition at line 15 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypebuiltin-cpp">NativeTypeBuiltin.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30bab39d1e3769662a05bf103710580f0dd6">llvm::pdb::BuiltinType</a>, <a href="#acacf2730104f97f4e5aa317a613b166e">Length</a>, <a href="#ae93920c7f4ef51034c238faef5493807">Mods</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativerawsymbol/#a4cbeed8a0b429b5aea245873a199f97b">llvm::pdb::NativeRawSymbol::NativeRawSymbol</a>, <a href="#aacdef3860356750ef3cba14ff8d2ea69">Session</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="#a924e41756f472cb92448ad19fb78f1e0">Type</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~NativeTypeBuiltin() {#ad317438c1cb77e99e42f3e8e57d9ff2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NativeTypeBuiltin::~NativeTypeBuiltin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypebuiltin-h">NativeTypeBuiltin.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#aa2bd90ec10496f7396a818f9c3ab5f71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NativeTypeBuiltin::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, int Indent, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2c">PdbSymbolIdField</a> ShowIdFields, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2c">PdbSymbolIdField</a> RecurseIdFields)</td>
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



<p>Declaration at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypebuiltin-h">NativeTypeBuiltin.h</a>, definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypebuiltin-cpp">NativeTypeBuiltin.cpp</a>.</p>

</div>
</div>

### getBuiltinType() {#a26a45f8ca4a45172797d48d1942ed38b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PDB_BuiltinType NativeTypeBuiltin::getBuiltinType ()</td>
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



<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypebuiltin-h">NativeTypeBuiltin.h</a>, definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypebuiltin-cpp">NativeTypeBuiltin.cpp</a>.</p>


<p>Reference <a href="#a924e41756f472cb92448ad19fb78f1e0">Type</a>.</p>

</div>
</div>

### getLength() {#a5e601ab708c4c5995710ff798d63096a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t NativeTypeBuiltin::getLength ()</td>
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



<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypebuiltin-h">NativeTypeBuiltin.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypebuiltin-cpp">NativeTypeBuiltin.cpp</a>.</p>


<p>Reference <a href="#acacf2730104f97f4e5aa317a613b166e">Length</a>.</p>

</div>
</div>

### getSymTag() {#abdff09d12522af7b345a5b910edc6389}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PDB_SymType NativeTypeBuiltin::getSymTag ()</td>
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



<p>Declaration at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypebuiltin-h">NativeTypeBuiltin.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypebuiltin-cpp">NativeTypeBuiltin.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30bab39d1e3769662a05bf103710580f0dd6">llvm::pdb::BuiltinType</a>.</p>

</div>
</div>

### isConstType() {#accc7ab996f7047ffcb83efb1b2585062}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeBuiltin::isConstType ()</td>
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



<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypebuiltin-h">NativeTypeBuiltin.h</a>, definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypebuiltin-cpp">NativeTypeBuiltin.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#acf5c2920c8a10eeb1d8c5d3a9c2adfb6a79ceee9f8e3c1f0cc74223e05d2448bf">llvm::codeview::Const</a>, <a href="#ae93920c7f4ef51034c238faef5493807">Mods</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#acf5c2920c8a10eeb1d8c5d3a9c2adfb6a6adf97f83acf6453d4a6a4b1070f3754">llvm::codeview::None</a>.</p>

</div>
</div>

### isUnalignedType() {#a66bbd30b0740cf33e2fc6a7bb77f852f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeBuiltin::isUnalignedType ()</td>
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



<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypebuiltin-h">NativeTypeBuiltin.h</a>, definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypebuiltin-cpp">NativeTypeBuiltin.cpp</a>.</p>


<p>References <a href="#ae93920c7f4ef51034c238faef5493807">Mods</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#acf5c2920c8a10eeb1d8c5d3a9c2adfb6a6adf97f83acf6453d4a6a4b1070f3754">llvm::codeview::None</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#acf5c2920c8a10eeb1d8c5d3a9c2adfb6a9f19679888db198f8dd45606487e6cd6">llvm::codeview::Unaligned</a>.</p>

</div>
</div>

### isVolatileType() {#a9d356536f70c283bb8b1a7a8017ad21d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeTypeBuiltin::isVolatileType ()</td>
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



<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypebuiltin-h">NativeTypeBuiltin.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypebuiltin-cpp">NativeTypeBuiltin.cpp</a>.</p>


<p>References <a href="#ae93920c7f4ef51034c238faef5493807">Mods</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#acf5c2920c8a10eeb1d8c5d3a9c2adfb6a6adf97f83acf6453d4a6a4b1070f3754">llvm::codeview::None</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#acf5c2920c8a10eeb1d8c5d3a9c2adfb6a3e3af98b6b48c7e593d8d18863e3333b">llvm::codeview::Volatile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Length {#acacf2730104f97f4e5aa317a613b166e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::pdb::NativeTypeBuiltin::Length</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypebuiltin-h">NativeTypeBuiltin.h</a>.</p>


<p>Referenced by <a href="#a5e601ab708c4c5995710ff798d63096a">getLength</a> and <a href="#a4a9c8a66e690105eed603e7ca0b5d9a7">NativeTypeBuiltin</a>.</p>

</div>
</div>

### Mods {#ae93920c7f4ef51034c238faef5493807}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">codeview::ModifierOptions llvm::pdb::NativeTypeBuiltin::Mods</td>
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



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypebuiltin-h">NativeTypeBuiltin.h</a>.</p>


<p>Referenced by <a href="#accc7ab996f7047ffcb83efb1b2585062">isConstType</a>, <a href="#a66bbd30b0740cf33e2fc6a7bb77f852f">isUnalignedType</a>, <a href="#a9d356536f70c283bb8b1a7a8017ad21d">isVolatileType</a> and <a href="#a4a9c8a66e690105eed603e7ca0b5d9a7">NativeTypeBuiltin</a>.</p>

</div>
</div>

### Session {#aacdef3860356750ef3cba14ff8d2ea69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NativeSession&amp; llvm::pdb::NativeTypeBuiltin::Session</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypebuiltin-h">NativeTypeBuiltin.h</a>.</p>


<p>Referenced by <a href="#a4a9c8a66e690105eed603e7ca0b5d9a7">NativeTypeBuiltin</a>.</p>

</div>
</div>

### Type {#a924e41756f472cb92448ad19fb78f1e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PDB_BuiltinType llvm::pdb::NativeTypeBuiltin::Type</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypebuiltin-h">NativeTypeBuiltin.h</a>.</p>


<p>Referenced by <a href="#a26a45f8ca4a45172797d48d1942ed38b">getBuiltinType</a> and <a href="#a4a9c8a66e690105eed603e7ca0b5d9a7">NativeTypeBuiltin</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypebuiltin-h">NativeTypeBuiltin.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativetypebuiltin-cpp">NativeTypeBuiltin.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
