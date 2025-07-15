---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/symbolcache-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `SymbolCache.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/symbolcache-h">llvm/DebugInfo/PDB/Native/SymbolCache.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugchecksumssubsection-h">llvm/DebugInfo/CodeView/DebugChecksumsSubsection.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debuglinessubsection-h">llvm/DebugInfo/CodeView/DebugLinesSubsection.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/debugsubsectionrecord-h">llvm/DebugInfo/CodeView/DebugSubsectionRecord.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/lazyrandomtypecollection-h">llvm/DebugInfo/CodeView/LazyRandomTypeCollection.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symboldeserializer-h">llvm/DebugInfo/CodeView/SymbolDeserializer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecord-h">llvm/DebugInfo/CodeView/SymbolRecord.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typedeserializer-h">llvm/DebugInfo/CodeView/TypeDeserializer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">llvm/DebugInfo/CodeView/TypeRecord.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecordhelpers-h">llvm/DebugInfo/CodeView/TypeRecordHelpers.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/ipdbsourcefile-h">llvm/DebugInfo/PDB/IPDBSourceFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbimodulelist-h">llvm/DebugInfo/PDB/Native/DbiModuleList.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">llvm/DebugInfo/PDB/Native/DbiStream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/moduledebugstream-h">llvm/DebugInfo/PDB/Native/ModuleDebugStream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativecompilandsymbol-h">llvm/DebugInfo/PDB/Native/NativeCompilandSymbol.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativeenumglobals-h">llvm/DebugInfo/PDB/Native/NativeEnumGlobals.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativeenumlinenumbers-h">llvm/DebugInfo/PDB/Native/NativeEnumLineNumbers.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativeenumtypes-h">llvm/DebugInfo/PDB/Native/NativeEnumTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativefunctionsymbol-h">llvm/DebugInfo/PDB/Native/NativeFunctionSymbol.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativeinlinesitesymbol-h">llvm/DebugInfo/PDB/Native/NativeInlineSiteSymbol.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativelinenumber-h">llvm/DebugInfo/PDB/Native/NativeLineNumber.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativepublicsymbol-h">llvm/DebugInfo/PDB/Native/NativePublicSymbol.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativerawsymbol-h">llvm/DebugInfo/PDB/Native/NativeRawSymbol.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">llvm/DebugInfo/PDB/Native/NativeSession.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypearray-h">llvm/DebugInfo/PDB/Native/NativeTypeArray.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypebuiltin-h">llvm/DebugInfo/PDB/Native/NativeTypeBuiltin.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeenum-h">llvm/DebugInfo/PDB/Native/NativeTypeEnum.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypefunctionsig-h">llvm/DebugInfo/PDB/Native/NativeTypeFunctionSig.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypepointer-h">llvm/DebugInfo/PDB/Native/NativeTypePointer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypetypedef-h">llvm/DebugInfo/PDB/Native/NativeTypeTypedef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypeudt-h">llvm/DebugInfo/PDB/Native/NativeTypeUDT.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativetypevtshape-h">llvm/DebugInfo/PDB/Native/NativeTypeVTShape.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/pdbfile-h">llvm/DebugInfo/PDB/Native/PDBFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/publicsstream-h">llvm/DebugInfo/PDB/Native/PublicsStream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/symbolstream-h">llvm/DebugInfo/PDB/Native/SymbolStream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/tpistream-h">llvm/DebugInfo/PDB/Native/TpiStream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbol-h">llvm/DebugInfo/PDB/PDBSymbol.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbolcompiland-h">llvm/DebugInfo/PDB/PDBSymbolCompiland.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/builtintypeentry">BuiltinTypeEntry</a></td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> struct <a href="/web-llvm/docs/api/structs/builtintypeentry">BuiltinTypeEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2bb5059bfb8f769c971b1b76ee96173">BuiltinTypes</a>[] = ...</td>
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

## Variables

### BuiltinTypes {#ae2bb5059bfb8f769c971b1b76ee96173}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const struct BuiltinTypeEntry BuiltinTypes[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    {<a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubcommon-h/#a8e64f5532820f43f01399ac8bb2ff3e9ac9d3e887722f2bc482bcca9d41c512af">codeview::SimpleTypeKind::None</a>, <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubcommon-h/#a8e64f5532820f43f01399ac8bb2ff3e9ac9d3e887722f2bc482bcca9d41c512af">PDB_BuiltinType::None</a>, 0},
    {<a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a8ce14d8b0fc90289ee23848f6de11c47">codeview::SimpleTypeKind::Void</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a8ce14d8b0fc90289ee23848f6de11c47">PDB_BuiltinType::Void</a>, 0},
    {codeview::SimpleTypeKind::HResult, PDB_BuiltinType::HResult, 4},
    {codeview::SimpleTypeKind::Int16Short, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a637b69dea56f804278aa50e975337e01">PDB_BuiltinType::Int</a>, 2},
    {codeview::SimpleTypeKind::UInt16Short, PDB_BuiltinType::UInt, 2},
    {<a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a788a72ddbf1bd572b3fcd7a5e7ec8cff">codeview::SimpleTypeKind::Int32</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a637b69dea56f804278aa50e975337e01">PDB_BuiltinType::Int</a>, 4},
    {codeview::SimpleTypeKind::UInt32, PDB_BuiltinType::UInt, 4},
    {codeview::SimpleTypeKind::Int32Long, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a637b69dea56f804278aa50e975337e01">PDB_BuiltinType::Int</a>, 4},
    {codeview::SimpleTypeKind::UInt32Long, PDB_BuiltinType::UInt, 4},
    {codeview::SimpleTypeKind::Int64Quad, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a637b69dea56f804278aa50e975337e01">PDB_BuiltinType::Int</a>, 8},
    {codeview::SimpleTypeKind::UInt64Quad, PDB_BuiltinType::UInt, 8},
    {codeview::SimpleTypeKind::NarrowCharacter, PDB_BuiltinType::Char, 1},
    {codeview::SimpleTypeKind::WideCharacter, PDB_BuiltinType::WCharT, 2},
    {codeview::SimpleTypeKind::Character16, PDB_BuiltinType::Char16, 2},
    {codeview::SimpleTypeKind::Character32, PDB_BuiltinType::Char32, 4},
    {codeview::SimpleTypeKind::Character8, PDB_BuiltinType::Char8, 1},
    {codeview::SimpleTypeKind::SignedCharacter, PDB_BuiltinType::Char, 1},
    {codeview::SimpleTypeKind::UnsignedCharacter, PDB_BuiltinType::UInt, 1},
    {codeview::SimpleTypeKind::Float32, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36ad67b0ee7230dcecb610254e4e5e589cd">PDB_BuiltinType::Float</a>, 4},
    {codeview::SimpleTypeKind::Float64, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36ad67b0ee7230dcecb610254e4e5e589cd">PDB_BuiltinType::Float</a>, 8},
    {codeview::SimpleTypeKind::Float80, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36ad67b0ee7230dcecb610254e4e5e589cd">PDB_BuiltinType::Float</a>, 10},
    {codeview::SimpleTypeKind::Boolean8, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a29dcc89db32a1eead61fe67cff38c060">PDB_BuiltinType::Bool</a>, 1},
}
</div>
</dd>
</dl>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/symbolcache-cpp">SymbolCache.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
