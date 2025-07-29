---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/debuginfo/lib/debuginfo/pdb/udtlayout-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `UDTLayout.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/udtlayout-h">llvm/DebugInfo/PDB/UDTLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">llvm/ADT/BitVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/ipdbenumchildren-h">llvm/DebugInfo/PDB/IPDBEnumChildren.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/ipdblinenumber-h">llvm/DebugInfo/PDB/IPDBLineNumber.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/ipdbrawsymbol-h">llvm/DebugInfo/PDB/IPDBRawSymbol.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/ipdbsession-h">llvm/DebugInfo/PDB/IPDBSession.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbol-h">llvm/DebugInfo/PDB/PDBSymbol.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboldata-h">llvm/DebugInfo/PDB/PDBSymbolData.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolfunc-h">llvm/DebugInfo/PDB/PDBSymbolFunc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboltypebaseclass-h">llvm/DebugInfo/PDB/PDBSymbolTypeBaseClass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboltypebuiltin-h">llvm/DebugInfo/PDB/PDBSymbolTypeBuiltin.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboltypefunctionsig-h">llvm/DebugInfo/PDB/PDBSymbolTypeFunctionSig.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboltypepointer-h">llvm/DebugInfo/PDB/PDBSymbolTypePointer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboltypeudt-h">llvm/DebugInfo/PDB/PDBSymbolTypeUDT.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboltypevtable-h">llvm/DebugInfo/PDB/PDBSymbolTypeVTable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbtypes-h">llvm/DebugInfo/PDB/PDBTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include &lt;memory&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol">PDBSymbol</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e32eafcf44bd2c6a419a9fe615d9f4c">getSymbolType</a> (const PDBSymbol &amp;Symbol)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33d3e2e087cade1db9986aa11f7207a6">getTypeLength</a> (const PDBSymbol &amp;Symbol)</td>
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


<div class="doxySectionDef">

## Functions

### getSymbolType() {#a9e32eafcf44bd2c6a419a9fe615d9f4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; PDBSymbol &gt; getSymbolType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol">PDBSymbol</a> &amp; Symbol)</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/udtlayout-cpp">UDTLayout.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pdb/ipdbsession/#af1a5e8227daa0df4bf2603f1c79619d9">llvm::pdb::IPDBSession::getSymbolById</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/ipdbrawsymbol/#af2d3204420c4a501391a94801d1093e3">llvm::pdb::IPDBRawSymbol::getTypeId</a>.</p>


<p>Referenced by <a href="#a33d3e2e087cade1db9986aa11f7207a6">getTypeLength</a> and <a href="/web-llvm/docs/api/classes/llvm/object/xcoffcsectauxref/#a0dbeba64af94a7e5dcc2c3ec326d1353">llvm::object::XCOFFCsectAuxRef::isLabel</a>.</p>

</div>
</div>

### getTypeLength() {#a33d3e2e087cade1db9986aa11f7207a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t getTypeLength (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol">PDBSymbol</a> &amp; Symbol)</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/udtlayout-cpp">UDTLayout.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pdb/ipdbrawsymbol/#a93a2474b599e4ddbbd72285c98febe31">llvm::pdb::IPDBRawSymbol::getLength</a> and <a href="#a9e32eafcf44bd2c6a419a9fe615d9f4c">getSymbolType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/datamemberlayoutitem/#a178a9e728b70cd289c3f491283b3164b">llvm::pdb::DataMemberLayoutItem::DataMemberLayoutItem</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/vtablelayoutitem/#aa3300b9c44d96281bad0d1ca6659fe80">llvm::pdb::VTableLayoutItem::VTableLayoutItem</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
