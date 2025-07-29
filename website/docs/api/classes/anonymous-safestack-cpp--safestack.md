---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-safestack-cpp-/safestack
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SafeStack` Class

<p>The <a href="/web-llvm/docs/api/classes/anonymous-safestack-cpp-/safestack">SafeStack</a> pass splits the stack of each function into the safe stack, which is only accessed through memory safe dereferences (as determined statically), and the unsafe stack, which contains all local variables that are accessed in ways that we can't prove to be safe. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{SafeStack.cpp}::SafeStack { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ff2b0a485f7d973f73735c0faaf97d6">SafeStack</a> (Function &amp;F, const TargetLoweringBase &amp;TL, const DataLayout &amp;DL, DomTreeUpdater *DTU, ScalarEvolution &amp;SE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77d82dc0922a0f94f90fcc7e9e194035">run</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a572baa7949cda8e8d64831be45b7e4a0">getStackGuard</a> (IRBuilder&lt;&gt; &amp;IRB, Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the value of the stack canary. <a href="#a572baa7949cda8e8d64831be45b7e4a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad29b23a2061e7b9167f9468610f3fec4">checkStackGuard</a> (IRBuilder&lt;&gt; &amp;IRB, Function &amp;F, Instruction &amp;RI, AllocaInst *StackGuardSlot, Value *StackGuard)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Load stack guard from the frame and check if it has changed. <a href="#ad29b23a2061e7b9167f9468610f3fec4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2647defecb2cc7dbab9dcf4dbdffdd5d">findInsts</a> (Function &amp;F, SmallVectorImpl&lt; AllocaInst * &gt; &amp;StaticAllocas, SmallVectorImpl&lt; AllocaInst * &gt; &amp;DynamicAllocas, SmallVectorImpl&lt; Argument * &gt; &amp;ByValArguments, SmallVectorImpl&lt; Instruction * &gt; &amp;Returns, SmallVectorImpl&lt; Instruction * &gt; &amp;StackRestorePoints)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find all static allocas, dynamic allocas, return instructions and stack restore points (exception unwind blocks and setjmp calls) in the given function and append them to the respective vectors. <a href="#a2647defecb2cc7dbab9dcf4dbdffdd5d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a133cc8c049b2d0ecd7c68476b1661f2f">getStaticAllocaAllocationSize</a> (const AllocaInst *AI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate the allocation size of a given alloca. <a href="#a133cc8c049b2d0ecd7c68476b1661f2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a198cdea1012ffc357c206472f62097ef">moveStaticAllocasToUnsafeStack</a> (IRBuilder&lt;&gt; &amp;IRB, Function &amp;F, ArrayRef&lt; AllocaInst * &gt; StaticAllocas, ArrayRef&lt; Argument * &gt; ByValArguments, Instruction *BasePointer, AllocaInst *StackGuardSlot)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate space for all static allocas in <span class="doxyComputerOutput">StaticAllocas</span>, replace allocas with pointers into the unsafe stack. <a href="#a198cdea1012ffc357c206472f62097ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4f0595e39d8987403b4e68f83913b62">createStackRestorePoints</a> (IRBuilder&lt;&gt; &amp;IRB, Function &amp;F, ArrayRef&lt; Instruction * &gt; StackRestorePoints, Value *StaticTop, bool NeedDynamicTop)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate code to restore the stack after all stack restore points in <span class="doxyComputerOutput">StackRestorePoints</span>. <a href="#ae4f0595e39d8987403b4e68f83913b62">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a646cba08b7b831bc1a69f76115879e1d">moveDynamicAllocasToUnsafeStack</a> (Function &amp;F, Value *UnsafeStackPtr, AllocaInst *DynamicTop, ArrayRef&lt; AllocaInst * &gt; DynamicAllocas)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace all allocas in <span class="doxyComputerOutput">DynamicAllocas</span> with code to allocate space dynamically on the unsafe stack and store the dynamic unsafe stack top to <span class="doxyComputerOutput">DynamicTop</span> if non-null. <a href="#a646cba08b7b831bc1a69f76115879e1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a225b3ee158c579f35d39cbaaf9b173ac">IsSafeStackAlloca</a> (const Value *AllocaPtr, uint64_t AllocaSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check whether a given allocation must be put on the safe stack or not. <a href="#a225b3ee158c579f35d39cbaaf9b173ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88f2b0c59ad5cc524af82b165f29445f">IsMemIntrinsicSafe</a> (const MemIntrinsic *MI, const Use &amp;U, const Value *AllocaPtr, uint64_t AllocaSize)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad67c167b4e9598cedeba64a67c2da921">IsAccessSafe</a> (Value *Addr, uint64_t Size, const Value *AllocaPtr, uint64_t AllocaSize)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51cd056e6fdd75ba5df9648d2c892c40">ShouldInlinePointerAddress</a> (CallInst &amp;CI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a314e690ef4594d10e931d766b80255fa">TryInlinePointerAddress</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19170e028721f22772b6eb8a10060079">F</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase">TargetLoweringBase</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5685c0e5a629c5f91f6d0287ee7286b5">TL</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a234ee7e62cd05ed11d05f6d61a0d3bb4">DL</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/domtreeupdater">DomTreeUpdater</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55712a28613867720cb8ff96151781b0">DTU</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8526150449a320a38bf2cf23389417c4">SE</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05f43cd8ef6dc3e37841b1c82ab56c02">StackPtrTy</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a5f796786fb80782c6fe9d0155770eb">IntPtrTy</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abafec07e95935177a6adc6238de2d813">Int32Ty</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adafd2686788d7d619e687923a8c68623">UnsafeStackPtr</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae047348073cd7780b9a260609ef24488">StackAlignment</a> = Align::Constant&lt;16&gt;()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unsafe stack alignment. <a href="#ae047348073cd7780b9a260609ef24488">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The <a href="/web-llvm/docs/api/classes/anonymous-safestack-cpp-/safestack">SafeStack</a> pass splits the stack of each function into the safe stack, which is only accessed through memory safe dereferences (as determined statically), and the unsafe stack, which contains all local variables that are accessed in ways that we can't prove to be safe.</p>

<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/safestack-cpp">SafeStack.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SafeStack() {#a0ff2b0a485f7d973f73735c0faaf97d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SafeStack.cpp}::SafeStack::SafeStack (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase">TargetLoweringBase</a> &amp; TL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/domtreeupdater">DomTreeUpdater</a> * DTU, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
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



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/safestack-cpp">SafeStack.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#a77d82dc0922a0f94f90fcc7e9e194035}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SafeStack.cpp}::SafeStack::run ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/safestack-cpp">SafeStack.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1b30cd686a320a8e5cb4532fd3a552a8">llvm::IRBuilderBase::CreateAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aabfc20af4dcf7d94262824dcac2e7bed">llvm::IRBuilderBase::CreateStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab73bb6948312ca0f98055c6a74c37045">llvm::IRBuilderBase::getPtrTy</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocalscope/#a0e0b4a5906e0bc2a7fa033548c59a220">llvm::DILocalScope::getSubprogram</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/safestack-cpp/#a2ad09c26566b46cb04e9ab38bbc80604">SafeStackUsePointerAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a63fc74646456a3bed261512f21efe29c">llvm::IRBuilderBase::SetCurrentDebugLocation</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-safestack-cpp-/safestacklegacypass/#a7cac2bf189a71c58d1514aaaac25414a">anonymous{SafeStack.cpp}::SafeStackLegacyPass::runOnFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### checkStackGuard() {#ad29b23a2061e7b9167f9468610f3fec4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SafeStack.cpp}::SafeStack::checkStackGuard (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; RI, <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * StackGuardSlot, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * StackGuard)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Load stack guard from the frame and check if it has changed.</p>

<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/safestack-cpp">SafeStack.cpp</a>.</p>

</div>
</div>

### createStackRestorePoints() {#ae4f0595e39d8987403b4e68f83913b62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocaInst * anonymous{SafeStack.cpp}::SafeStack::createStackRestorePoints (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; StackRestorePoints, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * StaticTop, bool NeedDynamicTop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate code to restore the stack after all stack restore points in <span class="doxyComputerOutput">StackRestorePoints</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A local variable in which to maintain the dynamic top of the unsafe stack if needed.</p></dd>
</dl>


<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/safestack-cpp">SafeStack.cpp</a>.</p>

</div>
</div>

### findInsts() {#a2647defecb2cc7dbab9dcf4dbdffdd5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SafeStack.cpp}::SafeStack::findInsts (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * &gt; &amp; StaticAllocas, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * &gt; &amp; DynamicAllocas, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> * &gt; &amp; ByValArguments, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; Returns, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; StackRestorePoints)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find all static allocas, dynamic allocas, return instructions and stack restore points (exception unwind blocks and setjmp calls) in the given function and append them to the respective vectors.</p>

<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/safestack-cpp">SafeStack.cpp</a>.</p>

</div>
</div>

### getStackGuard() {#a572baa7949cda8e8d64831be45b7e4a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{SafeStack.cpp}::SafeStack::getStackGuard (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the value of the stack canary.</p>

<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/safestack-cpp">SafeStack.cpp</a>.</p>

</div>
</div>

### getStaticAllocaAllocationSize() {#a133cc8c049b2d0ecd7c68476b1661f2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{SafeStack.cpp}::SafeStack::getStaticAllocaAllocationSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * AI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate the allocation size of a given alloca.</p>


<p>Returns 0 if the size can not be statically determined.</p>


<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/safestack-cpp">SafeStack.cpp</a>.</p>

</div>
</div>

### IsAccessSafe() {#ad67c167b4e9598cedeba64a67c2da921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SafeStack.cpp}::SafeStack::IsAccessSafe (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, uint64_t Size, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * AllocaPtr, uint64_t AllocaSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/safestack-cpp">SafeStack.cpp</a>.</p>

</div>
</div>

### IsMemIntrinsicSafe() {#a88f2b0c59ad5cc524af82b165f29445f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SafeStack.cpp}::SafeStack::IsMemIntrinsicSafe (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memintrinsic">MemIntrinsic</a> * MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp; U, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * AllocaPtr, uint64_t AllocaSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/safestack-cpp">SafeStack.cpp</a>.</p>

</div>
</div>

### IsSafeStackAlloca() {#a225b3ee158c579f35d39cbaaf9b173ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SafeStack.cpp}::SafeStack::IsSafeStackAlloca (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * AllocaPtr, uint64_t AllocaSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check whether a given allocation must be put on the safe stack or not.</p>


<p>The function analyzes all uses of AI and checks whether it is only accessed in a memory safe way (as decided statically).</p>


<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/safestack-cpp">SafeStack.cpp</a>.</p>

</div>
</div>

### moveDynamicAllocasToUnsafeStack() {#a646cba08b7b831bc1a69f76115879e1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SafeStack.cpp}::SafeStack::moveDynamicAllocasToUnsafeStack (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * UnsafeStackPtr, <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * DynamicTop, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * &gt; DynamicAllocas)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace all allocas in <span class="doxyComputerOutput">DynamicAllocas</span> with code to allocate space dynamically on the unsafe stack and store the dynamic unsafe stack top to <span class="doxyComputerOutput">DynamicTop</span> if non-null.</p>

<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/safestack-cpp">SafeStack.cpp</a>.</p>

</div>
</div>

### moveStaticAllocasToUnsafeStack() {#a198cdea1012ffc357c206472f62097ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{SafeStack.cpp}::SafeStack::moveStaticAllocasToUnsafeStack (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * &gt; StaticAllocas, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> * &gt; ByValArguments, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * BasePointer, <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * StackGuardSlot)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocate space for all static allocas in <span class="doxyComputerOutput">StaticAllocas</span>, replace allocas with pointers into the unsafe stack.</p>


<p>We explicitly compute and set the unsafe stack layout for all unsafe static alloca instructions.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A pointer to the top of the unsafe stack after all unsafe static allocas are allocated.</p></dd>
</dl>


<p>We save the unsafe "base pointer" in the prologue into a local variable and restore it in the epilogue.</p>


<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/safestack-cpp">SafeStack.cpp</a>.</p>

</div>
</div>

### ShouldInlinePointerAddress() {#a51cd056e6fdd75ba5df9648d2c892c40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SafeStack.cpp}::SafeStack::ShouldInlinePointerAddress (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; CI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/safestack-cpp">SafeStack.cpp</a>.</p>

</div>
</div>

### TryInlinePointerAddress() {#a314e690ef4594d10e931d766b80255fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SafeStack.cpp}::SafeStack::TryInlinePointerAddress ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/safestack-cpp">SafeStack.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DL {#a234ee7e62cd05ed11d05f6d61a0d3bb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout&amp; anonymous{SafeStack.cpp}::SafeStack::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/safestack-cpp">SafeStack.cpp</a>.</p>

</div>
</div>

### DTU {#a55712a28613867720cb8ff96151781b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DomTreeUpdater* anonymous{SafeStack.cpp}::SafeStack::DTU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/safestack-cpp">SafeStack.cpp</a>.</p>

</div>
</div>

### F {#a19170e028721f22772b6eb8a10060079}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function&amp; anonymous{SafeStack.cpp}::SafeStack::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/safestack-cpp">SafeStack.cpp</a>.</p>

</div>
</div>

### Int32Ty {#abafec07e95935177a6adc6238de2d813}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* anonymous{SafeStack.cpp}::SafeStack::Int32Ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/safestack-cpp">SafeStack.cpp</a>.</p>

</div>
</div>

### IntPtrTy {#a1a5f796786fb80782c6fe9d0155770eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* anonymous{SafeStack.cpp}::SafeStack::IntPtrTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/safestack-cpp">SafeStack.cpp</a>.</p>

</div>
</div>

### SE {#a8526150449a320a38bf2cf23389417c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution&amp; anonymous{SafeStack.cpp}::SafeStack::SE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/safestack-cpp">SafeStack.cpp</a>.</p>

</div>
</div>

### StackPtrTy {#a05f43cd8ef6dc3e37841b1c82ab56c02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* anonymous{SafeStack.cpp}::SafeStack::StackPtrTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/safestack-cpp">SafeStack.cpp</a>.</p>

</div>
</div>

### TL {#a5685c0e5a629c5f91f6d0287ee7286b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLoweringBase&amp; anonymous{SafeStack.cpp}::SafeStack::TL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/safestack-cpp">SafeStack.cpp</a>.</p>

</div>
</div>

### UnsafeStackPtr {#adafd2686788d7d619e687923a8c68623}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* anonymous{SafeStack.cpp}::SafeStack::UnsafeStackPtr = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/safestack-cpp">SafeStack.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### StackAlignment {#ae047348073cd7780b9a260609ef24488}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align anonymous{SafeStack.cpp}::SafeStack::StackAlignment = Align::Constant&lt;16&gt;()</td>
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

<p>Unsafe stack alignment.</p>


<p>Each stack frame must ensure that the stack is aligned to this value. We need to re-align the unsafe stack if the alignment of any object on the stack exceeds this value.</p>


<p>16 seems like a reasonable upper bound on the alignment of objects that we might expect to appear on the stack on most common targets.</p>


<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/safestack-cpp">SafeStack.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/safestack-cpp">SafeStack.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
