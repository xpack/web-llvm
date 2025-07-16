---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/regioninfopass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RegionInfoPass` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::RegionInfoPass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">llvm/Analysis/RegionInfo.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78b5c4f45e7dd177d056c548f8a71cec">RegionInfoPass</a> ()</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c616dd8c56fa725c3ce0153bde58aa3">~RegionInfoPass</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regioninfo">RegionInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25fc1f919fad53ff89cd2883608e034d">getRegionInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/regioninfo">RegionInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e957d406b9b057d9c90f564c91b41a1">getRegionInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regioninfo">RegionInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaf8b63529529c4551c65b83d2ae09af">RI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a426e2b569823b732245039848a6ffaaa">ID</a> = 0</td>
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

## FunctionPass interface Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f190fc7ae16274a25436aef02eba40c">runOnFunction</a> (Function &amp;F) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnFunction - Virtual method overriden by subclasses to do the per-function processing of the pass. <a href="#a0f190fc7ae16274a25436aef02eba40c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a226dceb373b68e3be5cd508b1b4f79">releaseMemory</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a0a226dceb373b68e3be5cd508b1b4f79">releaseMemory()</a> - This member can be implemented by a pass if it wants to be able to release its memory when it is no longer needed. <a href="#a0a226dceb373b68e3be5cd508b1b4f79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa91384178101684963d79211bf0f9db4">verifyAnalysis</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#aa91384178101684963d79211bf0f9db4">verifyAnalysis()</a> - This member can be implemented by a analysis pass to check state of analysis information. <a href="#aa91384178101684963d79211bf0f9db4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad510ccd391f3fe3ea27847ab0ed19128">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job. <a href="#ad510ccd391f3fe3ea27847ab0ed19128">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2a9c3b5060d123523291339064eb2a9">print</a> (raw_ostream &amp;OS, const Module *) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print - Print out the internal state of the pass. <a href="#ad2a9c3b5060d123523291339064eb2a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1d16b1a18d54d59024c399bf87cd50f">dump</a> () const</td>
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


<p>Definition at line 940 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RegionInfoPass() {#a78b5c4f45e7dd177d056c548f8a71cec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegionInfoPass::RegionInfoPass ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 946 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regioninfo-cpp">RegionInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/functionpass/#a7691d83e3561f781cae4ce4a01bdfa93">llvm::FunctionPass::FunctionPass</a>, <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#a426e2b569823b732245039848a6ffaaa">ID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a51fb13e893461bbbe192dc999b3476df">llvm::initializeRegionInfoPassPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~RegionInfoPass() {#a1c616dd8c56fa725c3ce0153bde58aa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegionInfoPass::~RegionInfoPass ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 947 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getRegionInfo() {#a25fc1f919fad53ff89cd2883608e034d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegionInfo &amp; llvm::RegionInfoPass::getRegionInfo ()</td>
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



<p>Definition at line 949 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/graphtraits-f3f97e3a720012d251f1ecf6267c5354/#ab997d55864f652db3d5cf30dc4ef532f">llvm::GraphTraits&lt; RegionInfoPass * &gt;::getEntryNode</a>, <a href="/web-llvm/docs/api/structs/anonymous-regionprinter-cpp-/regioninfopassgraphtraits/#a3a24ad4146237b673452489ec4e74c19">anonymous{RegionPrinter.cpp}::RegionInfoPassGraphTraits::getGraph</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-f3f97e3a720012d251f1ecf6267c5354/#a43abf14bf407a3e9a505e41b68a9acf8">llvm::GraphTraits&lt; RegionInfoPass * &gt;::nodes_begin</a> and <a href="/web-llvm/docs/api/structs/llvm/graphtraits-f3f97e3a720012d251f1ecf6267c5354/#a4d5c9c210dd30f004833176fc96207b3">llvm::GraphTraits&lt; RegionInfoPass * &gt;::nodes_end</a>.</p>

</div>
</div>

### getRegionInfo() {#a3e957d406b9b057d9c90f564c91b41a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegionInfo &amp; llvm::RegionInfoPass::getRegionInfo ()</td>
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



<p>Definition at line 951 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### RI {#afaf8b63529529c4551c65b83d2ae09af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegionInfo llvm::RegionInfoPass::RI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 941 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a426e2b569823b732245039848a6ffaaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char RegionInfoPass::ID = 0</td>
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



<p>Definition at line 944 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>.</p>


<p>Referenced by <a href="#a78b5c4f45e7dd177d056c548f8a71cec">RegionInfoPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## FunctionPass interface

### dump {#aa1d16b1a18d54d59024c399bf87cd50f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void RegionInfoPass::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 960 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regioninfo-cpp">RegionInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>.</p>

</div>
</div>

### getAnalysisUsage {#ad510ccd391f3fe3ea27847ab0ed19128}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegionInfoPass::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;)</td>
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


<p>Declaration at line 958 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regioninfo-cpp">RegionInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a>, <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#afd8af3487564621ceeb41c2838c4469e">llvm::AnalysisUsage::addRequiredTransitive</a> and <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#af22b06a6a4f9df80454071685a0d6a02">llvm::AnalysisUsage::setPreservesAll</a>.</p>

</div>
</div>

### print {#ad2a9c3b5060d123523291339064eb2a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegionInfoPass::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M)</td>
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


<p>Declaration at line 959 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regioninfo-cpp">RegionInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dominancefrontierwrapperpass/#a688e0430e409c4a8c9ba8f90159a2480">llvm::DominanceFrontierWrapperPass::print</a>.</p>

</div>
</div>

### releaseMemory {#a0a226dceb373b68e3be5cd508b1b4f79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegionInfoPass::releaseMemory ()</td>
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

<p><a href="#a0a226dceb373b68e3be5cd508b1b4f79">releaseMemory()</a> - This member can be implemented by a pass if it wants to be able to release its memory when it is no longer needed.</p>


<p>The default behavior of passes is to hold onto memory for the entire duration of their lifetime (which is the entire compile time). For pipelined passes, this is not a big deal because that memory gets recycled every time the pass is invoked on another program unit. For IP passes, it is more important to free memory when it is unused.</p>


<p>Optionally implement this function to release pass memory when it is no longer used.</p>


<p>Declaration at line 956 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regioninfo-cpp">RegionInfo.cpp</a>.</p>


<p>Referenced by <a href="#a0f190fc7ae16274a25436aef02eba40c">runOnFunction</a>.</p>

</div>
</div>

### runOnFunction {#a0f190fc7ae16274a25436aef02eba40c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegionInfoPass::runOnFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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

<p>runOnFunction - Virtual method overriden by subclasses to do the per-function processing of the pass.</p>

<p>Declaration at line 955 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regioninfo-cpp">RegionInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a9e8fa29f7cb6a03aa586afae7591f6cc">DF</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a> and <a href="#a0a226dceb373b68e3be5cd508b1b4f79">releaseMemory</a>.</p>

</div>
</div>

### verifyAnalysis {#aa91384178101684963d79211bf0f9db4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegionInfoPass::verifyAnalysis ()</td>
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

<p><a href="#aa91384178101684963d79211bf0f9db4">verifyAnalysis()</a> - This member can be implemented by a analysis pass to check state of analysis information.</p>

<p>Declaration at line 957 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a>, definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regioninfo-cpp">RegionInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">RegionInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/regioninfo-cpp">RegionInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
