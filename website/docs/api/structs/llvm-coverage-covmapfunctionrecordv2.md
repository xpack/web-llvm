---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/coverage/covmapfunctionrecordv2
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CovMapFunctionRecordV2` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::coverage::CovMapFunctionRecordV2 { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">llvm/ProfileData/Coverage/CoverageMapping.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfc4144e458ec3f710d79fcb6a18949e">ThisT</a> = <a href="/web-llvm/docs/api/structs/llvm/coverage/covmapfunctionrecordv2">CovMapFunctionRecordV2</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9ac4f7199d9c210f512f4d62d52afaa">INSTR_PROF_DATA</a> (const uint64_t, llvm::Type::getInt64Ty(Ctx), NameRef, ConstantInt::get(llvm::Type::getInt64Ty(Ctx), IndexedInstrProf::ComputeHash(getPGOFuncNameVarInitializer(Inc-&gt;getName())))) INSTR_PROF_DATA(const uint64_t</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c38c917e96172dd6fa5600c60da5baa">llvm::Type::getInt64Ty</a> (Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acea11458f4ef9e855dd2446e6ef755aa">ConstantInt::get</a> (llvm::Type::getInt64Ty(Ctx), Inc-&gt;getHash() -&gt;getZExtValue())) INSTR_PROF_DATA(const IntPtrT</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af617e126cbe8b17158fee6ddc2d34238">llvm::PointerType::getUnqual</a> (Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a608a6de3e222a2a193251c3c1a50da1f">INSTR_PROF_DATA</a> (IntPtrT, llvm::PointerType::getUnqual(Ctx), Values, ValuesPtrExpr) INSTR_PROF_DATA(const uint32_t</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dde80a8c60c0a77f8ac969d0a9b8d10">llvm::Type::getInt32Ty</a> (Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a817881ee0e75219918aec00c1592cd27">ConstantInt::get</a> (llvm::Type::getInt32Ty(Ctx), NumCounters)) INSTR_PROF_DATA(const uint16_t</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa080ab71a7e08fd9a6ac23cebecd6f20">ConstantArray::get</a> (Int16ArrayTy, Int16ArrayVals)) INSTR_PROF_DATA(const uint32_t</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dde80a8c60c0a77f8ac969d0a9b8d10">llvm::Type::getInt32Ty</a> (Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64a80b3006a2a77833ef4019d1914f97">ConstantInt::get</a> (llvm::Type::getInt32Ty(Ctx), NumBitmapBytes)) INSTR_PROF_VTABLE_DATA(const uint64_t</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e53669d4dbc681568a033ce0051b110">llvm::Type::getInt64Ty</a> (Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96e50203ffa3df715148e5a5d2b9b107">ConstantInt::get</a> (llvm::Type::getInt64Ty(Ctx), IndexedInstrProf::ComputeHash(PGOVTableName))) INSTR_PROF_VTABLE_DATA(const IntPtrT</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb7ee946f46d707510ddfe66f33c6edb">llvm::PointerType::getUnqual</a> (Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61a3654a30b0808717e74cbaec8f663b">INSTR_PROF_VTABLE_DATA</a> (const uint32_t, llvm::Type::getInt32Ty(Ctx), VTableSize, ConstantInt::get(llvm::Type::getInt32Ty(Ctx), VTableSizeVal)) INSTR_PROF_VALUE_NODE(uint64_t</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe9a832fcb352e5f30ed785c06ff3570">llvm::Type::getInt64Ty</a> (Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae951b7a4602779927781573689e41578">ConstantInt::get</a> (llvm::Type::GetInt64Ty(Ctx), 0)) INSTR_PROF_VALUE_NODE(uint64_t</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe9a832fcb352e5f30ed785c06ff3570">llvm::Type::getInt64Ty</a> (Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f75103da3755b92eb2ffe87b86df14d">ConstantInt::get</a> (llvm::Type::GetInt64Ty(Ctx), 0)) INSTR_PROF_VALUE_NODE(PtrToNodeT</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22accad038c3bb897139bef42bf9e632">llvm::PointerType::getUnqual</a> (Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab68ea607e5a2a7e4c8516c92d768445c">ConstantInt::get</a> (llvm::PointerType::getUnqual(Ctx), 0)) INSTR_PROF_RAW_HEADER(uint64_t</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a000fd82e0825577455639986dccc1d03">CountersBegin</a> (uintptr_t) DataBegin) INSTR_PROF_RAW_HEADER(uint64_t</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr uintptr_t uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2140bc5b3a5b973c0ea311f10d339665">BitmapBegin</a> (uintptr_t) DataBegin) VALUE_PROF_FUNC_PARAM(uint64_t</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr uintptr_t uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13a4c3fa97efd682c349c55b52cf6d99">Type::getInt64Ty</a> (Ctx)) INSTR_PROF_COMMA VALUE_PROF_FUNC_PARAM(void *</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr uintptr_t uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb452c32f2f06ccfdb5a12dfe66202eb">PointerType::getUnqual</a> (Ctx)) INSTR_PROF_COMMA COVMAP_FUNC_RECORD(const int64_t</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr uintptr_t uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cbac04a21f12be016f1660fdb81b937">llvm::Type::getInt64Ty</a> (Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr uintptr_t uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab5ab0a502ae638d65b58aa52dc5c7e2">llvm::ConstantInt::get</a> (llvm::Type::getInt64Ty(Ctx), NameHash)) COVMAP_FUNC_RECORD(const uint32_t</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr uintptr_t uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52cb05ce4cc7e0cabb3c1d923a855120">llvm::Type::getInt32Ty</a> (Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr uintptr_t uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5c9cd1e40099d4a17499e05c29a3897">llvm::ConstantInt::get</a> (llvm::Type::getInt32Ty(Ctx), CoverageMapping.size())) COVMAP_FUNC_RECORD(const uint64_t</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr uintptr_t uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cbac04a21f12be016f1660fdb81b937">llvm::Type::getInt64Ty</a> (Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr uintptr_t uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf0d25641503b95280716a39316f1666">llvm::ConstantInt::get</a> (llvm::Type::getInt64Ty(Ctx), FuncHash)) COVMAP_HEADER(uint32_t</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr uintptr_t uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad37e20fe902b87a43f77c1c6075f8346">llvm::ConstantInt::get</a> (Int32Ty, NRecords)) COVMAP_HEADER(uint32_t</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr uintptr_t uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6f13707796d8025fc0b5849bc1e4f7a">llvm::ConstantInt::get</a> (Int32Ty, FilenamesSize)) COVMAP_HEADER(uint32_t</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr uintptr_t uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a270c104aba8485059bf01bd6a78e90">llvm::ConstantInt::get</a> (Int32Ty, CoverageMappingSize)) COVMAP_HEADER(uint32_t</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr uintptr_t uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9958148b32aaa7a2358ee25eb48201d">llvm::ConstantInt::get</a> (Int32Ty, CovMapVersion::CurrentVersion)) COVINIT_FUNC(IntPtrT</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr uintptr_t uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dbe6fa0a3f07775518609c082963314">llvm::PointerType::getUnqual</a> (Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr uintptr_t uintptr_t WriteoutF</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acebd5d673954341ac75c74e40734748d">COVINIT_FUNC</a> (IntPtrT, llvm::PointerType::getUnqual(Ctx), ResetFunction, ResetF) CovMapFunctionRecordV2()=delete</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness Endian&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad406eef6436923ee9251d065976f2028">getFuncHash</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness Endian&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8af933677c6962e6ed2a391693d47449">getDataSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness Endian&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae90f2ee6c112db32d4d3cf9a9a3e393c">getFuncNameRef</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness Endian&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5195dca17a38898707e15c2c46f2b7fd">getFuncName</a> (InstrProfSymtab &amp;ProfileNames, StringRef &amp;FuncName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness Endian&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab6c23e2207fd951c4f2ec6847317c297">advanceByOne</a> (const char *MappingBuf) const -&gt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#adfc4144e458ec3f710d79fcb6a18949e">ThisT</a> * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness Endian&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1750e1f657e31786989c4a606f385e03">getFilenamesRef</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness Endian&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac55ac9a9f5991a705aca7c621b30c157">getCoverageMapping</a> (const char *MappingBuf) const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab343075eb5039fde91e70927de54b80b">FuncHash</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85c26d5d40a32100f8a3b101af27556e">FunctionPointer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac95449eed053567defb8d9a375f9c11c">NumCounters</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d81627d3370ffee684b5207db7313f1">Int16ArrayTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12bba685e2d013f8cf9b33690515abe1">NumValueSites</a>[IPVK_Last+1]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb31d226aa2f73f363d5270d6d22d9e7">NumBitmapBytes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab48f7b34773777c9ef9d8746300dcd36">VTableNameHash</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35e6e61ff14f92143dda1db7bb82a9d0">VTablePointer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4253d1ac8c17c06f024d98ec015a2e65">Value</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3712639f986abfbf7ec06044cbaf7225">Count</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef8095173642431ebbc762025fa7661c">Next</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7a0c20446f268b51ac57762c3c69f7c">CountersDelta</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4fca4f5a0156ba91e01bb29ceb89e86">BitmapDelta</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr uintptr_t uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d69bdeeac481f54cee58fa937a484c0">TargetValue</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr uintptr_t uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8c2bd337eb3c376bb1b106e901bd829">Data</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr uintptr_t uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af63b9c5eea2c2ea9ec26e869cc397d6b">NameRef</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr uintptr_t uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcdb4ca975978fbc1ecd592e39c21e49">DataSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr uintptr_t uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a318fa32e8ae8b9f8239f5efce918c173">FuncHash</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr uintptr_t uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a802f1e4cd451599870c56021ae29d4f1">Int32Ty</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr uintptr_t uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae233e83d9962efe5ac6f4f4369efb5cf">NRecords</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr uintptr_t uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e68ee137236f62cd5cffdf873463b81">FilenamesSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr uintptr_t uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a354ed800f5cb75a04a37f0da72b5e0a5">CoverageSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr uintptr_t uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20d994dbff2ba4ecd321b88f7d3d62a5">Version</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionAddr VTableAddr uintptr_t uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0dffd3dd2e0cb1173f0e5eb315eb4ba">WriteoutFunction</a></td>
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


<p>Definition at line 1295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ThisT {#adfc4144e458ec3f710d79fcb6a18949e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::coverage::CovMapFunctionRecordV2::ThisT =  CovMapFunctionRecordV2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### advanceByOne() {#ab6c23e2207fd951c4f2ec6847317c297}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; const char *, const ThisT * &gt; llvm::coverage::CovMapFunctionRecordV2::advanceByOne (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * MappingBuf)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1049 of file InstrProfData.inc, definition at line 1049 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### BitmapBegin() {#a2140bc5b3a5b973c0ea311f10d339665}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV2::BitmapBegin (uintptr_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file InstrProfData.inc.</p>

</div>
</div>

### ConstantArray::get() {#aa080ab71a7e08fd9a6ac23cebecd6f20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr llvm::coverage::CovMapFunctionRecordV2::ConstantArray::get (<a href="#a6d81627d3370ffee684b5207db7313f1">Int16ArrayTy</a>, Int16ArrayVals)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file InstrProfData.inc.</p>

</div>
</div>

### ConstantInt::get() {#acea11458f4ef9e855dd2446e6ef755aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coverage::CovMapFunctionRecordV2::ConstantInt::get (<a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>(Ctx), Inc-&gt; getHash=) ->getZExtValue()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file InstrProfData.inc.</p>

</div>
</div>

### ConstantInt::get() {#a817881ee0e75219918aec00c1592cd27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr llvm::coverage::CovMapFunctionRecordV2::ConstantInt::get (<a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>(Ctx), <a href="#ac95449eed053567defb8d9a375f9c11c">NumCounters</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file InstrProfData.inc.</p>

</div>
</div>

### ConstantInt::get() {#a64a80b3006a2a77833ef4019d1914f97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr llvm::coverage::CovMapFunctionRecordV2::ConstantInt::get (<a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>(Ctx), <a href="#afb31d226aa2f73f363d5270d6d22d9e7">NumBitmapBytes</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file InstrProfData.inc.</p>

</div>
</div>

### ConstantInt::get() {#a96e50203ffa3df715148e5a5d2b9b107}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr llvm::coverage::CovMapFunctionRecordV2::ConstantInt::get (<a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>(Ctx), <a href="/web-llvm/docs/api/namespaces/llvm/indexedinstrprof/#a26647986f25d6168afc4204fd79873df">IndexedInstrProf::ComputeHash</a>(PGOVTableName))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file InstrProfData.inc.</p>

</div>
</div>

### ConstantInt::get() {#ae951b7a4602779927781573689e41578}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr llvm::coverage::CovMapFunctionRecordV2::ConstantInt::get (llvm::Type::GetInt64Ty(Ctx), 0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file InstrProfData.inc.</p>

</div>
</div>

### ConstantInt::get() {#a5f75103da3755b92eb2ffe87b86df14d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr llvm::coverage::CovMapFunctionRecordV2::ConstantInt::get (llvm::Type::GetInt64Ty(Ctx), 0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file InstrProfData.inc.</p>

</div>
</div>

### ConstantInt::get() {#ab68ea607e5a2a7e4c8516c92d768445c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr llvm::coverage::CovMapFunctionRecordV2::ConstantInt::get (<a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>(Ctx), 0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file InstrProfData.inc.</p>

</div>
</div>

### CountersBegin() {#a000fd82e0825577455639986dccc1d03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t llvm::coverage::CovMapFunctionRecordV2::CountersBegin (uintptr_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file InstrProfData.inc.</p>

</div>
</div>

### COVINIT\_FUNC() {#acebd5d673954341ac75c74e40734748d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t WriteoutF llvm::coverage::CovMapFunctionRecordV2::COVINIT_FUNC (IntPtrT, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>(Ctx), ResetFunction, ResetF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 315 of file InstrProfData.inc.</p>

</div>
</div>

### getCoverageMapping() {#ac55ac9a9f5991a705aca7c621b30c157}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::coverage::CovMapFunctionRecordV2::getCoverageMapping (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * MappingBuf)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1058 of file InstrProfData.inc, definition at line 1058 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### getDataSize() {#a8af933677c6962e6ed2a391693d47449}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::coverage::CovMapFunctionRecordV2::getDataSize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1033 of file InstrProfData.inc, definition at line 1033 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### getFilenamesRef() {#a1750e1f657e31786989c4a606f385e03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::coverage::CovMapFunctionRecordV2::getFilenamesRef ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1053 of file InstrProfData.inc, definition at line 1053 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### getFuncHash() {#ad406eef6436923ee9251d065976f2028}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::coverage::CovMapFunctionRecordV2::getFuncHash ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1029 of file InstrProfData.inc, definition at line 1029 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### getFuncName() {#a5195dca17a38898707e15c2c46f2b7fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::coverage::CovMapFunctionRecordV2::getFuncName (<a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab">InstrProfSymtab</a> &amp; ProfileNames, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; FuncName)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1042 of file InstrProfData.inc, definition at line 1042 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### getFuncNameRef() {#ae90f2ee6c112db32d4d3cf9a9a3e393c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::coverage::CovMapFunctionRecordV2::getFuncNameRef ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1037 of file InstrProfData.inc, definition at line 1037 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### INSTR\_PROF\_DATA() {#ab9ac4f7199d9c210f512f4d62d52afaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coverage::CovMapFunctionRecordV2::INSTR_PROF_DATA (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>(Ctx), <a href="#af63b9c5eea2c2ea9ec26e869cc397d6b">NameRef</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a969709dd49c28865a482d8b870f87c46">ConstantInt::get</a>(<a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>(Ctx), <a href="/web-llvm/docs/api/namespaces/llvm/indexedinstrprof/#a26647986f25d6168afc4204fd79873df">IndexedInstrProf::ComputeHash</a>(<a href="/web-llvm/docs/api/namespaces/llvm/#a847a04fa34e6ed7f199e9f7704ab706f">getPGOFuncNameVarInitializer</a>(Inc-&gt;<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp/#a2ee79648e8bce3ddbb26358ff10e3e82">getName</a>()))))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_DATA() {#a608a6de3e222a2a193251c3c1a50da1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr llvm::coverage::CovMapFunctionRecordV2::INSTR_PROF_DATA (IntPtrT, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>(Ctx), Values, ValuesPtrExpr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file InstrProfData.inc.</p>

</div>
</div>

### INSTR\_PROF\_VTABLE\_DATA() {#a61a3654a30b0808717e74cbaec8f663b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr llvm::coverage::CovMapFunctionRecordV2::INSTR_PROF_VTABLE_DATA (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>(Ctx), VTableSize, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a969709dd49c28865a482d8b870f87c46">ConstantInt::get</a>(<a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>(Ctx), VTableSizeVal))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file InstrProfData.inc.</p>

</div>
</div>

### llvm::ConstantInt::get() {#aab5ab0a502ae638d65b58aa52dc5c7e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV2::llvm::ConstantInt::get (<a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>(Ctx), NameHash)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 264 of file InstrProfData.inc.</p>

</div>
</div>

### llvm::ConstantInt::get() {#af5c9cd1e40099d4a17499e05c29a3897}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV2::llvm::ConstantInt::get (<a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>(Ctx), CoverageMapping. size=())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 268 of file InstrProfData.inc.</p>

</div>
</div>

### llvm::ConstantInt::get() {#aaf0d25641503b95280716a39316f1666}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV2::llvm::ConstantInt::get (<a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>(Ctx), <a href="#ab343075eb5039fde91e70927de54b80b">FuncHash</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 271 of file InstrProfData.inc.</p>

</div>
</div>

### llvm::ConstantInt::get() {#ad37e20fe902b87a43f77c1c6075f8346}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV2::llvm::ConstantInt::get (<a href="#a802f1e4cd451599870c56021ae29d4f1">Int32Ty</a>, <a href="#ae233e83d9962efe5ac6f4f4369efb5cf">NRecords</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 297 of file InstrProfData.inc.</p>

</div>
</div>

### llvm::ConstantInt::get() {#af6f13707796d8025fc0b5849bc1e4f7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV2::llvm::ConstantInt::get (<a href="#a802f1e4cd451599870c56021ae29d4f1">Int32Ty</a>, <a href="#a7e68ee137236f62cd5cffdf873463b81">FilenamesSize</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 299 of file InstrProfData.inc.</p>

</div>
</div>

### llvm::ConstantInt::get() {#a2a270c104aba8485059bf01bd6a78e90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV2::llvm::ConstantInt::get (<a href="#a802f1e4cd451599870c56021ae29d4f1">Int32Ty</a>, CoverageMappingSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 301 of file InstrProfData.inc.</p>

</div>
</div>

### llvm::ConstantInt::get() {#ab9958148b32aaa7a2358ee25eb48201d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV2::llvm::ConstantInt::get (<a href="#a802f1e4cd451599870c56021ae29d4f1">Int32Ty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coverage/#a1f74a57a4d0c2ea7ebb8fb8767d66000abd6806945019b5af73b2f980a24f5b03">CovMapVersion::CurrentVersion</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 303 of file InstrProfData.inc.</p>

</div>
</div>

### llvm::PointerType::getUnqual() {#af617e126cbe8b17158fee6ddc2d34238}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coverage::CovMapFunctionRecordV2::llvm::PointerType::getUnqual (Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file InstrProfData.inc.</p>

</div>
</div>

### llvm::PointerType::getUnqual() {#acb7ee946f46d707510ddfe66f33c6edb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr llvm::coverage::CovMapFunctionRecordV2::llvm::PointerType::getUnqual (Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file InstrProfData.inc.</p>

</div>
</div>

### llvm::PointerType::getUnqual() {#a22accad038c3bb897139bef42bf9e632}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr llvm::coverage::CovMapFunctionRecordV2::llvm::PointerType::getUnqual (Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file InstrProfData.inc.</p>

</div>
</div>

### llvm::PointerType::getUnqual() {#a0dbe6fa0a3f07775518609c082963314}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV2::llvm::PointerType::getUnqual (Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 313 of file InstrProfData.inc.</p>

</div>
</div>

### llvm::Type::getInt32Ty() {#a9dde80a8c60c0a77f8ac969d0a9b8d10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr llvm::coverage::CovMapFunctionRecordV2::llvm::Type::getInt32Ty (Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file InstrProfData.inc.</p>

</div>
</div>

### llvm::Type::getInt32Ty() {#a9dde80a8c60c0a77f8ac969d0a9b8d10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr llvm::coverage::CovMapFunctionRecordV2::llvm::Type::getInt32Ty (Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file InstrProfData.inc.</p>

</div>
</div>

### llvm::Type::getInt32Ty() {#a52cb05ce4cc7e0cabb3c1d923a855120}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV2::llvm::Type::getInt32Ty (Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 267 of file InstrProfData.inc.</p>

</div>
</div>

### llvm::Type::getInt64Ty() {#a9c38c917e96172dd6fa5600c60da5baa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coverage::CovMapFunctionRecordV2::llvm::Type::getInt64Ty (Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file InstrProfData.inc.</p>

</div>
</div>

### llvm::Type::getInt64Ty() {#a6e53669d4dbc681568a033ce0051b110}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr llvm::coverage::CovMapFunctionRecordV2::llvm::Type::getInt64Ty (Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file InstrProfData.inc.</p>

</div>
</div>

### llvm::Type::getInt64Ty() {#abe9a832fcb352e5f30ed785c06ff3570}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr llvm::coverage::CovMapFunctionRecordV2::llvm::Type::getInt64Ty (Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file InstrProfData.inc.</p>

</div>
</div>

### llvm::Type::getInt64Ty() {#abe9a832fcb352e5f30ed785c06ff3570}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr llvm::coverage::CovMapFunctionRecordV2::llvm::Type::getInt64Ty (Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file InstrProfData.inc.</p>

</div>
</div>

### llvm::Type::getInt64Ty() {#a6cbac04a21f12be016f1660fdb81b937}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV2::llvm::Type::getInt64Ty (Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 263 of file InstrProfData.inc.</p>

</div>
</div>

### llvm::Type::getInt64Ty() {#a6cbac04a21f12be016f1660fdb81b937}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV2::llvm::Type::getInt64Ty (Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 270 of file InstrProfData.inc.</p>

</div>
</div>

### PointerType::getUnqual() {#aeb452c32f2f06ccfdb5a12dfe66202eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV2::PointerType::getUnqual (Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 189 of file InstrProfData.inc.</p>

</div>
</div>

### Type::getInt64Ty() {#a13a4c3fa97efd682c349c55b52cf6d99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV2::Type::getInt64Ty (Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file InstrProfData.inc.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BitmapDelta {#aa4fca4f5a0156ba91e01bb29ceb89e86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t llvm::coverage::CovMapFunctionRecordV2::BitmapDelta</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 167 of file InstrProfData.inc, definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### Count {#a3712639f986abfbf7ec06044cbaf7225}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr llvm::coverage::CovMapFunctionRecordV2::Count</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 139 of file InstrProfData.inc, definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### CountersDelta {#aa7a0c20446f268b51ac57762c3c69f7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr llvm::coverage::CovMapFunctionRecordV2::CountersDelta</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 165 of file InstrProfData.inc, definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### CoverageSize {#a354ed800f5cb75a04a37f0da72b5e0a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV2::CoverageSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 300 of file InstrProfData.inc, definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### Data {#ad8c2bd337eb3c376bb1b106e901bd829}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV2::Data</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 189 of file InstrProfData.inc, definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### DataSize {#afcdb4ca975978fbc1ecd592e39c21e49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV2::DataSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 267 of file InstrProfData.inc, definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### FilenamesSize {#a7e68ee137236f62cd5cffdf873463b81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV2::FilenamesSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 298 of file InstrProfData.inc, definition at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### FuncHash {#ab343075eb5039fde91e70927de54b80b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coverage::CovMapFunctionRecordV2::FuncHash</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 78 of file InstrProfData.inc, definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### FuncHash {#a318fa32e8ae8b9f8239f5efce918c173}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV2::FuncHash</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 270 of file InstrProfData.inc, definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### FunctionPointer {#a85c26d5d40a32100f8a3b101af27556e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coverage::CovMapFunctionRecordV2::FunctionPointer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 87 of file InstrProfData.inc, definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### Int16ArrayTy {#a6d81627d3370ffee684b5207db7313f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr llvm::coverage::CovMapFunctionRecordV2::Int16ArrayTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 93 of file InstrProfData.inc, definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### Int32Ty {#a802f1e4cd451599870c56021ae29d4f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV2::Int32Ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 296 of file InstrProfData.inc, definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### NameRef {#af63b9c5eea2c2ea9ec26e869cc397d6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV2::NameRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 263 of file InstrProfData.inc, definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### Next {#aef8095173642431ebbc762025fa7661c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr llvm::coverage::CovMapFunctionRecordV2::Next</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 141 of file InstrProfData.inc, definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### NRecords {#ae233e83d9962efe5ac6f4f4369efb5cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV2::NRecords</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 296 of file InstrProfData.inc, definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### NumBitmapBytes {#afb31d226aa2f73f363d5270d6d22d9e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr llvm::coverage::CovMapFunctionRecordV2::NumBitmapBytes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 95 of file InstrProfData.inc, definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### NumCounters {#ac95449eed053567defb8d9a375f9c11c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr llvm::coverage::CovMapFunctionRecordV2::NumCounters</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 91 of file InstrProfData.inc, definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### NumValueSites {#a12bba685e2d013f8cf9b33690515abe1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr llvm::coverage::CovMapFunctionRecordV2::NumValueSites[IPVK_Last+1]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 93 of file InstrProfData.inc, definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### TargetValue {#a5d69bdeeac481f54cee58fa937a484c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV2::TargetValue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 187 of file InstrProfData.inc, definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### Value {#a4253d1ac8c17c06f024d98ec015a2e65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr llvm::coverage::CovMapFunctionRecordV2::Value</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 137 of file InstrProfData.inc, definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### Version {#a20d994dbff2ba4ecd321b88f7d3d62a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV2::Version</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 302 of file InstrProfData.inc, definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### VTableNameHash {#ab48f7b34773777c9ef9d8746300dcd36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr llvm::coverage::CovMapFunctionRecordV2::VTableNameHash</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 110 of file InstrProfData.inc, definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### VTablePointer {#a35e6e61ff14f92143dda1db7bb82a9d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr llvm::coverage::CovMapFunctionRecordV2::VTablePointer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 113 of file InstrProfData.inc, definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### WriteoutFunction {#ab0dffd3dd2e0cb1173f0e5eb315eb4ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV2::WriteoutFunction</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 313 of file InstrProfData.inc, definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a></li>
<li>InstrProfData.inc</li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
