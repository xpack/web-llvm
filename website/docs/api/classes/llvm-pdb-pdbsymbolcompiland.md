---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pdb/pdbsymbolcompiland
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PDBSymbolCompiland` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::pdb::PDBSymbolCompiland { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolcompiland-h">llvm/DebugInfo/PDB/PDBSymbolCompiland.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae38008c9a00f5570010cee8f743e0e5e">dump</a> (PDBSymDumper &amp;Dumper) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dumps the contents of a symbol a <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a>. <a href="#ae38008c9a00f5570010cee8f743e0e5e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09a8cb81d55088ca26ab8918686e217b">getSourceFileName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10cadbc43e6950a1500f1308cb931c2d">getSourceFileFullPath</a> () const</td>
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


<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolcompiland-h">PDBSymbolCompiland.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### dump() {#ae38008c9a00f5570010cee8f743e0e5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PDBSymbolCompiland::dump (<a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper">PDBSymDumper</a> &amp; Dumper)</td>
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


<p>By default this will just call <a href="#ae38008c9a00f5570010cee8f743e0e5e">dump()</a> on the underlying RawSymbol, which allows us to discover unknown properties, but individual implementations of <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol">PDBSymbol</a> may override the behavior to only dump known fields.</p>


<p>Declaration at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolcompiland-h">PDBSymbolCompiland.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/pdbsymbolcompiland-cpp">PDBSymbolCompiland.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#a0a9c807b3e63885f9d510ba25ecfc6ce">llvm::pdb::PDBSymDumper::dump</a>.</p>

</div>
</div>

### getSourceFileFullPath() {#a10cadbc43e6950a1500f1308cb931c2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string PDBSymbolCompiland::getSourceFileFullPath ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolcompiland-h">PDBSymbolCompiland.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/pdbsymbolcompiland-cpp">PDBSymbolCompiland.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#ad1056825d31bf187d0be430c51aac281">llvm::sys::path::extension</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol/#a84de898fb71434cbc866dde23a5b68f4">llvm::pdb::PDBSymbol::findAllChildren</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol/#a3b6a0b10e4bbd63d238a2bfa8bdf2bd2">llvm::pdb::PDBSymbol::findOneChild</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#ac35ec1dacb408d4c65d55249c0e02474">llvm::sys::path::is_absolute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a1d1b2eadb80309d27efbb727411c54ecaa380321aa205806f65896c4ae00291c7">llvm::pdb::NS_CaseInsensitive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ac10322dc19a928c2dbb83ec9689dc23caac70412e939d72a9234cdebb1af5867b">llvm::pdb::Path</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol/#aedc72dbd19536e5430d4033dc82305f4">llvm::pdb::PDBSymbol::RawSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol/#a3ae1db01febde23d665bae01f44df67d">llvm::pdb::PDBSymbol::Session</a>.</p>


<p>Referenced by <a href="#a09a8cb81d55088ca26ab8918686e217b">getSourceFileName</a>.</p>

</div>
</div>

### getSourceFileName() {#a09a8cb81d55088ca26ab8918686e217b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string PDBSymbolCompiland::getSourceFileName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolcompiland-h">PDBSymbolCompiland.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/pdbsymbolcompiland-cpp">PDBSymbolCompiland.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#aa56d25bb5127dd7a5831c25764f76cbe">llvm::sys::path::filename</a>, <a href="#a10cadbc43e6950a1500f1308cb931c2d">getSourceFileFullPath</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolcompiland-h">PDBSymbolCompiland.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/pdbsymbolcompiland-cpp">PDBSymbolCompiland.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
