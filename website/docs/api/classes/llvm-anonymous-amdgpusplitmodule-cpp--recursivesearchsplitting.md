---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/recursivesearchsplitting
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RecursiveSearchSplitting` Class Reference

<p>Partitioning algorithm. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::anonymous{AMDGPUSplitModule.cpp}::RecursiveSearchSplitting { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8eaf74ac38a942f1ca6e2307d38467cd">SubmitProposalFn</a> = <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitproposal">SplitProposal</a>)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7730964440282e892cf5d22604f49507">RecursiveSearchSplitting</a> (const SplitGraph &amp;SG, unsigned NumParts, SubmitProposalFn SubmitProposal)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38bc18e3b30c87e344d2b70e51815d1e">run</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0739b040a06dd1b36ca667304fc744a">setupWorkList</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collects all graph entry points's clusters and sort them so the most expensive clusters are viewed first. <a href="#ab0739b040a06dd1b36ca667304fc744a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dea9f559c7898a7c1838196750eb229">pickPartition</a> (unsigned Depth, unsigned Idx, SplitProposal SP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursive function that assigns the worklist item at <span class="doxyComputerOutput">Idx</span> into a partition of <span class="doxyComputerOutput">SP</span>. <a href="#a7dea9f559c7898a7c1838196750eb229">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; unsigned, <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-amdgpusplitmodule-cpp-/#a0c86b2852d6e78ed3aaaf412ed290186">CostType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2aeab1fffacfe90661414ba4ff5916b0">findMostSimilarPartition</a> (const WorkListEntry &amp;Entry, const SplitProposal &amp;SP)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph">SplitGraph</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac72bec81fe77abda548d7c33dc65f9e3">SG</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98d8698f3811e2b014080b312bc6addd">NumParts</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a8eaf74ac38a942f1ca6e2307d38467cd">SubmitProposalFn</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e4fa35277e25ff218a47a90d5be9578">SubmitProposal</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/anonymous-amdgpusplitmodule-cpp-/#a0c86b2852d6e78ed3aaaf412ed290186">CostType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d853df2d3aff682ef9d8fa4e6d7ada9">LargeClusterThreshold</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a284419741bd1701815761c018ce7aa68">NumProposalsSubmitted</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; WorkListEntry &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d737d273e2bc529b2ae699d90d30dc2">WorkList</a></td>
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

<p>Partitioning algorithm.</p>


<p>This is a recursive search algorithm that can explore multiple possiblities.</p>


<p>When a cluster of nodes can go into more than one partition, and we haven't reached maximum search depth, we recurse and explore both options and their consequences. Both branches will yield a proposal, and the driver will grade both and choose the best one.</p>


<p>If max depth is reached, we will use some heuristics to make a choice. Most of the time we will just use the least-pressured (cheapest) partition, but if a cluster is particularly big and there is a good amount of overlap with an existing partition, we will choose that partition instead.</p>


<p>Definition at line 915 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### SubmitProposalFn {#a8eaf74ac38a942f1ca6e2307d38467cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::anonymous{AMDGPUSplitModule.cpp}::RecursiveSearchSplitting::SubmitProposalFn =  function_ref&lt;void(SplitProposal)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 917 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### RecursiveSearchSplitting() {#a7730964440282e892cf5d22604f49507}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::anonymous{AMDGPUSplitModule.cpp}::RecursiveSearchSplitting::RecursiveSearchSplitting (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph">SplitGraph</a> &amp; SG, unsigned NumParts, <a href="#a8eaf74ac38a942f1ca6e2307d38467cd">SubmitProposalFn</a> SubmitProposal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 919 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-amdgpusplitmodule-cpp-/#afa109a30d0599119589438ed40cf7c7b">llvm::anonymous{AMDGPUSplitModule.cpp}::LargeFnFactor</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-amdgpusplitmodule-cpp-/#a02273768ec41f48168b8b464f639bcd3">llvm::anonymous{AMDGPUSplitModule.cpp}::MaxDepth</a>, <a href="#a7730964440282e892cf5d22604f49507">RecursiveSearchSplitting</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="#a7730964440282e892cf5d22604f49507">RecursiveSearchSplitting</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#a38bc18e3b30c87e344d2b70e51815d1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::anonymous{AMDGPUSplitModule.cpp}::RecursiveSearchSplitting::run ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 922 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-amdgpusplitmodule-cpp-/#a0706966ac4f391854346bebfcda816fa">llvm::anonymous{AMDGPUSplitModule.cpp}::splitAMDGPUModule</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### findMostSimilarPartition() {#a2aeab1fffacfe90661414ba4ff5916b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; unsigned, CostType &gt; llvm::anonymous{AMDGPUSplitModule.cpp}::RecursiveSearchSplitting::findMostSimilarPartition (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> WorkListEntry &amp; Entry, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitproposal">SplitProposal</a> &amp; SP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A pair: first element is the PID of the partition that has the most similarities with <span class="doxyComputerOutput">Entry</span>, or <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-amdgpusplitmodule-cpp-/#a286dd4db76f60ca092a2a00292b5638d">InvalidPID</a> if no partition was found with at least one element in common. The second element is the aggregated cost of all dependencies in common between <span class="doxyComputerOutput">Entry</span> and that partition.</p></dd>
</dl>


<p>Definition at line 956 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>

</div>
</div>

### pickPartition() {#a7dea9f559c7898a7c1838196750eb229}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::anonymous{AMDGPUSplitModule.cpp}::RecursiveSearchSplitting::pickPartition (unsigned Depth, unsigned Idx, <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitproposal">SplitProposal</a> SP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recursive function that assigns the worklist item at <span class="doxyComputerOutput">Idx</span> into a partition of <span class="doxyComputerOutput">SP</span>.</p>


<p><span class="doxyComputerOutput">Depth</span> is the current search depth. When this value is equal to <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-amdgpusplitmodule-cpp-/#a02273768ec41f48168b8b464f639bcd3">MaxDepth</a>, we can no longer recurse.</p>


<p>This function only recurses if there is more than one possible assignment, otherwise it is iterative to avoid creating a call stack that is as big as WorkList.</p>


<p>Definition at line 948 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>

</div>
</div>

### setupWorkList() {#ab0739b040a06dd1b36ca667304fc744a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::anonymous{AMDGPUSplitModule.cpp}::RecursiveSearchSplitting::setupWorkList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collects all graph entry points's clusters and sort them so the most expensive clusters are viewed first.</p>


<p>This will merge clusters together if they share a non-copyable dependency.</p>


<p>Definition at line 937 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LargeClusterThreshold {#a2d853df2d3aff682ef9d8fa4e6d7ada9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CostType llvm::anonymous{AMDGPUSplitModule.cpp}::RecursiveSearchSplitting::LargeClusterThreshold = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 964 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>

</div>
</div>

### NumParts {#a98d8698f3811e2b014080b312bc6addd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::anonymous{AMDGPUSplitModule.cpp}::RecursiveSearchSplitting::NumParts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 959 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>

</div>
</div>

### NumProposalsSubmitted {#a284419741bd1701815761c018ce7aa68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::anonymous{AMDGPUSplitModule.cpp}::RecursiveSearchSplitting::NumProposalsSubmitted = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 965 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>

</div>
</div>

### SG {#ac72bec81fe77abda548d7c33dc65f9e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SplitGraph&amp; llvm::anonymous{AMDGPUSplitModule.cpp}::RecursiveSearchSplitting::SG</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 958 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>

</div>
</div>

### SubmitProposal {#a4e4fa35277e25ff218a47a90d5be9578}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SubmitProposalFn llvm::anonymous{AMDGPUSplitModule.cpp}::RecursiveSearchSplitting::SubmitProposal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 960 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>

</div>
</div>

### WorkList {#a1d737d273e2bc529b2ae699d90d30dc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;WorkListEntry&gt; llvm::anonymous{AMDGPUSplitModule.cpp}::RecursiveSearchSplitting::WorkList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 966 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
