---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/crashrecoverycontextdeletecleanup
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CrashRecoveryContextDeleteCleanup` Class Template

<p>Cleanup handler that reclaims resource by calling 'delete' on it. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T&gt;
class llvm::CrashRecoveryContextDeleteCleanup&lt;T&gt; { ... }
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
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aca3c8569d6d02ea3024b632d8b3db467">CrashRecoveryContextDeleteCleanup</a> (CrashRecoveryContext *context, T *resource)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ade263e7380db647baa178472cc93be7a">recoverResources</a> () override</td>
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

<p>Cleanup handler that reclaims resource by calling 'delete' on it.</p>

<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CrashRecoveryContextDeleteCleanup() {#aca3c8569d6d02ea3024b632d8b3db467}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CrashRecoveryContextDeleteCleanup&lt; T &gt;::CrashRecoveryContextDeleteCleanup (<a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontext">CrashRecoveryContext</a> * context, T * resource)</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontextcleanup/#a5ea1b8631bce469d2dd873f1587937be">llvm::CrashRecoveryContextCleanup::context</a>, <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontextcleanupbase/#a2702ec45c2c26d2490fca9818cae9c87">llvm::CrashRecoveryContextCleanupBase&lt; CrashRecoveryContextDeleteCleanup&lt; T &gt;, T &gt;::CrashRecoveryContextCleanupBase</a>, <a href="#aca3c8569d6d02ea3024b632d8b3db467">llvm::CrashRecoveryContextDeleteCleanup&lt; T &gt;::CrashRecoveryContextDeleteCleanup</a>, <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontextcleanupbase/#a7409ae4ff379ef98870edae5053de46a">llvm::CrashRecoveryContextCleanupBase&lt; CrashRecoveryContextDeleteCleanup&lt; T &gt;, T &gt;::resource</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#aca3c8569d6d02ea3024b632d8b3db467">llvm::CrashRecoveryContextDeleteCleanup&lt; T &gt;::CrashRecoveryContextDeleteCleanup</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### recoverResources() {#ade263e7380db647baa178472cc93be7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CrashRecoveryContextDeleteCleanup&lt; T &gt;::recoverResources ()</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontextcleanupbase/#a7409ae4ff379ef98870edae5053de46a">llvm::CrashRecoveryContextCleanupBase&lt; CrashRecoveryContextDeleteCleanup&lt; T &gt;, T &gt;::resource</a>.</p>

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
