---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/legalizationartifactcombiner
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LegalizationArtifactCombiner` Class



## Declaration

<div class="doxyDeclaration">
class llvm::LegalizationArtifactCombiner { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">llvm/CodeGen/GlobalISel/LegalizationArtifactCombiner.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03f496f983de483a0dbbecaa5fd6d049">LegalizationArtifactCombiner</a> (MachineIRBuilder &amp;B, MachineRegisterInfo &amp;MRI, const LegalizerInfo &amp;LI, GISelKnownBits *KB=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4696dcc1ada21996da960c711f26ee1">tryCombineAnyExt</a> (MachineInstr &amp;MI, SmallVectorImpl&lt; MachineInstr * &gt; &amp;DeadInsts, SmallVectorImpl&lt; Register &gt; &amp;UpdatedDefs, GISelObserverWrapper &amp;Observer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cff897f0ed479f872425600e0800701">tryCombineZExt</a> (MachineInstr &amp;MI, SmallVectorImpl&lt; MachineInstr * &gt; &amp;DeadInsts, SmallVectorImpl&lt; Register &gt; &amp;UpdatedDefs, GISelObserverWrapper &amp;Observer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ccd1c1459e615587ee51ab55dea54bc">tryCombineSExt</a> (MachineInstr &amp;MI, SmallVectorImpl&lt; MachineInstr * &gt; &amp;DeadInsts, SmallVectorImpl&lt; Register &gt; &amp;UpdatedDefs, GISelObserverWrapper &amp;Observer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a525b60970cc862aa413d171d805704d4">tryCombineTrunc</a> (MachineInstr &amp;MI, SmallVectorImpl&lt; MachineInstr * &gt; &amp;DeadInsts, SmallVectorImpl&lt; Register &gt; &amp;UpdatedDefs, GISelObserverWrapper &amp;Observer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3140a2195ea3bf00ed638bd5a2a13b35">tryFoldImplicitDef</a> (MachineInstr &amp;MI, SmallVectorImpl&lt; MachineInstr * &gt; &amp;DeadInsts, SmallVectorImpl&lt; Register &gt; &amp;UpdatedDefs, GISelObserverWrapper &amp;Observer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to fold G_[ASZ]EXT (G_IMPLICIT_DEF). <a href="#a3140a2195ea3bf00ed638bd5a2a13b35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bc5915736e0e4317a049e55fa502667">tryFoldUnmergeCast</a> (MachineInstr &amp;MI, MachineInstr &amp;CastMI, SmallVectorImpl&lt; MachineInstr * &gt; &amp;DeadInsts, SmallVectorImpl&lt; Register &gt; &amp;UpdatedDefs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ef6fa1f344222ac170e33582b82c482">tryCombineUnmergeValues</a> (GUnmerge &amp;MI, SmallVectorImpl&lt; MachineInstr * &gt; &amp;DeadInsts, SmallVectorImpl&lt; Register &gt; &amp;UpdatedDefs, GISelChangeObserver &amp;Observer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaa5a895e6a8003daae912a9bf636040">tryCombineExtract</a> (MachineInstr &amp;MI, SmallVectorImpl&lt; MachineInstr * &gt; &amp;DeadInsts, SmallVectorImpl&lt; Register &gt; &amp;UpdatedDefs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3eb465a2b7eef72ebd92bf15445c5903">tryCombineInstruction</a> (MachineInstr &amp;MI, SmallVectorImpl&lt; MachineInstr * &gt; &amp;DeadInsts, GISelObserverWrapper &amp;WrapperObserver)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to combine away MI. <a href="#a3eb465a2b7eef72ebd92bf15445c5903">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af17518f3afc618ea647254083ea96570">markDefDead</a> (MachineInstr &amp;MI, MachineInstr &amp;DefMI, SmallVectorImpl&lt; MachineInstr * &gt; &amp;DeadInsts, unsigned DefIdx=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark a def of one of MI's original operands, DefMI, as dead if changing MI (either by killing it or changing operands) results in DefMI being dead too. <a href="#af17518f3afc618ea647254083ea96570">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bbd60c8700c24ef664169510f2f2179">markInstAndDefDead</a> (MachineInstr &amp;MI, MachineInstr &amp;DefMI, SmallVectorImpl&lt; MachineInstr * &gt; &amp;DeadInsts, unsigned DefIdx=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark MI as dead. <a href="#a7bbd60c8700c24ef664169510f2f2179">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d17dedd924eed66e10933d33fa7d081">deleteMarkedDeadInsts</a> (SmallVectorImpl&lt; MachineInstr * &gt; &amp;DeadInsts, GISelObserverWrapper &amp;WrapperObserver)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erase the dead instructions in the list and call the observer hooks. <a href="#a0d17dedd924eed66e10933d33fa7d081">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acceb0ec23b77795db55a5b885dcb2526">isInstUnsupported</a> (const LegalityQuery &amp;Query) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the target legalizer info has specified anything about the instruction, or if unsupported. <a href="#acceb0ec23b77795db55a5b885dcb2526">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a788191f0672d3f7fc6f933bbcbe40989">isInstLegal</a> (const LegalityQuery &amp;Query) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93332a95b33f22a013925196bd32ca63">isConstantUnsupported</a> (LLT Ty) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a308d3b1ca60f948dcb6368307eb15b5b">lookThroughCopyInstrs</a> (Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Looks through copy instructions and returns the actual source register. <a href="#a308d3b1ca60f948dcb6368307eb15b5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71c9784647274be3a91aed025e51e017">Builder</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac329f4a7750840b7ec79bf66b582256b">MRI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a677f3e590a6b218a45a187449870c765">LI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/giselknownbits">GISelKnownBits</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b250e7d00ea2f42fa907853c772fcf4">KB</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79837ead25e5a97d27a176df66809a5b">canFoldMergeOpcode</a> (unsigned MergeOp, unsigned ConvertOp, LLT OpTy, LLT DestTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99f0584edf9a13120df821e7f77d9731">replaceRegOrBuildCopy</a> (Register DstReg, Register SrcReg, MachineRegisterInfo &amp;MRI, MachineIRBuilder &amp;Builder, SmallVectorImpl&lt; Register &gt; &amp;UpdatedDefs, GISelChangeObserver &amp;Observer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to replace DstReg with SrcReg or build a COPY instruction depending on the register constraints. <a href="#a99f0584edf9a13120df821e7f77d9731">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96102361800d3246d34875817532b3a8">getDefIndex</a> (const MachineInstr &amp;MI, Register SearchDef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the operand index in <span class="doxyComputerOutput">MI</span> that defines <span class="doxyComputerOutput">Def</span>. <a href="#a96102361800d3246d34875817532b3a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a459a8d683931bba6671985772f5d7dba">isArtifactCast</a> (unsigned Opc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a010771f5f5f2de8e4efdbd310ffb6178">getArtifactSrcReg</a> (const MachineInstr &amp;MI)</td>
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


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LegalizationArtifactCombiner() {#a03f496f983de483a0dbbecaa5fd6d049}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LegalizationArtifactCombiner::LegalizationArtifactCombiner (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo">LegalizerInfo</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits">GISelKnownBits</a> * KB=nullptr)</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### tryCombineAnyExt() {#af4696dcc1ada21996da960c711f26ee1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LegalizationArtifactCombiner::tryCombineAnyExt (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; DeadInsts, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; UpdatedDefs, <a href="/web-llvm/docs/api/classes/llvm/giselobserverwrapper">GISelObserverWrapper</a> &amp; Observer)</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocation/#a78cc51c415c7e64b5efe2c8458fbd35a">llvm::DILocation::getMergedLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ad168e9806711429475c916e9b0d521c1">llvm::MIPatternMatch::m_all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#abb0025cff9b34811f8ce06ff14d4702c">llvm::MIPatternMatch::m_any_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ad93cf713aceed1711ddd0ccbe62c8277">llvm::MIPatternMatch::m_GAnyExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a32dcb8cba57833770e79dfe2fd395b49">llvm::MIPatternMatch::m_GSExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aeaad33cb0fd8ffab79aab1414253854d">llvm::MIPatternMatch::m_GTrunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a2e06342dcfb65c2c40e4121eb688d4df">llvm::MIPatternMatch::m_GZExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ac48bb7526cd273b2dbeaabdc481d641f">llvm::MIPatternMatch::m_MInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a00b04b7613c62a52917e1d2467faeab0">llvm::MIPatternMatch::m_Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a99f0584edf9a13120df821e7f77d9731">replaceRegOrBuildCopy</a> and <a href="#a3140a2195ea3bf00ed638bd5a2a13b35">tryFoldImplicitDef</a>.</p>


<p>Referenced by <a href="#a3eb465a2b7eef72ebd92bf15445c5903">tryCombineInstruction</a>.</p>

</div>
</div>

### tryCombineExtract() {#aaaa5a895e6a8003daae912a9bf636040}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LegalizationArtifactCombiner::tryCombineExtract (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; DeadInsts, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; UpdatedDefs)</td>
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



<p>Definition at line 1269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a432824f0975bb863478bf4ef3a5df258">llvm::MachineInstr::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#a3eb465a2b7eef72ebd92bf15445c5903">tryCombineInstruction</a>.</p>

</div>
</div>

### tryCombineInstruction() {#a3eb465a2b7eef72ebd92bf15445c5903}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LegalizationArtifactCombiner::tryCombineInstruction (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; DeadInsts, <a href="/web-llvm/docs/api/classes/llvm/giselobserverwrapper">GISelObserverWrapper</a> &amp; WrapperObserver)</td>
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

<p>Try to combine away MI.</p>


<p>Returns true if it combined away the MI. Adds instructions that are dead as a result of the combine into DeadInsts, which can include MI.</p>


<p>Definition at line 1322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/giselobserverwrapper/#a45e6c5136bf69d404a0e16018368641f">llvm::GISelObserverWrapper::changedInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#af4696dcc1ada21996da960c711f26ee1">tryCombineAnyExt</a>, <a href="#aaaa5a895e6a8003daae912a9bf636040">tryCombineExtract</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/artifactvaluefinder/#aba0755f8db842bb12cb51ef2f3977bac">llvm::LegalizationArtifactCombiner::ArtifactValueFinder::tryCombineMergeLike</a>, <a href="#a5ccd1c1459e615587ee51ab55dea54bc">tryCombineSExt</a>, <a href="#a525b60970cc862aa413d171d805704d4">tryCombineTrunc</a>, <a href="#a9ef6fa1f344222ac170e33582b82c482">tryCombineUnmergeValues</a> and <a href="#a3cff897f0ed479f872425600e0800701">tryCombineZExt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizer/#a80314c2b261b78cb7335a265f43ba1b5">llvm::Legalizer::legalizeMachineFunction</a>.</p>

</div>
</div>

### tryCombineSExt() {#a5ccd1c1459e615587ee51ab55dea54bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LegalizationArtifactCombiner::tryCombineSExt (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; DeadInsts, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; UpdatedDefs, <a href="/web-llvm/docs/api/classes/llvm/giselobserverwrapper">GISelObserverWrapper</a> &amp; Observer)</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ad168e9806711429475c916e9b0d521c1">llvm::MIPatternMatch::m_all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#abb0025cff9b34811f8ce06ff14d4702c">llvm::MIPatternMatch::m_any_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a32dcb8cba57833770e79dfe2fd395b49">llvm::MIPatternMatch::m_GSExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aeaad33cb0fd8ffab79aab1414253854d">llvm::MIPatternMatch::m_GTrunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a2e06342dcfb65c2c40e4121eb688d4df">llvm::MIPatternMatch::m_GZExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ac48bb7526cd273b2dbeaabdc481d641f">llvm::MIPatternMatch::m_MInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a00b04b7613c62a52917e1d2467faeab0">llvm::MIPatternMatch::m_Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a99f0584edf9a13120df821e7f77d9731">replaceRegOrBuildCopy</a> and <a href="#a3140a2195ea3bf00ed638bd5a2a13b35">tryFoldImplicitDef</a>.</p>


<p>Referenced by <a href="#a3eb465a2b7eef72ebd92bf15445c5903">tryCombineInstruction</a>.</p>

</div>
</div>

### tryCombineTrunc() {#a525b60970cc862aa413d171d805704d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LegalizationArtifactCombiner::tryCombineTrunc (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; DeadInsts, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; UpdatedDefs, <a href="/web-llvm/docs/api/classes/llvm/giselobserverwrapper">GISelObserverWrapper</a> &amp; Observer)</td>
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



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/artifactvaluefinder/#a98385033fc4d8cc660c0b3689f3ed51a">llvm::LegalizationArtifactCombiner::ArtifactValueFinder::findValueFromDef</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aeaad33cb0fd8ffab79aab1414253854d">llvm::MIPatternMatch::m_GTrunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a00b04b7613c62a52917e1d2467faeab0">llvm::MIPatternMatch::m_Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#a99f0584edf9a13120df821e7f77d9731">replaceRegOrBuildCopy</a>.</p>


<p>Referenced by <a href="#a3eb465a2b7eef72ebd92bf15445c5903">tryCombineInstruction</a>.</p>

</div>
</div>

### tryCombineUnmergeValues() {#a9ef6fa1f344222ac170e33582b82c482}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LegalizationArtifactCombiner::tryCombineUnmergeValues (<a href="/web-llvm/docs/api/classes/llvm/gunmerge">GUnmerge</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; DeadInsts, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; UpdatedDefs, <a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver">GISelChangeObserver</a> &amp; Observer)</td>
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



<p>Definition at line 1061 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/legalizeactionstep/#a1ad3bef7dbfe7e650af077cede882b93">llvm::LegalizeActionStep::Action</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654a123b973f813232425a88cae2ef685a5a">llvm::LegalizeActions::FewerElements</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4b2430ab5e686b82f8cd6fd588d6de6f">llvm::getDefIgnoringCopies</a>, <a href="#a96102361800d3246d34875817532b3a8">getDefIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654a167074ba3b742859ff5dbe464381e107">llvm::LegalizeActions::Legal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654a5ff0dbefe0555c538e207b9ee20e26cf">llvm::LegalizeActions::Lower</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654ad0868c394d6503253b0d29c7e383e78b">llvm::LegalizeActions::NarrowScalar</a>, <a href="#a99f0584edf9a13120df821e7f77d9731">replaceRegOrBuildCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/artifactvaluefinder/#a90cc54876f57e2f6ee698215c7550ba7">llvm::LegalizationArtifactCombiner::ArtifactValueFinder::tryCombineUnmergeDefs</a>, <a href="/web-llvm/docs/api/structs/llvm/legalizeactionstep/#aafa2d5d36d517a05b8f11d2c96a86de7">llvm::LegalizeActionStep::TypeIdx</a> and <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654a47383e4f532d33bd4f45d182896d7c17">llvm::LegalizeActions::Unsupported</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsregisterbankinfo-cpp/#aa3f4b8913b938fe26940a3ee727e4244">combineAwayG_UNMERGE_VALUES</a> and <a href="#a3eb465a2b7eef72ebd92bf15445c5903">tryCombineInstruction</a>.</p>

</div>
</div>

### tryCombineZExt() {#a3cff897f0ed479f872425600e0800701}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LegalizationArtifactCombiner::tryCombineZExt (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; DeadInsts, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; UpdatedDefs, <a href="/web-llvm/docs/api/classes/llvm/giselobserverwrapper">GISelObserverWrapper</a> &amp; Observer)</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/giselobserverwrapper/#a45e6c5136bf69d404a0e16018368641f">llvm::GISelObserverWrapper::changedInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/giselobserverwrapper/#a6794cc3c5eb81ee2b2330f78ccb6f335">llvm::GISelObserverWrapper::changingInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a071e8d814b2b30b02544fad964227b8e">llvm::APInt::getAllOnes</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a32dcb8cba57833770e79dfe2fd395b49">llvm::MIPatternMatch::m_GSExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aeaad33cb0fd8ffab79aab1414253854d">llvm::MIPatternMatch::m_GTrunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a2e06342dcfb65c2c40e4121eb688d4df">llvm::MIPatternMatch::m_GZExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a00b04b7613c62a52917e1d2467faeab0">llvm::MIPatternMatch::m_Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a99f0584edf9a13120df821e7f77d9731">replaceRegOrBuildCopy</a>, <a href="#a3140a2195ea3bf00ed638bd5a2a13b35">tryFoldImplicitDef</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a1dc76cc8bf703e6ada68bededcbb9573">llvm::APInt::zext</a>.</p>


<p>Referenced by <a href="#a3eb465a2b7eef72ebd92bf15445c5903">tryCombineInstruction</a>.</p>

</div>
</div>

### tryFoldImplicitDef() {#a3140a2195ea3bf00ed638bd5a2a13b35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LegalizationArtifactCombiner::tryFoldImplicitDef (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; DeadInsts, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; UpdatedDefs, <a href="/web-llvm/docs/api/classes/llvm/giselobserverwrapper">GISelObserverWrapper</a> &amp; Observer)</td>
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

<p>Try to fold G_[ASZ]EXT (G_IMPLICIT_DEF).</p>

<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0edf31d256ecb3ac003bf2d81a576c9e">llvm::getOpcodeDef</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#a99f0584edf9a13120df821e7f77d9731">replaceRegOrBuildCopy</a>.</p>


<p>Referenced by <a href="#af4696dcc1ada21996da960c711f26ee1">tryCombineAnyExt</a>, <a href="#a5ccd1c1459e615587ee51ab55dea54bc">tryCombineSExt</a> and <a href="#a3cff897f0ed479f872425600e0800701">tryCombineZExt</a>.</p>

</div>
</div>

### tryFoldUnmergeCast() {#a1bc5915736e0e4317a049e55fa502667}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LegalizationArtifactCombiner::tryFoldUnmergeCast (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; CastMI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; DeadInsts, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; UpdatedDefs)</td>
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



<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#adabd45e67a1847750a117317b5ef8f9f">llvm::LLT::changeElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae4165ca7bcbee300d5e9c065adcc1415">llvm::LLT::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654af7c712e88ef2300e4bc43089d1cdf3e5">llvm::LegalizeActions::MoreElements</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### deleteMarkedDeadInsts() {#a0d17dedd924eed66e10933d33fa7d081}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LegalizationArtifactCombiner::deleteMarkedDeadInsts (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; DeadInsts, <a href="/web-llvm/docs/api/classes/llvm/giselobserverwrapper">GISelObserverWrapper</a> &amp; WrapperObserver)</td>
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

<p>Erase the dead instructions in the list and call the observer hooks.</p>


<p>Normally the <a href="/web-llvm/docs/api/classes/llvm/legalizer">Legalizer</a> will deal with erasing instructions that have been marked dead. However, for the trunc(ext(x)) cases we can end up trying to process instructions which have been marked dead, but otherwise break the MIR by introducing multiple vreg defs. For those cases, allow the combines to explicitly delete the instructions before we run into trouble.</p>


<p>Definition at line 1520 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>

</div>
</div>

### isConstantUnsupported() {#a93332a95b33f22a013925196bd32ca63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LegalizationArtifactCombiner::isConstantUnsupported (<a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
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



<p>Definition at line 1542 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>

</div>
</div>

### isInstLegal() {#a788191f0672d3f7fc6f933bbcbe40989}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LegalizationArtifactCombiner::isInstLegal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/legalityquery">LegalityQuery</a> &amp; Query)</td>
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



<p>Definition at line 1538 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>

</div>
</div>

### isInstUnsupported() {#acceb0ec23b77795db55a5b885dcb2526}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LegalizationArtifactCombiner::isInstUnsupported (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/legalityquery">LegalityQuery</a> &amp; Query)</td>
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

<p>Checks if the target legalizer info has specified anything about the instruction, or if unsupported.</p>

<p>Definition at line 1532 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>

</div>
</div>

### lookThroughCopyInstrs() {#a308d3b1ca60f948dcb6368307eb15b5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::LegalizationArtifactCombiner::lookThroughCopyInstrs (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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

<p>Looks through copy instructions and returns the actual source register.</p>

<p>Definition at line 1553 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>

</div>
</div>

### markDefDead() {#af17518f3afc618ea647254083ea96570}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LegalizationArtifactCombiner::markDefDead (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; DefMI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; DeadInsts, unsigned DefIdx=0)</td>
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

<p>Mark a def of one of MI's original operands, DefMI, as dead if changing MI (either by killing it or changing operands) results in DefMI being dead too.</p>


<p>In-between COPYs or artifact-casts are also collected if they are dead. MI is not marked dead.</p>


<p>Definition at line 1449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>

</div>
</div>

### markInstAndDefDead() {#a7bbd60c8700c24ef664169510f2f2179}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LegalizationArtifactCombiner::markInstAndDefDead (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; DefMI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; DeadInsts, unsigned DefIdx=0)</td>
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

<p>Mark MI as dead.</p>


<p>If a def of one of MI's operands, DefMI, would also be dead due to MI being killed, then mark DefMI as dead too. Some of the combines (extends(trunc)), try to walk through redundant copies in between the extends and the truncs, and this attempts to collect the in between copies if they're dead.</p>


<p>Definition at line 1507 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Builder {#a71c9784647274be3a91aed025e51e017}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineIRBuilder&amp; llvm::LegalizationArtifactCombiner::Builder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>

</div>
</div>

### KB {#a1b250e7d00ea2f42fa907853c772fcf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GISelKnownBits* llvm::LegalizationArtifactCombiner::KB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>

</div>
</div>

### LI {#a677f3e590a6b218a45a187449870c765}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LegalizerInfo&amp; llvm::LegalizationArtifactCombiner::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>

</div>
</div>

### MRI {#ac329f4a7750840b7ec79bf66b582256b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo&amp; llvm::LegalizationArtifactCombiner::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### canFoldMergeOpcode() {#a79837ead25e5a97d27a176df66809a5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LegalizationArtifactCombiner::canFoldMergeOpcode (unsigned MergeOp, unsigned ConvertOp, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> OpTy, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> DestTy)</td>
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



<p>Definition at line 516 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>.</p>

</div>
</div>

### getDefIndex() {#a96102361800d3246d34875817532b3a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LegalizationArtifactCombiner::getDefIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SearchDef)</td>
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

<p>Return the operand index in <span class="doxyComputerOutput">MI</span> that defines <span class="doxyComputerOutput">Def</span>.</p>

<p>Definition at line 595 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a9ef6fa1f344222ac170e33582b82c482">tryCombineUnmergeValues</a>.</p>

</div>
</div>

### replaceRegOrBuildCopy() {#a99f0584edf9a13120df821e7f77d9731}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LegalizationArtifactCombiner::replaceRegOrBuildCopy (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DstReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SrcReg, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; UpdatedDefs, <a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver">GISelChangeObserver</a> &amp; Observer)</td>
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

<p>Try to replace DstReg with SrcReg or build a COPY instruction depending on the register constraints.</p>

<p>Definition at line 570 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a708b9606a37961be41adad607c81c532">llvm::canReplaceReg</a>, <a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver/#a45a05a932f80f51023592ff5131d56a5">llvm::GISelChangeObserver::changedInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver/#a1f637715070a99aa4140444e12697f9a">llvm::GISelChangeObserver::changingInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>.</p>


<p>Referenced by <a href="#af4696dcc1ada21996da960c711f26ee1">tryCombineAnyExt</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/artifactvaluefinder/#aba0755f8db842bb12cb51ef2f3977bac">llvm::LegalizationArtifactCombiner::ArtifactValueFinder::tryCombineMergeLike</a>, <a href="#a5ccd1c1459e615587ee51ab55dea54bc">tryCombineSExt</a>, <a href="#a525b60970cc862aa413d171d805704d4">tryCombineTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/artifactvaluefinder/#a90cc54876f57e2f6ee698215c7550ba7">llvm::LegalizationArtifactCombiner::ArtifactValueFinder::tryCombineUnmergeDefs</a>, <a href="#a9ef6fa1f344222ac170e33582b82c482">tryCombineUnmergeValues</a>, <a href="#a3cff897f0ed479f872425600e0800701">tryCombineZExt</a> and <a href="#a3140a2195ea3bf00ed638bd5a2a13b35">tryFoldImplicitDef</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getArtifactSrcReg() {#a010771f5f5f2de8e4efdbd310ffb6178}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::LegalizationArtifactCombiner::getArtifactSrcReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 1425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>

</div>
</div>

### isArtifactCast() {#a459a8d683931bba6671985772f5d7dba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LegalizationArtifactCombiner::isArtifactCast (unsigned Opc)</td>
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



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">LegalizationArtifactCombiner.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
