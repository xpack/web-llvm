---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/vptransformstate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `VPTransformState` Struct Reference

<p><a href="/web-llvm/docs/api/structs/llvm/vptransformstate">VPTransformState</a> holds information passed down when "executing" a <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>, needed for generating the output IR. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::VPTransformState { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">Transforms/Vectorize/VPlan.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ebf82a75f3e15d18aedb2ea43683d4b">VPTransformState</a> (const TargetTransformInfo *TTI, ElementCount VF, unsigned UF, LoopInfo *LI, DominatorTree *DT, IRBuilderBase &amp;Builder, InnerLoopVectorizer *ILV, VPlan *Plan, Loop *CurrentParentLoop, Type *CanonicalIVTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48955fd76dc29a6b4391aef55ce3efd3">get</a> (VPValue *Def, bool IsScalar=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the generated vector <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> for a given <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> <span class="doxyComputerOutput">Def</span> if <span class="doxyComputerOutput">IsScalar</span> is false, otherwise return the generated scalar. <a href="#a48955fd76dc29a6b4391aef55ce3efd3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac239a91075321de19449d54f092ab82a">get</a> (VPValue *Def, const VPLane &amp;Lane)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the generated <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> for a given <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> and given Part and Lane. <a href="#ac239a91075321de19449d54f092ab82a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01e794c73f3f3d02f6f07b38b53d1d7d">hasVectorValue</a> (VPValue *Def)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01cda016820d12b73ec4b20254c15481">hasScalarValue</a> (VPValue *Def, VPLane Lane)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3ac355d8def4b4935de51a9560b44d7">set</a> (VPValue *Def, Value *V, bool IsScalar=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the generated vector <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> for a given <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a>, if <span class="doxyComputerOutput">IsScalar</span> is false. <a href="#af3ac355d8def4b4935de51a9560b44d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca235882503a6560cc0ad817721b671c">reset</a> (VPValue *Def, Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset an existing vector value for <span class="doxyComputerOutput">Def</span> and a given <span class="doxyComputerOutput">Part</span>. <a href="#aca235882503a6560cc0ad817721b671c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96f61745bc423d971ad2369e9175335a">set</a> (VPValue *Def, Value *V, const VPLane &amp;Lane)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the generated scalar <span class="doxyComputerOutput">V</span> for <span class="doxyComputerOutput">Def</span> and the given <span class="doxyComputerOutput">Lane</span>. <a href="#a96f61745bc423d971ad2369e9175335a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85a2c16cba57732c4896af99fd67c0d0">reset</a> (VPValue *Def, Value *V, const VPLane &amp;Lane)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset an existing scalar value for <span class="doxyComputerOutput">Def</span> and a given <span class="doxyComputerOutput">Lane</span>. <a href="#a85a2c16cba57732c4896af99fd67c0d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5797d36eb67fb263b8c111e12e9818aa">addNewMetadata</a> (Instruction *To, const Instruction *Orig)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add additional metadata to <span class="doxyComputerOutput">To</span> that was not present on <span class="doxyComputerOutput">Orig</span>. <a href="#a5797d36eb67fb263b8c111e12e9818aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4238cde7c588137b218845e15ce7cb34">addMetadata</a> (Value *To, Instruction *From)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add metadata from one instruction to another. <a href="#a4238cde7c588137b218845e15ce7cb34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae69fb3f4bb10e284f6e2090ff13a7c61">setDebugLocFrom</a> (DebugLoc DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the debug location in the builder using the debug location <span class="doxyComputerOutput">DL</span>. <a href="#ae69fb3f4bb10e284f6e2090ff13a7c61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a447197675bef200ebccf2b4d5b90ce4c">packScalarIntoVectorValue</a> (VPValue *Def, const VPLane &amp;Lane)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct the vector value of a scalarized value <span class="doxyComputerOutput">V</span> one lane at a time. <a href="#a447197675bef200ebccf2b4d5b90ce4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb13e5ab4533e5b2695a9587e3b94821">TTI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Transform Info. <a href="#abb13e5ab4533e5b2695a9587e3b94821">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adeaf44a788c3e001582a71790894b78d">VF</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The chosen Vectorization Factor of the loop being vectorized. <a href="#adeaf44a788c3e001582a71790894b78d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/vplane">VPLane</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96b2bb4032a684ffc2081371a58c3036">Lane</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hold the index to generate specific scalar instructions. <a href="#a96b2bb4032a684ffc2081371a58c3036">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f9f697a98fcec6357affe7769381305">Data</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b7320d132cc4de25e10a3a040930dcf">CFG</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a064321c6b19fea81a6f75a27d6a96025">LI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hold a pointer to <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> to register new basic blocks in the loop. <a href="#a064321c6b19fea81a6f75a27d6a96025">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8a293d9d0bf609e45f591ce4bd55bb3">Builder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hold a reference to the <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a> used to generate output IR code. <a href="#aa8a293d9d0bf609e45f591ce4bd55bb3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer">InnerLoopVectorizer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1c0c61b215e77a1ccb1d7e413be42d1">ILV</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hold a pointer to <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer">InnerLoopVectorizer</a> to reuse its IR generation methods. <a href="#ac1c0c61b215e77a1ccb1d7e413be42d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0b363a134c3bfac25ba209704ef3ee3">Plan</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pointer to the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> code is generated for. <a href="#ac0b363a134c3bfac25ba209704ef3ee3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af27e976d899bab8ed5802d667cba34e4">CurrentParentLoop</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The parent loop object for the current scope, or nullptr. <a href="#af27e976d899bab8ed5802d667cba34e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopversioning">LoopVersioning</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a555dce6c07b78f3291cbcdca4c28ff6a">LVer</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/loopversioning">LoopVersioning</a>. <a href="#a555dce6c07b78f3291cbcdca4c28ff6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fe11cf712ce34a33ab0b5c5c2667ec2">ExpandedSCEVs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map SCEVs to their expanded values. <a href="#a1fe11cf712ce34a33ab0b5c5c2667ec2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vptypeanalysis">VPTypeAnalysis</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d5b7257acb6a8ba7029d597872ebfa5">TypeAnalysis</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>VPlan-based type analysis. <a href="#a2d5b7257acb6a8ba7029d597872ebfa5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/structs/llvm/vptransformstate">VPTransformState</a> holds information passed down when "executing" a <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>, needed for generating the output IR.</p>

<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VPTransformState() {#a9ebf82a75f3e15d18aedb2ea43683d4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPTransformState::VPTransformState (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * TTI, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF, unsigned UF, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer">InnerLoopVectorizer</a> * ILV, <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> * Plan, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * CurrentParentLoop, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * CanonicalIVTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="#aa8a293d9d0bf609e45f591ce4bd55bb3">Builder</a>, <a href="#a4b7320d132cc4de25e10a3a040930dcf">CFG</a>, <a href="#af27e976d899bab8ed5802d667cba34e4">CurrentParentLoop</a>, <a href="#ac1c0c61b215e77a1ccb1d7e413be42d1">ILV</a>, <a href="#a064321c6b19fea81a6f75a27d6a96025">LI</a>, <a href="#a555dce6c07b78f3291cbcdca4c28ff6a">LVer</a>, <a href="#ac0b363a134c3bfac25ba209704ef3ee3">Plan</a>, <a href="#abb13e5ab4533e5b2695a9587e3b94821">TTI</a>, <a href="#a2d5b7257acb6a8ba7029d597872ebfa5">TypeAnalysis</a> and <a href="#adeaf44a788c3e001582a71790894b78d">VF</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addMetadata() {#a4238cde7c588137b218845e15ce7cb34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPTransformState::addMetadata (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * To, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * From)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add metadata from one instruction to another.</p>


<p>This includes both the original MDs from <span class="doxyComputerOutput">From</span> and additional ones (</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#a5797d36eb67fb263b8c111e12e9818aa">addNewMetadata</a>). <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> this <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> <em>newly created</em> <a href="/web-llvm/docs/api/namespaces/llvm/#a7e3e687ddfdcbacd404bcf17b917dd88">instructions</a> in the <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">vector</a> loop.</p></dd>
</dl>


<p>Declaration at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="#a5797d36eb67fb263b8c111e12e9818aa">addNewMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a48a6deb3e714d54e75caadcf84b0ca76">llvm::propagateMetadata</a>.</p>

</div>
</div>

### addNewMetadata() {#a5797d36eb67fb263b8c111e12e9818aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPTransformState::addNewMetadata (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * To, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Orig)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add additional metadata to <span class="doxyComputerOutput">To</span> that was not present on <span class="doxyComputerOutput">Orig</span>.</p>


<p>Currently this is used to add the noalias annotations based on the inserted memchecks. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> this for instructions that are <em>cloned</em> into the vector loop.</p>


<p>Declaration at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#a555dce6c07b78f3291cbcdca4c28ff6a">LVer</a>.</p>


<p>Referenced by <a href="#a4238cde7c588137b218845e15ce7cb34">addMetadata</a>.</p>

</div>
</div>

### get() {#a48955fd76dc29a6b4391aef55ce3efd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * VPTransformState::get (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Def, bool IsScalar=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the generated vector <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> for a given <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> <span class="doxyComputerOutput">Def</span> if <span class="doxyComputerOutput">IsScalar</span> is false, otherwise return the generated scalar.</p>


<p>\See set.</p>


<p>Declaration at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#aa8a293d9d0bf609e45f591ce4bd55bb3">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a4b7320d132cc4de25e10a3a040930dcf">CFG</a>, <a href="#a2f9f697a98fcec6357affe7769381305">Data</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="#a48955fd76dc29a6b4391aef55ce3efd3">get</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="#a01cda016820d12b73ec4b20254c15481">hasScalarValue</a>, <a href="#a01e794c73f3f3d02f6f07b38b53d1d7d">hasVectorValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a002a77cdbc23293b8f7a8458ffd0f905">llvm::vputils::isUniformAfterVectorization</a>, <a href="#a96b2bb4032a684ffc2081371a58c3036">Lane</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a5e3c306be8d629a994f3644765421d5f">llvm::vputils::onlyFirstLaneUsed</a>, <a href="#a447197675bef200ebccf2b4d5b90ce4c">packScalarIntoVectorValue</a>, <a href="#ac0b363a134c3bfac25ba209704ef3ee3">Plan</a>, <a href="#af3ac355d8def4b4935de51a9560b44d7">set</a> and <a href="#adeaf44a788c3e001582a71790894b78d">VF</a>.</p>


<p>Referenced by <a href="#a48955fd76dc29a6b4391aef55ce3efd3">get</a> and <a href="#a447197675bef200ebccf2b4d5b90ce4c">packScalarIntoVectorValue</a>.</p>

</div>
</div>

### get() {#ac239a91075321de19449d54f092ab82a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * VPTransformState::get (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Def, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vplane">VPLane</a> &amp; Lane)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the generated <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> for a given <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> and given Part and Lane.</p>

<p>Declaration at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa8a293d9d0bf609e45f591ce4bd55bb3">Builder</a>, <a href="#a2f9f697a98fcec6357affe7769381305">Data</a>, <a href="/web-llvm/docs/api/classes/llvm/vplane/#af6be7b0459911799a13a8174138c7020">llvm::VPLane::getFirstLane</a>, <a href="#a01cda016820d12b73ec4b20254c15481">hasScalarValue</a>, <a href="#a01e794c73f3f3d02f6f07b38b53d1d7d">hasVectorValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a002a77cdbc23293b8f7a8458ffd0f905">llvm::vputils::isUniformAfterVectorization</a>, <a href="#a96b2bb4032a684ffc2081371a58c3036">Lane</a> and <a href="#adeaf44a788c3e001582a71790894b78d">VF</a>.</p>

</div>
</div>

### hasScalarValue() {#a01cda016820d12b73ec4b20254c15481}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPTransformState::hasScalarValue (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Def, <a href="/web-llvm/docs/api/classes/llvm/vplane">VPLane</a> Lane)</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="#a2f9f697a98fcec6357affe7769381305">Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a96b2bb4032a684ffc2081371a58c3036">Lane</a> and <a href="#adeaf44a788c3e001582a71790894b78d">VF</a>.</p>


<p>Referenced by <a href="#a48955fd76dc29a6b4391aef55ce3efd3">get</a> and <a href="#ac239a91075321de19449d54f092ab82a">get</a>.</p>

</div>
</div>

### hasVectorValue() {#a01e794c73f3f3d02f6f07b38b53d1d7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPTransformState::hasVectorValue (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Def)</td>
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



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="#a2f9f697a98fcec6357affe7769381305">Data</a>.</p>


<p>Referenced by <a href="#a48955fd76dc29a6b4391aef55ce3efd3">get</a> and <a href="#ac239a91075321de19449d54f092ab82a">get</a>.</p>

</div>
</div>

### packScalarIntoVectorValue() {#a447197675bef200ebccf2b4d5b90ce4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPTransformState::packScalarIntoVectorValue (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Def, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vplane">VPLane</a> &amp; Lane)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct the vector value of a scalarized value <span class="doxyComputerOutput">V</span> one lane at a time.</p>

<p>Declaration at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="#aa8a293d9d0bf609e45f591ce4bd55bb3">Builder</a>, <a href="#a48955fd76dc29a6b4391aef55ce3efd3">get</a>, <a href="#a96b2bb4032a684ffc2081371a58c3036">Lane</a>, <a href="#af3ac355d8def4b4935de51a9560b44d7">set</a> and <a href="#adeaf44a788c3e001582a71790894b78d">VF</a>.</p>


<p>Referenced by <a href="#a48955fd76dc29a6b4391aef55ce3efd3">get</a>.</p>

</div>
</div>

### reset() {#aca235882503a6560cc0ad817721b671c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPTransformState::reset (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Def, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Reset an existing vector value for <span class="doxyComputerOutput">Def</span> and a given <span class="doxyComputerOutput">Part</span>.</p>

<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a2f9f697a98fcec6357affe7769381305">Data</a>.</p>

</div>
</div>

### reset() {#a85a2c16cba57732c4896af99fd67c0d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPTransformState::reset (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Def, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vplane">VPLane</a> &amp; Lane)</td>
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

<p>Reset an existing scalar value for <span class="doxyComputerOutput">Def</span> and a given <span class="doxyComputerOutput">Lane</span>.</p>

<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a2f9f697a98fcec6357affe7769381305">Data</a>, <a href="#a96b2bb4032a684ffc2081371a58c3036">Lane</a> and <a href="#adeaf44a788c3e001582a71790894b78d">VF</a>.</p>

</div>
</div>

### set() {#af3ac355d8def4b4935de51a9560b44d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPTransformState::set (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Def, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, bool IsScalar=false)</td>
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

<p>Set the generated vector <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> for a given <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a>, if <span class="doxyComputerOutput">IsScalar</span> is false.</p>


<p>If <span class="doxyComputerOutput">IsScalar</span> is true, set the scalar in lane 0.</p>


<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a2f9f697a98fcec6357affe7769381305">Data</a>, <a href="#af3ac355d8def4b4935de51a9560b44d7">set</a> and <a href="#adeaf44a788c3e001582a71790894b78d">VF</a>.</p>


<p>Referenced by <a href="#a48955fd76dc29a6b4391aef55ce3efd3">get</a>, <a href="#a447197675bef200ebccf2b4d5b90ce4c">packScalarIntoVectorValue</a> and <a href="#af3ac355d8def4b4935de51a9560b44d7">set</a>.</p>

</div>
</div>

### set() {#a96f61745bc423d971ad2369e9175335a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPTransformState::set (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * Def, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vplane">VPLane</a> &amp; Lane)</td>
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

<p>Set the generated scalar <span class="doxyComputerOutput">V</span> for <span class="doxyComputerOutput">Def</span> and the given <span class="doxyComputerOutput">Lane</span>.</p>

<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a2f9f697a98fcec6357affe7769381305">Data</a>, <a href="#a96b2bb4032a684ffc2081371a58c3036">Lane</a> and <a href="#adeaf44a788c3e001582a71790894b78d">VF</a>.</p>

</div>
</div>

### setDebugLocFrom() {#ae69fb3f4bb10e284f6e2090ff13a7c61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPTransformState::setDebugLocFrom (<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the debug location in the builder using the debug location <span class="doxyComputerOutput">DL</span>.</p>

<p>Declaration at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="#aa8a293d9d0bf609e45f591ce4bd55bb3">Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocation/#ae79e1d26012dca43293dea8a19fc002b">llvm::DILocation::cloneByMultiplyingDuplicationFactor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61cf315897c96016607a2b8d5916a64d">llvm::EnableFSDiscriminator</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#ac0b363a134c3bfac25ba209704ef3ee3">Plan</a> and <a href="#adeaf44a788c3e001582a71790894b78d">VF</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Builder {#aa8a293d9d0bf609e45f591ce4bd55bb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRBuilderBase&amp; llvm::VPTransformState::Builder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Hold a reference to the <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a> used to generate output IR code.</p>

<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vplan/#a5a956378c8f267d4b2afc6e036a08d42">llvm::VPlan::createInitialVPlan</a>, <a href="#a48955fd76dc29a6b4391aef55ce3efd3">get</a>, <a href="#ac239a91075321de19449d54f092ab82a">get</a>, <a href="#a447197675bef200ebccf2b4d5b90ce4c">packScalarIntoVectorValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a143bc5faeb35f7363570e97bccf76e53">llvm::VPlan::prepareToExecute</a>, <a href="#ae69fb3f4bb10e284f6e2090ff13a7c61">setDebugLocFrom</a> and <a href="#a9ebf82a75f3e15d18aedb2ea43683d4b">VPTransformState</a>.</p>

</div>
</div>

### CFG {#a4b7320d132cc4de25e10a3a040930dcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct llvm::VPTransformState::CFGState llvm::VPTransformState::CFG</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="#a48955fd76dc29a6b4391aef55ce3efd3">get</a> and <a href="#a9ebf82a75f3e15d18aedb2ea43683d4b">VPTransformState</a>.</p>

</div>
</div>

### CurrentParentLoop {#af27e976d899bab8ed5802d667cba34e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop* llvm::VPTransformState::CurrentParentLoop = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The parent loop object for the current scope, or nullptr.</p>

<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="#a9ebf82a75f3e15d18aedb2ea43683d4b">VPTransformState</a>.</p>

</div>
</div>

### Data {#a2f9f697a98fcec6357affe7769381305}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct llvm::VPTransformState::DataState llvm::VPTransformState::Data</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="#a48955fd76dc29a6b4391aef55ce3efd3">get</a>, <a href="#ac239a91075321de19449d54f092ab82a">get</a>, <a href="#a01cda016820d12b73ec4b20254c15481">hasScalarValue</a>, <a href="#a01e794c73f3f3d02f6f07b38b53d1d7d">hasVectorValue</a>, <a href="#aca235882503a6560cc0ad817721b671c">reset</a>, <a href="#a85a2c16cba57732c4896af99fd67c0d0">reset</a>, <a href="#af3ac355d8def4b4935de51a9560b44d7">set</a> and <a href="#a96f61745bc423d971ad2369e9175335a">set</a>.</p>

</div>
</div>

### ExpandedSCEVs {#a1fe11cf712ce34a33ab0b5c5c2667ec2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const SCEV *, Value *&gt; llvm::VPTransformState::ExpandedSCEVs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map SCEVs to their expanded values.</p>


<p>Populated when executing VPExpandSCEVRecipes.</p>


<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### ILV {#ac1c0c61b215e77a1ccb1d7e413be42d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InnerLoopVectorizer* llvm::VPTransformState::ILV</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Hold a pointer to <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer">InnerLoopVectorizer</a> to reuse its IR generation methods.</p>

<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="#a9ebf82a75f3e15d18aedb2ea43683d4b">VPTransformState</a>.</p>

</div>
</div>

### Lane {#a96b2bb4032a684ffc2081371a58c3036}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;VPLane&gt; llvm::VPTransformState::Lane</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Hold the index to generate specific scalar instructions.</p>


<p>Null indicates that all instances are to be generated, using either scalar or vector instructions.</p>


<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#ac503442fd011b1b4a03ab40ad3f9402e">llvm::VPRegionBlock::execute</a>, <a href="#a48955fd76dc29a6b4391aef55ce3efd3">get</a>, <a href="#ac239a91075321de19449d54f092ab82a">get</a>, <a href="#a01cda016820d12b73ec4b20254c15481">hasScalarValue</a>, <a href="#a447197675bef200ebccf2b4d5b90ce4c">packScalarIntoVectorValue</a>, <a href="#a85a2c16cba57732c4896af99fd67c0d0">reset</a> and <a href="#a96f61745bc423d971ad2369e9175335a">set</a>.</p>

</div>
</div>

### LI {#a064321c6b19fea81a6f75a27d6a96025}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* llvm::VPTransformState::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Hold a pointer to <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> to register new basic blocks in the loop.</p>

<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="#a9ebf82a75f3e15d18aedb2ea43683d4b">VPTransformState</a>.</p>

</div>
</div>

### LVer {#a555dce6c07b78f3291cbcdca4c28ff6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopVersioning* llvm::VPTransformState::LVer = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/loopversioning">LoopVersioning</a>.</p>


<p>It's only set up (non-null) if memchecks were used.</p>


<p>This is currently only used to add no-alias metadata based on the memchecks. The actually versioning is performed manually.</p>


<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="#a5797d36eb67fb263b8c111e12e9818aa">addNewMetadata</a> and <a href="#a9ebf82a75f3e15d18aedb2ea43683d4b">VPTransformState</a>.</p>

</div>
</div>

### Plan {#ac0b363a134c3bfac25ba209704ef3ee3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPlan* llvm::VPTransformState::Plan</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pointer to the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> code is generated for.</p>

<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a36d6728b8c3cfca0a9bd02c3f0273477">llvm::LoopVectorizationPlanner::buildVPlans</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a5a956378c8f267d4b2afc6e036a08d42">llvm::VPlan::createInitialVPlan</a>, <a href="#a48955fd76dc29a6b4391aef55ce3efd3">get</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a10f355c5a55dd7e98d31c2f7e0b590aa">llvm::LoopVectorizationPlanner::getPlanFor</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#ac3a6a342405e61ad992020460a530dc4">llvm::LoopVectorizationPlanner::printPlans</a>, <a href="#ae69fb3f4bb10e284f6e2090ff13a7c61">setDebugLocFrom</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinterleavedaccessinfo/#a24f3316a0caf6117d7447bda1023823f">llvm::VPInterleavedAccessInfo::VPInterleavedAccessInfo</a> and <a href="#a9ebf82a75f3e15d18aedb2ea43683d4b">VPTransformState</a>.</p>

</div>
</div>

### TTI {#abb13e5ab4533e5b2695a9587e3b94821}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetTransformInfo* llvm::VPTransformState::TTI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Transform Info.</p>

<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="#a9ebf82a75f3e15d18aedb2ea43683d4b">VPTransformState</a>.</p>

</div>
</div>

### TypeAnalysis {#a2d5b7257acb6a8ba7029d597872ebfa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPTypeAnalysis llvm::VPTransformState::TypeAnalysis</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>VPlan-based type analysis.</p>

<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="#a9ebf82a75f3e15d18aedb2ea43683d4b">VPTransformState</a>.</p>

</div>
</div>

### VF {#adeaf44a788c3e001582a71790894b78d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ElementCount llvm::VPTransformState::VF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The chosen Vectorization Factor of the loop being vectorized.</p>

<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a36d6728b8c3cfca0a9bd02c3f0273477">llvm::LoopVectorizationPlanner::buildVPlans</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a6b4c6fbb498daefe2972ddc3546c926b">llvm::VPBasicBlock::cost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#aa948ba905ff37c533b3c85068f94fd24">llvm::VPRegionBlock::cost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#ac503442fd011b1b4a03ab40ad3f9402e">llvm::VPRegionBlock::execute</a>, <a href="#a48955fd76dc29a6b4391aef55ce3efd3">get</a>, <a href="#ac239a91075321de19449d54f092ab82a">get</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a10f355c5a55dd7e98d31c2f7e0b590aa">llvm::LoopVectorizationPlanner::getPlanFor</a>, <a href="#a01cda016820d12b73ec4b20254c15481">hasScalarValue</a>, <a href="#a447197675bef200ebccf2b4d5b90ce4c">packScalarIntoVectorValue</a>, <a href="#a85a2c16cba57732c4896af99fd67c0d0">reset</a>, <a href="#af3ac355d8def4b4935de51a9560b44d7">set</a>, <a href="#a96f61745bc423d971ad2369e9175335a">set</a>, <a href="#ae69fb3f4bb10e284f6e2090ff13a7c61">setDebugLocFrom</a> and <a href="#a9ebf82a75f3e15d18aedb2ea43683d4b">VPTransformState</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
