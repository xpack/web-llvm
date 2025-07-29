---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-armparalleldsp-cpp-/armparalleldsp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ARMParallelDSP` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{ARMParallelDSP.cpp}::ARMParallelDSP { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a630ad39d94e6a277c4fe4897dca2d6">ARMParallelDSP</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a150618f73ac168f3449ea9325dc36b81">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job. <a href="#a150618f73ac168f3449ea9325dc36b81">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae40feb69d50495a1f334abd82dd64e87">runOnFunction</a> (Function &amp;F) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnFunction - Virtual method overriden by subclasses to do the per-function processing of the pass. <a href="#ae40feb69d50495a1f334abd82dd64e87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned MaxBitWidth&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a14816bda1c3d93504862f538b8552b2c">IsNarrowSequence</a> (Value *V)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a14816bda1c3d93504862f538b8552b2c">IsNarrowSequence</a> (Value *V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ce19b9cfbbf5a8e0357d362aa149165">Search</a> (Value *V, BasicBlock *BB, Reduction &amp;R)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a0fee4fb01764913166728d5481007b">RecordMemoryOps</a> (BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterate through the block and record base, offset pairs of loads which can be widened into a single load. <a href="#a3a0fee4fb01764913166728d5481007b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4eac8127e14c492618723e64fbd5b94">InsertParallelMACs</a> (Reduction &amp;Reduction)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add9c8e613705140553a70e421e698ba6">AreSequentialLoads</a> (LoadInst *Ld0, LoadInst *Ld1, MemInstList &amp;VecMem)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c48257d1f1ddea263a31b17f39c8d1f">CreateWideLoad</a> (MemInstList &amp;Loads, IntegerType *LoadTy)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84cbfdda21a579202a8f77cd13a56dc7">CreateParallelPairs</a> (Reduction &amp;R)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71a9e01f852028de4677ea71c25427be">MatchSMLAD</a> (Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to match and generate: SMLAD, SMLADX - Signed Multiply Accumulate Dual performs two signed 16x16-bit multiplications. <a href="#a71a9e01f852028de4677ea71c25427be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a842317de50461451af68f82dba063a22">SE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97c896ce24325aa7830d03b03d76940d">AA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6556597687fc35a1c8c9c2c67e5868d8">TLI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93e541ad5387a555ba1aa0261cdc36a5">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fc8126bf685be2216ba7c2569cb6b50">DL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a330e3c0510e2c70ba07598a8c92c82f1">M</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> *, <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb63284749eefa70cddc40473a8305c9">LoadPairs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28c21e73b1a64a1beab71960bae74e8a">OffsetLoads</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> *, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-armparalleldsp-cpp-/widenedload">WidenedLoad</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ac85a686af94a278d49e4357729cc18">WideLoads</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ceb898a98993a9e3d4242e07595440d">ID</a> = 0</td>
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


<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ARMParallelDSP() {#a7a630ad39d94e6a277c4fe4897dca2d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ARMParallelDSP.cpp}::ARMParallelDSP::ARMParallelDSP ()</td>
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



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/functionpass/#a7691d83e3561f781cae4ce4a01bdfa93">llvm::FunctionPass::FunctionPass</a> and <a href="#a9ceb898a98993a9e3d4242e07595440d">ID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ade96383e5517033e1f9ecb902654ee38">llvm::createARMParallelDSPPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAnalysisUsage() {#a150618f73ac168f3449ea9325dc36b81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ARMParallelDSP.cpp}::ARMParallelDSP::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;)</td>
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

<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job.</p>


<p>If a pass specifies that it uses a particular analysis result to this function, it can then use the <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">getAnalysis&lt;AnalysisType&gt;()</a> function, below.</p>


<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae9356b720f6fbab112d809738dcc4f2a">llvm::AnalysisUsage::addPreserved</a>, <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a6590d0486104165ca40c7df0707f7b9e">llvm::Pass::getAnalysisUsage</a> and <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#af11a6ebf7ab3c388234cb6d5378439a3">llvm::AnalysisUsage::setPreservesCFG</a>.</p>

</div>
</div>

### IsNarrowSequence() {#a14816bda1c3d93504862f538b8552b2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned MaxBitWidth&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ARMParallelDSP.cpp}::ARMParallelDSP::IsNarrowSequence (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>

</div>
</div>

### runOnFunction() {#ae40feb69d50495a1f334abd82dd64e87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ARMParallelDSP.cpp}::ARMParallelDSP::runOnFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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

<p>runOnFunction - Virtual method overriden by subclasses to do the per-function processing of the pass.</p>

<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp/#af24a9993434d23fc65da617585da4616">DisableParallelDSP</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/functionpass/#af9f5f511d75e16f09a5520cb9444cfa8">llvm::FunctionPass::skipFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### AreSequentialLoads() {#add9c8e613705140553a70e421e698ba6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMParallelDSP::AreSequentialLoads (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * Ld0, <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * Ld1, <a href="/web-llvm/docs/api/namespaces/anonymous-armparalleldsp-cpp-/#aa39736b60c5d2c5ec4a5d659b833ce09">MemInstList</a> &amp; VecMem)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

### CreateParallelPairs() {#a84cbfdda21a579202a8f77cd13a56dc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMParallelDSP::CreateParallelPairs (<a href="/web-llvm/docs/api/classes/anonymous-armparalleldsp-cpp-/reduction">Reduction</a> &amp; R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

### CreateWideLoad() {#a4c48257d1f1ddea263a31b17f39c8d1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoadInst * ARMParallelDSP::CreateWideLoad (<a href="/web-llvm/docs/api/namespaces/anonymous-armparalleldsp-cpp-/#aa39736b60c5d2c5ec4a5d659b833ce09">MemInstList</a> &amp; Loads, <a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> * LoadTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

### InsertParallelMACs() {#ad4eac8127e14c492618723e64fbd5b94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMParallelDSP::InsertParallelMACs (<a href="/web-llvm/docs/api/classes/anonymous-armparalleldsp-cpp-/reduction">Reduction</a> &amp; Reduction)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

### IsNarrowSequence() {#a14816bda1c3d93504862f538b8552b2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ARMParallelDSP.cpp}::ARMParallelDSP::IsNarrowSequence (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

### MatchSMLAD() {#a71a9e01f852028de4677ea71c25427be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMParallelDSP::MatchSMLAD (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to match and generate: SMLAD, SMLADX - Signed Multiply Accumulate Dual performs two signed 16x16-bit multiplications.</p>


<p>It adds the products to a 32-bit accumulate operand. Optionally, the instruction can exchange the halfwords of the second operand before performing the arithmetic.</p>


<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

### RecordMemoryOps() {#a3a0fee4fb01764913166728d5481007b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMParallelDSP::RecordMemoryOps (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Iterate through the block and record base, offset pairs of loads which can be widened into a single load.</p>

<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

### Search() {#a5ce19b9cfbbf5a8e0357d362aa149165}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMParallelDSP::Search (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/anonymous-armparalleldsp-cpp-/reduction">Reduction</a> &amp; R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AA {#a97c896ce24325aa7830d03b03d76940d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasAnalysis* anonymous{ARMParallelDSP.cpp}::ARMParallelDSP::AA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

### DL {#a3fc8126bf685be2216ba7c2569cb6b50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout* anonymous{ARMParallelDSP.cpp}::ARMParallelDSP::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

### DT {#a93e541ad5387a555ba1aa0261cdc36a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* anonymous{ARMParallelDSP.cpp}::ARMParallelDSP::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

### LoadPairs {#abb63284749eefa70cddc40473a8305c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;LoadInst*, LoadInst*&gt; anonymous{ARMParallelDSP.cpp}::ARMParallelDSP::LoadPairs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

### M {#a330e3c0510e2c70ba07598a8c92c82f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module* anonymous{ARMParallelDSP.cpp}::ARMParallelDSP::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

### OffsetLoads {#a28c21e73b1a64a1beab71960bae74e8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;LoadInst*, 4&gt; anonymous{ARMParallelDSP.cpp}::ARMParallelDSP::OffsetLoads</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

### SE {#a842317de50461451af68f82dba063a22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution* anonymous{ARMParallelDSP.cpp}::ARMParallelDSP::SE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

### TLI {#a6556597687fc35a1c8c9c2c67e5868d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLibraryInfo* anonymous{ARMParallelDSP.cpp}::ARMParallelDSP::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

### WideLoads {#a5ac85a686af94a278d49e4357729cc18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;LoadInst*, std::unique_ptr&lt;WidenedLoad&gt; &gt; anonymous{ARMParallelDSP.cpp}::ARMParallelDSP::WideLoads</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a9ceb898a98993a9e3d4242e07595440d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char ARMParallelDSP::ID = 0</td>
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



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a>.</p>


<p>Referenced by <a href="#a7a630ad39d94e6a277c4fe4897dca2d6">ARMParallelDSP</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armparalleldsp-cpp">ARMParallelDSP.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
