---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/regallocpriorityadvisoranalysis
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RegAllocPriorityAdvisorAnalysis` Class



## Declaration

<div class="doxyDeclaration">
class llvm::RegAllocPriorityAdvisorAnalysis { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">CodeGen/RegAllocPriorityAdvisor.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/immutablepass">ImmutablePass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/immutablepass">ImmutablePass</a> class - This class is used to provide information that does not need to be run. <a href="/web-llvm/docs/api/classes/llvm/immutablepass/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/releasemodepriorityadvisoranalysis">ReleaseModePriorityAdvisorAnalysis</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AdvisorMode : int { <a href="#a1deddc62c2392976d25f8854e553266e">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a7d15aec3410da7d0d5d555aba98301">RegAllocPriorityAdvisorAnalysis</a> (AdvisorMode Mode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/regallocpriorityadvisor">RegAllocPriorityAdvisor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f4c9b6d8a72709c186c17043f62df58">getAdvisor</a> (const MachineFunction &amp;MF, const RAGreedy &amp;RA)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an advisor for the given context (i.e. machine function, etc) <a href="#a7f4c9b6d8a72709c186c17043f62df58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1deddc62c2392976d25f8854e553266e">AdvisorMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3365028dc63a24695bc74b60a68e3b7d">getAdvisorMode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44a4fe42c94856368a8232cc4653395f">logRewardIfNeeded</a> (const MachineFunction &amp;MF, llvm::function_ref&lt; float()&gt; GetReward)</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8349e67bcda852a915644c9feb681d1e">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job. <a href="#a8349e67bcda852a915644c9feb681d1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee485e2ed8b641ed3eeadf7fdd998b68">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#aee485e2ed8b641ed3eeadf7fdd998b68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a1deddc62c2392976d25f8854e553266e">AdvisorMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a221fda564b086030eb0404b2b74ead16">Mode</a></td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a269b87ebbd6efe686becfac673d5077a">ID</a> = 0</td>
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


<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### AdvisorMode {#a1deddc62c2392976d25f8854e553266e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::RegAllocPriorityAdvisorAnalysis::AdvisorMode : int</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Default<a id="a1deddc62c2392976d25f8854e553266ea7a1920d61156abc05a60135aefe8bc67"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Release<a id="a1deddc62c2392976d25f8854e553266eab8e7b465df7c5979dc731d06e84ce2cf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Development<a id="a1deddc62c2392976d25f8854e553266ea330f49df8243756a8a4dc7f7f7ee6dfe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Dummy<a id="a1deddc62c2392976d25f8854e553266eabcf036b6f33e182d4705f4f5b1af13ac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### RegAllocPriorityAdvisorAnalysis() {#a0a7d15aec3410da7d0d5d555aba98301}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegAllocPriorityAdvisorAnalysis::RegAllocPriorityAdvisorAnalysis (<a href="#a1deddc62c2392976d25f8854e553266e">AdvisorMode</a> Mode)</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a>.</p>


<p>References <a href="#a269b87ebbd6efe686becfac673d5077a">ID</a> and <a href="/web-llvm/docs/api/classes/llvm/immutablepass/#a4d664099280bb09275254d64c329d25d">llvm::ImmutablePass::ImmutablePass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/releasemodepriorityadvisoranalysis/#a6c47875062ea0e5fefbf84b74022aadd">llvm::ReleaseModePriorityAdvisorAnalysis::classof</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-cpp/#acb4ccb1e3e3e40a5db92d467a97369c6">INITIALIZE_PASS</a> and <a href="/web-llvm/docs/api/classes/llvm/releasemodepriorityadvisoranalysis/#a0b550cfad8280d9f3fa7e876294eefd9">llvm::ReleaseModePriorityAdvisorAnalysis::ReleaseModePriorityAdvisorAnalysis</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAdvisor() {#a7f4c9b6d8a72709c186c17043f62df58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::unique_ptr&lt; RegAllocPriorityAdvisor &gt; llvm::RegAllocPriorityAdvisorAnalysis::getAdvisor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ragreedy">RAGreedy</a> &amp; RA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get an advisor for the given context (i.e. machine function, etc)</p>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp/#a3e47bdb3e296b00df96eff7896fa57bf">RA</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-cpp/#acb4ccb1e3e3e40a5db92d467a97369c6">INITIALIZE_PASS</a>.</p>

</div>
</div>

### getAdvisorMode() {#a3365028dc63a24695bc74b60a68e3b7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AdvisorMode llvm::RegAllocPriorityAdvisorAnalysis::getAdvisorMode ()</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a>.</p>

</div>
</div>

### logRewardIfNeeded() {#a44a4fe42c94856368a8232cc4653395f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::RegAllocPriorityAdvisorAnalysis::logRewardIfNeeded (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/function-ref">llvm::function_ref</a>&lt; float()&gt; GetReward)</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getAnalysisUsage() {#a8349e67bcda852a915644c9feb681d1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RegAllocPriorityAdvisorAnalysis::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job.</p>


<p>If a pass specifies that it uses a particular analysis result to this function, it can then use the <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">getAnalysis&lt;AnalysisType&gt;()</a> function, below.</p>


<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#af22b06a6a4f9df80454071685a0d6a02">llvm::AnalysisUsage::setPreservesAll</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-cpp/#acb4ccb1e3e3e40a5db92d467a97369c6">INITIALIZE_PASS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getPassName() {#aee485e2ed8b641ed3eeadf7fdd998b68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef RegAllocPriorityAdvisorAnalysis::getPassName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getPassName - Return a nice clean name for a pass.</p>


<p>This usually implemented in terms of the name that is registered by one of the Registration templates, but can be overloaded directly.</p>


<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a>, definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-cpp">RegAllocPriorityAdvisor.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Mode {#a221fda564b086030eb0404b2b74ead16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AdvisorMode llvm::RegAllocPriorityAdvisorAnalysis::Mode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a269b87ebbd6efe686becfac673d5077a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char RegAllocPriorityAdvisorAnalysis::ID = 0</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a>.</p>


<p>Referenced by <a href="#a0a7d15aec3410da7d0d5d555aba98301">RegAllocPriorityAdvisorAnalysis</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-cpp">RegAllocPriorityAdvisor.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
