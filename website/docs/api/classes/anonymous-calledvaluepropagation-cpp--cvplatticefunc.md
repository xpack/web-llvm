---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticefunc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CVPLatticeFunc` Class

<p>The custom lattice function used by the generic sparse propagation solver. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{CalledValuePropagation.cpp}::CVPLatticeFunc { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/abstractlatticefunction">AbstractLatticeFunction&lt;LatticeKey, LatticeVal&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/abstractlatticefunction">AbstractLatticeFunction</a> - This class is implemented by the dataflow instance to specify what the lattice values are and how they handle merges etc. <a href="/web-llvm/docs/api/classes/llvm/abstractlatticefunction/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2871c5f1c7d8fc5bcd439d7bcbb062f0">CVPLatticeFunc</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval">CVPLatticeVal</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb30837e313d7f27034e124d4b11b682">ComputeLatticeVal</a> (CVPLatticeKey Key) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute and return a <a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval">CVPLatticeVal</a> for the given <a href="/web-llvm/docs/api/namespaces/anonymous-calledvaluepropagation-cpp-/#ad7f1b84f271a81d82529c9325b602ac5">CVPLatticeKey</a>. <a href="#afb30837e313d7f27034e124d4b11b682">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval">CVPLatticeVal</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0011b8df581b97747a420890826a7eeb">MergeValues</a> (CVPLatticeVal X, CVPLatticeVal Y) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge the two given lattice values. <a href="#a0011b8df581b97747a420890826a7eeb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07b5f3acfce195f2c0a986f1a5e4ae4d">ComputeInstructionState</a> (Instruction &amp;I, SmallDenseMap&lt; CVPLatticeKey, CVPLatticeVal, 16 &gt; &amp;ChangedValues, SparseSolver&lt; CVPLatticeKey, CVPLatticeVal &gt; &amp;SS) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the lattice values that change as a result of executing the given instruction. <a href="#a07b5f3acfce195f2c0a986f1a5e4ae4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e88a64a5ab058152c2b3527235b8e35">PrintLatticeVal</a> (CVPLatticeVal LV, raw_ostream &amp;OS) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the given <a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval">CVPLatticeVal</a> to the specified stream. <a href="#a8e88a64a5ab058152c2b3527235b8e35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbdbb95ae012d4c2490d6222fcea1ba0">PrintLatticeKey</a> (CVPLatticeKey Key, raw_ostream &amp;OS) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the given <a href="/web-llvm/docs/api/namespaces/anonymous-calledvaluepropagation-cpp-/#ad7f1b84f271a81d82529c9325b602ac5">CVPLatticeKey</a> to the specified stream. <a href="#adbdbb95ae012d4c2490d6222fcea1ba0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55c60f0886755f1d37ce6220d23ec4bc">getIndirectCalls</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We collect a set of indirect calls when visiting call sites. <a href="#a55c60f0886755f1d37ce6220d23ec4bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval">CVPLatticeVal</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c55f3a97181f269156b826a7c55b4b6">computeConstant</a> (Constant *C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute a new lattice value for the given constant. <a href="#a1c55f3a97181f269156b826a7c55b4b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f75e0e3c87665740faeff537f9ea06e">visitReturn</a> (ReturnInst &amp;I, SmallDenseMap&lt; CVPLatticeKey, CVPLatticeVal, 16 &gt; &amp;ChangedValues, SparseSolver&lt; CVPLatticeKey, CVPLatticeVal &gt; &amp;SS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle return instructions. <a href="#a4f75e0e3c87665740faeff537f9ea06e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25fde0929ac4c41e8ea4fb0cb58cf9e8">visitCallBase</a> (CallBase &amp;CB, SmallDenseMap&lt; CVPLatticeKey, CVPLatticeVal, 16 &gt; &amp;ChangedValues, SparseSolver&lt; CVPLatticeKey, CVPLatticeVal &gt; &amp;SS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle call sites. <a href="#a25fde0929ac4c41e8ea4fb0cb58cf9e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73311c82b2106d6f1b9a1293627da1ab">visitSelect</a> (SelectInst &amp;I, SmallDenseMap&lt; CVPLatticeKey, CVPLatticeVal, 16 &gt; &amp;ChangedValues, SparseSolver&lt; CVPLatticeKey, CVPLatticeVal &gt; &amp;SS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle select instructions. <a href="#a73311c82b2106d6f1b9a1293627da1ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a915f4f9419abdf3719dc5db0ad525372">visitLoad</a> (LoadInst &amp;I, SmallDenseMap&lt; CVPLatticeKey, CVPLatticeVal, 16 &gt; &amp;ChangedValues, SparseSolver&lt; CVPLatticeKey, CVPLatticeVal &gt; &amp;SS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle load instructions. <a href="#a915f4f9419abdf3719dc5db0ad525372">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5622d73374d4e7083c41cf5b27ae8ad2">visitStore</a> (StoreInst &amp;I, SmallDenseMap&lt; CVPLatticeKey, CVPLatticeVal, 16 &gt; &amp;ChangedValues, SparseSolver&lt; CVPLatticeKey, CVPLatticeVal &gt; &amp;SS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle store instructions. <a href="#a5622d73374d4e7083c41cf5b27ae8ad2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a948ff62dd6e6404557c86c149e9aecf9">visitInst</a> (Instruction &amp;I, SmallDenseMap&lt; CVPLatticeKey, CVPLatticeVal, 16 &gt; &amp;ChangedValues, SparseSolver&lt; CVPLatticeKey, CVPLatticeVal &gt; &amp;SS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle all other instructions. <a href="#a948ff62dd6e6404557c86c149e9aecf9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> *, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31556d2c0d0852914df4fd0c965cf450">IndirectCalls</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Holds the indirect calls we encounter during the analysis. <a href="#a31556d2c0d0852914df4fd0c965cf450">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The custom lattice function used by the generic sparse propagation solver.</p>


<p>It handles merging lattice values and computing new lattice values for constants, arguments, values returned from trackable functions, and values located in trackable global variables. It also computes the lattice values that change as a result of executing instructions.</p>


<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CVPLatticeFunc() {#a2871c5f1c7d8fc5bcd439d7bcbb062f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CalledValuePropagation.cpp}::CVPLatticeFunc::CVPLatticeFunc ()</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/abstractlatticefunction/#a3630859cb3da8279f4ee4b50e6d86851">llvm::AbstractLatticeFunction&lt; CVPLatticeKey, CVPLatticeVal &gt;::AbstractLatticeFunction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp/#a1d2bce545ae26cccf351c2c0d35d64e4">runCVP</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### ComputeInstructionState() {#a07b5f3acfce195f2c0a986f1a5e4ae4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CalledValuePropagation.cpp}::CVPLatticeFunc::ComputeInstructionState (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-calledvaluepropagation-cpp-/#ad7f1b84f271a81d82529c9325b602ac5">CVPLatticeKey</a>, <a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval">CVPLatticeVal</a>, 16 &gt; &amp; ChangedValues, <a href="/web-llvm/docs/api/classes/llvm/sparsesolver">SparseSolver</a>&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-calledvaluepropagation-cpp-/#ad7f1b84f271a81d82529c9325b602ac5">CVPLatticeKey</a>, <a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval">CVPLatticeVal</a> &gt; &amp; SS)</td>
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

<p>Compute the lattice values that change as a result of executing the given instruction.</p>


<p>The changed values are stored in <span class="doxyComputerOutput">ChangedValues</span>. We handle just a few kinds of instructions since we're only propagating values that can be called.</p>


<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### ComputeLatticeVal() {#afb30837e313d7f27034e124d4b11b682}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CVPLatticeVal anonymous{CalledValuePropagation.cpp}::CVPLatticeFunc::ComputeLatticeVal (<a href="/web-llvm/docs/api/namespaces/anonymous-calledvaluepropagation-cpp-/#ad7f1b84f271a81d82529c9325b602ac5">CVPLatticeKey</a> Key)</td>
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

<p>Compute and return a <a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval">CVPLatticeVal</a> for the given <a href="/web-llvm/docs/api/namespaces/anonymous-calledvaluepropagation-cpp-/#ad7f1b84f271a81d82529c9325b602ac5">CVPLatticeKey</a>.</p>

<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af1d3deadf8d348b2329f4e7fa5386e5b">llvm::canTrackArgumentsInterprocedurally</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7414a7c636bc5a30b0e8478019a1bcd4">llvm::canTrackGlobalVariableInterprocedurally</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abea1c899c9779be14155ce717136ebe4">llvm::canTrackReturnsInterprocedurally</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractlatticefunction/#a02ada13ec5d86d5ef19b22b784b4ffd1">llvm::AbstractLatticeFunction&lt; CVPLatticeKey, CVPLatticeVal &gt;::getOverdefinedVal</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractlatticefunction/#ac8c706169cac63369933e4bc06012858">llvm::AbstractLatticeFunction&lt; CVPLatticeKey, CVPLatticeVal &gt;::getUndefVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-calledvaluepropagation-cpp-/#a5f10072974ec01bdf70a2f2215f44b23a4789f23283b3a61f858b641a1bef19a3">anonymous{CalledValuePropagation.cpp}::Memory</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-calledvaluepropagation-cpp-/#a5f10072974ec01bdf70a2f2215f44b23a0ba7583639a274c434bbe6ef797115a4">anonymous{CalledValuePropagation.cpp}::Register</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-calledvaluepropagation-cpp-/#a5f10072974ec01bdf70a2f2215f44b23a988fd738de9c6d177440c5dcf69e73ce">anonymous{CalledValuePropagation.cpp}::Return</a>.</p>

</div>
</div>

### getIndirectCalls() {#a55c60f0886755f1d37ce6220d23ec4bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSetImpl&lt; CallBase * &gt; &amp; anonymous{CalledValuePropagation.cpp}::CVPLatticeFunc::getIndirectCalls ()</td>
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

<p>We collect a set of indirect calls when visiting call sites.</p>


<p>This method returns a reference to that set.</p>


<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>

</div>
</div>

### MergeValues() {#a0011b8df581b97747a420890826a7eeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CVPLatticeVal anonymous{CalledValuePropagation.cpp}::CVPLatticeFunc::MergeValues (<a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval">CVPLatticeVal</a> X, <a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval">CVPLatticeVal</a> Y)</td>
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

<p>Merge the two given lattice values.</p>


<p>The interesting cases are merging two FunctionSet values and a FunctionSet value with an Undefined value. For these cases, we simply union the function sets. If the size of the union is greater than the maximum functions we track, the merged value is overdefined.</p>


<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/abstractlatticefunction/#a02ada13ec5d86d5ef19b22b784b4ffd1">llvm::AbstractLatticeFunction&lt; CVPLatticeKey, CVPLatticeVal &gt;::getOverdefinedVal</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractlatticefunction/#ac8c706169cac63369933e4bc06012858">llvm::AbstractLatticeFunction&lt; CVPLatticeKey, CVPLatticeVal &gt;::getUndefVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp/#a0c244e5ff5a1fb8c12ec6d8fe73d0ba0">MaxFunctionsPerValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### PrintLatticeKey() {#adbdbb95ae012d4c2490d6222fcea1ba0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CalledValuePropagation.cpp}::CVPLatticeFunc::PrintLatticeKey (<a href="/web-llvm/docs/api/namespaces/anonymous-calledvaluepropagation-cpp-/#ad7f1b84f271a81d82529c9325b602ac5">CVPLatticeKey</a> Key, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>Print the given <a href="/web-llvm/docs/api/namespaces/anonymous-calledvaluepropagation-cpp-/#ad7f1b84f271a81d82529c9325b602ac5">CVPLatticeKey</a> to the specified stream.</p>

<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-calledvaluepropagation-cpp-/#a5f10072974ec01bdf70a2f2215f44b23a4789f23283b3a61f858b641a1bef19a3">anonymous{CalledValuePropagation.cpp}::Memory</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-calledvaluepropagation-cpp-/#a5f10072974ec01bdf70a2f2215f44b23a0ba7583639a274c434bbe6ef797115a4">anonymous{CalledValuePropagation.cpp}::Register</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-calledvaluepropagation-cpp-/#a5f10072974ec01bdf70a2f2215f44b23a988fd738de9c6d177440c5dcf69e73ce">anonymous{CalledValuePropagation.cpp}::Return</a>.</p>

</div>
</div>

### PrintLatticeVal() {#a8e88a64a5ab058152c2b3527235b8e35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CalledValuePropagation.cpp}::CVPLatticeFunc::PrintLatticeVal (<a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval">CVPLatticeVal</a> LV, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>Print the given <a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval">CVPLatticeVal</a> to the specified stream.</p>

<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/abstractlatticefunction/#a02ada13ec5d86d5ef19b22b784b4ffd1">llvm::AbstractLatticeFunction&lt; CVPLatticeKey, CVPLatticeVal &gt;::getOverdefinedVal</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractlatticefunction/#ac8c706169cac63369933e4bc06012858">llvm::AbstractLatticeFunction&lt; CVPLatticeKey, CVPLatticeVal &gt;::getUndefVal</a> and <a href="/web-llvm/docs/api/classes/llvm/abstractlatticefunction/#a9f907a6f73caddcf4ee0f2da89775a8d">llvm::AbstractLatticeFunction&lt; CVPLatticeKey, CVPLatticeVal &gt;::getUntrackedVal</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### computeConstant() {#a1c55f3a97181f269156b826a7c55b4b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CVPLatticeVal anonymous{CalledValuePropagation.cpp}::CVPLatticeFunc::computeConstant (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C)</td>
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

<p>Compute a new lattice value for the given constant.</p>


<p>The constant, after stripping any pointer casts, should be a <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>. We ignore null pointers as an optimization, since calling these values is undefined behavior.</p>


<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>

</div>
</div>

### visitCallBase() {#a25fde0929ac4c41e8ea4fb0cb58cf9e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CalledValuePropagation.cpp}::CVPLatticeFunc::visitCallBase (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-calledvaluepropagation-cpp-/#ad7f1b84f271a81d82529c9325b602ac5">CVPLatticeKey</a>, <a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval">CVPLatticeVal</a>, 16 &gt; &amp; ChangedValues, <a href="/web-llvm/docs/api/classes/llvm/sparsesolver">SparseSolver</a>&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-calledvaluepropagation-cpp-/#ad7f1b84f271a81d82529c9325b602ac5">CVPLatticeKey</a>, <a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval">CVPLatticeVal</a> &gt; &amp; SS)</td>
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

<p>Handle call sites.</p>


<p>The state of a called function's formal arguments is the merge of the argument state with the call sites corresponding actual argument state. The call site state is the merge of the call site state with the returned value state of the called function.</p>


<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>

</div>
</div>

### visitInst() {#a948ff62dd6e6404557c86c149e9aecf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CalledValuePropagation.cpp}::CVPLatticeFunc::visitInst (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-calledvaluepropagation-cpp-/#ad7f1b84f271a81d82529c9325b602ac5">CVPLatticeKey</a>, <a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval">CVPLatticeVal</a>, 16 &gt; &amp; ChangedValues, <a href="/web-llvm/docs/api/classes/llvm/sparsesolver">SparseSolver</a>&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-calledvaluepropagation-cpp-/#ad7f1b84f271a81d82529c9325b602ac5">CVPLatticeKey</a>, <a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval">CVPLatticeVal</a> &gt; &amp; SS)</td>
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

<p>Handle all other instructions.</p>


<p>All other instructions are marked overdefined.</p>


<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>

</div>
</div>

### visitLoad() {#a915f4f9419abdf3719dc5db0ad525372}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CalledValuePropagation.cpp}::CVPLatticeFunc::visitLoad (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-calledvaluepropagation-cpp-/#ad7f1b84f271a81d82529c9325b602ac5">CVPLatticeKey</a>, <a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval">CVPLatticeVal</a>, 16 &gt; &amp; ChangedValues, <a href="/web-llvm/docs/api/classes/llvm/sparsesolver">SparseSolver</a>&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-calledvaluepropagation-cpp-/#ad7f1b84f271a81d82529c9325b602ac5">CVPLatticeKey</a>, <a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval">CVPLatticeVal</a> &gt; &amp; SS)</td>
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

<p>Handle load instructions.</p>


<p>If the pointer operand of the load is a global variable, we attempt to track the value. The loaded value state is the merge of the loaded value state with the global variable state.</p>


<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>

</div>
</div>

### visitReturn() {#a4f75e0e3c87665740faeff537f9ea06e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CalledValuePropagation.cpp}::CVPLatticeFunc::visitReturn (<a href="/web-llvm/docs/api/classes/llvm/returninst">ReturnInst</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-calledvaluepropagation-cpp-/#ad7f1b84f271a81d82529c9325b602ac5">CVPLatticeKey</a>, <a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval">CVPLatticeVal</a>, 16 &gt; &amp; ChangedValues, <a href="/web-llvm/docs/api/classes/llvm/sparsesolver">SparseSolver</a>&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-calledvaluepropagation-cpp-/#ad7f1b84f271a81d82529c9325b602ac5">CVPLatticeKey</a>, <a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval">CVPLatticeVal</a> &gt; &amp; SS)</td>
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

<p>Handle return instructions.</p>


<p>The function's return state is the merge of the returned value state and the function's return state.</p>


<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>

</div>
</div>

### visitSelect() {#a73311c82b2106d6f1b9a1293627da1ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CalledValuePropagation.cpp}::CVPLatticeFunc::visitSelect (<a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-calledvaluepropagation-cpp-/#ad7f1b84f271a81d82529c9325b602ac5">CVPLatticeKey</a>, <a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval">CVPLatticeVal</a>, 16 &gt; &amp; ChangedValues, <a href="/web-llvm/docs/api/classes/llvm/sparsesolver">SparseSolver</a>&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-calledvaluepropagation-cpp-/#ad7f1b84f271a81d82529c9325b602ac5">CVPLatticeKey</a>, <a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval">CVPLatticeVal</a> &gt; &amp; SS)</td>
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

<p>Handle select instructions.</p>


<p>The select instruction state is the merge the true and false value states.</p>


<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>

</div>
</div>

### visitStore() {#a5622d73374d4e7083c41cf5b27ae8ad2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CalledValuePropagation.cpp}::CVPLatticeFunc::visitStore (<a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-calledvaluepropagation-cpp-/#ad7f1b84f271a81d82529c9325b602ac5">CVPLatticeKey</a>, <a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval">CVPLatticeVal</a>, 16 &gt; &amp; ChangedValues, <a href="/web-llvm/docs/api/classes/llvm/sparsesolver">SparseSolver</a>&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-calledvaluepropagation-cpp-/#ad7f1b84f271a81d82529c9325b602ac5">CVPLatticeKey</a>, <a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval">CVPLatticeVal</a> &gt; &amp; SS)</td>
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

<p>Handle store instructions.</p>


<p>If the pointer operand of the store is a global variable, we attempt to track the value. The global variable state is the merge of the stored value state with the global variable state.</p>


<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### IndirectCalls {#a31556d2c0d0852914df4fd0c965cf450}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;CallBase *, 32&gt; anonymous{CalledValuePropagation.cpp}::CVPLatticeFunc::IndirectCalls</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Holds the indirect calls we encounter during the analysis.</p>


<p>We will attach metadata to these calls after the analysis indicating the functions the calls can possibly target.</p>


<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
