---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-hexagonconstpropagation-cpp-/hexagonconstevaluator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `HexagonConstEvaluator` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{HexagonConstPropagation.cpp}::HexagonConstEvaluator { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator">MachineConstEvaluator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1e9d3eca7a10a4d8e55dc1d59f7f775">HexagonConstEvaluator</a> (MachineFunction &amp;Fn)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad86353e56a3963118b327c0f528a5004">evaluate</a> (const MachineInstr &amp;MI, const CellMap &amp;Inputs, CellMap &amp;Outputs) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a2ef99d0107b0bf1ffddee13cb010d4">evaluate</a> (const RegisterSubReg &amp;R, const LatticeCell &amp;SrcC, LatticeCell &amp;Result) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a561e8197481b2a01d7f75fd567c7801e">evaluate</a> (const MachineInstr &amp;BrI, const CellMap &amp;Inputs, SetVector&lt; const MachineBasicBlock * &gt; &amp;Targets, bool &amp;FallsThru) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb1b2cd5e1fcdf67c9d6e0a723ad1265">rewrite</a> (MachineInstr &amp;MI, const CellMap &amp;Inputs) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef9a31b15115f0423f4351c280d689ff">getRegBitWidth</a> (unsigned Reg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7225de4fc119a99fadb4cf99a3dea8aa">replaceWithNop</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73f270914656280f3bebd87a6dd88b34">evaluateHexRSEQ32</a> (RegisterSubReg RL, RegisterSubReg RH, const CellMap &amp;Inputs, LatticeCell &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bec5d4c74bd3b8fdf06a46b49a5441e">evaluateHexCompare</a> (const MachineInstr &amp;MI, const CellMap &amp;Inputs, CellMap &amp;Outputs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e3a458c29b7bc6e0c9898b36588c457">evaluateHexCompare2</a> (uint32_t Cmp, const MachineOperand &amp;Src1, const MachineOperand &amp;Src2, const CellMap &amp;Inputs, bool &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48c4a3103f15b7a4502d22e7e58602b4">evaluateHexLogical</a> (const MachineInstr &amp;MI, const CellMap &amp;Inputs, CellMap &amp;Outputs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41d8532f767a666f0c47e15f6183b1c1">evaluateHexCondMove</a> (const MachineInstr &amp;MI, const CellMap &amp;Inputs, CellMap &amp;Outputs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab452409175cd7c7843344c8524d452e1">evaluateHexExt</a> (const MachineInstr &amp;MI, const CellMap &amp;Inputs, CellMap &amp;Outputs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70a5f748085e3d55d325600fb69ed93d">evaluateHexVector1</a> (const MachineInstr &amp;MI, const CellMap &amp;Inputs, CellMap &amp;Outputs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60382731d23baa1617956053d341166f">evaluateHexVector2</a> (const MachineInstr &amp;MI, const CellMap &amp;Inputs, CellMap &amp;Outputs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad311d97c27a07860cd248b27ac3fa23e">replaceAllRegUsesWith</a> (Register FromReg, Register ToReg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d471facb3bdba33e4cff4597dfd235e">rewriteHexBranch</a> (MachineInstr &amp;BrI, const CellMap &amp;Inputs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9146d0a44151d5af2ca75dec688f8e42">rewriteHexConstDefs</a> (MachineInstr &amp;MI, const CellMap &amp;Inputs, bool &amp;AllDefs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c4d733bb1a8172251e6892798b10aa7">rewriteHexConstUses</a> (MachineInstr &amp;MI, const CellMap &amp;Inputs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f5d4c0376be9e5450b2912d2022bf6f">MRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo">HexagonInstrInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe873072fa795fd1cc98386029fb152b">HII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo">HexagonRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf8a4098ead9c5b6182c72d165bb7294">HRI</a></td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15c61b7667cd62229ce910397d250d05">getCmp</a> (unsigned Opc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a62e1787302d1abfb23fefc8ce3e391">getCmpImm</a> (unsigned Opc, unsigned OpX, const MachineOperand &amp;MO)</td>
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


<p>Definition at line 1840 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### HexagonConstEvaluator() {#ab1e9d3eca7a10a4d8e55dc1d59f7f775}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{HexagonConstPropagation.cpp}::HexagonConstEvaluator::HexagonConstEvaluator (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1842 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="#ad86353e56a3963118b327c0f528a5004">evaluate</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### evaluate() {#ad86353e56a3963118b327c0f528a5004}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonConstEvaluator::evaluate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Outputs)</td>
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



<p>Definition at line 1844 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#a81f86d4f90d1b1e59de098544dc38763">anonymous{HexagonConstPropagation.cpp}::LatticeCell::add</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a9286d9966b9f76f339e39527de308291">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::constToInt</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a37c32e4b0b6cc910bfbbda5a20187396">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::CX</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#ac4917e6688b786a03dc01c382e1d9da3">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateCLBr</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#adf9bc561d4be2336b852a9dfa94a1ac8">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateCOPY</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a2fb4263d9f6453677dfd6fc3e72ed999">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateCTBr</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a342ccbdb8062b6646c20282b1367d686">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateEXTRACTr</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a7ab7f3071651b3a1f99deea3408edd6e">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateORri</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstpropagator/cellmap/#ab24773faeaec92cc45cf756a7bf552cf">anonymous{HexagonConstPropagation.cpp}::MachineConstPropagator::CellMap::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstpropagator/cellmap/#a70652f4c80c1f55b55c280a615f03d8f">anonymous{HexagonConstPropagation.cpp}::MachineConstPropagator::CellMap::has</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a5c790b664ce2cce9da4e09c8dcf2f180">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::intToConst</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a75eb135014670ce946e78739cdc9b51b">llvm::MachineOperand::isDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/constantproperties/#af78a969bb965b0f4d2bdb79ce9baf20eac255ffe2552a03202a03d622ce4d5216">anonymous{HexagonConstPropagation.cpp}::ConstantProperties::NonZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#acf8436e28b183b48eecf6b8564536c7aa7e62627fded515ebb9ff5d0ec9571d95">llvm::Hexagon::ps_sub_hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#acf8436e28b183b48eecf6b8564536c7aa4c96233dec1eedf779c37f230f6d8c10">llvm::Hexagon::ps_sub_lo</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg/#a70736188b24e0c19b8840c503758ab0c">anonymous{HexagonConstPropagation.cpp}::RegisterSubReg::Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg/#ab0cde6a2675d991140fbe6de6287ef43">anonymous{HexagonConstPropagation.cpp}::RegisterSubReg::SubReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstpropagator/cellmap/#a31510f818171cf38a456a47a1d53bcfe">anonymous{HexagonConstPropagation.cpp}::MachineConstPropagator::CellMap::update</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/constantproperties/#af78a969bb965b0f4d2bdb79ce9baf20eaef919e157ce009f336138b8e817db61f">anonymous{HexagonConstPropagation.cpp}::ConstantProperties::Zero</a>.</p>


<p>Referenced by <a href="#a2a2ef99d0107b0bf1ffddee13cb010d4">evaluate</a> and <a href="#ab1e9d3eca7a10a4d8e55dc1d59f7f775">HexagonConstEvaluator</a>.</p>

</div>
</div>

### evaluate() {#a2a2ef99d0107b0bf1ffddee13cb010d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{HexagonConstPropagation.cpp}::HexagonConstEvaluator::evaluate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg">RegisterSubReg</a> &amp; R, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell">LatticeCell</a> &amp; SrcC, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell">LatticeCell</a> &amp; Result)</td>
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



<p>Definition at line 1846 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="#ad86353e56a3963118b327c0f528a5004">evaluate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#aeb1b2cd5e1fcdf67c9d6e0a723ad1265">rewrite</a>.</p>

</div>
</div>

### evaluate() {#a561e8197481b2a01d7f75fd567c7801e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonConstEvaluator::evaluate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; BrI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; Targets, bool &amp; FallsThru)</td>
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



<p>Definition at line 1848 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstpropagator/cellmap/#ab24773faeaec92cc45cf756a7bf552cf">anonymous{HexagonConstPropagation.cpp}::MachineConstPropagator::CellMap::get</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a57e64b633278df75c699e6b98ce15031">llvm::MachineOperand::getMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstpropagator/cellmap/#a70652f4c80c1f55b55c280a615f03d8f">anonymous{HexagonConstPropagation.cpp}::MachineConstPropagator::CellMap::has</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#a1ee72f5324a484622701610ac0d2615f">anonymous{HexagonConstPropagation.cpp}::LatticeCell::isBottom</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a91c590e8191655a6739eb4df9c443896">llvm::MachineInstr::isUnconditionalBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/constantproperties/#af78a969bb965b0f4d2bdb79ce9baf20eac255ffe2552a03202a03d622ce4d5216">anonymous{HexagonConstPropagation.cpp}::ConstantProperties::NonZero</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#ab13878421737db422070f682fda17077">anonymous{HexagonConstPropagation.cpp}::LatticeCell::properties</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg/#a70736188b24e0c19b8840c503758ab0c">anonymous{HexagonConstPropagation.cpp}::RegisterSubReg::Reg</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg/#ab0cde6a2675d991140fbe6de6287ef43">anonymous{HexagonConstPropagation.cpp}::RegisterSubReg::SubReg</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/constantproperties/#af78a969bb965b0f4d2bdb79ce9baf20eaef919e157ce009f336138b8e817db61f">anonymous{HexagonConstPropagation.cpp}::ConstantProperties::Zero</a>.</p>

</div>
</div>

### rewrite() {#aeb1b2cd5e1fcdf67c9d6e0a723ad1265}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonConstEvaluator::rewrite (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs)</td>
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



<p>Definition at line 1851 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a2a2ef99d0107b0bf1ffddee13cb010d4">evaluate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### evaluateHexCompare() {#a9bec5d4c74bd3b8fdf06a46b49a5441e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonConstEvaluator::evaluateHexCompare (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Outputs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1863 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>

</div>
</div>

### evaluateHexCompare2() {#a6e3a458c29b7bc6e0c9898b36588c457}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonConstEvaluator::evaluateHexCompare2 (uint32_t Cmp, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Src1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Src2, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs, bool &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1866 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>

</div>
</div>

### evaluateHexCondMove() {#a41d8532f767a666f0c47e15f6183b1c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonConstEvaluator::evaluateHexCondMove (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Outputs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1870 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>

</div>
</div>

### evaluateHexExt() {#ab452409175cd7c7843344c8524d452e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonConstEvaluator::evaluateHexExt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Outputs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1872 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>

</div>
</div>

### evaluateHexLogical() {#a48c4a3103f15b7a4502d22e7e58602b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonConstEvaluator::evaluateHexLogical (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Outputs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1868 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>

</div>
</div>

### evaluateHexRSEQ32() {#a73f270914656280f3bebd87a6dd88b34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonConstEvaluator::evaluateHexRSEQ32 (<a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg">RegisterSubReg</a> RL, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg">RegisterSubReg</a> RH, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell">LatticeCell</a> &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1861 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>

</div>
</div>

### evaluateHexVector1() {#a70a5f748085e3d55d325600fb69ed93d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonConstEvaluator::evaluateHexVector1 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Outputs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1874 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>

</div>
</div>

### evaluateHexVector2() {#a60382731d23baa1617956053d341166f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{HexagonConstPropagation.cpp}::HexagonConstEvaluator::evaluateHexVector2 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Outputs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1876 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>

</div>
</div>

### getRegBitWidth() {#aef9a31b15115f0423f4351c280d689ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned HexagonConstEvaluator::getRegBitWidth (unsigned Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1854 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>

</div>
</div>

### replaceAllRegUsesWith() {#ad311d97c27a07860cd248b27ac3fa23e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonConstEvaluator::replaceAllRegUsesWith (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> FromReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> ToReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1879 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>

</div>
</div>

### replaceWithNop() {#a7225de4fc119a99fadb4cf99a3dea8aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonConstEvaluator::replaceWithNop (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1859 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>

</div>
</div>

### rewriteHexBranch() {#a1d471facb3bdba33e4cff4597dfd235e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonConstEvaluator::rewriteHexBranch (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; BrI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1880 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>

</div>
</div>

### rewriteHexConstDefs() {#a9146d0a44151d5af2ca75dec688f8e42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonConstEvaluator::rewriteHexConstDefs (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs, bool &amp; AllDefs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1881 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>

</div>
</div>

### rewriteHexConstUses() {#a0c4d733bb1a8172251e6892798b10aa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonConstEvaluator::rewriteHexConstUses (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1883 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### HII {#abe873072fa795fd1cc98386029fb152b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const HexagonInstrInfo&amp; anonymous{HexagonConstPropagation.cpp}::HexagonConstEvaluator::HII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1886 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>

</div>
</div>

### HRI {#acf8a4098ead9c5b6182c72d165bb7294}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const HexagonRegisterInfo&amp; anonymous{HexagonConstPropagation.cpp}::HexagonConstEvaluator::HRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1887 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>

</div>
</div>

### MRI {#a0f5d4c0376be9e5450b2912d2022bf6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* anonymous{HexagonConstPropagation.cpp}::HexagonConstEvaluator::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1885 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getCmp() {#a15c61b7667cd62229ce910397d250d05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t HexagonConstEvaluator::getCmp (unsigned Opc)</td>
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



<p>Definition at line 1856 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>

</div>
</div>

### getCmpImm() {#a4a62e1787302d1abfb23fefc8ce3e391}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt HexagonConstEvaluator::getCmpImm (unsigned Opc, unsigned OpX, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
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



<p>Definition at line 1857 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
