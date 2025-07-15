---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-crashrecoverycontext-cpp-/crashrecoverycontextimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CrashRecoveryContextImpl` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{CrashRecoveryContext.cpp}::CrashRecoveryContextImpl { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1869eda15bbfbe6a0cc0d58bfc4a81a0">CrashRecoveryContextImpl</a> (CrashRecoveryContext *CRC) noexcept</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4902594b0a34090bff9a747241935ad0">~CrashRecoveryContextImpl</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09c5e7dcb5555b5088bf3f86b3375672">setSwitchedThread</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called when the separate crash-recovery thread was finished, to indicate that we don't need to clear the thread-local CurrentContext. <a href="#a09c5e7dcb5555b5088bf3f86b3375672">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f8515fbcec00f4cf6990321677ebdbd">HandleCrash</a> (int RetCode, uintptr_t Context)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-crashrecoverycontext-cpp-/crashrecoverycontextimpl">CrashRecoveryContextImpl</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94c0fd5a8b423857291b1ba6d49f41a8">Next</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontext">CrashRecoveryContext</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fc9ad48d561ba2a8fb7c6eac1e26304">CRC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">::jmp_buf</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac05b69ddefb0a3d22a4146f23f4857a0">JumpBuffer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">volatile unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe3b2dc63d72670464e9e11c5a572281">Failed</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34ed1abd912873bd2cefec539f2ca343">SwitchedThread</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5e5c79b37f5b8e3a2e936bf6ffe9ea3">ValidJumpBuffer</a></td>
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


<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CrashRecoveryContextImpl() {#a1869eda15bbfbe6a0cc0d58bfc4a81a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CrashRecoveryContext.cpp}::CrashRecoveryContextImpl::CrashRecoveryContextImpl (<a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontext">CrashRecoveryContext</a> * CRC)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel noexcept">noexcept</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>References <a href="#a1fc9ad48d561ba2a8fb7c6eac1e26304">CRC</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-crashrecoverycontext-cpp-/#a04bd06e1fbf71b7df3cc3b119d9309d1">anonymous{CrashRecoveryContext.cpp}::CurrentContext</a>, <a href="#a94c0fd5a8b423857291b1ba6d49f41a8">Next</a>, <a href="#a34ed1abd912873bd2cefec539f2ca343">SwitchedThread</a> and <a href="#aa5e5c79b37f5b8e3a2e936bf6ffe9ea3">ValidJumpBuffer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~CrashRecoveryContextImpl() {#a4902594b0a34090bff9a747241935ad0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CrashRecoveryContext.cpp}::CrashRecoveryContextImpl::~CrashRecoveryContextImpl ()</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-crashrecoverycontext-cpp-/#a04bd06e1fbf71b7df3cc3b119d9309d1">anonymous{CrashRecoveryContext.cpp}::CurrentContext</a>, <a href="#a94c0fd5a8b423857291b1ba6d49f41a8">Next</a> and <a href="#a34ed1abd912873bd2cefec539f2ca343">SwitchedThread</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### HandleCrash() {#a0f8515fbcec00f4cf6990321677ebdbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CrashRecoveryContext.cpp}::CrashRecoveryContextImpl::HandleCrash (int RetCode, uintptr_t Context)</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#ad01be72a9c0cb2dc4c676aa0057a9b31">llvm::sys::CleanupOnSignal</a>, <a href="#a1fc9ad48d561ba2a8fb7c6eac1e26304">CRC</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-crashrecoverycontext-cpp-/#a04bd06e1fbf71b7df3cc3b119d9309d1">anonymous{CrashRecoveryContext.cpp}::CurrentContext</a>, <a href="#afe3b2dc63d72670464e9e11c5a572281">Failed</a>, <a href="#ac05b69ddefb0a3d22a4146f23f4857a0">JumpBuffer</a>, <a href="#a94c0fd5a8b423857291b1ba6d49f41a8">Next</a> and <a href="#aa5e5c79b37f5b8e3a2e936bf6ffe9ea3">ValidJumpBuffer</a>.</p>

</div>
</div>

### setSwitchedThread() {#a09c5e7dcb5555b5088bf3f86b3375672}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CrashRecoveryContext.cpp}::CrashRecoveryContextImpl::setSwitchedThread ()</td>
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

<p>Called when the separate crash-recovery thread was finished, to indicate that we don't need to clear the thread-local CurrentContext.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>Reference <a href="#a34ed1abd912873bd2cefec539f2ca343">SwitchedThread</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CRC {#a1fc9ad48d561ba2a8fb7c6eac1e26304}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CrashRecoveryContext* anonymous{CrashRecoveryContext.cpp}::CrashRecoveryContextImpl::CRC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>Referenced by <a href="#a1869eda15bbfbe6a0cc0d58bfc4a81a0">CrashRecoveryContextImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontext/#a105fa65624c954b0a44d73615cbbeba1">llvm::CrashRecoveryContext::GetCurrent</a> and <a href="#a0f8515fbcec00f4cf6990321677ebdbd">HandleCrash</a>.</p>

</div>
</div>

### Failed {#afe3b2dc63d72670464e9e11c5a572281}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">volatile unsigned anonymous{CrashRecoveryContext.cpp}::CrashRecoveryContextImpl::Failed</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>Referenced by <a href="#a0f8515fbcec00f4cf6990321677ebdbd">HandleCrash</a>.</p>

</div>
</div>

### JumpBuffer {#ac05b69ddefb0a3d22a4146f23f4857a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">::jmp_buf anonymous{CrashRecoveryContext.cpp}::CrashRecoveryContextImpl::JumpBuffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>Referenced by <a href="#a0f8515fbcec00f4cf6990321677ebdbd">HandleCrash</a>.</p>

</div>
</div>

### Next {#a94c0fd5a8b423857291b1ba6d49f41a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CrashRecoveryContextImpl* anonymous{CrashRecoveryContext.cpp}::CrashRecoveryContextImpl::Next</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>Referenced by <a href="#a1869eda15bbfbe6a0cc0d58bfc4a81a0">CrashRecoveryContextImpl</a>, <a href="#a0f8515fbcec00f4cf6990321677ebdbd">HandleCrash</a> and <a href="#a4902594b0a34090bff9a747241935ad0">~CrashRecoveryContextImpl</a>.</p>

</div>
</div>

### SwitchedThread {#a34ed1abd912873bd2cefec539f2ca343}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{CrashRecoveryContext.cpp}::CrashRecoveryContextImpl::SwitchedThread</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>Referenced by <a href="#a1869eda15bbfbe6a0cc0d58bfc4a81a0">CrashRecoveryContextImpl</a>, <a href="#a09c5e7dcb5555b5088bf3f86b3375672">setSwitchedThread</a> and <a href="#a4902594b0a34090bff9a747241935ad0">~CrashRecoveryContextImpl</a>.</p>

</div>
</div>

### ValidJumpBuffer {#aa5e5c79b37f5b8e3a2e936bf6ffe9ea3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{CrashRecoveryContext.cpp}::CrashRecoveryContextImpl::ValidJumpBuffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a>.</p>


<p>Referenced by <a href="#a1869eda15bbfbe6a0cc0d58bfc4a81a0">CrashRecoveryContextImpl</a> and <a href="#a0f8515fbcec00f4cf6990321677ebdbd">HandleCrash</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp">CrashRecoveryContext.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
