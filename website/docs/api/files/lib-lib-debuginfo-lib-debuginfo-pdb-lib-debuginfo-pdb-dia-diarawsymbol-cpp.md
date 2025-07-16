---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/dia/diarawsymbol-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `DIARawSymbol.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/dia/diarawsymbol-h">llvm/DebugInfo/PDB/DIA/DIARawSymbol.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/formatters-h">llvm/DebugInfo/CodeView/Formatters.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/dia/diaenumlinenumbers-h">llvm/DebugInfo/PDB/DIA/DIAEnumLineNumbers.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/dia/diaenumsymbols-h">llvm/DebugInfo/PDB/DIA/DIAEnumSymbols.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/dia/dialinenumber-h">llvm/DebugInfo/PDB/DIA/DIALineNumber.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/dia/diasession-h">llvm/DebugInfo/PDB/DIA/DIASession.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/dia/diautils-h">llvm/DebugInfo/PDB/DIA/DIAUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbextras-h">llvm/DebugInfo/PDB/PDBExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboltypebuiltin-h">llvm/DebugInfo/PDB/PDBSymbolTypeBuiltin.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboltypepointer-h">llvm/DebugInfo/PDB/PDBSymbolTypePointer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboltypevtable-h">llvm/DebugInfo/PDB/PDBSymbolTypeVTable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboltypevtableshape-h">llvm/DebugInfo/PDB/PDBSymbolTypeVTableShape.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/convertutf-h">llvm/Support/ConvertUTF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-diarawsymbol-cpp-">anonymous{DIARawSymbol.cpp}</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af692299230707620c17a5cc8462ee94f">RAW_ID_METHOD_DUMP</a>(Stream, Method, Session, FieldId, ShowFlags, RecurseFlags)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0575bfe05438286c96eb56bcb485e6a">RAW_METHOD_DUMP</a>(Stream, Method)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5da7db4d1270ca2d1c3dfe1f5965956b">RAW_METHOD_DUMP_AS</a>(Stream, Method, Type)&nbsp;&nbsp;&nbsp;...</td>
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

## Macro Definitions

### RAW\_ID\_METHOD\_DUMP {#af692299230707620c17a5cc8462ee94f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RAW_ID_METHOD_DUMP(Stream, Method, Session, FieldId, ShowFlags, RecurseFlags)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  DumpDIAIdValue(Stream, Indent, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>{#Method}, Symbol,                   \
                 &amp;IDiaSymbol::get_##Method, Session, FieldId, ShowFlags,       \
                 RecurseFlags);
</div>
</dd>
</dl>

<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/dia/diarawsymbol-cpp">DIARawSymbol.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/diarawsymbol/#afc40184fefae68d8c008089f04a0a0bc">llvm::pdb::DIARawSymbol::dump</a>.</p>

</div>
</div>

### RAW\_METHOD\_DUMP {#ac0575bfe05438286c96eb56bcb485e6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RAW_METHOD_DUMP(Stream, Method)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  DumpDIAValue(Stream, Indent, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>{#Method}, Symbol,                     \
               &amp;IDiaSymbol::get_##Method);
</div>
</dd>
</dl>

<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/dia/diarawsymbol-cpp">DIARawSymbol.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/diarawsymbol/#afc40184fefae68d8c008089f04a0a0bc">llvm::pdb::DIARawSymbol::dump</a>.</p>

</div>
</div>

### RAW\_METHOD\_DUMP\_AS {#a5da7db4d1270ca2d1c3dfe1f5965956b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RAW_METHOD_DUMP_AS(Stream, Method, Type)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  DumpDIAValueAs&lt;<a href="/web-llvm/docs/api/classes/llvm/type">Type</a>&gt;(Stream, Indent, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>{#Method}, Symbol,             \
                       &amp;IDiaSymbol::get_##Method);
</div>
</dd>
</dl>

<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/dia/diarawsymbol-cpp">DIARawSymbol.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/diarawsymbol/#afc40184fefae68d8c008089f04a0a0bc">llvm::pdb::DIARawSymbol::dump</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
