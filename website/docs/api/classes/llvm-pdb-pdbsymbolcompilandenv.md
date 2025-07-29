---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pdb/pdbsymbolcompilandenv
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PDBSymbolCompilandEnv` Class



## Declaration

<div class="doxyDeclaration">
class llvm::pdb::PDBSymbolCompilandEnv { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolcompilandenv-h">llvm/DebugInfo/PDB/PDBSymbolCompilandEnv.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44fe22419542ce7e1d2da6be07c98f5b">dump</a> (PDBSymDumper &amp;Dumper) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dumps the contents of a symbol a <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a>. <a href="#a44fe22419542ce7e1d2da6be07c98f5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a859c4fc930e3b66da9200bea5ae69be5">getValue</a> () const</td>
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


<p>Definition at line 18 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolcompilandenv-h">PDBSymbolCompilandEnv.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### dump() {#a44fe22419542ce7e1d2da6be07c98f5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PDBSymbolCompilandEnv::dump (<a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper">PDBSymDumper</a> &amp; Dumper)</td>
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


<p>By default this will just call <a href="#a44fe22419542ce7e1d2da6be07c98f5b">dump()</a> on the underlying RawSymbol, which allows us to discover unknown properties, but individual implementations of <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol">PDBSymbol</a> may override the behavior to only dump known fields.</p>


<p>Declaration at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolcompilandenv-h">PDBSymbolCompilandEnv.h</a>, definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/pdbsymbolcompilandenv-cpp">PDBSymbolCompilandEnv.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#a0a9c807b3e63885f9d510ba25ecfc6ce">llvm::pdb::PDBSymDumper::dump</a>.</p>

</div>
</div>

### getValue() {#a859c4fc930e3b66da9200bea5ae69be5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string PDBSymbolCompilandEnv::getValue ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolcompilandenv-h">PDBSymbolCompilandEnv.h</a>, definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/pdbsymbolcompilandenv-cpp">PDBSymbolCompilandEnv.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol/#aedc72dbd19536e5430d4033dc82305f4">llvm::pdb::PDBSymbol::RawSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a434cfa04e4ed34b7a901378557d4ca9ea4501cbae351ca0ef6f162f946ba58d0e">llvm::pdb::String</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a18dbfcb332af7515599ee795cf462843">llvm::Value::Value</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolcompilandenv-h">PDBSymbolCompilandEnv.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/pdbsymbolcompilandenv-cpp">PDBSymbolCompilandEnv.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
