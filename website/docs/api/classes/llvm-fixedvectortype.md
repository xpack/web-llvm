---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/fixedvectortype
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `FixedVectorType` Class

<p>Class to represent fixed width SIMD vectors. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::FixedVectorType { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class of all SIMD vector types. <a href="/web-llvm/docs/api/classes/llvm/vectortype/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf26ea4a39f2089bc1a4ef1d9aa9f8f0">FixedVectorType</a> (Type *ElTy, unsigned NumElts)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1893caf878859959ba6a3d5442ef1439">getNumElements</a> () const</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9a870d5df50fe0133a410b7c9114c80">get</a> (Type *ElementType, unsigned NumElts)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6f714114223f932592ba32fbd718582">get</a> (Type *ElementType, const FixedVectorType *FVTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a510fe1022b20cfb823cf9f1ee7f23a00">getInteger</a> (FixedVectorType *VTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65b7c4625325b13cb9f3db7923aae4f6">getExtendedElementVectorType</a> (FixedVectorType *VTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae173d4d87902647680bdd90572cf7f6f">getTruncatedElementVectorType</a> (FixedVectorType *VTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62c10db57b57fc5b046c5b56d34052b2">getSubdividedVectorType</a> (FixedVectorType *VTy, int NumSubdivs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdb8103793f8643efb6d981d9cfcb99c">getHalfElementsVectorType</a> (FixedVectorType *VTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4581545c459454e57838691ebff7b1b6">getDoubleElementsVectorType</a> (FixedVectorType *VTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebadb220373b8cc720263fda3019f6f3">classof</a> (const Type *T)</td>
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

## Description {#details}

<p>Class to represent fixed width SIMD vectors.</p>

<p>Definition at line 563 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### FixedVectorType() {#aaf26ea4a39f2089bc1a4ef1d9aa9f8f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FixedVectorType::FixedVectorType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElTy, unsigned NumElts)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 565 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa98aa825426dd4de2d19a3de9983a2d5d">llvm::Type::FixedVectorTyID</a> and <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a302dbb3a7c0b1d6c35d76d3caaf4a6ba">llvm::VectorType::VectorType</a>.</p>


<p>Referenced by <a href="#ac6f714114223f932592ba32fbd718582">get</a>, <a href="#a4581545c459454e57838691ebff7b1b6">getDoubleElementsVectorType</a>, <a href="#a65b7c4625325b13cb9f3db7923aae4f6">getExtendedElementVectorType</a>, <a href="#afdb8103793f8643efb6d981d9cfcb99c">getHalfElementsVectorType</a>, <a href="#a510fe1022b20cfb823cf9f1ee7f23a00">getInteger</a>, <a href="#a62c10db57b57fc5b046c5b56d34052b2">getSubdividedVectorType</a> and <a href="#ae173d4d87902647680bdd90572cf7f6f">getTruncatedElementVectorType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getNumElements() {#a1893caf878859959ba6a3d5442ef1439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FixedVectorType::getNumElements ()</td>
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



<p>Definition at line 606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a9531bece2eddd17e21a9fd250fcbe50a">llvm::VectorType::ElementQuantity</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvegatherscatterlowering-cpp/#a7393bb18a6b67be8b26127bd4aab0cd4">CheckAndCreateOffsetAdd</a>, <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo/#a512a96bc40ecd933dab9e74af6be51b0">anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::computeFromSVI</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#ad60130f0b45a3ff1e759b010afefb94d">anonymous{ConstantFolding.cpp}::ConstantFoldFixedVectorCall</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a7d0da22d172cf90028dcf5fdc8ff2cb8">anonymous{ConstantFolding.cpp}::constantFoldVectorReduce</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a40a1fc4e57a69c562fb3d215eaa71280">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::convertBlendvToSelectMask</a>, <a href="#ac6f714114223f932592ba32fbd718582">get</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#ae83866ca1a903e74fd6b66c1fec0d528">llvm::ARMTTIImpl::getCmpSelInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a09656dc032c419abcec4768d009ed7a0">llvm::X86TTIImpl::getInterleavedMemoryOpCostAVX512</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#af41ea97386e5b3aab125935caf351bb5">llvm::ARMTTIImpl::getMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a22615a6ebaa0232be4b70be555bf0690">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getOrderedReductionCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a8a8b818a539c2cbbe1a954a875c5fcec">getVectorCallCosts</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/baseshuffleanalysis/#a7c6c1a7f00536e9ea11d05420bda55cd">anonymous{SLPVectorizer.cpp}::BaseShuffleAnalysis::isIdentityMask</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a891d016891d8c8ba74acaf3f6fec2c95">llvm::ShuffleVectorInst::isInterleave</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ac9518b8cf085f38ae07134937ad85d31">llvm::ARMTargetLowering::isLegalInterleavedAccessType</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-scalarizer-cpp-/#a8d655aa36bb1ee964b8774b5aeb7e018">anonymous{Scalarizer.cpp}::isStructOfMatchingFixedVectors</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a822917bc16eaefe906d8b1f968572a14">isV2BF16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#af48841917cf8f6f2ebf633b63cec48fb">isV2F16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpreparefunctions-cpp/#a0f104a4f4a7edce928ac0aea2a3509b8">lowerFunnelShifts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0947c6f5b0bdcd54aa4a8447602f8283">llvm::lowerUnaryVectorIntrinsicAsLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#a265a1edd4b8035734cda280bb91b390d">matchIntrinsicType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#aff60d107b0bf41de42918c5bf046d8c3">promoteAllocaUserToVector</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#aef67bcdb0247f9b4b984725fa065e1ce">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitPHINode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#aebadb220373b8cc720263fda3019f6f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FixedVectorType::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 602 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa98aa825426dd4de2d19a3de9983a2d5d">llvm::Type::FixedVectorTyID</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### get() {#af9a870d5df50fe0133a410b7c9114c80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FixedVectorType * FixedVectorType::get (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElementType, unsigned NumElts)</td>
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



<p>Declaration at line 569 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 791 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a40a1fc4e57a69c562fb3d215eaa71280">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::convertBlendvToSelectMask</a>, <a href="/web-llvm/docs/api/classes/llvm/matrixbuilder/#ae5881267e88ebfd0527460a92b61f960">llvm::MatrixBuilder::CreateColumnMajorLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#ace7e2f01b65afba76343f22d042a12df">CreateGCRelocates</a>, <a href="/web-llvm/docs/api/classes/llvm/matrixbuilder/#ac4d302983f7d34c7555b016c5901341a">llvm::MatrixBuilder::CreateMatrixMultiply</a>, <a href="/web-llvm/docs/api/classes/llvm/matrixbuilder/#a5342cc18cecbb68eff164826df1476e0">llvm::MatrixBuilder::CreateMatrixTranspose</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5aade91cf963bd6be461be24ff3a284c">createTblForTrunc</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a1fb67d47830d47e72144d7456dbb7fa0">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::createTiledLoops</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics/#a5f7b74afe2d1d4f3cc3373cd8af2e6ad">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::createTileDPLoops</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics/#a991aa40e1236f6093ee0c3d93628319c">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::createTileLoadStoreLoops</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ad2818cfb16c332aba0ca0ae99d9e40a7">DecodeFixedType</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#ab11bf3064668e4cf78d846d9092a7168">emitX86ScalarSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a06358c30f3e98d9e57f4ae9162f33c72">evaluateInDifferentElementOrder</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktagging-cpp-/initializerbuilder/#abb4311f92fffab12cf33d0aa638f944e">anonymous{AArch64StackTagging.cpp}::InitializerBuilder::flatten</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aa5ea18feb56580024a1693b1f98fb3f6">anonymous{ConstantFolding.cpp}::FoldBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a50164cfe569a57c0fcc574d0d1fc1863">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a1f6c8af64ed18f5f5810f78abf9b4f33">foldTruncInsEltPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aee3e98b16f1c8d8d8b30b9a459a6a602">foldVecTruncToExtElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp/#aaba8002e40481888d8e4933ce4487081">generateNewInstTree</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a79459acee890c44fac5c279584480b08">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a2b15feb32345af4916487fa3fa9d6227">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a0ad360dbce483cc0903211b623b9debd">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#ae5bc9cac664aeb67c181f9add7309cfa">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a8ee97870547b76f8387091128a00e90c">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#ab8b693ee2fbb4c4173fa2725c110021b">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantvector/#ade9fa017ca3aa82f7694a47090547bc1">llvm::ConstantVector::get</a>, <a href="#ac6f714114223f932592ba32fbd718582">get</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a24fb14e02fa8e4a261838b46074e42fa">llvm::AArch64TTIImpl::getArithmeticReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a5dcb8d597c1066eec7ef713b758f78f4">llvm::ARMTTIImpl::getArithmeticReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#aa0e22cc6f0e4ea9717d5ad07df6806ee">llvm::X86TTIImpl::getArithmeticReductionCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargettransforminfo-cpp/#a5e5d97b679ac5ed7ad7f5b4639c450d7">getCmpOpsType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#acc193957138fece590fe07417912f018">llvm::ConstantDataVector::getFP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#aeecde9516e68842cb97c340bb693a7a9">llvm::ConstantDataVector::getFP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#aa736794cd9a0acefdb428c5ed892a66f">llvm::ConstantDataVector::getFP</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#af5de925ed31e50af1df0f4d5e26a50c6">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::getI32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplcrtpbase/#a95442a0e0980e874df3bf77d6c8dee44">llvm::TargetTransformInfoImplCRTPBase&lt; T &gt;::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#aa55e1630a0d0f515bb43b6e9c04b8cd8">llvm::ARMTTIImpl::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a09ac3c26a04fdf36e4bcc0e725fca41e">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#affbb031405865e13b46411b934814a83">llvm::RISCVTTIImpl::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a7cf79a6310f5976179616844e2fab292">llvm::X86TTIImpl::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a09656dc032c419abcec4768d009ed7a0">llvm::X86TTIImpl::getInterleavedMemoryOpCostAVX512</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-cpp/#ad618098d4191356253e5694fd90a4634">getIntrinsicParamType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#ab1577d309005660f819a91c8268ec001">llvm::X86TTIImpl::getMaskedMemoryOpCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a8eaaa1b4edc9934bfea0469269f3d869">getMemCmpLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ac8acdac12a8890cbfe798dc2c5fb2d24">llvm::GCNTTIImpl::getMemcpyLoopLoweringType</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ac976273389caab4360013b109184e0bb">llvm::GCNTTIImpl::getMemcpyLoopResidualLoweringType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a9b1fee580716dee9404fc4e20c486392">llvm::X86TTIImpl::getMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a7b2fcbe31b1e7a23ebe5be0c1e70343a">llvm::ARMTTIImpl::getMinMaxReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a4b5cc16bea89163600c002e89334a82e">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getMinMaxReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a5bbf78518932b5f97922ea947063ed58">llvm::X86TTIImpl::getMinMaxReductionCost</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#abe3f2bc12df17a7c061c315f7bfcf12e">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getMMXVectorTy</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a4791c0c5f18aaa298445226456f15547">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#acd545bc376f8f5880178094a2d165476">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#abe6716586fd3697256a6bc605a72f06f">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getReplicationShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a6b9321187f70bb8fc4c103af466f6c21">llvm::X86TTIImpl::getReplicationShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#aa5453e30640ec93e948873506385608f">llvm::X86TTIImpl::getScalarizationOverhead</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a7480612cfe31fd07e5d1d5d45bf3c3b4">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getShadowOriginPtrKernel</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a1e2ab02b19200a9749a3a7f67d7e7cdb">llvm::RISCVTTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a671590a0e2685f1038479bd7c00b920a">llvm::X86TTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a8980bac40df22db2e293fd48b13a3b76">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getStoreMinimumVF</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a2c1b9368972e15e3602d4279f9988584">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getTreeReductionCost</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ab0cfceeb37508e56f9c127e59766a668">llvm::EVT::getTypeForEVT</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#ab3d70bf3dae5a7c20d3a0ff4fc67a000">llvm::X86TTIImpl::getVectorInstrCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a065bd87e0b855701cd8ca61aa05d4c50">getWidenedType</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#ab0b350bfd8575c9113f0e0f9624e6450">getX86MaskVec</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a897ffb621380e9230778c792ca27d9c4">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::getZeroMatrix</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#aa78bfa47c700608c53890cc25cd44a5b">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleNEONVectorStoreIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ab99310a04afb6c28186b1a6428eb75b0">hoistConditionalLoadsStores</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a43d9b7161f7ae393a165599ca211fe2f">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::improveShuffleKindFromMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a24da6451c0e494831c85fa96cb572c9a">insertSinCosCall</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a47cb7185e35282131b486036ff7c45df">llvm::X86TTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#ab4c31035e44c7bda618eb2eb81dcf314">isVectorPromotionViableForSlice</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypesequential/#ga5ec731adf74fb40bc3b401956d0c6ff2">LLVMVectorType</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a5d31f8dc135425bc0f938f13bcca4a0a">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::loadMatrix</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#aa8322b8934ca2ae69762c7056c3bf358">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::loadMatrix</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#ab3118e33ed28deca370645b8b909fa5a">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::lowerDotProduct</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a51e11fac59331e5e9704295214a2d5ee">LowerFSINCOS</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a6cbcd096f254563525e65e58557ed901">llvm::AArch64TargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ad190bc43c7fc8555debc7228fc5364b9">llvm::ARMTargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aa4094e6b2a8203e5c8b67ecf186d51a9">llvm::AArch64TargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#aa3168bc53fc117710cec207cc6f60518">llvm::ARMTargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ab33d2ce475c619c3e4412b33aac3b5bb">llvm::RISCVTargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86interleavedaccess-cpp-/x86interleavedaccessgroup/#a57d756a0a03371c31155a702e0ba4d85">anonymous{X86InterleavedAccess.cpp}::X86InterleavedAccessGroup::lowerIntoOptimizedSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp/#a804c9545f28631dc405eccad6d7234a7">lowerKernelArguments</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#aadb2a52a94fd7cf1e3f1643e0f5e2934">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerTranspose</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuimageintrinsicoptimizer-cpp/#a0751e03131065414fffaa087c9e084cb">optimizeSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a75e6b6bf03adf614aaf100a9afdcd612">optimizeVectorResizeWithIntegerBitCasts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#aff60d107b0bf41de42918c5bf046d8c3">promoteAllocaUserToVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a2f20b406ad481a5f9d33949e4ccd9f05">shrinkFPConstantVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#aae1a4eb9b437e719a333c79f74c9a1b2">simplifyAMDGCNMemoryIntrinsicDemanded</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#adbe56869c99b539068e8a442d8738dae">simplifyX86extrq</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a158032a7de947df4dc475c236414f0a2">simplifyX86insertq</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a7db2eee6dd2ea98d0ec3c05950be2915">simplifyX86pmulh</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#af928743a3a7070559bd992164e601a19">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::storeMatrix</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#a1616baf1b22efae9f17bb3d499ac8931">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::storePrimitiveShadowOrigin</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a4ce4b835cffc5fa4123fe82f5f39cf97">upgradeAArch64IntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a90bcc9afc1cc990c8790a5424a93c926">upgradeARMIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#aabed4dadfe0a32d2cc856553788212ba">upgradeArmOrAarch64IntrinsicFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#acd3fbecf680813e839ac85bf3b3a81f2">upgradeMaskedCompare</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#ac0a8da35200651179e36ea9764bfcc89">upgradePTESTIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#af61729415c4cfec66c791cd52a532eb9">upgradeX86IntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a1128556ee677ef705440ec4b2158d754">upgradeX86PSLLDQIntrinsics</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a7639e118359323dbad0b719e9855841a">upgradeX86PSRLDQIntrinsics</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#aabb3d90405099bce8007a11942f3ab92">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitBitCastInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#aef67bcdb0247f9b4b984725fa065e1ce">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitPHINode</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad31108b4f7156db7565eadba1285c93a">llvm::InstCombinerImpl::visitShuffleVectorInst</a>.</p>

</div>
</div>

### get() {#ac6f714114223f932592ba32fbd718582}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FixedVectorType * llvm::FixedVectorType::get (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElementType, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a> * FVTy)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 571 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="#aaf26ea4a39f2089bc1a4ef1d9aa9f8f0">FixedVectorType</a>, <a href="#af9a870d5df50fe0133a410b7c9114c80">get</a> and <a href="#a1893caf878859959ba6a3d5442ef1439">getNumElements</a>.</p>

</div>
</div>

### getDoubleElementsVectorType() {#a4581545c459454e57838691ebff7b1b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FixedVectorType * llvm::FixedVectorType::getDoubleElementsVectorType (<a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a> * VTy)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 598 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#aaf26ea4a39f2089bc1a4ef1d9aa9f8f0">FixedVectorType</a> and <a href="/web-llvm/docs/api/classes/llvm/vectortype/#ac423a4165a8f57cd2865ef33dd9be484">llvm::VectorType::getDoubleElementsVectorType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a1e2ab02b19200a9749a3a7f67d7e7cdb">llvm::RISCVTTIImpl::getShuffleCost</a>.</p>

</div>
</div>

### getExtendedElementVectorType() {#a65b7c4625325b13cb9f3db7923aae4f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FixedVectorType * llvm::FixedVectorType::getExtendedElementVectorType (<a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a> * VTy)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 579 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#aaf26ea4a39f2089bc1a4ef1d9aa9f8f0">FixedVectorType</a> and <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a3b1f5f847d812d85eaaa8a19bd01bcf4">llvm::VectorType::getExtendedElementVectorType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a7db2eee6dd2ea98d0ec3c05950be2915">simplifyX86pmulh</a>.</p>

</div>
</div>

### getHalfElementsVectorType() {#afdb8103793f8643efb6d981d9cfcb99c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FixedVectorType * llvm::FixedVectorType::getHalfElementsVectorType (<a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a> * VTy)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 594 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#aaf26ea4a39f2089bc1a4ef1d9aa9f8f0">FixedVectorType</a> and <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a12589d52afe7ea72485b0a431327a6e6">llvm::VectorType::getHalfElementsVectorType</a>.</p>

</div>
</div>

### getInteger() {#a510fe1022b20cfb823cf9f1ee7f23a00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FixedVectorType * llvm::FixedVectorType::getInteger (<a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a> * VTy)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 575 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#aaf26ea4a39f2089bc1a4ef1d9aa9f8f0">FixedVectorType</a> and <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a781c723920fb1d098c4d959f3218d9aa">llvm::VectorType::getInteger</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a50016fb8102156a9c168cfd348b3509a">llvm::AArch64TargetLowering::optimizeExtendOrTruncateConversion</a>.</p>

</div>
</div>

### getSubdividedVectorType() {#a62c10db57b57fc5b046c5b56d34052b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FixedVectorType * llvm::FixedVectorType::getSubdividedVectorType (<a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a> * VTy, int NumSubdivs)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 588 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#aaf26ea4a39f2089bc1a4ef1d9aa9f8f0">FixedVectorType</a> and <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a62425c077bf32e483e2e041e26bce530">llvm::VectorType::getSubdividedVectorType</a>.</p>

</div>
</div>

### getTruncatedElementVectorType() {#ae173d4d87902647680bdd90572cf7f6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FixedVectorType * llvm::FixedVectorType::getTruncatedElementVectorType (<a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a> * VTy)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 583 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#aaf26ea4a39f2089bc1a4ef1d9aa9f8f0">FixedVectorType</a> and <a href="/web-llvm/docs/api/classes/llvm/vectortype/#aa0f42bf1b84f6c3dac6c70d2cc7f92bc">llvm::VectorType::getTruncatedElementVectorType</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
