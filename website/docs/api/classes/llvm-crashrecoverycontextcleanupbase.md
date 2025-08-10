---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/crashrecoverycontextcleanupbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CrashRecoveryContextCleanupBase` Class Template

<p>Base class of cleanup handler that controls recovery of resources of the given type. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename Derived, typename T&gt;
class llvm::CrashRecoveryContextCleanupBase&lt;Derived, T&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">llvm/Support/CrashRecoveryContext.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontextcleanup">CrashRecoveryContextCleanup</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract base class of cleanup handlers. <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontextcleanup/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a2702ec45c2c26d2490fca9818cae9c87">CrashRecoveryContextCleanupBase</a> (CrashRecoveryContext *context, T *resource)</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7409ae4ff379ef98870edae5053de46a">resource</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static Derived *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9d8431be1392f30d889407188ec4a0c0">create</a> (T *x)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates cleanup handler. <a href="#a9d8431be1392f30d889407188ec4a0c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Base class of cleanup handler that controls recovery of resources of the given type.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Template Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Derived</td>
<td class="doxyParamItemDescription"><p>Class that uses this class as a base.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">T</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> of controlled resource.</p></td>
</tr>
</table>
</dd>
</dl>

<p>This class serves as a base for its template parameter as implied by Curiously Recurring Template <a href="/web-llvm/docs/api/classes/llvm/pattern">Pattern</a>.</p>


<p>This class factors out creation of a cleanup handler. The latter requires knowledge of the current recovery context, which is provided by this class.</p>


<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### CrashRecoveryContextCleanupBase() {#a2702ec45c2c26d2490fca9818cae9c87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CrashRecoveryContextCleanupBase&lt; Derived, T &gt;::CrashRecoveryContextCleanupBase (<a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontext">CrashRecoveryContext</a> * context, T * resource)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontextcleanup/#a5ea1b8631bce469d2dd873f1587937be">llvm::CrashRecoveryContextCleanup::context</a>, <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontextcleanup/#aa21dcf8f6f911c07f904e03e624ab4e0">llvm::CrashRecoveryContextCleanup::CrashRecoveryContext</a>, <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontextcleanup/#a21168cbcae683b16ce8fca5a4104e79e">llvm::CrashRecoveryContextCleanup::CrashRecoveryContextCleanup</a>, <a href="#a7409ae4ff379ef98870edae5053de46a">llvm::CrashRecoveryContextCleanupBase&lt; Derived, T &gt;::resource</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### resource {#a7409ae4ff379ef98870edae5053de46a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T* llvm::CrashRecoveryContextCleanupBase&lt; Derived, T &gt;::resource</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>.</p>


<p>Referenced by <a href="#a2702ec45c2c26d2490fca9818cae9c87">llvm::CrashRecoveryContextCleanupBase&lt; Derived, T &gt;::CrashRecoveryContextCleanupBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#a9d8431be1392f30d889407188ec4a0c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Derived * llvm::CrashRecoveryContextCleanupBase&lt; Derived, T &gt;::create (T * x)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates cleanup handler.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">x</td>
<td class="doxyParamItemDescription"><p>Pointer to the resource recovered by this handler.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>New handler or null if the method was called outside a recovery context.</p></dd>
</dl>


<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontextcleanup/#a5ea1b8631bce469d2dd873f1587937be">llvm::CrashRecoveryContextCleanup::context</a>, <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontextcleanup/#aa21dcf8f6f911c07f904e03e624ab4e0">llvm::CrashRecoveryContextCleanup::CrashRecoveryContext</a>, <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontext/#a105fa65624c954b0a44d73615cbbeba1">llvm::CrashRecoveryContext::GetCurrent</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
