---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitproposal
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SplitProposal` Class Reference

<p>Represents a module splitting proposal. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::anonymous{AMDGPUSplitModule.cpp}::SplitProposal { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5260eb179c3a6fda24345ae0e6740556">SplitProposal</a> (const SplitGraph &amp;SG, unsigned MaxPartitions)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5836550f3b15be3dbc6d707dd8c2de45">operator[]</a> (unsigned PID) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98f31ddf4352a17257ff914f32ddbd02">setName</a> (StringRef NewName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6aa5f53b7b30135cb3afbcf4e223091">getName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac598f5cbb000dbdd8adbf94cb2242e1a">add</a> (unsigned PID, const BitVector &amp;BV)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0215de52344b43a21c90bb5e2293a5fb">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a843229cfda9f61491b29bbf045507f4d">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c57a3c3b97578adb6ee510485e6eb47">findCheapestPartition</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b2732b0f1d325de354b9a80d03768c3">calculateScores</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate the CodeSize and Bottleneck scores. <a href="#a7b2732b0f1d325de354b9a80d03768c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0d86d73dbaff64cd671fcc91556906d">verifyCompleteness</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b814b24fd11bbfc3ffc4f289c8cd36b">getCodeSizeScore</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Only available after <a href="#a7b2732b0f1d325de354b9a80d03768c3">calculateScores</a> is called. <a href="#a2b814b24fd11bbfc3ffc4f289c8cd36b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b7f24ee69de158b68769c29464e6b1c">getBottleneckScore</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Only available after <a href="#a7b2732b0f1d325de354b9a80d03768c3">calculateScores</a> is called. <a href="#a8b7f24ee69de158b68769c29464e6b1c">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4852101f030179131b282abd8b68472">updateScore</a> (unsigned PID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dffdd74fdb3f63eb0575af92316ec0c">CodeSizeScore</a> = 0.0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a9d3c3b27a59332c8a125e379aab3d2">BottleneckScore</a> = 0.0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68862bd778b559c366841f473aae424e">TotalCost</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Aggregated cost of all partitions. <a href="#a68862bd778b559c366841f473aae424e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph">SplitGraph</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5be665118ca4eaa1f454bb07f789dfa3">SG</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9aed4ef82f529f96d7e8722be8f5b8a8">Name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::pair&lt; <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-amdgpusplitmodule-cpp-/#a0c86b2852d6e78ed3aaaf412ed290186">CostType</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64189c990b43608f8c1c8121bb6ecaaf">Partitions</a></td>
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

<p>Represents a module splitting proposal.</p>


<p>Proposals are made of N BitVectors, one for each partition, where each bit set indicates that the node is present and should be copied inside that partition.</p>


<p>Proposals have several metrics attached so they can be compared/sorted, which the driver to try multiple strategies resultings in multiple proposals and choose the best one out of them.</p>


<p>Definition at line 760 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SplitProposal() {#a5260eb179c3a6fda24345ae0e6740556}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitProposal::SplitProposal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph">SplitGraph</a> &amp; SG, unsigned MaxPartitions)</td>
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



<p>Definition at line 762 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\[\]() {#a5836550f3b15be3dbc6d707dd8c2de45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BitVector &amp; llvm::anonymous{AMDGPUSplitModule.cpp}::SplitProposal::operator[] (unsigned PID)</td>
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



<p>Definition at line 769 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#ac598f5cbb000dbdd8adbf94cb2242e1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::anonymous{AMDGPUSplitModule.cpp}::SplitProposal::add (unsigned PID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; BV)</td>
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



<p>Definition at line 773 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>

</div>
</div>

### calculateScores() {#a7b2732b0f1d325de354b9a80d03768c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::anonymous{AMDGPUSplitModule.cpp}::SplitProposal::calculateScores ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate the CodeSize and Bottleneck scores.</p>

<p>Definition at line 786 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a7b2732b0f1d325de354b9a80d03768c3">calculateScores</a>.</p>


<p>Referenced by <a href="#a7b2732b0f1d325de354b9a80d03768c3">calculateScores</a>.</p>

</div>
</div>

### dump() {#a843229cfda9f61491b29bbf045507f4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void llvm::anonymous{AMDGPUSplitModule.cpp}::SplitProposal::dump ()</td>
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



<p>Definition at line 779 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aa9f638c7ae7fdd206a6c60e26bef9751">print</a>.</p>

</div>
</div>

### findCheapestPartition() {#a2c57a3c3b97578adb6ee510485e6eb47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::anonymous{AMDGPUSplitModule.cpp}::SplitProposal::findCheapestPartition ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 783 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="#a2c57a3c3b97578adb6ee510485e6eb47">findCheapestPartition</a> and <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-amdgpusplitmodule-cpp-/#a286dd4db76f60ca092a2a00292b5638d">llvm::anonymous{AMDGPUSplitModule.cpp}::InvalidPID</a>.</p>


<p>Referenced by <a href="#a2c57a3c3b97578adb6ee510485e6eb47">findCheapestPartition</a>.</p>

</div>
</div>

### getBottleneckScore() {#a8b7f24ee69de158b68769c29464e6b1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double llvm::anonymous{AMDGPUSplitModule.cpp}::SplitProposal::getBottleneckScore ()</td>
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

<p>Only available after <a href="#a7b2732b0f1d325de354b9a80d03768c3">calculateScores</a> is called.</p>


<p>A number between [0, 1] which indicates how big of a bottleneck is expected from the largest partition.</p>


<p>A score of 1.0 means the biggest partition is as big as the source module, so build time will be equal to or greater than the build time of the initial input.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is always rounded up to 3 decimal places.</p>


<p>This is one of the metrics used to estimate this proposal's build time.</p>


<p>Definition at line 815 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-amdgpusplitmodule-cpp-/#aa718ad43704d8324301fe03964cdc7c3">llvm::anonymous{AMDGPUSplitModule.cpp}::evaluateProposal</a>.</p>

</div>
</div>

### getCodeSizeScore() {#a2b814b24fd11bbfc3ffc4f289c8cd36b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double llvm::anonymous{AMDGPUSplitModule.cpp}::SplitProposal::getCodeSizeScore ()</td>
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

<p>Only available after <a href="#a7b2732b0f1d325de354b9a80d03768c3">calculateScores</a> is called.</p>


<p>A positive number indicating the % of code duplication that this proposal creates. e.g. 0.2 means this proposal adds roughly 20% code size by duplicating some functions across partitions.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is always rounded up to 3 decimal places.</p>


<p>A perfect score would be 0.0, and anything approaching 1.0 is very bad.</p>


<p>Definition at line 801 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-amdgpusplitmodule-cpp-/#aa718ad43704d8324301fe03964cdc7c3">llvm::anonymous{AMDGPUSplitModule.cpp}::evaluateProposal</a>.</p>

</div>
</div>

### getName() {#aa6aa5f53b7b30135cb3afbcf4e223091}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::anonymous{AMDGPUSplitModule.cpp}::SplitProposal::getName ()</td>
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



<p>Definition at line 767 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>

</div>
</div>

### print() {#a0215de52344b43a21c90bb5e2293a5fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::anonymous{AMDGPUSplitModule.cpp}::SplitProposal::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 778 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-amdgpusplitmodule-cpp-/#a2ffb58efadf5885f67a4ecd791d2b218">llvm::anonymous{AMDGPUSplitModule.cpp}::formatRatioOf</a> and <a href="#a0215de52344b43a21c90bb5e2293a5fb">print</a>.</p>


<p>Referenced by <a href="#a0215de52344b43a21c90bb5e2293a5fb">print</a>.</p>

</div>
</div>

### setName() {#a98f31ddf4352a17257ff914f32ddbd02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::anonymous{AMDGPUSplitModule.cpp}::SplitProposal::setName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> NewName)</td>
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



<p>Definition at line 766 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>

</div>
</div>

### verifyCompleteness() {#aa0d86d73dbaff64cd671fcc91556906d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::anonymous{AMDGPUSplitModule.cpp}::SplitProposal::verifyCompleteness ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 789 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#aa0d86d73dbaff64cd671fcc91556906d">verifyCompleteness</a>.</p>


<p>Referenced by <a href="#aa0d86d73dbaff64cd671fcc91556906d">verifyCompleteness</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### updateScore() {#aa4852101f030179131b282abd8b68472}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::anonymous{AMDGPUSplitModule.cpp}::SplitProposal::updateScore (unsigned PID)</td>
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



<p>Definition at line 818 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BottleneckScore {#a3a9d3c3b27a59332c8a125e379aab3d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double llvm::anonymous{AMDGPUSplitModule.cpp}::SplitProposal::BottleneckScore = 0.0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#a8b7f24ee69de158b68769c29464e6b1c">getBottleneckScore</a></p></dd>
</dl>


<p>Definition at line 830 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>

</div>
</div>

### CodeSizeScore {#a7dffdd74fdb3f63eb0575af92316ec0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double llvm::anonymous{AMDGPUSplitModule.cpp}::SplitProposal::CodeSizeScore = 0.0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#a2b814b24fd11bbfc3ffc4f289c8cd36b">getCodeSizeScore</a></p></dd>
</dl>


<p>Definition at line 828 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>

</div>
</div>

### Name {#a9aed4ef82f529f96d7e8722be8f5b8a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::anonymous{AMDGPUSplitModule.cpp}::SplitProposal::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 835 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>

</div>
</div>

### Partitions {#a64189c990b43608f8c1c8121bb6ecaaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::pair&lt;CostType, BitVector&gt; &gt; llvm::anonymous{AMDGPUSplitModule.cpp}::SplitProposal::Partitions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 837 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>

</div>
</div>

### SG {#a5be665118ca4eaa1f454bb07f789dfa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SplitGraph* llvm::anonymous{AMDGPUSplitModule.cpp}::SplitProposal::SG = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 834 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>

</div>
</div>

### TotalCost {#a68862bd778b559c366841f473aae424e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CostType llvm::anonymous{AMDGPUSplitModule.cpp}::SplitProposal::TotalCost = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Aggregated cost of all partitions.</p>

<p>Definition at line 832 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>

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
