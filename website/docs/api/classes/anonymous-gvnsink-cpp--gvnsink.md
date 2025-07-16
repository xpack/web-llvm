---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-gvnsink-cpp-/gvnsink
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GVNSink` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{GVNSink.cpp}::GVNSink { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8895aed5d4168ada50076def330294cb">GVNSink</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a900ef156c51ab7bbcff3a4d45856a670">run</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10f57b404caeef8298ef9b73e5623e62">shouldAvoidSinkingInstruction</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/anonymous-gvnsink-cpp-/sinkinginstructioncandidate">SinkingInstructionCandidate</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a615e436433febab97d63752dad0b6443">analyzeInstructionForSinking</a> (LockstepReverseIterator &amp;LRI, unsigned &amp;InstNum, unsigned &amp;MemoryInstNum, ModelledPHISet &amp;NeededPHIs, SmallPtrSetImpl&lt; Value * &gt; &amp;PHIContents)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The main heuristic function. <a href="#a615e436433febab97d63752dad0b6443">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0d92c05f187ee62ca80be814942815c">analyzeInitialPHIs</a> (BasicBlock *BB, ModelledPHISet &amp;PHIs, SmallPtrSetImpl&lt; Value * &gt; &amp;PHIContents)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/anonymous-gvnsink-cpp-/modelledphi">ModelledPHI</a> for each PHI in BB, adding to PHIs. <a href="#ad0d92c05f187ee62ca80be814942815c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1978eb73a064966f49065af5933e1121">sinkBB</a> (BasicBlock *BBEnd)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The main instruction sinking driver. <a href="#a1978eb73a064966f49065af5933e1121">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7aa4f387bf3256314174d29c338651c">sinkLastInstruction</a> (ArrayRef&lt; BasicBlock * &gt; Blocks, BasicBlock *BBEnd)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform the actual mechanics of sinking an instruction from Blocks into BBEnd, which is their only successor. <a href="#af7aa4f387bf3256314174d29c338651c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a335fab6d4c71441126fa5a8fce1f9f05">foldPointlessPHINodes</a> (BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove PHIs that all have the same incoming value. <a href="#a335fab6d4c71441126fa5a8fce1f9f05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-gvnsink-cpp-/valuetable">ValueTable</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b16b627c1d49e24b6cf69afd74cf62f">VN</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fa34857c4f047ac0ada32de21c30a36">RPOTOrder</a></td>
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


<p>Definition at line 595 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GVNSink() {#a8895aed5d4168ada50076def330294cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{GVNSink.cpp}::GVNSink::GVNSink ()</td>
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



<p>Definition at line 597 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#a900ef156c51ab7bbcff3a4d45856a670}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{GVNSink.cpp}::GVNSink::run (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 599 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/reversepostordertraversal/#ac958000d711f19778f1b40792821b5b3">llvm::ReversePostOrderTraversal&lt; GraphT, GT &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/reversepostordertraversal/#ae945899e1218a9240c3fed1e5789cbba">llvm::ReversePostOrderTraversal&lt; GraphT, GT &gt;::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad66c4759666aab78529658362b498c74">llvm::pred_empty</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### analyzeInitialPHIs() {#ad0d92c05f187ee62ca80be814942815c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{GVNSink.cpp}::GVNSink::analyzeInitialPHIs (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/namespaces/anonymous-gvnsink-cpp-/#a3cb4bce4910377f3e897dfdff0280ad9">ModelledPHISet</a> &amp; PHIs, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; PHIContents)</td>
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

<p>Create a <a href="/web-llvm/docs/api/classes/anonymous-gvnsink-cpp-/modelledphi">ModelledPHI</a> for each PHI in BB, adding to PHIs.</p>

<p>Definition at line 642 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>

</div>
</div>

### analyzeInstructionForSinking() {#a615e436433febab97d63752dad0b6443}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; SinkingInstructionCandidate &gt; anonymous{GVNSink.cpp}::GVNSink::analyzeInstructionForSinking (<a href="/web-llvm/docs/api/classes/anonymous-gvnsink-cpp-/lockstepreverseiterator">LockstepReverseIterator</a> &amp; LRI, unsigned &amp; InstNum, unsigned &amp; MemoryInstNum, <a href="/web-llvm/docs/api/namespaces/anonymous-gvnsink-cpp-/#a3cb4bce4910377f3e897dfdff0280ad9">ModelledPHISet</a> &amp; NeededPHIs, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; PHIContents)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The main heuristic function.</p>


<p>Analyze the set of instructions pointed to by LRI and return a candidate solution if these instructions can be sunk, or std::nullopt otherwise.</p>


<p>Definition at line 637 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>

</div>
</div>

### foldPointlessPHINodes() {#a335fab6d4c71441126fa5a8fce1f9f05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{GVNSink.cpp}::GVNSink::foldPointlessPHINodes (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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

<p>Remove PHIs that all have the same incoming value.</p>

<p>Definition at line 661 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>

</div>
</div>

### shouldAvoidSinkingInstruction() {#a10f57b404caeef8298ef9b73e5623e62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{GVNSink.cpp}::GVNSink::shouldAvoidSinkingInstruction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 626 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>

</div>
</div>

### sinkBB() {#a1978eb73a064966f49065af5933e1121}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{GVNSink.cpp}::GVNSink::sinkBB (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BBEnd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The main instruction sinking driver.</p>


<p>Set up state and try and sink instructions into BBEnd from its predecessors.</p>


<p>Definition at line 654 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>

</div>
</div>

### sinkLastInstruction() {#af7aa4f387bf3256314174d29c338651c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{GVNSink.cpp}::GVNSink::sinkLastInstruction (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; Blocks, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BBEnd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform the actual mechanics of sinking an instruction from Blocks into BBEnd, which is their only successor.</p>

<p>Definition at line 658 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### RPOTOrder {#a7fa34857c4f047ac0ada32de21c30a36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const BasicBlock *, unsigned&gt; anonymous{GVNSink.cpp}::GVNSink::RPOTOrder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 624 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>

</div>
</div>

### VN {#a9b16b627c1d49e24b6cf69afd74cf62f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueTable anonymous{GVNSink.cpp}::GVNSink::VN</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 623 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
