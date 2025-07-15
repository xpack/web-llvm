---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/detail/abisupportimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ABISupportImpl` Class Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;typename ORCABI&gt;
class llvm::orc::detail::ABISupportImpl&lt;ORCABI&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">llvm/ExecutionEngine/Orc/EPCIndirectionUtils.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/epcindirectionutils/abisupport">ABISupport</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ABI support base class. <a href="/web-llvm/docs/api/classes/llvm/orc/epcindirectionutils/abisupport/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ORCABI&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ae7e17656fb0eca8765dde96cabd9c176">ABISupportImpl</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ORCABI&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab676d1d6e07b2182de3f69e80da56e56">writeResolverCode</a> (char *ResolverWorkingMem, ExecutorAddr ResolverTargetAddr, ExecutorAddr ReentryFnAddr, ExecutorAddr ReentryCtxAddr) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ORCABI&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a710cd2aa2fd3b3a20e3af974af9a12c7">writeTrampolines</a> (char *TrampolineBlockWorkingMem, ExecutorAddr TrampolineBlockTargetAddr, ExecutorAddr ResolverAddr, unsigned NumTrampolines) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ORCABI&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8d69be6ba0ba6be255d42054e9f1fd63">writeIndirectStubsBlock</a> (char *StubsBlockWorkingMem, ExecutorAddr StubsBlockTargetAddress, ExecutorAddr PointersBlockTargetAddress, unsigned NumStubs) const override</td>
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


<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ABISupportImpl() {#ae7e17656fb0eca8765dde96cabd9c176}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ORCABI&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::detail::ABISupportImpl&lt; ORCABI &gt;::ABISupportImpl ()</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/orc/epcindirectionutils/abisupport/#a2d118a2e895b534eade2213697a80197">llvm::orc::EPCIndirectionUtils::ABISupport::ABISupport</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### writeIndirectStubsBlock() {#a8d69be6ba0ba6be255d42054e9f1fd63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ORCABI&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::detail::ABISupportImpl&lt; ORCABI &gt;::writeIndirectStubsBlock (char * StubsBlockWorkingMem, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> StubsBlockTargetAddress, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> PointersBlockTargetAddress, unsigned NumStubs)</td>
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



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>.</p>

</div>
</div>

### writeResolverCode() {#ab676d1d6e07b2182de3f69e80da56e56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ORCABI&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::detail::ABISupportImpl&lt; ORCABI &gt;::writeResolverCode (char * ResolverWorkingMem, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> ResolverTargetAddr, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> ReentryFnAddr, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> ReentryCtxAddr)</td>
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



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>.</p>

</div>
</div>

### writeTrampolines() {#a710cd2aa2fd3b3a20e3af974af9a12c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ORCABI&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::detail::ABISupportImpl&lt; ORCABI &gt;::writeTrampolines (char * TrampolineBlockWorkingMem, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> TrampolineBlockTargetAddr, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> ResolverAddr, unsigned NumTrampolines)</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
