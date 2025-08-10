---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/csemirbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CSEMIRBuilder` Class

<p>Defines a builder that does CSE of MachineInstructions using <a href="/web-llvm/docs/api/classes/llvm/giselcseinfo">GISelCSEInfo</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::CSEMIRBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/csemirbuilder-h">llvm/CodeGen/GlobalISel/CSEMIRBuilder.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper class to build <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>. <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c2e15b867893ec15cb49acfbb38e542">buildInstr</a> (unsigned Opc, ArrayRef&lt; DstOp &gt; DstOps, ArrayRef&lt; SrcOp &gt; SrcOps, std::optional&lt; unsigned &gt; Flag=std::nullopt) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af20c06f6ef57cddf624f531efbaf69e7">buildConstant</a> (const DstOp &amp;Res, const ConstantInt &amp;Val) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_CONSTANT <span class="doxyComputerOutput">Val</span>. <a href="#af20c06f6ef57cddf624f531efbaf69e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1fe7f5085d203a5984b2450f907b239">buildFConstant</a> (const DstOp &amp;Res, const ConstantFP &amp;Val) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FCONSTANT <span class="doxyComputerOutput">Val</span>. <a href="#ae1fe7f5085d203a5984b2450f907b239">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad662a74c60eeb99f6a24927479eda063">MachineIRBuilder</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Some constructors for easy use. <a href="#ad662a74c60eeb99f6a24927479eda063">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa03c7e0eb5346e000177cb95b910cc71">MachineIRBuilder</a> (MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6149c9a2642b91bfdb471868a7f8bd1f">MachineIRBuilder</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator InsPt)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d5d8e859928cc003454a2ba18372a71">MachineIRBuilder</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d69fb9fe28f38bfe61a276caec92263">MachineIRBuilder</a> (MachineInstr &amp;MI, GISelChangeObserver &amp;Observer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa048045615f06db86c3a4e317ed3a2b3">MachineIRBuilder</a> (const MachineIRBuilderState &amp;BState)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdce4b9880a0aed02fe487da6a613cbd">buildConstant</a> (const DstOp &amp;Res, int64_t Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_CONSTANT <span class="doxyComputerOutput">Val</span>. <a href="#afdce4b9880a0aed02fe487da6a613cbd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab952b8b71fdba5baaf6a083e06d71da2">buildConstant</a> (const DstOp &amp;Res, const APInt &amp;Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4265ff404073d12b765bc9fee4e7f186">buildFConstant</a> (const DstOp &amp;Res, double Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa28f164b227803f0fef41094366c2dca">buildFConstant</a> (const DstOp &amp;Res, const APFloat &amp;Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab53292a8500fa16004af814a68e277fb">dominates</a> (MachineBasicBlock::const_iterator A, MachineBasicBlock::const_iterator B) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if A dominates B (within the same basic block). <a href="#ab53292a8500fa16004af814a68e277fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bce118c21f6190369af1a308b734807">getDominatingInstrForID</a> (FoldingSetNodeID &amp;ID, void *&amp;NodeInsertPos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For given <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, find a machineinstr in the CSE Map. <a href="#a6bce118c21f6190369af1a308b734807">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6e8209ef4c337a011476b902bd799cc">canPerformCSEForOpc</a> (unsigned Opc) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Simple check if we can CSE (we have the CSEInfo) or if this Opcode is safe to CSE. <a href="#ae6e8209ef4c337a011476b902bd799cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a665403895fbe470c1252de4819d00f04">profileDstOp</a> (const DstOp &amp;Op, GISelInstProfileBuilder &amp;B) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9dea911a6daa75a4db7e113076bef58">profileDstOps</a> (ArrayRef&lt; DstOp &gt; Ops, GISelInstProfileBuilder &amp;B) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac091b02ba9259014e18c883b2b829d92">profileSrcOp</a> (const SrcOp &amp;Op, GISelInstProfileBuilder &amp;B) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a599a4fcb5249b1c6c96ad7a6800bb4c1">profileSrcOps</a> (ArrayRef&lt; SrcOp &gt; Ops, GISelInstProfileBuilder &amp;B) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39e86102e53060a9daabe3fbeb4e27f3">profileMBBOpcode</a> (GISelInstProfileBuilder &amp;B, unsigned Opc) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7619bee4a86d2909d5861716198eb23">profileEverything</a> (unsigned Opc, ArrayRef&lt; DstOp &gt; DstOps, ArrayRef&lt; SrcOp &gt; SrcOps, std::optional&lt; unsigned &gt; Flags, GISelInstProfileBuilder &amp;B) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20ecb12f5d22d71cd40f9e3ea6553296">memoizeMI</a> (MachineInstrBuilder MIB, void *NodeInsertPos)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d23c2aafd35499e6ab41c13cb8c9523">generateCopiesIfRequired</a> (ArrayRef&lt; DstOp &gt; DstOps, MachineInstrBuilder &amp;MIB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17236385c665da0dbf18b5ab098bb58e">checkCopyToDefsPossible</a> (ArrayRef&lt; DstOp &gt; DstOps)</td>
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

<p>Defines a builder that does CSE of MachineInstructions using <a href="/web-llvm/docs/api/classes/llvm/giselcseinfo">GISelCSEInfo</a>.</p>


<p>Eg usage.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">GISelCSEInfo *<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a> =</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    &amp;getAnalysis&lt;GISelCSEAnalysisWrapperPass&gt;().getCSEInfo();</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">CSEMIRBuilder CB(Builder.getState());</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">CB.setCSEInfo(<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> = CB.buildConstant(s32, 42);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> = CB.buildConstant(s32, 42);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>(<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> == <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> CReg = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.createGenericVirtualRegister(s32);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">C</a> = CB.buildConstant(CReg, 42);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>(<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">C</a>-&gt;getOpcode() == TargetOpcode::COPY);</span></span></div>

</div>


<p>Explicitly passing in a register would materialize a copy if possible. <a href="/web-llvm/docs/api/classes/llvm/csemirbuilder">CSEMIRBuilder</a> also does trivial constant folding for binary ops.</p>


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/csemirbuilder-h">CSEMIRBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### buildConstant() {#af20c06f6ef57cddf624f531efbaf69e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder CSEMIRBuilder::buildConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> &amp; Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_CONSTANT <span class="doxyComputerOutput">Val</span>.</p>


<p>G_CONSTANT is an integer constant with the specified size and value. <span class="doxyComputerOutput">Val</span> will be extended or truncated to the size of <span class="doxyComputerOutput">Reg</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register with scalar or pointer type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The newly created instruction.</p></dd>
</dl>


<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/csemirbuilder-h">CSEMIRBuilder.h</a>, definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/csemirbuilder-cpp">CSEMIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/giselinstprofilebuilder/#af6e18ff9d3e123fa8f958b846796e531">llvm::GISelInstProfileBuilder::addNodeIDMachineOperand</a>, <a href="#af20c06f6ef57cddf624f531efbaf69e7">buildConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#af751c28a69e1d07e19dad11e4e26a70d">llvm::MachineIRBuilder::buildConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a55bde2ba6aacac745a29a7e50c6be007">llvm::MachineIRBuilder::buildSplatBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a5e7a07b4efeaec2afcb83a6551b38441">llvm::MachineOperand::CreateCImm</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a49a5649c0de9dee3dacbab3019872923">llvm::DstOp::getLLTTy</a> and <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ad7322f56c0659b8dc8e55567767b74d6">llvm::MachineIRBuilder::getMRI</a>.</p>


<p>Referenced by <a href="#af20c06f6ef57cddf624f531efbaf69e7">buildConstant</a> and <a href="#a9c2e15b867893ec15cb49acfbb38e542">buildInstr</a>.</p>

</div>
</div>

### buildConstant() {#afdce4b9880a0aed02fe487da6a613cbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, int64_t Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_CONSTANT <span class="doxyComputerOutput">Val</span>.</p>


<p>G_CONSTANT is an integer constant with the specified size and value.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register with scalar type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The newly created instruction.</p></dd>
</dl>


<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/csemirbuilder-h">CSEMIRBuilder.h</a>, definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>

</div>
</div>

### buildConstant() {#ab952b8b71fdba5baaf6a083e06d71da2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/csemirbuilder-h">CSEMIRBuilder.h</a>, definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>

</div>
</div>

### buildFConstant() {#ae1fe7f5085d203a5984b2450f907b239}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder CSEMIRBuilder::buildFConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantfp">ConstantFP</a> &amp; Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build and insert <span class="doxyComputerOutput">Res</span> = G_FCONSTANT <span class="doxyComputerOutput">Val</span>.</p>


<p>G_FCONSTANT is a floating-point constant with the specified size and value.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>setBasicBlock or setMI must have been called.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">Res</span> must be a generic virtual register with scalar type.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The newly created instruction.</p></dd>
</dl>


<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/csemirbuilder-h">CSEMIRBuilder.h</a>, definition at line 361 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/csemirbuilder-cpp">CSEMIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/giselinstprofilebuilder/#af6e18ff9d3e123fa8f958b846796e531">llvm::GISelInstProfileBuilder::addNodeIDMachineOperand</a>, <a href="#ae1fe7f5085d203a5984b2450f907b239">buildFConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a81a7959d3e7f624343ecdf6905e251dd">llvm::MachineIRBuilder::buildFConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a55bde2ba6aacac745a29a7e50c6be007">llvm::MachineIRBuilder::buildSplatBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a2cd605d7476194cf38e7ef6d2c57391a">llvm::MachineOperand::CreateFPImm</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a49a5649c0de9dee3dacbab3019872923">llvm::DstOp::getLLTTy</a> and <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ad7322f56c0659b8dc8e55567767b74d6">llvm::MachineIRBuilder::getMRI</a>.</p>


<p>Referenced by <a href="#ae1fe7f5085d203a5984b2450f907b239">buildFConstant</a> and <a href="#a9c2e15b867893ec15cb49acfbb38e542">buildInstr</a>.</p>

</div>
</div>

### buildFConstant() {#a4265ff404073d12b765bc9fee4e7f186}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildFConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, double Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/csemirbuilder-h">CSEMIRBuilder.h</a>, definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>

</div>
</div>

### buildFConstant() {#aa28f164b227803f0fef41094366c2dca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineIRBuilder::buildFConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/csemirbuilder-h">CSEMIRBuilder.h</a>, definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a>.</p>

</div>
</div>

### buildInstr() {#a9c2e15b867893ec15cb49acfbb38e542}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder CSEMIRBuilder::buildInstr (unsigned Opc, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &gt; DstOps, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &gt; SrcOps, std::optional&lt; unsigned &gt; Flag=std::nullopt)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/csemirbuilder-h">CSEMIRBuilder.h</a>, definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/csemirbuilder-cpp">CSEMIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a60609bd46d38414e2c9e2334f9740727">llvm::MachineIRBuilder::buildBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a96b7ed72c9782cd69b2b9b341cf73112">llvm::MachineIRBuilder::buildBuildVectorConstant</a>, <a href="#af20c06f6ef57cddf624f531efbaf69e7">buildConstant</a>, <a href="#ae1fe7f5085d203a5984b2450f907b239">buildFConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a8bc92b8a902afb7675480ecc729a66d4">llvm::MachineIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59a7ed1e5bfd8f5d0c66a7346ee5f87b">llvm::ConstantFoldBinOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3442c3f5bc7a9a528d36fcedf116b19c">llvm::ConstantFoldCountZeros</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3692c4606635fb9fb9391257b422c761">llvm::ConstantFoldExtOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2664741ca8fa0d154ef9e738aef0db7b">llvm::ConstantFoldFPBinOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a840d23b9684bb12aa8254d66bcbd3cce">llvm::ConstantFoldICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1aef656147029ec93dabe8abf51806b6">llvm::ConstantFoldIntToFloat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a904cc16cfe269559a2ff1cc7f06df6d5">llvm::ConstantFoldVectorBinop</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a721fc555cb3d8dc2a1a680dcc2ce69b2">llvm::ArrayRef&lt; T &gt;::front</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a2a885e28d6a7936c7442d063aea666f6">llvm::MachineIRBuilder::getCSEInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#aeb6d0a9254bc3183046873436fc7c12e">llvm::MachineIRBuilder::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#a9370c0de85c12bd0062063b7fcbc64ed">llvm::SrcOp::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ad7322f56c0659b8dc8e55567767b74d6">llvm::MachineIRBuilder::getMRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a1c5fadb14ff1d77faad0cb58a43252ab">llvm::MachineInstrBuilder::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#ae229785d0c8a8ce25d34be18fe150a54">llvm::SrcOp::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae4165ca7bcbee300d5e9c065adcc1415">llvm::LLT::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/giselcseinfo/#a8e8e16efa8d6ea664212d5d10d4a2141">llvm::GISelCSEInfo::handleRemoveInst</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### MachineIRBuilder() {#ad662a74c60eeb99f6a24927479eda063}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineIRBuilder::MachineIRBuilder ()</td>
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

<p>Some constructors for easy use.</p>

<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/csemirbuilder-h">CSEMIRBuilder.h</a>.</p>

</div>
</div>

### MachineIRBuilder() {#aa03c7e0eb5346e000177cb95b910cc71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineIRBuilder::MachineIRBuilder (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/csemirbuilder-h">CSEMIRBuilder.h</a>, definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>

</div>
</div>

### MachineIRBuilder() {#a6149c9a2642b91bfdb471868a7f8bd1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineIRBuilder::MachineIRBuilder (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> InsPt)</td>
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



<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/csemirbuilder-h">CSEMIRBuilder.h</a>, definition at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>

</div>
</div>

### MachineIRBuilder() {#a7d5d8e859928cc003454a2ba18372a71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineIRBuilder::MachineIRBuilder (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/csemirbuilder-h">CSEMIRBuilder.h</a>, definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>

</div>
</div>

### MachineIRBuilder() {#a8d69fb9fe28f38bfe61a276caec92263}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineIRBuilder::MachineIRBuilder (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver">GISelChangeObserver</a> &amp; Observer)</td>
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



<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/csemirbuilder-h">CSEMIRBuilder.h</a>, definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>

</div>
</div>

### MachineIRBuilder() {#aa048045615f06db86c3a4e317ed3a2b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineIRBuilder::MachineIRBuilder (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machineirbuilderstate">MachineIRBuilderState</a> &amp; BState)</td>
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



<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/csemirbuilder-h">CSEMIRBuilder.h</a>, definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### canPerformCSEForOpc() {#ae6e8209ef4c337a011476b902bd799cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CSEMIRBuilder::canPerformCSEForOpc (unsigned Opc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Simple check if we can CSE (we have the CSEInfo) or if this Opcode is safe to CSE.</p>

<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/csemirbuilder-h">CSEMIRBuilder.h</a>, definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/csemirbuilder-cpp">CSEMIRBuilder.cpp</a>.</p>

</div>
</div>

### checkCopyToDefsPossible() {#a17236385c665da0dbf18b5ab098bb58e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CSEMIRBuilder::checkCopyToDefsPossible (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &gt; DstOps)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/csemirbuilder-h">CSEMIRBuilder.h</a>, definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/csemirbuilder-cpp">CSEMIRBuilder.cpp</a>.</p>

</div>
</div>

### dominates() {#ab53292a8500fa16004af814a68e277fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CSEMIRBuilder::dominates (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a199a6e4bfdffc8f3379ef4f35004488f">MachineBasicBlock::const_iterator</a> A, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a199a6e4bfdffc8f3379ef4f35004488f">MachineBasicBlock::const_iterator</a> B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if A dominates B (within the same basic block).</p>


<p>Both iterators must be in the same basic block.</p>


<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/csemirbuilder-h">CSEMIRBuilder.h</a>, definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/csemirbuilder-cpp">CSEMIRBuilder.cpp</a>.</p>

</div>
</div>

### generateCopiesIfRequired() {#a9d23c2aafd35499e6ab41c13cb8c9523}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder CSEMIRBuilder::generateCopiesIfRequired (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &gt; DstOps, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp; MIB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/csemirbuilder-h">CSEMIRBuilder.h</a>, definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/csemirbuilder-cpp">CSEMIRBuilder.cpp</a>.</p>

</div>
</div>

### getDominatingInstrForID() {#a6bce118c21f6190369af1a308b734807}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder CSEMIRBuilder::getDominatingInstrForID (<a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> &amp; ID, void *&amp; NodeInsertPos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For given <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, find a machineinstr in the CSE Map.</p>


<p>If found, check if it dominates the current insertion point and if not, move it just before the current insertion point and return it. If not found, return Null <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a>.</p>


<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/csemirbuilder-h">CSEMIRBuilder.h</a>, definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/csemirbuilder-cpp">CSEMIRBuilder.cpp</a>.</p>

</div>
</div>

### memoizeMI() {#a20ecb12f5d22d71cd40f9e3ea6553296}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder CSEMIRBuilder::memoizeMI (<a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> MIB, void * NodeInsertPos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/csemirbuilder-h">CSEMIRBuilder.h</a>, definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/csemirbuilder-cpp">CSEMIRBuilder.cpp</a>.</p>

</div>
</div>

### profileDstOp() {#a665403895fbe470c1252de4819d00f04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CSEMIRBuilder::profileDstOp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &amp; Op, <a href="/web-llvm/docs/api/classes/llvm/giselinstprofilebuilder">GISelInstProfileBuilder</a> &amp; B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/csemirbuilder-h">CSEMIRBuilder.h</a>, definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/csemirbuilder-cpp">CSEMIRBuilder.cpp</a>.</p>

</div>
</div>

### profileDstOps() {#af9dea911a6daa75a4db7e113076bef58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CSEMIRBuilder::profileDstOps (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &gt; Ops, <a href="/web-llvm/docs/api/classes/llvm/giselinstprofilebuilder">GISelInstProfileBuilder</a> &amp; B)</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/csemirbuilder-h">CSEMIRBuilder.h</a>.</p>

</div>
</div>

### profileEverything() {#ad7619bee4a86d2909d5861716198eb23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CSEMIRBuilder::profileEverything (unsigned Opc, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &gt; DstOps, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &gt; SrcOps, std::optional&lt; unsigned &gt; Flags, <a href="/web-llvm/docs/api/classes/llvm/giselinstprofilebuilder">GISelInstProfileBuilder</a> &amp; B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/csemirbuilder-h">CSEMIRBuilder.h</a>, definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/csemirbuilder-cpp">CSEMIRBuilder.cpp</a>.</p>

</div>
</div>

### profileMBBOpcode() {#a39e86102e53060a9daabe3fbeb4e27f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CSEMIRBuilder::profileMBBOpcode (<a href="/web-llvm/docs/api/classes/llvm/giselinstprofilebuilder">GISelInstProfileBuilder</a> &amp; B, unsigned Opc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/csemirbuilder-h">CSEMIRBuilder.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/csemirbuilder-cpp">CSEMIRBuilder.cpp</a>.</p>

</div>
</div>

### profileSrcOp() {#ac091b02ba9259014e18c883b2b829d92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CSEMIRBuilder::profileSrcOp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &amp; Op, <a href="/web-llvm/docs/api/classes/llvm/giselinstprofilebuilder">GISelInstProfileBuilder</a> &amp; B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/csemirbuilder-h">CSEMIRBuilder.h</a>, definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/csemirbuilder-cpp">CSEMIRBuilder.cpp</a>.</p>

</div>
</div>

### profileSrcOps() {#a599a4fcb5249b1c6c96ad7a6800bb4c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CSEMIRBuilder::profileSrcOps (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &gt; Ops, <a href="/web-llvm/docs/api/classes/llvm/giselinstprofilebuilder">GISelInstProfileBuilder</a> &amp; B)</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/csemirbuilder-h">CSEMIRBuilder.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/csemirbuilder-h">CSEMIRBuilder.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">MachineIRBuilder.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/csemirbuilder-cpp">CSEMIRBuilder.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/machineirbuilder-cpp">MachineIRBuilder.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
