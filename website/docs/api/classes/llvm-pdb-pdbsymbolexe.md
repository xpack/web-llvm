---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pdb/pdbsymbolexe
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PDBSymbolExe` Class



## Declaration

<div class="doxyDeclaration">
class llvm::pdb::PDBSymbolExe { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolexe-h">llvm/DebugInfo/PDB/PDBSymbolExe.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol">PDBSymbol</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol">PDBSymbol</a> defines the base of the inheritance hierarchy for concrete symbol types (e.g. <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5743e1ae5558806327745b3faa1f464">dump</a> (PDBSymDumper &amp;Dumper) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dumps the contents of a symbol a <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a>. <a href="#aa5743e1ae5558806327745b3faa1f464">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74272ca0ece3c89962b8a37675dacef1">getPointerByteSize</a> () const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36d5ed19129f27ba5da5fc050175bbfc">dumpChildren</a> (raw_ostream &amp;OS, StringRef Label, PDB_SymType ChildType, int Indent) const</td>
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


<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolexe-h">PDBSymbolExe.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### dump() {#aa5743e1ae5558806327745b3faa1f464}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PDBSymbolExe::dump (<a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper">PDBSymDumper</a> &amp; Dumper)</td>
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

<p>Dumps the contents of a symbol a <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a>.</p>


<p>By default this will just call <a href="#aa5743e1ae5558806327745b3faa1f464">dump()</a> on the underlying RawSymbol, which allows us to discover unknown properties, but individual implementations of <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol">PDBSymbol</a> may override the behavior to only dump known fields.</p>


<p>Declaration at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolexe-h">PDBSymbolExe.h</a>, definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/pdbsymbolexe-cpp">PDBSymbolExe.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#a0a9c807b3e63885f9d510ba25ecfc6ce">llvm::pdb::PDBSymDumper::dump</a>.</p>

</div>
</div>

### getPointerByteSize() {#a74272ca0ece3c89962b8a37675dacef1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t PDBSymbolExe::getPointerByteSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolexe-h">PDBSymbolExe.h</a>, definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/pdbsymbolexe-cpp">PDBSymbolExe.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol/#a3b6a0b10e4bbd63d238a2bfa8bdf2bd2">llvm::pdb::PDBSymbol::findOneChild</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4b24b650f118105cc5fbc34c83f006cf">llvm::getMachineType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a1928545fad40360ae644901d7308cbeba8a9da7865483c5fd359f3acef178d26d">llvm::pdb::x86</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### dumpChildren() {#a36d5ed19129f27ba5da5fc050175bbfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::pdb::PDBSymbolExe::dumpChildren (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Label, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30b">PDB_SymType</a> ChildType, int Indent)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolexe-h">PDBSymbolExe.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolexe-h">PDBSymbolExe.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/pdbsymbolexe-cpp">PDBSymbolExe.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
