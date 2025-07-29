---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/amdgpucombinerhelper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AMDGPUCombinerHelper` Class



## Declaration

<div class="doxyDeclaration">
class llvm::AMDGPUCombinerHelper { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-h">Target/AMDGPU/AMDGPUCombinerHelper.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/combinerhelper">CombinerHelper</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18c1004eb8289cb0eb22a92785334aff">AMDGPUCombinerHelper</a> (GISelChangeObserver &amp;Observer, MachineIRBuilder &amp;B, bool IsPreLegalize, GISelKnownBits *KB, MachineDominatorTree *MDT, const LegalizerInfo *LI, const GCNSubtarget &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca13b2618c4733bb6b46c2667fbd847b">matchFoldableFneg</a> (MachineInstr &amp;MI, MachineInstr *&amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa20f5e3d228e0f30d2f3c53c53cc6c93">applyFoldableFneg</a> (MachineInstr &amp;MI, MachineInstr *&amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78bf4f9ce583ccdc1b4dbaf6c56a0030">matchExpandPromotedF16FMed3</a> (MachineInstr &amp;MI, Register Src0, Register Src1, Register Src2) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af04d5efb4c01491738f47fb92325d238">applyExpandPromotedF16FMed3</a> (MachineInstr &amp;MI, Register Src0, Register Src1, Register Src2) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d07561addd0b024b31991b0d09c6beb">matchCombineFmulWithSelectToFldexp</a> (MachineInstr &amp;MI, MachineInstr &amp;Sel, std::function&lt; void(MachineIRBuilder &amp;)&gt; &amp;MatchInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab45ce737b2839bf39a18e22fbb502ca9">CombinerHelper</a> (GISelChangeObserver &amp;Observer, MachineIRBuilder &amp;B, bool IsPreLegalize, GISelKnownBits *KB=nullptr, MachineDominatorTree *MDT=nullptr, const LegalizerInfo *LI=nullptr)</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f954ee3addd2568bddc327e72d9e61e">STI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ace3404b21b3ffa9bd3f0815d457b90">TII</a></td>
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


<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-h">AMDGPUCombinerHelper.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AMDGPUCombinerHelper() {#a18c1004eb8289cb0eb22a92785334aff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPUCombinerHelper::AMDGPUCombinerHelper (<a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver">GISelChangeObserver</a> &amp; Observer, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, bool IsPreLegalize, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits">GISelKnownBits</a> * KB, <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> * MDT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo">LegalizerInfo</a> * LI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-h">AMDGPUCombinerHelper.h</a>, definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-cpp">AMDGPUCombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#ab45ce737b2839bf39a18e22fbb502ca9">CombinerHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a7baaf2859fea3988241fef9589a47557">llvm::CombinerHelper::IsPreLegalize</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a73fb0011cd095655aa70f5e6e315b838">llvm::CombinerHelper::KB</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#aca634f15887089866f5d88dac807786c">llvm::CombinerHelper::LI</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#acebc61bc26bf037e13a22af30d10b071">llvm::CombinerHelper::MDT</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ada82db26b18384aaa5d15440061bf5a3">llvm::CombinerHelper::Observer</a>, <a href="#a8f954ee3addd2568bddc327e72d9e61e">STI</a> and <a href="#a4ace3404b21b3ffa9bd3f0815d457b90">TII</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### applyExpandPromotedF16FMed3() {#af04d5efb4c01491738f47fb92325d238}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUCombinerHelper::applyExpandPromotedF16FMed3 (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Src0, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Src1, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Src2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-h">AMDGPUCombinerHelper.h</a>, definition at line 438 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-cpp">AMDGPUCombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#aee882972a50054d1a691edcc470e4dc8">llvm::CombinerHelper::Builder</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a9fdbebed8efeedc9c2b5be88e2e33798">llvm::CombinerHelper::MRI</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>

</div>
</div>

### applyFoldableFneg() {#aa20f5e3d228e0f30d2f3c53c53cc6c93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUCombinerHelper::applyFoldableFneg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *&amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-h">AMDGPUCombinerHelper.h</a>, definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-cpp">AMDGPUCombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#aee882972a50054d1a691edcc470e4dc8">llvm::CombinerHelper::Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-cpp/#aa1fb5f8783e14903b020a9abb19d1123">inverseMinMax</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ac58f55029dff0a1026f13b8b5ee80338">llvm::MIPatternMatch::m_GFNeg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a00b04b7613c62a52917e1d2467faeab0">llvm::MIPatternMatch::m_Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a9fdbebed8efeedc9c2b5be88e2e33798">llvm::CombinerHelper::MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a6711738d18f70c1843eac7255405df54">llvm::CombinerHelper::replaceOpcodeWith</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a290f07593ec0820655db5efe88422c44">llvm::CombinerHelper::replaceRegOpWith</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a28ea263eb2492e410f764fc705781c05">llvm::CombinerHelper::replaceRegWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### CombinerHelper() {#ab45ce737b2839bf39a18e22fbb502ca9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CombinerHelper::CombinerHelper (<a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver">GISelChangeObserver</a> &amp; Observer, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, bool IsPreLegalize, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits">GISelKnownBits</a> * KB=nullptr, <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> * MDT=nullptr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo">LegalizerInfo</a> * LI=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-h">AMDGPUCombinerHelper.h</a>, definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>Referenced by <a href="#a18c1004eb8289cb0eb22a92785334aff">AMDGPUCombinerHelper</a>.</p>

</div>
</div>

### matchCombineFmulWithSelectToFldexp() {#a5d07561addd0b024b31991b0d09c6beb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUCombinerHelper::matchCombineFmulWithSelectToFldexp (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Sel, std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp;)&gt; &amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-h">AMDGPUCombinerHelper.h</a>, definition at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-cpp">AMDGPUCombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#aee882972a50054d1a691edcc470e4dc8">llvm::CombinerHelper::Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a4f404daab6050b7a8e95bb247d4aefb2">llvm::LLT::changeElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#abb1f260fc4da86ce2e93fa8628aa0b1d">llvm::LLT::float16</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aee6abb440f4fe52097595d934283f0a1">llvm::LLT::float32</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a0631408a6598e34659cc5495c3ec090b">llvm::LLT::float64</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae4165ca7bcbee300d5e9c065adcc1415">llvm::LLT::getScalarType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abc5c248ad4db5af7c01b1ed6d5cf7ad5">llvm::isConstantOrConstantSplatVectorFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a9fdbebed8efeedc9c2b5be88e2e33798">llvm::CombinerHelper::MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="#a4ace3404b21b3ffa9bd3f0815d457b90">TII</a>.</p>

</div>
</div>

### matchExpandPromotedF16FMed3() {#a78bf4f9ce583ccdc1b4dbaf6c56a0030}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUCombinerHelper::matchExpandPromotedF16FMed3 (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Src0, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Src1, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Src2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-h">AMDGPUCombinerHelper.h</a>, definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-cpp">AMDGPUCombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-cpp/#a3cc2ef5101115495b8700d1e71834d9e">isFPExtFromF16OrConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a9fdbebed8efeedc9c2b5be88e2e33798">llvm::CombinerHelper::MRI</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>

</div>
</div>

### matchFoldableFneg() {#aca13b2618c4733bb6b46c2667fbd847b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUCombinerHelper::matchFoldableFneg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *&amp; MatchInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-h">AMDGPUCombinerHelper.h</a>, definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-cpp">AMDGPUCombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-cpp/#a6258ac417f46d2a916004b2cd9de625f">allUsesHaveSourceMods</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-cpp/#ab467040f392d6225926cf1d4431cd06e">fnegFoldsIntoMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-cpp/#a51d2560cf9a3b689810956a41ce33276">isConstantCostlierToNegate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-cpp/#a3e7e31abaa8b235f868f1cf3565d5838">mayIgnoreSignedZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a9fdbebed8efeedc9c2b5be88e2e33798">llvm::CombinerHelper::MRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### STI {#a8f954ee3addd2568bddc327e72d9e61e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GCNSubtarget&amp; llvm::AMDGPUCombinerHelper::STI</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-h">AMDGPUCombinerHelper.h</a>.</p>


<p>Referenced by <a href="#a18c1004eb8289cb0eb22a92785334aff">AMDGPUCombinerHelper</a>.</p>

</div>
</div>

### TII {#a4ace3404b21b3ffa9bd3f0815d457b90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SIInstrInfo&amp; llvm::AMDGPUCombinerHelper::TII</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-h">AMDGPUCombinerHelper.h</a>.</p>


<p>Referenced by <a href="#a18c1004eb8289cb0eb22a92785334aff">AMDGPUCombinerHelper</a> and <a href="#a5d07561addd0b024b31991b0d09c6beb">matchCombineFmulWithSelectToFldexp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-cpp">AMDGPUCombinerHelper.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-h">AMDGPUCombinerHelper.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
