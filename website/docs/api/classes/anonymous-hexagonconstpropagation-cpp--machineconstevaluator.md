---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MachineConstEvaluator` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator { ... }
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/hexagonconstevaluator">HexagonConstEvaluator</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> = <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstpropagator/cellmap">MachineConstPropagator::CellMap</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a261857237efac777a2276932250c0a54">MachineConstEvaluator</a> (MachineFunction &amp;Fn)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae49e6b5430baec5f6fd80157c8627282">~MachineConstEvaluator</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20f516d544c71d0983efc0d99bad30bc">evaluate</a> (const MachineInstr &amp;MI, const CellMap &amp;Inputs, CellMap &amp;Outputs)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a477c0d05e2e7e12dfd51d7f7ca3d161d">evaluate</a> (const RegisterSubReg &amp;R, const LatticeCell &amp;SrcC, LatticeCell &amp;Result)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00560e76184e436f82e32992f4575ca8">evaluate</a> (const MachineInstr &amp;BrI, const CellMap &amp;Inputs, SetVector&lt; const MachineBasicBlock * &gt; &amp;Targets, bool &amp;CanFallThru)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5263e6869ad90c6c462e3c329b03645a">rewrite</a> (MachineInstr &amp;MI, const CellMap &amp;Inputs)=0</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd3a5d63ecde206c7feb8164c106ac07">getCell</a> (const RegisterSubReg &amp;R, const CellMap &amp;Inputs, LatticeCell &amp;RC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9286d9966b9f76f339e39527de308291">constToInt</a> (const Constant *C, APInt &amp;Val) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c790b664ce2cce9da4e09c8dcf2f180">intToConst</a> (const APInt &amp;Val) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a175283278a754c84b75df5e20c5796">evaluateCMPrr</a> (uint32_t Cmp, const RegisterSubReg &amp;R1, const RegisterSubReg &amp;R2, const CellMap &amp;Inputs, bool &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46ce255d2c91bc39276b3abf153b1e58">evaluateCMPri</a> (uint32_t Cmp, const RegisterSubReg &amp;R1, const APInt &amp;A2, const CellMap &amp;Inputs, bool &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a069e11f50fb0348dacac4b0ad2715bbe">evaluateCMPrp</a> (uint32_t Cmp, const RegisterSubReg &amp;R1, uint64_t Props2, const CellMap &amp;Inputs, bool &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0c949f0956bdd475184e8d934dc96e2">evaluateCMPii</a> (uint32_t Cmp, const APInt &amp;A1, const APInt &amp;A2, bool &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d79f7c97b9ebb6f1e78ca528ad3c3f4">evaluateCMPpi</a> (uint32_t Cmp, uint32_t Props, const APInt &amp;A2, bool &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39b553530fd53da65768fd8a51389eeb">evaluateCMPpp</a> (uint32_t Cmp, uint32_t Props1, uint32_t Props2, bool &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf9bc561d4be2336b852a9dfa94a1ac8">evaluateCOPY</a> (const RegisterSubReg &amp;R1, const CellMap &amp;Inputs, LatticeCell &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbb80dd4d686b8eda7304201f49f48e9">evaluateANDrr</a> (const RegisterSubReg &amp;R1, const RegisterSubReg &amp;R2, const CellMap &amp;Inputs, LatticeCell &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e49cc0a8c1be83f39602a85c288835f">evaluateANDri</a> (const RegisterSubReg &amp;R1, const APInt &amp;A2, const CellMap &amp;Inputs, LatticeCell &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb6200d2329fa2e4debe961e66440ccf">evaluateANDii</a> (const APInt &amp;A1, const APInt &amp;A2, APInt &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c9526b09e12ac8a17ba2ab79aeff1c5">evaluateORrr</a> (const RegisterSubReg &amp;R1, const RegisterSubReg &amp;R2, const CellMap &amp;Inputs, LatticeCell &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ab7f3071651b3a1f99deea3408edd6e">evaluateORri</a> (const RegisterSubReg &amp;R1, const APInt &amp;A2, const CellMap &amp;Inputs, LatticeCell &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac14920dc310e76994e10477d3a30ffb">evaluateORii</a> (const APInt &amp;A1, const APInt &amp;A2, APInt &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a812ba4120e868c63ef47c07d4963ec29">evaluateXORrr</a> (const RegisterSubReg &amp;R1, const RegisterSubReg &amp;R2, const CellMap &amp;Inputs, LatticeCell &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40b8bf88c0e4f03f5dfdcd1a34610530">evaluateXORri</a> (const RegisterSubReg &amp;R1, const APInt &amp;A2, const CellMap &amp;Inputs, LatticeCell &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8ed36cbf2cad668c07842c44e26ae4d">evaluateXORii</a> (const APInt &amp;A1, const APInt &amp;A2, APInt &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f45763d26a7cd4e3f11ebde35694017">evaluateZEXTr</a> (const RegisterSubReg &amp;R1, unsigned Width, unsigned Bits, const CellMap &amp;Inputs, LatticeCell &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80a69d92372f6bfde4ea47c1b55b84bb">evaluateZEXTi</a> (const APInt &amp;A1, unsigned Width, unsigned Bits, APInt &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1254219a658c0740a16c1461cbb81e49">evaluateSEXTr</a> (const RegisterSubReg &amp;R1, unsigned Width, unsigned Bits, const CellMap &amp;Inputs, LatticeCell &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab018e5f3273fdf77d6838c1bb037137a">evaluateSEXTi</a> (const APInt &amp;A1, unsigned Width, unsigned Bits, APInt &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4917e6688b786a03dc01c382e1d9da3">evaluateCLBr</a> (const RegisterSubReg &amp;R1, bool Zeros, bool Ones, const CellMap &amp;Inputs, LatticeCell &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fe1f82ca176ae71b0d72e241df952ea">evaluateCLBi</a> (const APInt &amp;A1, bool Zeros, bool Ones, APInt &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fb4263d9f6453677dfd6fc3e72ed999">evaluateCTBr</a> (const RegisterSubReg &amp;R1, bool Zeros, bool Ones, const CellMap &amp;Inputs, LatticeCell &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56d6f482a718e221a121400cb89aef5b">evaluateCTBi</a> (const APInt &amp;A1, bool Zeros, bool Ones, APInt &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a342ccbdb8062b6646c20282b1367d686">evaluateEXTRACTr</a> (const RegisterSubReg &amp;R1, unsigned Width, unsigned Bits, unsigned Offset, bool Signed, const CellMap &amp;Inputs, LatticeCell &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7767cf650405a9ff3d68ae59a76c15d">evaluateEXTRACTi</a> (const APInt &amp;A1, unsigned Bits, unsigned Offset, bool Signed, APInt &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a992c70a7697deaf90987fc37148fc211">evaluateSplatr</a> (const RegisterSubReg &amp;R1, unsigned Bits, unsigned Count, const CellMap &amp;Inputs, LatticeCell &amp;Result)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c5315388a7981c96e7f006c78980966">evaluateSplati</a> (const APInt &amp;A1, unsigned Bits, unsigned Count, APInt &amp;Result)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a175345dc12ffa8b0fc7e1af05a2b4e99">TRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac180992caa0708a693ae60f707a1af45">MF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37c32e4b0b6cc910bfbbda5a20187396">CX</a></td>
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


<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### CellMap {#a2642f5609c60c3f7878b1b917e9875f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::CellMap =  MachineConstPropagator::CellMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MachineConstEvaluator() {#a261857237efac777a2276932250c0a54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::MachineConstEvaluator (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; Fn)</td>
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



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="#a37c32e4b0b6cc910bfbbda5a20187396">CX</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/evaluator-cpp/#a92efb02157b6836e1232c577d34678d6">getFunction</a>, <a href="#ac180992caa0708a693ae60f707a1af45">MF</a> and <a href="#a175345dc12ffa8b0fc7e1af05a2b4e99">TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MachineConstEvaluator() {#ae49e6b5430baec5f6fd80157c8627282}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::~MachineConstEvaluator ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### evaluate() {#a20f516d544c71d0983efc0d99bad30bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs, <a href="#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Outputs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#afbb80dd4d686b8eda7304201f49f48e9">evaluateANDrr</a>, <a href="#a5c9526b09e12ac8a17ba2ab79aeff1c5">evaluateORrr</a> and <a href="#abd3a5d63ecde206c7feb8164c106ac07">getCell</a>.</p>

</div>
</div>

### evaluate() {#a477c0d05e2e7e12dfd51d7f7ca3d161d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg">RegisterSubReg</a> &amp; R, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell">LatticeCell</a> &amp; SrcC, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell">LatticeCell</a> &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>

</div>
</div>

### evaluate() {#a00560e76184e436f82e32992f4575ca8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; BrI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; Targets, bool &amp; CanFallThru)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>

</div>
</div>

### rewrite() {#a5263e6869ad90c6c462e3c329b03645a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::rewrite (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### constToInt() {#a9286d9966b9f76f339e39527de308291}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineConstEvaluator::constToInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Val)</td>
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



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/classes/llvm/constantint/#af7e1934ed72a405ef073ea5f9bbe828e">llvm::ConstantInt::getValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/hexagonconstevaluator/#ad86353e56a3963118b327c0f528a5004">anonymous{HexagonConstPropagation.cpp}::HexagonConstEvaluator::evaluate</a>, <a href="#a3e49cc0a8c1be83f39602a85c288835f">evaluateANDri</a>, <a href="#afbb80dd4d686b8eda7304201f49f48e9">evaluateANDrr</a>, <a href="#ac4917e6688b786a03dc01c382e1d9da3">evaluateCLBr</a>, <a href="#a46ce255d2c91bc39276b3abf153b1e58">evaluateCMPri</a>, <a href="#a069e11f50fb0348dacac4b0ad2715bbe">evaluateCMPrp</a>, <a href="#a3a175283278a754c84b75df5e20c5796">evaluateCMPrr</a>, <a href="#a2fb4263d9f6453677dfd6fc3e72ed999">evaluateCTBr</a>, <a href="#a342ccbdb8062b6646c20282b1367d686">evaluateEXTRACTr</a>, <a href="#a7ab7f3071651b3a1f99deea3408edd6e">evaluateORri</a>, <a href="#a5c9526b09e12ac8a17ba2ab79aeff1c5">evaluateORrr</a>, <a href="#a1254219a658c0740a16c1461cbb81e49">evaluateSEXTr</a>, <a href="#a992c70a7697deaf90987fc37148fc211">evaluateSplatr</a>, <a href="#a40b8bf88c0e4f03f5dfdcd1a34610530">evaluateXORri</a>, <a href="#a812ba4120e868c63ef47c07d4963ec29">evaluateXORrr</a> and <a href="#a9f45763d26a7cd4e3f11ebde35694017">evaluateZEXTr</a>.</p>

</div>
</div>

### evaluateANDii() {#adb6200d2329fa2e4debe961e66440ccf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineConstEvaluator::evaluateANDii (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; A1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; A2, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Result)</td>
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



<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>Referenced by <a href="#a3e49cc0a8c1be83f39602a85c288835f">evaluateANDri</a>.</p>

</div>
</div>

### evaluateANDri() {#a3e49cc0a8c1be83f39602a85c288835f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineConstEvaluator::evaluateANDri (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg">RegisterSubReg</a> &amp; R1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; A2, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell">LatticeCell</a> &amp; Result)</td>
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



<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#a81f86d4f90d1b1e59de098544dc38763">anonymous{HexagonConstPropagation.cpp}::LatticeCell::add</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a9286d9966b9f76f339e39527de308291">constToInt</a>, <a href="#adb6200d2329fa2e4debe961e66440ccf">evaluateANDii</a>, <a href="#abd3a5d63ecde206c7feb8164c106ac07">getCell</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstpropagator/cellmap/#a70652f4c80c1f55b55c280a615f03d8f">anonymous{HexagonConstPropagation.cpp}::MachineConstPropagator::CellMap::has</a>, <a href="#a5c790b664ce2cce9da4e09c8dcf2f180">intToConst</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#a1ee72f5324a484622701610ac0d2615f">anonymous{HexagonConstPropagation.cpp}::LatticeCell::isBottom</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#aed4734b49f3e9c04536c619bf56003dc">anonymous{HexagonConstPropagation.cpp}::LatticeCell::isProperty</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg/#a70736188b24e0c19b8840c503758ab0c">anonymous{HexagonConstPropagation.cpp}::RegisterSubReg::Reg</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#afa5e1e7c3e449f788949809bb8cd134f">anonymous{HexagonConstPropagation.cpp}::LatticeCell::size</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#a5b017ee29c0481d436846d41d233b756">anonymous{HexagonConstPropagation.cpp}::LatticeCell::Values</a>.</p>


<p>Referenced by <a href="#afbb80dd4d686b8eda7304201f49f48e9">evaluateANDrr</a>.</p>

</div>
</div>

### evaluateANDrr() {#afbb80dd4d686b8eda7304201f49f48e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineConstEvaluator::evaluateANDrr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg">RegisterSubReg</a> &amp; R1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg">RegisterSubReg</a> &amp; R2, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell">LatticeCell</a> &amp; Result)</td>
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



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9286d9966b9f76f339e39527de308291">constToInt</a>, <a href="#a20f516d544c71d0983efc0d99bad30bc">evaluate</a>, <a href="#a3e49cc0a8c1be83f39602a85c288835f">evaluateANDri</a>, <a href="#afbb80dd4d686b8eda7304201f49f48e9">evaluateANDrr</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstpropagator/cellmap/#ab24773faeaec92cc45cf756a7bf552cf">anonymous{HexagonConstPropagation.cpp}::MachineConstPropagator::CellMap::get</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstpropagator/cellmap/#a70652f4c80c1f55b55c280a615f03d8f">anonymous{HexagonConstPropagation.cpp}::MachineConstPropagator::CellMap::has</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#a1ee72f5324a484622701610ac0d2615f">anonymous{HexagonConstPropagation.cpp}::LatticeCell::isBottom</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#aed4734b49f3e9c04536c619bf56003dc">anonymous{HexagonConstPropagation.cpp}::LatticeCell::isProperty</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h/#a9211f62d8e1e6de999eaa63ec0f6ae02">R2</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg/#a70736188b24e0c19b8840c503758ab0c">anonymous{HexagonConstPropagation.cpp}::RegisterSubReg::Reg</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#afa5e1e7c3e449f788949809bb8cd134f">anonymous{HexagonConstPropagation.cpp}::LatticeCell::size</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#a5b017ee29c0481d436846d41d233b756">anonymous{HexagonConstPropagation.cpp}::LatticeCell::Values</a>.</p>


<p>Referenced by <a href="#afbb80dd4d686b8eda7304201f49f48e9">evaluateANDrr</a>.</p>

</div>
</div>

### evaluateCLBi() {#a7fe1f82ca176ae71b0d72e241df952ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineConstEvaluator::evaluateCLBi (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; A1, bool Zeros, bool Ones, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Result)</td>
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



<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aa619d96a87c8a5be606b1a4a4ac0115d">llvm::APInt::countl_one</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8bad27827f46bca6baf814cbd2b64e84">llvm::APInt::countl_zero</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>.</p>


<p>Referenced by <a href="#ac4917e6688b786a03dc01c382e1d9da3">evaluateCLBr</a>.</p>

</div>
</div>

### evaluateCLBr() {#ac4917e6688b786a03dc01c382e1d9da3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineConstEvaluator::evaluateCLBr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg">RegisterSubReg</a> &amp; R1, bool Zeros, bool Ones, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell">LatticeCell</a> &amp; Result)</td>
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



<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a9286d9966b9f76f339e39527de308291">constToInt</a>, <a href="#a7fe1f82ca176ae71b0d72e241df952ea">evaluateCLBi</a>, <a href="#abd3a5d63ecde206c7feb8164c106ac07">getCell</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstpropagator/cellmap/#a70652f4c80c1f55b55c280a615f03d8f">anonymous{HexagonConstPropagation.cpp}::MachineConstPropagator::CellMap::has</a>, <a href="#a5c790b664ce2cce9da4e09c8dcf2f180">intToConst</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#a1ee72f5324a484622701610ac0d2615f">anonymous{HexagonConstPropagation.cpp}::LatticeCell::isBottom</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#aed4734b49f3e9c04536c619bf56003dc">anonymous{HexagonConstPropagation.cpp}::LatticeCell::isProperty</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg/#a70736188b24e0c19b8840c503758ab0c">anonymous{HexagonConstPropagation.cpp}::RegisterSubReg::Reg</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#afa5e1e7c3e449f788949809bb8cd134f">anonymous{HexagonConstPropagation.cpp}::LatticeCell::size</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#a5b017ee29c0481d436846d41d233b756">anonymous{HexagonConstPropagation.cpp}::LatticeCell::Values</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/hexagonconstevaluator/#ad86353e56a3963118b327c0f528a5004">anonymous{HexagonConstPropagation.cpp}::HexagonConstEvaluator::evaluate</a>.</p>

</div>
</div>

### evaluateCMPii() {#af0c949f0956bdd475184e8d934dc96e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineConstEvaluator::evaluateCMPii (uint32_t Cmp, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; A1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; A2, bool &amp; Result)</td>
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



<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/comparison/#a39668000392fa4abbd587966a42db47dab24618d660fcecfc17f88a51a8902955">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::Comparison::EQ</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/comparison/#a39668000392fa4abbd587966a42db47da6e93116b6b71d16d2c84db906e6e5128">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::Comparison::G</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ad76807eccec7690dec05dd5f36aceb08">llvm::APInt::isSameValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/comparison/#a39668000392fa4abbd587966a42db47dae9dc5301a4703fd8f71e8ae4796d4dfe">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::Comparison::L</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/comparison/#a39668000392fa4abbd587966a42db47da07aed9a1d212a4e0b332ebe5730377da">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::Comparison::NE</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aca8fce65eb69a82aa10a635e2e79877a">llvm::APInt::sext</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#adafa9575780f9246d1df0b7e2a619356">llvm::APInt::slt</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/comparison/#a39668000392fa4abbd587966a42db47da864bce22cd44dd5acdba2abd48ada7c3">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::Comparison::U</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a545e8d5dfa1688acea0d0e275b03682f">llvm::APInt::ult</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a1dc76cc8bf703e6ada68bededcbb9573">llvm::APInt::zext</a>.</p>


<p>Referenced by <a href="#a46ce255d2c91bc39276b3abf153b1e58">evaluateCMPri</a>.</p>

</div>
</div>

### evaluateCMPpi() {#a6d79f7c97b9ebb6f1e78ca528ad3c3f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineConstEvaluator::evaluateCMPpi (uint32_t Cmp, uint32_t Props, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; A2, bool &amp; Result)</td>
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



<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/comparison/#a39668000392fa4abbd587966a42db47dab24618d660fcecfc17f88a51a8902955">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::Comparison::EQ</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/constantproperties/#af78a969bb965b0f4d2bdb79ce9baf20eade64a482e898536df49815e59c181e68">anonymous{HexagonConstPropagation.cpp}::ConstantProperties::Finite</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/comparison/#a39668000392fa4abbd587966a42db47da6e93116b6b71d16d2c84db906e6e5128">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::Comparison::G</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a6804d9caf15411f55e7b9e9f397f0422">llvm::APInt::isNegative</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/comparison/#a39668000392fa4abbd587966a42db47dae9dc5301a4703fd8f71e8ae4796d4dfe">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::Comparison::L</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/constantproperties/#af78a969bb965b0f4d2bdb79ce9baf20eaa0cccb008a3914b88dfc26d7763f0179">anonymous{HexagonConstPropagation.cpp}::ConstantProperties::NaN</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/comparison/#a39668000392fa4abbd587966a42db47da07aed9a1d212a4e0b332ebe5730377da">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::Comparison::NE</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/constantproperties/#af78a969bb965b0f4d2bdb79ce9baf20ea08112154ca09f6cbf19bbbd8b1b3a34c">anonymous{HexagonConstPropagation.cpp}::ConstantProperties::NegOrZero</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/constantproperties/#af78a969bb965b0f4d2bdb79ce9baf20eac255ffe2552a03202a03d622ce4d5216">anonymous{HexagonConstPropagation.cpp}::ConstantProperties::NonZero</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/constantproperties/#af78a969bb965b0f4d2bdb79ce9baf20eadc91a81eb1fbc5305a83ac09843d10f9">anonymous{HexagonConstPropagation.cpp}::ConstantProperties::PosOrZero</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/comparison/#a39668000392fa4abbd587966a42db47da864bce22cd44dd5acdba2abd48ada7c3">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::Comparison::U</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/constantproperties/#af78a969bb965b0f4d2bdb79ce9baf20eae39e5aad668b29b247469a47a090f83f">anonymous{HexagonConstPropagation.cpp}::ConstantProperties::Unknown</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/constantproperties/#af78a969bb965b0f4d2bdb79ce9baf20eaef919e157ce009f336138b8e817db61f">anonymous{HexagonConstPropagation.cpp}::ConstantProperties::Zero</a>.</p>


<p>Referenced by <a href="#a46ce255d2c91bc39276b3abf153b1e58">evaluateCMPri</a> and <a href="#a069e11f50fb0348dacac4b0ad2715bbe">evaluateCMPrp</a>.</p>

</div>
</div>

### evaluateCMPpp() {#a39b553530fd53da65768fd8a51389eeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineConstEvaluator::evaluateCMPpp (uint32_t Cmp, uint32_t Props1, uint32_t Props2, bool &amp; Result)</td>
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



<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/comparison/#a39668000392fa4abbd587966a42db47dab24618d660fcecfc17f88a51a8902955">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::Comparison::EQ</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/comparison/#a39668000392fa4abbd587966a42db47da6e93116b6b71d16d2c84db906e6e5128">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::Comparison::G</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/comparison/#a39668000392fa4abbd587966a42db47dae9dc5301a4703fd8f71e8ae4796d4dfe">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::Comparison::L</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/comparison/#a39668000392fa4abbd587966a42db47da07aed9a1d212a4e0b332ebe5730377da">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::Comparison::NE</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/comparison/#a39668000392fa4abbd587966a42db47da864bce22cd44dd5acdba2abd48ada7c3">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::Comparison::U</a>.</p>


<p>Referenced by <a href="#a069e11f50fb0348dacac4b0ad2715bbe">evaluateCMPrp</a> and <a href="#a3a175283278a754c84b75df5e20c5796">evaluateCMPrr</a>.</p>

</div>
</div>

### evaluateCMPri() {#a46ce255d2c91bc39276b3abf153b1e58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineConstEvaluator::evaluateCMPri (uint32_t Cmp, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg">RegisterSubReg</a> &amp; R1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; A2, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs, bool &amp; Result)</td>
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



<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9286d9966b9f76f339e39527de308291">constToInt</a>, <a href="#af0c949f0956bdd475184e8d934dc96e2">evaluateCMPii</a>, <a href="#a6d79f7c97b9ebb6f1e78ca528ad3c3f4">evaluateCMPpi</a>, <a href="#abd3a5d63ecde206c7feb8164c106ac07">getCell</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstpropagator/cellmap/#a70652f4c80c1f55b55c280a615f03d8f">anonymous{HexagonConstPropagation.cpp}::MachineConstPropagator::CellMap::has</a> and <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg/#a70736188b24e0c19b8840c503758ab0c">anonymous{HexagonConstPropagation.cpp}::RegisterSubReg::Reg</a>.</p>


<p>Referenced by <a href="#a3a175283278a754c84b75df5e20c5796">evaluateCMPrr</a>.</p>

</div>
</div>

### evaluateCMPrp() {#a069e11f50fb0348dacac4b0ad2715bbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineConstEvaluator::evaluateCMPrp (uint32_t Cmp, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg">RegisterSubReg</a> &amp; R1, uint64_t Props2, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs, bool &amp; Result)</td>
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



<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9286d9966b9f76f339e39527de308291">constToInt</a>, <a href="#a6d79f7c97b9ebb6f1e78ca528ad3c3f4">evaluateCMPpi</a>, <a href="#a39b553530fd53da65768fd8a51389eeb">evaluateCMPpp</a>, <a href="#abd3a5d63ecde206c7feb8164c106ac07">getCell</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstpropagator/cellmap/#a70652f4c80c1f55b55c280a615f03d8f">anonymous{HexagonConstPropagation.cpp}::MachineConstPropagator::CellMap::has</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/comparison/#abc0b532d7422273606194f5a113059fc">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::Comparison::negate</a> and <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg/#a70736188b24e0c19b8840c503758ab0c">anonymous{HexagonConstPropagation.cpp}::RegisterSubReg::Reg</a>.</p>


<p>Referenced by <a href="#a3a175283278a754c84b75df5e20c5796">evaluateCMPrr</a>.</p>

</div>
</div>

### evaluateCMPrr() {#a3a175283278a754c84b75df5e20c5796}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineConstEvaluator::evaluateCMPrr (uint32_t Cmp, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg">RegisterSubReg</a> &amp; R1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg">RegisterSubReg</a> &amp; R2, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs, bool &amp; Result)</td>
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



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9286d9966b9f76f339e39527de308291">constToInt</a>, <a href="#a39b553530fd53da65768fd8a51389eeb">evaluateCMPpp</a>, <a href="#a46ce255d2c91bc39276b3abf153b1e58">evaluateCMPri</a>, <a href="#a069e11f50fb0348dacac4b0ad2715bbe">evaluateCMPrp</a>, <a href="#abd3a5d63ecde206c7feb8164c106ac07">getCell</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstpropagator/cellmap/#a70652f4c80c1f55b55c280a615f03d8f">anonymous{HexagonConstPropagation.cpp}::MachineConstPropagator::CellMap::has</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#aed4734b49f3e9c04536c619bf56003dc">anonymous{HexagonConstPropagation.cpp}::LatticeCell::isProperty</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/comparison/#abc0b532d7422273606194f5a113059fc">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::Comparison::negate</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#ab13878421737db422070f682fda17077">anonymous{HexagonConstPropagation.cpp}::LatticeCell::properties</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h/#a9211f62d8e1e6de999eaa63ec0f6ae02">R2</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg/#a70736188b24e0c19b8840c503758ab0c">anonymous{HexagonConstPropagation.cpp}::RegisterSubReg::Reg</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#afa5e1e7c3e449f788949809bb8cd134f">anonymous{HexagonConstPropagation.cpp}::LatticeCell::size</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#a5b017ee29c0481d436846d41d233b756">anonymous{HexagonConstPropagation.cpp}::LatticeCell::Values</a>.</p>

</div>
</div>

### evaluateCOPY() {#adf9bc561d4be2336b852a9dfa94a1ac8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineConstEvaluator::evaluateCOPY (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg">RegisterSubReg</a> &amp; R1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell">LatticeCell</a> &amp; Result)</td>
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



<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>Reference <a href="#abd3a5d63ecde206c7feb8164c106ac07">getCell</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/hexagonconstevaluator/#ad86353e56a3963118b327c0f528a5004">anonymous{HexagonConstPropagation.cpp}::HexagonConstEvaluator::evaluate</a>.</p>

</div>
</div>

### evaluateCTBi() {#a56d6f482a718e221a121400cb89aef5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineConstEvaluator::evaluateCTBi (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; A1, bool Zeros, bool Ones, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Result)</td>
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



<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af34a543ce8585d04c1ae22c78b3182dd">llvm::APInt::countr_one</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a83c7c9008ba213687483b60a658b4a13">llvm::APInt::countr_zero</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>.</p>


<p>Referenced by <a href="#a2fb4263d9f6453677dfd6fc3e72ed999">evaluateCTBr</a>.</p>

</div>
</div>

### evaluateCTBr() {#a2fb4263d9f6453677dfd6fc3e72ed999}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineConstEvaluator::evaluateCTBr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg">RegisterSubReg</a> &amp; R1, bool Zeros, bool Ones, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell">LatticeCell</a> &amp; Result)</td>
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



<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a9286d9966b9f76f339e39527de308291">constToInt</a>, <a href="#a56d6f482a718e221a121400cb89aef5b">evaluateCTBi</a>, <a href="#abd3a5d63ecde206c7feb8164c106ac07">getCell</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstpropagator/cellmap/#a70652f4c80c1f55b55c280a615f03d8f">anonymous{HexagonConstPropagation.cpp}::MachineConstPropagator::CellMap::has</a>, <a href="#a5c790b664ce2cce9da4e09c8dcf2f180">intToConst</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#a1ee72f5324a484622701610ac0d2615f">anonymous{HexagonConstPropagation.cpp}::LatticeCell::isBottom</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#aed4734b49f3e9c04536c619bf56003dc">anonymous{HexagonConstPropagation.cpp}::LatticeCell::isProperty</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg/#a70736188b24e0c19b8840c503758ab0c">anonymous{HexagonConstPropagation.cpp}::RegisterSubReg::Reg</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#afa5e1e7c3e449f788949809bb8cd134f">anonymous{HexagonConstPropagation.cpp}::LatticeCell::size</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#a5b017ee29c0481d436846d41d233b756">anonymous{HexagonConstPropagation.cpp}::LatticeCell::Values</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/hexagonconstevaluator/#ad86353e56a3963118b327c0f528a5004">anonymous{HexagonConstPropagation.cpp}::HexagonConstEvaluator::evaluate</a>.</p>

</div>
</div>

### evaluateEXTRACTi() {#ae7767cf650405a9ff3d68ae59a76c15d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineConstEvaluator::evaluateEXTRACTi (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; A1, unsigned Bits, unsigned Offset, bool Signed, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Result)</td>
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



<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#ab6006923d1a3139d70abc8f6552a7960">llvm::APInt::ashr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af34549c39d6f741fbdaf9a795aa306e9">llvm::APInt::lshr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#acb9c55b6986369948507ca5241b4e411">llvm::APInt::shl</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed</a>.</p>


<p>Referenced by <a href="#a342ccbdb8062b6646c20282b1367d686">evaluateEXTRACTr</a>.</p>

</div>
</div>

### evaluateEXTRACTr() {#a342ccbdb8062b6646c20282b1367d686}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineConstEvaluator::evaluateEXTRACTr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg">RegisterSubReg</a> &amp; R1, unsigned Width, unsigned Bits, unsigned Offset, bool Signed, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell">LatticeCell</a> &amp; Result)</td>
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



<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a9286d9966b9f76f339e39527de308291">constToInt</a>, <a href="#ae7767cf650405a9ff3d68ae59a76c15d">evaluateEXTRACTi</a>, <a href="#abd3a5d63ecde206c7feb8164c106ac07">getCell</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstpropagator/cellmap/#a70652f4c80c1f55b55c280a615f03d8f">anonymous{HexagonConstPropagation.cpp}::MachineConstPropagator::CellMap::has</a>, <a href="#a5c790b664ce2cce9da4e09c8dcf2f180">intToConst</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#a1ee72f5324a484622701610ac0d2615f">anonymous{HexagonConstPropagation.cpp}::LatticeCell::isBottom</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#aed4734b49f3e9c04536c619bf56003dc">anonymous{HexagonConstPropagation.cpp}::LatticeCell::isProperty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#ab13878421737db422070f682fda17077">anonymous{HexagonConstPropagation.cpp}::LatticeCell::properties</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg/#a70736188b24e0c19b8840c503758ab0c">anonymous{HexagonConstPropagation.cpp}::RegisterSubReg::Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#afa5e1e7c3e449f788949809bb8cd134f">anonymous{HexagonConstPropagation.cpp}::LatticeCell::size</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#a5b017ee29c0481d436846d41d233b756">anonymous{HexagonConstPropagation.cpp}::LatticeCell::Values</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/constantproperties/#af78a969bb965b0f4d2bdb79ce9baf20eaef919e157ce009f336138b8e817db61f">anonymous{HexagonConstPropagation.cpp}::ConstantProperties::Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/hexagonconstevaluator/#ad86353e56a3963118b327c0f528a5004">anonymous{HexagonConstPropagation.cpp}::HexagonConstEvaluator::evaluate</a>.</p>

</div>
</div>

### evaluateORii() {#aac14920dc310e76994e10477d3a30ffb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineConstEvaluator::evaluateORii (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; A1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; A2, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Result)</td>
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



<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>Referenced by <a href="#a7ab7f3071651b3a1f99deea3408edd6e">evaluateORri</a>.</p>

</div>
</div>

### evaluateORri() {#a7ab7f3071651b3a1f99deea3408edd6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineConstEvaluator::evaluateORri (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg">RegisterSubReg</a> &amp; R1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; A2, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell">LatticeCell</a> &amp; Result)</td>
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



<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#a81f86d4f90d1b1e59de098544dc38763">anonymous{HexagonConstPropagation.cpp}::LatticeCell::add</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a9286d9966b9f76f339e39527de308291">constToInt</a>, <a href="#aac14920dc310e76994e10477d3a30ffb">evaluateORii</a>, <a href="#abd3a5d63ecde206c7feb8164c106ac07">getCell</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstpropagator/cellmap/#a70652f4c80c1f55b55c280a615f03d8f">anonymous{HexagonConstPropagation.cpp}::MachineConstPropagator::CellMap::has</a>, <a href="#a5c790b664ce2cce9da4e09c8dcf2f180">intToConst</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#a1ee72f5324a484622701610ac0d2615f">anonymous{HexagonConstPropagation.cpp}::LatticeCell::isBottom</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#aed4734b49f3e9c04536c619bf56003dc">anonymous{HexagonConstPropagation.cpp}::LatticeCell::isProperty</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg/#a70736188b24e0c19b8840c503758ab0c">anonymous{HexagonConstPropagation.cpp}::RegisterSubReg::Reg</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#afa5e1e7c3e449f788949809bb8cd134f">anonymous{HexagonConstPropagation.cpp}::LatticeCell::size</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#a5b017ee29c0481d436846d41d233b756">anonymous{HexagonConstPropagation.cpp}::LatticeCell::Values</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/hexagonconstevaluator/#ad86353e56a3963118b327c0f528a5004">anonymous{HexagonConstPropagation.cpp}::HexagonConstEvaluator::evaluate</a> and <a href="#a5c9526b09e12ac8a17ba2ab79aeff1c5">evaluateORrr</a>.</p>

</div>
</div>

### evaluateORrr() {#a5c9526b09e12ac8a17ba2ab79aeff1c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineConstEvaluator::evaluateORrr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg">RegisterSubReg</a> &amp; R1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg">RegisterSubReg</a> &amp; R2, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell">LatticeCell</a> &amp; Result)</td>
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



<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9286d9966b9f76f339e39527de308291">constToInt</a>, <a href="#a20f516d544c71d0983efc0d99bad30bc">evaluate</a>, <a href="#a7ab7f3071651b3a1f99deea3408edd6e">evaluateORri</a>, <a href="#a5c9526b09e12ac8a17ba2ab79aeff1c5">evaluateORrr</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstpropagator/cellmap/#ab24773faeaec92cc45cf756a7bf552cf">anonymous{HexagonConstPropagation.cpp}::MachineConstPropagator::CellMap::get</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstpropagator/cellmap/#a70652f4c80c1f55b55c280a615f03d8f">anonymous{HexagonConstPropagation.cpp}::MachineConstPropagator::CellMap::has</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#a1ee72f5324a484622701610ac0d2615f">anonymous{HexagonConstPropagation.cpp}::LatticeCell::isBottom</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#aed4734b49f3e9c04536c619bf56003dc">anonymous{HexagonConstPropagation.cpp}::LatticeCell::isProperty</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h/#a9211f62d8e1e6de999eaa63ec0f6ae02">R2</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg/#a70736188b24e0c19b8840c503758ab0c">anonymous{HexagonConstPropagation.cpp}::RegisterSubReg::Reg</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#afa5e1e7c3e449f788949809bb8cd134f">anonymous{HexagonConstPropagation.cpp}::LatticeCell::size</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#a5b017ee29c0481d436846d41d233b756">anonymous{HexagonConstPropagation.cpp}::LatticeCell::Values</a>.</p>


<p>Referenced by <a href="#a5c9526b09e12ac8a17ba2ab79aeff1c5">evaluateORrr</a>.</p>

</div>
</div>

### evaluateSEXTi() {#ab018e5f3273fdf77d6838c1bb037137a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineConstEvaluator::evaluateSEXTi (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; A1, unsigned Width, unsigned Bits, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Result)</td>
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



<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af2daa0ee117afefed4c82eee55bf97b7">llvm::APInt::getSExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aca8fce65eb69a82aa10a635e2e79877a">llvm::APInt::sext</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a317c64fd4cfebc88e79387b3821a629d">llvm::APInt::trunc</a>.</p>


<p>Referenced by <a href="#a1254219a658c0740a16c1461cbb81e49">evaluateSEXTr</a>.</p>

</div>
</div>

### evaluateSEXTr() {#a1254219a658c0740a16c1461cbb81e49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineConstEvaluator::evaluateSEXTr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg">RegisterSubReg</a> &amp; R1, unsigned Width, unsigned Bits, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell">LatticeCell</a> &amp; Result)</td>
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



<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a9286d9966b9f76f339e39527de308291">constToInt</a>, <a href="#ab018e5f3273fdf77d6838c1bb037137a">evaluateSEXTi</a>, <a href="#abd3a5d63ecde206c7feb8164c106ac07">getCell</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstpropagator/cellmap/#a70652f4c80c1f55b55c280a615f03d8f">anonymous{HexagonConstPropagation.cpp}::MachineConstPropagator::CellMap::has</a>, <a href="#a5c790b664ce2cce9da4e09c8dcf2f180">intToConst</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#a1ee72f5324a484622701610ac0d2615f">anonymous{HexagonConstPropagation.cpp}::LatticeCell::isBottom</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#aed4734b49f3e9c04536c619bf56003dc">anonymous{HexagonConstPropagation.cpp}::LatticeCell::isProperty</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg/#a70736188b24e0c19b8840c503758ab0c">anonymous{HexagonConstPropagation.cpp}::RegisterSubReg::Reg</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#afa5e1e7c3e449f788949809bb8cd134f">anonymous{HexagonConstPropagation.cpp}::LatticeCell::size</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#a5b017ee29c0481d436846d41d233b756">anonymous{HexagonConstPropagation.cpp}::LatticeCell::Values</a>.</p>

</div>
</div>

### evaluateSplati() {#a3c5315388a7981c96e7f006c78980966}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineConstEvaluator::evaluateSplati (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; A1, unsigned Bits, unsigned Count, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Result)</td>
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



<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a317c64fd4cfebc88e79387b3821a629d">llvm::APInt::trunc</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a1dc76cc8bf703e6ada68bededcbb9573">llvm::APInt::zext</a>.</p>


<p>Referenced by <a href="#a992c70a7697deaf90987fc37148fc211">evaluateSplatr</a>.</p>

</div>
</div>

### evaluateSplatr() {#a992c70a7697deaf90987fc37148fc211}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineConstEvaluator::evaluateSplatr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg">RegisterSubReg</a> &amp; R1, unsigned Bits, unsigned Count, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell">LatticeCell</a> &amp; Result)</td>
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



<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a9286d9966b9f76f339e39527de308291">constToInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="#a3c5315388a7981c96e7f006c78980966">evaluateSplati</a>, <a href="#abd3a5d63ecde206c7feb8164c106ac07">getCell</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstpropagator/cellmap/#a70652f4c80c1f55b55c280a615f03d8f">anonymous{HexagonConstPropagation.cpp}::MachineConstPropagator::CellMap::has</a>, <a href="#a5c790b664ce2cce9da4e09c8dcf2f180">intToConst</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#a1ee72f5324a484622701610ac0d2615f">anonymous{HexagonConstPropagation.cpp}::LatticeCell::isBottom</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#aed4734b49f3e9c04536c619bf56003dc">anonymous{HexagonConstPropagation.cpp}::LatticeCell::isProperty</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg/#a70736188b24e0c19b8840c503758ab0c">anonymous{HexagonConstPropagation.cpp}::RegisterSubReg::Reg</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#afa5e1e7c3e449f788949809bb8cd134f">anonymous{HexagonConstPropagation.cpp}::LatticeCell::size</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#a5b017ee29c0481d436846d41d233b756">anonymous{HexagonConstPropagation.cpp}::LatticeCell::Values</a>.</p>

</div>
</div>

### evaluateXORii() {#ad8ed36cbf2cad668c07842c44e26ae4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineConstEvaluator::evaluateXORii (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; A1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; A2, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Result)</td>
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



<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>Referenced by <a href="#a40b8bf88c0e4f03f5dfdcd1a34610530">evaluateXORri</a>.</p>

</div>
</div>

### evaluateXORri() {#a40b8bf88c0e4f03f5dfdcd1a34610530}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineConstEvaluator::evaluateXORri (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg">RegisterSubReg</a> &amp; R1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; A2, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell">LatticeCell</a> &amp; Result)</td>
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



<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a9286d9966b9f76f339e39527de308291">constToInt</a>, <a href="#ad8ed36cbf2cad668c07842c44e26ae4d">evaluateXORii</a>, <a href="#abd3a5d63ecde206c7feb8164c106ac07">getCell</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstpropagator/cellmap/#a70652f4c80c1f55b55c280a615f03d8f">anonymous{HexagonConstPropagation.cpp}::MachineConstPropagator::CellMap::has</a>, <a href="#a5c790b664ce2cce9da4e09c8dcf2f180">intToConst</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#aed4734b49f3e9c04536c619bf56003dc">anonymous{HexagonConstPropagation.cpp}::LatticeCell::isProperty</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#ab13878421737db422070f682fda17077">anonymous{HexagonConstPropagation.cpp}::LatticeCell::properties</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg/#a70736188b24e0c19b8840c503758ab0c">anonymous{HexagonConstPropagation.cpp}::RegisterSubReg::Reg</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#afa5e1e7c3e449f788949809bb8cd134f">anonymous{HexagonConstPropagation.cpp}::LatticeCell::size</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#a5b017ee29c0481d436846d41d233b756">anonymous{HexagonConstPropagation.cpp}::LatticeCell::Values</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/constantproperties/#af78a969bb965b0f4d2bdb79ce9baf20eaef919e157ce009f336138b8e817db61f">anonymous{HexagonConstPropagation.cpp}::ConstantProperties::Zero</a>.</p>


<p>Referenced by <a href="#a812ba4120e868c63ef47c07d4963ec29">evaluateXORrr</a>.</p>

</div>
</div>

### evaluateXORrr() {#a812ba4120e868c63ef47c07d4963ec29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineConstEvaluator::evaluateXORrr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg">RegisterSubReg</a> &amp; R1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg">RegisterSubReg</a> &amp; R2, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell">LatticeCell</a> &amp; Result)</td>
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



<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9286d9966b9f76f339e39527de308291">constToInt</a>, <a href="#a40b8bf88c0e4f03f5dfdcd1a34610530">evaluateXORri</a>, <a href="#abd3a5d63ecde206c7feb8164c106ac07">getCell</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstpropagator/cellmap/#a70652f4c80c1f55b55c280a615f03d8f">anonymous{HexagonConstPropagation.cpp}::MachineConstPropagator::CellMap::has</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#aed4734b49f3e9c04536c619bf56003dc">anonymous{HexagonConstPropagation.cpp}::LatticeCell::isProperty</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#ab13878421737db422070f682fda17077">anonymous{HexagonConstPropagation.cpp}::LatticeCell::properties</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h/#a9211f62d8e1e6de999eaa63ec0f6ae02">R2</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg/#a70736188b24e0c19b8840c503758ab0c">anonymous{HexagonConstPropagation.cpp}::RegisterSubReg::Reg</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#afa5e1e7c3e449f788949809bb8cd134f">anonymous{HexagonConstPropagation.cpp}::LatticeCell::size</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#a5b017ee29c0481d436846d41d233b756">anonymous{HexagonConstPropagation.cpp}::LatticeCell::Values</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/constantproperties/#af78a969bb965b0f4d2bdb79ce9baf20eaef919e157ce009f336138b8e817db61f">anonymous{HexagonConstPropagation.cpp}::ConstantProperties::Zero</a>.</p>

</div>
</div>

### evaluateZEXTi() {#a80a69d92372f6bfde4ea47c1b55b84bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineConstEvaluator::evaluateZEXTi (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; A1, unsigned Width, unsigned Bits, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Result)</td>
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



<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ad960e1ff48d25c382b6d28e7961f074e">llvm::APInt::getLowBitsSet</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a2ed912a28808268e35bd58e8f11251aa">llvm::APInt::zextOrTrunc</a>.</p>


<p>Referenced by <a href="#a9f45763d26a7cd4e3f11ebde35694017">evaluateZEXTr</a>.</p>

</div>
</div>

### evaluateZEXTr() {#a9f45763d26a7cd4e3f11ebde35694017}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineConstEvaluator::evaluateZEXTr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg">RegisterSubReg</a> &amp; R1, unsigned Width, unsigned Bits, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell">LatticeCell</a> &amp; Result)</td>
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



<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a9286d9966b9f76f339e39527de308291">constToInt</a>, <a href="#a80a69d92372f6bfde4ea47c1b55b84bb">evaluateZEXTi</a>, <a href="#abd3a5d63ecde206c7feb8164c106ac07">getCell</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstpropagator/cellmap/#a70652f4c80c1f55b55c280a615f03d8f">anonymous{HexagonConstPropagation.cpp}::MachineConstPropagator::CellMap::has</a>, <a href="#a5c790b664ce2cce9da4e09c8dcf2f180">intToConst</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#aed4734b49f3e9c04536c619bf56003dc">anonymous{HexagonConstPropagation.cpp}::LatticeCell::isProperty</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg/#a70736188b24e0c19b8840c503758ab0c">anonymous{HexagonConstPropagation.cpp}::RegisterSubReg::Reg</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#afa5e1e7c3e449f788949809bb8cd134f">anonymous{HexagonConstPropagation.cpp}::LatticeCell::size</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#a5b017ee29c0481d436846d41d233b756">anonymous{HexagonConstPropagation.cpp}::LatticeCell::Values</a>.</p>

</div>
</div>

### getCell() {#abd3a5d63ecde206c7feb8164c106ac07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineConstEvaluator::getCell (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg">RegisterSubReg</a> &amp; R, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2642f5609c60c3f7878b1b917e9875f4">CellMap</a> &amp; Inputs, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell">LatticeCell</a> &amp; RC)</td>
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



<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="#a20f516d544c71d0983efc0d99bad30bc">evaluate</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstpropagator/cellmap/#ab24773faeaec92cc45cf756a7bf552cf">anonymous{HexagonConstPropagation.cpp}::MachineConstPropagator::CellMap::get</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#a1ee72f5324a484622701610ac0d2615f">anonymous{HexagonConstPropagation.cpp}::LatticeCell::isBottom</a>.</p>


<p>Referenced by <a href="#a3e49cc0a8c1be83f39602a85c288835f">evaluateANDri</a>, <a href="#ac4917e6688b786a03dc01c382e1d9da3">evaluateCLBr</a>, <a href="#a46ce255d2c91bc39276b3abf153b1e58">evaluateCMPri</a>, <a href="#a069e11f50fb0348dacac4b0ad2715bbe">evaluateCMPrp</a>, <a href="#a3a175283278a754c84b75df5e20c5796">evaluateCMPrr</a>, <a href="#adf9bc561d4be2336b852a9dfa94a1ac8">evaluateCOPY</a>, <a href="#a2fb4263d9f6453677dfd6fc3e72ed999">evaluateCTBr</a>, <a href="#a342ccbdb8062b6646c20282b1367d686">evaluateEXTRACTr</a>, <a href="#a7ab7f3071651b3a1f99deea3408edd6e">evaluateORri</a>, <a href="#a1254219a658c0740a16c1461cbb81e49">evaluateSEXTr</a>, <a href="#a992c70a7697deaf90987fc37148fc211">evaluateSplatr</a>, <a href="#a40b8bf88c0e4f03f5dfdcd1a34610530">evaluateXORri</a>, <a href="#a812ba4120e868c63ef47c07d4963ec29">evaluateXORrr</a> and <a href="#a9f45763d26a7cd4e3f11ebde35694017">evaluateZEXTr</a>.</p>

</div>
</div>

### intToConst() {#a5c790b664ce2cce9da4e09c8dcf2f180}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ConstantInt * MachineConstEvaluator::intToConst (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Val)</td>
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



<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>Reference <a href="#a37c32e4b0b6cc910bfbbda5a20187396">CX</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/hexagonconstevaluator/#ad86353e56a3963118b327c0f528a5004">anonymous{HexagonConstPropagation.cpp}::HexagonConstEvaluator::evaluate</a>, <a href="#a3e49cc0a8c1be83f39602a85c288835f">evaluateANDri</a>, <a href="#ac4917e6688b786a03dc01c382e1d9da3">evaluateCLBr</a>, <a href="#a2fb4263d9f6453677dfd6fc3e72ed999">evaluateCTBr</a>, <a href="#a342ccbdb8062b6646c20282b1367d686">evaluateEXTRACTr</a>, <a href="#a7ab7f3071651b3a1f99deea3408edd6e">evaluateORri</a>, <a href="#a1254219a658c0740a16c1461cbb81e49">evaluateSEXTr</a>, <a href="#a992c70a7697deaf90987fc37148fc211">evaluateSplatr</a>, <a href="#a40b8bf88c0e4f03f5dfdcd1a34610530">evaluateXORri</a> and <a href="#a9f45763d26a7cd4e3f11ebde35694017">evaluateZEXTr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### TRI {#a175345dc12ffa8b0fc7e1af05a2b4e99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo&amp; anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>Referenced by <a href="#a261857237efac777a2276932250c0a54">MachineConstEvaluator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### CX {#a37c32e4b0b6cc910bfbbda5a20187396}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext&amp; anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::CX</td>
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



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/hexagonconstevaluator/#ad86353e56a3963118b327c0f528a5004">anonymous{HexagonConstPropagation.cpp}::HexagonConstEvaluator::evaluate</a>, <a href="#a5c790b664ce2cce9da4e09c8dcf2f180">intToConst</a> and <a href="#a261857237efac777a2276932250c0a54">MachineConstEvaluator</a>.</p>

</div>
</div>

### MF {#ac180992caa0708a693ae60f707a1af45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction&amp; anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::MF</td>
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



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>Referenced by <a href="#a261857237efac777a2276932250c0a54">MachineConstEvaluator</a>.</p>

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
