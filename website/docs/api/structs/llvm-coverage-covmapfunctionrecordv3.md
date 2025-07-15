---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/coverage/covmapfunctionrecordv3
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CovMapFunctionRecordV3` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::coverage::CovMapFunctionRecordV3 { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">llvm/ProfileData/Coverage/CoverageMapping.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97c7bf8bd1a08a130a33640f05599438">ThisT</a> = <a href="/web-llvm/docs/api/structs/llvm/coverage/covmapfunctionrecordv3">CovMapFunctionRecordV3</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca725cdc0a276bc882981b0ddf24d11c">INSTR_PROF_DATA</a> (const uint64_t, llvm::Type::getInt64Ty(Ctx), NameRef, ConstantInt::get(llvm::Type::getInt64Ty(Ctx), IndexedInstrProf::ComputeHash(getPGOFuncNameVarInitializer(Inc-&gt;getName())))) INSTR_PROF_DATA(const uint64_t</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75177ded4586cc5648bf78103ee6089f">llvm::Type::getInt64Ty</a> (Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70e2f2248600575ce7a4dd76a51fa57a">ConstantInt::get</a> (llvm::Type::getInt64Ty(Ctx), Inc-&gt;getHash() -&gt;getZExtValue())) INSTR_PROF_DATA(const IntPtrT</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0884c3fbb47eb1871d3dc5a5c30ae6d5">llvm::PointerType::getUnqual</a> (Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ae9a2d314cc8233443cdbffe8e56a3f">INSTR_PROF_DATA</a> (IntPtrT, llvm::PointerType::getUnqual(Ctx), Values, ValuesPtrExpr) INSTR_PROF_DATA(const uint32_t</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e88d0e0cd4e878b46b239e5b6488526">llvm::Type::getInt32Ty</a> (Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8245431e136cfc564da1b0b1f07a6331">ConstantInt::get</a> (llvm::Type::getInt32Ty(Ctx), NumCounters)) INSTR_PROF_DATA(const uint16_t</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf42be1ddf6bc789aea2aa0f62e06a1f">ConstantArray::get</a> (Int16ArrayTy, Int16ArrayVals)) INSTR_PROF_DATA(const uint32_t</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e88d0e0cd4e878b46b239e5b6488526">llvm::Type::getInt32Ty</a> (Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ac9b9880c1790ecddf4beab77b60921">ConstantInt::get</a> (llvm::Type::getInt32Ty(Ctx), NumBitmapBytes)) INSTR_PROF_VTABLE_DATA(const uint64_t</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b0701adb323e7e14a9f7be3815ecbec">llvm::Type::getInt64Ty</a> (Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6959cbd97799820a8d4ceeae59b33f5c">ConstantInt::get</a> (llvm::Type::getInt64Ty(Ctx), IndexedInstrProf::ComputeHash(PGOVTableName))) INSTR_PROF_VTABLE_DATA(const IntPtrT</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b57b65cbb41983527526f20364d9206">llvm::PointerType::getUnqual</a> (Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf2e4fb149c052263201d5605dcfc1e2">INSTR_PROF_VTABLE_DATA</a> (const uint32_t, llvm::Type::getInt32Ty(Ctx), VTableSize, ConstantInt::get(llvm::Type::getInt32Ty(Ctx), VTableSizeVal)) INSTR_PROF_VALUE_NODE(uint64_t</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fab9f7de92e20bcf671d8376c957d5b">llvm::Type::getInt64Ty</a> (Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd83c5bfbd9771b53bd8226600f4d4b6">ConstantInt::get</a> (llvm::Type::GetInt64Ty(Ctx), 0)) INSTR_PROF_VALUE_NODE(uint64_t</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fab9f7de92e20bcf671d8376c957d5b">llvm::Type::getInt64Ty</a> (Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe03df0331848a0b736b5fbff4d72c78">ConstantInt::get</a> (llvm::Type::GetInt64Ty(Ctx), 0)) INSTR_PROF_VALUE_NODE(PtrToNodeT</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54cc6aa0719a701a9c2ae29e1ce96e6c">llvm::PointerType::getUnqual</a> (Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cf0bb907eb1be34d87391416b951392">ConstantInt::get</a> (llvm::PointerType::getUnqual(Ctx), 0)) INSTR_PROF_RAW_HEADER(uint64_t</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a614b7d789d0288628f02552b0612d27b">CountersBegin</a> (uintptr_t) DataBegin) INSTR_PROF_RAW_HEADER(uint64_t</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cc2a09eced63d84265a8ddf9985ec60">BitmapBegin</a> (uintptr_t) DataBegin) VALUE_PROF_FUNC_PARAM(uint64_t</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2452625c3989ec1f75ab7a9bd3c5112f">Type::getInt64Ty</a> (Ctx)) INSTR_PROF_COMMA VALUE_PROF_FUNC_PARAM(void *</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac58808184042c36d9fb31d4ec8261bc8">PointerType::getUnqual</a> (Ctx)) INSTR_PROF_COMMA COVMAP_FUNC_RECORD(const int64_t</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7283d8febf21e2f32a56d3bad09fa868">llvm::Type::getInt64Ty</a> (Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13acb70e61ab2795e5959bf1be03646e">llvm::ConstantInt::get</a> (llvm::Type::getInt64Ty(Ctx), NameHash)) COVMAP_FUNC_RECORD(const uint32_t</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbfdae92913004959f3ebd3b28b09143">llvm::Type::getInt32Ty</a> (Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a185b289865ae19e504cae70bcb5cc587">llvm::ConstantInt::get</a> (llvm::Type::getInt32Ty(Ctx), CoverageMapping.size())) COVMAP_FUNC_RECORD(const uint64_t</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7283d8febf21e2f32a56d3bad09fa868">llvm::Type::getInt64Ty</a> (Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7b9f150907f67ddfea220dcbbf9e03b">llvm::ConstantInt::get</a> (llvm::Type::getInt64Ty(Ctx), FuncHash)) COVMAP_FUNC_RECORD(const uint64_t</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7283d8febf21e2f32a56d3bad09fa868">llvm::Type::getInt64Ty</a> (Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7df0a592066717b892253387fe3f418c">llvm::ConstantInt::get</a> (llvm::Type::getInt64Ty(Ctx), FilenamesRef)) COVMAP_FUNC_RECORD(const char</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6143b3a9e83bc2c63389a55b4ad16ff1">llvm::ArrayType::get</a> (llvm::Type::getInt8Ty(Ctx), CoverageMapping.size())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6d296772222083f41c1ec50c39b47ae">llvm::ConstantDataArray::getRaw</a> (CoverageMapping, CoverageMapping.size(), llvm::Type::getInt8Ty(Ctx))) COVMAP_HEADER(uint32_t</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7774ff8985da40e14521b403e6c38a5d">llvm::ConstantInt::get</a> (Int32Ty, NRecords)) COVMAP_HEADER(uint32_t</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf558a68a4e5f80e53c5441ea82f1144">llvm::ConstantInt::get</a> (Int32Ty, FilenamesSize)) COVMAP_HEADER(uint32_t</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca7a0130bb41d78c5d545f2314d7a6c1">llvm::ConstantInt::get</a> (Int32Ty, CoverageMappingSize)) COVMAP_HEADER(uint32_t</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a652b59d72023587667a895896595b3f2">llvm::ConstantInt::get</a> (Int32Ty, CovMapVersion::CurrentVersion)) COVINIT_FUNC(IntPtrT</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b894502e55a92954ce30776053768f3">llvm::PointerType::getUnqual</a> (Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afab7691f81fb85189f22b87be50b6f68">COVINIT_FUNC</a> (IntPtrT, llvm::PointerType::getUnqual(Ctx), ResetFunction, ResetF) CovMapFunctionRecordV3()=delete</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a04838974aa74da37938100e7bde9b5f0">getFuncHash</a> () const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab20497e686699292b3dc6d5fa56198a7">getDataSize</a> () const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8eabf8b7188573ac4f9fe214e3d8daf6">getFuncNameRef</a> () const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aae26f9280f5560d10db6b56c25ccebc1">getFuncName</a> (InstrProfSymtab &amp;ProfileNames, StringRef &amp;FuncName) const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aacd1c3b629e7654b6815ea47208b56fc">getFilenamesRef</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the filename set reference. <a href="#aacd1c3b629e7654b6815ea47208b56fc">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9dd3a6a6598cd669fa947a6362072921">getCoverageMapping</a> (const char *) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read the inline coverage mapping. <a href="#a9dd3a6a6598cd669fa947a6362072921">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5f2f03ee090cd22a2f83984e04029dad">advanceByOne</a> (const char *) const -&gt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/coverage/covmapfunctionrecordv3">CovMapFunctionRecordV3</a> * &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78e40c8fb9f6af346bf075ccd48a3ad1">FuncHash</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a220912f0d4f5b54f67bd99f6e6929267">FunctionPointer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae82a685a089f405364e9903388032293">NumCounters</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55ef5e453fe1a96a29a5d7713b64a6db">Int16ArrayTy</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d754125b984fdc70c7e23e7500fcb4e">NumValueSites</a>[IPVK_Last+1]</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7a990cceb8715d2ffdc2a5418044ef9">NumBitmapBytes</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84e5d26f9b2f93776b197750c77e208f">VTableNameHash</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaeeff5c4d242145e6f92a62956748aa">VTablePointer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68527845e43960ac580405dc5d4e028e">Value</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a036a459f123f4b801f0c6693b02ba74d">Count</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a559cfbd20237656444d8138d5291a5">Next</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32f02bcf9ac5a476559d3ddfc0a414d9">CountersDelta</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea320f75c03324f80770877aeacbc84e">BitmapDelta</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe6f67e40d797be8ba28ca711cc2ea15">TargetValue</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaca0ca689412d2670139ddeefa15cea9">Data</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f8a8b1bd3b8fbe228336fe494b13308">NameRef</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abad71b13ecf1bdeaaedfac205f35a7af">DataSize</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aceac10f25aa6a347ea4ed466aedb7e8d">FuncHash</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d9ab29cc0274986a13b3447430a3388">FilenamesRef</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53f7f07e6f627017cea3455c17b5c35d">CoverageMapping</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4c4990fc18a2c4ca149c991b0718b7b">Int32Ty</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92128e18116745cc76289da1ed911980">NRecords</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e8e0b42895d5cff1a4353d832238f39">FilenamesSize</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fe5817ad2957a411cd28f817f159d80">CoverageSize</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8714ed0173a4e15ec2d6c8c86b776ae7">Version</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef482761ffa17789ffc26fea96bb3237">WriteoutFunction</a></td>
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


<p>Definition at line 1339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ThisT {#a97c7bf8bd1a08a130a33640f05599438}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::coverage::CovMapFunctionRecordV3::ThisT =  CovMapFunctionRecordV3</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### advanceByOne() {#a5f2f03ee090cd22a2f83984e04029dad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; const char *, const CovMapFunctionRecordV3 * &gt; llvm::coverage::CovMapFunctionRecordV3::advanceByOne (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *)</td>
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



<p>Declaration at line 1063 of file InstrProfData.inc, definition at line 1063 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### BitmapBegin() {#a8cc2a09eced63d84265a8ddf9985ec60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV3::BitmapBegin (uintptr_t)</td>
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

### ConstantArray::get() {#adf42be1ddf6bc789aea2aa0f62e06a1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr llvm::coverage::CovMapFunctionRecordV3::ConstantArray::get (<a href="#a55ef5e453fe1a96a29a5d7713b64a6db">Int16ArrayTy</a>, Int16ArrayVals)</td>
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

### ConstantInt::get() {#a70e2f2248600575ce7a4dd76a51fa57a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coverage::CovMapFunctionRecordV3::ConstantInt::get (<a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>(Ctx), Inc-&gt; getHash=) ->getZExtValue()</td>
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

### ConstantInt::get() {#a8245431e136cfc564da1b0b1f07a6331}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr llvm::coverage::CovMapFunctionRecordV3::ConstantInt::get (<a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>(Ctx), <a href="#ae82a685a089f405364e9903388032293">NumCounters</a>)</td>
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

### ConstantInt::get() {#a4ac9b9880c1790ecddf4beab77b60921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr llvm::coverage::CovMapFunctionRecordV3::ConstantInt::get (<a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>(Ctx), <a href="#ac7a990cceb8715d2ffdc2a5418044ef9">NumBitmapBytes</a>)</td>
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

### ConstantInt::get() {#a6959cbd97799820a8d4ceeae59b33f5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr llvm::coverage::CovMapFunctionRecordV3::ConstantInt::get (<a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>(Ctx), <a href="/web-llvm/docs/api/namespaces/llvm/indexedinstrprof/#a26647986f25d6168afc4204fd79873df">IndexedInstrProf::ComputeHash</a>(PGOVTableName))</td>
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

### ConstantInt::get() {#afd83c5bfbd9771b53bd8226600f4d4b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr llvm::coverage::CovMapFunctionRecordV3::ConstantInt::get (llvm::Type::GetInt64Ty(Ctx), 0)</td>
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

### ConstantInt::get() {#abe03df0331848a0b736b5fbff4d72c78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr llvm::coverage::CovMapFunctionRecordV3::ConstantInt::get (llvm::Type::GetInt64Ty(Ctx), 0)</td>
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

### ConstantInt::get() {#a3cf0bb907eb1be34d87391416b951392}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr llvm::coverage::CovMapFunctionRecordV3::ConstantInt::get (<a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>(Ctx), 0)</td>
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

### CountersBegin() {#a614b7d789d0288628f02552b0612d27b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t llvm::coverage::CovMapFunctionRecordV3::CountersBegin (uintptr_t)</td>
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

### COVINIT\_FUNC() {#afab7691f81fb85189f22b87be50b6f68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t WriteoutF llvm::coverage::CovMapFunctionRecordV3::COVINIT_FUNC (IntPtrT, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>(Ctx), ResetFunction, ResetF)</td>
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

### getCoverageMapping() {#a9dd3a6a6598cd669fa947a6362072921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::coverage::CovMapFunctionRecordV3::getCoverageMapping (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *)</td>
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

<p>Read the inline coverage mapping.</p>


<p>Ignore the buffer parameter, it is for out-of-line coverage mapping data only.</p>


<p>Declaration at line 1055 of file InstrProfData.inc, definition at line 1055 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### getDataSize() {#ab20497e686699292b3dc6d5fa56198a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::coverage::CovMapFunctionRecordV3::getDataSize ()</td>
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

### getFilenamesRef() {#aacd1c3b629e7654b6815ea47208b56fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::coverage::CovMapFunctionRecordV3::getFilenamesRef ()</td>
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

<p>Get the filename set reference.</p>

<p>Declaration at line 1048 of file InstrProfData.inc, definition at line 1048 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### getFuncHash() {#a04838974aa74da37938100e7bde9b5f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::coverage::CovMapFunctionRecordV3::getFuncHash ()</td>
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

### getFuncName() {#aae26f9280f5560d10db6b56c25ccebc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::coverage::CovMapFunctionRecordV3::getFuncName (<a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab">InstrProfSymtab</a> &amp; ProfileNames, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; FuncName)</td>
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

### getFuncNameRef() {#a8eabf8b7188573ac4f9fe214e3d8daf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::coverage::CovMapFunctionRecordV3::getFuncNameRef ()</td>
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

### INSTR\_PROF\_DATA() {#aca725cdc0a276bc882981b0ddf24d11c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coverage::CovMapFunctionRecordV3::INSTR_PROF_DATA (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>(Ctx), <a href="#a2f8a8b1bd3b8fbe228336fe494b13308">NameRef</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a969709dd49c28865a482d8b870f87c46">ConstantInt::get</a>(<a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>(Ctx), <a href="/web-llvm/docs/api/namespaces/llvm/indexedinstrprof/#a26647986f25d6168afc4204fd79873df">IndexedInstrProf::ComputeHash</a>(<a href="/web-llvm/docs/api/namespaces/llvm/#a847a04fa34e6ed7f199e9f7704ab706f">getPGOFuncNameVarInitializer</a>(Inc-&gt;<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp/#a2ee79648e8bce3ddbb26358ff10e3e82">getName</a>()))))</td>
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

### INSTR\_PROF\_DATA() {#a3ae9a2d314cc8233443cdbffe8e56a3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr llvm::coverage::CovMapFunctionRecordV3::INSTR_PROF_DATA (IntPtrT, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>(Ctx), Values, ValuesPtrExpr)</td>
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

### INSTR\_PROF\_VTABLE\_DATA() {#acf2e4fb149c052263201d5605dcfc1e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr llvm::coverage::CovMapFunctionRecordV3::INSTR_PROF_VTABLE_DATA (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>(Ctx), VTableSize, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a969709dd49c28865a482d8b870f87c46">ConstantInt::get</a>(<a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>(Ctx), VTableSizeVal))</td>
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

### llvm::ArrayType::get() {#a6143b3a9e83bc2c63389a55b4ad16ff1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV3::llvm::ArrayType::get (<a href="/web-llvm/docs/api/classes/llvm/type/#a7ba5de75f50bb4a4ba920698edf39b28">llvm::Type::getInt8Ty</a>(Ctx), CoverageMapping. size=())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 278 of file InstrProfData.inc.</p>

</div>
</div>

### llvm::ConstantDataArray::getRaw() {#ac6d296772222083f41c1ec50c39b47ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV3::llvm::ConstantDataArray::getRaw (<a href="/web-llvm/docs/api/classes/llvm/coverage/coveragemapping">CoverageMapping</a>, CoverageMapping. size=(), <a href="/web-llvm/docs/api/classes/llvm/type/#a7ba5de75f50bb4a4ba920698edf39b28">llvm::Type::getInt8Ty</a>(Ctx))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 281 of file InstrProfData.inc.</p>

</div>
</div>

### llvm::ConstantInt::get() {#a13acb70e61ab2795e5959bf1be03646e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV3::llvm::ConstantInt::get (<a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>(Ctx), NameHash)</td>
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

### llvm::ConstantInt::get() {#a185b289865ae19e504cae70bcb5cc587}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV3::llvm::ConstantInt::get (<a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>(Ctx), CoverageMapping. size=())</td>
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

### llvm::ConstantInt::get() {#ac7b9f150907f67ddfea220dcbbf9e03b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV3::llvm::ConstantInt::get (<a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>(Ctx), <a href="#a78e40c8fb9f6af346bf075ccd48a3ad1">FuncHash</a>)</td>
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

### llvm::ConstantInt::get() {#a7df0a592066717b892253387fe3f418c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV3::llvm::ConstantInt::get (<a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>(Ctx), <a href="#a2d9ab29cc0274986a13b3447430a3388">FilenamesRef</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 275 of file InstrProfData.inc.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/coverage/mcdc/#a664abf9526909f1ea77ab40a4da231b9">llvm::coverage::mcdc::getParams</a> and <a href="/web-llvm/docs/api/structs/llvm/coverage/countermappingregion/#ae0714010bf7401f3ac8f7d0da65638ae">llvm::coverage::CounterMappingRegion::MCDCParams</a>.</p>

</div>
</div>

### llvm::ConstantInt::get() {#a7774ff8985da40e14521b403e6c38a5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV3::llvm::ConstantInt::get (<a href="#ad4c4990fc18a2c4ca149c991b0718b7b">Int32Ty</a>, <a href="#a92128e18116745cc76289da1ed911980">NRecords</a>)</td>
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

### llvm::ConstantInt::get() {#adf558a68a4e5f80e53c5441ea82f1144}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV3::llvm::ConstantInt::get (<a href="#ad4c4990fc18a2c4ca149c991b0718b7b">Int32Ty</a>, <a href="#a9e8e0b42895d5cff1a4353d832238f39">FilenamesSize</a>)</td>
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

### llvm::ConstantInt::get() {#aca7a0130bb41d78c5d545f2314d7a6c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV3::llvm::ConstantInt::get (<a href="#ad4c4990fc18a2c4ca149c991b0718b7b">Int32Ty</a>, CoverageMappingSize)</td>
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

### llvm::ConstantInt::get() {#a652b59d72023587667a895896595b3f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV3::llvm::ConstantInt::get (<a href="#ad4c4990fc18a2c4ca149c991b0718b7b">Int32Ty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coverage/#a1f74a57a4d0c2ea7ebb8fb8767d66000abd6806945019b5af73b2f980a24f5b03">CovMapVersion::CurrentVersion</a>)</td>
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

### llvm::PointerType::getUnqual() {#a0884c3fbb47eb1871d3dc5a5c30ae6d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coverage::CovMapFunctionRecordV3::llvm::PointerType::getUnqual (Ctx)</td>
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

### llvm::PointerType::getUnqual() {#a9b57b65cbb41983527526f20364d9206}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr llvm::coverage::CovMapFunctionRecordV3::llvm::PointerType::getUnqual (Ctx)</td>
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

### llvm::PointerType::getUnqual() {#a54cc6aa0719a701a9c2ae29e1ce96e6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr llvm::coverage::CovMapFunctionRecordV3::llvm::PointerType::getUnqual (Ctx)</td>
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

### llvm::PointerType::getUnqual() {#a4b894502e55a92954ce30776053768f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV3::llvm::PointerType::getUnqual (Ctx)</td>
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

### llvm::Type::getInt32Ty() {#a6e88d0e0cd4e878b46b239e5b6488526}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr llvm::coverage::CovMapFunctionRecordV3::llvm::Type::getInt32Ty (Ctx)</td>
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

### llvm::Type::getInt32Ty() {#a6e88d0e0cd4e878b46b239e5b6488526}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr llvm::coverage::CovMapFunctionRecordV3::llvm::Type::getInt32Ty (Ctx)</td>
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

### llvm::Type::getInt32Ty() {#afbfdae92913004959f3ebd3b28b09143}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV3::llvm::Type::getInt32Ty (Ctx)</td>
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

### llvm::Type::getInt64Ty() {#a75177ded4586cc5648bf78103ee6089f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coverage::CovMapFunctionRecordV3::llvm::Type::getInt64Ty (Ctx)</td>
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

### llvm::Type::getInt64Ty() {#a3b0701adb323e7e14a9f7be3815ecbec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr llvm::coverage::CovMapFunctionRecordV3::llvm::Type::getInt64Ty (Ctx)</td>
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

### llvm::Type::getInt64Ty() {#a3fab9f7de92e20bcf671d8376c957d5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr llvm::coverage::CovMapFunctionRecordV3::llvm::Type::getInt64Ty (Ctx)</td>
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

### llvm::Type::getInt64Ty() {#a3fab9f7de92e20bcf671d8376c957d5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr llvm::coverage::CovMapFunctionRecordV3::llvm::Type::getInt64Ty (Ctx)</td>
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

### llvm::Type::getInt64Ty() {#a7283d8febf21e2f32a56d3bad09fa868}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV3::llvm::Type::getInt64Ty (Ctx)</td>
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

### llvm::Type::getInt64Ty() {#a7283d8febf21e2f32a56d3bad09fa868}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV3::llvm::Type::getInt64Ty (Ctx)</td>
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

### llvm::Type::getInt64Ty() {#a7283d8febf21e2f32a56d3bad09fa868}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV3::llvm::Type::getInt64Ty (Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 274 of file InstrProfData.inc.</p>

</div>
</div>

### PointerType::getUnqual() {#ac58808184042c36d9fb31d4ec8261bc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV3::PointerType::getUnqual (Ctx)</td>
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

### Type::getInt64Ty() {#a2452625c3989ec1f75ab7a9bd3c5112f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV3::Type::getInt64Ty (Ctx)</td>
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

### BitmapDelta {#aea320f75c03324f80770877aeacbc84e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t llvm::coverage::CovMapFunctionRecordV3::BitmapDelta</td>
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

### Count {#a036a459f123f4b801f0c6693b02ba74d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr llvm::coverage::CovMapFunctionRecordV3::Count</td>
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

### CountersDelta {#a32f02bcf9ac5a476559d3ddfc0a414d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr llvm::coverage::CovMapFunctionRecordV3::CountersDelta</td>
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

### CoverageMapping {#a53f7f07e6f627017cea3455c17b5c35d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV3::CoverageMapping</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 280 of file InstrProfData.inc, definition at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### CoverageSize {#a0fe5817ad2957a411cd28f817f159d80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV3::CoverageSize</td>
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

### Data {#aaca0ca689412d2670139ddeefa15cea9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV3::Data</td>
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

### DataSize {#abad71b13ecf1bdeaaedfac205f35a7af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV3::DataSize</td>
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

### FilenamesRef {#a2d9ab29cc0274986a13b3447430a3388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV3::FilenamesRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 274 of file InstrProfData.inc, definition at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### FilenamesSize {#a9e8e0b42895d5cff1a4353d832238f39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV3::FilenamesSize</td>
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

### FuncHash {#a78e40c8fb9f6af346bf075ccd48a3ad1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coverage::CovMapFunctionRecordV3::FuncHash</td>
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

### FuncHash {#aceac10f25aa6a347ea4ed466aedb7e8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV3::FuncHash</td>
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

### FunctionPointer {#a220912f0d4f5b54f67bd99f6e6929267}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::coverage::CovMapFunctionRecordV3::FunctionPointer</td>
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

### Int16ArrayTy {#a55ef5e453fe1a96a29a5d7713b64a6db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr llvm::coverage::CovMapFunctionRecordV3::Int16ArrayTy</td>
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

### Int32Ty {#ad4c4990fc18a2c4ca149c991b0718b7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV3::Int32Ty</td>
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

### NameRef {#a2f8a8b1bd3b8fbe228336fe494b13308}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV3::NameRef</td>
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

### Next {#a1a559cfbd20237656444d8138d5291a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr llvm::coverage::CovMapFunctionRecordV3::Next</td>
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

### NRecords {#a92128e18116745cc76289da1ed911980}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV3::NRecords</td>
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

### NumBitmapBytes {#ac7a990cceb8715d2ffdc2a5418044ef9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr llvm::coverage::CovMapFunctionRecordV3::NumBitmapBytes</td>
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

### NumCounters {#ae82a685a089f405364e9903388032293}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr llvm::coverage::CovMapFunctionRecordV3::NumCounters</td>
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

### NumValueSites {#a9d754125b984fdc70c7e23e7500fcb4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr llvm::coverage::CovMapFunctionRecordV3::NumValueSites[IPVK_Last+1]</td>
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

### TargetValue {#afe6f67e40d797be8ba28ca711cc2ea15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV3::TargetValue</td>
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

### Value {#a68527845e43960ac580405dc5d4e028e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr llvm::coverage::CovMapFunctionRecordV3::Value</td>
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

### Version {#a8714ed0173a4e15ec2d6c8c86b776ae7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV3::Version</td>
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

### VTableNameHash {#a84e5d26f9b2f93776b197750c77e208f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr llvm::coverage::CovMapFunctionRecordV3::VTableNameHash</td>
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

### VTablePointer {#adaeeff5c4d242145e6f92a62956748aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr llvm::coverage::CovMapFunctionRecordV3::VTablePointer</td>
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

### WriteoutFunction {#aef482761ffa17789ffc26fea96bb3237}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddr VTableAddr uintptr_t uintptr_t llvm::coverage::CovMapFunctionRecordV3::WriteoutFunction</td>
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
