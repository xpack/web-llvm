---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/contexttrienode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ContextTrieNode` Class



## Declaration

<div class="doxyDeclaration">
class llvm::ContextTrieNode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">llvm/Transforms/IPO/SampleContextTracker.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad99cc0c31b712fcf6713422c0354c0e9">ContextTrieNode</a> (ContextTrieNode *Parent=nullptr, FunctionId FName=FunctionId(), FunctionSamples *FSamples=nullptr, LineLocation CallLoc={0, 0})</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab05fd0aa0f2a966006e4b4bd448617e7">getChildContext</a> (const LineLocation &amp;CallSite, FunctionId ChildName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53db652fc4a21c80c9094604ee15c334">getHottestChildContext</a> (const LineLocation &amp;CallSite)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0aa47b79624491957a2ba676d69bd886">getOrCreateChildContext</a> (const LineLocation &amp;CallSite, FunctionId ChildName, bool AllowCreate=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77604ff4be17a6eb893f38f8e57d437a">removeChildContext</a> (const LineLocation &amp;CallSite, FunctionId ChildName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; uint64_t, <a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f957c3b9a4c1c915ff992784abea057">getAllChildContext</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e8b7da0d22a72878bbaee1cca8bf5a1">getFuncName</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a247f427d8cb89802a69482144f937aaf">getFunctionSamples</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac12abae83b7ced7abcade7bc0c1b791a">setFunctionSamples</a> (FunctionSamples *FSamples)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a6c65e5b3512f5973981d812400d7ad">getFunctionSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a0942f739b9b53953d448ebcff86f62">addFunctionSize</a> (uint32_t FSize)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/sampleprof/linelocation">LineLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a225eff054e4076aff7702dd9369d0541">getCallSiteLoc</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8bf97f262edd3ba302dc33322d8df9a">getParentContext</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59fc5483fdf80df68af01f91ff84c1f4">setParentContext</a> (ContextTrieNode *Parent)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c286e600646df09f49833c4d86410bf">setCallSiteLoc</a> (const LineLocation &amp;Loc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7093e7044301e523f3ce925334f12823">dumpNode</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81ea229aabd3a896f030b02f875bf748">dumpTree</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; uint64_t, <a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95743a734df5de03f081dca7c422c33a">AllChildContext</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdc0441873acdaeee3352176cf93f0db">ParentContext</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa936fd2b04f53e4ade6efbdd011fa525">FuncName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b8fa10b4ad7cd4c94dac7ea63f5e3de">FuncSamples</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a953c18bf4cf74e874d6c08fb31bf01d1">FuncSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/sampleprof/linelocation">LineLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03865f52729d776c51ce31e30153ad34">CallSiteLoc</a></td>
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


<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ContextTrieNode() {#ad99cc0c31b712fcf6713422c0354c0e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ContextTrieNode::ContextTrieNode (<a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a> * Parent=nullptr, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> FName=<a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a>(), <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> * FSamples=nullptr, <a href="/web-llvm/docs/api/structs/llvm/sampleprof/linelocation">LineLocation</a> CallLoc={0, 0})</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>.</p>


<p>Reference <a href="#ad99cc0c31b712fcf6713422c0354c0e9">ContextTrieNode</a>.</p>


<p>Referenced by <a href="#ad99cc0c31b712fcf6713422c0354c0e9">ContextTrieNode</a>, <a href="#a81ea229aabd3a896f030b02f875bf748">dumpTree</a>, <a href="#ab05fd0aa0f2a966006e4b4bd448617e7">getChildContext</a>, <a href="#a53db652fc4a21c80c9094604ee15c334">getHottestChildContext</a>, <a href="#a0aa47b79624491957a2ba676d69bd886">getOrCreateChildContext</a>, <a href="#ab8bf97f262edd3ba302dc33322d8df9a">getParentContext</a> and <a href="#a59fc5483fdf80df68af01f91ff84c1f4">setParentContext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addFunctionSize() {#a8a0942f739b9b53953d448ebcff86f62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ContextTrieNode::addFunctionSize (uint32_t FSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>

</div>
</div>

### dumpNode() {#a7093e7044301e523f3ce925334f12823}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ContextTrieNode::dumpNode ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>.</p>

</div>
</div>

### dumpTree() {#a81ea229aabd3a896f030b02f875bf748}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ContextTrieNode::dumpTree ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>


<p>References <a href="#ad99cc0c31b712fcf6713422c0354c0e9">ContextTrieNode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>.</p>

</div>
</div>

### getAllChildContext() {#a0f957c3b9a4c1c915ff992784abea057}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt; uint64_t, ContextTrieNode &gt; &amp; llvm::ContextTrieNode::getAllChildContext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#af2c5a7cbd593261dc632d06d8225c04d">llvm::SampleContextTracker::getIndirectCalleeContextSamplesFor</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/profiledcallgraph/#acae2ab44bcb9d9add7c351061ac8e6f6">llvm::sampleprof::ProfiledCallGraph::ProfiledCallGraph</a> and <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#a03cbc7841d2552fcd7639666975fa13c">llvm::SampleContextTracker::promoteMergeContextSamplesTree</a>.</p>

</div>
</div>

### getCallSiteLoc() {#a225eff054e4076aff7702dd9369d0541}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LineLocation llvm::ContextTrieNode::getCallSiteLoc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#aa12ce67d21274bae7db762b1e5728bf6">llvm::SampleContextTracker::getContextString</a>, <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#af2c5a7cbd593261dc632d06d8225c04d">llvm::SampleContextTracker::getIndirectCalleeContextSamplesFor</a> and <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#a03cbc7841d2552fcd7639666975fa13c">llvm::SampleContextTracker::promoteMergeContextSamplesTree</a>.</p>

</div>
</div>

### getChildContext() {#ab05fd0aa0f2a966006e4b4bd448617e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContextTrieNode * llvm::ContextTrieNode::getChildContext (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/sampleprof/linelocation">LineLocation</a> &amp; CallSite, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> ChildName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>


<p>References <a href="#ad99cc0c31b712fcf6713422c0354c0e9">ContextTrieNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid/#a8f6fbd8851c1e7809544abaf1fae75a0">llvm::sampleprof::FunctionId::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a4fc907c22a54099eca9b792ab963b4a3">llvm::sampleprof::FunctionSamples::getCallSiteHash</a> and <a href="#a53db652fc4a21c80c9094604ee15c334">getHottestChildContext</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#a03cbc7841d2552fcd7639666975fa13c">llvm::SampleContextTracker::promoteMergeContextSamplesTree</a>.</p>

</div>
</div>

### getFuncName() {#a8e8b7da0d22a72878bbaee1cca8bf5a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionId llvm::ContextTrieNode::getFuncName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>

</div>
</div>

### getFunctionSamples() {#a247f427d8cb89802a69482144f937aaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionSamples * llvm::ContextTrieNode::getFunctionSamples ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#af9a5eace41510a920670a82474022c7a">llvm::SampleContextTracker::getCalleeContextSamplesFor</a>, <a href="#a53db652fc4a21c80c9094604ee15c334">getHottestChildContext</a>, <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#af2c5a7cbd593261dc632d06d8225c04d">llvm::SampleContextTracker::getIndirectCalleeContextSamplesFor</a>, <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#a03cbc7841d2552fcd7639666975fa13c">llvm::SampleContextTracker::promoteMergeContextSamplesTree</a> and <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#a8960053536efb781f864875695ddd403">llvm::SampleContextTracker::SampleContextTracker</a>.</p>

</div>
</div>

### getFunctionSize() {#a3a6c65e5b3512f5973981d812400d7ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint32_t &gt; llvm::ContextTrieNode::getFunctionSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>

</div>
</div>

### getHottestChildContext() {#a53db652fc4a21c80c9094604ee15c334}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContextTrieNode * llvm::ContextTrieNode::getHottestChildContext (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/sampleprof/linelocation">LineLocation</a> &amp; CallSite)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>


<p>References <a href="#ad99cc0c31b712fcf6713422c0354c0e9">ContextTrieNode</a>, <a href="#a247f427d8cb89802a69482144f937aaf">getFunctionSamples</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#adb2786061d3e569b42b7d661ccc57484">llvm::sampleprof::FunctionSamples::getTotalSamples</a>.</p>


<p>Referenced by <a href="#ab05fd0aa0f2a966006e4b4bd448617e7">getChildContext</a>.</p>

</div>
</div>

### getOrCreateChildContext() {#a0aa47b79624491957a2ba676d69bd886}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContextTrieNode * llvm::ContextTrieNode::getOrCreateChildContext (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/sampleprof/linelocation">LineLocation</a> &amp; CallSite, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> ChildName, bool AllowCreate=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad99cc0c31b712fcf6713422c0354c0e9">ContextTrieNode</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a4fc907c22a54099eca9b792ab963b4a3">llvm::sampleprof::FunctionSamples::getCallSiteHash</a>.</p>

</div>
</div>

### getParentContext() {#ab8bf97f262edd3ba302dc33322d8df9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContextTrieNode * llvm::ContextTrieNode::getParentContext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>


<p>Reference <a href="#ad99cc0c31b712fcf6713422c0354c0e9">ContextTrieNode</a>.</p>

</div>
</div>

### removeChildContext() {#a77604ff4be17a6eb893f38f8e57d437a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ContextTrieNode::removeChildContext (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/sampleprof/linelocation">LineLocation</a> &amp; CallSite, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> ChildName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a4fc907c22a54099eca9b792ab963b4a3">llvm::sampleprof::FunctionSamples::getCallSiteHash</a>.</p>

</div>
</div>

### setCallSiteLoc() {#a1c286e600646df09f49833c4d86410bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ContextTrieNode::setCallSiteLoc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/sampleprof/linelocation">LineLocation</a> &amp; Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>

</div>
</div>

### setFunctionSamples() {#ac12abae83b7ced7abcade7bc0c1b791a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ContextTrieNode::setFunctionSamples (<a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> * FSamples)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#a8960053536efb781f864875695ddd403">llvm::SampleContextTracker::SampleContextTracker</a>.</p>

</div>
</div>

### setParentContext() {#a59fc5483fdf80df68af01f91ff84c1f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ContextTrieNode::setParentContext (<a href="/web-llvm/docs/api/classes/llvm/contexttrienode">ContextTrieNode</a> * Parent)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>, definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a>.</p>


<p>Reference <a href="#ad99cc0c31b712fcf6713422c0354c0e9">ContextTrieNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AllChildContext {#a95743a734df5de03f081dca7c422c33a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;uint64_t, ContextTrieNode&gt; llvm::ContextTrieNode::AllChildContext</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>.</p>

</div>
</div>

### CallSiteLoc {#a03865f52729d776c51ce31e30153ad34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LineLocation llvm::ContextTrieNode::CallSiteLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>.</p>

</div>
</div>

### FuncName {#aa936fd2b04f53e4ade6efbdd011fa525}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionId llvm::ContextTrieNode::FuncName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>.</p>

</div>
</div>

### FuncSamples {#a1b8fa10b4ad7cd4c94dac7ea63f5e3de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionSamples* llvm::ContextTrieNode::FuncSamples</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>.</p>

</div>
</div>

### FuncSize {#a953c18bf4cf74e874d6c08fb31bf01d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint32_t&gt; llvm::ContextTrieNode::FuncSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>.</p>

</div>
</div>

### ParentContext {#acdc0441873acdaeee3352176cf93f0db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContextTrieNode* llvm::ContextTrieNode::ParentContext</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">SampleContextTracker.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/samplecontexttracker-cpp">SampleContextTracker.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
