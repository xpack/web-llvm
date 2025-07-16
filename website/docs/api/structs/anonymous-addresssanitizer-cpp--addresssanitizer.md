---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AddressSanitizer` Struct Reference

<p><a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer">AddressSanitizer</a>: instrument the code in module to find memory bugs. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{AddressSanitizer.cpp}::AddressSanitizer { ... }
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d62ed5898951d0775ed218ad3e2d56e">FunctionStackPoisoner</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae700acd5d174922e475ea31fdb8fe51f">AddressSanitizer</a> (Module &amp;M, const StackSafetyGlobalInfo *SSGI, int InstrumentationWithCallsThreshold, uint32_t MaxInlinePoisoningSize, bool CompileKernel=false, bool Recover=false, bool UseAfterScope=false, AsanDetectStackUseAfterReturnMode UseAfterReturn=AsanDetectStackUseAfterReturnMode::Runtime)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a8741af2dcfc3312679330e1069c734">getAllocaSizeInBytes</a> (const AllocaInst &amp;AI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b2938393443d2c8a8e005292eed060f">isInterestingAlloca</a> (const AllocaInst &amp;AI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if we want (and can) handle this alloca. <a href="#a3b2938393443d2c8a8e005292eed060f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef822a56c96fe3f688c09d71bacb9b65">ignoreAccess</a> (Instruction *Inst, Value *Ptr)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a768d59ed528e3f461065b20571b913dc">getInterestingMemoryOperands</a> (Instruction *I, SmallVectorImpl&lt; InterestingMemoryOperand &gt; &amp;Interesting)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e375fb896826338e488dae6f16e853b">instrumentMop</a> (ObjectSizeOffsetVisitor &amp;ObjSizeVis, InterestingMemoryOperand &amp;O, bool UseCalls, const DataLayout &amp;DL, RuntimeCallInserter &amp;RTCI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2d43eb64d8a2c479e94d13a0699ba38">instrumentPointerComparisonOrSubtraction</a> (Instruction *I, RuntimeCallInserter &amp;RTCI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b79beccbeb33ff89c797f5ac7b3fce3">instrumentAddress</a> (Instruction *OrigIns, Instruction *InsertBefore, Value *Addr, MaybeAlign Alignment, uint32_t TypeStoreSize, bool IsWrite, Value *SizeArgument, bool UseCalls, uint32_t Exp, RuntimeCallInserter &amp;RTCI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a548c5b4779101e84af6a92e2548be083">instrumentAMDGPUAddress</a> (Instruction *OrigIns, Instruction *InsertBefore, Value *Addr, uint32_t TypeStoreSize, bool IsWrite, Value *SizeArgument)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af54e01fb7fd5db7ff76495fcabc90ea1">genAMDGPUReportBlock</a> (IRBuilder&lt;&gt; &amp;IRB, Value *Cond, bool Recover)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6119f1988ee2e260e58defc26361639">instrumentUnusualSizeOrAlignment</a> (Instruction *I, Instruction *InsertBefore, Value *Addr, TypeSize TypeStoreSize, bool IsWrite, Value *SizeArgument, bool UseCalls, uint32_t Exp, RuntimeCallInserter &amp;RTCI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad73240db48b2eda2b2ca2ce38530c552">instrumentMaskedLoadOrStore</a> (AddressSanitizer *Pass, const DataLayout &amp;DL, Type *IntptrTy, Value *Mask, Value *EVL, Value *Stride, Instruction *I, Value *Addr, MaybeAlign Alignment, unsigned Granularity, Type *OpType, bool IsWrite, Value *SizeArgument, bool UseCalls, uint32_t Exp, RuntimeCallInserter &amp;RTCI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0406832b34218bdfd92947d2612f3c3d">createSlowPathCmp</a> (IRBuilder&lt;&gt; &amp;IRB, Value *AddrLong, Value *ShadowValue, uint32_t TypeStoreSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67ce284f582c0557f843076f92ab7fd6">generateCrashCode</a> (Instruction *InsertBefore, Value *Addr, bool IsWrite, size_t AccessSizeIndex, Value *SizeArgument, uint32_t Exp, RuntimeCallInserter &amp;RTCI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8e997542278bc23b2e3a5f3ddeffdea">instrumentMemIntrinsic</a> (MemIntrinsic *MI, RuntimeCallInserter &amp;RTCI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a220cbee431faba18cde250a8c23a9409">memToShadow</a> (Value *Shadow, IRBuilder&lt;&gt; &amp;IRB)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a198a94d5bead3d753bfc1bc8383e16e6">suppressInstrumentationSiteForDebug</a> (int &amp;Instrumented)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a489ae04c136c4b088d849d7d6dc20965">instrumentFunction</a> (Function &amp;F, const TargetLibraryInfo *TLI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10f3ee26e5d2bcc100abe6939fdf9fd6">maybeInsertAsanInitAtFunctionEntry</a> (Function &amp;F)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc1dbfd3922f952c6e5edbed42521c54">maybeInsertDynamicShadowAtFunctionEntry</a> (Function &amp;F)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f0e568588160e095493dcfc7b5a010e">markEscapedLocalAllocas</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12fa8f30445084f234d2cbea08ba4bcb">initializeCallbacks</a> (const TargetLibraryInfo *TLI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bf7a4d1ec425e8dcd9b951b714450a1">LooksLikeCodeInBug11395</a> (Instruction *I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a004265d2f068709e1560b951481623c8">GlobalIsLinkerInitialized</a> (GlobalVariable *G)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff14ae86828d92743d0a51e416417bf0">isSafeAccess</a> (ObjectSizeOffsetVisitor &amp;ObjSizeVis, Value *Addr, TypeSize TypeStoreSize) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89cc545f9fe270f29f2efbb0991663e6">M</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c4f608f2e1df0938e81741b299a3ddf">C</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a448785d72e180f6c2587e1b5642d4645">DL</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae402906bf8d98003fa463b7675342e75">TargetTriple</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa471876e3b35ebd7c8b1e513fe4ec79f">LongSize</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a122b5e2f48ff4615c234801262cd01a4">CompileKernel</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbf72d97d36a991442b801fe8d32f7ba">Recover</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a647cef8d81710b74217afc85bbe68aa7">UseAfterScope</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a273ffd11c1ebf40fc70e3b22009adabd">AsanDetectStackUseAfterReturnMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22362f89ee9a3ef30f238ea48d814e11">UseAfterReturn</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fec4bfc0d330e5cf68900b623fdd54a">IntptrTy</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4249dd9568f01769c55be3c87f05f075">Int32Ty</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointertype">PointerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d3042d20c13c4ba7e3578310d08aff3">PtrTy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/shadowmapping">ShadowMapping</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cc8bd72eb748c10a54dd1deb3a823e0">Mapping</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e81171102c974155d6c46b85f6aba9c">AsanHandleNoReturnFunc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11c906fca6e7dfcf53f707a009a26a9a">AsanPtrCmpFunction</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8589c5483007db6c978d45f2122c8260">AsanPtrSubFunction</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5701ba86e3de2ae24657cf95c79ea191">AsanShadowGlobal</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a947d41b90cbce228960055822cbd68b4">AsanErrorCallback</a>[2][2][kNumberOfAccessSizes]</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2260119a0e81966573b867a72a7495e7">AsanMemoryAccessCallback</a>[2][2][kNumberOfAccessSizes]</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee567759d4da5f8d324fe83f05b0ab0c">AsanErrorCallbackSized</a>[2][2]</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa79d2163ea5a60441ce1c279dae85092">AsanMemoryAccessCallbackSized</a>[2][2]</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a131268669f7ad4dc9f6732a4b11b3132">AsanMemmove</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86bcfc36a6b12da22fd39d2ee154b99f">AsanMemcpy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ba4d638bef98aaad74d8c9bba11cf1c">AsanMemset</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09f9778f7a39307358016bba2e40929a">LocalDynamicShadow</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stacksafetyglobalinfo">StackSafetyGlobalInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefb654e803c831c1ed132b20b25ff0ae">SSGI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcf9022da301d296da86d7d824be91a4">ProcessedAllocas</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a383ec71f6eae83c038539c2da166da">AMDGPUAddressShared</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a642ee339f26cc895e7cc04a9bb6a0b57">AMDGPUAddressPrivate</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c3e1ca620fa1e446e9b2222c8a0b578">InstrumentationWithCallsThreshold</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16a1329918c325821f41dc4f4bd0c18a">MaxInlinePoisoningSize</a></td>
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

<p><a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer">AddressSanitizer</a>: instrument the code in module to find memory bugs.</p>

<p>Definition at line 719 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<div class="doxySectionDef">

## Friends

### FunctionStackPoisoner {#a5d62ed5898951d0775ed218ad3e2d56e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner">FunctionStackPoisoner</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 809 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="#ae700acd5d174922e475ea31fdb8fe51f">AddressSanitizer</a>, <a href="#a5d62ed5898951d0775ed218ad3e2d56e">FunctionStackPoisoner</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a5d62ed5898951d0775ed218ad3e2d56e">FunctionStackPoisoner</a> and <a href="#a489ae04c136c4b088d849d7d6dc20965">instrumentFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AddressSanitizer() {#ae700acd5d174922e475ea31fdb8fe51f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AddressSanitizer.cpp}::AddressSanitizer::AddressSanitizer (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stacksafetyglobalinfo">StackSafetyGlobalInfo</a> * SSGI, int InstrumentationWithCallsThreshold, uint32_t MaxInlinePoisoningSize, bool CompileKernel=false, bool Recover=false, bool UseAfterScope=false, <a href="/web-llvm/docs/api/namespaces/llvm/#a273ffd11c1ebf40fc70e3b22009adabd">AsanDetectStackUseAfterReturnMode</a> UseAfterReturn=AsanDetectStackUseAfterReturnMode::Runtime)</td>
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



<p>Definition at line 720 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#aa09777d1507554d2873581bb83442022">ClEnableKasan</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a7b6dcf17e1b173746a4939b677ca1fb0">ClInstrumentationWithCallsThreshold</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a96c36d2e9698f2974735d30dfea6893c">ClMaxInlinePoisoningSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ab07c89b5ab3621d59817baefdae128cb">ClRecover</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ab96ca2732f7eaecb2e762c9c754f7b37">ClUseAfterReturn</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a9a4fc66faeab43a236796f382e142af4">ClUseAfterScope</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#acaf8e4c3e40e01e848c1fad5f05b81cd">llvm::Type::getIntNTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ac4b45ab450a043187e92eaace7d62018">getShadowMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a273ffd11c1ebf40fc70e3b22009adabda4bbb8f967da6d1a610596d7257179c2b">llvm::Invalid</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a273ffd11c1ebf40fc70e3b22009adabdabc366f2d0ba3d681e7a3899917c5d3de">llvm::Runtime</a>.</p>


<p>Referenced by <a href="#a5d62ed5898951d0775ed218ad3e2d56e">FunctionStackPoisoner</a> and <a href="#ad73240db48b2eda2b2ca2ce38530c552">instrumentMaskedLoadOrStore</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createSlowPathCmp() {#a0406832b34218bdfd92947d2612f3c3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * AddressSanitizer::createSlowPathCmp (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * AddrLong, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ShadowValue, uint32_t TypeStoreSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 794 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4841d2c05da686940d2c9cc56f0bb348">llvm::IRBuilderBase::CreateICmpSGE</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac79ca3c2d2d74cf33684397a91846564">llvm::IRBuilderBase::CreateIntCast</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="#a9b79beccbeb33ff89c797f5ac7b3fce3">instrumentAddress</a>.</p>

</div>
</div>

### genAMDGPUReportBlock() {#af54e01fb7fd5db7ff76495fcabc90ea1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * AddressSanitizer::genAMDGPUReportBlock (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Cond, bool Recover)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 779 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aafd864f39fd28e235eea03ae424ab8e0">llvm::IRBuilderBase::CreateIsNotNull</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#ae609aeb09c2b1c9f03fb90228654b281">llvm::MDBuilder::createUnlikelyBranchWeights</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a60a6d6c205f483fa96597a960f3c093b">llvm::IRBuilderBase::GetInsertBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4e5c1b91bf5e2860398e3fa35c96b5af">llvm::IRBuilderBase::GetInsertPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1fb6e8365dbf4ef3a7426ff3d531ff87">llvm::IRBuilderBase::getInt1Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a64748b5a9f8d8dd4499f84312e2c1336">llvm::IRBuilderBase::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#afc70e919c88c86159cc94cea29b6c210">llvm::BasicBlock::getModule</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad0243f1634f75e231041023ffaa8501a">llvm::IRBuilderBase::getVoidTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ae7f00801ef2ef87699661f1dca513b52">kAMDGPUBallotName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a0942316ad508b030eec9f8ac3104b964">kAMDGPUUnreachableName</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad957413955739c91204c96e33e0cc933">llvm::SplitBlockAndInsertIfThen</a>.</p>


<p>Referenced by <a href="#a9b79beccbeb33ff89c797f5ac7b3fce3">instrumentAddress</a>.</p>

</div>
</div>

### generateCrashCode() {#a67ce284f582c0557f843076f92ab7fd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * AddressSanitizer::generateCrashCode (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * InsertBefore, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, bool IsWrite, size_t AccessSizeIndex, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * SizeArgument, uint32_t Exp, <a href="/web-llvm/docs/api/classes/anonymous-addresssanitizer-cpp-/runtimecallinserter">RuntimeCallInserter</a> &amp; RTCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 796 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-addresssanitizer-cpp-/runtimecallinserter/#ac35be115df797c75d7875cf63e56ea2b">anonymous{AddressSanitizer.cpp}::RuntimeCallInserter::createRuntimeCall</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5852dc0d180581d34902e8abcbf7e930">llvm::IRBuilderBase::getInt32Ty</a>.</p>


<p>Referenced by <a href="#a9b79beccbeb33ff89c797f5ac7b3fce3">instrumentAddress</a>.</p>

</div>
</div>

### getAllocaSizeInBytes() {#a8a8741af2dcfc3312679330e1069c734}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeSize anonymous{AddressSanitizer.cpp}::AddressSanitizer::getAllocaSizeInBytes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> &amp; AI)</td>
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



<p>Definition at line 754 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/allocainst/#ad92f6c67d55ced3de1569ee791c38679">llvm::AllocaInst::getAllocationSize</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#af65afd02332c4f21c2fab7d217d6600f">llvm::Instruction::getDataLayout</a>.</p>


<p>Referenced by <a href="#a3b2938393443d2c8a8e005292eed060f">isInterestingAlloca</a>.</p>

</div>
</div>

### getInterestingMemoryOperands() {#a768d59ed528e3f461065b20571b913dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AddressSanitizer::getInterestingMemoryOperands (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/interestingmemoryoperand">InterestingMemoryOperand</a> &gt; &amp; Interesting)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 762 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a98491b92a3cd11f11c29f752625b136d">ClInstrumentAtomics</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a33190b8a2d49613b79d5374db635dd0a">ClInstrumentByval</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#adc5cd4695253418937546218dbe26922">ClInstrumentReads</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a2df764565c5764a2af608a819cfa2540">ClInstrumentWrites</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#aef822a56c96fe3f688c09d71bacb9b65">ignoreAccess</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a> and <a href="/web-llvm/docs/api/structs/llvm/maybealign/#a06846474be3ab85f8d30c388faf3b116">llvm::MaybeAlign::valueOrOne</a>.</p>


<p>Referenced by <a href="#a489ae04c136c4b088d849d7d6dc20965">instrumentFunction</a>.</p>

</div>
</div>

### ignoreAccess() {#aef822a56c96fe3f688c09d71bacb9b65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AddressSanitizer::ignoreAccess (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 761 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#aeff4047a82cefd8108f2bc7263e924fa">ClSkipPromotableAllocas</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a21fe87bf00db76089c043fed6a23fb76">llvm::findAllocaForValue</a>, <a href="#a3b2938393443d2c8a8e005292eed060f">isInterestingAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a66fb0770ddf5f596079ee32ca4b8b599">isUnsupportedAMDGPUAddrspace</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>


<p>Referenced by <a href="#a768d59ed528e3f461065b20571b913dc">getInterestingMemoryOperands</a>.</p>

</div>
</div>

### instrumentAddress() {#a9b79beccbeb33ff89c797f5ac7b3fce3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AddressSanitizer::instrumentAddress (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * OrigIns, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * InsertBefore, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, <a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> Alignment, uint32_t TypeStoreSize, bool IsWrite, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * SizeArgument, bool UseCalls, uint32_t Exp, <a href="/web-llvm/docs/api/classes/anonymous-addresssanitizer-cpp-/runtimecallinserter">RuntimeCallInserter</a> &amp; RTCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 770 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#acfc2efa648ba005caa42cf6f28d82757">ClAlwaysSlowPath</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a53fdfe303964c0943c25d294cd1cf193">ClOptimizeCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a9f40e42226cee617c16cb1c447b115c5">llvm::BranchInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3313ae2d314fb689cebdaf062d86eec5">llvm::IRBuilderBase::CreateAlignedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a53541ed6f92b18419f937f1f969aa0f6">llvm::IRBuilderBase::CreateIntToPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aafd864f39fd28e235eea03ae424ab8e0">llvm::IRBuilderBase::CreateIsNotNull</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3ef26a11123d639b64307cc3c1b869b9">llvm::IRBuilderBase::CreatePointerCast</a>, <a href="/web-llvm/docs/api/classes/anonymous-addresssanitizer-cpp-/runtimecallinserter/#ac35be115df797c75d7875cf63e56ea2b">anonymous{AddressSanitizer.cpp}::RuntimeCallInserter::createRuntimeCall</a>, <a href="#a0406832b34218bdfd92947d2612f3c3d">createSlowPathCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#ae609aeb09c2b1c9f03fb90228654b281">llvm::MDBuilder::createUnlikelyBranchWeights</a>, <a href="#af54e01fb7fd5db7ff76495fcabc90ea1">genAMDGPUReportBlock</a>, <a href="#a67ce284f582c0557f843076f92ab7fd6">generateCrashCode</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#a8d7f800be5fd53dcfcdcbdc6fd9ccfe3">llvm::PointerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5852dc0d180581d34902e8abcbf7e930">llvm::IRBuilderBase::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6e5d2e18c81baaeec7dadc81a0dea993">llvm::Instruction::getSuccessor</a>, <a href="#a548c5b4779101e84af6a92e2548be083">instrumentAMDGPUAddress</a>, <a href="#a220cbee431faba18cde250a8c23a9409">memToShadow</a>, <a href="/web-llvm/docs/api/structs/llvm/asanaccessinfo/#ac266711cabbe76782e3e68d0ad07f120">llvm::ASanAccessInfo::Packed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a016a85f7487f995fe80141e102a7a5ae">llvm::ReplaceInstWithInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae8f5bf5cc06f696b52c709677df00fbf">llvm::Instruction::setDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad957413955739c91204c96e33e0cc933">llvm::SplitBlockAndInsertIfThen</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#adcdff5e32d9b4d801f187d48b106e579">TypeStoreSizeToSizeIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a> and <a href="/web-llvm/docs/api/structs/llvm/maybealign/#a06846474be3ab85f8d30c388faf3b116">llvm::MaybeAlign::valueOrOne</a>.</p>


<p>Referenced by <a href="#ac6119f1988ee2e260e58defc26361639">instrumentUnusualSizeOrAlignment</a>.</p>

</div>
</div>

### instrumentAMDGPUAddress() {#a548c5b4779101e84af6a92e2548be083}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * AddressSanitizer::instrumentAMDGPUAddress (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * OrigIns, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * InsertBefore, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, uint32_t TypeStoreSize, bool IsWrite, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * SizeArgument)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 775 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a89f675aadae7232445c74ee4167ff591">llvm::IRBuilderBase::CreateNot</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7c742b32ebcd73d6dc851afac295b0f2">llvm::Type::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a66fb0770ddf5f596079ee32ca4b8b599">isUnsupportedAMDGPUAddrspace</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad957413955739c91204c96e33e0cc933">llvm::SplitBlockAndInsertIfThen</a>.</p>


<p>Referenced by <a href="#a9b79beccbeb33ff89c797f5ac7b3fce3">instrumentAddress</a>.</p>

</div>
</div>

### instrumentFunction() {#a489ae04c136c4b088d849d7d6dc20965}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AddressSanitizer::instrumentFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 803 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caa67f293befacbbf974525116ccf2ff42">llvm::GlobalValue::AvailableExternallyLinkage</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#aa14af85369bdb6b331cd00f499d4cf63">ClDebugFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a16413f1a88d8baca228d0a1b4cc0bfc6">llvm::SmallPtrSetImplBase::clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a7988b8281b1972c35eb5833f8c23a1a3">ClInvalidPointerCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#afe56a2bdf58d01cf437e1abba61e2830">ClInvalidPointerPairs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a8398c67027004edc3649be6b6db60eab">ClInvalidPointerSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#af7099fa6660e94761e7f5b525b330bb2">ClMaxInsnsToInstrumentPerBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a6d7586f09e72a8d0b38a7b28ce03068c">ClOpt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ab320a8dd5d6290c1e021de274df4c809">ClOptSameTemp</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/classes/anonymous-addresssanitizer-cpp-/runtimecallinserter/#ac35be115df797c75d7875cf63e56ea2b">anonymous{AddressSanitizer.cpp}::RuntimeCallInserter::createRuntimeCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a5d62ed5898951d0775ed218ad3e2d56e">FunctionStackPoisoner</a>, <a href="#a768d59ed528e3f461065b20571b913dc">getInterestingMemoryOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a565f546ad95bd3a9bbe9a1e5040803f0">llvm::Instruction::hasMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="#ab8e997542278bc23b2e3a5f3ddeffdea">instrumentMemIntrinsic</a>, <a href="#a9e375fb896826338e488dae6f16e853b">instrumentMop</a>, <a href="#ae2d43eb64d8a2c479e94d13a0699ba38">instrumentPointerComparisonOrSubtraction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a8d829e3f1a798c5c559b716ba05a4d7d">isInterestingPointerComparison</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a1e0c09290631b1be732e7387c75aca09">isInterestingPointerSubtraction</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a5f0e568588160e095493dcfc7b5a010e">markEscapedLocalAllocas</a>, <a href="#a10f3ee26e5d2bcc100abe6939fdf9fd6">maybeInsertAsanInitAtFunctionEntry</a>, <a href="#abc1dbfd3922f952c6e5edbed42521c54">maybeInsertDynamicShadowAtFunctionEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae63427c4d8f3c1ce48401b38ed9198f1">llvm::maybeMarkSanitizerLibraryCallNoBuiltin</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner/#a6d9d3b77ad59887d486351a427b585b0">anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="#a198a94d5bead3d753bfc1bc8383e16e6">suppressInstrumentationSiteForDebug</a>.</p>

</div>
</div>

### instrumentMaskedLoadOrStore() {#ad73240db48b2eda2b2ca2ce38530c552}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AddressSanitizer::instrumentMaskedLoadOrStore (<a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer">AddressSanitizer</a> * Pass, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * IntptrTy, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Mask, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * EVL, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Stride, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, <a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> Alignment, unsigned Granularity, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * OpType, bool IsWrite, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * SizeArgument, bool UseCalls, uint32_t Exp, <a href="/web-llvm/docs/api/classes/anonymous-addresssanitizer-cpp-/runtimecallinserter">RuntimeCallInserter</a> &amp; RTCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 787 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="#ae700acd5d174922e475ea31fdb8fe51f">AddressSanitizer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a73e0482b96d9d0cdfcc90c0a34f5b0db">llvm::IRBuilderBase::CreateGEP</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aecd40f9a16dc0ef1e0bc416599f89277">llvm::IRBuilderBase::CreateMul</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5b416a8603ccb844165c8df22454ac05">llvm::IRBuilderBase::CreatePtrAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a01b9989f797101a150d7a960255adfec">doInstrumentAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4e5c1b91bf5e2860398e3fa35c96b5af">llvm::IRBuilderBase::GetInsertPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af71ef8ea795d6a6eb87a3499f3b0c90f">llvm::SplitBlockAndInsertForEachLane</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad957413955739c91204c96e33e0cc933">llvm::SplitBlockAndInsertIfThen</a>.</p>


<p>Referenced by <a href="#a9e375fb896826338e488dae6f16e853b">instrumentMop</a>.</p>

</div>
</div>

### instrumentMemIntrinsic() {#ab8e997542278bc23b2e3a5f3ddeffdea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AddressSanitizer::instrumentMemIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/memintrinsic">MemIntrinsic</a> * MI, <a href="/web-llvm/docs/api/classes/anonymous-addresssanitizer-cpp-/runtimecallinserter">RuntimeCallInserter</a> &amp; RTCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 800 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aeb6ccc122c2f6868fc3a1e68e1ae157c">llvm::IRBuilderBase::CreateAddrSpaceCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac79ca3c2d2d74cf33684397a91846564">llvm::IRBuilderBase::CreateIntCast</a>, <a href="/web-llvm/docs/api/classes/anonymous-addresssanitizer-cpp-/runtimecallinserter/#ac35be115df797c75d7875cf63e56ea2b">anonymous{AddressSanitizer.cpp}::RuntimeCallInserter::createRuntimeCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5852dc0d180581d34902e8abcbf7e930">llvm::IRBuilderBase::getInt32Ty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a489ae04c136c4b088d849d7d6dc20965">instrumentFunction</a>.</p>

</div>
</div>

### instrumentMop() {#a9e375fb896826338e488dae6f16e853b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AddressSanitizer::instrumentMop (<a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetvisitor">ObjectSizeOffsetVisitor</a> &amp; ObjSizeVis, <a href="/web-llvm/docs/api/classes/llvm/interestingmemoryoperand">InterestingMemoryOperand</a> &amp; O, bool UseCalls, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/anonymous-addresssanitizer-cpp-/runtimecallinserter">RuntimeCallInserter</a> &amp; RTCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 765 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a8769662e83dc63443d2cfa743cd8407b">ClForceExperiment</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ad7ffe665351fede3f8025e2cb84ccc83">ClInitializers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a6d7586f09e72a8d0b38a7b28ce03068c">ClOpt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#abd03cce0a222ad0e49b3074b9258f894">ClOptGlobals</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ab6e8695312b588ef5a110f33c9beb09c">ClOptStack</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a01b9989f797101a150d7a960255adfec">doInstrumentAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b1c5788b85ffa254be0e834edf5cf8f">llvm::getUnderlyingObject</a>, <a href="#ad73240db48b2eda2b2ca2ce38530c552">instrumentMaskedLoadOrStore</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#a489ae04c136c4b088d849d7d6dc20965">instrumentFunction</a>.</p>

</div>
</div>

### instrumentPointerComparisonOrSubtraction() {#ae2d43eb64d8a2c479e94d13a0699ba38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AddressSanitizer::instrumentPointerComparisonOrSubtraction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/anonymous-addresssanitizer-cpp-/runtimecallinserter">RuntimeCallInserter</a> &amp; RTCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 768 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3ef26a11123d639b64307cc3c1b869b9">llvm::IRBuilderBase::CreatePointerCast</a>, <a href="/web-llvm/docs/api/classes/anonymous-addresssanitizer-cpp-/runtimecallinserter/#ac35be115df797c75d7875cf63e56ea2b">anonymous{AddressSanitizer.cpp}::RuntimeCallInserter::createRuntimeCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#a489ae04c136c4b088d849d7d6dc20965">instrumentFunction</a>.</p>

</div>
</div>

### instrumentUnusualSizeOrAlignment() {#ac6119f1988ee2e260e58defc26361639}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AddressSanitizer::instrumentUnusualSizeOrAlignment (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * InsertBefore, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, <a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a> TypeStoreSize, bool IsWrite, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * SizeArgument, bool UseCalls, uint32_t Exp, <a href="/web-llvm/docs/api/classes/anonymous-addresssanitizer-cpp-/runtimecallinserter">RuntimeCallInserter</a> &amp; RTCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 781 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a53541ed6f92b18419f937f1f969aa0f6">llvm::IRBuilderBase::CreateIntToPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5849d19e500f8c6713ec44889058f424">llvm::IRBuilderBase::CreateLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3ef26a11123d639b64307cc3c1b869b9">llvm::IRBuilderBase::CreatePointerCast</a>, <a href="/web-llvm/docs/api/classes/anonymous-addresssanitizer-cpp-/runtimecallinserter/#ac35be115df797c75d7875cf63e56ea2b">anonymous{AddressSanitizer.cpp}::RuntimeCallInserter::createRuntimeCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a92c83e803f2cf22906da0aaec44ff6d7">llvm::IRBuilderBase::CreateSub</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a55086d93549de64322f4d3e8f5dd4883">llvm::IRBuilderBase::CreateTypeSize</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5852dc0d180581d34902e8abcbf7e930">llvm::IRBuilderBase::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a9b79beccbeb33ff89c797f5ac7b3fce3">instrumentAddress</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### isInterestingAlloca() {#a3b2938393443d2c8a8e005292eed060f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AddressSanitizer::isInterestingAlloca (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> &amp; AI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check if we want (and can) handle this alloca.</p>

<p>Definition at line 759 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#aeff4047a82cefd8108f2bc7263e924fa">ClSkipPromotableAllocas</a>, <a href="#a8a8741af2dcfc3312679330e1069c734">getAllocaSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a9b5ec84ea363eca9e35ddca20a5313af">llvm::AllocaInst::getAllocatedType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5023b360abc7a5d1612061fba30003a6">llvm::isAllocaPromotable</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a36e31f42170be95fc392dad696d9ba19">llvm::AllocaInst::isStaticAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a3016b467a9ecb5506956f7d029509db5">llvm::AllocaInst::isSwiftError</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a9bb98c4ac4cf77f5782e5e41f2c6f38a">llvm::AllocaInst::isUsedWithInAlloca</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/lint-cpp/#a45005634b54e2126cb3e6ec0dbc9ade4">isZero</a>.</p>


<p>Referenced by <a href="#aef822a56c96fe3f688c09d71bacb9b65">ignoreAccess</a>.</p>

</div>
</div>

### markEscapedLocalAllocas() {#a5f0e568588160e095493dcfc7b5a010e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AddressSanitizer::markEscapedLocalAllocas (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 806 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a> and <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a36e31f42170be95fc392dad696d9ba19">llvm::AllocaInst::isStaticAlloca</a>.</p>


<p>Referenced by <a href="#a489ae04c136c4b088d849d7d6dc20965">instrumentFunction</a>.</p>

</div>
</div>

### maybeInsertAsanInitAtFunctionEntry() {#a10f3ee26e5d2bcc100abe6939fdf9fd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AddressSanitizer::maybeInsertAsanInitAtFunctionEntry (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 804 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67d90c79914c0bdfadad630647f8843b">llvm::declareSanitizerInitFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a361b5f11d7b296279f45007be01c2913">kAsanInitName</a>.</p>


<p>Referenced by <a href="#a489ae04c136c4b088d849d7d6dc20965">instrumentFunction</a>.</p>

</div>
</div>

### maybeInsertDynamicShadowAtFunctionEntry() {#abc1dbfd3922f952c6e5edbed42521c54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AddressSanitizer::maybeInsertDynamicShadowAtFunctionEntry (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 805 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a63147f939444e77f3a294dc59c2939ba">ClWithIfuncSuppressRemat</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3ef26a11123d639b64307cc3c1b869b9">llvm::IRBuilderBase::CreatePointerCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a44dec91bb943f56f8bba3e9171a76947">llvm::InlineAsm::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a72f82be6c1dbdf567e8dd11251e87000">kAsanShadowMemoryDynamicAddress</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a8d1135f2ee91e5d486647a37f8074dcc">kDynamicShadowSentinel</a>.</p>


<p>Referenced by <a href="#a489ae04c136c4b088d849d7d6dc20965">instrumentFunction</a>.</p>

</div>
</div>

### memToShadow() {#a220cbee431faba18cde250a8c23a9409}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * AddressSanitizer::memToShadow (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Shadow, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 801 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5849d19e500f8c6713ec44889058f424">llvm::IRBuilderBase::CreateLShr</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab61be8e3cf17e9848aeeeabacfa1b09a">llvm::IRBuilderBase::CreateOr</a>.</p>


<p>Referenced by <a href="#a9b79beccbeb33ff89c797f5ac7b3fce3">instrumentAddress</a>.</p>

</div>
</div>

### suppressInstrumentationSiteForDebug() {#a198a94d5bead3d753bfc1bc8383e16e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AddressSanitizer::suppressInstrumentationSiteForDebug (int &amp; Instrumented)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 802 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a8052781b69a1a9e2f58c190a15b67628">ClDebugMax</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a0dd632512536154ac3d012e7065f2bcf">ClDebugMin</a>.</p>


<p>Referenced by <a href="#a489ae04c136c4b088d849d7d6dc20965">instrumentFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### GlobalIsLinkerInitialized() {#a004265d2f068709e1560b951481623c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AddressSanitizer::GlobalIsLinkerInitialized (<a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 814 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### initializeCallbacks() {#a12fa8f30445084f234d2cbea08ba4bcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AddressSanitizer::initializeCallbacks (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 811 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### isSafeAccess() {#aff14ae86828d92743d0a51e416417bf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AddressSanitizer::isSafeAccess (<a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetvisitor">ObjectSizeOffsetVisitor</a> &amp; ObjSizeVis, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, <a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a> TypeStoreSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 815 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### LooksLikeCodeInBug11395() {#a2bf7a4d1ec425e8dcd9b951b714450a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AddressSanitizer::LooksLikeCodeInBug11395 (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 813 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AMDGPUAddressPrivate {#a642ee339f26cc895e7cc04a9bb6a0b57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{AddressSanitizer.cpp}::AddressSanitizer::AMDGPUAddressPrivate</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 865 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### AMDGPUAddressShared {#a3a383ec71f6eae83c038539c2da166da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{AddressSanitizer.cpp}::AddressSanitizer::AMDGPUAddressShared</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 864 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### AsanErrorCallback {#a947d41b90cbce228960055822cbd68b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{AddressSanitizer.cpp}::AddressSanitizer::AsanErrorCallback[2][2][kNumberOfAccessSizes]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 852 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### AsanErrorCallbackSized {#aee567759d4da5f8d324fe83f05b0ab0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{AddressSanitizer.cpp}::AddressSanitizer::AsanErrorCallbackSized[2][2]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 856 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### AsanHandleNoReturnFunc {#a3e81171102c974155d6c46b85f6aba9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{AddressSanitizer.cpp}::AddressSanitizer::AsanHandleNoReturnFunc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 847 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### AsanMemcpy {#a86bcfc36a6b12da22fd39d2ee154b99f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{AddressSanitizer.cpp}::AddressSanitizer::AsanMemcpy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 859 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### AsanMemmove {#a131268669f7ad4dc9f6732a4b11b3132}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{AddressSanitizer.cpp}::AddressSanitizer::AsanMemmove</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 859 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### AsanMemoryAccessCallback {#a2260119a0e81966573b867a72a7495e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{AddressSanitizer.cpp}::AddressSanitizer::AsanMemoryAccessCallback[2][2][kNumberOfAccessSizes]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 853 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### AsanMemoryAccessCallbackSized {#aa79d2163ea5a60441ce1c279dae85092}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{AddressSanitizer.cpp}::AddressSanitizer::AsanMemoryAccessCallbackSized[2][2]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 857 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### AsanMemset {#a8ba4d638bef98aaad74d8c9bba11cf1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{AddressSanitizer.cpp}::AddressSanitizer::AsanMemset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 859 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### AsanPtrCmpFunction {#a11c906fca6e7dfcf53f707a009a26a9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{AddressSanitizer.cpp}::AddressSanitizer::AsanPtrCmpFunction</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 848 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### AsanPtrSubFunction {#a8589c5483007db6c978d45f2122c8260}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{AddressSanitizer.cpp}::AddressSanitizer::AsanPtrSubFunction</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 848 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### AsanShadowGlobal {#a5701ba86e3de2ae24657cf95c79ea191}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant* anonymous{AddressSanitizer.cpp}::AddressSanitizer::AsanShadowGlobal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 849 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### C {#a7c4f608f2e1df0938e81741b299a3ddf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext* anonymous{AddressSanitizer.cpp}::AddressSanitizer::C</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 835 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### CompileKernel {#a122b5e2f48ff4615c234801262cd01a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AddressSanitizer.cpp}::AddressSanitizer::CompileKernel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 839 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### DL {#a448785d72e180f6c2587e1b5642d4645}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout* anonymous{AddressSanitizer.cpp}::AddressSanitizer::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 836 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### InstrumentationWithCallsThreshold {#a3c3e1ca620fa1e446e9b2222c8a0b578}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{AddressSanitizer.cpp}::AddressSanitizer::InstrumentationWithCallsThreshold</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 866 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### Int32Ty {#a4249dd9568f01769c55be3c87f05f075}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* anonymous{AddressSanitizer.cpp}::AddressSanitizer::Int32Ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 844 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### IntptrTy {#a9fec4bfc0d330e5cf68900b623fdd54a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* anonymous{AddressSanitizer.cpp}::AddressSanitizer::IntptrTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 843 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### LocalDynamicShadow {#a09f9778f7a39307358016bba2e40929a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* anonymous{AddressSanitizer.cpp}::AddressSanitizer::LocalDynamicShadow = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 860 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### LongSize {#aa471876e3b35ebd7c8b1e513fe4ec79f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{AddressSanitizer.cpp}::AddressSanitizer::LongSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 838 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### M {#a89cc545f9fe270f29f2efbb0991663e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module&amp; anonymous{AddressSanitizer.cpp}::AddressSanitizer::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 834 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### Mapping {#a1cc8bd72eb748c10a54dd1deb3a823e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ShadowMapping anonymous{AddressSanitizer.cpp}::AddressSanitizer::Mapping</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 846 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### MaxInlinePoisoningSize {#a16a1329918c325821f41dc4f4bd0c18a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t anonymous{AddressSanitizer.cpp}::AddressSanitizer::MaxInlinePoisoningSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 867 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### ProcessedAllocas {#afcf9022da301d296da86d7d824be91a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const AllocaInst *, bool&gt; anonymous{AddressSanitizer.cpp}::AddressSanitizer::ProcessedAllocas</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 862 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### PtrTy {#a5d3042d20c13c4ba7e3578310d08aff3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerType* anonymous{AddressSanitizer.cpp}::AddressSanitizer::PtrTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 845 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### Recover {#adbf72d97d36a991442b801fe8d32f7ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AddressSanitizer.cpp}::AddressSanitizer::Recover</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 840 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### SSGI {#aefb654e803c831c1ed132b20b25ff0ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const StackSafetyGlobalInfo* anonymous{AddressSanitizer.cpp}::AddressSanitizer::SSGI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 861 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### TargetTriple {#ae402906bf8d98003fa463b7675342e75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple anonymous{AddressSanitizer.cpp}::AddressSanitizer::TargetTriple</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 837 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### UseAfterReturn {#a22362f89ee9a3ef30f238ea48d814e11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsanDetectStackUseAfterReturnMode anonymous{AddressSanitizer.cpp}::AddressSanitizer::UseAfterReturn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 842 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### UseAfterScope {#a647cef8d81710b74217afc85bbe68aa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AddressSanitizer.cpp}::AddressSanitizer::UseAfterScope</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 841 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
