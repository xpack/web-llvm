---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/crashrecoverycontextdestructorcleanup
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CrashRecoveryContextDestructorCleanup` Class Template Reference

<p>Cleanup handler that reclaims resource by calling destructor on it. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T&gt;
class llvm::CrashRecoveryContextDestructorCleanup&lt;T&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">llvm/Support/CrashRecoveryContext.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontextcleanupbase">CrashRecoveryContextCleanupBase&lt;Derived, T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class of cleanup handler that controls recovery of resources of the given type. <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontextcleanupbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a7b53e58725be5496bb5dbd0acd18bf3e">CrashRecoveryContextDestructorCleanup</a> (CrashRecoveryContext *context, T *resource)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a35db3c84dbd2fa7b27d6d274692b62f2">recoverResources</a> () override</td>
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

<p>Cleanup handler that reclaims resource by calling destructor on it.</p>

<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CrashRecoveryContextDestructorCleanup() {#a7b53e58725be5496bb5dbd0acd18bf3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CrashRecoveryContextDestructorCleanup&lt; T &gt;::CrashRecoveryContextDestructorCleanup (<a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontext">CrashRecoveryContext</a> * context, T * resource)</td>
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



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontextcleanup/#a5ea1b8631bce469d2dd873f1587937be">llvm::CrashRecoveryContextCleanup::context</a>, <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontextcleanupbase/#a2702ec45c2c26d2490fca9818cae9c87">llvm::CrashRecoveryContextCleanupBase&lt; CrashRecoveryContextDestructorCleanup&lt; T &gt;, T &gt;::CrashRecoveryContextCleanupBase</a>, <a href="#a7b53e58725be5496bb5dbd0acd18bf3e">llvm::CrashRecoveryContextDestructorCleanup&lt; T &gt;::CrashRecoveryContextDestructorCleanup</a>, <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontextcleanupbase/#a7409ae4ff379ef98870edae5053de46a">llvm::CrashRecoveryContextCleanupBase&lt; CrashRecoveryContextDestructorCleanup&lt; T &gt;, T &gt;::resource</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a7b53e58725be5496bb5dbd0acd18bf3e">llvm::CrashRecoveryContextDestructorCleanup&lt; T &gt;::CrashRecoveryContextDestructorCleanup</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### recoverResources() {#a35db3c84dbd2fa7b27d6d274692b62f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CrashRecoveryContextDestructorCleanup&lt; T &gt;::recoverResources ()</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontextcleanupbase/#a7409ae4ff379ef98870edae5053de46a">llvm::CrashRecoveryContextCleanupBase&lt; CrashRecoveryContextDestructorCleanup&lt; T &gt;, T &gt;::resource</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
