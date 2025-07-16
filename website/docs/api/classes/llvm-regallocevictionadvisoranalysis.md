---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/regallocevictionadvisoranalysis
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RegAllocEvictionAdvisorAnalysis` Class Reference

<p>ImmutableAnalysis abstraction for fetching the Eviction Advisor. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::RegAllocEvictionAdvisorAnalysis { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">CodeGen/RegAllocEvictionAdvisor.h</a>"
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AdvisorMode : int { <a href="#a02472e81dfeca389aba455abdef60a09">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a569f300915b37b41ea6be1f09ec7c0af">RegAllocEvictionAdvisorAnalysis</a> (AdvisorMode Mode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/regallocevictionadvisor">RegAllocEvictionAdvisor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5482596d863d8c79a9fbbedc54ebd65">getAdvisor</a> (const MachineFunction &amp;MF, const RAGreedy &amp;RA)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an advisor for the given context (i.e. machine function, etc) <a href="#ae5482596d863d8c79a9fbbedc54ebd65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a02472e81dfeca389aba455abdef60a09">AdvisorMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a316e648b5902dd3cd7c450353a757f51">getAdvisorMode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af85a271d5272cd8436126e7954862f30">logRewardIfNeeded</a> (const MachineFunction &amp;MF, llvm::function_ref&lt; float()&gt; GetReward)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a005390fe88a690353da791886d6c1dcd">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job. <a href="#a005390fe88a690353da791886d6c1dcd">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d266c6510cfb84292f6e4fa2e1b4c74">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#a2d266c6510cfb84292f6e4fa2e1b4c74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a02472e81dfeca389aba455abdef60a09">AdvisorMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8202d84422235f0eea575ebc2174705f">Mode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aade7de0efd531765acebabd803cb4509">ID</a> = 0</td>
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

<p>ImmutableAnalysis abstraction for fetching the Eviction Advisor.</p>


<p>We model it as an analysis to decouple the user from the implementation insofar as dependencies on other analyses goes. The motivation for it being an immutable pass is twofold:</p>


<ul class="doxyList ">
<li>in the ML implementation case, the evaluator is stateless but (especially in the development mode) expensive to set up. With an immutable pass, we set it up once.</li>
<li>in the 'development' mode ML case, we want to capture the training log during allocation (this is a log of features encountered and decisions made), and then measure a score, potentially a few steps after allocation completes. So we need the properties of an immutable pass to keep the logger state around until we can make that measurement.</li>
</ul>

<p>Because we need to offer additional services in 'development' mode, the implementations of this analysis need to implement RTTI support.</p>


<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### AdvisorMode {#a02472e81dfeca389aba455abdef60a09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::RegAllocEvictionAdvisorAnalysis::AdvisorMode : int</td>
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
<td class="doxyEnumItemName">Default<a id="a02472e81dfeca389aba455abdef60a09a7a1920d61156abc05a60135aefe8bc67"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Release<a id="a02472e81dfeca389aba455abdef60a09ab8e7b465df7c5979dc731d06e84ce2cf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Development<a id="a02472e81dfeca389aba455abdef60a09a330f49df8243756a8a4dc7f7f7ee6dfe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### RegAllocEvictionAdvisorAnalysis() {#a569f300915b37b41ea6be1f09ec7c0af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegAllocEvictionAdvisorAnalysis::RegAllocEvictionAdvisorAnalysis (<a href="#a02472e81dfeca389aba455abdef60a09">AdvisorMode</a> Mode)</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>.</p>


<p>References <a href="#aade7de0efd531765acebabd803cb4509">ID</a> and <a href="/web-llvm/docs/api/classes/llvm/immutablepass/#a4d664099280bb09275254d64c329d25d">llvm::ImmutablePass::ImmutablePass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#a9b33d70eb77e44e553ac5aa79a3da589">INITIALIZE_PASS</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/mlregallocevictadvisor-cpp/#a4035cde766164dedab4604c02b29e045">INITIALIZE_PASS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAdvisor() {#ae5482596d863d8c79a9fbbedc54ebd65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::unique_ptr&lt; RegAllocEvictionAdvisor &gt; llvm::RegAllocEvictionAdvisorAnalysis::getAdvisor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ragreedy">RAGreedy</a> &amp; RA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get an advisor for the given context (i.e. machine function, etc)</p>

<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp/#a3e47bdb3e296b00df96eff7896fa57bf">RA</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#a9b33d70eb77e44e553ac5aa79a3da589">INITIALIZE_PASS</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/mlregallocevictadvisor-cpp/#a4035cde766164dedab4604c02b29e045">INITIALIZE_PASS</a>.</p>

</div>
</div>

### getAdvisorMode() {#a316e648b5902dd3cd7c450353a757f51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AdvisorMode llvm::RegAllocEvictionAdvisorAnalysis::getAdvisorMode ()</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>.</p>

</div>
</div>

### logRewardIfNeeded() {#af85a271d5272cd8436126e7954862f30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::RegAllocEvictionAdvisorAnalysis::logRewardIfNeeded (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/function-ref">llvm::function_ref</a>&lt; float()&gt; GetReward)</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/mlregallocevictadvisor-cpp/#a4035cde766164dedab4604c02b29e045">INITIALIZE_PASS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getAnalysisUsage() {#a005390fe88a690353da791886d6c1dcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RegAllocEvictionAdvisorAnalysis::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;)</td>
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


<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#af22b06a6a4f9df80454071685a0d6a02">llvm::AnalysisUsage::setPreservesAll</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/mlregallocevictadvisor-cpp/#a4035cde766164dedab4604c02b29e045">INITIALIZE_PASS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getPassName() {#a2d266c6510cfb84292f6e4fa2e1b4c74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef RegAllocEvictionAdvisorAnalysis::getPassName ()</td>
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


<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>, definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp">RegAllocEvictionAdvisor.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Mode {#a8202d84422235f0eea575ebc2174705f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AdvisorMode llvm::RegAllocEvictionAdvisorAnalysis::Mode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#aade7de0efd531765acebabd803cb4509}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char RegAllocEvictionAdvisorAnalysis::ID = 0</td>
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



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a>.</p>


<p>Referenced by <a href="#a569f300915b37b41ea6be1f09ec7c0af">RegAllocEvictionAdvisorAnalysis</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp">RegAllocEvictionAdvisor.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-h">RegAllocEvictionAdvisor.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
