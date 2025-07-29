---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/analysis/irsimilarityidentifier-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `IRSimilarityIdentifier.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">llvm/Analysis/IRSimilarityIdentifier.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/setoperations-h">llvm/ADT/SetOperations.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">llvm/IR/Intrinsics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">llvm/IR/Operator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">llvm/IR/User.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/suffixtree-h">llvm/Support/SuffixTree.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">detail::zippy&lt; detail::zip_shortest, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; int, 4 &gt; &amp;, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; int, 4 &gt; &amp;, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp;, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; &gt; <a href="#a461e1adc16a7dc9d148b35c8751a1002">ZippedRelativeLocationsT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbf484050e75f5876a5f490e2047e233">checkNumberingAndReplaceCommutative</a> (const DenseMap&lt; Value *, unsigned &gt; &amp;SourceValueToNumberMapping, DenseMap&lt; unsigned, DenseSet&lt; unsigned &gt; &gt; &amp;CurrentSrcTgtNumberMapping, ArrayRef&lt; Value * &gt; &amp;SourceOperands, DenseSet&lt; unsigned &gt; &amp;TargetValueNumbers)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if one or more of the assigned global value numbers for the operands in <span class="doxyComputerOutput">TargetValueNumbers</span> is in the current mapping set for operand numbers in <span class="doxyComputerOutput">SourceOperands</span>. <a href="#afbf484050e75f5876a5f490e2047e233">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01e8f5742b534af36f06b7378e647d78">checkNumberingAndReplace</a> (DenseMap&lt; unsigned, DenseSet&lt; unsigned &gt; &gt; &amp;CurrentSrcTgtNumberMapping, unsigned SourceArgVal, unsigned TargetArgVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if operand number <span class="doxyComputerOutput">TargetArgVal</span> is in the current mapping set for operand number <span class="doxyComputerOutput">SourceArgVal</span>. <a href="#a01e8f5742b534af36f06b7378e647d78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb57434f498dac697cfa36cd1cb9394c">createCandidatesFromSuffixTree</a> (const IRInstructionMapper &amp;Mapper, std::vector&lt; IRInstructionData * &gt; &amp;InstrList, std::vector&lt; unsigned &gt; &amp;IntegerMapping, SuffixTree::RepeatedSubstring &amp;RS, std::vector&lt; IRSimilarityCandidate &gt; &amp;CandsForRepSubstring)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>From a repeated subsequence, find all the different instances of the subsequence from the <span class="doxyComputerOutput">InstrList</span>, and create an <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> from the <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> in subsequence. <a href="#adb57434f498dac697cfa36cd1cb9394c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> *, <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe58a1278a6b1a8f254a740575a6a102">CheckLargerCands</a> (IRSimilarityCandidate &amp;CandA, IRSimilarityCandidate &amp;CandB, DenseMap&lt; unsigned, DenseSet&lt; IRSimilarityCandidate * &gt; &gt; &amp;IndexToIncludedCand, DenseMap&lt; IRSimilarityCandidate *, unsigned &gt; &amp;CandToGroup)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look for larger IRSimilarityCandidates From the previously matched IRSimilarityCandidates that fully contain <span class="doxyComputerOutput">CandA</span> or <span class="doxyComputerOutput">CandB</span>. <a href="#afe58a1278a6b1a8f254a740575a6a102">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad34b0969cb7181bf8847c796b0e52825">findCandidateStructures</a> (std::vector&lt; IRSimilarityCandidate &gt; &amp;CandsForRepSubstring, DenseMap&lt; unsigned, SimilarityGroup &gt; &amp;StructuralGroups, DenseMap&lt; unsigned, DenseSet&lt; IRSimilarityCandidate * &gt; &gt; &amp;IndexToIncludedCand, DenseMap&lt; IRSimilarityCandidate *, unsigned &gt; &amp;CandToOverallGroup)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>From the list of IRSimilarityCandidates, perform a comparison between each <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> to determine if there are overlapping <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a>, or if they do not have the same structure. <a href="#ad34b0969cb7181bf8847c796b0e52825">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ee6d21a9c3c91cd985c0b25cc11af59">INITIALIZE_PASS</a> (IRSimilarityIdentifierWrapperPass, "ir-similarity-identifier", "ir-similarity-identifier", false, true) IRSimilarityIdentifierWrapperPass</td>
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


<div class="doxySectionDef">

## Typedefs

### ZippedRelativeLocationsT {#a461e1adc16a7dc9d148b35c8751a1002}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef detail::zippy&lt;detail::zip_shortest, SmallVector&lt;int, 4&gt; &amp;, SmallVector&lt;int, 4&gt; &amp;, ArrayRef&lt;Value *&gt; &amp;, ArrayRef&lt;Value *&gt; &amp;&gt; ZippedRelativeLocationsT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 783 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### CheckLargerCands() {#afe58a1278a6b1a8f254a740575a6a102}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::pair&lt; IRSimilarityCandidate *, IRSimilarityCandidate * &gt; &gt; CheckLargerCands (<a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> &amp; CandA, <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> &amp; CandB, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> * &gt; &gt; &amp; IndexToIncludedCand, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> *, unsigned &gt; &amp; CandToGroup)</td>
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

<p>Look for larger IRSimilarityCandidates From the previously matched IRSimilarityCandidates that fully contain <span class="doxyComputerOutput">CandA</span> or <span class="doxyComputerOutput">CandB</span>.</p>


<p>If there is an overlap, return a pair of structurally similar, larger IRSimilarityCandidates.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] CandA</td>
<td class="doxyParamItemDescription"><p>- The first candidate we are trying to determine the structure of.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] CandB</td>
<td class="doxyParamItemDescription"><p>- The second candidate we are trying to determine the structure of.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] IndexToIncludedCand</td>
<td class="doxyParamItemDescription"><p>- Mapping of index of the an instruction in a circuit to the IRSimilarityCandidates that include this instruction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] CandToOverallGroup</td>
<td class="doxyParamItemDescription"><p>- Mapping of <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> to a number representing the structural group assigned to it.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1202 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad7dc7318244359268414719e0959346e">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a9a3c9d867ff6bde97841c2b7983f5c70">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a56034ec173ce8feff8568c0e29462094">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate/#a5fd2e1a8a3658307e8c0d87a153d8c24">llvm::IRSimilarity::IRSimilarityCandidate::getEndIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate/#ada960ccf6a96ca62ce5db3af1b7bf7f5">llvm::IRSimilarity::IRSimilarityCandidate::getStartIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2162d123f222998300d308bdefdb38b9">llvm::set_intersect</a>.</p>


<p>Referenced by <a href="#ad34b0969cb7181bf8847c796b0e52825">findCandidateStructures</a>.</p>

</div>
</div>

### checkNumberingAndReplace() {#a01e8f5742b534af36f06b7378e647d78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool checkNumberingAndReplace (<a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; unsigned &gt; &gt; &amp; CurrentSrcTgtNumberMapping, unsigned SourceArgVal, unsigned TargetArgVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if operand number <span class="doxyComputerOutput">TargetArgVal</span> is in the current mapping set for operand number <span class="doxyComputerOutput">SourceArgVal</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] CurrentSrcTgtNumberMapping</td>
<td class="doxyParamItemDescription"><p>current mapping of global value numbers from source <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> to target <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] SourceArgVal</td>
<td class="doxyParamItemDescription"><p>The global value number for an operand in the in the original candidate.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] TargetArgVal</td>
<td class="doxyParamItemDescription"><p>The global value number for the corresponding operand in the other candidate.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if there exists a mapping and false if not.</p></dd>
</dl>


<p>Definition at line 604 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1fbf4d66a9eeaa9ade03e8febee097ee">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad409c2de8502b94c8a0b1193307c63b6">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a> and <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a9a025cb106832026cd05c2b4648a699f">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate/#afaccf8f3711195931b9eaaa317eb637c">llvm::IRSimilarity::IRSimilarityCandidate::compareNonCommutativeOperandMapping</a>.</p>

</div>
</div>

### checkNumberingAndReplaceCommutative() {#afbf484050e75f5876a5f490e2047e233}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool checkNumberingAndReplaceCommutative (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, unsigned &gt; &amp; SourceValueToNumberMapping, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; unsigned &gt; &gt; &amp; CurrentSrcTgtNumberMapping, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; SourceOperands, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; unsigned &gt; &amp; TargetValueNumbers)</td>
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

<p>Determine if one or more of the assigned global value numbers for the operands in <span class="doxyComputerOutput">TargetValueNumbers</span> is in the current mapping set for operand numbers in <span class="doxyComputerOutput">SourceOperands</span>.</p>


<p>The set of possible corresponding global value numbers are replaced with the most recent version of compatible values.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] SourceValueToNumberMapping</td>
<td class="doxyParamItemDescription"><p>- The mapping of a <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> to global value number for the source IRInstructionCandidate.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] CurrentSrcTgtNumberMapping</td>
<td class="doxyParamItemDescription"><p>- The current mapping of source <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> global value numbers to a set of possible numbers in the target.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] SourceOperands</td>
<td class="doxyParamItemDescription"><p>- The operands in the original <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> in the current instruction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] TargetValueNumbers</td>
<td class="doxyParamItemDescription"><p>- The global value numbers of the operands in the corresponding <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> in the other <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a>.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if there exists a possible mapping between the source <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> operands and the target <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> operands, and false if not.</p></dd>
</dl>


<p>Definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a50d461a887e200e704e5157d3b21514d">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad409c2de8502b94c8a0b1193307c63b6">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a49c487a9395a6c384be8544cfb2cfccf">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a9a3c9d867ff6bde97841c2b7983f5c70">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a1eb8504bab5f794778d82db6ac829923">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a3d95cc2d359b8d9ed5bd9504b44930b5">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a9a025cb106832026cd05c2b4648a699f">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/densemap/#aa67dc49a37f9cee49ebd4d3bde73d8e4">llvm::DenseMap&lt; KeyT, ValueT, KeyInfoT, BucketT &gt;::swap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate/#afe6bd5545903e7ba1de9af2e7d0d2a4a">llvm::IRSimilarity::IRSimilarityCandidate::compareCommutativeOperandMapping</a>.</p>

</div>
</div>

### createCandidatesFromSuffixTree() {#adb57434f498dac697cfa36cd1cb9394c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void createCandidatesFromSuffixTree (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructionmapper">IRInstructionMapper</a> &amp; Mapper, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> * &gt; &amp; InstrList, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; unsigned &gt; &amp; IntegerMapping, <a href="/web-llvm/docs/api/structs/llvm/suffixtree/repeatedsubstring">SuffixTree::RepeatedSubstring</a> &amp; RS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> &gt; &amp; CandsForRepSubstring)</td>
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

<p>From a repeated subsequence, find all the different instances of the subsequence from the <span class="doxyComputerOutput">InstrList</span>, and create an <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> from the <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> in subsequence.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] Mapper</td>
<td class="doxyParamItemDescription"><p>- The instruction mapper for basic correctness checks.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] InstrList</td>
<td class="doxyParamItemDescription"><p>- The vector that holds the instruction data.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] IntegerMapping</td>
<td class="doxyParamItemDescription"><p>- The vector that holds the mapped integers.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] CandsForRepSubstring</td>
<td class="doxyParamItemDescription"><p>- The vector to store the generated IRSimilarityCandidates.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 965 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructionmapper/#a60e5af3b7e239b6fdad88efbe1e861bd">llvm::IRSimilarity::IRInstructionMapper::IllegalInstrNumber</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/structs/llvm/suffixtree/repeatedsubstring/#ad780377fbb89deb15edff3b2a46a0087">llvm::SuffixTree::RepeatedSubstring::Length</a> and <a href="/web-llvm/docs/api/structs/llvm/suffixtree/repeatedsubstring/#aad6ddbc1a3f079b548de9f43990488ac">llvm::SuffixTree::RepeatedSubstring::StartIndices</a>.</p>

</div>
</div>

### findCandidateStructures() {#ad34b0969cb7181bf8847c796b0e52825}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void findCandidateStructures (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> &gt; &amp; CandsForRepSubstring, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#a2198f86ce16da838bdeea4de7e59ef31">SimilarityGroup</a> &gt; &amp; StructuralGroups, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> * &gt; &gt; &amp; IndexToIncludedCand, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> *, unsigned &gt; &amp; CandToOverallGroup)</td>
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

<p>From the list of IRSimilarityCandidates, perform a comparison between each <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> to determine if there are overlapping <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a>, or if they do not have the same structure.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] CandsForRepSubstring</td>
<td class="doxyParamItemDescription"><p>- The vector containing the IRSimilarityCandidates.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] StructuralGroups</td>
<td class="doxyParamItemDescription"><p>- the mapping of unsigned integers to vector of IRSimilarityCandidates where each of the IRSimilarityCandidates in the vector are structurally similar to one another.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] IndexToIncludedCand</td>
<td class="doxyParamItemDescription"><p>- Mapping of index of the an instruction in a circuit to the IRSimilarityCandidates that include this instruction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] CandToOverallGroup</td>
<td class="doxyParamItemDescription"><p>- Mapping of <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> to a number representing the structural group assigned to it.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1275 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="#afe58a1278a6b1a8f254a740575a6a102">CheckLargerCands</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adf4e7878fc0b3b8dcde545178564190d">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate/#ab7090e2692a1125bbf970b981dbe21ce">llvm::IRSimilarity::IRSimilarityCandidate::compareStructure</a>, <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate/#ab887db0898db0bfae23199acc51e4f48">llvm::IRSimilarity::IRSimilarityCandidate::createCanonicalMappingFor</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a> and <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>.</p>

</div>
</div>

### INITIALIZE\_PASS() {#a0ee6d21a9c3c91cd985c0b25cc11af59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS (<a href="/web-llvm/docs/api/classes/llvm/irsimilarityidentifierwrapperpass">IRSimilarityIdentifierWrapperPass</a>, "ir-similarity-identifier", "ir-similarity-identifier", false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1473 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa08a8e8f8a5ca6f473894b1e5bcb6343">llvm::initializeIRSimilarityIdentifierWrapperPassPass</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
