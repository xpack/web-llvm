---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/debuginfo/lib/debuginfo/pdb/pdbsymbol-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `PDBSymbol.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbol-h">llvm/DebugInfo/PDB/PDBSymbol.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/ipdbenumchildren-h">llvm/DebugInfo/PDB/IPDBEnumChildren.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/ipdblinenumber-h">llvm/DebugInfo/PDB/IPDBLineNumber.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/ipdbrawsymbol-h">llvm/DebugInfo/PDB/IPDBRawSymbol.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/ipdbsession-h">llvm/DebugInfo/PDB/IPDBSession.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbextras-h">llvm/DebugInfo/PDB/PDBExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolannotation-h">llvm/DebugInfo/PDB/PDBSymbolAnnotation.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolblock-h">llvm/DebugInfo/PDB/PDBSymbolBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolcompiland-h">llvm/DebugInfo/PDB/PDBSymbolCompiland.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolcompilanddetails-h">llvm/DebugInfo/PDB/PDBSymbolCompilandDetails.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolcompilandenv-h">llvm/DebugInfo/PDB/PDBSymbolCompilandEnv.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolcustom-h">llvm/DebugInfo/PDB/PDBSymbolCustom.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboldata-h">llvm/DebugInfo/PDB/PDBSymbolData.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolexe-h">llvm/DebugInfo/PDB/PDBSymbolExe.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolfunc-h">llvm/DebugInfo/PDB/PDBSymbolFunc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolfuncdebugend-h">llvm/DebugInfo/PDB/PDBSymbolFuncDebugEnd.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolfuncdebugstart-h">llvm/DebugInfo/PDB/PDBSymbolFuncDebugStart.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbollabel-h">llvm/DebugInfo/PDB/PDBSymbolLabel.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolpublicsymbol-h">llvm/DebugInfo/PDB/PDBSymbolPublicSymbol.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolthunk-h">llvm/DebugInfo/PDB/PDBSymbolThunk.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboltypearray-h">llvm/DebugInfo/PDB/PDBSymbolTypeArray.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboltypebaseclass-h">llvm/DebugInfo/PDB/PDBSymbolTypeBaseClass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboltypebuiltin-h">llvm/DebugInfo/PDB/PDBSymbolTypeBuiltin.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboltypecustom-h">llvm/DebugInfo/PDB/PDBSymbolTypeCustom.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboltypedimension-h">llvm/DebugInfo/PDB/PDBSymbolTypeDimension.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboltypeenum-h">llvm/DebugInfo/PDB/PDBSymbolTypeEnum.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboltypefriend-h">llvm/DebugInfo/PDB/PDBSymbolTypeFriend.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboltypefunctionarg-h">llvm/DebugInfo/PDB/PDBSymbolTypeFunctionArg.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboltypefunctionsig-h">llvm/DebugInfo/PDB/PDBSymbolTypeFunctionSig.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboltypemanaged-h">llvm/DebugInfo/PDB/PDBSymbolTypeManaged.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboltypepointer-h">llvm/DebugInfo/PDB/PDBSymbolTypePointer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboltypetypedef-h">llvm/DebugInfo/PDB/PDBSymbolTypeTypedef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboltypeudt-h">llvm/DebugInfo/PDB/PDBSymbolTypeUDT.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboltypevtable-h">llvm/DebugInfo/PDB/PDBSymbolTypeVTable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymboltypevtableshape-h">llvm/DebugInfo/PDB/PDBSymbolTypeVTableShape.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolunknown-h">llvm/DebugInfo/PDB/PDBSymbolUnknown.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolusingnamespace-h">llvm/DebugInfo/PDB/PDBSymbolUsingNamespace.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbtypes-h">llvm/DebugInfo/PDB/PDBTypes.h</a>"
#include &lt;memory&gt;
</div>

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acff875bdf8cbf8d69b46d2293c34c587">FACTORY_SYMTAG_CASE</a>(Tag, Type)&nbsp;&nbsp;&nbsp;...</td>
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

### FACTORY\_SYMTAG\_CASE {#acff875bdf8cbf8d69b46d2293c34c587}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FACTORY_SYMTAG_CASE(Tag, Type)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case PDB_SymType::Tag:                                                       \
    return std::unique_ptr&lt;<a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol">PDBSymbol</a>&gt;(new <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>(PDBSession));
</div>
</dd>
</dl>

<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/pdbsymbol-cpp">PDBSymbol.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
