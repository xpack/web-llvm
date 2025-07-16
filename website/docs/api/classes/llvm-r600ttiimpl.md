---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/r600ttiimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `R600TTIImpl` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::R600TTIImpl { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-h">Target/AMDGPU/R600TargetTransformInfo.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0818a900f80140a6270f56b061742fc8">BaseT</a> = <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase">BasicTTIImplBase</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/r600ttiimpl">R600TTIImpl</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a833df3756b468861986f2cde857fb1bf">TTI</a> = <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab93330bd3223afb926c2d8f0a0fd6b76">R600TTIImpl</a> (const AMDGPUTargetMachine *TM, const Function &amp;F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/r600subtarget">R600Subtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7227703bc4f261f4520652521a14616d">getST</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering">AMDGPUTargetLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a897f07324ee20d4f60c0ba81d993eff1">getTLI</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e339c3466d8f873a4758618a176f35d">getUnrollingPreferences</a> (Loop *L, ScalarEvolution &amp;SE, TTI::UnrollingPreferences &amp;UP, OptimizationRemarkEmitter *ORE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24166f42244179ae0551eaf4c160c86f">getPeelingPreferences</a> (Loop *L, ScalarEvolution &amp;SE, TTI::PeelingPreferences &amp;PP)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf3f5c15694256f2cd6cba8cc6c3a22e">getHardwareNumberOfRegisters</a> (bool Vec) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9c8f663a50b6df34d7ad51988e3ec04">getNumberOfRegisters</a> (bool Vec) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebb07a0c2442cf05312ce6844e21fbd2">getRegisterBitWidth</a> (TargetTransformInfo::RegisterKind Vector) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af22fb016fc2e6502d2d6c37a298df98e">getMinVectorRegisterBitWidth</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6b38f927752e74714725aeaa75ad133">getLoadStoreVecRegBitWidth</a> (unsigned AddrSpace) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a123e4fe3b614b2fe9869dae4017fb332">isLegalToVectorizeMemChain</a> (unsigned ChainSizeInBytes, Align Alignment, unsigned AddrSpace) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af437596f08ba00c667b174ee5e41920e">isLegalToVectorizeLoadChain</a> (unsigned ChainSizeInBytes, Align Alignment, unsigned AddrSpace) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a1478ef1f6170cd0bc5ae58c89bc1f6">isLegalToVectorizeStoreChain</a> (unsigned ChainSizeInBytes, Align Alignment, unsigned AddrSpace) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bfce9237a4882c6862de27708677f5c">getMaxInterleaveFactor</a> (ElementCount VF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30fec1c5a8125be962816feeefc92009">getCFInstrCost</a> (unsigned Opcode, TTI::TargetCostKind CostKind, const Instruction *I=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af55f0e0db010c77e07d4b29c9fe27d61">getVectorInstrCost</a> (unsigned Opcode, Type *ValTy, TTI::TargetCostKind CostKind, unsigned Index, Value *Op0, Value *Op1)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81afd44d4e43317c632ab251ebd86388">getVectorInstrCost</a> (unsigned Opcode, Type *Val, TTI::TargetCostKind CostKind, unsigned Index, Value *Scalar, ArrayRef&lt; std::tuple&lt; Value *, User *, int &gt; &gt; ScalarUserAndIdx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fc4bd79eb699484c0bb1e05644dfd8a">getVectorInstrCost</a> (const Instruction &amp;I, Type *Val, TTI::TargetCostKind CostKind, unsigned Index)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3284ad80346e18c6d2f963bf49a8b271">BaseT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/r600subtarget">R600Subtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8843e028040275f9fea05dd83e5ba21e">ST</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering">AMDGPUTargetLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaa28cd38c0d765049572f190cc269ab">TLI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a063c9805ecdd13cced0edf21a0d45150">CommonTTI</a></td>
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


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-h">R600TargetTransformInfo.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### BaseT {#a0818a900f80140a6270f56b061742fc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::R600TTIImpl::BaseT =  BasicTTIImplBase&lt;R600TTIImpl&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-h">R600TargetTransformInfo.h</a>.</p>

</div>
</div>

### TTI {#a833df3756b468861986f2cde857fb1bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::R600TTIImpl::TTI =  TargetTransformInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-h">R600TargetTransformInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### R600TTIImpl() {#ab93330bd3223afb926c2d8f0a0fd6b76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">R600TTIImpl::R600TTIImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine">AMDGPUTargetMachine</a> * TM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-h">R600TargetTransformInfo.h</a>, definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-cpp">R600TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a01aadd7eea7124cd9f5cd7cea37d8dab">llvm::TargetTransformInfoImplBase::getDataLayout</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getCFInstrCost() {#a30fec1c5a8125be962816feeefc92009}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost R600TTIImpl::getCFInstrCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-h">R600TargetTransformInfo.h</a>, definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-cpp">R600TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#aa459db33f4b14d518af003bf95c3417e">llvm::BasicTTIImplBase&lt; R600TTIImpl &gt;::getCFInstrCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba737cfc93e5a2ff961677d57186167e7c">llvm::TargetTransformInfo::TCK_CodeSize</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba7f80055e1969cb850739546467460ad8">llvm::TargetTransformInfo::TCK_SizeAndLatency</a>.</p>

</div>
</div>

### getHardwareNumberOfRegisters() {#acf3f5c15694256f2cd6cba8cc6c3a22e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned R600TTIImpl::getHardwareNumberOfRegisters (bool Vec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-h">R600TargetTransformInfo.h</a>, definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-cpp">R600TargetTransformInfo.cpp</a>.</p>


<p>Referenced by <a href="#af9c8f663a50b6df34d7ad51988e3ec04">getNumberOfRegisters</a>.</p>

</div>
</div>

### getLoadStoreVecRegBitWidth() {#aa6b38f927752e74714725aeaa75ad133}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned R600TTIImpl::getLoadStoreVecRegBitWidth (unsigned AddrSpace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-h">R600TargetTransformInfo.h</a>, definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-cpp">R600TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aa6d3112da64eecbdbb50aacb5f8251e8">llvm::AMDGPUAS::CONSTANT_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a68e5b0cf4fb0f4c890718e035b0bda43">llvm::AMDGPUAS::CONSTANT_BUFFER_0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a1ae19b57472eec1e951506094d92a411">llvm::AMDGPUAS::CONSTANT_BUFFER_15</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1abf4559ef958a13c33f6ec7ed13fd44e5">llvm::AMDGPUAS::GLOBAL_ADDRESS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a77b1c964e2ff99057bf5e75140457abe">llvm::AMDGPUAS::LOCAL_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a4da965819228912d2be72bf34ace8ac7">llvm::AMDGPUAS::PARAM_D_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aa03e3cb93fc64ad53958ab0a2ff22f3a">llvm::AMDGPUAS::PARAM_I_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aec164f45437d8827346f2d8ec645479a">llvm::AMDGPUAS::PRIVATE_ADDRESS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a5b71ba6fa435ec288aba849e113721a7">llvm::AMDGPUAS::REGION_ADDRESS</a>.</p>

</div>
</div>

### getMaxInterleaveFactor() {#a8bfce9237a4882c6862de27708677f5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned R600TTIImpl::getMaxInterleaveFactor (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-h">R600TargetTransformInfo.h</a>, definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-cpp">R600TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a991f269cde2e7fbcb254ef371efc8d1a">llvm::ElementCount::isScalar</a>.</p>

</div>
</div>

### getMinVectorRegisterBitWidth() {#af22fb016fc2e6502d2d6c37a298df98e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned R600TTIImpl::getMinVectorRegisterBitWidth ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-h">R600TargetTransformInfo.h</a>, definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-cpp">R600TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getNumberOfRegisters() {#af9c8f663a50b6df34d7ad51988e3ec04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned R600TTIImpl::getNumberOfRegisters (bool Vec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-h">R600TargetTransformInfo.h</a>, definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-cpp">R600TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="#acf3f5c15694256f2cd6cba8cc6c3a22e">getHardwareNumberOfRegisters</a>.</p>

</div>
</div>

### getPeelingPreferences() {#a24166f42244179ae0551eaf4c160c86f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void R600TTIImpl::getPeelingPreferences (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/peelingpreferences">TTI::PeelingPreferences</a> &amp; PP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-h">R600TargetTransformInfo.h</a>, definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-cpp">R600TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getRegisterBitWidth() {#aebb07a0c2442cf05312ce6844e21fbd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeSize R600TTIImpl::getRegisterBitWidth (<a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a8bb3b1ccf19b8c85429b777dfa4a0166">TargetTransformInfo::RegisterKind</a> Vector)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-h">R600TargetTransformInfo.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-cpp">R600TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/typesize/#a003b4369b4130e669dc9139798e0193c">llvm::TypeSize::getFixed</a>.</p>

</div>
</div>

### getST() {#a7227703bc4f261f4520652521a14616d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const R600Subtarget * llvm::R600TTIImpl::getST ()</td>
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



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-h">R600TargetTransformInfo.h</a>.</p>

</div>
</div>

### getTLI() {#a897f07324ee20d4f60c0ba81d993eff1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AMDGPUTargetLowering * llvm::R600TTIImpl::getTLI ()</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-h">R600TargetTransformInfo.h</a>.</p>

</div>
</div>

### getUnrollingPreferences() {#a8e339c3466d8f873a4758618a176f35d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void R600TTIImpl::getUnrollingPreferences (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences">TTI::UnrollingPreferences</a> &amp; UP, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> * ORE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-h">R600TargetTransformInfo.h</a>, definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-cpp">R600TargetTransformInfo.cpp</a>.</p>

</div>
</div>

### getVectorInstrCost() {#af55f0e0db010c77e07d4b29c9fe27d61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost R600TTIImpl::getVectorInstrCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ValTy, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, unsigned Index, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-h">R600TargetTransformInfo.h</a>, definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-cpp">R600TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#aec0b8db50138e2a68aca36959b6692a5">llvm::BasicTTIImplBase&lt; R600TTIImpl &gt;::DL</a> and <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a27bfcb3dd99fa7a7ca8dc24eeac6e8e6">llvm::BasicTTIImplBase&lt; R600TTIImpl &gt;::getVectorInstrCost</a>.</p>

</div>
</div>

### getVectorInstrCost() {#a81afd44d4e43317c632ab251ebd86388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost llvm::BasicTTIImplBase&lt; R600TTIImpl &gt;::getVectorInstrCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, unsigned Index, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Scalar, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/user">User</a> *, int &gt; &gt; ScalarUserAndIdx)</td>
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

<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-h">R600TargetTransformInfo.h</a>, definition at line 1355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicttiimpl-h">BasicTTIImpl.h</a>.</p>

</div>
</div>

### getVectorInstrCost() {#a5fc4bd79eb699484c0bb1e05644dfd8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost llvm::BasicTTIImplBase&lt; R600TTIImpl &gt;::getVectorInstrCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, unsigned Index)</td>
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



<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-h">R600TargetTransformInfo.h</a>, definition at line 1363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicttiimpl-h">BasicTTIImpl.h</a>.</p>

</div>
</div>

### isLegalToVectorizeLoadChain() {#af437596f08ba00c667b174ee5e41920e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600TTIImpl::isLegalToVectorizeLoadChain (unsigned ChainSizeInBytes, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, unsigned AddrSpace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-h">R600TargetTransformInfo.h</a>, definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-cpp">R600TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="#a123e4fe3b614b2fe9869dae4017fb332">isLegalToVectorizeMemChain</a>.</p>

</div>
</div>

### isLegalToVectorizeMemChain() {#a123e4fe3b614b2fe9869dae4017fb332}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600TTIImpl::isLegalToVectorizeMemChain (unsigned ChainSizeInBytes, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, unsigned AddrSpace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-h">R600TargetTransformInfo.h</a>, definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-cpp">R600TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aec164f45437d8827346f2d8ec645479a">llvm::AMDGPUAS::PRIVATE_ADDRESS</a>.</p>


<p>Referenced by <a href="#af437596f08ba00c667b174ee5e41920e">isLegalToVectorizeLoadChain</a> and <a href="#a4a1478ef1f6170cd0bc5ae58c89bc1f6">isLegalToVectorizeStoreChain</a>.</p>

</div>
</div>

### isLegalToVectorizeStoreChain() {#a4a1478ef1f6170cd0bc5ae58c89bc1f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600TTIImpl::isLegalToVectorizeStoreChain (unsigned ChainSizeInBytes, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, unsigned AddrSpace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-h">R600TargetTransformInfo.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-cpp">R600TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="#a123e4fe3b614b2fe9869dae4017fb332">isLegalToVectorizeMemChain</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BaseT {#a3284ad80346e18c6d2f963bf49a8b271}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::R600TTIImpl::BaseT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-h">R600TargetTransformInfo.h</a>.</p>

</div>
</div>

### CommonTTI {#a063c9805ecdd13cced0edf21a0d45150}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPUTTIImpl llvm::R600TTIImpl::CommonTTI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-h">R600TargetTransformInfo.h</a>.</p>

</div>
</div>

### ST {#a8843e028040275f9fea05dd83e5ba21e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const R600Subtarget* llvm::R600TTIImpl::ST</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-h">R600TargetTransformInfo.h</a>.</p>

</div>
</div>

### TLI {#aaaa28cd38c0d765049572f190cc269ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AMDGPUTargetLowering* llvm::R600TTIImpl::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-h">R600TargetTransformInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicttiimpl-h">BasicTTIImpl.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-cpp">R600TargetTransformInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600targettransforminfo-h">R600TargetTransformInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
