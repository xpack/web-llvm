---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/blockcoverageinference
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BlockCoverageInference` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::BlockCoverageInference { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/blockcoverageinference-h">llvm/Transforms/Instrumentation/BlockCoverageInference.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae32601a7bb4649eaebb6123b7c000dd1">BlockSet</a> = <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 4 &gt;</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bf078f29dedeabd2954933fc1d93919">DotFuncBCIInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ec2012966b48e628d0afe7fb3a01f8b">BlockCoverageInference</a> (const Function &amp;F, bool ForceInstrumentEntry)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cd68a41956d11d1d2647c1de065b1e0">shouldInstrumentBlock</a> (const BasicBlock &amp;BB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae32601a7bb4649eaebb6123b7c000dd1">BlockSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe4e816c7ba92d54465becab471317c1">getDependencies</a> (const BasicBlock &amp;BB) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09b2833329e8e77c280ce50d1f6f560e">getInstrumentedBlocksHash</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0091b4d3d6e228e4b82c8cdb56363754">dump</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump the inference graph. <a href="#a0091b4d3d6e228e4b82c8cdb56363754">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cb0caabfbfedc60d222a51bde7d5525">viewBlockCoverageGraph</a> (const DenseMap&lt; const BasicBlock *, bool &gt; *Coverage=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>View the inferred block coverage as a dot file. <a href="#a6cb0caabfbfedc60d222a51bde7d5525">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13b68c7195bdb8b2d6f35c638f5576d4">findDependencies</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute <span class="doxyComputerOutput">PredecessorDependencies</span> and <span class="doxyComputerOutput">SuccessorDependencies</span>. <a href="#a13b68c7195bdb8b2d6f35c638f5576d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24eb58426a7363bce23ab376b021315a">getReachableAvoiding</a> (const BasicBlock &amp;Start, const BasicBlock &amp;Avoid, bool IsForward, BlockSet &amp;Reachable) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the set of basic blocks that are reachable from <span class="doxyComputerOutput">Start</span> without the basic block <span class="doxyComputerOutput">Avoid</span>. <a href="#a24eb58426a7363bce23ab376b021315a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a125c045caf4fa2af0fbd75e6e992b17b">F</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad3ccb4e767fcb9922f425f2e4c2ef6f">ForceInstrumentEntry</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="#ae32601a7bb4649eaebb6123b7c000dd1">BlockSet</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbbbdc38bb1cf2e832c8e56d912acf03">PredecessorDependencies</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps blocks to a minimal list of predecessors that can be used to infer this block's coverage. <a href="#adbbbdc38bb1cf2e832c8e56d912acf03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="#ae32601a7bb4649eaebb6123b7c000dd1">BlockSet</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6d368d838595003301c7155fa8d75ef">SuccessorDependencies</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps blocks to a minimal list of successors that can be used to infer this block's coverage. <a href="#ad6d368d838595003301c7155fa8d75ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33effb9cf781bc56c76077efc94d9e1f">getBlockNames</a> (ArrayRef&lt; const BasicBlock * &gt; BBs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a825a3b2183f11ef3e2c5cef04311c9dd">getBlockNames</a> (BlockSet BBs)</td>
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


<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/blockcoverageinference-h">BlockCoverageInference.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### BlockSet {#ae32601a7bb4649eaebb6123b7c000dd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::BlockCoverageInference::BlockSet =  SmallSetVector&lt;const BasicBlock *, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/blockcoverageinference-h">BlockCoverageInference.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### DotFuncBCIInfo {#a9bf078f29dedeabd2954933fc1d93919}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/dotfuncbciinfo">DotFuncBCIInfo</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/blockcoverageinference-h">BlockCoverageInference.h</a>.</p>


<p>Reference <a href="#a9bf078f29dedeabd2954933fc1d93919">DotFuncBCIInfo</a>.</p>


<p>Referenced by <a href="#a9bf078f29dedeabd2954933fc1d93919">DotFuncBCIInfo</a> and <a href="#a6cb0caabfbfedc60d222a51bde7d5525">viewBlockCoverageGraph</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### BlockCoverageInference() {#a7ec2012966b48e628d0afe7fb3a01f8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockCoverageInference::BlockCoverageInference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, bool ForceInstrumentEntry)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/blockcoverageinference-h">BlockCoverageInference.h</a>, definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/blockcoverageinference-cpp">BlockCoverageInference.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a2cd68a41956d11d1d2647c1de065b1e0">shouldInstrumentBlock</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a0091b4d3d6e228e4b82c8cdb56363754}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BlockCoverageInference::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump the inference graph.</p>

<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/blockcoverageinference-h">BlockCoverageInference.h</a>, definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/blockcoverageinference-cpp">BlockCoverageInference.cpp</a>.</p>


<p>References <a href="#a09b2833329e8e77c280ce50d1f6f560e">getInstrumentedBlocksHash</a>, <a href="#a2cd68a41956d11d1d2647c1de065b1e0">shouldInstrumentBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a>.</p>

</div>
</div>

### getDependencies() {#abe4e816c7ba92d54465becab471317c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockCoverageInference::BlockSet BlockCoverageInference::getDependencies (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the set of blocks <span class="doxyComputerOutput">Deps</span> such that <span class="doxyComputerOutput">BB</span> is covered iff any blocks in <span class="doxyComputerOutput">Deps</span> are covered.</p></dd>
</dl>


<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/blockcoverageinference-h">BlockCoverageInference.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/blockcoverageinference-cpp">BlockCoverageInference.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a1b4bf7c97cdc8159fd73d48063f0b250">llvm::BasicBlock::getParent</a> and <a href="/web-llvm/docs/api/classes/llvm/setvector/#a66af03d5b92dcc21371703b525509956">llvm::SetVector&lt; T, Vector, Set, N &gt;::set_union</a>.</p>

</div>
</div>

### getInstrumentedBlocksHash() {#a09b2833329e8e77c280ce50d1f6f560e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t BlockCoverageInference::getInstrumentedBlocksHash ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a hash that depends on the set of instrumented blocks.</p></dd>
</dl>


<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/blockcoverageinference-h">BlockCoverageInference.h</a>, definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/blockcoverageinference-cpp">BlockCoverageInference.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/jamcrc/#a90e799935e361788dee83dfb9b2d5099">llvm::JamCRC::getCRC</a>, <a href="#a2cd68a41956d11d1d2647c1de065b1e0">shouldInstrumentBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/jamcrc/#af4c43564c4a47b6d9741736e3962e279">llvm::JamCRC::update</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a46eee35129898d0466b2af97eacb19ee">llvm::support::endian::write64le</a>.</p>


<p>Referenced by <a href="#a0091b4d3d6e228e4b82c8cdb56363754">dump</a>.</p>

</div>
</div>

### shouldInstrumentBlock() {#a2cd68a41956d11d1d2647c1de065b1e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BlockCoverageInference::shouldInstrumentBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if <span class="doxyComputerOutput">BB</span> should be instrumented for coverage.</p></dd>
</dl>


<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/blockcoverageinference-h">BlockCoverageInference.h</a>, definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/blockcoverageinference-cpp">BlockCoverageInference.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a1b4bf7c97cdc8159fd73d48063f0b250">llvm::BasicBlock::getParent</a>.</p>


<p>Referenced by <a href="#a7ec2012966b48e628d0afe7fb3a01f8b">BlockCoverageInference</a>, <a href="#a0091b4d3d6e228e4b82c8cdb56363754">dump</a> and <a href="#a09b2833329e8e77c280ce50d1f6f560e">getInstrumentedBlocksHash</a>.</p>

</div>
</div>

### viewBlockCoverageGraph() {#a6cb0caabfbfedc60d222a51bde7d5525}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BlockCoverageInference::viewBlockCoverageGraph (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, bool &gt; * Coverage=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>View the inferred block coverage as a dot file.</p>


<p>Filled gray blocks are instrumented, red outlined blocks are found to be covered, red edges show that a block's coverage can be inferred from its successors, and blue edges show that a block's coverage can be inferred from its predecessors.</p>


<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/blockcoverageinference-h">BlockCoverageInference.h</a>, definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/blockcoverageinference-cpp">BlockCoverageInference.cpp</a>.</p>


<p>References <a href="#a9bf078f29dedeabd2954933fc1d93919">DotFuncBCIInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a45fc498e695e5b2061ab5e6ec8e604a1">llvm::WriteGraph</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### findDependencies() {#a13b68c7195bdb8b2d6f35c638f5576d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BlockCoverageInference::findDependencies ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute <span class="doxyComputerOutput">PredecessorDependencies</span> and <span class="doxyComputerOutput">SuccessorDependencies</span>.</p>

<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/blockcoverageinference-h">BlockCoverageInference.h</a>, definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/blockcoverageinference-cpp">BlockCoverageInference.cpp</a>.</p>

</div>
</div>

### getReachableAvoiding() {#a24eb58426a7363bce23ab376b021315a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BlockCoverageInference::getReachableAvoiding (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; Start, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; Avoid, bool IsForward, <a href="#ae32601a7bb4649eaebb6123b7c000dd1">BlockSet</a> &amp; Reachable)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the set of basic blocks that are reachable from <span class="doxyComputerOutput">Start</span> without the basic block <span class="doxyComputerOutput">Avoid</span>.</p>

<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/blockcoverageinference-h">BlockCoverageInference.h</a>, definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/blockcoverageinference-cpp">BlockCoverageInference.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### F {#a125c045caf4fa2af0fbd75e6e992b17b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function&amp; llvm::BlockCoverageInference::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/blockcoverageinference-h">BlockCoverageInference.h</a>.</p>

</div>
</div>

### ForceInstrumentEntry {#aad3ccb4e767fcb9922f425f2e4c2ef6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BlockCoverageInference::ForceInstrumentEntry</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/blockcoverageinference-h">BlockCoverageInference.h</a>.</p>

</div>
</div>

### PredecessorDependencies {#adbbbdc38bb1cf2e832c8e56d912acf03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const BasicBlock *, BlockSet&gt; llvm::BlockCoverageInference::PredecessorDependencies</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps blocks to a minimal list of predecessors that can be used to infer this block's coverage.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/blockcoverageinference-h">BlockCoverageInference.h</a>.</p>

</div>
</div>

### SuccessorDependencies {#ad6d368d838595003301c7155fa8d75ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const BasicBlock *, BlockSet&gt; llvm::BlockCoverageInference::SuccessorDependencies</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps blocks to a minimal list of successors that can be used to infer this block's coverage.</p>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/blockcoverageinference-h">BlockCoverageInference.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getBlockNames() {#a33effb9cf781bc56c76077efc94d9e1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string BlockCoverageInference::getBlockNames (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; BBs)</td>
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



<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/blockcoverageinference-h">BlockCoverageInference.h</a>, definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/blockcoverageinference-cpp">BlockCoverageInference.cpp</a>.</p>

</div>
</div>

### getBlockNames() {#a825a3b2183f11ef3e2c5cef04311c9dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::BlockCoverageInference::getBlockNames (<a href="#ae32601a7bb4649eaebb6123b7c000dd1">BlockSet</a> BBs)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/blockcoverageinference-h">BlockCoverageInference.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/blockcoverageinference-h">BlockCoverageInference.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/blockcoverageinference-cpp">BlockCoverageInference.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
