---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-hotcoldsplitting-cpp-/outliningregion
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `OutliningRegion` Class

<p>A maximal outlining region. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{HotColdSplitting.cpp}::OutliningRegion { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb4320cb58bc4cbe61cd1e3c8e7f73f3">OutliningRegion</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f35d35f99dde67eaebf75393bee5275">OutliningRegion</a> (OutliningRegion &amp;&amp;)=default</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebdd1fd6521198094faf4f2b2229a4ff">OutliningRegion</a> (const OutliningRegion &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-hotcoldsplitting-cpp-/outliningregion">OutliningRegion</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add67f7f4d83727202d564d298c9e13ac">operator=</a> (OutliningRegion &amp;&amp;)=default</td>
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

## Private Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-hotcoldsplitting-cpp-/outliningregion">OutliningRegion</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb77049886673d713f7c1b537d58312c">operator=</a> (const OutliningRegion &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa311967da870ea02dda9f469e13f7b6e">empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether this region has nothing to extract. <a href="#aa311967da870ea02dda9f469e13f7b6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, unsigned &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa46fd5229e05fd19ab8885fd0449e7e7">blocks</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The blocks in this region. <a href="#aa46fd5229e05fd19ab8885fd0449e7e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11603ff4c792faf9ce03bd0c31d12e93">isEntireFunctionCold</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the entire function containing this region is cold. <a href="#a11603ff4c792faf9ce03bd0c31d12e93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a4896b3891581797e838017eb11e76221">BlockSequence</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a631ea87e33f8e50c1b90ae334ceea4c8">takeSingleEntrySubRegion</a> (DominatorTree &amp;DT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove a sub-region from this region and return it as a block sequence. <a href="#a631ea87e33f8e50c1b90ae334ceea4c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/hotcoldsplitting-cpp/#a0134180716271c522b7b0e1537ce7d9b">BlockTy</a>, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace6ae890f4e7aa267464886f5fbce68d">Blocks</a> = {}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A list of (block, score) pairs. <a href="#ace6ae890f4e7aa267464886f5fbce68d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc123ad80418ee9c05ce41828f5a9af2">SuggestedEntryPoint</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The suggested entry point into the region. <a href="#adc123ad80418ee9c05ce41828f5a9af2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adff91e87c433b9098aeff30d38daabfc">EntireFunctionCold</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the entire function is cold. <a href="#adff91e87c433b9098aeff30d38daabfc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::vector&lt; <a href="/web-llvm/docs/api/classes/anonymous-hotcoldsplitting-cpp-/outliningregion">OutliningRegion</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aead9a4f05ccb13941f28611766176f30">create</a> (BasicBlock &amp;SinkBB, const DominatorTree &amp;DT, const PostDominatorTree &amp;PDT)</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ee6c67827d545040e0faf02da6d85f8">getEntryPointScore</a> (BasicBlock &amp;BB, unsigned Score)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If <span class="doxyComputerOutput">BB</span> is a viable entry point, return <span class="doxyComputerOutput">Score</span>. Return 0 otherwise. <a href="#a9ee6c67827d545040e0faf02da6d85f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a292d8e312f6c5754a04cfadbe63cbfb2">ScoreForSuccBlock</a> = 1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>These scores should be lower than the score for predecessor blocks, because regions starting at predecessor blocks are typically larger. <a href="#a292d8e312f6c5754a04cfadbe63cbfb2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7675720de200796de9221d11a40b6a0">ScoreForSinkBlock</a> = 1</td>
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

<p>A maximal outlining region.</p>


<p>This contains all blocks post-dominated by a sink block, the sink block itself, and all blocks dominated by the sink. If sink-predecessors and sink-successors cannot be extracted in one region, the static constructor returns a list of suitable extraction regions.</p>


<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/hotcoldsplitting-cpp">HotColdSplitting.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### OutliningRegion() {#afb4320cb58bc4cbe61cd1e3c8e7f73f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{HotColdSplitting.cpp}::OutliningRegion::OutliningRegion ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/hotcoldsplitting-cpp">HotColdSplitting.cpp</a>.</p>

</div>
</div>

### OutliningRegion() {#a3f35d35f99dde67eaebf75393bee5275}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{HotColdSplitting.cpp}::OutliningRegion::OutliningRegion (<a href="/web-llvm/docs/api/classes/anonymous-hotcoldsplitting-cpp-/outliningregion">OutliningRegion</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/hotcoldsplitting-cpp">HotColdSplitting.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### OutliningRegion() {#aebdd1fd6521198094faf4f2b2229a4ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{HotColdSplitting.cpp}::OutliningRegion::OutliningRegion (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-hotcoldsplitting-cpp-/outliningregion">OutliningRegion</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 487 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/hotcoldsplitting-cpp">HotColdSplitting.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#add67f7f4d83727202d564d298c9e13ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutliningRegion &amp; anonymous{HotColdSplitting.cpp}::OutliningRegion::operator= (<a href="/web-llvm/docs/api/classes/anonymous-hotcoldsplitting-cpp-/outliningregion">OutliningRegion</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/hotcoldsplitting-cpp">HotColdSplitting.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Operators

### operator=() {#acb77049886673d713f7c1b537d58312c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutliningRegion &amp; anonymous{HotColdSplitting.cpp}::OutliningRegion::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-hotcoldsplitting-cpp-/outliningregion">OutliningRegion</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 488 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/hotcoldsplitting-cpp">HotColdSplitting.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### blocks() {#aa46fd5229e05fd19ab8885fd0449e7e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; std::pair&lt; BasicBlock *, unsigned &gt; &gt; anonymous{HotColdSplitting.cpp}::OutliningRegion::blocks ()</td>
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

<p>The blocks in this region.</p>

<p>Definition at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/hotcoldsplitting-cpp">HotColdSplitting.cpp</a>.</p>

</div>
</div>

### empty() {#aa311967da870ea02dda9f469e13f7b6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{HotColdSplitting.cpp}::OutliningRegion::empty ()</td>
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

<p>Whether this region has nothing to extract.</p>

<p>Definition at line 597 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/hotcoldsplitting-cpp">HotColdSplitting.cpp</a>.</p>


<p>Referenced by <a href="#a631ea87e33f8e50c1b90ae334ceea4c8">takeSingleEntrySubRegion</a>.</p>

</div>
</div>

### isEntireFunctionCold() {#a11603ff4c792faf9ce03bd0c31d12e93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{HotColdSplitting.cpp}::OutliningRegion::isEntireFunctionCold ()</td>
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

<p>Whether the entire function containing this region is cold.</p>

<p>Definition at line 603 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/hotcoldsplitting-cpp">HotColdSplitting.cpp</a>.</p>


<p>Referenced by <a href="#a631ea87e33f8e50c1b90ae334ceea4c8">takeSingleEntrySubRegion</a>.</p>

</div>
</div>

### takeSingleEntrySubRegion() {#a631ea87e33f8e50c1b90ae334ceea4c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockSequence anonymous{HotColdSplitting.cpp}::OutliningRegion::takeSingleEntrySubRegion (<a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT)</td>
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

<p>Remove a sub-region from this region and return it as a block sequence.</p>

<p>Definition at line 606 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/hotcoldsplitting-cpp">HotColdSplitting.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#a5c69311e8d44898dac36a155c3d8691d">llvm::DominatorTree::dominates</a>, <a href="#aa311967da870ea02dda9f469e13f7b6e">empty</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a>, <a href="#a11603ff4c792faf9ce03bd0c31d12e93">isEntireFunctionCold</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9ec2517b6489e71067be03afebb4d350">llvm::remove_if</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Blocks {#ace6ae890f4e7aa267464886f5fbce68d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;BlockTy, 0&gt; anonymous{HotColdSplitting.cpp}::OutliningRegion::Blocks = {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A list of (block, score) pairs.</p>


<p>A block's score is non-zero iff it's a viable sub-region entry point. Blocks with higher scores are better entry points (i.e. they are more distant ancestors of the sink block).</p>


<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/hotcoldsplitting-cpp">HotColdSplitting.cpp</a>.</p>

</div>
</div>

### EntireFunctionCold {#adff91e87c433b9098aeff30d38daabfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{HotColdSplitting.cpp}::OutliningRegion::EntireFunctionCold = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether the entire function is cold.</p>

<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/hotcoldsplitting-cpp">HotColdSplitting.cpp</a>.</p>

</div>
</div>

### SuggestedEntryPoint {#adc123ad80418ee9c05ce41828f5a9af2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* anonymous{HotColdSplitting.cpp}::OutliningRegion::SuggestedEntryPoint = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The suggested entry point into the region.</p>


<p>If the region has multiple entry points, all blocks within the region may not be reachable from this entry point.</p>


<p>Definition at line 472 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/hotcoldsplitting-cpp">HotColdSplitting.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#aead9a4f05ccb13941f28611766176f30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; OutliningRegion &gt; anonymous{HotColdSplitting.cpp}::OutliningRegion::create (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; SinkBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a> &amp; PDT)</td>
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



<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/hotcoldsplitting-cpp">HotColdSplitting.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a4c46542f8881cacd05836ba00ab8ec">llvm::df_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad6c4441c599522e0d10c1391a460c275">llvm::df_end</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#a5c69311e8d44898dac36a155c3d8691d">llvm::DominatorTree::dominates</a>, <a href="/web-llvm/docs/api/classes/llvm/postdominatortree/#ac74ec035b8eeaeb39cfea312fa876c75">llvm::PostDominatorTree::dominates</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abe62b2144b4f06c41efe3c775316f282">llvm::idf_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ea0b29d9cab61cc46291acf44187279">llvm::idf_end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hotcoldsplitting-cpp-/#aef2714d7816ffbf7f4eebf159be19d1f">anonymous{HotColdSplitting.cpp}::mayExtractBlock</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad66c4759666aab78529658362b498c74">llvm::pred_empty</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getEntryPointScore() {#a9ee6c67827d545040e0faf02da6d85f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{HotColdSplitting.cpp}::OutliningRegion::getEntryPointScore (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB, unsigned Score)</td>
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

<p>If <span class="doxyComputerOutput">BB</span> is a viable entry point, return <span class="doxyComputerOutput">Score</span>. Return 0 otherwise.</p>

<p>Definition at line 478 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/hotcoldsplitting-cpp">HotColdSplitting.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### ScoreForSinkBlock {#ab7675720de200796de9221d11a40b6a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{HotColdSplitting.cpp}::OutliningRegion::ScoreForSinkBlock = 1</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/hotcoldsplitting-cpp">HotColdSplitting.cpp</a>.</p>

</div>
</div>

### ScoreForSuccBlock {#a292d8e312f6c5754a04cfadbe63cbfb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{HotColdSplitting.cpp}::OutliningRegion::ScoreForSuccBlock = 1</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>These scores should be lower than the score for predecessor blocks, because regions starting at predecessor blocks are typically larger.</p>

<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/hotcoldsplitting-cpp">HotColdSplitting.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/hotcoldsplitting-cpp">HotColdSplitting.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
