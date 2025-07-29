---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pdb/pdbsymboldata
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PDBSymbolData` Class



## Declaration

<div class="doxyDeclaration">
class llvm::pdb::PDBSymbolData { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboldata-h">llvm/DebugInfo/PDB/PDBSymbolData.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad76cd5f4677d9621c3d41be1d7c28b70">dump</a> (PDBSymDumper &amp;Dumper) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dumps the contents of a symbol a <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a>. <a href="#ad76cd5f4677d9621c3d41be1d7c28b70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a217f1bfdff572ea30e762481e0049ebf">IPDBEnumLineNumbers</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ef5a30390a902cfefa0387a0ce416c7">getLineNumbers</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af53e517e0357a84a29fa4b5c6938afb2">getCompilandId</a> () const</td>
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


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboldata-h">PDBSymbolData.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### dump() {#ad76cd5f4677d9621c3d41be1d7c28b70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PDBSymbolData::dump (<a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper">PDBSymDumper</a> &amp; Dumper)</td>
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


<p>By default this will just call <a href="#ad76cd5f4677d9621c3d41be1d7c28b70">dump()</a> on the underlying RawSymbol, which allows us to discover unknown properties, but individual implementations of <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol">PDBSymbol</a> may override the behavior to only dump known fields.</p>


<p>Declaration at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboldata-h">PDBSymbolData.h</a>, definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/pdbsymboldata-cpp">PDBSymbolData.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#a0a9c807b3e63885f9d510ba25ecfc6ce">llvm::pdb::PDBSymDumper::dump</a>.</p>

</div>
</div>

### getCompilandId() {#af53e517e0357a84a29fa4b5c6938afb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t PDBSymbolData::getCompilandId ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboldata-h">PDBSymbolData.h</a>, definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/pdbsymboldata-cpp">PDBSymbolData.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30ba247232063f777fa3c2371e077db8b61b">llvm::pdb::Compiland</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30bad9191bc18d794c7946c20fd549ceab73">llvm::pdb::Exe</a>, <a href="#a4ef5a30390a902cfefa0387a0ce416c7">getLineNumbers</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol/#aedc72dbd19536e5430d4033dc82305f4">llvm::pdb::PDBSymbol::RawSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol/#a3ae1db01febde23d665bae01f44df67d">llvm::pdb::PDBSymbol::Session</a>.</p>

</div>
</div>

### getLineNumbers() {#a4ef5a30390a902cfefa0387a0ce416c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; IPDBEnumLineNumbers &gt; PDBSymbolData::getLineNumbers ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboldata-h">PDBSymbolData.h</a>, definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/pdbsymboldata-cpp">PDBSymbolData.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol/#aedc72dbd19536e5430d4033dc82305f4">llvm::pdb::PDBSymbol::RawSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol/#a3ae1db01febde23d665bae01f44df67d">llvm::pdb::PDBSymbol::Session</a>.</p>


<p>Referenced by <a href="#af53e517e0357a84a29fa4b5c6938afb2">getCompilandId</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboldata-h">PDBSymbolData.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/pdbsymboldata-cpp">PDBSymbolData.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
