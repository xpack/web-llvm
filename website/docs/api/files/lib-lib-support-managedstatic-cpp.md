---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/managedstatic-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `ManagedStatic.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/managedstatic-h">llvm/Support/ManagedStatic.h</a>"
#include "llvm/Config/config.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threading-h">llvm/Support/Threading.h</a>"
#include &lt;cassert&gt;
#include &lt;mutex&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::recursive_mutex *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0abfe48f6977bc7312df534c0916feda">getManagedStaticMutex</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/managedstaticbase">ManagedStaticBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b09c6b05b45efd4853fa743e908d9b1">StaticList</a> = nullptr</td>
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

### getManagedStaticMutex() {#a0abfe48f6977bc7312df534c0916feda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::recursive_mutex * getManagedStaticMutex ()</td>
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



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/support/managedstatic-cpp">ManagedStatic.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/managedstaticbase/#a0455c2e6ef911ce3116fceb21d68c44c">llvm::ManagedStaticBase::RegisterManagedStatic</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### StaticList {#a2b09c6b05b45efd4853fa743e908d9b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ManagedStaticBase* StaticList = nullptr</td>
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



<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/support/managedstatic-cpp">ManagedStatic.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/managedstaticbase/#ac73eaf69bd83e867f9ad27fc7251b79c">llvm::ManagedStaticBase::destroy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac27f7fe6f1543ef516aa0998bad20335">llvm::llvm_shutdown</a> and <a href="/web-llvm/docs/api/classes/llvm/managedstaticbase/#a0455c2e6ef911ce3116fceb21d68c44c">llvm::ManagedStaticBase::RegisterManagedStatic</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
