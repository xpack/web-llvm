---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/blockfrequencyinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `BlockFrequencyInfo` Class

<p><a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> pass uses <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimpl">BlockFrequencyInfoImpl</a> implementation to estimate IR basic block frequencies. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::BlockFrequencyInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">llvm/Analysis/BlockFrequencyInfo.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f808d2e24f8c80d50be3a1636fe8abf">ImplType</a> = <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimpl">BlockFrequencyInfoImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63f02875db1a565606e8eea6bb05db1b">BlockFrequencyInfo</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a875729888376d4b8c4a0426242bdaf39">BlockFrequencyInfo</a> (const Function &amp;F, const BranchProbabilityInfo &amp;BPI, const LoopInfo &amp;LI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd2bac681140481173c55877752d2886">BlockFrequencyInfo</a> (const BlockFrequencyInfo &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96d2c7b1813f8c4e09e9cc137841c6d0">BlockFrequencyInfo</a> (BlockFrequencyInfo &amp;&amp;Arg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1866a9f48f05827180a76af09f9fd59d">~BlockFrequencyInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a557c1b880e465c1e2cdb22603d079d82">operator=</a> (const BlockFrequencyInfo &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bc86f75614469a44de970fed4de97f0">operator=</a> (BlockFrequencyInfo &amp;&amp;RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada47feae78e3f75c04c5474d5d805b09">invalidate</a> (Function &amp;F, const PreservedAnalyses &amp;PA, FunctionAnalysisManager::Invalidator &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle invalidation explicitly. <a href="#ada47feae78e3f75c04c5474d5d805b09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e347b3d4af60ff4752900497cb60fbb">getFunction</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo">BranchProbabilityInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a890d37fd94628447295e95a4ed325fc8">getBPI</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69b85e6e41851b721a5bc1adc3d2f661">view</a> (StringRef="BlockFrequencyDAGs") const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pop up a ghostview window with the current block frequency propagation rendered using dot. <a href="#a69b85e6e41851b721a5bc1adc3d2f661">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8b72c18add22acd827f7a6cd1ff1bff">getBlockFreq</a> (const BasicBlock *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getblockFreq - Return block frequency. <a href="#ab8b72c18add22acd827f7a6cd1ff1bff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45e6b2c5c4e59ddc05ad9a2685706e75">getBlockProfileCount</a> (const BasicBlock *BB, bool AllowSynthetic=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the estimated profile count of <span class="doxyComputerOutput">BB</span>. <a href="#a45e6b2c5c4e59ddc05ad9a2685706e75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02c90557d0de0a6573903a55ef08f20d">getProfileCountFromFreq</a> (BlockFrequency Freq) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the estimated profile count of <span class="doxyComputerOutput">Freq</span>. <a href="#a02c90557d0de0a6573903a55ef08f20d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0057533e78de6c22b6d3dd3ae3ec0b5f">isIrrLoopHeader</a> (const BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">BB</span> is an irreducible loop header block. <a href="#a0057533e78de6c22b6d3dd3ae3ec0b5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13f090421b36f5795113215ab6c507ce">setBlockFreq</a> (const BasicBlock *BB, BlockFrequency Freq)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79d23612ec0c59f4c30ccfabfc2b312c">setBlockFreqAndScale</a> (const BasicBlock *ReferenceBB, BlockFrequency Freq, SmallPtrSetImpl&lt; BasicBlock * &gt; &amp;BlocksToScale)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the frequency of <span class="doxyComputerOutput">ReferenceBB</span> to <span class="doxyComputerOutput">Freq</span> and scale the frequencies of the blocks in <span class="doxyComputerOutput">BlocksToScale</span> such that their frequencies relative to <span class="doxyComputerOutput">ReferenceBB</span> remain unchanged. <a href="#a79d23612ec0c59f4c30ccfabfc2b312c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a028fa7f559c340968f4faefbd899e69b">calculate</a> (const Function &amp;F, const BranchProbabilityInfo &amp;BPI, const LoopInfo &amp;LI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>calculate - compute block frequency info for the given function. <a href="#a028fa7f559c340968f4faefbd899e69b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c6cc2749829526cefbb731b0474e0be">getEntryFreq</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0ed2aa793189babbd64c24e1cb77156">releaseMemory</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcdff384c4765fb588d0c50c973f2168">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeec3f4d44d62f63f2bdd75c0379c83f0">verifyMatch</a> (BlockFrequencyInfo &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimpl">ImplType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48a6a13446724cf4a56d3d6a0ca34792">BFI</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> pass uses <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimpl">BlockFrequencyInfoImpl</a> implementation to estimate IR basic block frequencies.</p>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">BlockFrequencyInfo.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### ImplType {#a2f808d2e24f8c80d50be3a1636fe8abf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::BlockFrequencyInfo::ImplType =  BlockFrequencyInfoImpl&lt;BasicBlock&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">BlockFrequencyInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### BlockFrequencyInfo() {#a63f02875db1a565606e8eea6bb05db1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequencyInfo::BlockFrequencyInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">BlockFrequencyInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#a96d2c7b1813f8c4e09e9cc137841c6d0">BlockFrequencyInfo</a>, <a href="#afd2bac681140481173c55877752d2886">BlockFrequencyInfo</a>, <a href="#a7bc86f75614469a44de970fed4de97f0">operator=</a>, <a href="#a557c1b880e465c1e2cdb22603d079d82">operator=</a>, <a href="#aeec3f4d44d62f63f2bdd75c0379c83f0">verifyMatch</a>, <a href="#a69b85e6e41851b721a5bc1adc3d2f661">view</a> and <a href="#a1866a9f48f05827180a76af09f9fd59d">~BlockFrequencyInfo</a>.</p>

</div>
</div>

### BlockFrequencyInfo() {#a875729888376d4b8c4a0426242bdaf39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequencyInfo::BlockFrequencyInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo">BranchProbabilityInfo</a> &amp; BPI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">BlockFrequencyInfo.h</a>, definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp">BlockFrequencyInfo.cpp</a>.</p>


<p>References <a href="#a028fa7f559c340968f4faefbd899e69b">calculate</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### BlockFrequencyInfo() {#afd2bac681140481173c55877752d2886}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BlockFrequencyInfo::BlockFrequencyInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> &amp;)</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">BlockFrequencyInfo.h</a>.</p>


<p>Reference <a href="#a63f02875db1a565606e8eea6bb05db1b">BlockFrequencyInfo</a>.</p>

</div>
</div>

### BlockFrequencyInfo() {#a96d2c7b1813f8c4e09e9cc137841c6d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequencyInfo::BlockFrequencyInfo (<a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> &amp;&amp; Arg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">BlockFrequencyInfo.h</a>, definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp">BlockFrequencyInfo.cpp</a>.</p>


<p>References <a href="#a63f02875db1a565606e8eea6bb05db1b">BlockFrequencyInfo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~BlockFrequencyInfo() {#a1866a9f48f05827180a76af09f9fd59d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequencyInfo::~BlockFrequencyInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">BlockFrequencyInfo.h</a>.</p>


<p>References <a href="#a63f02875db1a565606e8eea6bb05db1b">BlockFrequencyInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a557c1b880e465c1e2cdb22603d079d82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequencyInfo &amp; llvm::BlockFrequencyInfo::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> &amp;)</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">BlockFrequencyInfo.h</a>.</p>


<p>References <a href="#a63f02875db1a565606e8eea6bb05db1b">BlockFrequencyInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator=() {#a7bc86f75614469a44de970fed4de97f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequencyInfo &amp; BlockFrequencyInfo::operator= (<a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> &amp;&amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">BlockFrequencyInfo.h</a>, definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp">BlockFrequencyInfo.cpp</a>.</p>


<p>References <a href="#a63f02875db1a565606e8eea6bb05db1b">BlockFrequencyInfo</a> and <a href="#ad0ed2aa793189babbd64c24e1cb77156">releaseMemory</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### calculate() {#a028fa7f559c340968f4faefbd899e69b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BlockFrequencyInfo::calculate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo">BranchProbabilityInfo</a> &amp; BPI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>calculate - compute block frequency info for the given function.</p>

<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">BlockFrequencyInfo.h</a>, definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp">BlockFrequencyInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af0bf055834b973decc2477a8061624ffa49315903a2559d882f356ae28a455556">llvm::GVDT_None</a>, <a href="#abcdff384c4765fb588d0c50c973f2168">print</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2989956d53d56f7227c7d36891c73f4f">llvm::PrintBFI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a12ed6cda79362a16ba48b0849cf00df2">llvm::PrintBFIFuncName</a>, <a href="#a69b85e6e41851b721a5bc1adc3d2f661">view</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6391a34afa5b4ed1a5e556a8cc4d971b">llvm::ViewBlockFreqFuncName</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp/#a2d6116a6ffd9acfeb0f3975c7317646d">ViewBlockFreqPropagationDAG</a>.</p>


<p>Referenced by <a href="#a875729888376d4b8c4a0426242bdaf39">BlockFrequencyInfo</a>.</p>

</div>
</div>

### getBlockFreq() {#ab8b72c18add22acd827f7a6cd1ff1bff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequency BlockFrequencyInfo::getBlockFreq (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getblockFreq - Return block frequency.</p>


<p>Return 0 if we don't have the information. Please note that initial frequency is equal to ENTRY_FREQ. It means that we should not rely on the value itself, but only on the comparison to the other block frequencies. We do this to avoid using of floating points.</p>


<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">BlockFrequencyInfo.h</a>, definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp">BlockFrequencyInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a652ede21e988a4de569cdbc7863ea234">isColdCallSite</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a83a2e4a8c4f5b3b8dee5407d55e8872d">updateCallerBFI</a>.</p>

</div>
</div>

### getBlockProfileCount() {#a45e6b2c5c4e59ddc05ad9a2685706e75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; BlockFrequencyInfo::getBlockProfileCount (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, bool AllowSynthetic=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the estimated profile count of <span class="doxyComputerOutput">BB</span>.</p>


<p>This computes the relative block frequency of <span class="doxyComputerOutput">BB</span> and multiplies it by the enclosing function's count (if available) and returns the value.</p>


<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">BlockFrequencyInfo.h</a>, definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp">BlockFrequencyInfo.cpp</a>.</p>


<p>Reference <a href="#a1e347b3d4af60ff4752900497cb60fbb">getFunction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a13254d395258a157ea8ce4a0e1a96050">fixFuncEntryCount</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a6c13c3a269c58cac403ad567c29d679e">verifyFuncBFI</a>.</p>

</div>
</div>

### getBPI() {#a890d37fd94628447295e95a4ed325fc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BranchProbabilityInfo * BlockFrequencyInfo::getBPI ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">BlockFrequencyInfo.h</a>, definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp">BlockFrequencyInfo.cpp</a>.</p>

</div>
</div>

### getEntryFreq() {#a9c6cc2749829526cefbb731b0474e0be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequency BlockFrequencyInfo::getEntryFreq ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">BlockFrequencyInfo.h</a>, definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp">BlockFrequencyInfo.cpp</a>.</p>

</div>
</div>

### getFunction() {#a1e347b3d4af60ff4752900497cb60fbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function * BlockFrequencyInfo::getFunction ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">BlockFrequencyInfo.h</a>, definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp">BlockFrequencyInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/function/#a8743c58384e11cb6228f6f871304ad35">llvm::Function::getFunction</a>.</p>


<p>Referenced by <a href="#a45e6b2c5c4e59ddc05ad9a2685706e75">getBlockProfileCount</a> and <a href="#a02c90557d0de0a6573903a55ef08f20d">getProfileCountFromFreq</a>.</p>

</div>
</div>

### getProfileCountFromFreq() {#a02c90557d0de0a6573903a55ef08f20d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; BlockFrequencyInfo::getProfileCountFromFreq (<a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> Freq)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the estimated profile count of <span class="doxyComputerOutput">Freq</span>.</p>


<p>This uses the frequency <span class="doxyComputerOutput">Freq</span> and multiplies it by the enclosing function's count (if available) and returns the value.</p>


<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">BlockFrequencyInfo.h</a>, definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp">BlockFrequencyInfo.cpp</a>.</p>


<p>Reference <a href="#a1e347b3d4af60ff4752900497cb60fbb">getFunction</a>.</p>

</div>
</div>

### invalidate() {#ada47feae78e3f75c04c5474d5d805b09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BlockFrequencyInfo::invalidate (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PreservedAnalyses &amp; PA, FunctionAnalysisManager::Invalidator &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handle invalidation explicitly.</p>

<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">BlockFrequencyInfo.h</a>, definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp">BlockFrequencyInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### isIrrLoopHeader() {#a0057533e78de6c22b6d3dd3ae3ec0b5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BlockFrequencyInfo::isIrrLoopHeader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if <span class="doxyComputerOutput">BB</span> is an irreducible loop header block.</p>


<p>Otherwise false.</p>


<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">BlockFrequencyInfo.h</a>, definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp">BlockFrequencyInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### print() {#abcdff384c4765fb588d0c50c973f2168}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BlockFrequencyInfo::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">BlockFrequencyInfo.h</a>, definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp">BlockFrequencyInfo.cpp</a>.</p>


<p>Referenced by <a href="#a028fa7f559c340968f4faefbd899e69b">calculate</a>.</p>

</div>
</div>

### releaseMemory() {#ad0ed2aa793189babbd64c24e1cb77156}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BlockFrequencyInfo::releaseMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">BlockFrequencyInfo.h</a>, definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp">BlockFrequencyInfo.cpp</a>.</p>


<p>Referenced by <a href="#a7bc86f75614469a44de970fed4de97f0">operator=</a>.</p>

</div>
</div>

### setBlockFreq() {#a13f090421b36f5795113215ab6c507ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BlockFrequencyInfo::setBlockFreq (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> Freq)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">BlockFrequencyInfo.h</a>, definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp">BlockFrequencyInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a83a2e4a8c4f5b3b8dee5407d55e8872d">updateCallerBFI</a>.</p>

</div>
</div>

### setBlockFreqAndScale() {#a79d23612ec0c59f4c30ccfabfc2b312c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BlockFrequencyInfo::setBlockFreqAndScale (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * ReferenceBB, <a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> Freq, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; BlocksToScale)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the frequency of <span class="doxyComputerOutput">ReferenceBB</span> to <span class="doxyComputerOutput">Freq</span> and scale the frequencies of the blocks in <span class="doxyComputerOutput">BlocksToScale</span> such that their frequencies relative to <span class="doxyComputerOutput">ReferenceBB</span> remain unchanged.</p>

<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">BlockFrequencyInfo.h</a>, definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp">BlockFrequencyInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a9541bbf765f7db0b078a45d6f43c34b4a8cb28931840da67702e5bd9068512905">BBFreq</a> and <a href="/web-llvm/docs/api/classes/llvm/blockfrequency/#a8e9ed6b20c2503f66f1fd0725297aedc">llvm::BlockFrequency::getFrequency</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a83a2e4a8c4f5b3b8dee5407d55e8872d">updateCallerBFI</a>.</p>

</div>
</div>

### verifyMatch() {#aeec3f4d44d62f63f2bdd75c0379c83f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BlockFrequencyInfo::verifyMatch (<a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">BlockFrequencyInfo.h</a>, definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp">BlockFrequencyInfo.cpp</a>.</p>


<p>References <a href="#a63f02875db1a565606e8eea6bb05db1b">BlockFrequencyInfo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### view() {#a69b85e6e41851b721a5bc1adc3d2f661}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BlockFrequencyInfo::view (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> title="BlockFrequencyDAGs")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pop up a ghostview window with the current block frequency propagation rendered using dot.</p>

<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">BlockFrequencyInfo.h</a>, definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp">BlockFrequencyInfo.cpp</a>.</p>


<p>References <a href="#a63f02875db1a565606e8eea6bb05db1b">BlockFrequencyInfo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab8635363d4287c93f64c55ad5567fcf0">llvm::ViewGraph</a>.</p>


<p>Referenced by <a href="#a028fa7f559c340968f4faefbd899e69b">calculate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BFI {#a48a6a13446724cf4a56d3d6a0ca34792}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ImplType&gt; llvm::BlockFrequencyInfo::BFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">BlockFrequencyInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">BlockFrequencyInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp">BlockFrequencyInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
