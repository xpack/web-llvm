---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-crashrecoverycontext-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `anonymous{CrashRecoveryContext.cpp}` Namespace



## Definition

<div class="doxyDefinition">
namespace anonymous{CrashRecoveryContext.cpp} { ... }
</div>

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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mutex &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69566229ae01d190f424f18be453175d">getCrashRecoveryContextMutex</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a793005af6ae802d5a2a2e8ceb4ac2135">LLVM_THREAD_LOCAL</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-crashrecoverycontext-cpp-/crashrecoverycontextimpl">CrashRecoveryContextImpl</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04bd06e1fbf71b7df3cc3b119d9309d1">CurrentContext</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acac7a11d792efcc4ddb07a9b08cc55aa">gCrashRecoveryEnabled</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a793005af6ae802d5a2a2e8ceb4ac2135">LLVM_THREAD_LOCAL</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontext">CrashRecoveryContext</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91ee307a6601945fc93d1a66162326a7">IsRecoveringFromCrash</a></td>
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

### getCrashRecoveryContextMutex() {#a69566229ae01d190f424f18be453175d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex &amp; anonymous{CrashRecoveryContext.cpp}::getCrashRecoveryContextMutex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### CurrentContext {#a04bd06e1fbf71b7df3cc3b119d9309d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_THREAD_LOCAL const CrashRecoveryContextImpl* anonymous{CrashRecoveryContext.cpp}::CurrentContext</td>
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



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-crashrecoverycontext-cpp-/crashrecoverycontextimpl/#a1869eda15bbfbe6a0cc0d58bfc4a81a0">anonymous{CrashRecoveryContext.cpp}::CrashRecoveryContextImpl::CrashRecoveryContextImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-crashrecoverycontext-cpp-/crashrecoverycontextimpl/#a0f8515fbcec00f4cf6990321677ebdbd">anonymous{CrashRecoveryContext.cpp}::CrashRecoveryContextImpl::HandleCrash</a> and <a href="/web-llvm/docs/api/structs/anonymous-crashrecoverycontext-cpp-/crashrecoverycontextimpl/#a4902594b0a34090bff9a747241935ad0">anonymous{CrashRecoveryContext.cpp}::CrashRecoveryContextImpl::~CrashRecoveryContextImpl</a>.</p>

</div>
</div>

### gCrashRecoveryEnabled {#acac7a11d792efcc4ddb07a9b08cc55aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CrashRecoveryContext.cpp}::gCrashRecoveryEnabled = false</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>

</div>
</div>

### IsRecoveringFromCrash {#a91ee307a6601945fc93d1a66162326a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_THREAD_LOCAL const CrashRecoveryContext* anonymous{CrashRecoveryContext.cpp}::IsRecoveringFromCrash</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
