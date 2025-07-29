---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/loopinfowrapperpass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LoopInfoWrapperPass` Class

<p>The legacy pass manager's analysis pass to compute loop information. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LoopInfoWrapperPass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">llvm/Analysis/LoopInfo.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a961c86177bf3257b60bef12e132a840b">LoopInfoWrapperPass</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70b7acc05e61064b2b7aba8e0a24ee40">getLoopInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a538ed6c49f977026adbd5f229521b6ca">getLoopInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea27493f9f8413433bab89a007ced708">runOnFunction</a> (Function &amp;F) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate the natural loop information for a given function. <a href="#aea27493f9f8413433bab89a007ced708">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea281601b9f1c88d8cc2a4d6245d3b7d">verifyAnalysis</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#aea281601b9f1c88d8cc2a4d6245d3b7d">verifyAnalysis()</a> - This member can be implemented by a analysis pass to check state of analysis information. <a href="#aea281601b9f1c88d8cc2a4d6245d3b7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e0d515ceebdc3b0329af8a6f1d3cbe8">releaseMemory</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a9e0d515ceebdc3b0329af8a6f1d3cbe8">releaseMemory()</a> - This member can be implemented by a pass if it wants to be able to release its memory when it is no longer needed. <a href="#a9e0d515ceebdc3b0329af8a6f1d3cbe8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8642d6b46a33ae54407c516b18d142f">print</a> (raw_ostream &amp;O, const Module *M=nullptr) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print - Print out the internal state of the pass. <a href="#af8642d6b46a33ae54407c516b18d142f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a715603b0503ecf76d50bebba1820cc49">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job. <a href="#a715603b0503ecf76d50bebba1820cc49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42d749a59668d8924d87298ed8d94e81">LI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe944d1ff93d411b69b4a27ac33f02e4">ID</a> = 0</td>
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

<p>The legacy pass manager's analysis pass to compute loop information.</p>

<p>Definition at line 593 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LoopInfoWrapperPass() {#a961c86177bf3257b60bef12e132a840b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfoWrapperPass::LoopInfoWrapperPass ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 599 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 1213 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/functionpass/#a7691d83e3561f781cae4ce4a01bdfa93">llvm::FunctionPass::FunctionPass</a>, <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#abe944d1ff93d411b69b4a27ac33f02e4">ID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a150c16646e011b61c56a051e49b2f2fb">llvm::initializeLoopInfoWrapperPassPass</a>.</p>


<p>Referenced by <a href="#aea27493f9f8413433bab89a007ced708">runOnFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAnalysisUsage() {#a715603b0503ecf76d50bebba1820cc49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoopInfoWrapperPass::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;)</td>
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

<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job.</p>


<p>If a pass specifies that it uses a particular analysis result to this function, it can then use the <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">getAnalysis&lt;AnalysisType&gt;()</a> function, below.</p>


<p>Declaration at line 613 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 1242 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#afd8af3487564621ceeb41c2838c4469e">llvm::AnalysisUsage::addRequiredTransitive</a> and <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#af22b06a6a4f9df80454071685a0d6a02">llvm::AnalysisUsage::setPreservesAll</a>.</p>

</div>
</div>

### getLoopInfo() {#a70b7acc05e61064b2b7aba8e0a24ee40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo &amp; llvm::LoopInfoWrapperPass::getLoopInfo ()</td>
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



<p>Definition at line 601 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>.</p>

</div>
</div>

### getLoopInfo() {#a538ed6c49f977026adbd5f229521b6ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LoopInfo &amp; llvm::LoopInfoWrapperPass::getLoopInfo ()</td>
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



<p>Definition at line 602 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>.</p>

</div>
</div>

### print() {#af8642d6b46a33ae54407c516b18d142f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoopInfoWrapperPass::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M=nullptr)</td>
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

<p>print - Print out the internal state of the pass.</p>


<p>This is called by Analyze to print out the contents of an analysis. Otherwise it is not necessary to implement this method. Beware that the module pointer MAY be null. This automatically forwards to a virtual function that does not provide the Module* in case the analysis doesn't need it it can just be ignored.</p>


<p>Declaration at line 611 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 1247 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dominatortreewrapperpass/#a4496321c90df2dcaa979fe540e82baa1">llvm::DominatorTreeWrapperPass::print</a>.</p>

</div>
</div>

### releaseMemory() {#a9e0d515ceebdc3b0329af8a6f1d3cbe8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopInfoWrapperPass::releaseMemory ()</td>
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

<p><a href="#a9e0d515ceebdc3b0329af8a6f1d3cbe8">releaseMemory()</a> - This member can be implemented by a pass if it wants to be able to release its memory when it is no longer needed.</p>


<p>The default behavior of passes is to hold onto memory for the entire duration of their lifetime (which is the entire compile time). For pipelined passes, this is not a big deal because that memory gets recycled every time the pass is invoked on another program unit. For IP passes, it is more important to free memory when it is unused.</p>


<p>Optionally implement this function to release pass memory when it is no longer used.</p>


<p>Definition at line 609 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>.</p>


<p>Referenced by <a href="#aea27493f9f8413433bab89a007ced708">runOnFunction</a>.</p>

</div>
</div>

### runOnFunction() {#aea27493f9f8413433bab89a007ced708}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Natural Loop true bool LoopInfoWrapperPass::runOnFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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

<p>Calculate the natural loop information for a given function.</p>

<p>Declaration at line 605 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 1224 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a>, <a href="#a961c86177bf3257b60bef12e132a840b">LoopInfoWrapperPass</a>, <a href="#a9e0d515ceebdc3b0329af8a6f1d3cbe8">releaseMemory</a> and <a href="#aea27493f9f8413433bab89a007ced708">runOnFunction</a>.</p>


<p>Referenced by <a href="#aea27493f9f8413433bab89a007ced708">runOnFunction</a>.</p>

</div>
</div>

### verifyAnalysis() {#aea281601b9f1c88d8cc2a4d6245d3b7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoopInfoWrapperPass::verifyAnalysis ()</td>
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

<p><a href="#aea281601b9f1c88d8cc2a4d6245d3b7d">verifyAnalysis()</a> - This member can be implemented by a analysis pass to check state of analysis information.</p>

<p>Declaration at line 607 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 1230 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8bf0b85d705bf73d1af85056ef77b9c5">llvm::VerifyLoopInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LI {#a42d749a59668d8924d87298ed8d94e81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo llvm::LoopInfoWrapperPass::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 594 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#abe944d1ff93d411b69b4a27ac33f02e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char LoopInfoWrapperPass::ID = 0</td>
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



<p>Definition at line 597 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>.</p>


<p>Referenced by <a href="#a961c86177bf3257b60bef12e132a840b">LoopInfoWrapperPass</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
