---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gcnttiimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GCNTTIImpl` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::GCNTTIImpl { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">Target/AMDGPU/AMDGPUTargetTransformInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase">BasicTTIImplBase&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class which can be used to help build a TTI implementation. <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7778a56149ad652d321d99e7fd92bbd0">BaseT</a> = <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase">BasicTTIImplBase</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl">GCNTTIImpl</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1916fb589364c4f6c3a8d13cb304d011">TTI</a> = <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19dce49c9c18898b9f4ca348fa3c89ec">GCNTTIImpl</a> (const AMDGPUTargetMachine *TM, const Function &amp;F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeef5bd47e34fd5b8224c2b25a7d71a75">hasBranchDivergence</a> (const Function *F=nullptr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74357df9d89b3b32fbdc98894a64d776">getUnrollingPreferences</a> (Loop *L, ScalarEvolution &amp;SE, TTI::UnrollingPreferences &amp;UP, OptimizationRemarkEmitter *ORE)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18185887f6b451a8b30f37e38a3c4628">getPeelingPreferences</a> (Loop *L, ScalarEvolution &amp;SE, TTI::PeelingPreferences &amp;PP)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#aa4c17e89b1ef061ed69f42b7cee93dbe">TTI::PopcntSupportKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45d9249c12ad9cacdf615df6805cf321">getPopcntSupport</a> (unsigned TyWidth)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d6914224bb40fba26048b8f6f73d5f0">getNumberOfRegisters</a> (unsigned RCID) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a087fa556b9e8ec33fd3cf9564ce9d234">getRegisterBitWidth</a> (TargetTransformInfo::RegisterKind Vector) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c4c575078ed7e4d2fb757f4f581a111">getMinVectorRegisterBitWidth</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9af56ff6a91d5a8f104d53daea5474c1">getMaximumVF</a> (unsigned ElemWidth, unsigned Opcode) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9761430bcfb8f1f8317f6f91c6a160da">getLoadVectorFactor</a> (unsigned VF, unsigned LoadSize, unsigned ChainSizeInBytes, VectorType *VecTy) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bbfb3bc77775d693176036e552f4f89">getStoreVectorFactor</a> (unsigned VF, unsigned StoreSize, unsigned ChainSizeInBytes, VectorType *VecTy) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc4fda3f5dbe6ef115dd164a67c256d5">getLoadStoreVecRegBitWidth</a> (unsigned AddrSpace) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5355c5e0a1cb9fecfd198f6d7c3714dd">isLegalToVectorizeMemChain</a> (unsigned ChainSizeInBytes, Align Alignment, unsigned AddrSpace) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e8a8bc0e04667c2fe7c0470f66483c5">isLegalToVectorizeLoadChain</a> (unsigned ChainSizeInBytes, Align Alignment, unsigned AddrSpace) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a624b8c25783d9c13165a7960e501ef66">isLegalToVectorizeStoreChain</a> (unsigned ChainSizeInBytes, Align Alignment, unsigned AddrSpace) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d69deab247604d04ac57db167a884b1">getMaxMemIntrinsicInlineSizeThreshold</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8acdac12a8890cbfe798dc2c5fb2d24">getMemcpyLoopLoweringType</a> (LLVMContext &amp;Context, Value *Length, unsigned SrcAddrSpace, unsigned DestAddrSpace, Align SrcAlign, Align DestAlign, std::optional&lt; uint32_t &gt; AtomicElementSize) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac976273389caab4360013b109184e0bb">getMemcpyLoopResidualLoweringType</a> (SmallVectorImpl&lt; Type * &gt; &amp;OpsOut, LLVMContext &amp;Context, unsigned RemainingBytes, unsigned SrcAddrSpace, unsigned DestAddrSpace, Align SrcAlign, Align DestAlign, std::optional&lt; uint32_t &gt; AtomicCpySize) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a644495365c2a3cd22d5b308ba96f41da">getMaxInterleaveFactor</a> (ElementCount VF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8de5bf4f45a9fe750de151c5532d4fec">getTgtMemIntrinsic</a> (IntrinsicInst *Inst, MemIntrinsicInfo &amp;Info) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8b00d72cfbbf3ef02315ae6a0ecc418">getArithmeticInstrCost</a> (unsigned Opcode, Type *Ty, TTI::TargetCostKind CostKind, TTI::OperandValueInfo Op1Info={TTI::OK_AnyValue, TTI::OP_None}, TTI::OperandValueInfo Op2Info={TTI::OK_AnyValue, TTI::OP_None}, ArrayRef&lt; const Value * &gt; Args={}, const Instruction *CxtI=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb54c0dfe9425fa97b6b762479d146f2">getCFInstrCost</a> (unsigned Opcode, TTI::TargetCostKind CostKind, const Instruction *I=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e874f5073fd59211348a2ea23e9d0ce">isInlineAsmSourceOfDivergence</a> (const CallInst *CI, ArrayRef&lt; unsigned &gt; Indices={}) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyze if the results of inline asm are divergent. <a href="#a3e874f5073fd59211348a2ea23e9d0ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f0c067bd859c66c848ab7d23639c3e8">getVectorInstrCost</a> (unsigned Opcode, Type *ValTy, TTI::TargetCostKind CostKind, unsigned Index, Value *Op0, Value *Op1)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f1861e30cebca3c33d71a2e73de0c5b">isReadRegisterSourceOfDivergence</a> (const IntrinsicInst *ReadReg) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcaf33f0c60678d66d47c074de4cc46a">isSourceOfDivergence</a> (const Value *V) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11fb81052cf8abb712c95daa2f0344d6">isAlwaysUniform</a> (const Value *V) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b5f809d01fe5e1162f330b6a2ee9552">isValidAddrSpaceCast</a> (unsigned FromAS, unsigned ToAS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ed9ebdc2557a7eb4ce1b14bef0b26a7">addrspacesMayAlias</a> (unsigned AS0, unsigned AS1) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78ce7ba5277b35db1be42d3e572604ff">getFlatAddressSpace</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9d766b132f29a13565b6b239174bf44">collectFlatAddressOperands</a> (SmallVectorImpl&lt; int &gt; &amp;OpIndexes, Intrinsic::ID IID) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50886b60225b4fe1c63d74fbf1028cca">canHaveNonUndefGlobalInitializerInAddressSpace</a> (unsigned AS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9910dce4a3e020d503a0e4062d66646f">rewriteIntrinsicWithAddressSpace</a> (IntrinsicInst *II, Value *OldV, Value *NewV) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5be25044bcd47e6c80f68c90159891f">canSimplifyLegacyMulToMul</a> (const Instruction &amp;I, const Value *Op0, const Value *Op1, InstCombiner &amp;IC) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1747fa66edae41ea9492c338ef853e12">simplifyDemandedLaneMaskArg</a> (InstCombiner &amp;IC, IntrinsicInst &amp;II, unsigned LaneAgIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Simplify a lane index operand (e.g. <a href="#a1747fa66edae41ea9492c338ef853e12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3d1835a72f8f0ba85ace9e2c0fbfc96">instCombineIntrinsic</a> (InstCombiner &amp;IC, IntrinsicInst &amp;II) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c469b9715a7fccaba1b1d673597682c">simplifyDemandedVectorEltsIntrinsic</a> (InstCombiner &amp;IC, IntrinsicInst &amp;II, APInt DemandedElts, APInt &amp;UndefElts, APInt &amp;UndefElts2, APInt &amp;UndefElts3, std::function&lt; void(Instruction *, unsigned, APInt, APInt &amp;)&gt; SimplifyAndSetOp) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a883340380993770830f245b05a84d472">getVectorSplitCost</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefd2591b1c59fbc42ad11361b7e23518">getShuffleCost</a> (TTI::ShuffleKind Kind, VectorType *Tp, ArrayRef&lt; int &gt; Mask, TTI::TargetCostKind CostKind, int Index, VectorType *SubTp, ArrayRef&lt; const Value * &gt; Args={}, const Instruction *CxtI=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7302061b4aaf73033fc317a6ab8b8d65">isProfitableToSinkOperands</a> (Instruction *I, SmallVectorImpl&lt; Use * &gt; &amp;Ops) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether it is profitable to sink the operands of an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> I to the basic block of I. <a href="#a7302061b4aaf73033fc317a6ab8b8d65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab22e771266e47d5314bdf2eb148bac1f">areInlineCompatible</a> (const Function *Caller, const Function *Callee) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4868fa84d8116f9d4e0dcab86456c831">getInliningLastCallToStaticBonus</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c2338ef386c7d553b00c8bece389fc4">getInliningThresholdMultiplier</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab09ae263a3c9738a327d87123ca1c3e1">adjustInliningThreshold</a> (const CallBase *CB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2a358830eca13fbd32b219f5318a7d8">getCallerAllocaCost</a> (const CallBase *CB, const AllocaInst *AI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c4c3efc142f7752a7d08cf1c3e95793">getInlinerVectorBonusPercent</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe02f4d6b04ada7f0864494bd23b83d7">getArithmeticReductionCost</a> (unsigned Opcode, VectorType *Ty, std::optional&lt; FastMathFlags &gt; FMF, TTI::TargetCostKind CostKind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09fb36481c632cf2772ebce4492cb31e">getIntrinsicInstrCost</a> (const IntrinsicCostAttributes &amp;ICA, TTI::TargetCostKind CostKind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21d34e75ec9f5b42d39e85688a0f0d20">getMinMaxReductionCost</a> (Intrinsic::ID IID, VectorType *Ty, FastMathFlags FMF, TTI::TargetCostKind CostKind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5631fc631ce554e5f2d2f483e2275e01">getCacheLineSize</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Data cache line size for LoopDataPrefetch pass. Has no use before GFX12. <a href="#a5631fc631ce554e5f2d2f483e2275e01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98cb1900dc59835badd6284a9b5c1298">getPrefetchDistance</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>How much before a load we should place the prefetch instruction. <a href="#a98cb1900dc59835badd6284a9b5c1298">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b93f987c913933d2e8cc77fe73da617">shouldPrefetchAddressSpace</a> (unsigned AS) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c38fde7667a3797047f16dce4017457">getVectorInstrCost</a> (unsigned Opcode, Type *Val, TTI::TargetCostKind CostKind, unsigned Index, Value *Scalar, ArrayRef&lt; std::tuple&lt; Value *, User *, int &gt; &gt; ScalarUserAndIdx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c49c54ca70e79f02ea0f0e9c21d779c">getVectorInstrCost</a> (const Instruction &amp;I, Type *Val, TTI::TargetCostKind CostKind, unsigned Index)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c1e1b6a35a698fe2897453c3fc9bc78">getST</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering">SITargetLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af407f42a426ea51df3d855630dace9cc">getTLI</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5acae0ee67a85000756d6092e279e0ce">get64BitInstrCost</a> (TTI::TargetCostKind CostKind) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd144d77eb83570b9357a87be6436050">getTypeLegalizationCost</a> (Type *Ty) const</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72880c841c19ba0188ec9bc3de940880">BaseT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70668df44acfd1359f0503169b40f6b5">ST</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering">SITargetLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1690c829bc65b1865b73ac8d51dc2bfa">TLI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgputtiimpl">AMDGPUTTIImpl</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42a49692a2fa8c44734a64f2c8cd0383">CommonTTI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae01e15d49b1faaaf48d8e9371e099244">IsGraphics</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abaefa3538cd4912511c6f698275a85dd">HasFP32Denormals</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52a92e3c1c14ba5f677fb51799df4e63">HasFP64FP16Denormals</a></td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad12661481860e268d0d31ec17093d0dd">getFullRateInstrCost</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adec33a5f18cccc8f7e9f1549c34e9daf">getHalfRateInstrCost</a> (TTI::TargetCostKind CostKind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a703eba755312a0cf60db2c18666dfcef">getQuarterRateInstrCost</a> (TTI::TargetCostKind CostKind)</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab06e07b89bb8c532da42cda3a0b9dddf">InlinerVectorBonusPercent</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b9ebe63a0046f959313f2e6f9af470e">InlineFeatureIgnoreList</a> = ...</td>
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


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### BaseT {#a7778a56149ad652d321d99e7fd92bbd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GCNTTIImpl::BaseT =  BasicTTIImplBase&lt;GCNTTIImpl&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>.</p>

</div>
</div>

### TTI {#a1916fb589364c4f6c3a8d13cb304d011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GCNTTIImpl::TTI =  TargetTransformInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### GCNTTIImpl() {#a19dce49c9c18898b9f4ca348fa3c89ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNTTIImpl::GCNTTIImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine">AMDGPUTargetMachine</a> * TM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a01aadd7eea7124cd9f5cd7cea37d8dab">llvm::TargetTransformInfoImplBase::getDataLayout</a>, <a href="/web-llvm/docs/api/structs/llvm/denormalmode/#a8b25a485fab5c4ade966d2ad73bc2ccf">llvm::DenormalMode::getPreserveSign</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#aef71c4b21823f236e70cc6d62375adcd">Mode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addrspacesMayAlias() {#a3ed9ebdc2557a7eb4ce1b14bef0b26a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNTTIImpl::addrspacesMayAlias (unsigned AS0, unsigned AS1)</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a95a786842e24ab75d92296a169ca75b5">llvm::AMDGPU::addrspacesMayAlias</a>.</p>

</div>
</div>

### adjustInliningThreshold() {#ab09ae263a3c9738a327d87123ca1c3e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GCNTTIImpl::adjustInliningThreshold (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 1342 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp/#a490938b206738261d5984fe958a872ad">adjustInliningThresholdUsingCallee</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp/#a26e3547a49b58b4e815ff5c73cad7865">ArgAllocaCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#aec0b8db50138e2a68aca36959b6692a5">llvm::BasicTTIImplBase&lt; GCNTTIImpl &gt;::DL</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp/#aa883d40ffa8836538699a7974632d0a0">getCallArgsTotalAllocaSize</a>.</p>

</div>
</div>

### areInlineCompatible() {#ab22e771266e47d5314bdf2eb148bac1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNTTIImpl::areInlineCompatible (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Caller, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Callee)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 1225 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp/#a511ad5c70fcf51f6b6f29025fd9e54a9">InlineMaxBB</a> and <a href="/web-llvm/docs/api/structs/llvm/simoderegisterdefaults/#abdddc79ec28eda713a19458d04d46fd6">llvm::SIModeRegisterDefaults::isInlineCompatible</a>.</p>

</div>
</div>

### canHaveNonUndefGlobalInitializerInAddressSpace() {#a50886b60225b4fe1c63d74fbf1028cca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNTTIImpl::canHaveNonUndefGlobalInitializerInAddressSpace (unsigned AS)</td>
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



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a77b1c964e2ff99057bf5e75140457abe">llvm::AMDGPUAS::LOCAL_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aec164f45437d8827346f2d8ec645479a">llvm::AMDGPUAS::PRIVATE_ADDRESS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a5b71ba6fa435ec288aba849e113721a7">llvm::AMDGPUAS::REGION_ADDRESS</a>.</p>

</div>
</div>

### canSimplifyLegacyMulToMul() {#ae5be25044bcd47e6c80f68c90159891f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNTTIImpl::canSimplifyLegacyMulToMul (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, <a href="/web-llvm/docs/api/classes/llvm/instcombiner">InstCombiner</a> &amp; IC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp">AMDGPUInstCombineIntrinsic.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#af56f7a148b00922368e55ab9c4948724">llvm::InstCombiner::getSimplifyQuery</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a505cdf903e17bf9be677769bf0980adc">llvm::SimplifyQuery::getWithInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a42c8f0b3d870c96030032b8ed8a2a1e3">llvm::isKnownNeverInfOrNaN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aa09f5e8610a5a2941eb4f42777059942">llvm::PatternMatch::m_FiniteNonZero</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="#ae3d1835a72f8f0ba85ace9e2c0fbfc96">instCombineIntrinsic</a>.</p>

</div>
</div>

### collectFlatAddressOperands() {#aa9d766b132f29a13565b6b239174bf44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNTTIImpl::collectFlatAddressOperands (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; int &gt; &amp; OpIndexes, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> IID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 1063 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### getArithmeticInstrCost() {#ae8b00d72cfbbf3ef02315ae6a0ecc418}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost GCNTTIImpl::getArithmeticInstrCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/operandvalueinfo">TTI::OperandValueInfo</a> Op1Info={<a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#afa38851d75434d1476444ac93f94cb4ca9c0eecea29e9fa58e4dac7ee32b9b2ac">TTI::OK_AnyValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a733fb237f3037c95ed59de6055b176c5a2bc39e3785b29fe7bc4af768842a2072">TTI::OP_None</a>}, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/operandvalueinfo">TTI::OperandValueInfo</a> Op2Info={<a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#afa38851d75434d1476444ac93f94cb4ca9c0eecea29e9fa58e4dac7ee32b9b2ac">TTI::OK_AnyValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a733fb237f3037c95ed59de6055b176c5a2bc39e3785b29fe7bc4af768842a2072">TTI::OP_None</a>}, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Args={}, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CxtI=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 546 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a32ec12017722f5b42a295fe5eb0b0bdf">llvm::ISD::FADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaf552e181879ad14956985859308d77d9">llvm::FAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fpopfusion/#a9c71bae9f02af273833fde586d529fc5aa9dfaae1f5b7d4ebb31ccf9aee1aacce">llvm::FPOpFusion::Fast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abc6c09c7af98236460f0b020eb3be94e">llvm::ISD::FDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ab5860c97a00c4627a08cab7b0c8178">llvm::ISD::FMUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6d26c45c040d8f85d577a5f645261d1a">llvm::ISD::FNEG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abdd7bbb76dac7962dda6e116e33699da">llvm::ISD::FREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2852a5b6baa80b1589a46737210a8cad">llvm::ISD::FSUB</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#ae3c3eb22dfa7c2b373ac485024f99aa6">llvm::BasicTTIImplBase&lt; GCNTTIImpl &gt;::getArithmeticInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#adf69200e2ae35a69c5eeecd4c0ee4d1c">llvm::Instruction::hasAllowContract</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#aa11ca53210de69609754994339179e10">llvm::Instruction::hasApproxFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3a402430a1bbe70a9282dcb0e0b6a2cd">llvm::Value::hasOneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a8f87f39b5e0dedd0793bb3a450f463cf">llvm::PatternMatch::m_FPOne</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#ac44f6b9fdbb5f9cc199f8329cb0b272ca89f768b1267e3083b4eb05b4ab77e717">llvm::TargetTransformInfo::TCC_Free</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a158da2b6d3d938aaa15b6acd00150e2c">llvm::Value::user_begin</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a>.</p>

</div>
</div>

### getArithmeticReductionCost() {#afe02f4d6b04ada7f0864494bd23b83d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost GCNTTIImpl::getArithmeticReductionCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * Ty, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> &gt; FMF, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 827 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#aec0b8db50138e2a68aca36959b6692a5">llvm::BasicTTIImplBase&lt; GCNTTIImpl &gt;::DL</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#aacaa7d017eb34bf5050b2fb7f6dd91c4">llvm::BasicTTIImplBase&lt; GCNTTIImpl &gt;::getArithmeticReductionCost</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a547a88964f1673c84410baa7a2a83f4d">llvm::EVT::getScalarSizeInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a7aecc3cf03beff532c2b8bfe81e500c8">llvm::TargetTransformInfo::requiresOrderedReduction</a>.</p>

</div>
</div>

### getCacheLineSize() {#a5631fc631ce554e5f2d2f483e2275e01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNTTIImpl::getCacheLineSize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Data cache line size for LoopDataPrefetch pass. Has no use before GFX12.</p>

<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>.</p>

</div>
</div>

### getCallerAllocaCost() {#ab2a358830eca13fbd32b219f5318a7d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GCNTTIImpl::getCallerAllocaCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * AI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 1353 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp/#a26e3547a49b58b4e815ff5c73cad7865">ArgAllocaCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp/#a4a1be703f870d2a1cd4ed04464f5cc9f">ArgAllocaCutoff</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#aec0b8db50138e2a68aca36959b6692a5">llvm::BasicTTIImplBase&lt; GCNTTIImpl &gt;::DL</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a9b5ec84ea363eca9e35ddca20a5313af">llvm::AllocaInst::getAllocatedType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp/#aa883d40ffa8836538699a7974632d0a0">getCallArgsTotalAllocaSize</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="#a6c2338ef386c7d553b00c8bece389fc4">getInliningThresholdMultiplier</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a>.</p>

</div>
</div>

### getCFInstrCost() {#adb54c0dfe9425fa97b6b762479d146f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost GCNTTIImpl::getCFInstrCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 796 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#aa459db33f4b14d518af003bf95c3417e">llvm::BasicTTIImplBase&lt; GCNTTIImpl &gt;::getCFInstrCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba737cfc93e5a2ff961677d57186167e7c">llvm::TargetTransformInfo::TCK_CodeSize</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba7f80055e1969cb850739546467460ad8">llvm::TargetTransformInfo::TCK_SizeAndLatency</a>.</p>

</div>
</div>

### getFlatAddressSpace() {#a78ce7ba5277b35db1be42d3e572604ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNTTIImpl::getFlatAddressSpace ()</td>
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



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aaa1e27e4fc68e5706a4b7bbaed447c14">llvm::AMDGPUAS::FLAT_ADDRESS</a>.</p>

</div>
</div>

### getInlinerVectorBonusPercent() {#a7c4c3efc142f7752a7d08cf1c3e95793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::GCNTTIImpl::getInlinerVectorBonusPercent ()</td>
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



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>.</p>

</div>
</div>

### getInliningLastCallToStaticBonus() {#a4868fa84d8116f9d4e0dcab86456c831}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int GCNTTIImpl::getInliningLastCallToStaticBonus ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 1337 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a9579c636821954ba2e7ff3561766db67">llvm::TargetTransformInfoImplBase::getInliningLastCallToStaticBonus</a> and <a href="#a6c2338ef386c7d553b00c8bece389fc4">getInliningThresholdMultiplier</a>.</p>

</div>
</div>

### getInliningThresholdMultiplier() {#a6c2338ef386c7d553b00c8bece389fc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCNTTIImpl::getInliningThresholdMultiplier ()</td>
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



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="#ab2a358830eca13fbd32b219f5318a7d8">getCallerAllocaCost</a> and <a href="#a4868fa84d8116f9d4e0dcab86456c831">getInliningLastCallToStaticBonus</a>.</p>

</div>
</div>

### getIntrinsicInstrCost() {#a09fb36481c632cf2772ebce4492cb31e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost GCNTTIImpl::getIntrinsicInstrCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intrinsiccostattributes">IntrinsicCostAttributes</a> &amp; ICA, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 727 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiccostattributes/#af12b3fb3cabe9735daed0349fae1887d">llvm::IntrinsicCostAttributes::getID</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a05184f6230f850d3f972f6d904bd2ef5">llvm::BasicTTIImplBase&lt; GCNTTIImpl &gt;::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiccostattributes/#a3c2339b82bd84f5ce831ebbf3e1aee5c">llvm::IntrinsicCostAttributes::getReturnType</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp/#a9281391bbf7df76a0cf95a51fd71f5b0">intrinsicHasPackedVectorBenefit</a>.</p>

</div>
</div>

### getLoadStoreVecRegBitWidth() {#adc4fda3f5dbe6ef115dd164a67c256d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GCNTTIImpl::getLoadStoreVecRegBitWidth (unsigned AddrSpace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1ae0523ec09f17ea21ac251db04f249f13">llvm::AMDGPUAS::BUFFER_FAT_POINTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1af3a547aa91b97183a165b876de8e24d8">llvm::AMDGPUAS::BUFFER_RESOURCE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a3f428ecb6bd1846dcc64d491627bf34c">llvm::AMDGPUAS::BUFFER_STRIDED_POINTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aa6d3112da64eecbdbb50aacb5f8251e8">llvm::AMDGPUAS::CONSTANT_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a1caf1e287a5fe7250388d66ed72aa0c1">llvm::AMDGPUAS::CONSTANT_ADDRESS_32BIT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1abf4559ef958a13c33f6ec7ed13fd44e5">llvm::AMDGPUAS::GLOBAL_ADDRESS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aec164f45437d8827346f2d8ec645479a">llvm::AMDGPUAS::PRIVATE_ADDRESS</a>.</p>

</div>
</div>

### getLoadVectorFactor() {#a9761430bcfb8f1f8317f6f91c6a160da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GCNTTIImpl::getLoadVectorFactor (unsigned VF, unsigned LoadSize, unsigned ChainSizeInBytes, <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * VecTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>.</p>

</div>
</div>

### getMaximumVF() {#a9af56ff6a91d5a8f104d53daea5474c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GCNTTIImpl::getMaximumVF (unsigned ElemWidth, unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getMaxInterleaveFactor() {#a644495365c2a3cd22d5b308ba96f41da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GCNTTIImpl::getMaxInterleaveFactor (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 511 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a991f269cde2e7fbcb254ef371efc8d1a">llvm::ElementCount::isScalar</a>.</p>

</div>
</div>

### getMaxMemIntrinsicInlineSizeThreshold() {#a1d69deab247604d04ac57db167a884b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t GCNTTIImpl::getMaxMemIntrinsicInlineSizeThreshold ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getMemcpyLoopLoweringType() {#ac8acdac12a8890cbfe798dc2c5fb2d24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * GCNTTIImpl::getMemcpyLoopLoweringType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Length, unsigned SrcAddrSpace, unsigned DestAddrSpace, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> SrcAlign, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> DestAlign, std::optional&lt; uint32_t &gt; AtomicElementSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a87f56db834c58ca630624956ecf6972f">llvm::Type::getInt16Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#acaf8e4c3e40e01e848c1fad5f05b81cd">llvm::Type::getIntNTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a77b1c964e2ff99057bf5e75140457abe">llvm::AMDGPUAS::LOCAL_ADDRESS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp/#af843c51255e07629b549e19cb11a369a">MemcpyLoopUnroll</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59f98bbb1f440db8d5db1c8b5bd819f6">llvm::MinAlign</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a5b71ba6fa435ec288aba849e113721a7">llvm::AMDGPUAS::REGION_ADDRESS</a>.</p>

</div>
</div>

### getMemcpyLoopResidualLoweringType() {#ac976273389caab4360013b109184e0bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNTTIImpl::getMemcpyLoopResidualLoweringType (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; &amp; OpsOut, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, unsigned RemainingBytes, unsigned SrcAddrSpace, unsigned DestAddrSpace, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> SrcAlign, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> DestAlign, std::optional&lt; uint32_t &gt; AtomicCpySize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a87f56db834c58ca630624956ecf6972f">llvm::Type::getInt16Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7ba5de75f50bb4a4ba920698edf39b28">llvm::Type::getInt8Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a7ee986b3ced1ba5562ed34c5e633bed2">llvm::TargetTransformInfoImplBase::getMemcpyLoopResidualLoweringType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59f98bbb1f440db8d5db1c8b5bd819f6">llvm::MinAlign</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### getMinMaxReductionCost() {#a21d34e75ec9f5b42d39e85688a0f0d20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost GCNTTIImpl::getMinMaxReductionCost (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> IID, <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMF, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 845 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#aec0b8db50138e2a68aca36959b6692a5">llvm::BasicTTIImplBase&lt; GCNTTIImpl &gt;::DL</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a4b5cc16bea89163600c002e89334a82e">llvm::BasicTTIImplBase&lt; GCNTTIImpl &gt;::getMinMaxReductionCost</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#a547a88964f1673c84410baa7a2a83f4d">llvm::EVT::getScalarSizeInBits</a>.</p>

</div>
</div>

### getMinVectorRegisterBitWidth() {#a8c4c575078ed7e4d2fb757f4f581a111}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GCNTTIImpl::getMinVectorRegisterBitWidth ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getNumberOfRegisters() {#a4d6914224bb40fba26048b8f6f73d5f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GCNTTIImpl::getNumberOfRegisters (unsigned RCID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getPeelingPreferences() {#a18185887f6b451a8b30f37e38a3c4628}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNTTIImpl::getPeelingPreferences (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/peelingpreferences">TTI::PeelingPreferences</a> &amp; PP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 1400 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getPopcntSupport() {#a45d9249c12ad9cacdf615df6805cf321}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TTI::PopcntSupportKind llvm::GCNTTIImpl::getPopcntSupport (unsigned TyWidth)</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#aa4c17e89b1ef061ed69f42b7cee93dbeac71465fd61f1ba8aa2c7c397722b5e05">llvm::TargetTransformInfo::PSK_FastHardware</a>.</p>

</div>
</div>

### getPrefetchDistance() {#a98cb1900dc59835badd6284a9b5c1298}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GCNTTIImpl::getPrefetchDistance ()</td>
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

<p>How much before a load we should place the prefetch instruction.</p>


<p>This is currently measured in number of IR instructions.</p>


<p>Declaration at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 1426 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getRegisterBitWidth() {#a087fa556b9e8ec33fd3cf9564ce9d234}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeSize GCNTTIImpl::getRegisterBitWidth (<a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a8bb3b1ccf19b8c85429b777dfa4a0166">TargetTransformInfo::RegisterKind</a> Vector)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/typesize/#a003b4369b4130e669dc9139798e0193c">llvm::TypeSize::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/typesize/#a5fd620f2446d1a4cb0d55a12d182bb34">llvm::TypeSize::getScalable</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a8bb3b1ccf19b8c85429b777dfa4a0166a183020fbea95c99db23f6d3594f4c4af">llvm::TargetTransformInfo::RGK_FixedWidthVector</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a8bb3b1ccf19b8c85429b777dfa4a0166a331413d3887a08546d0973091f6a4993">llvm::TargetTransformInfo::RGK_ScalableVector</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a8bb3b1ccf19b8c85429b777dfa4a0166ad8f233645107107ed48d2e4a915152cc">llvm::TargetTransformInfo::RGK_Scalar</a>.</p>

</div>
</div>

### getShuffleCost() {#aefd2591b1c59fbc42ad11361b7e23518}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost GCNTTIImpl::getShuffleCost (<a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af46433d0e36d3f80afc3a8c67b5c53ec">TTI::ShuffleKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * Tp, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, int Index, <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * SubTp, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Args={}, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CxtI=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 1146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac214df91cdc242f4710ea5a93939c678">llvm::count_if</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#aec0b8db50138e2a68aca36959b6692a5">llvm::BasicTTIImplBase&lt; GCNTTIImpl &gt;::DL</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#afdce715c901d62e2c1367a0ff5248175">llvm::VectorType::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a60269460307676b0f5be6e2e22044529">llvm::BasicTTIImplBase&lt; GCNTTIImpl &gt;::getShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a43d9b7161f7ae393a165599ca211fe2f">llvm::BasicTTIImplBase&lt; GCNTTIImpl &gt;::improveShuffleKindFromMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af46433d0e36d3f80afc3a8c67b5c53ecab1ac8982cdb119f39a5fe74610a46796">llvm::TargetTransformInfo::SK_Broadcast</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af46433d0e36d3f80afc3a8c67b5c53ecafd6c03f570400fcb24d861aa21ddffe9">llvm::TargetTransformInfo::SK_ExtractSubvector</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af46433d0e36d3f80afc3a8c67b5c53eca466a4d581cf3a553414b9c2e889b944a">llvm::TargetTransformInfo::SK_InsertSubvector</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af46433d0e36d3f80afc3a8c67b5c53eca7beec9815d0197f2d31fac9968e9205b">llvm::TargetTransformInfo::SK_PermuteSingleSrc</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af46433d0e36d3f80afc3a8c67b5c53ecab4616961a3bfdaec42aedc4fc426ccfe">llvm::TargetTransformInfo::SK_PermuteTwoSrc</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af46433d0e36d3f80afc3a8c67b5c53ecaea788d98147161f25d5adc3ec6ce7e1f">llvm::TargetTransformInfo::SK_Reverse</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af46433d0e36d3f80afc3a8c67b5c53eca64d439485545faa793c20de7fbfd274c">llvm::TargetTransformInfo::SK_Select</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af46433d0e36d3f80afc3a8c67b5c53ecaa9e18b2636661e341804da24971997df">llvm::TargetTransformInfo::SK_Splice</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2aef8609af541a5b1b01484b29d0f62534">llvm::AMDGPUSubtarget::VOLCANIC_ISLANDS</a>.</p>

</div>
</div>

### getStoreVectorFactor() {#a5bbfb3bc77775d693176036e552f4f89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GCNTTIImpl::getStoreVectorFactor (unsigned VF, unsigned StoreSize, unsigned ChainSizeInBytes, <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * VecTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getTgtMemIntrinsic() {#a8de5bf4f45a9fe750de151c5532d4fec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNTTIImpl::getTgtMemIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * Inst, <a href="/web-llvm/docs/api/structs/llvm/memintrinsicinfo">MemIntrinsicInfo</a> &amp; Info)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 520 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst/#a7ff64b3625b6f9020556ed05a5f72af4">llvm::IntrinsicInst::getIntrinsicID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ae3b0fa849dbd758b450f98fcfde936a2">llvm::SequentiallyConsistent</a>.</p>

</div>
</div>

### getUnrollingPreferences() {#a74357df9d89b3b32fbdc98894a64d776}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNTTIImpl::getUnrollingPreferences (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences">TTI::UnrollingPreferences</a> &amp; UP, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> * ORE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 1394 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getVectorInstrCost() {#a0f0c067bd859c66c848ab7d23639c3e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost GCNTTIImpl::getVectorInstrCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ValTy, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, unsigned Index, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 859 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#aec0b8db50138e2a68aca36959b6692a5">llvm::BasicTTIImplBase&lt; GCNTTIImpl &gt;::DL</a> and <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a27bfcb3dd99fa7a7ca8dc24eeac6e8e6">llvm::BasicTTIImplBase&lt; GCNTTIImpl &gt;::getVectorInstrCost</a>.</p>

</div>
</div>

### getVectorInstrCost() {#a7c38fde7667a3797047f16dce4017457}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost llvm::BasicTTIImplBase&lt; GCNTTIImpl &gt;::getVectorInstrCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, unsigned Index, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Scalar, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/user">User</a> *, int &gt; &gt; ScalarUserAndIdx)</td>
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




<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ScalarUserAndIdx</td>
<td class="doxyParamItemDescription"><p>encodes the information about extracts from a vector with 'Scalar' being the value being extracted,'<a href="/web-llvm/docs/api/classes/llvm/user">User</a>' being the user of the <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/loopextractor-cpp/#a84dff14934298a71113ab11312c243f6">extract(nullptr if user is not known before vectorization)</a> and 'Idx' being the extract lane.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 1355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicttiimpl-h">BasicTTIImpl.h</a>.</p>

</div>
</div>

### getVectorInstrCost() {#a0c49c54ca70e79f02ea0f0e9c21d779c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost llvm::BasicTTIImplBase&lt; GCNTTIImpl &gt;::getVectorInstrCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, unsigned Index)</td>
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



<p>Declaration at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 1363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicttiimpl-h">BasicTTIImpl.h</a>.</p>

</div>
</div>

### getVectorSplitCost() {#a883340380993770830f245b05a84d472}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost llvm::GCNTTIImpl::getVectorSplitCost ()</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>.</p>

</div>
</div>

### hasBranchDivergence() {#aeef5bd47e34fd5b8224c2b25a7d71a75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNTTIImpl::hasBranchDivergence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### instCombineIntrinsic() {#ae3d1835a72f8f0ba85ace9e2c0fbfc96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; Instruction * &gt; GCNTTIImpl::instCombineIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/instcombiner">InstCombiner</a> &amp; IC, <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; II)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp">AMDGPUInstCombineIntrinsic.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#a0f72a62efd0912aba72c6818c720023c">llvm::CallBase::addFnAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#ad8c80fc37943fda4be56cf1e0b6cb145">llvm::FastMathFlags::allowContract</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#ae1d331bc844ecb92bdeb0b706ae04396">llvm::InstCombiner::Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#a472408c33fff86419b4ff8fb2e343a64">canContractSqrtToRsq</a>, <a href="#ae5be25044bcd47e6c80f68c90159891f">canSimplifyLegacyMulToMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3cd3a3ec28036937ecebe767498ba55d">llvm::ConstantFoldCompareInstOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a257e3cb529defa79ad7a9f42072f339a">llvm::APFloat::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#adc6a2686b807c18e4a7f7fc58e68d423">llvm::IRBuilderBase::CreateAShr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a102aafbf0ca4e05fa1620a24f797fcfb">llvm::IRBuilderBase::CreateExtractVector</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad27ceb2345c5c425b50c7e88ae8f75bb">llvm::IRBuilderBase::CreateFAddFMF</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aec0517c3f23ebbd05772964b3d4ab793">llvm::IRBuilderBase::CreateFMulFMF</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6ef1729b04a4fbd6c6f27787cdd0e813">llvm::IRBuilderBase::CreateICmpNE</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a17320ebd77e834577a5ebd1063039625">llvm::IRBuilderBase::CreateInsertElement</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5849d19e500f8c6713ec44889058f424">llvm::IRBuilderBase::CreateLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a095134beddcf2138be07947f93e44437">llvm::IRBuilderBase::CreateMaxNum</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4710e2f0e50f8caca5afc934c26445c6">llvm::IRBuilderBase::CreateMinNum</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5253081f40ffcad9c0e8ba6a5c437006">llvm::IRBuilderBase::CreateSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b6a3be6451cf6a789d9305d90751c40">llvm::IRBuilderBase::CreateShl</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9e6950f7f17700d5c0d61ad0b846ec5c">llvm::IRBuilderBase::CreateZExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#a7fbae83b06276268455de0368194f94a">defaultComponentBroadcast</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a107d394b970c9f03a486a15cdd08f0df">llvm::APFloat::divide</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#aec0b8db50138e2a68aca36959b6692a5">llvm::BasicTTIImplBase&lt; GCNTTIImpl &gt;::DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#a190073d8a0e9a2eeb56f0cb96816d7ef">llvm::InstCombiner::eraseInstFromFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a403260df3a211e47e65f35fbfd9bee8faf5ccb8d51ca38e2f3329955fc0149cd4">llvm::Exponent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaf552e181879ad14956985859308d77d9">llvm::FAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dabf7829a22591343ad790b1357955a7df">llvm::fcAllFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba392f2cfc83c62daa024d96b8a13872f8">llvm::CmpInst::FIRST_FCMP_PREDICATE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba1d680986286d79b2eb671750e9c78dbe">llvm::CmpInst::FIRST_ICMP_PREDICATE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#aadf903de6f82a588de4eed4d082b5b8c">fmed3AMDGCN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eab48b2a9934af7a531cfd7236ded9d50e">llvm::FMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/mfmascaleformats/#a9785fc000bbc68de951782f0262a4916a80efc414ecf3af8e0199e92491ba39de">llvm::AMDGPU::MFMAScaleFormats::FP4_E2M1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/mfmascaleformats/#a9785fc000bbc68de951782f0262a4916ab51206bafa983cccd8077b420ea9c815">llvm::AMDGPU::MFMAScaleFormats::FP6_E2M3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/mfmascaleformats/#a9785fc000bbc68de951782f0262a4916a9c623040c1fd2e15080bb0b86bb3557e">llvm::AMDGPU::MFMAScaleFormats::FP6_E3M2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/mfmascaleformats/#a9785fc000bbc68de951782f0262a4916a9a32ce37983385a998153cfe4db24902">llvm::AMDGPU::MFMAScaleFormats::FP8_E4M3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/mfmascaleformats/#a9785fc000bbc68de951782f0262a4916a7040322aab91653ad01a2b617e4da207">llvm::AMDGPU::MFMAScaleFormats::FP8_E5M2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a53d315bdfbe8ab3760ebbea3faebc5f8">llvm::frexp</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#affbb7e2e9ad8d18114816f2443d672b9">llvm::MDString::get</a>, <a href="/web-llvm/docs/api/classes/llvm/metadataasvalue/#a3188a1aa0df768d8f254cd8d8fdeface">llvm::MetadataAsValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a4ae5ff22b700a42bcc5d889233721335">llvm::UndefValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa2ed385be8984b4306762990278eb13d">llvm::IRBuilderBase::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa7cce62ac5cc6df09cce0535874336b7">llvm::ConstantInt::getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator/#a8be4fec4d0b6071fb7d7520364fd5378">llvm::FPMathOperator::getFastMathFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ae550f2e9436b395b614b4377ba27007f">llvm::Type::getHalfTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aed8a22d92c99b81842589d3cd66c7bee">llvm::AMDGPU::getImageDimIntrinsicInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a6f2864671b22c9f6135b6ae5d41bcf54">llvm::ConstantFP::getInfinity</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a73f286a780fbb8c82c0a8574540719ea">llvm::IRBuilderBase::getInt64</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a31e2db8d1b315202d2c19e711b5365fd">llvm::IRBuilderBase::getIntNTy</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa2a54b545d237ecfe450fd1292f7675e">llvm::CmpInst::getInversePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#ab21342133676f10340dc3f541b128f24">llvm::ConstantFP::getNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a010e22ea9432c4b7d5962406932ed27b">llvm::APFloat::getQNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a643f8cd038a6fa41604fe8e3df11f977">llvm::APFloat::getSemantics</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#af56f7a148b00922368e55ab9c4948724">llvm::InstCombiner::getSimplifyQuery</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#af7e1934ed72a405ef073ea5f9bbe828e">llvm::ConstantInt::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a32aa14715eeb813d764fcf20f161f0a1">llvm::ConstantFP::getValueAPF</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#af591f8d18d0d9773192a0ffcca41796e">llvm::APFloat::getZero</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a75071440d60c24178371ca1299f4ef07">llvm::ConstantFP::getZero</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#ac09a21c371a9c535cbc13e8f82503aec">llvm::ConstantInt::getZExtValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a86415bb448a78ef1fed893f9eb0f5d06">llvm::APFloatBase::IEEEhalf</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aa78db24ff4e5fbe0c3013bd4b9edb7fca4c1772918997b32aa846df0cf32ca5f1">llvm::APFloatBase::IEK_Inf</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aa78db24ff4e5fbe0c3013bd4b9edb7fca23abe3c9be234401b670eed6856bc850">llvm::APFloatBase::IEK_NaN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a7bd850492d35a34f0fe419e5555997a9">llvm::CmpInst::isFPPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a763d4ccd87f2c21d2079796c0c9cd51a">llvm::APFloat::isNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#ae4b6abe77abf42fb02081a6cc41a0132">llvm::Constant::isNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a3712279d70deeec90a93db09deb12d02">llvm::CmpInst::isSigned</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#a4aa190c8317e282f580adfb651ea3d81">isTriviallyUniform</a>, <a href="/web-llvm/docs/api/structs/llvm/simplifyquery/#a8349c0152a8ece08ab63f6180baa7c8e">llvm::SimplifyQuery::isUndefValue</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bab10f753354ede9597f74448afbb0762c">llvm::CmpInst::LAST_FCMP_PREDICATE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa5c6e466e2df2c472e487f84531421fc">llvm::CmpInst::LAST_ICMP_PREDICATE</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a00ef056813d120034e387417e9cde341">llvm::PatternMatch::m_AllOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2c7e2b8240233bff5e5f1b38465420c1">llvm::PatternMatch::m_AnyZeroFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a7d9ab823fe85606fa795c0c6fc75aca6">llvm::PatternMatch::m_Cmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a67f7e0bb72983944baabef82bc0d9b49">llvm::PatternMatch::m_ConstantFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a66f6b638df59d75afc83d660a173f53d">llvm::PatternMatch::m_FPExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae138cfc26c6b3f24fd6fc3f3dfcbdfeb">llvm::PatternMatch::m_NaN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3b3d2d8c64a7881acb82bc7467569aa9">llvm::PatternMatch::m_One</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae5cf2b09af0c75d08cf9e5e8f2818a66">llvm::PatternMatch::m_SExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae77be336e228cf9aa00709a8606dfb98">llvm::PatternMatch::m_Zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a6ba4022cd30993a84d111871dd0f6ba6">llvm::PatternMatch::m_ZExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab9dc78a306f2befc7dc7f1da8c9eaca2">llvm::PatternMatch::m_ZExtOrSExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af54e0572ecf26033ac3fe4513016dfbe">llvm::Make_64</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a74b616ebc9fe99bb3d64e0f8181d8de7">llvm::APFloat::makeQuiet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#ae04610310004450abde7293643734104">matchFPExtFromF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7ca44467144e3b6bdac3e85ef6f90e7d832">llvm::NearestTiesToEven</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#a49f1bd0bdf0ef741bdd714cc1188d7c5">llvm::InstCombiner::replaceInstUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#ac2a56636a6f3742f5e495f67e67b6b36">llvm::InstCombiner::replaceOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a482d9cf95b588eb05cefeaa5c05be9a3">llvm::APFloatBase::rmTowardZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7757f52e61c8e086d79bdd166f50bb02">llvm::scalbn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#ab2354d93dbb7ffbde58e687309f44fad">simplifyAMDGCNImageIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#aae1a4eb9b437e719a333c79f74c9a1b2">simplifyAMDGCNMemoryIntrinsicDemanded</a>, <a href="#a1747fa66edae41ea9492c338ef853e12">simplifyDemandedLaneMaskArg</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ae855357b6c5e6e7ed1869272708a3a84">llvm::Value::takeName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#a58e687cb25ed94c378fc444895422a13">trimTrailingZerosInVector</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a317c64fd4cfebc88e79387b3821a629d">llvm::APInt::trunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### isAlwaysUniform() {#a11fb81052cf8abb712c95daa2f0344d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNTTIImpl::isAlwaysUniform (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 992 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2c2c51743fb4a1b17c59563909f3f24">llvm::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#aec0b8db50138e2a68aca36959b6692a5">llvm::BasicTTIImplBase&lt; GCNTTIImpl &gt;::DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/extractvalueinst/#a089f295919afbb059f9f745206094002">llvm::ExtractValueInst::getIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a018f0394a375233d538109968b76a05a">llvm::CallBase::isInlineAsm</a>, <a href="#a3e874f5073fd59211348a2ea23e9d0ce">isInlineAsmSourceOfDivergence</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5ee59b5ad9e64f6b900b6cdd5567b15b">llvm::AMDGPU::isIntrinsicAlwaysUniform</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a0c94f3ca4234f78cf22840e79087f3f2">llvm::PatternMatch::m_AShr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a1981217907f3dfb1d21e902d0396fb4d">llvm::PatternMatch::m_c_And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3aa1f5d3cd54d36e7e47f401a0118aeb">llvm::PatternMatch::m_ConstantInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3c0adc1054838f4498e0e860b637a22b">llvm::PatternMatch::m_Intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab8546ee1aaa68d6f4990e6241e24464c">llvm::PatternMatch::m_LShr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### isInlineAsmSourceOfDivergence() {#a3e874f5073fd59211348a2ea23e9d0ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNTTIImpl::isInlineAsmSourceOfDivergence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; Indices={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Analyze if the results of inline asm are divergent.</p>


<p>If <span class="doxyComputerOutput">Indices</span> is empty, this is analyzing the collective result of all output registers. Otherwise, this is only querying a specific result index if this returns multiple registers in a struct.</p>


<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 891 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#aec0b8db50138e2a68aca36959b6692a5">llvm::BasicTTIImplBase&lt; GCNTTIImpl &gt;::DL</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af65afd02332c4f21c2fab7d217d6600f">llvm::Instruction::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a511f48809ad14f13e50b957a137a9d34aabfa616f81b4833fdf462b07aabfa53f">llvm::InlineAsm::isOutput</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#a11fb81052cf8abb712c95daa2f0344d6">isAlwaysUniform</a> and <a href="#adcaf33f0c60678d66d47c074de4cc46a">isSourceOfDivergence</a>.</p>

</div>
</div>

### isLegalToVectorizeLoadChain() {#a1e8a8bc0e04667c2fe7c0470f66483c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNTTIImpl::isLegalToVectorizeLoadChain (unsigned ChainSizeInBytes, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, unsigned AddrSpace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="#a5355c5e0a1cb9fecfd198f6d7c3714dd">isLegalToVectorizeMemChain</a>.</p>

</div>
</div>

### isLegalToVectorizeMemChain() {#a5355c5e0a1cb9fecfd198f6d7c3714dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNTTIImpl::isLegalToVectorizeMemChain (unsigned ChainSizeInBytes, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, unsigned AddrSpace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aec164f45437d8827346f2d8ec645479a">llvm::AMDGPUAS::PRIVATE_ADDRESS</a>.</p>


<p>Referenced by <a href="#a1e8a8bc0e04667c2fe7c0470f66483c5">isLegalToVectorizeLoadChain</a> and <a href="#a624b8c25783d9c13165a7960e501ef66">isLegalToVectorizeStoreChain</a>.</p>

</div>
</div>

### isLegalToVectorizeStoreChain() {#a624b8c25783d9c13165a7960e501ef66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNTTIImpl::isLegalToVectorizeStoreChain (unsigned ChainSizeInBytes, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, unsigned AddrSpace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="#a5355c5e0a1cb9fecfd198f6d7c3714dd">isLegalToVectorizeMemChain</a>.</p>

</div>
</div>

### isProfitableToSinkOperands() {#a7302061b4aaf73033fc317a6ab8b8d65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNTTIImpl::isProfitableToSinkOperands (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> * &gt; &amp; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether it is profitable to sink the operands of an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> I to the basic block of I.</p>


<p>This helps using several modifiers (like abs and neg) more often.</p>


<p>Declaration at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 1209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#af07397df05f8eb1838b6d79871791e38">llvm::PatternMatch::m_FAbs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aba7473bfa862dd9eadf04a6fefc6aa69">llvm::PatternMatch::m_FNeg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>

</div>
</div>

### isReadRegisterSourceOfDivergence() {#a3f1861e30cebca3c33d71a2e73de0c5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNTTIImpl::isReadRegisterSourceOfDivergence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * ReadReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 927 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a56bb53e2d0b01c78c8c538f903fd45b8">llvm::MVT::getVT</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lvlgen-cpp/#a0a198e38a5def54ba58bebc655eda8e7">RegName</a>.</p>


<p>Referenced by <a href="#adcaf33f0c60678d66d47c074de4cc46a">isSourceOfDivergence</a>.</p>

</div>
</div>

### isSourceOfDivergence() {#adcaf33f0c60678d66d47c074de4cc46a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNTTIImpl::isSourceOfDivergence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the result of the value could potentially be different across workitems in a wavefront.</p></dd>
</dl>


<p>Declaration at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 950 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aaa1e27e4fc68e5706a4b7bbaed447c14">llvm::AMDGPUAS::FLAT_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5d7d70152f1d904df03f92ba26418387">llvm::AMDGPU::isArgPassedInSGPR</a>, <a href="#a3e874f5073fd59211348a2ea23e9d0ce">isInlineAsmSourceOfDivergence</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8ab2011ec30da8a5edbd54bf0e498363">llvm::AMDGPU::isIntrinsicSourceOfDivergence</a>, <a href="#a3f1861e30cebca3c33d71a2e73de0c5b">isReadRegisterSourceOfDivergence</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aec164f45437d8827346f2d8ec645479a">llvm::AMDGPUAS::PRIVATE_ADDRESS</a>.</p>

</div>
</div>

### isValidAddrSpaceCast() {#a5b5f809d01fe5e1162f330b6a2ee9552}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNTTIImpl::isValidAddrSpaceCast (unsigned FromAS, unsigned ToAS)</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a1caf1e287a5fe7250388d66ed72aa0c1">llvm::AMDGPUAS::CONSTANT_ADDRESS_32BIT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aaa1e27e4fc68e5706a4b7bbaed447c14">llvm::AMDGPUAS::FLAT_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ad67d696d7847623b61c63942d86f27ef">llvm::AMDGPU::isExtendedGlobalAddrSpace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a22dc5c679c09756d04fe07f9e22baf84">llvm::AMDGPU::isFlatGlobalAddrSpace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a77b1c964e2ff99057bf5e75140457abe">llvm::AMDGPUAS::LOCAL_ADDRESS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aec164f45437d8827346f2d8ec645479a">llvm::AMDGPUAS::PRIVATE_ADDRESS</a>.</p>

</div>
</div>

### rewriteIntrinsicWithAddressSpace() {#a9910dce4a3e020d503a0e4062d66646f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * GCNTTIImpl::rewriteIntrinsicWithAddressSpace (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * II, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * OldV, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NewV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 1077 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2c2c51743fb4a1b17c59563909f3f24">llvm::computeKnownBits</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a1d90fff0f1479f662286338ffecd7f05">llvm::KnownBits::countMinLeadingOnes</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#aec0b8db50138e2a68aca36959b6692a5">llvm::BasicTTIImplBase&lt; GCNTTIImpl &gt;::DL</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a909eca4ba9e5eefc203c8e3770bdab25">llvm::Type::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa7cce62ac5cc6df09cce0535874336b7">llvm::ConstantInt::getFalse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5ab2d0b0f0b8ceec3b907184e7567197">llvm::Type::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ad67d696d7847623b61c63942d86f27ef">llvm::AMDGPU::isExtendedGlobalAddrSpace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a77b1c964e2ff99057bf5e75140457abe">llvm::AMDGPUAS::LOCAL_ADDRESS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aec164f45437d8827346f2d8ec645479a">llvm::AMDGPUAS::PRIVATE_ADDRESS</a>.</p>

</div>
</div>

### shouldPrefetchAddressSpace() {#a5b93f987c913933d2e8cc77fe73da617}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNTTIImpl::shouldPrefetchAddressSpace (unsigned AS)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>if target want to issue a prefetch in address space <span class="doxyComputerOutput">AS</span>.</p></dd>
</dl>


<p>Declaration at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 1430 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a22dc5c679c09756d04fe07f9e22baf84">llvm::AMDGPU::isFlatGlobalAddrSpace</a>.</p>

</div>
</div>

### simplifyDemandedLaneMaskArg() {#a1747fa66edae41ea9492c338ef853e12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNTTIImpl::simplifyDemandedLaneMaskArg (<a href="/web-llvm/docs/api/classes/llvm/instcombiner">InstCombiner</a> &amp; IC, <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; II, unsigned LaneArgIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Simplify a lane index operand (e.g.</p>


<p>llvm.amdgcn.readlane src1).</p>


<p>The instruction only reads the low 5 bits for wave32, and 6 bits for wave64.</p>


<p>Declaration at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp">AMDGPUInstCombineIntrinsic.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/knownbits/#afd1c330d00d17bd267450ab43d5f0eec">llvm::KnownBits::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a5274c29c7da2473d342adfa98f34a025">llvm::KnownBits::isConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79dff91526e31b1a05f59eed6c189eb4">llvm::maskTrailingOnes</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#a95d0ee42ca35b04f96e22c6ae954e2f7">llvm::InstCombiner::SimplifyDemandedBits</a>.</p>


<p>Referenced by <a href="#ae3d1835a72f8f0ba85ace9e2c0fbfc96">instCombineIntrinsic</a>.</p>

</div>
</div>

### simplifyDemandedVectorEltsIntrinsic() {#a4c469b9715a7fccaba1b1d673597682c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; Value * &gt; GCNTTIImpl::simplifyDemandedVectorEltsIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/instcombiner">InstCombiner</a> &amp; IC, <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; II, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> DemandedElts, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; UndefElts, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; UndefElts2, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; UndefElts3, std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, unsigned, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;)&gt; SimplifyAndSetOp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 1538 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp">AMDGPUInstCombineIntrinsic.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#aae1a4eb9b437e719a333c79f74c9a1b2">simplifyAMDGCNMemoryIntrinsicDemanded</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### get64BitInstrCost() {#a5acae0ee67a85000756d6092e279e0ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int GCNTTIImpl::get64BitInstrCost (<a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 1405 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getST() {#a0c1e1b6a35a698fe2897453c3fc9bc78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GCNSubtarget * llvm::GCNTTIImpl::getST ()</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>.</p>

</div>
</div>

### getTLI() {#af407f42a426ea51df3d855630dace9cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SITargetLowering * llvm::GCNTTIImpl::getTLI ()</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>.</p>

</div>
</div>

### getTypeLegalizationCost() {#acd144d77eb83570b9357a87be6436050}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; InstructionCost, MVT &gt; GCNTTIImpl::getTypeLegalizationCost (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>, definition at line 1413 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BaseT {#a72880c841c19ba0188ec9bc3de940880}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::GCNTTIImpl::BaseT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>.</p>

</div>
</div>

### CommonTTI {#a42a49692a2fa8c44734a64f2c8cd0383}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPUTTIImpl llvm::GCNTTIImpl::CommonTTI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>.</p>

</div>
</div>

### HasFP32Denormals {#abaefa3538cd4912511c6f698275a85dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNTTIImpl::HasFP32Denormals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>.</p>

</div>
</div>

### HasFP64FP16Denormals {#a52a92e3c1c14ba5f677fb51799df4e63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNTTIImpl::HasFP64FP16Denormals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>.</p>

</div>
</div>

### IsGraphics {#ae01e15d49b1faaaf48d8e9371e099244}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNTTIImpl::IsGraphics</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>.</p>

</div>
</div>

### ST {#a70668df44acfd1359f0503169b40f6b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GCNSubtarget* llvm::GCNTTIImpl::ST</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>.</p>

</div>
</div>

### TLI {#a1690c829bc65b1865b73ac8d51dc2bfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SITargetLowering* llvm::GCNTTIImpl::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getFullRateInstrCost() {#ad12661481860e268d0d31ec17093d0dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::GCNTTIImpl::getFullRateInstrCost ()</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>.</p>

</div>
</div>

### getHalfRateInstrCost() {#adec33a5f18cccc8f7e9f1549c34e9daf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::GCNTTIImpl::getHalfRateInstrCost (<a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind)</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>.</p>

</div>
</div>

### getQuarterRateInstrCost() {#a703eba755312a0cf60db2c18666dfcef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::GCNTTIImpl::getQuarterRateInstrCost (<a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind)</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### InlineFeatureIgnoreList {#a0b9ebe63a0046f959313f2e6f9af470e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FeatureBitset GCNTTIImpl::InlineFeatureIgnoreList</td>
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
    AMDGPU::FeatureEnableLoadStoreOpt, AMDGPU::FeatureEnableSIScheduler,
    AMDGPU::FeatureEnableUnsafeDSOffsetFolding, AMDGPU::FeatureFlatForGlobal,
    AMDGPU::FeaturePromoteAlloca, AMDGPU::FeatureUnalignedScratchAccess,
    AMDGPU::FeatureUnalignedAccessMode,
    AMDGPU::FeatureAutoWaitcntBeforeBarrier,
    AMDGPU::FeatureSGPRInitBug, AMDGPU::FeatureXNACK,
    AMDGPU::FeatureTrapHandler,
    AMDGPU::FeatureSRAMECC,
    AMDGPU::FeatureFastFMAF32, AMDGPU::HalfRate64Ops}
</div>
</dd>
</dl>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>.</p>

</div>
</div>

### InlinerVectorBonusPercent {#ab06e07b89bb8c532da42cda3a0b9dddf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNTTIImpl::InlinerVectorBonusPercent = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicttiimpl-h">BasicTTIImpl.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp">AMDGPUInstCombineIntrinsic.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp">AMDGPUTargetTransformInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-h">AMDGPUTargetTransformInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
