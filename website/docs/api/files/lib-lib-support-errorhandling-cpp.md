---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/errorhandling-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `ErrorHandling.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/errorhandling-h">llvm-c/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "llvm/Config/config.h"
#include "llvm/Config/llvm-config.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errc-h">llvm/Support/Errc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">llvm/Support/Process.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/signals-h">llvm/Support/Signals.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threading-h">llvm/Support/Threading.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/windowserror-h">llvm/Support/WindowsError.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cassert&gt;
#include &lt;cstdlib&gt;
#include &lt;mutex&gt;
#include &lt;new&gt;
#include &lt;unistd.h&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bf540b19b562677965223f8286d0b75">out_of_memory_new_handler</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bf77e8726f283ee9fa0a48c07a871ee">bindingsErrorHandler</a> (void *user_data, const char *reason, bool gen_crash_diag)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gaf6159e6764fb23072ec25514b90b0ebd">LLVMInstallFatalErrorHandler</a> (LLVMFatalErrorHandler Handler)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Install a fatal error handler. <a href="/web-llvm/docs/api/groups/llvmcerror/#gaf6159e6764fb23072ec25514b90b0ebd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#ga7ea3d621a4b178b39e068f2c017ae617">LLVMResetFatalErrorHandler</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset the fatal error handler. <a href="/web-llvm/docs/api/groups/llvmcerror/#ga7ea3d621a4b178b39e068f2c017ae617">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static fatal_error_handler_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a170a641ca785d873866fb901dfcb7591">ErrorHandler</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac72f654da369115e0c7af8e47be7008c">ErrorHandlerUserData</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static fatal_error_handler_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8da7e4c7ebec27f103c4a756d70a60bb">BadAllocErrorHandler</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0e98715bcea19ec4cc4f15ebf476e32">BadAllocErrorHandlerUserData</a> = nullptr</td>
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

### bindingsErrorHandler() {#a8bf77e8726f283ee9fa0a48c07a871ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void bindingsErrorHandler (void * user_data, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * reason, bool gen_crash_diag)</td>
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



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/support/errorhandling-cpp">ErrorHandling.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa308b4893c1ee3415893491cd9c061d1">LLVM_EXTENSION</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcerror/#gaf6159e6764fb23072ec25514b90b0ebd">LLVMInstallFatalErrorHandler</a>.</p>

</div>
</div>

### out\_of\_memory\_new\_handler() {#a2bf540b19b562677965223f8286d0b75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void out_of_memory_new_handler ()</td>
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



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/support/errorhandling-cpp">ErrorHandling.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#afcd76d92f6ad67759238ccef6ec883af">llvm::report_bad_alloc_error</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a80220d8755a4812455d9bdf5ea315a08">llvm::install_out_of_memory_new_handler</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### BadAllocErrorHandler {#a8da7e4c7ebec27f103c4a756d70a60bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">fatal_error_handler_t BadAllocErrorHandler = nullptr</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/support/errorhandling-cpp">ErrorHandling.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a311f776700d2c293136de3dd6b259c1d">llvm::install_bad_alloc_error_handler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d240012e1f696d78bdc7a9dbd569768">llvm::remove_bad_alloc_error_handler</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#afcd76d92f6ad67759238ccef6ec883af">llvm::report_bad_alloc_error</a>.</p>

</div>
</div>

### BadAllocErrorHandlerUserData {#aa0e98715bcea19ec4cc4f15ebf476e32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* BadAllocErrorHandlerUserData = nullptr</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/support/errorhandling-cpp">ErrorHandling.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a311f776700d2c293136de3dd6b259c1d">llvm::install_bad_alloc_error_handler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d240012e1f696d78bdc7a9dbd569768">llvm::remove_bad_alloc_error_handler</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#afcd76d92f6ad67759238ccef6ec883af">llvm::report_bad_alloc_error</a>.</p>

</div>
</div>

### ErrorHandler {#a170a641ca785d873866fb901dfcb7591}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">fatal_error_handler_t ErrorHandler = nullptr</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/support/errorhandling-cpp">ErrorHandling.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/btfcontext/#a13889029c9c62dd629f63fc3b083752b">llvm::BTFContext::create</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinker/#af85bcc9515e3fea62b968dcfffe6a402">llvm::dwarf_linker::parallel::DWARFLinker::createLinker</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#aaef75f38cdc5c7015fe251728c47c9d9">llvm::dwarf_linker::parallel::DWARFLinkerImpl::DWARFLinkerImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2aeb96bbf49b1dd8f8a6cf1ceb4e86a7">llvm::install_fatal_error_handler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abdb4f14b8a339d669818c3c274d1add3">llvm::remove_fatal_error_handler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66fc8969d714a36fb8b4918753d1b973">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinker/#a4a7f0737ec70ef10abee719dd612fbe3">llvm::dwarf_linker::parallel::DWARFLinker::~DWARFLinker</a>.</p>

</div>
</div>

### ErrorHandlerUserData {#ac72f654da369115e0c7af8e47be7008c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* ErrorHandlerUserData = nullptr</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/support/errorhandling-cpp">ErrorHandling.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a2aeb96bbf49b1dd8f8a6cf1ceb4e86a7">llvm::install_fatal_error_handler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abdb4f14b8a339d669818c3c274d1add3">llvm::remove_fatal_error_handler</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a66fc8969d714a36fb8b4918753d1b973">llvm::report_fatal_error</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
