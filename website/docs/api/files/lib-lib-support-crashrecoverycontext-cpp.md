---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/crashrecoverycontext-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `CrashRecoveryContext.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">llvm/Support/CrashRecoveryContext.h</a>"
#include "llvm/Config/llvm-config.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/exitcodes-h">llvm/Support/ExitCodes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/signals-h">llvm/Support/Signals.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/thread-h">llvm/Support/thread.h</a>"
#include &lt;cassert&gt;
#include &lt;mutex&gt;
#include &lt;setjmp.h&gt;
#include &lt;signal.h&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-crashrecoverycontext-cpp-">anonymous{CrashRecoveryContext.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-crashrecoverycontext-cpp-/crashrecoverycontextimpl">CrashRecoveryContextImpl</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-crashrecoverycontext-cpp-/runsafelyonthreadinfo">RunSafelyOnThreadInfo</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afafe7a6e51a65dc858e161f5f0346eb7">installExceptionOrSignalHandlers</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72432dde4ac5721bf8d78d090a198dc6">uninstallExceptionOrSignalHandlers</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63942c4dec8efd06218370c042a12480">CrashRecoverySignalHandler</a> (int Signal)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e17e622d5d0183f2ef9371caa9a06a7">setThreadBackgroundPriority</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c4e05ef8e440fd1bed2772259584f6d">hasThreadBackgroundPriority</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6741df1ae96240967c1fab2d6668d59a">RunSafelyOnThread_Dispatch</a> (void *UserData)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a610cf56a4e6ab035bbce5e4bd4b35491">Signals</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c9e1adb1243628fba0a85d1679c5408">NumSignals</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">std::size</a>(<a href="#a610cf56a4e6ab035bbce5e4bd4b35491">Signals</a>)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78ca6b94aa2c38681accbf6cfbd577e6">PrevActions</a>[NumSignals]</td>
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


<div class="doxySectionDef">

## Functions

### CrashRecoverySignalHandler() {#a63942c4dec8efd06218370c042a12480}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CrashRecoverySignalHandler (int Signal)</td>
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



<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontext/#a85c3b9e248b6ed94762938f8cac81a49">llvm::CrashRecoveryContext::Disable</a>.</p>


<p>Referenced by <a href="#afafe7a6e51a65dc858e161f5f0346eb7">installExceptionOrSignalHandlers</a>.</p>

</div>
</div>

### hasThreadBackgroundPriority() {#a2c4e05ef8e440fd1bed2772259584f6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasThreadBackgroundPriority ()</td>
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



<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontext/#afdaeace1ba646601aab05b0530f7f1db">llvm::CrashRecoveryContext::RunSafelyOnThread</a>.</p>

</div>
</div>

### installExceptionOrSignalHandlers() {#afafe7a6e51a65dc858e161f5f0346eb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void installExceptionOrSignalHandlers ()</td>
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



<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>References <a href="#a63942c4dec8efd06218370c042a12480">CrashRecoverySignalHandler</a>, <a href="#a2c9e1adb1243628fba0a85d1679c5408">NumSignals</a>, <a href="#a78ca6b94aa2c38681accbf6cfbd577e6">PrevActions</a> and <a href="#a610cf56a4e6ab035bbce5e4bd4b35491">Signals</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontext/#a41167e1234529f6607af068e6c687ac0">llvm::CrashRecoveryContext::Enable</a>.</p>

</div>
</div>

### RunSafelyOnThread\_Dispatch() {#a6741df1ae96240967c1fab2d6668d59a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RunSafelyOnThread_Dispatch (void * UserData)</td>
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



<p>Definition at line 503 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a> and <a href="#a6e17e622d5d0183f2ef9371caa9a06a7">setThreadBackgroundPriority</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontext/#afdaeace1ba646601aab05b0530f7f1db">llvm::CrashRecoveryContext::RunSafelyOnThread</a>.</p>

</div>
</div>

### setThreadBackgroundPriority() {#a6e17e622d5d0183f2ef9371caa9a06a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void setThreadBackgroundPriority ()</td>
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



<p>Definition at line 480 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>Referenced by <a href="#a6741df1ae96240967c1fab2d6668d59a">RunSafelyOnThread_Dispatch</a>.</p>

</div>
</div>

### uninstallExceptionOrSignalHandlers() {#a72432dde4ac5721bf8d78d090a198dc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void uninstallExceptionOrSignalHandlers ()</td>
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



<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>References <a href="#a2c9e1adb1243628fba0a85d1679c5408">NumSignals</a>, <a href="#a78ca6b94aa2c38681accbf6cfbd577e6">PrevActions</a> and <a href="#a610cf56a4e6ab035bbce5e4bd4b35491">Signals</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontext/#a85c3b9e248b6ed94762938f8cac81a49">llvm::CrashRecoveryContext::Disable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### NumSignals {#a2c9e1adb1243628fba0a85d1679c5408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned NumSignals = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">std::size</a>(<a href="#a610cf56a4e6ab035bbce5e4bd4b35491">Signals</a>)</td>
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



<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>Referenced by <a href="#afafe7a6e51a65dc858e161f5f0346eb7">installExceptionOrSignalHandlers</a> and <a href="#a72432dde4ac5721bf8d78d090a198dc6">uninstallExceptionOrSignalHandlers</a>.</p>

</div>
</div>

### PrevActions {#a78ca6b94aa2c38681accbf6cfbd577e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct sigaction PrevActions[NumSignals]</td>
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



<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>Referenced by <a href="#afafe7a6e51a65dc858e161f5f0346eb7">installExceptionOrSignalHandlers</a> and <a href="#a72432dde4ac5721bf8d78d090a198dc6">uninstallExceptionOrSignalHandlers</a>.</p>

</div>
</div>

### Signals {#a610cf56a4e6ab035bbce5e4bd4b35491}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int Signals[]</td>
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
<div class="doxyVerbatim">=
    { SIGABRT, SIGBUS, SIGFPE, SIGILL, SIGSEGV, SIGTRAP }
</div>
</dd>
</dl>

<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>Referenced by <a href="#afafe7a6e51a65dc858e161f5f0346eb7">installExceptionOrSignalHandlers</a> and <a href="#a72432dde4ac5721bf8d78d090a198dc6">uninstallExceptionOrSignalHandlers</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
