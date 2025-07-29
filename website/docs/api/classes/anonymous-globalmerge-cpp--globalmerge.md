---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-globalmerge-cpp-/globalmerge
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GlobalMerge` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{GlobalMerge.cpp}::GlobalMerge { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> class - This class is used to implement most global optimizations. <a href="/web-llvm/docs/api/classes/llvm/functionpass/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92cb5e0ddb6f9c0ddacb9a9b791977af">GlobalMerge</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cf1070f862ab357580f5b924f603f97">GlobalMerge</a> (const TargetMachine *TM, unsigned MaximalOffset, bool OnlyOptimizeForSize, bool MergeExternalGlobals, bool MergeConstantGlobals, bool MergeConstAggressive)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe9c261f5762d1873822f0635616e14e">doInitialization</a> (Module &amp;M) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>doInitialization - Virtual method overridden by subclasses to do any necessary initialization before any pass is run. <a href="#abe9c261f5762d1873822f0635616e14e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf61528cedefeda0bcacc2f06fb48fd3">runOnFunction</a> (Function &amp;F) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnFunction - Virtual method overriden by subclasses to do the per-function processing of the pass. <a href="#abf61528cedefeda0bcacc2f06fb48fd3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2daf236b6de8b523794ea798dd933cc">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#af2daf236b6de8b523794ea798dd933cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a306b0d81a7cf944346a854335c0c3436">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job. <a href="#a306b0d81a7cf944346a854335c0c3436">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a302dbc6327c9bb114d43e1ed74fb7193">TM</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/globalmergeoptions">GlobalMergeOptions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b3a13fcf554ec947bb4d46fa5c4ca8b">Opt</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55444010b25f9c2a3c51e1026bd7e013">ID</a> = 0</td>
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


<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmerge-cpp">GlobalMerge.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GlobalMerge() {#a92cb5e0ddb6f9c0ddacb9a9b791977af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{GlobalMerge.cpp}::GlobalMerge::GlobalMerge ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmerge-cpp">GlobalMerge.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/functionpass/#a7691d83e3561f781cae4ce4a01bdfa93">llvm::FunctionPass::FunctionPass</a>, <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmerge-cpp/#a87e1b76cd4e667b47b90fc9b3e6e75c7">GlobalMergeMaxOffset</a>, <a href="#a55444010b25f9c2a3c51e1026bd7e013">ID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5de202f7dba1b52ff79a95c205fb130f">llvm::initializeGlobalMergePass</a>.</p>

</div>
</div>

### GlobalMerge() {#a7cf1070f862ab357580f5b924f603f97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{GlobalMerge.cpp}::GlobalMerge::GlobalMerge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> * TM, unsigned MaximalOffset, bool OnlyOptimizeForSize, bool MergeExternalGlobals, bool MergeConstantGlobals, bool MergeConstAggressive)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmerge-cpp">GlobalMerge.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/functionpass/#a7691d83e3561f781cae4ce4a01bdfa93">llvm::FunctionPass::FunctionPass</a>, <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#a55444010b25f9c2a3c51e1026bd7e013">ID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5de202f7dba1b52ff79a95c205fb130f">llvm::initializeGlobalMergePass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### doInitialization() {#abe9c261f5762d1873822f0635616e14e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{GlobalMerge.cpp}::GlobalMerge::doInitialization (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;)</td>
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

<p>doInitialization - Virtual method overridden by subclasses to do any necessary initialization before any pass is run.</p>

<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmerge-cpp">GlobalMerge.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#ad938857d6c6603847adf3a8cbe403d17">llvm::mdconst::extract</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmerge-cpp/#a8352e861e24cb13fa45de932a9a22be3">GlobalMergeMinDataSize</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### getAnalysisUsage() {#a306b0d81a7cf944346a854335c0c3436}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{GlobalMerge.cpp}::GlobalMerge::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;)</td>
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

<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job.</p>


<p>If a pass specifies that it uses a particular analysis result to this function, it can then use the <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">getAnalysis&lt;AnalysisType&gt;()</a> function, below.</p>


<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmerge-cpp">GlobalMerge.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pass/#a6590d0486104165ca40c7df0707f7b9e">llvm::Pass::getAnalysisUsage</a> and <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#af11a6ebf7ab3c388234cb6d5378439a3">llvm::AnalysisUsage::setPreservesCFG</a>.</p>

</div>
</div>

### getPassName() {#af2daf236b6de8b523794ea798dd933cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{GlobalMerge.cpp}::GlobalMerge::getPassName ()</td>
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

<p>getPassName - Return a nice clean name for a pass.</p>


<p>This usually implemented in terms of the name that is registered by one of the Registration templates, but can be overloaded directly.</p>


<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmerge-cpp">GlobalMerge.cpp</a>.</p>

</div>
</div>

### runOnFunction() {#abf61528cedefeda0bcacc2f06fb48fd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{GlobalMerge.cpp}::GlobalMerge::runOnFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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

<p>runOnFunction - Virtual method overriden by subclasses to do the per-function processing of the pass.</p>

<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmerge-cpp">GlobalMerge.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Opt {#a8b3a13fcf554ec947bb4d46fa5c4ca8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalMergeOptions anonymous{GlobalMerge.cpp}::GlobalMerge::Opt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmerge-cpp">GlobalMerge.cpp</a>.</p>

</div>
</div>

### TM {#a302dbc6327c9bb114d43e1ed74fb7193}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetMachine* anonymous{GlobalMerge.cpp}::GlobalMerge::TM = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmerge-cpp">GlobalMerge.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a55444010b25f9c2a3c51e1026bd7e013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char GlobalMerge::ID = 0</td>
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



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmerge-cpp">GlobalMerge.cpp</a>.</p>


<p>Referenced by <a href="#a92cb5e0ddb6f9c0ddacb9a9b791977af">GlobalMerge</a> and <a href="#a7cf1070f862ab357580f5b924f603f97">GlobalMerge</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmerge-cpp">GlobalMerge.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
