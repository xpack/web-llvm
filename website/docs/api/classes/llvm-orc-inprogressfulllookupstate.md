---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/inprogressfulllookupstate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `InProgressFullLookupState` Class



## Declaration

<div class="doxyDeclaration">
class llvm::orc::InProgressFullLookupState { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/inprogresslookupstate">InProgressLookupState</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b257d3ba2ff9d7ff38169bd8d35e0d8">InProgressFullLookupState</a> (LookupKind K, JITDylibSearchOrder SearchOrder, SymbolLookupSet LookupSet, SymbolState RequiredState, std::shared_ptr&lt; AsynchronousSymbolQuery &gt; Q, RegisterDependenciesFunction RegisterDependencies)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43d9a7a382ce864e1483f1d7587a5b28">complete</a> (std::unique_ptr&lt; InProgressLookupState &gt; IPLS) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44313e74357c376d23acf0c64eaf60ec">fail</a> (Error Err) override</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/asynchronoussymbolquery">AsynchronousSymbolQuery</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e1b18a72852c159503f9849cb43ccca">Q</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc/#a417b487970e79367118330a5587c8775">RegisterDependenciesFunction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a180dcdd8191976b33b33fa2d04990c3e">RegisterDependencies</a></td>
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


<p>Definition at line 564 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InProgressFullLookupState() {#a0b257d3ba2ff9d7ff38169bd8d35e0d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::InProgressFullLookupState::InProgressFullLookupState (<a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac17672ae6b70c781cc77713e88d698eb">LookupKind</a> K, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1a2b573da544cf233d62075a16146245">JITDylibSearchOrder</a> SearchOrder, <a href="/web-llvm/docs/api/classes/llvm/orc/symbollookupset">SymbolLookupSet</a> LookupSet, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#adac25fca9fb14b1defe43d18a81c16e8">SymbolState</a> RequiredState, std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/asynchronoussymbolquery">AsynchronousSymbolQuery</a> &gt; Q, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a417b487970e79367118330a5587c8775">RegisterDependenciesFunction</a> RegisterDependencies)</td>
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



<p>Definition at line 566 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/inprogresslookupstate/#aa2ef112a937cb6eb9bfc76ddeb5f14b7">llvm::orc::InProgressLookupState::InProgressLookupState</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/inprogresslookupstate/#a0503b098d8f706ceb3011e07018b1e20">llvm::orc::InProgressLookupState::K</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/inprogresslookupstate/#a67a1ee8aa73eb8d7753631bbb90cd4ff">llvm::orc::InProgressLookupState::LookupSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/inprogresslookupstate/#aa7827c12c8d1ab12601ed84b26bfb9ba">llvm::orc::InProgressLookupState::RequiredState</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/inprogresslookupstate/#a34a45b05b610fd64d9e88300a988d2f4">llvm::orc::InProgressLookupState::SearchOrder</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### complete() {#a43d9a7a382ce864e1483f1d7587a5b28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::InProgressFullLookupState::complete (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/inprogresslookupstate">InProgressLookupState</a> &gt; IPLS)</td>
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



<p>Definition at line 576 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/orc/inprogresslookupstate/#a34a45b05b610fd64d9e88300a988d2f4">llvm::orc::InProgressLookupState::SearchOrder</a>.</p>

</div>
</div>

### fail() {#a44313e74357c376d23acf0c64eaf60ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::InProgressFullLookupState::fail (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> Err)</td>
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



<p>Definition at line 582 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Q {#a2e1b18a72852c159503f9849cb43ccca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt;AsynchronousSymbolQuery&gt; llvm::orc::InProgressFullLookupState::Q</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 588 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### RegisterDependencies {#a180dcdd8191976b33b33fa2d04990c3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterDependenciesFunction llvm::orc::InProgressFullLookupState::RegisterDependencies</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 589 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/core-cpp">Core.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
