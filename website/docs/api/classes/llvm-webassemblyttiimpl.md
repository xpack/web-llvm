---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/webassemblyttiimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `WebAssemblyTTIImpl` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::WebAssemblyTTIImpl { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-h">Target/WebAssembly/WebAssemblyTargetTransformInfo.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase">BasicTTIImplBase</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/webassemblyttiimpl">WebAssemblyTTIImpl</a> &gt; <a href="#ac2002df93ca62220427ee77c10eb5645">BaseT</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> <a href="#a8b1912d9db36f0dac9ef6ffed9dce1f2">TTI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ece408ed6d54e6f522d5c6561a0211b">WebAssemblyTTIImpl</a> (const WebAssemblyTargetMachine *TM, const Function &amp;F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/webassemblysubtarget">WebAssemblySubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad81c9721ae1edee2e265b5b1518b0ba7">getST</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetlowering">WebAssemblyTargetLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f5fcb0b7ac2fbd0b65d76a47f90ad62">getTLI</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13ee3253daa82f7cda570bc7d10f6bc9">BaseT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/webassemblysubtarget">WebAssemblySubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27142477deb3eb4a452eb5abd8184240">ST</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetlowering">WebAssemblyTargetLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b9ece0d9231665e242e2f23d63692d6">TLI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#aa4c17e89b1ef061ed69f42b7cee93dbe">TTI::PopcntSupportKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac85247bd3aa93084215e5f8c36b7138b">getPopcntSupport</a> (unsigned TyWidth) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaa381079caefe69853af81f25e67928">getUnrollingPreferences</a> (Loop *L, ScalarEvolution &amp;SE, TTI::UnrollingPreferences &amp;UP, OptimizationRemarkEmitter *ORE) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae289888b64499c3bf4d5bd28ae19b2bc">getNumberOfRegisters</a> (unsigned ClassID) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a773c8dd48e0f26dbfd7302f88128559d">getRegisterBitWidth</a> (TargetTransformInfo::RegisterKind K) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad15604b9ba8788ef8bc91857c10474e9">getArithmeticInstrCost</a> (unsigned Opcode, Type *Ty, TTI::TargetCostKind CostKind, TTI::OperandValueInfo Op1Info={TTI::OK_AnyValue, TTI::OP_None}, TTI::OperandValueInfo Op2Info={TTI::OK_AnyValue, TTI::OP_None}, ArrayRef&lt; const Value * &gt; Args={}, const Instruction *CxtI=nullptr)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82b1e42b148ebdfbe1e856a1aacaf832">getVectorInstrCost</a> (unsigned Opcode, Type *Val, TTI::TargetCostKind CostKind, unsigned Index, Value *Op0, Value *Op1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a0692c75c1b45226b6afb90ad609eb86a">TTI::ReductionShuffle</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a181f6d38c57a84f999326ad805e8191f">getPreferredExpandedReductionShuffle</a> (const IntrinsicInst *II) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a760cd40e379c162238f82514245191b8">supportsTailCalls</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ac2e2e282105d3b50e85c76b9f948e7">isProfitableToSinkOperands</a> (Instruction *I, SmallVectorImpl&lt; Use * &gt; &amp;Ops) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48521a9ff1d2ebb46d8765c321fa56df">getVectorInstrCost</a> (unsigned Opcode, Type *Val, TTI::TargetCostKind CostKind, unsigned Index, Value *Scalar, ArrayRef&lt; std::tuple&lt; Value *, User *, int &gt; &gt; ScalarUserAndIdx)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb061fbf15492f20bf20f1c9f67a61ae">getVectorInstrCost</a> (const Instruction &amp;I, Type *Val, TTI::TargetCostKind CostKind, unsigned Index)</td>
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


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-h">WebAssemblyTargetTransformInfo.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### BaseT {#ac2002df93ca62220427ee77c10eb5645}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef BasicTTIImplBase&lt;WebAssemblyTTIImpl&gt; llvm::WebAssemblyTTIImpl::BaseT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-h">WebAssemblyTargetTransformInfo.h</a>.</p>

</div>
</div>

### TTI {#a8b1912d9db36f0dac9ef6ffed9dce1f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef TargetTransformInfo llvm::WebAssemblyTTIImpl::TTI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-h">WebAssemblyTargetTransformInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### WebAssemblyTTIImpl() {#a3ece408ed6d54e6f522d5c6561a0211b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::WebAssemblyTTIImpl::WebAssemblyTTIImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetmachine">WebAssemblyTargetMachine</a> * TM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-h">WebAssemblyTargetTransformInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a01aadd7eea7124cd9f5cd7cea37d8dab">llvm::TargetTransformInfoImplBase::getDataLayout</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getST() {#ad81c9721ae1edee2e265b5b1518b0ba7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const WebAssemblySubtarget * llvm::WebAssemblyTTIImpl::getST ()</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-h">WebAssemblyTargetTransformInfo.h</a>.</p>

</div>
</div>

### getTLI() {#a7f5fcb0b7ac2fbd0b65d76a47f90ad62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const WebAssemblyTargetLowering * llvm::WebAssemblyTTIImpl::getTLI ()</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-h">WebAssemblyTargetTransformInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BaseT {#a13ee3253daa82f7cda570bc7d10f6bc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::WebAssemblyTTIImpl::BaseT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-h">WebAssemblyTargetTransformInfo.h</a>.</p>

</div>
</div>

### ST {#a27142477deb3eb4a452eb5abd8184240}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const WebAssemblySubtarget* llvm::WebAssemblyTTIImpl::ST</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-h">WebAssemblyTargetTransformInfo.h</a>.</p>

</div>
</div>

### TLI {#a6b9ece0d9231665e242e2f23d63692d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const WebAssemblyTargetLowering* llvm::WebAssemblyTTIImpl::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-h">WebAssemblyTargetTransformInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Scalar TTI Implementations

### getPopcntSupport {#ac85247bd3aa93084215e5f8c36b7138b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetTransformInfo::PopcntSupportKind WebAssemblyTTIImpl::getPopcntSupport (unsigned TyWidth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-h">WebAssemblyTargetTransformInfo.h</a>, definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-cpp">WebAssemblyTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#aa4c17e89b1ef061ed69f42b7cee93dbeac71465fd61f1ba8aa2c7c397722b5e05">llvm::TargetTransformInfo::PSK_FastHardware</a>.</p>

</div>
</div>

### getUnrollingPreferences {#acaa381079caefe69853af81f25e67928}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WebAssemblyTTIImpl::getUnrollingPreferences (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences">TTI::UnrollingPreferences</a> &amp; UP, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> * ORE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-h">WebAssemblyTargetTransformInfo.h</a>, definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-cpp">WebAssemblyTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#acc2a7ecc1c0355035c91448ed850390f">llvm::TargetTransformInfo::UnrollingPreferences::BEInsns</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp/#aa04dbee2593fa5fbeb0552fcb8a00ee4">getCalledFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#abe34766b63068ff9df2cabd924c83cbc">llvm::TargetTransformInfoImplBase::isLoweredToCall</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#af9a7105299bd43b8b61c803f26e4a31b">llvm::TargetTransformInfo::UnrollingPreferences::OptSizeThreshold</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#af01349dac5ea8d7fc1d5bedcc82a17b8">llvm::TargetTransformInfo::UnrollingPreferences::Partial</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#a54b17420c467d2bb9edd2f79e54d2b6f">llvm::TargetTransformInfo::UnrollingPreferences::PartialOptSizeThreshold</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#ae28e05c1aac288aa7e4a49d858b35c46">llvm::TargetTransformInfo::UnrollingPreferences::PartialThreshold</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#ae31307b4efc5ce5311752041e7ff7cdc">llvm::TargetTransformInfo::UnrollingPreferences::Runtime</a> and <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/unrollingpreferences/#a20a872a70cd97f4915f64fb9470c32d0">llvm::TargetTransformInfo::UnrollingPreferences::UpperBound</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Vector TTI Implementations

### getArithmeticInstrCost {#ad15604b9ba8788ef8bc91857c10474e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost WebAssemblyTTIImpl::getArithmeticInstrCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/operandvalueinfo">TTI::OperandValueInfo</a> Op1Info={<a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#afa38851d75434d1476444ac93f94cb4ca9c0eecea29e9fa58e4dac7ee32b9b2ac">TTI::OK_AnyValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a733fb237f3037c95ed59de6055b176c5a2bc39e3785b29fe7bc4af768842a2072">TTI::OP_None</a>}, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/operandvalueinfo">TTI::OperandValueInfo</a> Op2Info={<a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#afa38851d75434d1476444ac93f94cb4ca9c0eecea29e9fa58e4dac7ee32b9b2ac">TTI::OK_AnyValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a733fb237f3037c95ed59de6055b176c5a2bc39e3785b29fe7bc4af768842a2072">TTI::OP_None</a>}, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Args={}, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CxtI=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-h">WebAssemblyTargetTransformInfo.h</a>, definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-cpp">WebAssemblyTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#ae3c3eb22dfa7c2b373ac485024f99aa6">llvm::BasicTTIImplBase&lt; T &gt;::getArithmeticInstrCost</a>, <a href="#ad15604b9ba8788ef8bc91857c10474e9">getArithmeticInstrCost</a>, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/operandvalueinfo/#ab57fcce122c37b4aaff911cf66b62583">llvm::TargetTransformInfo::OperandValueInfo::isUniform</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#ac44f6b9fdbb5f9cc199f8329cb0b272cae46c9eecc49bd2dc253c607e78a0fb86">llvm::TargetTransformInfo::TCC_Basic</a>.</p>


<p>Referenced by <a href="#ad15604b9ba8788ef8bc91857c10474e9">getArithmeticInstrCost</a>.</p>

</div>
</div>

### getNumberOfRegisters {#ae289888b64499c3bf4d5bd28ae19b2bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned WebAssemblyTTIImpl::getNumberOfRegisters (unsigned ClassID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-h">WebAssemblyTargetTransformInfo.h</a>, definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-cpp">WebAssemblyTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#add970b84395aef19d161ab202f09abb8">llvm::TargetTransformInfoImplBase::getNumberOfRegisters</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39a57dea6f5039281b7fee517fc43bf3110">llvm::Vector</a>.</p>

</div>
</div>

### getPreferredExpandedReductionShuffle {#a181f6d38c57a84f999326ad805e8191f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TTI::ReductionShuffle WebAssemblyTTIImpl::getPreferredExpandedReductionShuffle (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * II)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-h">WebAssemblyTargetTransformInfo.h</a>, definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-cpp">WebAssemblyTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a0692c75c1b45226b6afb90ad609eb86aa327036a1ef7ccbd87697bb2a2197d9ae">llvm::TargetTransformInfo::Pairwise</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a0692c75c1b45226b6afb90ad609eb86aaae6207387f79edd0cadf44ec25c995b3">llvm::TargetTransformInfo::SplitHalf</a>.</p>

</div>
</div>

### getRegisterBitWidth {#a773c8dd48e0f26dbfd7302f88128559d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeSize WebAssemblyTTIImpl::getRegisterBitWidth (<a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a8bb3b1ccf19b8c85429b777dfa4a0166">TargetTransformInfo::RegisterKind</a> K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-h">WebAssemblyTargetTransformInfo.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-cpp">WebAssemblyTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/typesize/#a003b4369b4130e669dc9139798e0193c">llvm::TypeSize::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/typesize/#a5fd620f2446d1a4cb0d55a12d182bb34">llvm::TypeSize::getScalable</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a8bb3b1ccf19b8c85429b777dfa4a0166a183020fbea95c99db23f6d3594f4c4af">llvm::TargetTransformInfo::RGK_FixedWidthVector</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a8bb3b1ccf19b8c85429b777dfa4a0166a331413d3887a08546d0973091f6a4993">llvm::TargetTransformInfo::RGK_ScalableVector</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a8bb3b1ccf19b8c85429b777dfa4a0166ad8f233645107107ed48d2e4a915152cc">llvm::TargetTransformInfo::RGK_Scalar</a>.</p>

</div>
</div>

### getVectorInstrCost {#a82b1e42b148ebdfbe1e856a1aacaf832}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost WebAssemblyTTIImpl::getVectorInstrCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, unsigned Index, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-h">WebAssemblyTargetTransformInfo.h</a>, definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-cpp">WebAssemblyTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a27bfcb3dd99fa7a7ca8dc24eeac6e8e6">llvm::BasicTTIImplBase&lt; T &gt;::getVectorInstrCost</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#ac44f6b9fdbb5f9cc199f8329cb0b272ca022565d444ccf496c0414bccefbcd9c8">llvm::TargetTransformInfo::TCC_Expensive</a>.</p>

</div>
</div>

### getVectorInstrCost {#a48521a9ff1d2ebb46d8765c321fa56df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost llvm::BasicTTIImplBase&lt; WebAssemblyTTIImpl &gt;::getVectorInstrCost (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, unsigned Index, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Scalar, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/user">User</a> *, int &gt; &gt; ScalarUserAndIdx)</td>
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

<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-h">WebAssemblyTargetTransformInfo.h</a>, definition at line 1355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicttiimpl-h">BasicTTIImpl.h</a>.</p>

</div>
</div>

### getVectorInstrCost {#adb061fbf15492f20bf20f1c9f67a61ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost llvm::BasicTTIImplBase&lt; WebAssemblyTTIImpl &gt;::getVectorInstrCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, unsigned Index)</td>
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



<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-h">WebAssemblyTargetTransformInfo.h</a>, definition at line 1363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicttiimpl-h">BasicTTIImpl.h</a>.</p>

</div>
</div>

### isProfitableToSinkOperands {#a0ac2e2e282105d3b50e85c76b9f948e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WebAssemblyTTIImpl::isProfitableToSinkOperands (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> * &gt; &amp; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-h">WebAssemblyTargetTransformInfo.h</a>, definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-cpp">WebAssemblyTargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aec67d7d9e090f41ec66d0d10169a440e">llvm::PatternMatch::m_InsertElt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5eee6cdb006c1d88b1123400f7f462d1">llvm::PatternMatch::m_Shuffle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a54d7212b9b2c57cced42037ae2fa7c61">llvm::PatternMatch::m_ZeroInt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>

</div>
</div>

### supportsTailCalls {#a760cd40e379c162238f82514245191b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WebAssemblyTTIImpl::supportsTailCalls ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-h">WebAssemblyTargetTransformInfo.h</a>, definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-cpp">WebAssemblyTargetTransformInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicttiimpl-h">BasicTTIImpl.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-cpp">WebAssemblyTargetTransformInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-h">WebAssemblyTargetTransformInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
