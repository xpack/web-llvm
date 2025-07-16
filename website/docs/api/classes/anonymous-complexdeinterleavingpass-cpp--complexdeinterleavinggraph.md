---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-complexdeinterleavingpass-cpp-/complexdeinterleavinggraph
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ComplexDeinterleavingGraph` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee4d1f2b9ad271e4b8d3239e11a6668c">Addend</a> = std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, bool &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa22814a2626c20ff9f393408985f3ed7">NodePtr</a> = ComplexDeinterleavingCompositeNode::NodePtr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add322e355d3cd27026eca02737fbe8ef">RawNodePtr</a> = <a href="/web-llvm/docs/api/structs/anonymous-complexdeinterleavingpass-cpp-/complexdeinterleavingcompositenode">ComplexDeinterleavingCompositeNode::RawNodePtr</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab596fd666a003cbaac1d18234d2738d9">ComplexDeinterleavingGraph</a> (const TargetLowering *TL, const TargetLibraryInfo *TLI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3ccbfd688d1be627bd14dbfe3a81cb3">dump</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae0a94b0e70bece345cdfa35fd068b06">dump</a> (raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a257b23cbc3b86d61dc953bad7beeaa5b">identifyNodes</a> (Instruction *RootI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns false if the deinterleaving operation should be cancelled for the current graph. <a href="#a257b23cbc3b86d61dc953bad7beeaa5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab582ba603d84d0ebf312a5f065c11dcf">collectPotentialReductions</a> (BasicBlock *B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>In case \pB is one-block loop, this function seeks potential reductions and populates ReductionInfo. <a href="#ab582ba603d84d0ebf312a5f065c11dcf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cc7cd380b6ceacc35ef685d5b047d80">identifyReductionNodes</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e6c4318cd8d3ae5bbe88df3d4a58490">checkNodes</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check that every instruction, from the roots to the leaves, has internal uses. <a href="#a7e6c4318cd8d3ae5bbe88df3d4a58490">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1a825a151b1c9b01a9054f14eb518d2">replaceNodes</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform the actual replacement of the underlying instruction graph. <a href="#ad1a825a151b1c9b01a9054f14eb518d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa22814a2626c20ff9f393408985f3ed7">NodePtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a2fac226f5195317edb9453a5ac26ab">prepareCompositeNode</a> (ComplexDeinterleavingOperation Operation, Value *R, Value *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa22814a2626c20ff9f393408985f3ed7">NodePtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93656fcd18467746b1a9596f19319a0e">submitCompositeNode</a> (NodePtr Node)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa22814a2626c20ff9f393408985f3ed7">NodePtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2137e88437956879eccc67c4a4b76b75">identifyPartialMul</a> (Instruction *Real, Instruction *Imag)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identifies a complex partial multiply pattern and its rotation, based on the following patterns. <a href="#a2137e88437956879eccc67c4a4b76b75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa22814a2626c20ff9f393408985f3ed7">NodePtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab20b202c523ebe8f22aaa2c5ddbf3411">identifyNodeWithImplicitAdd</a> (Instruction *I, Instruction *J, std::pair&lt; Value *, Value * &gt; &amp;CommonOperandI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identify the other branch of a Partial Mul, taking the CommonOperandI that is partially known from identifyPartialMul, filling in the other half of the complex pair. <a href="#ab20b202c523ebe8f22aaa2c5ddbf3411">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa22814a2626c20ff9f393408985f3ed7">NodePtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9ea780d7d68c1332eb5bf864f076bd2">identifyAdd</a> (Instruction *Real, Instruction *Imag)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identifies a complex add pattern and its rotation, based on the following patterns. <a href="#ab9ea780d7d68c1332eb5bf864f076bd2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa22814a2626c20ff9f393408985f3ed7">NodePtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d14c1e6ea480dff5cc819a140bd5705">identifySymmetricOperation</a> (Instruction *Real, Instruction *Imag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa22814a2626c20ff9f393408985f3ed7">NodePtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a101085d582525f42c85fdceb57a699ed">identifyPartialReduction</a> (Value *R, Value *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa22814a2626c20ff9f393408985f3ed7">NodePtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d97b8327df8c8bc6c7de875a5c14ea8">identifyDotProduct</a> (Value *Inst)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa22814a2626c20ff9f393408985f3ed7">NodePtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a016cf707b3117489bc324fd113d240c4">identifyNode</a> (Value *R, Value *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa22814a2626c20ff9f393408985f3ed7">NodePtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89c20b259de97fcdcbaa8efa7cbe47d3">identifyAdditions</a> (std::list&lt; Addend &gt; &amp;RealAddends, std::list&lt; Addend &gt; &amp;ImagAddends, std::optional&lt; FastMathFlags &gt; Flags, NodePtr Accumulator)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if a sum of complex numbers can be formed from <span class="doxyComputerOutput">RealAddends</span> and <span class="doxyComputerOutput">ImagAddens</span>. <a href="#a89c20b259de97fcdcbaa8efa7cbe47d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa22814a2626c20ff9f393408985f3ed7">NodePtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bf36cb65b4010f4652cd0fc5ced9905">extractPositiveAddend</a> (std::list&lt; Addend &gt; &amp;RealAddends, std::list&lt; Addend &gt; &amp;ImagAddends)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract one addend that have both real and imaginary parts positive. <a href="#a1bf36cb65b4010f4652cd0fc5ced9905">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa22814a2626c20ff9f393408985f3ed7">NodePtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9027cb775fa4a24d053d0d1e6553c816">identifyMultiplications</a> (std::vector&lt; Product &gt; &amp;RealMuls, std::vector&lt; Product &gt; &amp;ImagMuls, NodePtr Accumulator)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if sum of multiplications of complex numbers can be formed from <span class="doxyComputerOutput">RealMuls</span> and <span class="doxyComputerOutput">ImagMuls</span>. <a href="#a9027cb775fa4a24d053d0d1e6553c816">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e8ad218da67e38895a0bc9480ba5456">collectPartialMuls</a> (const std::vector&lt; Product &gt; &amp;RealMuls, const std::vector&lt; Product &gt; &amp;ImagMuls, std::vector&lt; PartialMulCandidate &gt; &amp;Candidates)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Go through pairs of multiplication (one Real and one Imag) and find all possible candidates for partial multiplication and put them into <span class="doxyComputerOutput">Candidates</span>. <a href="#a0e8ad218da67e38895a0bc9480ba5456">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa22814a2626c20ff9f393408985f3ed7">NodePtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5937e4ebf4eb3225c6b3ece71803dd3">identifyReassocNodes</a> (Instruction *I, Instruction *J)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the code is compiled with -Ofast or expressions have <span class="doxyComputerOutput">reassoc</span> flag, the order of complex computation operations may be significantly altered, and the real and imaginary parts may not be executed in parallel. <a href="#ad5937e4ebf4eb3225c6b3ece71803dd3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa22814a2626c20ff9f393408985f3ed7">NodePtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ba190af77b39acb6e39328cc1c5b037">identifyRoot</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa22814a2626c20ff9f393408985f3ed7">NodePtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cb65248a30c7879c142e0f739921303">identifyDeinterleave</a> (Instruction *Real, Instruction *Imag)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identifies the Deinterleave operation applied to a vector containing complex numbers. <a href="#a8cb65248a30c7879c142e0f739921303">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa22814a2626c20ff9f393408985f3ed7">NodePtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8afb602b44c4cdf5865153bed358cbc7">identifySplat</a> (Value *Real, Value *Imag)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>identifying the operation that represents a complex number repeated in a Splat vector. <a href="#a8afb602b44c4cdf5865153bed358cbc7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa22814a2626c20ff9f393408985f3ed7">NodePtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b0500ddd4c2f5f07ce1917161e856ec">identifyPHINode</a> (Instruction *Real, Instruction *Imag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa22814a2626c20ff9f393408985f3ed7">NodePtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8754646d476a7126b2510c456fd44e06">identifySelectNode</a> (Instruction *Real, Instruction *Imag)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identifies SelectInsts in a loop that has reduction with predication masks and/or predicated tail folding. <a href="#a8754646d476a7126b2510c456fd44e06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bddfc21953a333f04390f98a3f38655">replaceNode</a> (IRBuilderBase &amp;Builder, RawNodePtr Node)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af00a4fcb67689dd94e444a1a7725c5a8">processReductionOperation</a> (Value *OperationReplacement, RawNodePtr Node)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Complete IR modifications after producing new reduction operation: <a href="#af00a4fcb67689dd94e444a1a7725c5a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a797644989880279b5e7c4b9f414f1457">processReductionSingle</a> (Value *OperationReplacement, RawNodePtr Node)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa83a1aba8e1648a4fb53881455ce7ccb">TL</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa229dbdc43dd9054f8ff1df4c749a70d">TLI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="#aa22814a2626c20ff9f393408985f3ed7">NodePtr</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add22ea36c524da248974c52b24d36d1c">CompositeNodes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;, <a href="#aa22814a2626c20ff9f393408985f3ed7">NodePtr</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3af3410d977983a6d71537c5bc8fa5a">CachedResult</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40ad429fdd3f36e8940328539b46ec50">FinalInstructions</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="#aa22814a2626c20ff9f393408985f3ed7">NodePtr</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a098ed970ff8db7aee1ddd739158d0442">RootToNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Root instructions are instructions from which complex computation starts. <a href="#a098ed970ff8db7aee1ddd739158d0442">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44afe7333a791a9eb415f99a457303e3">OrderedRoots</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Topologically sorted root instructions. <a href="#a44afe7333a791a9eb415f99a457303e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d9ceb2e2de5133e4aba5af076d45cc2">BackEdge</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When examining a basic block for complex deinterleaving, if it is a simple one-block loop, then the only incoming block is 'Incoming' and the 'BackEdge' block is the block itself. <a href="#a2d9ceb2e2de5133e4aba5af076d45cc2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af090245bf7c2118c99c8519e6e3d7e12">Incoming</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa082061229175790bb77502a904a21ee">ReductionInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ReductionInfo maps from ReductionOp to PHInode and <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> OutsideUser as it is shown in the IR: <a href="#aa082061229175790bb77502a904a21ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7602841ce24fa9c4b6dac5f3dac7775">RealPHI</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>In the process of detecting a reduction, we consider a pair of ReductionOP, which we refer to as real and imag (or vice versa), and traverse the use-tree to detect complex operations. <a href="#af7602841ce24fa9c4b6dac5f3dac7775">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addcce769c805686315b406df3f5540b8">ImagPHI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad427720cd996b0b32340ab0bc3bc3b46">PHIsFound</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set this flag to true if RealPHI and ImagPHI were reached during reduction detection. <a href="#ad427720cd996b0b32340ab0bc3bc3b46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *, <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44ad2c7e2af6f19e431bdc2f7a2c6bac">OldToNewPHI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>OldToNewPHI maps the original real <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> to a new, double-sized <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a>. <a href="#a44ad2c7e2af6f19e431bdc2f7a2c6bac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### Addend {#aee4d1f2b9ad271e4b8d3239e11a6668c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::Addend =  std::pair&lt;Value *, bool&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### NodePtr {#aa22814a2626c20ff9f393408985f3ed7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::NodePtr =  ComplexDeinterleavingCompositeNode::NodePtr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### RawNodePtr {#add322e355d3cd27026eca02737fbe8ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::RawNodePtr =  ComplexDeinterleavingCompositeNode::RawNodePtr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ComplexDeinterleavingGraph() {#ab596fd666a003cbaac1d18234d2738d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::ComplexDeinterleavingGraph (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> * TL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### checkNodes() {#a7e6c4318cd8d3ae5bbe88df3d4a58490}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ComplexDeinterleavingGraph::checkNodes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check that every instruction, from the roots to the leaves, has internal uses.</p>

<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a766456df1dd21e804cd4596304e10764a8910da3aadda5afd2fcfedc1c16ba413">llvm::Deinterleave</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#af8a50544090e81ac83601aff8f4b0142">llvm::SmallPtrSetImplBase::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#ad97688dfe9cd802e2a0691cbe620218a">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::pop_back</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### collectPotentialReductions() {#ab582ba603d84d0ebf312a5f065c11dcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ComplexDeinterleavingGraph::collectPotentialReductions (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>In case \pB is one-block loop, this function seeks potential reductions and populates ReductionInfo.</p>


<p>Returns true if any reductions were identified.</p>


<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>.</p>

</div>
</div>

### dump() {#ab3ccbfd688d1be627bd14dbfe3a81cb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::dump ()</td>
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



<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="#ab3ccbfd688d1be627bd14dbfe3a81cb3">dump</a>.</p>


<p>Referenced by <a href="#ab3ccbfd688d1be627bd14dbfe3a81cb3">dump</a>.</p>

</div>
</div>

### dump() {#aae0a94b0e70bece345cdfa35fd068b06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/node/#a3a50a546aa28bc9ebd20afd6aff7588d">Node::dump</a>.</p>

</div>
</div>

### identifyNodes() {#a257b23cbc3b86d61dc953bad7beeaa5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ComplexDeinterleavingGraph::identifyNodes (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * RootI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns false if the deinterleaving operation should be cancelled for the current graph.</p>

<p>Definition at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/anonymous-complexdeinterleavingpass-cpp-/complexdeinterleavingcompositenode/#a0b9cf130d3c9e6eb5661b759bef40fe9">anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingCompositeNode::dump</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6a66ebb3aa12757479a3c88de77d78f8">llvm::Instruction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a766456df1dd21e804cd4596304e10764acaa30b74bf63d3bf50aa41b37f540557">llvm::ReductionOperation</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a766456df1dd21e804cd4596304e10764a5822996f6db7cb25161ba0deb37b365b">llvm::ReductionSingle</a>.</p>

</div>
</div>

### identifyReductionNodes() {#a7cc7cd380b6ceacc35ef685d5b047d80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ComplexDeinterleavingGraph::identifyReductionNodes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a766456df1dd21e804cd4596304e10764acaa30b74bf63d3bf50aa41b37f540557">llvm::ReductionOperation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a766456df1dd21e804cd4596304e10764a5822996f6db7cb25161ba0deb37b365b">llvm::ReductionSingle</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### replaceNodes() {#ad1a825a151b1c9b01a9054f14eb518d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ComplexDeinterleavingGraph::replaceNodes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform the actual replacement of the underlying instruction graph.</p>

<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1106b8a15061e8494873e10bb8a364e5">llvm::RecursivelyDeleteTriviallyDeadInstructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a766456df1dd21e804cd4596304e10764acaa30b74bf63d3bf50aa41b37f540557">llvm::ReductionOperation</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a766456df1dd21e804cd4596304e10764a5822996f6db7cb25161ba0deb37b365b">llvm::ReductionSingle</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### collectPartialMuls() {#a0e8ad218da67e38895a0bc9480ba5456}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ComplexDeinterleavingGraph::collectPartialMuls (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-complexdeinterleavingpass-cpp-/complexdeinterleavinggraph/product">Product</a> &gt; &amp; RealMuls, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-complexdeinterleavingpass-cpp-/complexdeinterleavinggraph/product">Product</a> &gt; &amp; ImagMuls, std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-complexdeinterleavingpass-cpp-/complexdeinterleavinggraph/partialmulcandidate">PartialMulCandidate</a> &gt; &amp; Candidates)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Go through pairs of multiplication (one Real and one Imag) and find all possible candidates for partial multiplication and put them into <span class="doxyComputerOutput">Candidates</span>.</p>


<p>Returns true if all <a href="/web-llvm/docs/api/structs/anonymous-complexdeinterleavingpass-cpp-/complexdeinterleavinggraph/product">Product</a> has pair with common operand</p>


<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### extractPositiveAddend() {#a1bf36cb65b4010f4652cd0fc5ced9905}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComplexDeinterleavingGraph::NodePtr ComplexDeinterleavingGraph::extractPositiveAddend (std::list&lt; <a href="#aee4d1f2b9ad271e4b8d3239e11a6668c">Addend</a> &gt; &amp; RealAddends, std::list&lt; <a href="#aee4d1f2b9ad271e4b8d3239e11a6668c">Addend</a> &gt; &amp; ImagAddends)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract one addend that have both real and imaginary parts positive.</p>

<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### identifyAdd() {#ab9ea780d7d68c1332eb5bf864f076bd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComplexDeinterleavingGraph::NodePtr ComplexDeinterleavingGraph::identifyAdd (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Real, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Imag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Identifies a complex add pattern and its rotation, based on the following patterns.</p>


<p>90: r: ar - bi i: ai + br 270: r: ar + bi i: ai - br</p>


<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### identifyAdditions() {#a89c20b259de97fcdcbaa8efa7cbe47d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComplexDeinterleavingGraph::NodePtr ComplexDeinterleavingGraph::identifyAdditions (std::list&lt; <a href="#aee4d1f2b9ad271e4b8d3239e11a6668c">Addend</a> &gt; &amp; RealAddends, std::list&lt; <a href="#aee4d1f2b9ad271e4b8d3239e11a6668c">Addend</a> &gt; &amp; ImagAddends, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> &gt; Flags, <a href="#aa22814a2626c20ff9f393408985f3ed7">NodePtr</a> Accumulator)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if a sum of complex numbers can be formed from <span class="doxyComputerOutput">RealAddends</span> and <span class="doxyComputerOutput">ImagAddens</span>.</p>


<p>If <span class="doxyComputerOutput">Accumulator</span> is not null, add the result to it. Return nullptr if it is not possible to construct a complex number. <span class="doxyComputerOutput">Flags</span> are needed to generate symmetric Add and Sub operations.</p>


<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### identifyDeinterleave() {#a8cb65248a30c7879c142e0f739921303}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComplexDeinterleavingGraph::NodePtr ComplexDeinterleavingGraph::identifyDeinterleave (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Real, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Imag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Identifies the Deinterleave operation applied to a vector containing complex numbers.</p>


<p>There are two ways to represent the Deinterleave operation:</p>


<ul class="doxyList ">
<li>Using two shufflevectors with even indices for /pReal instruction and odd indices for /pImag instructions (only for fixed-width vectors)</li>
<li>Using two extractvalue instructions applied to <span class="doxyComputerOutput">vector.deinterleave2</span> intrinsic (for both fixed and scalable vectors)</li>
</ul>

<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### identifyDotProduct() {#a8d97b8327df8c8bc6c7de875a5c14ea8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComplexDeinterleavingGraph::NodePtr ComplexDeinterleavingGraph::identifyDotProduct (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### identifyMultiplications() {#a9027cb775fa4a24d053d0d1e6553c816}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComplexDeinterleavingGraph::NodePtr ComplexDeinterleavingGraph::identifyMultiplications (std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-complexdeinterleavingpass-cpp-/complexdeinterleavinggraph/product">Product</a> &gt; &amp; RealMuls, std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-complexdeinterleavingpass-cpp-/complexdeinterleavinggraph/product">Product</a> &gt; &amp; ImagMuls, <a href="#aa22814a2626c20ff9f393408985f3ed7">NodePtr</a> Accumulator)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if sum of multiplications of complex numbers can be formed from <span class="doxyComputerOutput">RealMuls</span> and <span class="doxyComputerOutput">ImagMuls</span>.</p>


<p>If <span class="doxyComputerOutput">Accumulator</span> is not null, add the result to it. Return nullptr if it is not possible to construct a complex number.</p>


<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### identifyNode() {#a016cf707b3117489bc324fd113d240c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComplexDeinterleavingGraph::NodePtr ComplexDeinterleavingGraph::identifyNode (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * R, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### identifyNodeWithImplicitAdd() {#ab20b202c523ebe8f22aaa2c5ddbf3411}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComplexDeinterleavingGraph::NodePtr ComplexDeinterleavingGraph::identifyNodeWithImplicitAdd (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * J, std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; CommonOperandI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Identify the other branch of a Partial Mul, taking the CommonOperandI that is partially known from identifyPartialMul, filling in the other half of the complex pair.</p>

<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### identifyPartialMul() {#a2137e88437956879eccc67c4a4b76b75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComplexDeinterleavingGraph::NodePtr ComplexDeinterleavingGraph::identifyPartialMul (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Real, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Imag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Identifies a complex partial multiply pattern and its rotation, based on the following patterns.</p>


<p>0: r: cr + ar * br i: ci + ar * bi 90: r: cr - ai * bi i: ci + ai * br 180: r: cr - ar * br i: ci - ar * bi 270: r: cr + ai * bi i: ci - ai * br</p>


<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### identifyPartialReduction() {#a101085d582525f42c85fdceb57a699ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComplexDeinterleavingGraph::NodePtr ComplexDeinterleavingGraph::identifyPartialReduction (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * R, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### identifyPHINode() {#a0b0500ddd4c2f5f07ce1917161e856ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComplexDeinterleavingGraph::NodePtr ComplexDeinterleavingGraph::identifyPHINode (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Real, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Imag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### identifyReassocNodes() {#ad5937e4ebf4eb3225c6b3ece71803dd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComplexDeinterleavingGraph::NodePtr ComplexDeinterleavingGraph::identifyReassocNodes (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * J)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the code is compiled with -Ofast or expressions have <span class="doxyComputerOutput">reassoc</span> flag, the order of complex computation operations may be significantly altered, and the real and imaginary parts may not be executed in parallel.</p>


<p>This function takes this into consideration and employs a more general approach to identify complex computations. Initially, it gathers all the addends and multiplicands and then constructs a complex expression from them.</p>


<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### identifyRoot() {#a7ba190af77b39acb6e39328cc1c5b037}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComplexDeinterleavingGraph::NodePtr ComplexDeinterleavingGraph::identifyRoot (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### identifySelectNode() {#a8754646d476a7126b2510c456fd44e06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComplexDeinterleavingGraph::NodePtr ComplexDeinterleavingGraph::identifySelectNode (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Real, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Imag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Identifies SelectInsts in a loop that has reduction with predication masks and/or predicated tail folding.</p>

<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### identifySplat() {#a8afb602b44c4cdf5865153bed358cbc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComplexDeinterleavingGraph::NodePtr ComplexDeinterleavingGraph::identifySplat (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Real, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Imag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>identifying the operation that represents a complex number repeated in a Splat vector.</p>


<p>There are two possible types of splats: <a href="/web-llvm/docs/api/classes/llvm/constantexpr">ConstantExpr</a> with the opcode ShuffleVector and ShuffleVectorInstr. Both should have an initialization mask with all values set to zero.</p>


<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### identifySymmetricOperation() {#a8d14c1e6ea480dff5cc819a140bd5705}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComplexDeinterleavingGraph::NodePtr ComplexDeinterleavingGraph::identifySymmetricOperation (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Real, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Imag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### prepareCompositeNode() {#a5a2fac226f5195317edb9453a5ac26ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodePtr anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::prepareCompositeNode (<a href="/web-llvm/docs/api/namespaces/llvm/#a766456df1dd21e804cd4596304e10764">ComplexDeinterleavingOperation</a> Operation, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * R, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * I)</td>
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



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### processReductionOperation() {#af00a4fcb67689dd94e444a1a7725c5a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ComplexDeinterleavingGraph::processReductionOperation (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * OperationReplacement, <a href="#add322e355d3cd27026eca02737fbe8ef">RawNodePtr</a> Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Complete IR modifications after producing new reduction operation:</p>


<ul class="doxyList ">
<li>Populate the <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> generated for ComplexDeinterleavingOperation::ReductionPHI</li>
<li>Deinterleave the final value outside of the loop and repurpose original reduction users</li>
</ul>

<p>Definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### processReductionSingle() {#a797644989880279b5e7c4b9f414f1457}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ComplexDeinterleavingGraph::processReductionSingle (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * OperationReplacement, <a href="#add322e355d3cd27026eca02737fbe8ef">RawNodePtr</a> Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### replaceNode() {#a1bddfc21953a333f04390f98a3f38655}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * ComplexDeinterleavingGraph::replaceNode (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="#add322e355d3cd27026eca02737fbe8ef">RawNodePtr</a> Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### submitCompositeNode() {#a93656fcd18467746b1a9596f19319a0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodePtr anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::submitCompositeNode (<a href="#aa22814a2626c20ff9f393408985f3ed7">NodePtr</a> Node)</td>
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



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BackEdge {#a2d9ceb2e2de5133e4aba5af076d45cc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::BackEdge = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When examining a basic block for complex deinterleaving, if it is a simple one-block loop, then the only incoming block is 'Incoming' and the 'BackEdge' block is the block itself.</p>


<p>"</p>


<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### CachedResult {#ac3af3410d977983a6d71537c5bc8fa5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;std::pair&lt;Value *, Value *&gt;, NodePtr&gt; anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::CachedResult</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### CompositeNodes {#add22ea36c524da248974c52b24d36d1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;NodePtr&gt; anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::CompositeNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### FinalInstructions {#a40ad429fdd3f36e8940328539b46ec50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;Instruction *, 16&gt; anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::FinalInstructions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### ImagPHI {#addcce769c805686315b406df3f5540b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PHINode* anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::ImagPHI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### Incoming {#af090245bf7c2118c99c8519e6e3d7e12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::Incoming = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### OldToNewPHI {#a44ad2c7e2af6f19e431bdc2f7a2c6bac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;PHINode *, PHINode *&gt; anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::OldToNewPHI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>OldToNewPHI maps the original real <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> to a new, double-sized <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a>.</p>


<p>The new <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> corresponds to a vector of deinterleaved complex numbers. This mapping is populated during ComplexDeinterleavingOperation::ReductionPHI node replacement. It is then used in the ComplexDeinterleavingOperation::ReductionOperation node replacement process.</p>


<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### OrderedRoots {#a44afe7333a791a9eb415f99a457303e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Instruction *, 1&gt; anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::OrderedRoots</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Topologically sorted root instructions.</p>

<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### PHIsFound {#ad427720cd996b0b32340ab0bc3bc3b46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::PHIsFound = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set this flag to true if RealPHI and ImagPHI were reached during reduction detection.</p>

<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### RealPHI {#af7602841ce24fa9c4b6dac5f3dac7775}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PHINode* anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::RealPHI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>In the process of detecting a reduction, we consider a pair of ReductionOP, which we refer to as real and imag (or vice versa), and traverse the use-tree to detect complex operations.</p>


<p>As this is a reduction operation, it will eventually reach RealPHI and ImagPHI, which corresponds to the ReductionOPs that we suspect to be complex. RealPHI and ImagPHI are used by the identifyPHINode method.</p>


<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### ReductionInfo {#aa082061229175790bb77502a904a21ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt;Instruction *, std::pair&lt;PHINode *, Instruction *&gt; &gt; anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::ReductionInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ReductionInfo maps from ReductionOp to PHInode and <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> OutsideUser as it is shown in the IR:</p>


<p>vector.body: PHInode = phi &lt;vector type&gt; [ zeroinitializer, entry ], [ ReductionOp, vector.body ] ... ReductionOp = fadd i64 ... ... br i1 condition, label vector.body, middle.block</p>


<p>middle.block: OutsideUser = llvm.vector.reduce.fadd(..., ReductionOp)</p>


<p>OutsideUser can be <span class="doxyComputerOutput">llvm.vector.reduce.fadd</span> or <span class="doxyComputerOutput">fadd</span> preceding <span class="doxyComputerOutput">llvm.vector.reduce.fadd</span> when unroll factor isn't one.</p>


<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### RootToNode {#a098ed970ff8db7aee1ddd739158d0442}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;Instruction *, NodePtr&gt; anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::RootToNode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Root instructions are instructions from which complex computation starts.</p>

<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### TL {#aa83a1aba8e1648a4fb53881455ce7ccb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLowering* anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::TL = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

### TLI {#aa229dbdc43dd9054f8ff1df4c749a70d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLibraryInfo* anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::TLI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp">ComplexDeinterleavingPass.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
