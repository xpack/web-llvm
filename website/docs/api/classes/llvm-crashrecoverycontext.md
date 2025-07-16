---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/crashrecoverycontext
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CrashRecoveryContext` Class Reference

<p>Crash recovery helper object. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::CrashRecoveryContext { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">llvm/Support/CrashRecoveryContext.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9b65412e2f06422a5500e533cb3982d">CrashRecoveryContext</a> ()</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f1b3ccc1138c2449277d1605297bd23">~CrashRecoveryContext</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfd8df959280984cf865bc8690aa1386">registerCleanup</a> (CrashRecoveryContextCleanup *cleanup)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> cleanup handler, which is used when the recovery context is finished. <a href="#acfd8df959280984cf865bc8690aa1386">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79b3815988da0ba38acabefe15082e8a">unregisterCleanup</a> (CrashRecoveryContextCleanup *cleanup)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a27e5f3ab2b30dd6b1ef4c8d7e9e5a4">RunSafely</a> (function_ref&lt; void()&gt; Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Execute the provided callback function (with the given arguments) in a protected context. <a href="#a7a27e5f3ab2b30dd6b1ef4c8d7e9e5a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad65753a7501ff93f2d9248bc8bfb165f">RunSafely</a> (void(*Fn)(void *), void *UserData)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdaeace1ba646601aab05b0530f7f1db">RunSafelyOnThread</a> (function_ref&lt; void()&gt;, unsigned RequestedStackSize=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Execute the provide callback function (with the given arguments) in a protected context which is run in another thread (optionally with a requested stack size). <a href="#afdaeace1ba646601aab05b0530f7f1db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac160f3b79b873eec4c682721901a2f50">RunSafelyOnThread</a> (void(*Fn)(void *), void *UserData, unsigned RequestedStackSize=0)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37a76700bffd3d25b09e7828fa90277c">HandleExit</a> (int RetCode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Explicitly trigger a crash recovery in the current process, and return failure from <a href="#a7a27e5f3ab2b30dd6b1ef4c8d7e9e5a4">RunSafely()</a>. <a href="#a37a76700bffd3d25b09e7828fa90277c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa79c730e28c1406ada1243fae0e0358d">RetCode</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>In case of a crash, this is the crash identifier. <a href="#aa79c730e28c1406ada1243fae0e0358d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77f0ee6230e867e6e35366aba64a325f">DumpStackAndCleanupOnFailure</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Selects whether handling of failures should be done in the same way as for regular crashes. <a href="#a77f0ee6230e867e6e35366aba64a325f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a8821f156af38038e6160792bd74e4e">Impl</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontextcleanup">CrashRecoveryContextCleanup</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ac4fbc116d1e9911f656419fb84e600">head</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41167e1234529f6607af068e6c687ac0">Enable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable crash recovery. <a href="#a41167e1234529f6607af068e6c687ac0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85c3b9e248b6ed94762938f8cac81a49">Disable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disable crash recovery. <a href="#a85c3b9e248b6ed94762938f8cac81a49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontext">CrashRecoveryContext</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a105fa65624c954b0a44d73615cbbeba1">GetCurrent</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the active context, if the code is currently executing in a thread which is in a protected context. <a href="#a105fa65624c954b0a44d73615cbbeba1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa970a6de6e7146a147b195bb0609559c">isRecoveringFromCrash</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the current thread is recovering from a crash. <a href="#aa970a6de6e7146a147b195bb0609559c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cd4fbb22cd917e20bb699958b4339b2">isCrash</a> (int RetCode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if RetCode indicates that a signal or an exception occurred. <a href="#a0cd4fbb22cd917e20bb699958b4339b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbecc705fe2dd65984b0839e756d1f9a">throwIfCrash</a> (int RetCode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Throw again a signal or an exception, after it was catched once by a <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontext">CrashRecoveryContext</a>. <a href="#abbecc705fe2dd65984b0839e756d1f9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Crash recovery helper object.</p>


<p>This class implements support for running operations in a safe context so that crashes (memory errors, stack overflow, assertion violations) can be detected and control restored to the crashing thread. Crash detection is purely "best effort", the exact set of failures which can be recovered from is platform dependent.</p>


<p>Clients make use of this code by first calling <a href="#a41167e1234529f6607af068e6c687ac0">CrashRecoveryContext::Enable()</a>, and then executing unsafe operations via a <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontext">CrashRecoveryContext</a> object. For example:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> actual_work(</span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> *);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> foo() {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af9b65412e2f06422a5500e533cb3982d">CrashRecoveryContext</a> CRC;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!CRC.RunSafely(actual_work, 0)) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">     ... a crash was detected, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/anonymous-memprofreader-cpp-/#a5aa1da33006dea5aabda2768e34787b8">report</a> <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a> to user ...</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  ... no crash was detected ...</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>To assist recovery the class allows specifying set of actions that will be executed in any case, whether crash occurs or not. These actions may be used to reclaim resources in the case of crash.</p>


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CrashRecoveryContext() {#af9b65412e2f06422a5500e533cb3982d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CrashRecoveryContext::CrashRecoveryContext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>, definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a3dda14c3980f644b8796c1a51d7bf11b">llvm::sys::DisableSystemDialogsOnCrash</a>.</p>


<p>Referenced by <a href="#a105fa65624c954b0a44d73615cbbeba1">GetCurrent</a> and <a href="#a3f1b3ccc1138c2449277d1605297bd23">~CrashRecoveryContext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~CrashRecoveryContext() {#a3f1b3ccc1138c2449277d1605297bd23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CrashRecoveryContext::~CrashRecoveryContext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>, definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontextcleanup/#aca39a957a0440233d0cb1be95f18d6e0">llvm::CrashRecoveryContextCleanup::cleanupFired</a>, <a href="#af9b65412e2f06422a5500e533cb3982d">CrashRecoveryContext</a> and <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontextcleanup/#a78fd4542f4d45c47c5a7c0110827e461">llvm::CrashRecoveryContextCleanup::recoverResources</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### HandleExit() {#a37a76700bffd3d25b09e7828fa90277c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CrashRecoveryContext::HandleExit (int RetCode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Explicitly trigger a crash recovery in the current process, and return failure from <a href="#a7a27e5f3ab2b30dd6b1ef4c8d7e9e5a4">RunSafely()</a>.</p>


<p>This function does not return.</p>


<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>, definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="#aa79c730e28c1406ada1243fae0e0358d">RetCode</a>.</p>

</div>
</div>

### registerCleanup() {#acfd8df959280984cf865bc8690aa1386}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CrashRecoveryContext::registerCleanup (<a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontextcleanup">CrashRecoveryContextCleanup</a> * cleanup)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> cleanup handler, which is used when the recovery context is finished.</p>


<p>The recovery context owns the handler.</p>


<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>, definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfoimpl-cpp/#a3419f1e4b5a20b3ec28ae5f1f3c6f32b">cleanup</a>.</p>

</div>
</div>

### RunSafely() {#a7a27e5f3ab2b30dd6b1ef4c8d7e9e5a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CrashRecoveryContext::RunSafely (<a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void()&gt; Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Execute the provided callback function (with the given arguments) in a protected context.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the function completed successfully, and false if the function crashed (or HandleCrash was called explicitly). Clients should make as little assumptions as possible about the program state when RunSafely has returned false.</p></dd>
</dl>


<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>, definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#ad65753a7501ff93f2d9248bc8bfb165f">RunSafely</a>.</p>

</div>
</div>

### RunSafely() {#ad65753a7501ff93f2d9248bc8bfb165f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CrashRecoveryContext::RunSafely (void(*)(void *) Fn, void * UserData)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>.</p>


<p>Reference <a href="#a7a27e5f3ab2b30dd6b1ef4c8d7e9e5a4">RunSafely</a>.</p>

</div>
</div>

### RunSafelyOnThread() {#afdaeace1ba646601aab05b0530f7f1db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CrashRecoveryContext::RunSafelyOnThread (<a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void()&gt; Fn, unsigned RequestedStackSize=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Execute the provide callback function (with the given arguments) in a protected context which is run in another thread (optionally with a requested stack size).</p>


<p>See <a href="#a7a27e5f3ab2b30dd6b1ef4c8d7e9e5a4">RunSafely()</a>.</p>


<p>On Darwin, if PRIO_DARWIN_BG is set on the calling thread, it will be propagated to the new thread as well.</p>


<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>, definition at line 512 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp/#a2c4e05ef8e440fd1bed2772259584f6d">hasThreadBackgroundPriority</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp/#a6741df1ae96240967c1fab2d6668d59a">RunSafelyOnThread_Dispatch</a>.</p>


<p>Referenced by <a href="#ac160f3b79b873eec4c682721901a2f50">RunSafelyOnThread</a>.</p>

</div>
</div>

### RunSafelyOnThread() {#ac160f3b79b873eec4c682721901a2f50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CrashRecoveryContext::RunSafelyOnThread (void(*)(void *) Fn, void * UserData, unsigned RequestedStackSize=0)</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>.</p>


<p>Reference <a href="#afdaeace1ba646601aab05b0530f7f1db">RunSafelyOnThread</a>.</p>

</div>
</div>

### unregisterCleanup() {#a79b3815988da0ba38acabefe15082e8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CrashRecoveryContext::unregisterCleanup (<a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontextcleanup">CrashRecoveryContextCleanup</a> * cleanup)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>, definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfoimpl-cpp/#a3419f1e4b5a20b3ec28ae5f1f3c6f32b">cleanup</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DumpStackAndCleanupOnFailure {#a77f0ee6230e867e6e35366aba64a325f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CrashRecoveryContext::DumpStackAndCleanupOnFailure = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Selects whether handling of failures should be done in the same way as for regular crashes.</p>


<p>When this is active, a crash would print the callstack, clean-up any temporary files and create a coredump/minidump.</p>


<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>.</p>

</div>
</div>

### RetCode {#aa79c730e28c1406ada1243fae0e0358d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::CrashRecoveryContext::RetCode = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>In case of a crash, this is the crash identifier.</p>

<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>.</p>


<p>Referenced by <a href="#a37a76700bffd3d25b09e7828fa90277c">HandleExit</a>, <a href="#a0cd4fbb22cd917e20bb699958b4339b2">isCrash</a> and <a href="#abbecc705fe2dd65984b0839e756d1f9a">throwIfCrash</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### head {#a8ac4fbc116d1e9911f656419fb84e600}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CrashRecoveryContextCleanup* llvm::CrashRecoveryContext::head = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>.</p>

</div>
</div>

### Impl {#a3a8821f156af38038e6160792bd74e4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* llvm::CrashRecoveryContext::Impl = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### Disable() {#a85c3b9e248b6ed94762938f8cac81a49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CrashRecoveryContext::Disable ()</td>
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

<p>Disable crash recovery.</p>

<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>, definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp/#a72432dde4ac5721bf8d78d090a198dc6">uninstallExceptionOrSignalHandlers</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp/#a63942c4dec8efd06218370c042a12480">CrashRecoverySignalHandler</a>.</p>

</div>
</div>

### Enable() {#a41167e1234529f6607af068e6c687ac0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CrashRecoveryContext::Enable ()</td>
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

<p>Enable crash recovery.</p>

<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>, definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp/#afafe7a6e51a65dc858e161f5f0346eb7">installExceptionOrSignalHandlers</a>.</p>

</div>
</div>

### GetCurrent() {#a105fa65624c954b0a44d73615cbbeba1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CrashRecoveryContext * CrashRecoveryContext::GetCurrent ()</td>
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

<p>Return the active context, if the code is currently executing in a thread which is in a protected context.</p>

<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>, definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>References <a href="#af9b65412e2f06422a5500e533cb3982d">CrashRecoveryContext</a> and <a href="/web-llvm/docs/api/structs/anonymous-crashrecoverycontext-cpp-/crashrecoverycontextimpl/#a1fc9ad48d561ba2a8fb7c6eac1e26304">anonymous{CrashRecoveryContext.cpp}::CrashRecoveryContextImpl::CRC</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontextcleanupbase/#a9d8431be1392f30d889407188ec4a0c0">llvm::CrashRecoveryContextCleanupBase&lt; Derived, T &gt;::create</a> and <a href="/web-llvm/docs/api/classes/llvm/sys/process/#a38ee110d150d9b436e4d01405bd7f1a9">llvm::sys::Process::Exit</a>.</p>

</div>
</div>

### isCrash() {#a0cd4fbb22cd917e20bb699958b4339b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CrashRecoveryContext::isCrash (int RetCode)</td>
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

<p>Return true if RetCode indicates that a signal or an exception occurred.</p>

<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>, definition at line 449 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>Reference <a href="#aa79c730e28c1406ada1243fae0e0358d">RetCode</a>.</p>


<p>Referenced by <a href="#abbecc705fe2dd65984b0839e756d1f9a">throwIfCrash</a>.</p>

</div>
</div>

### isRecoveringFromCrash() {#aa970a6de6e7146a147b195bb0609559c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CrashRecoveryContext::isRecoveringFromCrash ()</td>
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

<p>Return true if the current thread is recovering from a crash.</p>

<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>, definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>

</div>
</div>

### throwIfCrash() {#abbecc705fe2dd65984b0839e756d1f9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CrashRecoveryContext::throwIfCrash (int RetCode)</td>
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

<p>Throw again a signal or an exception, after it was catched once by a <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontext">CrashRecoveryContext</a>.</p>

<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>, definition at line 467 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>References <a href="#a0cd4fbb22cd917e20bb699958b4339b2">isCrash</a>, <a href="#aa79c730e28c1406ada1243fae0e0358d">RetCode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a80109dae9b24e661ea7fbff184ced3da">llvm::sys::unregisterHandlers</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
