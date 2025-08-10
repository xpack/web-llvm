---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/legalizationartifactcombiner/artifactvaluefinder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ArtifactValueFinder` Class

<p>This class provides utilities for finding source registers of specific bit ranges in an artifact. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LegalizationArtifactCombiner::ArtifactValueFinder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">llvm/CodeGen/GlobalISel/LegalizationArtifactCombiner.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af452509ef47bcb2cae6feec603f566a3">ArtifactValueFinder</a> (MachineRegisterInfo &amp;Mri, MachineIRBuilder &amp;Builder, const LegalizerInfo &amp;Info)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98385033fc4d8cc660c0b3689f3ed51a">findValueFromDef</a> (Register DefReg, unsigned StartBit, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to find a source of the value defined in the def <span class="doxyComputerOutput">DefReg</span>, starting at position <span class="doxyComputerOutput">StartBit</span> with size <span class="doxyComputerOutput">Size</span>. <a href="#a98385033fc4d8cc660c0b3689f3ed51a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90cc54876f57e2f6ee698215c7550ba7">tryCombineUnmergeDefs</a> (GUnmerge &amp;MI, GISelChangeObserver &amp;Observer, SmallVectorImpl&lt; Register &gt; &amp;UpdatedDefs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to combine the defs of an unmerge <span class="doxyComputerOutput">MI</span> by attempting to find values that provides the bits for each def reg. <a href="#a90cc54876f57e2f6ee698215c7550ba7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gunmerge">GUnmerge</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa14e1721c0e785bf1ab1487c9920dc1">findUnmergeThatDefinesReg</a> (Register Reg, unsigned Size, unsigned &amp;DefOperandIdx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93c5d15966feaeebaae62c895be59524">isSequenceFromUnmerge</a> (GMergeLikeInstr &amp;MI, unsigned MergeStartIdx, GUnmerge *Unmerge, unsigned UnmergeIdxStart, unsigned NumElts, unsigned EltSize, bool AllowUndef)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba0755f8db842bb12cb51ef2f3977bac">tryCombineMergeLike</a> (GMergeLikeInstr &amp;MI, SmallVectorImpl&lt; MachineInstr * &gt; &amp;DeadInsts, SmallVectorImpl&lt; Register &gt; &amp;UpdatedDefs, GISelChangeObserver &amp;Observer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3122c26b7d034dc02d41560a1878aa5c">findValueFromConcat</a> (GConcatVectors &amp;Concat, unsigned StartBit, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an concat_vector op <span class="doxyComputerOutput">Concat</span> and a start bit and size, try to find the origin of the value defined by that start position and size. <a href="#a3122c26b7d034dc02d41560a1878aa5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a075a43cb7bd2b624f7d6a7bccc015740">findValueFromBuildVector</a> (GBuildVector &amp;BV, unsigned StartBit, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an build_vector op <span class="doxyComputerOutput">BV</span> and a start bit and size, try to find the origin of the value defined by that start position and size. <a href="#a075a43cb7bd2b624f7d6a7bccc015740">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa62263a99dd72d3d4696fcb9e36b009">findValueFromInsert</a> (MachineInstr &amp;MI, unsigned StartBit, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an G_INSERT op <span class="doxyComputerOutput">MI</span> and a start bit and size, try to find the origin of the value defined by that start position and size. <a href="#afa62263a99dd72d3d4696fcb9e36b009">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a837652d838b43f6d805d545fd58bc2ef">findValueFromExt</a> (MachineInstr &amp;MI, unsigned StartBit, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an G_SEXT, G_ZEXT, G_ANYEXT op <span class="doxyComputerOutput">MI</span> and a start bit and size, try to find the origin of the value defined by that start position and size. <a href="#a837652d838b43f6d805d545fd58bc2ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefab1441ac25c83a0d4c14b6feecbea8">findValueFromTrunc</a> (MachineInstr &amp;MI, unsigned StartBit, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an G_TRUNC op <span class="doxyComputerOutput">MI</span> and a start bit and size, try to find the origin of the value defined by that start position and size. <a href="#aefab1441ac25c83a0d4c14b6feecbea8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af43e98e08271ec604df5b2bd1ede5f7b">findValueFromDefImpl</a> (Register DefReg, unsigned StartBit, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Internal implementation for <a href="#a98385033fc4d8cc660c0b3689f3ed51a">findValueFromDef()</a>. <a href="#af43e98e08271ec604df5b2bd1ede5f7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ae34f5d93266fa4e2ec986f47f940e6">MRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a888220f78ce25c171642369741a6bf40">MIB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo">LegalizerInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaeee381052fcd255570f12e199ce56ab">LI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0852fc86777db8340ca9780cfd5c809f">CurrentBest</a> = <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>()</td>
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

<p>This class provides utilities for finding source registers of specific bit ranges in an artifact.</p>


<p>The routines can look through the source registers if they're other artifacts to try to find a non-artifact source of a value.</p>


<p>Definition at line 610 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ArtifactValueFinder() {#af452509ef47bcb2cae6feec603f566a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LegalizationArtifactCombiner::ArtifactValueFinder::ArtifactValueFinder (<a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; Mri, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; Builder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo">LegalizerInfo</a> &amp; Info)</td>
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



<p>Definition at line 877 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### findUnmergeThatDefinesReg() {#aaa14e1721c0e785bf1ab1487c9920dc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GUnmerge * llvm::LegalizationArtifactCombiner::ArtifactValueFinder::findUnmergeThatDefinesReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, unsigned Size, unsigned &amp; DefOperandIdx)</td>
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



<p>Definition at line 924 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a93c5d15966feaeebaae62c895be59524">isSequenceFromUnmerge</a> and <a href="#aba0755f8db842bb12cb51ef2f3977bac">tryCombineMergeLike</a>.</p>

</div>
</div>

### findValueFromDef() {#a98385033fc4d8cc660c0b3689f3ed51a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::LegalizationArtifactCombiner::ArtifactValueFinder::findValueFromDef (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DefReg, unsigned StartBit, unsigned Size)</td>
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

<p>Try to find a source of the value defined in the def <span class="doxyComputerOutput">DefReg</span>, starting at position <span class="doxyComputerOutput">StartBit</span> with size <span class="doxyComputerOutput">Size</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a register with the requested size, or an empty <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> if no better value could be found.</p></dd>
</dl>


<p>Definition at line 885 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a525b60970cc862aa413d171d805704d4">llvm::LegalizationArtifactCombiner::tryCombineTrunc</a> and <a href="#a90cc54876f57e2f6ee698215c7550ba7">tryCombineUnmergeDefs</a>.</p>

</div>
</div>

### isSequenceFromUnmerge() {#a93c5d15966feaeebaae62c895be59524}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LegalizationArtifactCombiner::ArtifactValueFinder::isSequenceFromUnmerge (<a href="/web-llvm/docs/api/classes/llvm/gmergelikeinstr">GMergeLikeInstr</a> &amp; MI, unsigned MergeStartIdx, <a href="/web-llvm/docs/api/classes/llvm/gunmerge">GUnmerge</a> * Unmerge, unsigned UnmergeIdxStart, unsigned NumElts, unsigned EltSize, bool AllowUndef)</td>
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



<p>Definition at line 939 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aaa14e1721c0e785bf1ab1487c9920dc1">findUnmergeThatDefinesReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#aba0755f8db842bb12cb51ef2f3977bac">tryCombineMergeLike</a>.</p>

</div>
</div>

### tryCombineMergeLike() {#aba0755f8db842bb12cb51ef2f3977bac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LegalizationArtifactCombiner::ArtifactValueFinder::tryCombineMergeLike (<a href="/web-llvm/docs/api/classes/llvm/gmergelikeinstr">GMergeLikeInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; DeadInsts, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; UpdatedDefs, <a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver">GISelChangeObserver</a> &amp; Observer)</td>
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



<p>Definition at line 961 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>


<p>References <a href="#aaa14e1721c0e785bf1ab1487c9920dc1">findUnmergeThatDefinesReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa47ab206f485fe45e4d8a882ff00fd42">llvm::getCoverTy</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="#a93c5d15966feaeebaae62c895be59524">isSequenceFromUnmerge</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a99f0584edf9a13120df821e7f77d9731">llvm::LegalizationArtifactCombiner::replaceRegOrBuildCopy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a3eb465a2b7eef72ebd92bf15445c5903">llvm::LegalizationArtifactCombiner::tryCombineInstruction</a>.</p>

</div>
</div>

### tryCombineUnmergeDefs() {#a90cc54876f57e2f6ee698215c7550ba7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LegalizationArtifactCombiner::ArtifactValueFinder::tryCombineUnmergeDefs (<a href="/web-llvm/docs/api/classes/llvm/gunmerge">GUnmerge</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver">GISelChangeObserver</a> &amp; Observer, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; UpdatedDefs)</td>
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

<p>Try to combine the defs of an unmerge <span class="doxyComputerOutput">MI</span> by attempting to find values that provides the bits for each def reg.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if all the defs of the unmerge have been made dead.</p></dd>
</dl>


<p>Definition at line 895 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a8cfcd92a373cdd7deefb939dd76b83e3">llvm::SmallBitVector::all</a>, <a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver/#a45a05a932f80f51023592ff5131d56a5">llvm::GISelChangeObserver::changedInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver/#a1f637715070a99aa4140444e12697f9a">llvm::GISelChangeObserver::changingInstr</a>, <a href="#a98385033fc4d8cc660c0b3689f3ed51a">findValueFromDef</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a99f0584edf9a13120df821e7f77d9731">llvm::LegalizationArtifactCombiner::replaceRegOrBuildCopy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a9ef6fa1f344222ac170e33582b82c482">llvm::LegalizationArtifactCombiner::tryCombineUnmergeValues</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### findValueFromBuildVector() {#a075a43cb7bd2b624f7d6a7bccc015740}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::LegalizationArtifactCombiner::ArtifactValueFinder::findValueFromBuildVector (<a href="/web-llvm/docs/api/classes/llvm/gbuildvector">GBuildVector</a> &amp; BV, unsigned StartBit, unsigned Size)</td>
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

<p>Given an build_vector op <span class="doxyComputerOutput">BV</span> and a start bit and size, try to find the origin of the value defined by that start position and size.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a register with the requested size, or the current best register found during the current query.</p></dd>
</dl>


<p>Definition at line 655 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>

</div>
</div>

### findValueFromConcat() {#a3122c26b7d034dc02d41560a1878aa5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::LegalizationArtifactCombiner::ArtifactValueFinder::findValueFromConcat (<a href="/web-llvm/docs/api/classes/llvm/gconcatvectors">GConcatVectors</a> &amp; Concat, unsigned StartBit, unsigned Size)</td>
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

<p>Given an concat_vector op <span class="doxyComputerOutput">Concat</span> and a start bit and size, try to find the origin of the value defined by that start position and size.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a register with the requested size, or the current best register found during the current query.</p></dd>
</dl>


<p>Definition at line 623 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>

</div>
</div>

### findValueFromDefImpl() {#af43e98e08271ec604df5b2bd1ede5f7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::LegalizationArtifactCombiner::ArtifactValueFinder::findValueFromDefImpl (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DefReg, unsigned StartBit, unsigned Size)</td>
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

<p>Internal implementation for <a href="#a98385033fc4d8cc660c0b3689f3ed51a">findValueFromDef()</a>.</p>


<p><a href="#a98385033fc4d8cc660c0b3689f3ed51a">findValueFromDef()</a> initializes some data like the CurrentBest register, which this method and its callees rely upon.</p>


<p>Definition at line 828 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>

</div>
</div>

### findValueFromExt() {#a837652d838b43f6d805d545fd58bc2ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::LegalizationArtifactCombiner::ArtifactValueFinder::findValueFromExt (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned StartBit, unsigned Size)</td>
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

<p>Given an G_SEXT, G_ZEXT, G_ANYEXT op <span class="doxyComputerOutput">MI</span> and a start bit and size, try to find the origin of the value defined by that start position and size.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a register with the requested size, or the current best register found during the current query.</p></dd>
</dl>


<p>Definition at line 782 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>

</div>
</div>

### findValueFromInsert() {#afa62263a99dd72d3d4696fcb9e36b009}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::LegalizationArtifactCombiner::ArtifactValueFinder::findValueFromInsert (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned StartBit, unsigned Size)</td>
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

<p>Given an G_INSERT op <span class="doxyComputerOutput">MI</span> and a start bit and size, try to find the origin of the value defined by that start position and size.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a register with the requested size, or the current best register found during the current query.</p></dd>
</dl>


<p>Definition at line 709 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>

</div>
</div>

### findValueFromTrunc() {#aefab1441ac25c83a0d4c14b6feecbea8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::LegalizationArtifactCombiner::ArtifactValueFinder::findValueFromTrunc (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned StartBit, unsigned Size)</td>
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

<p>Given an G_TRUNC op <span class="doxyComputerOutput">MI</span> and a start bit and size, try to find the origin of the value defined by that start position and size.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a register with the requested size, or the current best register found during the current query.</p></dd>
</dl>


<p>Definition at line 810 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CurrentBest {#a0852fc86777db8340ca9780cfd5c809f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::LegalizationArtifactCombiner::ArtifactValueFinder::CurrentBest = <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 616 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>

</div>
</div>

### LI {#aaeee381052fcd255570f12e199ce56ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LegalizerInfo&amp; llvm::LegalizationArtifactCombiner::ArtifactValueFinder::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 613 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>

</div>
</div>

### MIB {#a888220f78ce25c171642369741a6bf40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineIRBuilder&amp; llvm::LegalizationArtifactCombiner::ArtifactValueFinder::MIB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 612 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>

</div>
</div>

### MRI {#a6ae34f5d93266fa4e2ec986f47f940e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo&amp; llvm::LegalizationArtifactCombiner::ArtifactValueFinder::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 611 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
