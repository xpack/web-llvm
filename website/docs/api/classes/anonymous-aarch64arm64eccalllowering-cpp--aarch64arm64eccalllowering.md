---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AArch64Arm64ECCallLowering` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/modulepass">ModulePass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/modulepass">ModulePass</a> class - This class is used to implement unstructured interprocedural optimizations and analyses. <a href="/web-llvm/docs/api/classes/llvm/modulepass/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ed0ce49492f441faef4ff3eda95feef">AArch64Arm64ECCallLowering</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac134215053dd186eca7bdd553eabc68c">buildExitThunk</a> (FunctionType *FnTy, AttributeList Attrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a101a4250b1fd5a230a766de2a14cb271">buildEntryThunk</a> (Function *F)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7791efd93b12280fdad994fb6073933d">lowerCall</a> (CallBase *CB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7990af2ca325a18286d49b694c835c98">buildGuestExitThunk</a> (Function *F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f27dda1e68a24fab4b3ed4a9cfc0e7c">buildPatchableThunk</a> (GlobalAlias *UnmangledAlias, GlobalAlias *MangledAlias)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a471ef961ae64095de93c59dea0a3262f">processFunction</a> (Function &amp;F, SetVector&lt; GlobalValue * &gt; &amp;DirectCalledFns, DenseMap&lt; GlobalAlias *, GlobalAlias * &gt; &amp;FnsMap)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b0a136ac6a10743ef5d3cbc1ee0190e">runOnModule</a> (Module &amp;M) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnModule - Virtual method overriden by subclasses to process the module being operated on. <a href="#a7b0a136ac6a10743ef5d3cbc1ee0190e">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5d727c11773090e2d544de17d3e4a52">getThunkType</a> (FunctionType *FT, AttributeList AttrList, Arm64ECThunkType TT, raw_ostream &amp;Out, FunctionType *&amp;Arm64Ty, FunctionType *&amp;X64Ty, SmallVector&lt; ThunkArgTranslation &gt; &amp;ArgTranslations)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7826eddb43238e85df64e685e7409e8b">getThunkRetType</a> (FunctionType *FT, AttributeList AttrList, raw_ostream &amp;Out, Type *&amp;Arm64RetTy, Type *&amp;X64RetTy, SmallVectorImpl&lt; Type * &gt; &amp;Arm64ArgTypes, SmallVectorImpl&lt; Type * &gt; &amp;X64ArgTypes, SmallVector&lt; ThunkArgTranslation &gt; &amp;ArgTranslations, bool &amp;HasSretPtr)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a337cc0249b5bb2b22e423145f167ba0e">getThunkArgTypes</a> (FunctionType *FT, AttributeList AttrList, Arm64ECThunkType TT, raw_ostream &amp;Out, SmallVectorImpl&lt; Type * &gt; &amp;Arm64ArgTypes, SmallVectorImpl&lt; Type * &gt; &amp;X64ArgTypes, SmallVectorImpl&lt; ThunkArgTranslation &gt; &amp;ArgTranslations, bool HasSretPtr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-aarch64arm64eccalllowering-cpp-/thunkarginfo">ThunkArgInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a823917f99c3040652b4fcefe3a50b733">canonicalizeThunkType</a> (Type *T, Align Alignment, bool Ret, uint64_t ArgSizeBytes, raw_ostream &amp;Out)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33a4f57825c53d7ebe74d56810b581a9">cfguard_module_flag</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b0c0067cbd87d99ac5f3df0820f325d">GuardFnType</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a024ae70bd47eb5de12dc58b966e8424b">GuardFnPtrType</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47456c4caacc157e9bd763d5f80afb46">DispatchFnType</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaca0a7a70ba8eac6d7ca916cbf2563e">DispatchFnPtrType</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04e59f36fe6318523aa91882cae7ad85">GuardFnCFGlobal</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecb00297670106b8cf1a006b9418e228">GuardFnGlobal</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73404834af7a9fc03a061cf3ed8c3a03">DispatchFnGlobal</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f44ab3d46d6b7257eef4e78b373f323">M</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8071f609e79101fcd08e60c32263b3bb">PtrTy</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9067920ac136c9ceea5441206b94aeb1">I64Ty</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06b3923a520e241f51ffce8028add8c6">VoidTy</a></td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cfd5aff2bec223cd6100ca7eaf231cb">ID</a> = 0</td>
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


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64arm64eccalllowering-cpp">AArch64Arm64ECCallLowering.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AArch64Arm64ECCallLowering() {#a8ed0ce49492f441faef4ff3eda95feef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::AArch64Arm64ECCallLowering ()</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64arm64eccalllowering-cpp">AArch64Arm64ECCallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#a7cfd5aff2bec223cd6100ca7eaf231cb">ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4e5b0febbb4d15587bb9a3fb24d5e6cf">llvm::initializeAArch64Arm64ECCallLoweringPass</a> and <a href="/web-llvm/docs/api/classes/llvm/modulepass/#a723659a08d210f4f566887bda3f9f976">llvm::ModulePass::ModulePass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64arm64eccalllowering-cpp/#aacc28ff27759d26e74d37a78470ce0b7">INITIALIZE_PASS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### buildEntryThunk() {#a101a4250b1fd5a230a766de2a14cb271}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * AArch64Arm64ECCallLowering::buildEntryThunk (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64arm64eccalllowering-cpp">AArch64Arm64ECCallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4caf80cc3a71c40926e6c35a60ccdc6428e">llvm::CallingConv::ARM64EC_Thunk_X64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64arm64eccalllowering-cpp-/#a90d5de758d7bbed5750d7f8756efd59ea8e0d8fd987857f4309346ef8d456f262">anonymous{AArch64Arm64ECCallLowering.cpp}::Bitcast</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a05d7aedbbdc0fd24e8bc27edfe9c603f">llvm::Function::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1b30cd686a320a8e5cb4532fd3a552a8">llvm::IRBuilderBase::CreateAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5b416a8603ccb844165c8df22454ac05">llvm::IRBuilderBase::CreatePtrAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5d0c52ee1cde6421f98c193e0e42b97d">llvm::IRBuilderBase::CreateRet</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa6536556982b7e6e2e5884e471f3ce6b">llvm::IRBuilderBase::CreateRetVoid</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aabfc20af4dcf7d94262824dcac2e7bed">llvm::IRBuilderBase::CreateStore</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64arm64eccalllowering-cpp-/#a90d5de758d7bbed5750d7f8756efd59ea2ae40416f6380618d5b202ac553d6bdc">anonymous{AArch64Arm64ECCallLowering.cpp}::Direct</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ae7629a0652411dc2be61aea4fee2b39caadd024eaaab0666500593f30456bbc43">llvm::COFF::Entry</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a73f286a780fbb8c82c0a8574540719ea">llvm::IRBuilderBase::getInt64</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a1e415dc42f391c1d0cfcc1c28c00b2f4">llvm::FunctionType::getParamType</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#ad65790aa94dd4678a1d339d8304e1965">llvm::FunctionType::getReturnType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ae8eaa0b4eeac52a2b2282cb1bfd981ae">llvm::Type::isVoidTy</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caf2b592edf18170e7aff4e8f3bae3360c">llvm::GlobalValue::LinkOnceODRLinkage</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64arm64eccalllowering-cpp-/#a90d5de758d7bbed5750d7f8756efd59ead1f6023b9a6528d5f52dc7de2650be19">anonymous{AArch64Arm64ECCallLowering.cpp}::PointerIndirection</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#a7b0a136ac6a10743ef5d3cbc1ee0190e">runOnModule</a>.</p>

</div>
</div>

### buildExitThunk() {#ac134215053dd186eca7bdd553eabc68c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * AArch64Arm64ECCallLowering::buildExitThunk (<a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * FnTy, <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> Attrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64arm64eccalllowering-cpp">AArch64Arm64ECCallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca047fefb5017b2873eb2e88f1a27fb14a">llvm::CallingConv::ARM64EC_Thunk_Native</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4caf80cc3a71c40926e6c35a60ccdc6428e">llvm::CallingConv::ARM64EC_Thunk_X64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64arm64eccalllowering-cpp-/#a90d5de758d7bbed5750d7f8756efd59ea8e0d8fd987857f4309346ef8d456f262">anonymous{AArch64Arm64ECCallLowering.cpp}::Bitcast</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a05d7aedbbdc0fd24e8bc27edfe9c603f">llvm::Function::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1b30cd686a320a8e5cb4532fd3a552a8">llvm::IRBuilderBase::CreateAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5d0c52ee1cde6421f98c193e0e42b97d">llvm::IRBuilderBase::CreateRet</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa6536556982b7e6e2e5884e471f3ce6b">llvm::IRBuilderBase::CreateRetVoid</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aabfc20af4dcf7d94262824dcac2e7bed">llvm::IRBuilderBase::CreateStore</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64arm64eccalllowering-cpp-/#a90d5de758d7bbed5750d7f8756efd59ea2ae40416f6380618d5b202ac553d6bdc">anonymous{AArch64Arm64ECCallLowering.cpp}::Direct</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ae7629a0652411dc2be61aea4fee2b39cacd4cef2a5a26efd5d75ecca95bc6ff24">llvm::COFF::Exit</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a31e2db8d1b315202d2c19e711b5365fd">llvm::IRBuilderBase::getIntNTy</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a104d6154321899b53e40455e71d8e83a">llvm::FunctionType::getNumParams</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#ad65790aa94dd4678a1d339d8304e1965">llvm::FunctionType::getReturnType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ae8eaa0b4eeac52a2b2282cb1bfd981ae">llvm::Type::isVoidTy</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caf2b592edf18170e7aff4e8f3bae3360c">llvm::GlobalValue::LinkOnceODRLinkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a05d5616e1422394b4d350c008b0cc5e0">llvm::FunctionType::param_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#aeae69a459419ec0bb738cdc73f4fc2a1">llvm::FunctionType::param_end</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64arm64eccalllowering-cpp-/#a90d5de758d7bbed5750d7f8756efd59ead1f6023b9a6528d5f52dc7de2650be19">anonymous{AArch64Arm64ECCallLowering.cpp}::PointerIndirection</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a19010bf2388f505d1262e23f9f87a813">llvm::zip_equal</a>.</p>


<p>Referenced by <a href="#a7990af2ca325a18286d49b694c835c98">buildGuestExitThunk</a>, <a href="#a3f27dda1e68a24fab4b3ed4a9cfc0e7c">buildPatchableThunk</a>, <a href="#a7791efd93b12280fdad994fb6073933d">lowerCall</a> and <a href="#a7b0a136ac6a10743ef5d3cbc1ee0190e">runOnModule</a>.</p>

</div>
</div>

### buildGuestExitThunk() {#a7990af2ca325a18286d49b694c835c98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * AArch64Arm64ECCallLowering::buildGuestExitThunk (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64arm64eccalllowering-cpp">AArch64Arm64ECCallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#ac134215053dd186eca7bdd553eabc68c">buildExitThunk</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca3f8227288993442d6f4a0bb234c9bc5b">llvm::CallingConv::CFGuard_Check</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a05d7aedbbdc0fd24e8bc27edfe9c603f">llvm::Function::Create</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#affbb7e2e9ad8d18114816f2443d672b9">llvm::MDString::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0cc2ab42606e3b20a8746fa57c046ae8">llvm::getArm64ECMangledFunctionName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ae7629a0652411dc2be61aea4fee2b39ca7404e0873ae6dcd0018aa365c1b61029">llvm::COFF::GuestExit</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a0851b4de29686e9c3918449b054cfada">llvm::CallBase::setCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#ad682514c13f12f1a8d759d422fce6aefa2c3fc2c37f5db1dd777fad4e0d33ec7e">llvm::CallInst::TCK_MustTail</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca696bb1c9b0b0e76bb70c61f68866452a">llvm::GlobalValue::WeakODRLinkage</a>.</p>


<p>Referenced by <a href="#a7b0a136ac6a10743ef5d3cbc1ee0190e">runOnModule</a>.</p>

</div>
</div>

### buildPatchableThunk() {#a3f27dda1e68a24fab4b3ed4a9cfc0e7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * AArch64Arm64ECCallLowering::buildPatchableThunk (<a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a> * UnmangledAlias, <a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a> * MangledAlias)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64arm64eccalllowering-cpp">AArch64Arm64ECCallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#ac134215053dd186eca7bdd553eabc68c">buildExitThunk</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca3f8227288993442d6f4a0bb234c9bc5b">llvm::CallingConv::CFGuard_Check</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a05d7aedbbdc0fd24e8bc27edfe9c603f">llvm::Function::Create</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a7666cc7bd9294c7ae9992c41c591e08b">llvm::GlobalAlias::getAliasee</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ae7629a0652411dc2be61aea4fee2b39ca7404e0873ae6dcd0018aa365c1b61029">llvm::COFF::GuestExit</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a629a9b41f0b6dfa91f5b0a7ac34f2d1a">llvm::GlobalAlias::setAliasee</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a0851b4de29686e9c3918449b054cfada">llvm::CallBase::setCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#ad682514c13f12f1a8d759d422fce6aefa2c3fc2c37f5db1dd777fad4e0d33ec7e">llvm::CallInst::TCK_MustTail</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca696bb1c9b0b0e76bb70c61f68866452a">llvm::GlobalValue::WeakODRLinkage</a>.</p>


<p>Referenced by <a href="#a7b0a136ac6a10743ef5d3cbc1ee0190e">runOnModule</a>.</p>

</div>
</div>

### lowerCall() {#a7791efd93b12280fdad994fb6073933d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64Arm64ECCallLowering::lowerCall (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64arm64eccalllowering-cpp">AArch64Arm64ECCallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#ac134215053dd186eca7bdd553eabc68c">buildExitThunk</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca3f8227288993442d6f4a0bb234c9bc5b">llvm::CallingConv::CFGuard_Check</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ae0c55761fce39dd71617690b04385193">llvm::CallBase::getAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a8d13199cbf4d080d3b5dcf330dad5d2c">llvm::CallBase::getCalledOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac3c35bd078a268a207f607d0f57dadba">llvm::CallBase::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4ba3a5be6c0e9b9e8a525de055836733">llvm::Instruction::getModule</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a23ab5f34fb7b9476d45da0102ecbfae6">llvm::CallBase::getOperandBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a6b882824580b4666f692474ecbae56ad">llvm::Module::getTargetTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2fbfe5377a984518a7c03d8558df726d">llvm::CallBase::hasFnAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a7736bfc4c1afef875ecf02f2a7701fe3">llvm::Triple::isOSWindows</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a44d727ac5fccf852bfb2bae3e06adc9ca8997c6b0930e2c05209e95e7172c6cf3">llvm::LLVMContext::OB_funclet</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ad70fe60b7ed052c6a74863944b518251">llvm::CallBase::setCalledOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#a0851b4de29686e9c3918449b054cfada">llvm::CallBase::setCallingConv</a>.</p>


<p>Referenced by <a href="#a471ef961ae64095de93c59dea0a3262f">processFunction</a>.</p>

</div>
</div>

### processFunction() {#a471ef961ae64095de93c59dea0a3262f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64Arm64ECCallLowering::processFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * &gt; &amp; DirectCalledFns, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a> *, <a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a> * &gt; &amp; FnsMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64arm64eccalllowering-cpp">AArch64Arm64ECCallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4caf80cc3a71c40926e6c35a60ccdc6428e">llvm::CallingConv::ARM64EC_Thunk_X64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#affbb7e2e9ad8d18114816f2443d672b9">llvm::MDString::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0cc2ab42606e3b20a8746fa57c046ae8">llvm::getArm64ECMangledFunctionName</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="#a7791efd93b12280fdad994fb6073933d">lowerCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64arm64eccalllowering-cpp/#a079a08ba8e62d90d8a2d789fde93633b">LowerDirectToIndirect</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a886094eaed7ce32029ea52a641142b88">llvm::to_vector</a>.</p>


<p>Referenced by <a href="#a7b0a136ac6a10743ef5d3cbc1ee0190e">runOnModule</a>.</p>

</div>
</div>

### runOnModule() {#a7b0a136ac6a10743ef5d3cbc1ee0190e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64Arm64ECCallLowering::runOnModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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

<p>runOnModule - Virtual method overriden by subclasses to process the module being operated on.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64arm64eccalllowering-cpp">AArch64Arm64ECCallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca047fefb5017b2873eb2e88f1a27fb14a">llvm::CallingConv::ARM64EC_Thunk_Native</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4caf80cc3a71c40926e6c35a60ccdc6428e">llvm::CallingConv::ARM64EC_Thunk_X64</a>, <a href="#a101a4250b1fd5a230a766de2a14cb271">buildEntryThunk</a>, <a href="#ac134215053dd186eca7bdd553eabc68c">buildExitThunk</a>, <a href="#a7990af2ca325a18286d49b694c835c98">buildGuestExitThunk</a>, <a href="#a3f27dda1e68a24fab4b3ed4a9cfc0e7c">buildPatchableThunk</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a8a638534b520f72ab7f2c886da739a6c">llvm::GlobalAlias::create</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6948096330886cc831391c75adbadaf8a5354f0f932438b7ec4d5d82d4ec1ae22">llvm::GlobalValue::DefaultStorageClass</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6948096330886cc831391c75adbadaf8a81819441fb6de420d4290ac79aaf9dc0">llvm::GlobalValue::DLLExportStorageClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ae7629a0652411dc2be61aea4fee2b39caadd024eaaab0666500593f30456bbc43">llvm::COFF::Entry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ae7629a0652411dc2be61aea4fee2b39cacd4cef2a5a26efd5d75ecca95bc6ff24">llvm::COFF::Exit</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">llvm::GlobalValue::ExternalLinkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#a86397deb1d9d25f7a17ce22c4d66482f">llvm::mdconst::extract_or_null</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64arm64eccalllowering-cpp/#a7108745163cc6894b9a0e9c9430a48b8">GenerateThunks</a>, <a href="/web-llvm/docs/api/classes/llvm/arraytype/#a309fed0882f9d27038ff2df2afed7a00">llvm::ArrayType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantarray/#a0900dacdc7ad8e3ea0cc92993c7fd422">llvm::ConstantArray::get</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#affbb7e2e9ad8d18114816f2443d672b9">llvm::MDString::get</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#a8d7f800be5fd53dcfcdcbdc6fd9ccfe3">llvm::PointerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantstruct/#ab154936bb49a215c32bdbd18254fc477">llvm::ConstantStruct::getAnon</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0cc2ab42606e3b20a8746fa57c046ae8">llvm::getArm64ECMangledFunctionName</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ae79d05dd3d0b05e080e08f8c5c33f880">llvm::ConstantExpr::getBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a6e20e76960d952de088354cbcd14c3ab">llvm::Type::getVoidTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ae7629a0652411dc2be61aea4fee2b39ca7404e0873ae6dcd0018aa365c1b61029">llvm::COFF::GuestExit</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caf2b592edf18170e7aff4e8f3bae3360c">llvm::GlobalValue::LinkOnceODRLinkage</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a4aca2bf0c649ae08d5627e350bb80eb6">Mod</a>, <a href="#a471ef961ae64095de93c59dea0a3262f">processFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### canonicalizeThunkType() {#a823917f99c3040652b4fcefe3a50b733}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThunkArgInfo AArch64Arm64ECCallLowering::canonicalizeThunkType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, bool Ret, uint64_t ArgSizeBytes, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64arm64eccalllowering-cpp">AArch64Arm64ECCallLowering.cpp</a>.</p>

</div>
</div>

### getThunkArgTypes() {#a337cc0249b5bb2b22e423145f167ba0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64Arm64ECCallLowering::getThunkArgTypes (<a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * FT, <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> AttrList, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ae7629a0652411dc2be61aea4fee2b39c">Arm64ECThunkType</a> TT, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; &amp; Arm64ArgTypes, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; &amp; X64ArgTypes, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64arm64eccalllowering-cpp-/#a90d5de758d7bbed5750d7f8756efd59e">ThunkArgTranslation</a> &gt; &amp; ArgTranslations, bool HasSretPtr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64arm64eccalllowering-cpp">AArch64Arm64ECCallLowering.cpp</a>.</p>

</div>
</div>

### getThunkRetType() {#a7826eddb43238e85df64e685e7409e8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64Arm64ECCallLowering::getThunkRetType (<a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * FT, <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> AttrList, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *&amp; Arm64RetTy, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *&amp; X64RetTy, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; &amp; Arm64ArgTypes, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; &amp; X64ArgTypes, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64arm64eccalllowering-cpp-/#a90d5de758d7bbed5750d7f8756efd59e">ThunkArgTranslation</a> &gt; &amp; ArgTranslations, bool &amp; HasSretPtr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64arm64eccalllowering-cpp">AArch64Arm64ECCallLowering.cpp</a>.</p>

</div>
</div>

### getThunkType() {#aa5d727c11773090e2d544de17d3e4a52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64Arm64ECCallLowering::getThunkType (<a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * FT, <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> AttrList, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ae7629a0652411dc2be61aea4fee2b39c">Arm64ECThunkType</a> TT, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *&amp; Arm64Ty, <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *&amp; X64Ty, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64arm64eccalllowering-cpp-/#a90d5de758d7bbed5750d7f8756efd59e">ThunkArgTranslation</a> &gt; &amp; ArgTranslations)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64arm64eccalllowering-cpp">AArch64Arm64ECCallLowering.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### cfguard\_module\_flag {#a33a4f57825c53d7ebe74d56810b581a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::cfguard_module_flag = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64arm64eccalllowering-cpp">AArch64Arm64ECCallLowering.cpp</a>.</p>

</div>
</div>

### DispatchFnGlobal {#a73404834af7a9fc03a061cf3ed8c3a03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant* anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::DispatchFnGlobal = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64arm64eccalllowering-cpp">AArch64Arm64ECCallLowering.cpp</a>.</p>

</div>
</div>

### DispatchFnPtrType {#aeaca0a7a70ba8eac6d7ca916cbf2563e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerType* anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::DispatchFnPtrType = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64arm64eccalllowering-cpp">AArch64Arm64ECCallLowering.cpp</a>.</p>

</div>
</div>

### DispatchFnType {#a47456c4caacc157e9bd763d5f80afb46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType* anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::DispatchFnType = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64arm64eccalllowering-cpp">AArch64Arm64ECCallLowering.cpp</a>.</p>

</div>
</div>

### GuardFnCFGlobal {#a04e59f36fe6318523aa91882cae7ad85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant* anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::GuardFnCFGlobal = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64arm64eccalllowering-cpp">AArch64Arm64ECCallLowering.cpp</a>.</p>

</div>
</div>

### GuardFnGlobal {#aecb00297670106b8cf1a006b9418e228}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant* anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::GuardFnGlobal = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64arm64eccalllowering-cpp">AArch64Arm64ECCallLowering.cpp</a>.</p>

</div>
</div>

### GuardFnPtrType {#a024ae70bd47eb5de12dc58b966e8424b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerType* anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::GuardFnPtrType = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64arm64eccalllowering-cpp">AArch64Arm64ECCallLowering.cpp</a>.</p>

</div>
</div>

### GuardFnType {#a5b0c0067cbd87d99ac5f3df0820f325d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType* anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::GuardFnType = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64arm64eccalllowering-cpp">AArch64Arm64ECCallLowering.cpp</a>.</p>

</div>
</div>

### I64Ty {#a9067920ac136c9ceea5441206b94aeb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::I64Ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64arm64eccalllowering-cpp">AArch64Arm64ECCallLowering.cpp</a>.</p>

</div>
</div>

### M {#a9f44ab3d46d6b7257eef4e78b373f323}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module* anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::M = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64arm64eccalllowering-cpp">AArch64Arm64ECCallLowering.cpp</a>.</p>

</div>
</div>

### PtrTy {#a8071f609e79101fcd08e60c32263b3bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::PtrTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64arm64eccalllowering-cpp">AArch64Arm64ECCallLowering.cpp</a>.</p>

</div>
</div>

### VoidTy {#a06b3923a520e241f51ffce8028add8c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::VoidTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64arm64eccalllowering-cpp">AArch64Arm64ECCallLowering.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a7cfd5aff2bec223cd6100ca7eaf231cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char AArch64Arm64ECCallLowering::ID = 0</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64arm64eccalllowering-cpp">AArch64Arm64ECCallLowering.cpp</a>.</p>


<p>Referenced by <a href="#a8ed0ce49492f441faef4ff3eda95feef">AArch64Arm64ECCallLowering</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64arm64eccalllowering-cpp">AArch64Arm64ECCallLowering.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
