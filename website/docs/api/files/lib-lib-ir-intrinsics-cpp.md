---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/ir/intrinsics-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `Intrinsics.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">llvm/IR/Intrinsics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringtable-h">llvm/ADT/StringTable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "llvm/IR/IntrinsicsAArch64.h"
#include "llvm/IR/IntrinsicsAMDGPU.h"
#include "llvm/IR/IntrinsicsARM.h"
#include "llvm/IR/IntrinsicsBPF.h"
#include "llvm/IR/IntrinsicsHexagon.h"
#include "llvm/IR/IntrinsicsLoongArch.h"
#include "llvm/IR/IntrinsicsMips.h"
#include "llvm/IR/IntrinsicsNVPTX.h"
#include "llvm/IR/IntrinsicsPowerPC.h"
#include "llvm/IR/IntrinsicsR600.h"
#include "llvm/IR/IntrinsicsRISCV.h"
#include "llvm/IR/IntrinsicsS390.h"
#include "llvm/IR/IntrinsicsVE.h"
#include "llvm/IR/IntrinsicsX86.h"
#include "llvm/IR/IntrinsicsXCore.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "llvm/IR/IntrinsicImpl.inc"
#include "llvm/IR/ConstrainedOps.def"
</div>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaeb3a30e4d1bdc7fb8f6f8a31e03cef2">DeferredIntrinsicMatchPair</a> = std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/intrinsic/iitdescriptor">Intrinsic::IITDescriptor</a> &gt; &gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">IIT_Info { <a href="#ab47a6c0dd432fb555cdefe03dfd9d7ff">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#ab47a6c0dd432fb555cdefe03dfd9d7ff">IIT_Info</a> - These are enumerators that describe the entries returned by the getIntrinsicInfoTableEntries function. <a href="#ab47a6c0dd432fb555cdefe03dfd9d7ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae174d348b8da903ca2da92129a963e11">getMangledTypeStr</a> (Type *Ty, bool &amp;HasUnnamedType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a stable mangling for the type specified for use in the name mangling scheme used by 'any' types in intrinsic signatures. <a href="#ae174d348b8da903ca2da92129a963e11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34b48ceca0dfa72b4ce49be949a525b5">getIntrinsicNameImpl</a> (Intrinsic::ID Id, ArrayRef&lt; Type * &gt; Tys, Module *M, FunctionType *FT, bool EarlyModuleCheck)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab29da57c63bb1608298c863ea81696cc">DecodeIITType</a> (unsigned &amp;NextElt, ArrayRef&lt; unsigned char &gt; Infos, IIT_Info LastInfo, SmallVectorImpl&lt; Intrinsic::IITDescriptor &gt; &amp;OutputTable)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2818cfb16c332aba0ca0ae99d9e40a7">DecodeFixedType</a> (ArrayRef&lt; Intrinsic::IITDescriptor &gt; &amp;Infos, ArrayRef&lt; Type * &gt; Tys, LLVMContext &amp;Context)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae071c2a56ff28186d5476e562811b2f7">lookupLLVMIntrinsicByName</a> (ArrayRef&lt; unsigned &gt; NameOffsetTable, StringRef Name, StringRef Target="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Looks up Name in NameTable via binary search. <a href="#ae071c2a56ff28186d5476e562811b2f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt;, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7abd9a1f2faccb322ee43cd1fb4670d4">findTargetSubtable</a> (StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the segment of <span class="doxyComputerOutput">IntrinsicNameOffsetTable</span> for intrinsics with the same target as <span class="doxyComputerOutput">Name</span>, or the generic table if <span class="doxyComputerOutput">Name</span> is not target specific. <a href="#a7abd9a1f2faccb322ee43cd1fb4670d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a265a1edd4b8035734cda280bb91b390d">matchIntrinsicType</a> (Type *Ty, ArrayRef&lt; Intrinsic::IITDescriptor &gt; &amp;Infos, SmallVectorImpl&lt; Type * &gt; &amp;ArgTys, SmallVectorImpl&lt; DeferredIntrinsicMatchPair &gt; &amp;DeferredChecks, bool IsDeferredCheck)</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44df778ac954cf6f6ea9e7abf0b0f31b">GET_INTRINSIC_NAME_TABLE</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Table of string intrinsic names indexed by enum value. <a href="#a44df778ac954cf6f6ea9e7abf0b0f31b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1083b12e94b2ab9586d7235b59df0593">GET_INTRINSIC_IITINFO</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50de52d325910ac391669ff9cba9c7c6">GET_INTRINSIC_GENERATOR_GLOBAL</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc24b96416206d8b66746b2b57715825">GET_INTRINSIC_OVERLOAD_TABLE</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43e95a5326bc834212a448c123615884">GET_INTRINSIC_TARGET_DATA</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Table of per-target intrinsic name tables. <a href="#a43e95a5326bc834212a448c123615884">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f5bb28a5d61d5763f24db050985ec76">GET_INTRINSIC_ATTRIBUTES</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This defines the "Intrinsic::getAttributes(ID id)" method. <a href="#a6f5bb28a5d61d5763f24db050985ec76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86ffa004e88f3c86b29f423a3ee431f0">GET_LLVM_INTRINSIC_FOR_CLANG_BUILTIN</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff17443a4eb4d5eb29a5691f1dae49eb">GET_LLVM_INTRINSIC_FOR_MS_BUILTIN</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb1562b4fc2af28e0902580ce98800fd">INSTRUCTION</a>(NAME, NARG, ROUND_MODE, INTRINSIC)&nbsp;&nbsp;&nbsp;  case Intrinsic::INTRINSIC:</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac76c80c50f8ec1335d0a5a5ae26ab3da">INSTRUCTION</a>(NAME, NARG, ROUND_MODE, INTRINSIC)&nbsp;&nbsp;&nbsp;...</td>
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

## Typedefs

### DeferredIntrinsicMatchPair {#aaeb3a30e4d1bdc7fb8f6f8a31e03cef2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using DeferredIntrinsicMatchPair = 
    std::pair&lt;Type *, ArrayRef&lt;Intrinsic::IITDescriptor&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 787 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### IIT\_Info {#ab47a6c0dd432fb555cdefe03dfd9d7ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum IIT_Info </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#ab47a6c0dd432fb555cdefe03dfd9d7ff">IIT_Info</a> - These are enumerators that describe the entries returned by the getIntrinsicInfoTableEntries function.</p>


<p>Defined in Intrinsics.td.</p>


<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### DecodeFixedType() {#ad2818cfb16c332aba0ca0ae99d9e40a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * DecodeFixedType (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/intrinsic/iitdescriptor">Intrinsic::IITDescriptor</a> &gt; &amp; Infos, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; Tys, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context)</td>
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



<p>Definition at line 482 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#ad2818cfb16c332aba0ca0ae99d9e40a7">DecodeFixedType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a721fc555cb3d8dc2a1a680dcc2ce69b2">llvm::ArrayRef&lt; T &gt;::front</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#a8d7f800be5fd53dcfcdcbdc6fd9ccfe3">llvm::PointerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a18fc4545474c6ebb6f7c547f64f4fb31">llvm::StructType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/targetexttype/#a4807dd672ac18ce59733b41885eff1be">llvm::TargetExtType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ae3aa33c6054ec18e1d6bc6466d1b4103">llvm::Type::getBFloatTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a2cb59ea8f9e8543986d40c48acfd24a3">getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a90b790ccb1af4ea5ccd69db4b8cd2d81">llvm::IntegerType::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#acb145f988329d1d621f73abcafea21d8">llvm::Type::getDoubleTy</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a3b1f5f847d812d85eaaa8a19bd01bcf4">llvm::VectorType::getExtendedElementVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ad5e0fe0efdd88f98a5b5eb512d5351c2">llvm::Type::getFloatTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a49f37835a410e050b960dd936a54dd05">llvm::Type::getFP128Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a12589d52afe7ea72485b0a431327a6e6">llvm::VectorType::getHalfElementsVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ae550f2e9436b395b614b4377ba27007f">llvm::Type::getHalfTy</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a781c723920fb1d098c4d959f3218d9aa">llvm::VectorType::getInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a28fdf240b8220065bc60d6d1b1a2f174">llvm::Type::getMetadataTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a489d14cb1d049f4bcc5e3e9cdaf9c54d">llvm::Type::getPPC_FP128Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a62425c077bf32e483e2e041e26bce530">llvm::VectorType::getSubdividedVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a2b741dd02fbe0b1f02e589a785748639">llvm::Type::getTokenTy</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#aa0f42bf1b84f6c3dac6c70d2cc7f92bc">llvm::VectorType::getTruncatedElementVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a6e20e76960d952de088354cbcd14c3ab">llvm::Type::getVoidTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a08ceb864464bce07aed4387d665f6565">llvm::Type::getX86_AMXTy</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aebf6ca7590d4f766b894044015a0fa31">llvm::ArrayRef&lt; T &gt;::slice</a>.</p>


<p>Referenced by <a href="#ad2818cfb16c332aba0ca0ae99d9e40a7">DecodeFixedType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#aca1828635e30f34e4958afeb5541766e">llvm::Intrinsic::getType</a>.</p>

</div>
</div>

### DecodeIITType() {#ab29da57c63bb1608298c863ea81696cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DecodeIITType (unsigned &amp; NextElt, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned char &gt; Infos, <a href="#ab47a6c0dd432fb555cdefe03dfd9d7ff">IIT_Info</a> LastInfo, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/intrinsic/iitdescriptor">Intrinsic::IITDescriptor</a> &gt; &amp; OutputTable)</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>


<p>References <a href="#ab29da57c63bb1608298c863ea81696cc">DecodeIITType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="#ab29da57c63bb1608298c863ea81696cc">DecodeIITType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a264036c4b5fffd4ce40a5414d587d26b">llvm::Intrinsic::getIntrinsicInfoTableEntries</a>.</p>

</div>
</div>

### findTargetSubtable() {#a7abd9a1f2faccb322ee43cd1fb4670d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; ArrayRef&lt; unsigned &gt;, StringRef &gt; findTargetSubtable (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>Find the segment of <span class="doxyComputerOutput">IntrinsicNameOffsetTable</span> for intrinsics with the same target as <span class="doxyComputerOutput">Name</span>, or the generic table if <span class="doxyComputerOutput">Name</span> is not target specific.</p>


<p>Returns the relevant slice of <span class="doxyComputerOutput">IntrinsicNameOffsetTable</span> and the target name.</p>


<p>Definition at line 689 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a327a399b9f6ef414a29ddeffba934d26">llvm::partition_point</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a821cf516da0409f54e4cd8a5b7478ea7">llvm::Intrinsic::lookupIntrinsicID</a>.</p>

</div>
</div>

### getIntrinsicNameImpl() {#a34b48ceca0dfa72b4ce49be949a525b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string getIntrinsicNameImpl (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> Id, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; Tys, <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M, <a href="/web-llvm/docs/api/classes/functiontype">FunctionType</a> * FT, bool EarlyModuleCheck)</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#aac36688686cd311fab09e6b55efb7f96">llvm::Intrinsic::getBaseName</a>, <a href="#ae174d348b8da903ca2da92129a963e11">getMangledTypeStr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#aca1828635e30f34e4958afeb5541766e">llvm::Intrinsic::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#ab2d91e185087b0ac1f22ef439a170c7f">llvm::Intrinsic::isOverloaded</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a9a6d8be4a3793bd5cef4d3f25508a4fa">llvm::Intrinsic::getName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a3b2b24ea2831ebf75ab12501d3ca89e8">llvm::Intrinsic::getNameNoUnnamedTypes</a>.</p>

</div>
</div>

### getMangledTypeStr() {#ae174d348b8da903ca2da92129a963e11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string getMangledTypeStr (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, bool &amp; HasUnnamedType)</td>
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

<p>Returns a stable mangling for the type specified for use in the name mangling scheme used by 'any' types in intrinsic signatures.</p>


<p>The mangling of named types is simply their name. Manglings for unnamed types consist of a prefix ('p' for pointers, 'a' for arrays, 'f_' for functions) combined with the mangling of their component types. A vararg function type will have a suffix of 'vararg'. Since function types can contain other function types, we close a function type mangling with suffix 'f' which can't be confused with it's prefix. This ensures we don't have collisions between two unrelated function types. Otherwise, you might parse ffXX as f(fXX) or f(fX)X. (X is a placeholder for any other type.) The HasUnnamedType boolean is set if an unnamed type was encountered, indicating that extra care must be taken to ensure a unique name.</p>


<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaaa889d8e26c8078095629a42d1f930fa7">llvm::Type::BFloatTyID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabc549945f13bb5d5f5b80c550d2b92f5">llvm::Type::DoubleTyID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15">llvm::Type::FloatTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaaf645dbe1647a41fce26595aa8cd8bdfc">llvm::Type::FP128TyID</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a2cb59ea8f9e8543986d40c48acfd24a3">getBitWidth</a>, <a href="#ae174d348b8da903ca2da92129a963e11">getMangledTypeStr</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa301c3a4cc2bfd399628cfd473f383ff9">llvm::Type::HalfTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa8e724092b0496fe3d16e29863b46c249">llvm::Type::IntegerTyID</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaad3b3756c598c8acc2d002f5f9a2c1d04">llvm::Type::MetadataTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaac1fd0acf788a4de492dc0e3f51088f48">llvm::Type::PPC_FP128TyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa567ac2c7944f770cfb2c2cffc94b3520">llvm::Type::VoidTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa0abcabf751e05ec079d5907fc0733c65">llvm::Type::X86_AMXTyID</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabd37be4e521c37c8b5c07edbab59b8d7">llvm::Type::X86_FP80TyID</a>.</p>


<p>Referenced by <a href="#a34b48ceca0dfa72b4ce49be949a525b5">getIntrinsicNameImpl</a> and <a href="#ae174d348b8da903ca2da92129a963e11">getMangledTypeStr</a>.</p>

</div>
</div>

### lookupLLVMIntrinsicByName() {#ae071c2a56ff28186d5476e562811b2f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int lookupLLVMIntrinsicByName (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; NameOffsetTable, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Target="")</td>
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

<p>Looks up Name in NameTable via binary search.</p>


<p>NameTable must be sorted and all entries must start with "llvm.". If NameTable contains an exact match for Name or a prefix of Name followed by a dot, its index in NameTable is returned. Otherwise, -1 is returned.</p>


<p>Definition at line 626 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a7df34dbf636f2fbbb00f2b86eccdb1eb">High</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05609d049bfe3c5c2f64711566131a86a28d0edd045e05cf5af64e35ae0c4c6ef">llvm::Low</a>, <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref/#ad0f54a163ac500b144590640c6f1eb6b">anonymous{Path.cpp}::StringRef::npos</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a821cf516da0409f54e4cd8a5b7478ea7">llvm::Intrinsic::lookupIntrinsicID</a>.</p>

</div>
</div>

### matchIntrinsicType() {#a265a1edd4b8035734cda280bb91b390d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool matchIntrinsicType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/intrinsic/iitdescriptor">Intrinsic::IITDescriptor</a> &gt; &amp; Infos, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; &amp; ArgTys, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="#aaeb3a30e4d1bdc7fb8f6f8a31e03cef2">DeferredIntrinsicMatchPair</a> &gt; &amp; DeferredChecks, bool IsDeferredCheck)</td>
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



<p>Definition at line 791 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a721fc555cb3d8dc2a1a680dcc2ce69b2">llvm::ArrayRef&lt; T &gt;::front</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#afdce715c901d62e2c1367a0ff5248175">llvm::VectorType::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a3b1f5f847d812d85eaaa8a19bd01bcf4">llvm::VectorType::getExtendedElementVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a12589d52afe7ea72485b0a431327a6e6">llvm::VectorType::getHalfElementsVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a781c723920fb1d098c4d959f3218d9aa">llvm::VectorType::getInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#a1893caf878859959ba6a3d5442ef1439">llvm::FixedVectorType::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a62425c077bf32e483e2e041e26bce530">llvm::VectorType::getSubdividedVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#aa0f42bf1b84f6c3dac6c70d2cc7f92bc">llvm::VectorType::getTruncatedElementVectorType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a265a1edd4b8035734cda280bb91b390d">matchIntrinsicType</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aebf6ca7590d4f766b894044015a0fa31">llvm::ArrayRef&lt; T &gt;::slice</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a17dfad57f1487bb34ef68784a2e878c8">llvm::Intrinsic::matchIntrinsicSignature</a> and <a href="#a265a1edd4b8035734cda280bb91b390d">matchIntrinsicType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### GET\_INTRINSIC\_ATTRIBUTES {#a6f5bb28a5d61d5763f24db050985ec76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_INTRINSIC_ATTRIBUTES</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This defines the "Intrinsic::getAttributes(ID id)" method.</p>

<p>Definition at line 728 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>

</div>
</div>

### GET\_INTRINSIC\_GENERATOR\_GLOBAL {#a50de52d325910ac391669ff9cba9c7c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_INTRINSIC_GENERATOR_GLOBAL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 443 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>

</div>
</div>

### GET\_INTRINSIC\_IITINFO {#a1083b12e94b2ab9586d7235b59df0593}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_INTRINSIC_IITINFO</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>

</div>
</div>

### GET\_INTRINSIC\_NAME\_TABLE {#a44df778ac954cf6f6ea9e7abf0b0f31b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_INTRINSIC_NAME_TABLE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Table of string intrinsic names indexed by enum value.</p>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>

</div>
</div>

### GET\_INTRINSIC\_OVERLOAD\_TABLE {#abc24b96416206d8b66746b2b57715825}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_INTRINSIC_OVERLOAD_TABLE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 608 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>

</div>
</div>

### GET\_INTRINSIC\_TARGET\_DATA {#a43e95a5326bc834212a448c123615884}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_INTRINSIC_TARGET_DATA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Table of per-target intrinsic name tables.</p>

<p>Definition at line 614 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>

</div>
</div>

### GET\_LLVM\_INTRINSIC\_FOR\_CLANG\_BUILTIN {#a86ffa004e88f3c86b29f423a3ee431f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_LLVM_INTRINSIC_FOR_CLANG_BUILTIN</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 754 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>

</div>
</div>

### GET\_LLVM\_INTRINSIC\_FOR\_MS\_BUILTIN {#aff17443a4eb4d5eb29a5691f1dae49eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_LLVM_INTRINSIC_FOR_MS_BUILTIN</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 759 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>

</div>
</div>

### INSTRUCTION {#acb1562b4fc2af28e0902580ce98800fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTRUCTION(NAME, NARG, ROUND_MODE, INTRINSIC)&nbsp;&nbsp;&nbsp;  case Intrinsic::INTRINSIC:</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 765 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>

</div>
</div>

### INSTRUCTION {#ac76c80c50f8ec1335d0a5a5ae26ab3da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTRUCTION(NAME, NARG, ROUND_MODE, INTRINSIC)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case Intrinsic::INTRINSIC:                                                   \
    return ROUND_MODE == 1;
</div>
</dd>
</dl>

<p>Definition at line 777 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp">Intrinsics.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
