---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-x86winehstate-cpp-/winehstatepass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `WinEHStatePass` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{X86WinEHState.cpp}::WinEHStatePass { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> class - This class is used to implement most global optimizations. <a href="/web-llvm/docs/api/classes/llvm/functionpass/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e48622a153f4df7a3bfa187fec8161b">WinEHStatePass</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbb400505dff72ce49663ae73e4d7399">runOnFunction</a> (Function &amp;Fn) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnFunction - Virtual method overriden by subclasses to do the per-function processing of the pass. <a href="#acbb400505dff72ce49663ae73e4d7399">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1a1abaaac7c3cd7cfef7b48a30694ca">doInitialization</a> (Module &amp;M) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>doInitialization - Virtual method overridden by subclasses to do any necessary initialization before any pass is run. <a href="#ae1a1abaaac7c3cd7cfef7b48a30694ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88663c1c7ad06aa8cfd6e61171a2eea0">doFinalization</a> (Module &amp;M) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>doFinalization - Virtual method overriden by subclasses to do any necessary clean up after all passes have run. <a href="#a88663c1c7ad06aa8cfd6e61171a2eea0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73e99813111e70bd76222e7aed294503">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job. <a href="#a73e99813111e70bd76222e7aed294503">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28818b493f34d768689641df58d9f3a0">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#a28818b493f34d768689641df58d9f3a0">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabb9e60fcb85c2b8be9e59b9da87c509">emitExceptionRegistrationRecord</a> (Function *F)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6531381d3b4c35fa60c5483ec6147eff">linkExceptionRegistration</a> (IRBuilder&lt;&gt; &amp;Builder, Function *Handler)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06e3964eb17e10f8e2cba413dd957a7d">unlinkExceptionRegistration</a> (IRBuilder&lt;&gt; &amp;Builder)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44b995ee686caa7a59ff3a114be3859d">addStateStores</a> (Function &amp;F, WinEHFuncInfo &amp;FuncInfo)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29d491679fc7be97580a431525082022">insertStateNumberStore</a> (Instruction *IP, int State)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16761e3e97ad9aad58997098222b3e26">emitEHLSDA</a> (IRBuilder&lt;&gt; &amp;Builder, Function *F)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7d359cbecb10cd602beea0f1a5a8dc0">generateLSDAInEAXThunk</a> (Function *ParentFunc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate a thunk that puts the LSDA of ParentFunc in EAX and then calls PersonalityFn, forwarding the parameters passed to PEXCEPTION_ROUTINE: typedef _EXCEPTION_DISPOSITION (*PEXCEPTION_ROUTINE)( _EXCEPTION_RECORD *, void *, _CONTEXT *, void *); We essentially want this code: movl $lsda, eax jmpl ___CxxFrameHandler3. <a href="#ae7d359cbecb10cd602beea0f1a5a8dc0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a3ac26f6f5f0711bf9d65ddd33c7d19">isStateStoreNeeded</a> (EHPersonality Personality, CallBase &amp;Call)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc5cf1ccb6e6eacebb6059089b107b1e">rewriteSetJmpCall</a> (IRBuilder&lt;&gt; &amp;Builder, Function &amp;F, CallBase &amp;Call, Value *State)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa82ebd80cde26bc522d7601ff9366397">getBaseStateForBB</a> (DenseMap&lt; BasicBlock *, ColorVector &gt; &amp;BlockColors, WinEHFuncInfo &amp;FuncInfo, BasicBlock *BB)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c27048c04f867f50f03b080111722d5">getStateForCall</a> (DenseMap&lt; BasicBlock *, ColorVector &gt; &amp;BlockColors, WinEHFuncInfo &amp;FuncInfo, CallBase &amp;Call)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32f67080e7572d50e98deb18bb98bab8">updateEspForInAllocas</a> (Function &amp;F)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a871c197580f6ed74803f18db8e3f3546">getEHLinkRegistrationType</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the common EH registration subobject: typedef _EXCEPTION_DISPOSITION (*PEXCEPTION_ROUTINE)( _EXCEPTION_RECORD *, void *, _CONTEXT *, void *); struct EHRegistrationNode { EHRegistrationNode *Next; PEXCEPTION_ROUTINE Handler; };. <a href="#a871c197580f6ed74803f18db8e3f3546">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b61475e87628e0b14b585e2bb1adf08">getSEHRegistrationType</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The _except_handler3/4 registration node: struct EH4ExceptionRegistration { void *SavedESP; _EXCEPTION_POINTERS *ExceptionPointers; EHRegistrationNode SubRecord; int32_t EncodedScopeTable; int32_t TryLevel; };. <a href="#a0b61475e87628e0b14b585e2bb1adf08">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54fe0e994011e9664435096f1940fb70">getCXXEHRegistrationType</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The __CxxFrameHandler3 registration node: struct CXXExceptionRegistration { void *SavedESP; EHRegistrationNode SubRecord; int32_t TryLevel; };. <a href="#a54fe0e994011e9664435096f1940fb70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab75f52a6cd497d1fc616a062047481f2">TheModule</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04b7668f34f02d96ad7c047196e4b27c">EHLinkRegistrationTy</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bf7ee3ab4d09d97b2fbfd1c50c99e97">CXXEHRegistrationTy</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a172303e628de0faefff960d14945cd">SEHRegistrationTy</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4216cb83f8c13e05a0bb5c2a8b7cd8c2">SetJmp3</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5c06c13fad02ad3f2252a6cc1990b0e">CxxLongjmpUnwind</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a5d56157a385f8cd7d3e54ed87da1ba6a">EHPersonality</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefff39dfa612e42bea6817e232da68da">Personality</a> = EHPersonality::Unknown</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17805229da6b27a49f85d6676d7890e3">PersonalityFn</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7574a2d0d3e423f2d5aa3042a312f9c6">UseStackGuard</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5684ae225ed67542065b3f890146ed5a">ParentBaseState</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e3a036a1fdf221c0178eeb4d4e1f17b">SehLongjmpUnwind</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3fde70993d06bbfa0ac4c55ea6d0bf4">Cookie</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5aaf955a91e7b64657ac5bdff2a09b16">RegNode</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The stack allocation containing all EH data, including the link in the fs:00 chain and the current state. <a href="#a5aaf955a91e7b64657ac5bdff2a09b16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ad1c0348dbe7e3a1563ae89fee2b72d">RegNodeTy</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf361b2ff0698ad41b89def647b5a69e">EHGuardNode</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72cb67869d06835b9dd687346dd43151">StateFieldIndex</a> = ~0U</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The index of the state field of RegNode. <a href="#a72cb67869d06835b9dd687346dd43151">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1b0ebcd4f9bbbad856ddb18cb5fc808">Link</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The linked list node subobject inside of RegNode. <a href="#ae1b0ebcd4f9bbbad856ddb18cb5fc808">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ca04e50fa11ab262dec49c3b28786b1">ID</a> = 0</td>
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


<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### WinEHStatePass() {#a0e48622a153f4df7a3bfa187fec8161b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{X86WinEHState.cpp}::WinEHStatePass::WinEHStatePass ()</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/functionpass/#a7691d83e3561f781cae4ce4a01bdfa93">llvm::FunctionPass::FunctionPass</a> and <a href="#a8ca04e50fa11ab262dec49c3b28786b1">ID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0641056a8623d0cbbc16d705395bc75a">llvm::createX86WinEHStatePass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### doFinalization() {#a88663c1c7ad06aa8cfd6e61171a2eea0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WinEHStatePass::doFinalization (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;)</td>
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

<p>doFinalization - Virtual method overriden by subclasses to do any necessary clean up after all passes have run.</p>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#ae1a1abaaac7c3cd7cfef7b48a30694ca">doInitialization</a>.</p>

</div>
</div>

### doInitialization() {#ae1a1abaaac7c3cd7cfef7b48a30694ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86WinEHState.cpp}::WinEHStatePass::doInitialization (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;)</td>
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

<p>doInitialization - Virtual method overridden by subclasses to do any necessary initialization before any pass is run.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>


<p>References <a href="#a88663c1c7ad06aa8cfd6e61171a2eea0">doFinalization</a> and <a href="#a73e99813111e70bd76222e7aed294503">getAnalysisUsage</a>.</p>

</div>
</div>

### getAnalysisUsage() {#a73e99813111e70bd76222e7aed294503}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinEHStatePass::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;)</td>
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

<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job.</p>


<p>If a pass specifies that it uses a particular analysis result to this function, it can then use the <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">getAnalysis&lt;AnalysisType&gt;()</a> function, below.</p>


<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#af11a6ebf7ab3c388234cb6d5378439a3">llvm::AnalysisUsage::setPreservesCFG</a>.</p>


<p>Referenced by <a href="#ae1a1abaaac7c3cd7cfef7b48a30694ca">doInitialization</a>.</p>

</div>
</div>

### getPassName() {#a28818b493f34d768689641df58d9f3a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{X86WinEHState.cpp}::WinEHStatePass::getPassName ()</td>
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

<p>getPassName - Return a nice clean name for a pass.</p>


<p>This usually implemented in terms of the name that is registered by one of the Registration templates, but can be overloaded directly.</p>


<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

### runOnFunction() {#acbb400505dff72ce49663ae73e4d7399}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WinEHStatePass::runOnFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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

<p>runOnFunction - Virtual method overriden by subclasses to do the per-function processing of the pass.</p>

<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8d508f23e2580095561902c39911fb9b">llvm::classifyEHPersonality</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa014490a40c9286ee7e026a2f579eea9">llvm::isFuncletEHPersonality</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5d56157a385f8cd7d3e54ed87da1ba6aa88183b946cc5f0e8c96b2e66e1c74a7e">llvm::Unknown</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addStateStores() {#a44b995ee686caa7a59ff3a114be3859d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinEHStatePass::addStateStores (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/structs/llvm/winehfuncinfo">WinEHFuncInfo</a> &amp; FuncInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

### emitEHLSDA() {#a16761e3e97ad9aad58997098222b3e26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * WinEHStatePass::emitEHLSDA (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

### emitExceptionRegistrationRecord() {#aabb9e60fcb85c2b8be9e59b9da87c509}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinEHStatePass::emitExceptionRegistrationRecord (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

### generateLSDAInEAXThunk() {#ae7d359cbecb10cd602beea0f1a5a8dc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * WinEHStatePass::generateLSDAInEAXThunk (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * ParentFunc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate a thunk that puts the LSDA of ParentFunc in EAX and then calls PersonalityFn, forwarding the parameters passed to PEXCEPTION_ROUTINE: typedef _EXCEPTION_DISPOSITION (*PEXCEPTION_ROUTINE)( _EXCEPTION_RECORD *, void *, _CONTEXT *, void *); We essentially want this code: movl $lsda, eax jmpl ___CxxFrameHandler3.</p>

<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

### getBaseStateForBB() {#aa82ebd80cde26bc522d7601ff9366397}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int WinEHStatePass::getBaseStateForBB (<a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/namespaces/llvm/#ac16c24df0637600996c9c6081da170a2">ColorVector</a> &gt; &amp; BlockColors, <a href="/web-llvm/docs/api/structs/llvm/winehfuncinfo">WinEHFuncInfo</a> &amp; FuncInfo, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

### getCXXEHRegistrationType() {#a54fe0e994011e9664435096f1940fb70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * WinEHStatePass::getCXXEHRegistrationType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The __CxxFrameHandler3 registration node: struct CXXExceptionRegistration { void *SavedESP; EHRegistrationNode SubRecord; int32_t TryLevel; };.</p>

<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

### getEHLinkRegistrationType() {#a871c197580f6ed74803f18db8e3f3546}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * WinEHStatePass::getEHLinkRegistrationType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the common EH registration subobject: typedef _EXCEPTION_DISPOSITION (*PEXCEPTION_ROUTINE)( _EXCEPTION_RECORD *, void *, _CONTEXT *, void *); struct EHRegistrationNode { EHRegistrationNode *Next; PEXCEPTION_ROUTINE Handler; };.</p>

<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

### getSEHRegistrationType() {#a0b61475e87628e0b14b585e2bb1adf08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * WinEHStatePass::getSEHRegistrationType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The _except_handler3/4 registration node: struct EH4ExceptionRegistration { void *SavedESP; _EXCEPTION_POINTERS *ExceptionPointers; EHRegistrationNode SubRecord; int32_t EncodedScopeTable; int32_t TryLevel; };.</p>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

### getStateForCall() {#a0c27048c04f867f50f03b080111722d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int WinEHStatePass::getStateForCall (<a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/namespaces/llvm/#ac16c24df0637600996c9c6081da170a2">ColorVector</a> &gt; &amp; BlockColors, <a href="/web-llvm/docs/api/structs/llvm/winehfuncinfo">WinEHFuncInfo</a> &amp; FuncInfo, <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; Call)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

### insertStateNumberStore() {#a29d491679fc7be97580a431525082022}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinEHStatePass::insertStateNumberStore (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * IP, int State)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

### isStateStoreNeeded() {#a9a3ac26f6f5f0711bf9d65ddd33c7d19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WinEHStatePass::isStateStoreNeeded (<a href="/web-llvm/docs/api/namespaces/llvm/#a5d56157a385f8cd7d3e54ed87da1ba6a">EHPersonality</a> Personality, <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; Call)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

### linkExceptionRegistration() {#a6531381d3b4c35fa60c5483ec6147eff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinEHStatePass::linkExceptionRegistration (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Handler)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

### rewriteSetJmpCall() {#afc5cf1ccb6e6eacebb6059089b107b1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinEHStatePass::rewriteSetJmpCall (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; Call, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * State)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

### unlinkExceptionRegistration() {#a06e3964eb17e10f8e2cba413dd957a7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinEHStatePass::unlinkExceptionRegistration (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

### updateEspForInAllocas() {#a32f67080e7572d50e98deb18bb98bab8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinEHStatePass::updateEspForInAllocas (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Cookie {#aa3fde70993d06bbfa0ac4c55ea6d0bf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant* anonymous{X86WinEHState.cpp}::WinEHStatePass::Cookie = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

### CXXEHRegistrationTy {#a3bf7ee3ab4d09d97b2fbfd1c50c99e97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructType* anonymous{X86WinEHState.cpp}::WinEHStatePass::CXXEHRegistrationTy = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

### CxxLongjmpUnwind {#ab5c06c13fad02ad3f2252a6cc1990b0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{X86WinEHState.cpp}::WinEHStatePass::CxxLongjmpUnwind = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

### EHGuardNode {#aaf361b2ff0698ad41b89def647b5a69e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocaInst* anonymous{X86WinEHState.cpp}::WinEHStatePass::EHGuardNode = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

### EHLinkRegistrationTy {#a04b7668f34f02d96ad7c047196e4b27c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructType* anonymous{X86WinEHState.cpp}::WinEHStatePass::EHLinkRegistrationTy = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

### Link {#ae1b0ebcd4f9bbbad856ddb18cb5fc808}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* anonymous{X86WinEHState.cpp}::WinEHStatePass::Link = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The linked list node subobject inside of RegNode.</p>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

### ParentBaseState {#a5684ae225ed67542065b3f890146ed5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{X86WinEHState.cpp}::WinEHStatePass::ParentBaseState = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

### Personality {#aefff39dfa612e42bea6817e232da68da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EHPersonality anonymous{X86WinEHState.cpp}::WinEHStatePass::Personality = EHPersonality::Unknown</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

### PersonalityFn {#a17805229da6b27a49f85d6676d7890e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* anonymous{X86WinEHState.cpp}::WinEHStatePass::PersonalityFn = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

### RegNode {#a5aaf955a91e7b64657ac5bdff2a09b16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocaInst* anonymous{X86WinEHState.cpp}::WinEHStatePass::RegNode = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The stack allocation containing all EH data, including the link in the fs:00 chain and the current state.</p>

<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

### RegNodeTy {#a8ad1c0348dbe7e3a1563ae89fee2b72d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* anonymous{X86WinEHState.cpp}::WinEHStatePass::RegNodeTy = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

### SehLongjmpUnwind {#a9e3a036a1fdf221c0178eeb4d4e1f17b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{X86WinEHState.cpp}::WinEHStatePass::SehLongjmpUnwind = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

### SEHRegistrationTy {#a0a172303e628de0faefff960d14945cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructType* anonymous{X86WinEHState.cpp}::WinEHStatePass::SEHRegistrationTy = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

### SetJmp3 {#a4216cb83f8c13e05a0bb5c2a8b7cd8c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{X86WinEHState.cpp}::WinEHStatePass::SetJmp3 = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

### StateFieldIndex {#a72cb67869d06835b9dd687346dd43151}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{X86WinEHState.cpp}::WinEHStatePass::StateFieldIndex = ~0U</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The index of the state field of RegNode.</p>

<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

### TheModule {#ab75f52a6cd497d1fc616a062047481f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module* anonymous{X86WinEHState.cpp}::WinEHStatePass::TheModule = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

### UseStackGuard {#a7574a2d0d3e423f2d5aa3042a312f9c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86WinEHState.cpp}::WinEHStatePass::UseStackGuard = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a8ca04e50fa11ab262dec49c3b28786b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char WinEHStatePass::ID = 0</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a>.</p>


<p>Referenced by <a href="#a0e48622a153f4df7a3bfa187fec8161b">WinEHStatePass</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp">X86WinEHState.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
