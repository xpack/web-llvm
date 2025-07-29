---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/callgraphdotinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CallGraphDOTInfo` Class



## Declaration

<div class="doxyDeclaration">
class llvm::CallGraphDOTInfo { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc6bb41940850bb2ae61ef5895310618">CallGraphDOTInfo</a> (Module *M, CallGraph *CG, function_ref&lt; BlockFrequencyInfo *(Function &amp;)&gt; LookupBFI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52aed067514bb9184891b8f48d457cdc">getModule</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callgraph">CallGraph</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b0e613d517434a16339b0c8e96b8019">getCallGraph</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5864ac7f28ca5071bfc93304e65727c">getFreq</a> (const Function *F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a641dab53d619b6f748a6d46407fd1097">getMaxFreq</a> ()</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa42d4b00cff58aa766946e79fe13ceee">removeParallelEdges</a> ()</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> *(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4843af0c4dbeff65f9c4097ef3c30b09">LookupBFI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab496f86e01fa03e21f1e23c741a362a3">M</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callgraph">CallGraph</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bd189bd37722cee63c23e02f7349a1e">CG</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a214fa4c1cfbf1e44bc2401b2d72202">Freq</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb040bf890dd23b4dccd20f53696833c">MaxFreq</a></td>
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


<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callprinter-cpp">CallPrinter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CallGraphDOTInfo() {#adc6bb41940850bb2ae61ef5895310618}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CallGraphDOTInfo::CallGraphDOTInfo (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M, <a href="/web-llvm/docs/api/classes/llvm/callgraph">CallGraph</a> * CG, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> *(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; LookupBFI)</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callprinter-cpp">CallPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/callprinter-cpp/#a7425a76346631e5c264edb74afc2c91d">CallMultiGraph</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> and <a href="#a4843af0c4dbeff65f9c4097ef3c30b09">LookupBFI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getCallGraph() {#a0b0e613d517434a16339b0c8e96b8019}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallGraph * llvm::CallGraphDOTInfo::getCallGraph ()</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callprinter-cpp">CallPrinter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/graphtraits-02fb7f36a5622815e386262c1f910406/#a07c7ffaa3df4635a451ea088ee1a5971">llvm::GraphTraits&lt; CallGraphDOTInfo * &gt;::getEntryNode</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-02fb7f36a5622815e386262c1f910406/#af124dac4967882b35a6e3afafc30da8a">llvm::DOTGraphTraits&lt; CallGraphDOTInfo * &gt;::getNodeLabel</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-02fb7f36a5622815e386262c1f910406/#aa68d60ea21e7c35c8e87758eaa757621">llvm::GraphTraits&lt; CallGraphDOTInfo * &gt;::nodes_begin</a> and <a href="/web-llvm/docs/api/structs/llvm/graphtraits-02fb7f36a5622815e386262c1f910406/#ad20ad894a9bf9470be9b0990240c7d88">llvm::GraphTraits&lt; CallGraphDOTInfo * &gt;::nodes_end</a>.</p>

</div>
</div>

### getFreq() {#aa5864ac7f28ca5071bfc93304e65727c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::CallGraphDOTInfo::getFreq (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callprinter-cpp">CallPrinter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-02fb7f36a5622815e386262c1f910406/#a18c5d3cf4cf688e934da2909ce3d3b9f">llvm::DOTGraphTraits&lt; CallGraphDOTInfo * &gt;::getNodeAttributes</a>.</p>

</div>
</div>

### getMaxFreq() {#a641dab53d619b6f748a6d46407fd1097}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::CallGraphDOTInfo::getMaxFreq ()</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callprinter-cpp">CallPrinter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-02fb7f36a5622815e386262c1f910406/#ac9d14d432dda489dc7418e5a0175258a">llvm::DOTGraphTraits&lt; CallGraphDOTInfo * &gt;::getEdgeAttributes</a> and <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-02fb7f36a5622815e386262c1f910406/#a18c5d3cf4cf688e934da2909ce3d3b9f">llvm::DOTGraphTraits&lt; CallGraphDOTInfo * &gt;::getNodeAttributes</a>.</p>

</div>
</div>

### getModule() {#a52aed067514bb9184891b8f48d457cdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module * llvm::CallGraphDOTInfo::getModule ()</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callprinter-cpp">CallPrinter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-02fb7f36a5622815e386262c1f910406/#a1e5d2d7a177eff7597bbe96b871be19d">llvm::DOTGraphTraits&lt; CallGraphDOTInfo * &gt;::getGraphName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### removeParallelEdges() {#aa42d4b00cff58aa766946e79fe13ceee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallGraphDOTInfo::removeParallelEdges ()</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callprinter-cpp">CallPrinter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### LookupBFI {#a4843af0c4dbeff65f9c4097ef3c30b09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;BlockFrequencyInfo *(Function &amp;)&gt; llvm::CallGraphDOTInfo::LookupBFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callprinter-cpp">CallPrinter.cpp</a>.</p>


<p>Referenced by <a href="#adc6bb41940850bb2ae61ef5895310618">CallGraphDOTInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CG {#a2bd189bd37722cee63c23e02f7349a1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallGraph* llvm::CallGraphDOTInfo::CG</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callprinter-cpp">CallPrinter.cpp</a>.</p>

</div>
</div>

### Freq {#a1a214fa4c1cfbf1e44bc2401b2d72202}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Function *, uint64_t&gt; llvm::CallGraphDOTInfo::Freq</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callprinter-cpp">CallPrinter.cpp</a>.</p>

</div>
</div>

### M {#ab496f86e01fa03e21f1e23c741a362a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module* llvm::CallGraphDOTInfo::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callprinter-cpp">CallPrinter.cpp</a>.</p>

</div>
</div>

### MaxFreq {#aeb040bf890dd23b4dccd20f53696833c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::CallGraphDOTInfo::MaxFreq</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callprinter-cpp">CallPrinter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/callprinter-cpp">CallPrinter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
