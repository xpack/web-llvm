---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ppcttiimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PPCTTIImpl` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::PPCTTIImpl { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">Target/PowerPC/PPCTargetTransformInfo.h</a>"
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase">BasicTTIImplBase</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl">PPCTTIImpl</a> &gt; <a href="#a3f3b602e5aa0e5fbafe0f9cbd8ddfeb8">BaseT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> <a href="#a9b013e4de4eaf16f9109406454769c9e">TTI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67ad9b6f523e8f069393cc63f5ebbd48">PPCTTIImpl</a> (const PPCTargetMachine *TM, const Function &amp;F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04dad23556e58f793c9a508a1a2d9aa5">instCombineIntrinsic</a> (InstCombiner &amp;IC, IntrinsicInst &amp;II) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f6340e1553fa5efe4ac982aca342489">getST</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering">PPCTargetLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a363c4cd25ea027c9e16858d5c3a96237">getTLI</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6890cfbdd46db394eee48c877fefac8">BaseT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e5553af40f0126bfe71532e89785e25">ST</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering">PPCTargetLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2c9b2402e03f00e25275fb9338094bf">TLI</a></td>
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

## Vector TTI Implementations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">PPCRegisterClass { <a href="#a749451435ba7f18d4f92452cb9d4dfad">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#a5dbf65370a0656ea05a0aa97380c15cc">InstructionCost::CostType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b47f55029778253ccb3757c11867129">P9PipelineFlushEstimate</a> = 80</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ff1ab275738e5fd76b99302ea1914b7">useColdCCForColdCall</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a25c64855261e250b463691ffdab8be">enableAggressiveInterleaving</a> (bool LoopHasReductions)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/memcmpexpansionoptions">TTI::MemCmpExpansionOptions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50c0298502cc0cc5f2f7d11494f19384">enableMemCmpExpansion</a> (bool OptSize, bool IsZeroCmp) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c46642946508facc3825d05daac7222">enableInterleavedAccessVectorization</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3cd8f854314b1fac90c62cdf631f475">getNumberOfRegisters</a> (unsigned ClassID) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a554d0473620971823cbfe3109899c5fb">getRegisterClassForType</a> (bool Vector, Type *Ty=nullptr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13a06481e8adc2b65dcfb2f8f90efd84">getRegisterClassName</a> (unsigned ClassID) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08b9d86ee30f4a9280fda16fd5ecc77a">getRegisterBitWidth</a> (TargetTransformInfo::RegisterKind K) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66df225854bad2f92747deb811d070d3">getCacheLineSize</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a78235a7e939764a03017aaaf4a85ed">getPrefetchDistance</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e416262d1392f777f79a7f003f92be6">getMaxInterleaveFactor</a> (ElementCount VF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40003c9aae5f4e1d9cf4b042db0b0c13">vectorCostAdjustmentFactor</a> (unsigned Opcode, Type *Ty1, Type *Ty2)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35de5712aacf900ec00d1817008eeed1">getArithmeticInstrCost</a> (unsigned Opcode, Type *Ty, TTI::TargetCostKind CostKind, TTI::OperandValueInfo Op1Info={TTI::OK_AnyValue, TTI::OP_None}, TTI::OperandValueInfo Op2Info={TTI::OK_AnyValue, TTI::OP_None}, ArrayRef&lt; const Value * &gt; Args={}, const Instruction *CxtI=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2933bd38a4062250af0ebb41af0caa10">getShuffleCost</a> (TTI::ShuffleKind Kind, Type *Tp, ArrayRef&lt; int &gt; Mask, TTI::TargetCostKind CostKind, int Index, Type *SubTp, ArrayRef&lt; const Value * &gt; Args={}, const Instruction *CxtI=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa96045bfcd00b9908c624a5626b2c05c">getCastInstrCost</a> (unsigned Opcode, Type *Dst, Type *Src, TTI::CastContextHint CCH, TTI::TargetCostKind CostKind, const Instruction *I=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3967bfcec657293510c71cfbd5615fb">getCFInstrCost</a> (unsigned Opcode, TTI::TargetCostKind CostKind, const Instruction *I=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a228a182df5d1f649d5b9f6dc8be75011">getCmpSelInstrCost</a> (unsigned Opcode, Type *ValTy, Type *CondTy, CmpInst::Predicate VecPred, TTI::TargetCostKind CostKind, TTI::OperandValueInfo Op1Info={TTI::OK_AnyValue, TTI::OP_None}, TTI::OperandValueInfo Op2Info={TTI::OK_AnyValue, TTI::OP_None}, const Instruction *I=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a513e1873d7e7760f5e0241cc47a9aaca">getVectorInstrCost</a> (unsigned Opcode, Type *Val, TTI::TargetCostKind CostKind, unsigned Index, Value *Op0, Value *Op1)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ab346ad59b02578a3fc143c77397761">getMemoryOpCost</a> (unsigned Opcode, Type *Src, MaybeAlign Alignment, unsigned AddressSpace, TTI::TargetCostKind CostKind, TTI::OperandValueInfo OpInfo={TTI::OK_AnyValue, TTI::OP_None}, const Instruction *I=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afffe3207f30907d3ca4800ba3d26c9f0">getInterleavedMemoryOpCost</a> (unsigned Opcode, Type *VecTy, unsigned Factor, ArrayRef&lt; unsigned &gt; Indices, Align Alignment, unsigned AddressSpace, TTI::TargetCostKind CostKind, bool UseMaskForCond=false, bool UseMaskForGaps=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61d83c6f5d42c6579fc916fe97c02521">getIntrinsicInstrCost</a> (const IntrinsicCostAttributes &amp;ICA, TTI::TargetCostKind CostKind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae97a40d2d5ce54b3cef2afa036bc7117">areTypesABICompatible</a> (const Function *Caller, const Function *Callee, const ArrayRef&lt; Type * &gt; &amp;Types) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4522ba73eb89ae20c7ca46349303f3e">hasActiveVectorLength</a> (unsigned Opcode, Type *DataType, Align Alignment) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2dcbf9f4bf17b489bfdebc4187d25d4">getVPMemoryOpCost</a> (unsigned Opcode, Type *Src, Align Alignment, unsigned AddressSpace, TTI::TargetCostKind CostKind, const Instruction *I=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a507c08cbe76f2b19fc1a62d7e02343ea">supportsTailCallFor</a> (const CallBase *CB) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fe170d5f331fc7235f2a8561ca5c633">getVectorInstrCost</a> (unsigned Opcode, Type *Val, TTI::TargetCostKind CostKind, unsigned Index, Value *Scalar, ArrayRef&lt; std::tuple&lt; Value *, User *, int &gt; &gt; ScalarUserAndIdx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45f97f77b0a63e7af5079590c2a55e3a">getVectorInstrCost</a> (const Instruction &amp;I, Type *Val, TTI::TargetCostKind CostKind, unsigned Index)</td>
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

## Scalar TTI Implementations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0371e739dcb4a90dd9b0ba18bc053de0">getIntImmCost</a> (const APInt &amp;Imm, Type *Ty, TTI::TargetCostKind CostKind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4dec9e04986a6b05f1b45b1a5f1e8d9">getIntImmCostInst</a> (unsigned Opcode, unsigned Idx, const APInt &amp;Imm, Type *Ty, TTI::TargetCostKind CostKind, Instruction *Inst=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa00f36dbd11c8c610cb8830398f0325b">getIntImmCostIntrin</a> (Intrinsic::ID IID, unsigned Idx, const APInt &amp;Imm, Type *Ty, TTI::TargetCostKind CostKind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada4520fadc98f59acef021bda2d6e608">getInstructionCost</a> (const User *U, ArrayRef&lt; const Value * &gt; Operands, TTI::TargetCostKind CostKind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a987c4241bbd15c993aef6c58ed7dbacf">getPopcntSupport</a> (unsigned TyWidth)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae46906a076a2ec35cf6a38e433b48219">isHardwareLoopProfitable</a> (Loop *L, ScalarEvolution &amp;SE, AssumptionCache &amp;AC, TargetLibraryInfo *LibInfo, HardwareLoopInfo &amp;HWLoopInfo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf88172fa9f5c04416b60fa78f99e756">canSaveCmp</a> (Loop *L, BranchInst **BI, ScalarEvolution *SE, LoopInfo *LI, DominatorTree *DT, AssumptionCache *AC, TargetLibraryInfo *LibInfo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a515494cf182cfa8aec53bd6fef47a11e">getTgtMemIntrinsic</a> (IntrinsicInst *Inst, MemIntrinsicInfo &amp;Info)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6801a1b19bf8856a09f270d85fe25e9b">getUnrollingPreferences</a> (Loop *L, ScalarEvolution &amp;SE, TTI::UnrollingPreferences &amp;UP, OptimizationRemarkEmitter *ORE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacabbc276d0d5461b5d81eaaea461afd">getPeelingPreferences</a> (Loop *L, ScalarEvolution &amp;SE, TTI::PeelingPreferences &amp;PP)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e2c6081215dcc909699433f341692f7">isLSRCostLess</a> (const TargetTransformInfo::LSRCost &amp;C1, const TargetTransformInfo::LSRCost &amp;C2)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a409659881a20291018136b459356ff92">isNumRegsMajorCostOfLSR</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4c88dd3817b1258525743dea78b07e7">shouldBuildRelLookupTables</a> () const</td>
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


<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### BaseT {#a3f3b602e5aa0e5fbafe0f9cbd8ddfeb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef BasicTTIImplBase&lt;PPCTTIImpl&gt; llvm::PPCTTIImpl::BaseT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>.</p>

</div>
</div>

### TTI {#a9b013e4de4eaf16f9109406454769c9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef TargetTransformInfo llvm::PPCTTIImpl::TTI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### PPCTTIImpl() {#a67ad9b6f523e8f069393cc63f5ebbd48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PPCTTIImpl::PPCTTIImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppctargetmachine">PPCTargetMachine</a> * TM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a01aadd7eea7124cd9f5cd7cea37d8dab">llvm::TargetTransformInfoImplBase::getDataLayout</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### instCombineIntrinsic() {#a04dad23556e58f793c9a508a1a2d9aa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; Instruction * &gt; PPCTTIImpl::instCombineIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/instcombiner">InstCombiner</a> &amp; IC, <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; II)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#ae1d331bc844ecb92bdeb0b706ae04396">llvm::InstCombiner::Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#ad2e0ab6d7096fe67a2216fe349044387">llvm::CastInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a303d984774b5c8af8ee4da0aa1960207">llvm::IRBuilderBase::CreateExtractElement</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a17320ebd77e834577a5ebd1063039625">llvm::IRBuilderBase::CreateInsertElement</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#aec0b8db50138e2a68aca36959b6692a5">llvm::BasicTTIImplBase&lt; PPCTTIImpl &gt;::DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a4ae5ff22b700a42bcc5d889233721335">llvm::UndefValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#ae2eddfa57a32ec610ce9685720d591b7">llvm::InstCombiner::getAssumptionCache</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#a16262e69f9cdf5d2c9d5623c3b06af43">llvm::InstCombiner::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#a209240824927e66a0caa50636623e79a">llvm::InstCombiner::getDominatorTree</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8246a9e9405ffe2a9d8d020a949c8e96">llvm::IRBuilderBase::getInt32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6e7b79b3933def717c2a0f2fc6fa38e0">llvm::getOrEnforceKnownAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getST() {#a8f6340e1553fa5efe4ac982aca342489}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PPCSubtarget * llvm::PPCTTIImpl::getST ()</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>.</p>

</div>
</div>

### getTLI() {#a363c4cd25ea027c9e16858d5c3a96237}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PPCTargetLowering * llvm::PPCTTIImpl::getTLI ()</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BaseT {#ad6890cfbdd46db394eee48c877fefac8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::PPCTTIImpl::BaseT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>.</p>

</div>
</div>

### ST {#a9e5553af40f0126bfe71532e89785e25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PPCSubtarget* llvm::PPCTTIImpl::ST</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>.</p>

</div>
</div>

### TLI {#ab2c9b2402e03f00e25275fb9338094bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PPCTargetLowering* llvm::PPCTTIImpl::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Vector TTI Implementations

### areTypesABICompatible {#ae97a40d2d5ce54b3cef2afa036bc7117}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTTIImpl::areTypesABICompatible (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Caller, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Callee, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; &amp; Types)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 898 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a194d9ca1854ce9ab70dc3fb51ac8fcf5">llvm::TargetTransformInfoImplBase::areTypesABICompatible</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a>.</p>

</div>
</div>

### enableAggressiveInterleaving {#a9a25c64855261e250b463691ffdab8be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTTIImpl::enableAggressiveInterleaving (bool LoopHasReductions)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34ab81d0aba13bef5a963bb14709390283e">llvm::PPC::DIR_A2</a>.</p>

</div>
</div>

### enableInterleavedAccessVectorization {#a7c46642946508facc3825d05daac7222}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTTIImpl::enableInterleavedAccessVectorization ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>

</div>
</div>

### enableMemCmpExpansion {#a50c0298502cc0cc5f2f7d11494f19384}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PPCTTIImpl::TTI::MemCmpExpansionOptions PPCTTIImpl::enableMemCmpExpansion (bool OptSize, bool IsZeroCmp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>.</p>

</div>
</div>

### getArithmeticInstrCost {#a35de5712aacf900ec00d1817008eeed1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost PPCTTIImpl::getArithmeticInstrCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/operandvalueinfo">TTI::OperandValueInfo</a> Op1Info={<a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#afa38851d75434d1476444ac93f94cb4ca9c0eecea29e9fa58e4dac7ee32b9b2ac">TTI::OK_AnyValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a733fb237f3037c95ed59de6055b176c5a2bc39e3785b29fe7bc4af768842a2072">TTI::OP_None</a>}, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/operandvalueinfo">TTI::OperandValueInfo</a> Op2Info={<a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#afa38851d75434d1476444ac93f94cb4ca9c0eecea29e9fa58e4dac7ee32b9b2ac">TTI::OK_AnyValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a733fb237f3037c95ed59de6055b176c5a2bc39e3785b29fe7bc4af768842a2072">TTI::OP_None</a>}, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Args={}, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CxtI=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 582 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#ae3c3eb22dfa7c2b373ac485024f99aa6">llvm::BasicTTIImplBase&lt; PPCTTIImpl &gt;::getArithmeticInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#a6de26b938774385a0a4fb0d0b2a32d48">llvm::InstructionCost::getMax</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#ae01c5ced9fe2fe50f421ae121483ef04">llvm::InstructionCost::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">llvm::TargetTransformInfo::TCK_RecipThroughput</a> and <a href="#a40003c9aae5f4e1d9cf4b042db0b0c13">vectorCostAdjustmentFactor</a>.</p>

</div>
</div>

### getCacheLineSize {#a66df225854bad2f92747deb811d070d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned PPCTTIImpl::getCacheLineSize ()</td>
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



<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 499 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34a1a5dee2be7c154497739282b30ab123c">llvm::PPC::DIR_PWR10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34af6a785f2b13ce7870e8e4e6b9653f32f">llvm::PPC::DIR_PWR11</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34a0c8a5dd168df904e8c29520a47502a61">llvm::PPC::DIR_PWR7</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34aa3de856d909c5b0166919bf6e4bd1a3d">llvm::PPC::DIR_PWR8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34a0a03bfd83c00f4d1edab975b7bfe7f36">llvm::PPC::DIR_PWR9</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34ac1fc2f6d654da4e5a6a601e19d423846">llvm::PPC::DIR_PWR_FUTURE</a>.</p>

</div>
</div>

### getCastInstrCost {#aa96045bfcd00b9908c624a5626b2c05c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost PPCTTIImpl::getCastInstrCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Dst, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Src, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af84cce349a77262269fd3f6756f37a64">TTI::CastContextHint</a> CCH, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 636 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#ad0c9ac06022884eb218dc8f8c4056e43">llvm::BasicTTIImplBase&lt; PPCTTIImpl &gt;::getCastInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#a6de26b938774385a0a4fb0d0b2a32d48">llvm::InstructionCost::getMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#ae01c5ced9fe2fe50f421ae121483ef04">llvm::InstructionCost::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">llvm::TargetTransformInfo::TCK_RecipThroughput</a> and <a href="#a40003c9aae5f4e1d9cf4b042db0b0c13">vectorCostAdjustmentFactor</a>.</p>

</div>
</div>

### getCFInstrCost {#af3967bfcec657293510c71cfbd5615fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost PPCTTIImpl::getCFInstrCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 627 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">llvm::TargetTransformInfo::TCK_RecipThroughput</a>.</p>

</div>
</div>

### getCmpSelInstrCost {#a228a182df5d1f649d5b9f6dc8be75011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost PPCTTIImpl::getCmpSelInstrCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ValTy, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * CondTy, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> VecPred, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/operandvalueinfo">TTI::OperandValueInfo</a> Op1Info={<a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#afa38851d75434d1476444ac93f94cb4ca9c0eecea29e9fa58e4dac7ee32b9b2ac">TTI::OK_AnyValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a733fb237f3037c95ed59de6055b176c5a2bc39e3785b29fe7bc4af768842a2072">TTI::OP_None</a>}, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/operandvalueinfo">TTI::OperandValueInfo</a> Op2Info={<a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#afa38851d75434d1476444ac93f94cb4ca9c0eecea29e9fa58e4dac7ee32b9b2ac">TTI::OK_AnyValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a733fb237f3037c95ed59de6055b176c5a2bc39e3785b29fe7bc4af768842a2072">TTI::OP_None</a>}, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 656 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a50b7e0e6b16449abf0d13e75ddd43c58">llvm::BasicTTIImplBase&lt; PPCTTIImpl &gt;::getCmpSelInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#a6de26b938774385a0a4fb0d0b2a32d48">llvm::InstructionCost::getMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#ae01c5ced9fe2fe50f421ae121483ef04">llvm::InstructionCost::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">llvm::TargetTransformInfo::TCK_RecipThroughput</a> and <a href="#a40003c9aae5f4e1d9cf4b042db0b0c13">vectorCostAdjustmentFactor</a>.</p>

</div>
</div>

### getInterleavedMemoryOpCost {#afffe3207f30907d3ca4800ba3d26c9f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost PPCTTIImpl::getInterleavedMemoryOpCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * VecTy, unsigned Factor, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; Indices, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, unsigned AddressSpace, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, bool UseMaskForCond=false, bool UseMaskForGaps=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 858 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a09ac3c26a04fdf36e4bcc0e725fca41e">llvm::BasicTTIImplBase&lt; PPCTTIImpl &gt;::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#a6de26b938774385a0a4fb0d0b2a32d48">llvm::InstructionCost::getMax</a>, <a href="#a9ab346ad59b02578a3fc143c77397761">getMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#ab192bc3b4b8ccaa71341acf20e6ac335">llvm::BasicTTIImplBase&lt; PPCTTIImpl &gt;::getTypeLegalizationCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#ae01c5ced9fe2fe50f421ae121483ef04">llvm::InstructionCost::isValid</a> and <a href="#a40003c9aae5f4e1d9cf4b042db0b0c13">vectorCostAdjustmentFactor</a>.</p>

</div>
</div>

### getIntrinsicInstrCost {#a61d83c6f5d42c6579fc916fe97c02521}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost PPCTTIImpl::getIntrinsicInstrCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intrinsiccostattributes">IntrinsicCostAttributes</a> &amp; ICA, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 893 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a> and <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a05184f6230f850d3f972f6d904bd2ef5">llvm::BasicTTIImplBase&lt; PPCTTIImpl &gt;::getIntrinsicInstrCost</a>.</p>

</div>
</div>

### getMaxInterleaveFactor {#a8e416262d1392f777f79a7f003f92be6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned PPCTTIImpl::getMaxInterleaveFactor (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 516 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34a7b91cd4044a62473da3166dd0d2b2ddc">llvm::PPC::DIR_440</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34ab81d0aba13bef5a963bb14709390283e">llvm::PPC::DIR_A2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34a00d4f7d7f8d110db90749f417fceff3a">llvm::PPC::DIR_E500mc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34ac4e6bb06de05f2620850b3fc53a0433e">llvm::PPC::DIR_E5500</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34a1a5dee2be7c154497739282b30ab123c">llvm::PPC::DIR_PWR10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34af6a785f2b13ce7870e8e4e6b9653f32f">llvm::PPC::DIR_PWR11</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34a0c8a5dd168df904e8c29520a47502a61">llvm::PPC::DIR_PWR7</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34aa3de856d909c5b0166919bf6e4bd1a3d">llvm::PPC::DIR_PWR8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34a0a03bfd83c00f4d1edab975b7bfe7f36">llvm::PPC::DIR_PWR9</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34ac1fc2f6d654da4e5a6a601e19d423846">llvm::PPC::DIR_PWR_FUTURE</a>.</p>

</div>
</div>

### getMemoryOpCost {#a9ab346ad59b02578a3fc143c77397761}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost PPCTTIImpl::getMemoryOpCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Src, <a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> Alignment, unsigned AddressSpace, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/operandvalueinfo">TTI::OperandValueInfo</a> OpInfo={<a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#afa38851d75434d1476444ac93f94cb4ca9c0eecea29e9fa58e4dac7ee32b9b2ac">TTI::OK_AnyValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a733fb237f3037c95ed59de6055b176c5a2bc39e3785b29fe7bc4af768842a2072">TTI::OP_None</a>}, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 763 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#aec0b8db50138e2a68aca36959b6692a5">llvm::BasicTTIImplBase&lt; PPCTTIImpl &gt;::DL</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#a6de26b938774385a0a4fb0d0b2a32d48">llvm::InstructionCost::getMax</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a522a29dd7d0932170a6915e84657218b">llvm::BasicTTIImplBase&lt; PPCTTIImpl &gt;::getMemoryOpCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a2f1d58ac35de4475017aca6c5bda6d44">getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#ab192bc3b4b8ccaa71341acf20e6ac335">llvm::BasicTTIImplBase&lt; PPCTTIImpl &gt;::getTypeLegalizationCost</a>, <a href="#a513e1873d7e7760f5e0241cc47a9aaca">getVectorInstrCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#ae01c5ced9fe2fe50f421ae121483ef04">llvm::InstructionCost::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">llvm::TargetTransformInfo::TCK_RecipThroughput</a> and <a href="#a40003c9aae5f4e1d9cf4b042db0b0c13">vectorCostAdjustmentFactor</a>.</p>


<p>Referenced by <a href="#afffe3207f30907d3ca4800ba3d26c9f0">getInterleavedMemoryOpCost</a>.</p>

</div>
</div>

### getNumberOfRegisters {#ab3cd8f854314b1fac90c62cdf631f475}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned PPCTTIImpl::getNumberOfRegisters (unsigned ClassID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 446 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a749451435ba7f18d4f92452cb9d4dfadad393e4006e2974efe9611f88cc46fe45">FPRRC</a>, <a href="#a749451435ba7f18d4f92452cb9d4dfada7c7ac467127011c80d56f74ebfc2c10b">GPRRC</a>, <a href="#a749451435ba7f18d4f92452cb9d4dfada4da82063106b27dda4067dafd30cdff3">VRRC</a> and <a href="#a749451435ba7f18d4f92452cb9d4dfada680c571a8defb4ef3c30a4d2a8b4e4ae">VSXRC</a>.</p>

</div>
</div>

### getPrefetchDistance {#a9a78235a7e939764a03017aaaf4a85ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned PPCTTIImpl::getPrefetchDistance ()</td>
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



<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 512 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getRegisterBitWidth {#a08b9d86ee30f4a9280fda16fd5ecc77a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeSize PPCTTIImpl::getRegisterBitWidth (<a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a8bb3b1ccf19b8c85429b777dfa4a0166">TargetTransformInfo::RegisterKind</a> K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/typesize/#a003b4369b4130e669dc9139798e0193c">llvm::TypeSize::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/typesize/#a5fd620f2446d1a4cb0d55a12d182bb34">llvm::TypeSize::getScalable</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a8bb3b1ccf19b8c85429b777dfa4a0166a183020fbea95c99db23f6d3594f4c4af">llvm::TargetTransformInfo::RGK_FixedWidthVector</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a8bb3b1ccf19b8c85429b777dfa4a0166a331413d3887a08546d0973091f6a4993">llvm::TargetTransformInfo::RGK_ScalableVector</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a8bb3b1ccf19b8c85429b777dfa4a0166ad8f233645107107ed48d2e4a915152cc">llvm::TargetTransformInfo::RGK_Scalar</a>.</p>

</div>
</div>

### getRegisterClassForType {#a554d0473620971823cbfe3109899c5fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned PPCTTIImpl::getRegisterClassForType (bool Vector, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 457 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>References <a href="#a749451435ba7f18d4f92452cb9d4dfadad393e4006e2974efe9611f88cc46fe45">FPRRC</a>, <a href="#a749451435ba7f18d4f92452cb9d4dfada7c7ac467127011c80d56f74ebfc2c10b">GPRRC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39a57dea6f5039281b7fee517fc43bf3110">llvm::Vector</a>, <a href="#a749451435ba7f18d4f92452cb9d4dfada4da82063106b27dda4067dafd30cdff3">VRRC</a> and <a href="#a749451435ba7f18d4f92452cb9d4dfada680c571a8defb4ef3c30a4d2a8b4e4ae">VSXRC</a>.</p>

</div>
</div>

### getRegisterClassName {#a13a06481e8adc2b65dcfb2f8f90efd84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * PPCTTIImpl::getRegisterClassName (unsigned ClassID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 472 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>References <a href="#a749451435ba7f18d4f92452cb9d4dfadad393e4006e2974efe9611f88cc46fe45">FPRRC</a>, <a href="#a749451435ba7f18d4f92452cb9d4dfada7c7ac467127011c80d56f74ebfc2c10b">GPRRC</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a749451435ba7f18d4f92452cb9d4dfada4da82063106b27dda4067dafd30cdff3">VRRC</a> and <a href="#a749451435ba7f18d4f92452cb9d4dfada680c571a8defb4ef3c30a4d2a8b4e4ae">VSXRC</a>.</p>

</div>
</div>

### getShuffleCost {#a2933bd38a4062250af0ebb41af0caa10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost PPCTTIImpl::getShuffleCost (<a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af46433d0e36d3f80afc3a8c67b5c53ec">TTI::ShuffleKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Tp, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, int Index, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * SubTp, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Args={}, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CxtI=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 604 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#a6de26b938774385a0a4fb0d0b2a32d48">llvm::InstructionCost::getMax</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#ab192bc3b4b8ccaa71341acf20e6ac335">llvm::BasicTTIImplBase&lt; PPCTTIImpl &gt;::getTypeLegalizationCost</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#ae01c5ced9fe2fe50f421ae121483ef04">llvm::InstructionCost::isValid</a> and <a href="#a40003c9aae5f4e1d9cf4b042db0b0c13">vectorCostAdjustmentFactor</a>.</p>

</div>
</div>

### getVectorInstrCost {#a513e1873d7e7760f5e0241cc47a9aaca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost PPCTTIImpl::getVectorInstrCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, unsigned Index, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 673 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9329e79f62e9ab9b41cfbcafd314bcbd">llvm::ISD::EXTRACT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#a6de26b938774385a0a4fb0d0b2a32d48">llvm::InstructionCost::getMax</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7c742b32ebcd73d6dc851afac295b0f2">llvm::Type::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a27bfcb3dd99fa7a7ca8dc24eeac6e8e6">llvm::BasicTTIImplBase&lt; PPCTTIImpl &gt;::getVectorInstrCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad3bc7c2d379fbfdc2f8eaca038690ec9">llvm::ISD::INSERT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa0fd6bf3d33236279db7b707bba755f4">llvm::Type::isDoubleTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#ae01c5ced9fe2fe50f421ae121483ef04">llvm::InstructionCost::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a1bc022868b23918efa44df511f4d5b61">llvm::Type::isVectorTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp/#a5bc4ce5f29c2ad64b0ff451e5efb3309">VecMaskCost</a> and <a href="#a40003c9aae5f4e1d9cf4b042db0b0c13">vectorCostAdjustmentFactor</a>.</p>


<p>Referenced by <a href="#a9ab346ad59b02578a3fc143c77397761">getMemoryOpCost</a>.</p>

</div>
</div>

### getVectorInstrCost {#a6fe170d5f331fc7235f2a8561ca5c633}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost llvm::BasicTTIImplBase&lt; PPCTTIImpl &gt;::getVectorInstrCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, unsigned Index, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Scalar, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/user">User</a> *, int &gt; &gt; ScalarUserAndIdx)</td>
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

<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 1355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicttiimpl-h">BasicTTIImpl.h</a>.</p>

</div>
</div>

### getVectorInstrCost {#a45f97f77b0a63e7af5079590c2a55e3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost llvm::BasicTTIImplBase&lt; PPCTTIImpl &gt;::getVectorInstrCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, unsigned Index)</td>
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



<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 1363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicttiimpl-h">BasicTTIImpl.h</a>.</p>

</div>
</div>

### getVPMemoryOpCost {#ae2dcbf9f4bf17b489bfdebc4187d25d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost PPCTTIImpl::getVPMemoryOpCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Src, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, unsigned AddressSpace, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 1046 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34a0a03bfd83c00f4d1edab975b7bfe7f36">llvm::PPC::DIR_PWR9</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#aec0b8db50138e2a68aca36959b6692a5">llvm::BasicTTIImplBase&lt; PPCTTIImpl &gt;::DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a172b3291a66a7313017f3d68422da9cd">llvm::BasicTTIImplBase&lt; PPCTTIImpl &gt;::getMaskedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#a6de26b938774385a0a4fb0d0b2a32d48">llvm::InstructionCost::getMax</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#ab192bc3b4b8ccaa71341acf20e6ac335">llvm::BasicTTIImplBase&lt; PPCTTIImpl &gt;::getTypeLegalizationCost</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a5b06a0b2c63c886b6552a84f67604165">llvm::TargetTransformInfoImplBase::getVPMemoryOpCost</a>, <a href="#ad4522ba73eb89ae20c7ca46349303f3e">hasActiveVectorLength</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#ae01c5ced9fe2fe50f421ae121483ef04">llvm::InstructionCost::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">llvm::TargetTransformInfo::TCK_RecipThroughput</a>, <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a> and <a href="#a40003c9aae5f4e1d9cf4b042db0b0c13">vectorCostAdjustmentFactor</a>.</p>

</div>
</div>

### hasActiveVectorLength {#ad4522ba73eb89ae20c7ca46349303f3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTTIImpl::hasActiveVectorLength (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DataType, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 1018 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a13e877ef779ba7a0688081079f4f9b03">llvm::Type::getIntegerBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7c742b32ebcd73d6dc851afac295b0f2">llvm::Type::getScalarType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa0fd6bf3d33236279db7b707bba755f4">llvm::Type::isDoubleTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3ffc75c3a4cb82ba307a3334483eb4ac">llvm::Type::isFloatTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>.</p>


<p>Referenced by <a href="#ae2dcbf9f4bf17b489bfdebc4187d25d4">getVPMemoryOpCost</a>.</p>

</div>
</div>

### P9PipelineFlushEstimate {#a6b47f55029778253ccb3757c11867129}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InstructionCost::CostType llvm::PPCTTIImpl::P9PipelineFlushEstimate = 80</td>
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



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>.</p>

</div>
</div>

### PPCRegisterClass {#a749451435ba7f18d4f92452cb9d4dfad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::PPCTTIImpl::PPCRegisterClass </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GPRRC<a id="a749451435ba7f18d4f92452cb9d4dfada7c7ac467127011c80d56f74ebfc2c10b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FPRRC<a id="a749451435ba7f18d4f92452cb9d4dfadad393e4006e2974efe9611f88cc46fe45"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VRRC<a id="a749451435ba7f18d4f92452cb9d4dfada4da82063106b27dda4067dafd30cdff3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSXRC<a id="a749451435ba7f18d4f92452cb9d4dfada680c571a8defb4ef3c30a4d2a8b4e4ae"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>.</p>

</div>
</div>

### supportsTailCallFor {#a507c08cbe76f2b19fc1a62d7e02343ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTTIImpl::supportsTailCallFor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 1100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>

</div>
</div>

### useColdCCForColdCall {#a3ff1ab275738e5fd76b99302ea1914b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTTIImpl::useColdCCForColdCall (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp/#aef7cd120fa19fea4cf447e132f969f1b">EnablePPCColdCC</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### vectorCostAdjustmentFactor {#a40003c9aae5f4e1d9cf4b042db0b0c13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost PPCTTIImpl::vectorCostAdjustmentFactor (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty1, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 551 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#a57207993e2fe6ec98912e8072e4600bc">llvm::InstructionCost::getInvalid</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#ab192bc3b4b8ccaa71341acf20e6ac335">llvm::BasicTTIImplBase&lt; PPCTTIImpl &gt;::getTypeLegalizationCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp/#ad2093e0d56366af0bbe8387b51f4a4d5">isMMAType</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a1bc022868b23918efa44df511f4d5b61">llvm::Type::isVectorTy</a>.</p>


<p>Referenced by <a href="#a35de5712aacf900ec00d1817008eeed1">getArithmeticInstrCost</a>, <a href="#aa96045bfcd00b9908c624a5626b2c05c">getCastInstrCost</a>, <a href="#a228a182df5d1f649d5b9f6dc8be75011">getCmpSelInstrCost</a>, <a href="#afffe3207f30907d3ca4800ba3d26c9f0">getInterleavedMemoryOpCost</a>, <a href="#a9ab346ad59b02578a3fc143c77397761">getMemoryOpCost</a>, <a href="#a2933bd38a4062250af0ebb41af0caa10">getShuffleCost</a>, <a href="#a513e1873d7e7760f5e0241cc47a9aaca">getVectorInstrCost</a> and <a href="#ae2dcbf9f4bf17b489bfdebc4187d25d4">getVPMemoryOpCost</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Scalar TTI Implementations

### canSaveCmp {#adf88172fa9f5c04416b60fa78f99e756}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTTIImpl::canSaveCmp (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/branchinst">BranchInst</a> ** BI, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * LibInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 917 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/hardwareloopinfo/#a8c312c949b23870e888497137dd3b1c9">llvm::HardwareLoopInfo::canAnalyze</a>, <a href="#adf88172fa9f5c04416b60fa78f99e756">canSaveCmp</a>, <a href="/web-llvm/docs/api/structs/llvm/hardwareloopinfo/#a40f2c89f3eb246a1a8f7156237abad43">llvm::HardwareLoopInfo::ExitBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/hardwareloopinfo/#aef4460eccacc720018aa15086026c11d">llvm::HardwareLoopInfo::isHardwareLoopCandidate</a> and <a href="#ae46906a076a2ec35cf6a38e433b48219">isHardwareLoopProfitable</a>.</p>


<p>Referenced by <a href="#adf88172fa9f5c04416b60fa78f99e756">canSaveCmp</a>.</p>

</div>
</div>

### getInstructionCost {#ada4520fadc98f59acef021bda2d6e608}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost PPCTTIImpl::getInstructionCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> * U, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Operands, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplcrtpbase/#a95442a0e0980e874df3bf77d6c8dee44">llvm::TargetTransformInfoImplCRTPBase&lt; T &gt;::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#ab192bc3b4b8ccaa71341acf20e6ac335">llvm::BasicTTIImplBase&lt; PPCTTIImpl &gt;::getTypeLegalizationCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>

</div>
</div>

### getIntImmCost {#a0371e739dcb4a90dd9b0ba18bc053de0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost PPCTTIImpl::getIntImmCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Imm, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp/#aa5e2d2da670aa372d573b9fb63e34d13">DisablePPCConstHoist</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a84ea64a28fddeedc474285c33db7d760">llvm::TargetTransformInfoImplBase::getIntImmCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#ac44f6b9fdbb5f9cc199f8329cb0b272cae46c9eecc49bd2dc253c607e78a0fb86">llvm::TargetTransformInfo::TCC_Basic</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#ac44f6b9fdbb5f9cc199f8329cb0b272ca89f768b1267e3083b4eb05b4ab77e717">llvm::TargetTransformInfo::TCC_Free</a>.</p>


<p>Referenced by <a href="#aa4dec9e04986a6b05f1b45b1a5f1e8d9">getIntImmCostInst</a> and <a href="#aa00f36dbd11c8c610cb8830398f0325b">getIntImmCostIntrin</a>.</p>

</div>
</div>

### getIntImmCostInst {#aa4dec9e04986a6b05f1b45b1a5f1e8d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost PPCTTIImpl::getIntImmCostInst (unsigned Opcode, unsigned Idx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Imm, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp/#aa5e2d2da670aa372d573b9fb63e34d13">DisablePPCConstHoist</a>, <a href="#a0371e739dcb4a90dd9b0ba18bc053de0">getIntImmCost</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a24b6da26e439d299a11a81f2d5305362">llvm::TargetTransformInfoImplBase::getIntImmCostInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4e43e0513a033e8590ef9efc406fa3dd">llvm::isShiftedMask_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a582e08755c7a8d1b0bf6c5dcb765aaa8">llvm::isShiftedMask_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#ac44f6b9fdbb5f9cc199f8329cb0b272cae46c9eecc49bd2dc253c607e78a0fb86">llvm::TargetTransformInfo::TCC_Basic</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#ac44f6b9fdbb5f9cc199f8329cb0b272ca89f768b1267e3083b4eb05b4ab77e717">llvm::TargetTransformInfo::TCC_Free</a>.</p>

</div>
</div>

### getIntImmCostIntrin {#aa00f36dbd11c8c610cb8830398f0325b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost PPCTTIImpl::getIntImmCostIntrin (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> IID, unsigned Idx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Imm, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp/#aa5e2d2da670aa372d573b9fb63e34d13">DisablePPCConstHoist</a>, <a href="#a0371e739dcb4a90dd9b0ba18bc053de0">getIntImmCost</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a8038518d6ba1c83ac26aa0afcbe4daca">llvm::TargetTransformInfoImplBase::getIntImmCostIntrin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#ac44f6b9fdbb5f9cc199f8329cb0b272ca89f768b1267e3083b4eb05b4ab77e717">llvm::TargetTransformInfo::TCC_Free</a>.</p>

</div>
</div>

### getPeelingPreferences {#aacabbc276d0d5461b5d81eaaea461afd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCTTIImpl::getPeelingPreferences (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/peelingpreferences">TTI::PeelingPreferences</a> &amp; PP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a9d093749d001a714592c88df0e81b3fe">llvm::BasicTTIImplBase&lt; PPCTTIImpl &gt;::getPeelingPreferences</a>.</p>

</div>
</div>

### getPopcntSupport {#a987c4241bbd15c993aef6c58ed7dbacf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetTransformInfo::PopcntSupportKind PPCTTIImpl::getPopcntSupport (unsigned TyWidth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a2eeb56ba19044c9c01c2c0606ada7083ab0fb8c03d2414c080c21b73aeae5a13c">llvm::PPCSubtarget::POPCNTD_Slow</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a2eeb56ba19044c9c01c2c0606ada7083adf6cd18e5546a8897639fa528f81f375">llvm::PPCSubtarget::POPCNTD_Unavailable</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#aa4c17e89b1ef061ed69f42b7cee93dbeac71465fd61f1ba8aa2c7c397722b5e05">llvm::TargetTransformInfo::PSK_FastHardware</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#aa4c17e89b1ef061ed69f42b7cee93dbea01deb9d0bc6399399b0d8377bd09201d">llvm::TargetTransformInfo::PSK_SlowHardware</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#aa4c17e89b1ef061ed69f42b7cee93dbea0ce99a3a4fe2b7f2771a7b288a99ed2c">llvm::TargetTransformInfo::PSK_Software</a>.</p>

</div>
</div>

### getTgtMemIntrinsic {#a515494cf182cfa8aec53bd6fef47a11e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTTIImpl::getTgtMemIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * Inst, <a href="/web-llvm/docs/api/structs/llvm/memintrinsicinfo">MemIntrinsicInfo</a> &amp; Info)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 965 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst/#a7ff64b3625b6f9020556ed05a5f72af4">llvm::IntrinsicInst::getIntrinsicID</a>.</p>

</div>
</div>

### getUnrollingPreferences {#a6801a1b19bf8856a09f270d85fe25e9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCTTIImpl::getUnrollingPreferences (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences">TTI::UnrollingPreferences</a> &amp; UP, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> * ORE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#afaa4eb31d0f39aa8c7ac8d081a39fec5">llvm::TargetTransformInfo::UnrollingPreferences::AllowExpensiveTripCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34ab81d0aba13bef5a963bb14709390283e">llvm::PPC::DIR_A2</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a1017f6873c8e5d75aa472aa3f06b48e3">llvm::BasicTTIImplBase&lt; PPCTTIImpl &gt;::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#af01349dac5ea8d7fc1d5bedcc82a17b8">llvm::TargetTransformInfo::UnrollingPreferences::Partial</a> and <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#ae31307b4efc5ce5311752041e7ff7cdc">llvm::TargetTransformInfo::UnrollingPreferences::Runtime</a>.</p>

</div>
</div>

### isHardwareLoopProfitable {#ae46906a076a2ec35cf6a38e433b48219}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTTIImpl::isHardwareLoopProfitable (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp; AC, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * LibInfo, <a href="/web-llvm/docs/api/structs/llvm/hardwareloopinfo">HardwareLoopInfo</a> &amp; HWLoopInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/groups/arcopt/#ga9c9cf6ad55eb23d77d083a184e416c09">Call</a>, <a href="/web-llvm/docs/api/structs/llvm/codemetrics/#a7e174506b52ad46ea1f746a7f727d999">llvm::CodeMetrics::collectEphemeralValues</a>, <a href="/web-llvm/docs/api/structs/llvm/hardwareloopinfo/#ac3a4a577c64538aa965b6ce5d81de298">llvm::HardwareLoopInfo::CountType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac19cbbc4935a23e1d44f65e1eaba6b1d">llvm::extractBranchWeights</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel/#a2fdb857df4be03c47fa40a69110b84a8">llvm::TargetSchedModel::getIssueWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#abec0c616087c002528fcf80c6583eadd">llvm::ScalarEvolution::getSmallConstantTripCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel/#ab357b39c47df52a19882a831feda1b6f">llvm::TargetSchedModel::init</a>, <a href="/web-llvm/docs/api/structs/llvm/hardwareloopinfo/#a662d22fab06a18d9d9dc7c9bf1676bf9">llvm::HardwareLoopInfo::LoopDecrement</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp/#a6f3004139ef53bc2cf206b8864976928">Metrics</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp/#ab5a5c6c940ffaebe924b0e5d8ff55f71">SmallCTRLoopThreshold</a>.</p>


<p>Referenced by <a href="#adf88172fa9f5c04416b60fa78f99e756">canSaveCmp</a>.</p>

</div>
</div>

### isLSRCostLess {#a2e2c6081215dcc909699433f341692f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTTIImpl::isLSRCostLess (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/lsrcost">TargetTransformInfo::LSRCost</a> &amp; C1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/lsrcost">TargetTransformInfo::LSRCost</a> &amp; C2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 940 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/lsrcost/#a95eb887e84c6d2b102a6b0114276f8da">llvm::TargetTransformInfo::LSRCost::AddRecCost</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/lsrcost/#a66e939ebf350e35ede6f1af76f243b65">llvm::TargetTransformInfo::LSRCost::ImmCost</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/lsrcost/#a5b3b10333e5dcfbc64652b383025b77c">llvm::TargetTransformInfo::LSRCost::Insns</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a24dfd2b966967135b0dba8e680d313f0">llvm::TargetTransformInfoImplBase::isLSRCostLess</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp/#afd4dac08a721852e8c94e4ad417c3ec6">LsrNoInsnsCost</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/lsrcost/#ad56d6a45ed26384d00b88e431e6e9181">llvm::TargetTransformInfo::LSRCost::NumBaseAdds</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/lsrcost/#a1cc611760ab739d87bf545a55dcea72b">llvm::TargetTransformInfo::LSRCost::NumIVMuls</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/lsrcost/#acc4efcc7eb81341eb7b94387d7519fd7">llvm::TargetTransformInfo::LSRCost::NumRegs</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/lsrcost/#a56c87ad7c1654d83b3f4d7984fc66d75">llvm::TargetTransformInfo::LSRCost::ScaleCost</a> and <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/lsrcost/#afa00c85b17f12a25f99f238eaf86ece7">llvm::TargetTransformInfo::LSRCost::SetupCost</a>.</p>

</div>
</div>

### isNumRegsMajorCostOfLSR {#a409659881a20291018136b459356ff92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTTIImpl::isNumRegsMajorCostOfLSR ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 953 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>

</div>
</div>

### shouldBuildRelLookupTables {#ad4c88dd3817b1258525743dea78b07e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCTTIImpl::shouldBuildRelLookupTables ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a>, definition at line 957 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a49ae9dcb1b15c8bd79c384ddf3956db8">llvm::BasicTTIImplBase&lt; PPCTTIImpl &gt;::shouldBuildRelLookupTables</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicttiimpl-h">BasicTTIImpl.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-cpp">PPCTargetTransformInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargettransforminfo-h">PPCTargetTransformInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
