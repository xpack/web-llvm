---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/crashrecoverycontextcleanupregistrar
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CrashRecoveryContextCleanupRegistrar` Class Template Reference

<p>Helper class for managing resource cleanups. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T, typename Cleanup = CrashRecoveryContextDeleteCleanup&lt;T&gt;&gt;
class llvm::CrashRecoveryContextCleanupRegistrar&lt;T, Cleanup&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">llvm/Support/CrashRecoveryContext.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a22b2744432d950424a79cce9424ff02e">CrashRecoveryContextCleanupRegistrar</a> (T *x)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a00e5aae1b2a541afcaf103df3b4eb287">~CrashRecoveryContextCleanupRegistrar</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0cc8485800a00bacc1728815c0dc5220">unregister</a> ()</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontextcleanup">CrashRecoveryContextCleanup</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad04c80cc1170cb83628e552818bd177e">cleanup</a></td>
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

<p>Helper class for managing resource cleanups.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Template Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">T</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> of resource been reclaimed.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Cleanup</td>
<td class="doxyParamItemDescription"><p>Class that defines how the resource is reclaimed.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Clients create objects of this type in the code executed in a crash recovery context to ensure that the resource will be reclaimed even in the case of crash. For example:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> actual_work(</span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> *) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  ...</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  std::unique_ptr&lt;Resource&gt; <a href="/web-llvm/docs/api/namespaces/llvm/riscvfencefield/#a147be9e9780c1e33363ea572d4c7b25fa1835091d83e0e052cd1a32c99b2be731">R</a>(</span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> Resource());</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a22b2744432d950424a79cce9424ff02e">CrashRecoveryContextCleanupRegistrar</a> <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>(<a href="/web-llvm/docs/api/namespaces/llvm/riscvfencefield/#a147be9e9780c1e33363ea572d4c7b25fa1835091d83e0e052cd1a32c99b2be731">R</a>.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  ...</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> foo() {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  CrashRecoveryContext CRC;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!CRC.RunSafely(actual_work, 0)) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">     ... a crash was detected, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/anonymous-memprofreader-cpp-/#a5aa1da33006dea5aabda2768e34787b8">report</a> <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a> to user ...</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>

</div>


<p>If the code of <span class="doxyComputerOutput">actual_work</span> in the example above does not crash, the destructor of <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontextcleanupregistrar">CrashRecoveryContextCleanupRegistrar</a> removes cleanup code from the current <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontext">CrashRecoveryContext</a> and the resource is reclaimed by the destructor of std::unique_ptr. If crash happens, destructors are not called and the resource is reclaimed by cleanup object registered in the recovery context by the constructor of <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontextcleanupregistrar">CrashRecoveryContextCleanupRegistrar</a>.</p>


<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CrashRecoveryContextCleanupRegistrar() {#a22b2744432d950424a79cce9424ff02e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename Cleanup = CrashRecoveryContextDeleteCleanup&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CrashRecoveryContextCleanupRegistrar&lt; T, Cleanup &gt;::CrashRecoveryContextCleanupRegistrar (T * x)</td>
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



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfod/httpclient-cpp/#a0b91b2b50d54e38aa1e8e31e56c31357">Cleanup</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~CrashRecoveryContextCleanupRegistrar() {#a00e5aae1b2a541afcaf103df3b4eb287}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename Cleanup = CrashRecoveryContextDeleteCleanup&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CrashRecoveryContextCleanupRegistrar&lt; T, Cleanup &gt;::~CrashRecoveryContextCleanupRegistrar ()</td>
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



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>.</p>


<p>Reference <a href="#a0cc8485800a00bacc1728815c0dc5220">llvm::CrashRecoveryContextCleanupRegistrar&lt; T, Cleanup &gt;::unregister</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### unregister() {#a0cc8485800a00bacc1728815c0dc5220}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename Cleanup = CrashRecoveryContextDeleteCleanup&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CrashRecoveryContextCleanupRegistrar&lt; T, Cleanup &gt;::unregister ()</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>.</p>


<p>Referenced by <a href="#a00e5aae1b2a541afcaf103df3b4eb287">llvm::CrashRecoveryContextCleanupRegistrar&lt; T, Cleanup &gt;::~CrashRecoveryContextCleanupRegistrar</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### cleanup {#ad04c80cc1170cb83628e552818bd177e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename Cleanup = CrashRecoveryContextDeleteCleanup&lt;T&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CrashRecoveryContextCleanup* llvm::CrashRecoveryContextCleanupRegistrar&lt; T, Cleanup &gt;::cleanup</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crashrecoverycontext-h">CrashRecoveryContext.h</a>.</p>

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
