---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/codelayout
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `codelayout` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::codelayout { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/codelayout/cdsortconfig">CDSortConfig</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Algorithm-specific params for Cache-Directed Sort. <a href="/web-llvm/docs/api/structs/llvm/codelayout/cdsortconfig/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/codelayout/edgecount">EdgeCount</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90363531d13b5ad0853e7604759d3a12">EdgeT</a> = std::pair&lt; uint64_t, uint64_t &gt;</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab265fb35ca9607f01d99dae7a386ef77">computeExtTspLayout</a> (ArrayRef&lt; uint64_t &gt; NodeSizes, ArrayRef&lt; uint64_t &gt; NodeCounts, ArrayRef&lt; EdgeCount &gt; EdgeCounts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find a layout of nodes (basic blocks) of a given CFG optimizing jump locality and thus processor I-cache utilization. <a href="#ab265fb35ca9607f01d99dae7a386ef77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70c3cab5f18ff0a00d4ad43ec3287021">calcExtTspScore</a> (ArrayRef&lt; uint64_t &gt; Order, ArrayRef&lt; uint64_t &gt; NodeSizes, ArrayRef&lt; EdgeCount &gt; EdgeCounts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Estimate the "quality" of a given node order in CFG. <a href="#a70c3cab5f18ff0a00d4ad43ec3287021">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9785654b9d9d59e9f47ceac3364de40">calcExtTspScore</a> (ArrayRef&lt; uint64_t &gt; NodeSizes, ArrayRef&lt; EdgeCount &gt; EdgeCounts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Estimate the "quality" of the current node order in CFG. <a href="#ab9785654b9d9d59e9f47ceac3364de40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40b559a61a165123bb62e26c941a223b">computeCacheDirectedLayout</a> (ArrayRef&lt; uint64_t &gt; FuncSizes, ArrayRef&lt; uint64_t &gt; FuncCounts, ArrayRef&lt; EdgeCount &gt; CallCounts, ArrayRef&lt; uint64_t &gt; CallOffsets)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply a Cache-Directed Sort for functions represented by a call graph. <a href="#a40b559a61a165123bb62e26c941a223b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73e7e6f4b8c90a37295178a56661de2d">computeCacheDirectedLayout</a> (const CDSortConfig &amp;Config, ArrayRef&lt; uint64_t &gt; FuncSizes, ArrayRef&lt; uint64_t &gt; FuncCounts, ArrayRef&lt; EdgeCount &gt; CallCounts, ArrayRef&lt; uint64_t &gt; CallOffsets)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply a Cache-Directed Sort with a custom config. <a href="#a73e7e6f4b8c90a37295178a56661de2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Typedefs

### EdgeT {#a90363531d13b5ad0853e7604759d3a12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::codelayout::EdgeT =  std::pair&lt;uint64_t, uint64_t&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codelayout-h">CodeLayout.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### calcExtTspScore() {#a70c3cab5f18ff0a00d4ad43ec3287021}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double llvm::codelayout::calcExtTspScore (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Order, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; NodeSizes, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codelayout/edgecount">EdgeCount</a> &gt; EdgeCounts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Estimate the "quality" of a given node order in CFG.</p>


<p>The higher the score, the better the order is. The score is designed to reflect the locality of the given order, which is anti-correlated with the number of I-cache misses in a typical execution of the function.</p>


<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codelayout-h">CodeLayout.h</a>, definition at line 1428 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-codelayout-cpp-/#a70ace5af72b93aedcb782ef65032c4de">anonymous{CodeLayout.cpp}::extTSPScore</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="#ab9785654b9d9d59e9f47ceac3364de40">calcExtTspScore</a>.</p>

</div>
</div>

### calcExtTspScore() {#ab9785654b9d9d59e9f47ceac3364de40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double llvm::codelayout::calcExtTspScore (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; NodeSizes, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codelayout/edgecount">EdgeCount</a> &gt; EdgeCounts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Estimate the "quality" of the current node order in CFG.</p>

<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codelayout-h">CodeLayout.h</a>, definition at line 1449 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>


<p>References <a href="#a70c3cab5f18ff0a00d4ad43ec3287021">calcExtTspScore</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### computeCacheDirectedLayout() {#a40b559a61a165123bb62e26c941a223b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; uint64_t &gt; llvm::codelayout::computeCacheDirectedLayout (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; FuncSizes, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; FuncCounts, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codelayout/edgecount">EdgeCount</a> &gt; CallCounts, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; CallOffsets)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Apply a Cache-Directed Sort for functions represented by a call graph.</p>


<p>The placement is done by optimizing the call locality by co-locating frequently executed functions. <span class="doxyComputerOutput">FuncSizes:</span> The sizes of the nodes (in bytes). <span class="doxyComputerOutput">FuncCounts:</span> The execution counts of the nodes in the profile. <span class="doxyComputerOutput">CallCounts:</span> The execution counts of every edge (jump) in the profile. The map also defines the edges in CFG and should include 0-count edges. <span class="doxyComputerOutput">CallOffsets:</span> The offsets of the calls from their source nodes.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The best function order found.</p></dd>
</dl>


<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codelayout-h">CodeLayout.h</a>, definition at line 1471 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp/#af31ae8dde941bfd375efe1a73c3fe173">CacheEntries</a>, <a href="/web-llvm/docs/api/structs/llvm/codelayout/cdsortconfig/#ad5722362bbe8b820f7171a89b500180e">llvm::codelayout::CDSortConfig::CacheEntries</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp/#a26daa24afdae1ccc5c868908b7c09feb">CacheSize</a>, <a href="/web-llvm/docs/api/structs/llvm/codelayout/cdsortconfig/#a9b3e2b25b382491b92cc2ec6d066dae9">llvm::codelayout::CDSortConfig::CacheSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp/#aee880aaf36e616387690904c6cec9d51">CDMaxChainSize</a>, <a href="#a40b559a61a165123bb62e26c941a223b">computeCacheDirectedLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp/#aaef85ddf5227bdda042d13ae0679dac3">DistancePower</a>, <a href="/web-llvm/docs/api/structs/llvm/codelayout/cdsortconfig/#ab8843f638794cf74c8044107ae618200">llvm::codelayout::CDSortConfig::DistancePower</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp/#a4cf66d46bbaf7f65eb485907e4ba3d77">FrequencyScale</a>, <a href="/web-llvm/docs/api/structs/llvm/codelayout/cdsortconfig/#acf9844a48ea378fd1887b0a4146a7af3">llvm::codelayout::CDSortConfig::FrequencyScale</a> and <a href="/web-llvm/docs/api/structs/llvm/codelayout/cdsortconfig/#a7ca32aeb071c565b99935586655ac847">llvm::codelayout::CDSortConfig::MaxChainSize</a>.</p>


<p>Referenced by <a href="#a40b559a61a165123bb62e26c941a223b">computeCacheDirectedLayout</a>.</p>

</div>
</div>

### computeCacheDirectedLayout() {#a73e7e6f4b8c90a37295178a56661de2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; uint64_t &gt; llvm::codelayout::computeCacheDirectedLayout (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/codelayout/cdsortconfig">CDSortConfig</a> &amp; Config, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; FuncSizes, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; FuncCounts, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codelayout/edgecount">EdgeCount</a> &gt; CallCounts, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; CallOffsets)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Apply a Cache-Directed Sort with a custom config.</p>

<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codelayout-h">CodeLayout.h</a>, definition at line 1457 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/anonymous-codelayout-cpp-/cdsortimpl/#a68a9823d565755fe71d5a54fb0262947">anonymous{CodeLayout.cpp}::CDSortImpl::CDSortImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### computeExtTspLayout() {#ab265fb35ca9607f01d99dae7a386ef77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; uint64_t &gt; llvm::codelayout::computeExtTspLayout (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; NodeSizes, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; NodeCounts, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codelayout/edgecount">EdgeCount</a> &gt; EdgeCounts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find a layout of nodes (basic blocks) of a given CFG optimizing jump locality and thus processor I-cache utilization.</p>


<p>This is achieved via increasing the number of fall-through jumps and co-locating frequently executed nodes together. The nodes are assumed to be indexed by integers from [0, |V|) so that the current order is the identity permutation. <span class="doxyComputerOutput">NodeSizes:</span> The sizes of the nodes (in bytes). <span class="doxyComputerOutput">NodeCounts:</span> The execution counts of the nodes in the profile. <span class="doxyComputerOutput">EdgeCounts:</span> The execution counts of every edge (jump) in the profile. The map also defines the edges in CFG and should include 0-count edges.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The best block order found.</p></dd>
</dl>


<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codelayout-h">CodeLayout.h</a>, definition at line 1411 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/anonymous-codelayout-cpp-/exttspimpl/#a47333daefb26df0fb055e84fc9a77d9d">anonymous{CodeLayout.cpp}::ExtTSPImpl::ExtTSPImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codelayout-h">CodeLayout.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
